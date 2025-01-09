---
citekey: "{{citekey}}"
title: "{{title}}"
itemType: "{{itemType}}"
publicationTitle: "{{publicationTitle}}"
bookTitle: "{{bookTitle}}"
seriesTitle: "{{seriesTitle}}"
publisher: "{{publisher}}"
place: "{{place}}"
volume: "{{volume}}"
numberOfVolumes: "{{numberOfVolumes}}"
issue: "{{issue}}"
pages: "{{pages}}"
edition: "{{edition}}"
date: "{{date | format('YYYY-MM-DD')}}"
DOI: "{{DOI}}"
ISBN: "{{ISBN}}"
ISSN: "{{ISSN}}"
url: "{{url}}"
importance: 
status: incomplete
tags:
  - article
---

## {{title}}

### Table of Contents

- [Annotations](#annotations)
{% if notes.length > 0 %}
- [Notes](#notes)
{% endif %}
+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations

{% if annotations.length > 0 %}
{% set groupedAnnotations = annotations | groupby('page') %}
{% for page, annots in groupedAnnotations %}
#### Page {{page}}

{% for annotation in annots %}

{% if annotation.imageRelativePath %}
![{{annotation.imageFileName}}](<{{annotation.imageRelativePath}}>)
{% endif %}

{% if annotation.annotatedText %}
{% if annotation.colorCategory | lower == 'green' %}
{% set texts = annotation.annotatedText.split(',') %}
> {% for text in texts %}[[{{ text | trim | replace('/', '-') }}]]{% if not loop.last %}, {% endif %}{% endfor %}
{% else %}
> {{annotation.annotatedText}}
{% endif %}
{% else %}
> *(No annotated text)*
{% endif %}

{% if annotation.comment %}
**Comment**: {{annotation.comment}}
{% endif %}

- **Color**: {{annotation.color}} ({{annotation.colorCategory}})
- **Date**: {{annotation.date | format("YYYY-MM-DD h:mm a")}}

---

{% endfor %}
{% endfor %}
{% else %}
No annotations available.
{% endif %}

### Notes

{% if notes.length > 0 %}
{% for note in notes %}
{{note.note}}

---
{% endfor %}
{% else %}
No notes available.
{% endif %}

{% persist "notes" %}
{% if isFirstImport %}
<!-- Write your personal notes here -->
{% endif %}
{% endpersist %}

## Appendix

### Authors

{% for creator in creators %}
- [[{{creator.firstName}} {{creator.lastName}}]] ({{creator.creatorType}})
{% endfor %}

{% if abstractNote %}
### Abstract

{{abstractNote}}
{% endif %}

### Formatted Bibliography

{{bibliography}}

{% if tags.length > 0 %}
### Tags

{% for t in tags %}
- #{{ t.tag | replace(" ", "_") | lower }}
{% endfor %}
{% endif %}

{% if attachments.length > 0 %}
### Attachments

{% for attachment in attachments %}
- **{{attachment.title}}**: {{attachment.path}}
{% endfor %}
{% endif %}

{% if collections.length > 0 %}
### Collections

{% for collection in collections %}
- {{collection.name}}
{% endfor %}
{% endif %}

{% if relations.length > 0 %}
### Relations

{% for relation in relations %}
- {{relation}}
{% endfor %}
{% endif %}

### Backlinking

{% if publicationTitle or publisher or place or date or seriesTitle %}
#### Metadata Links

{% if publicationTitle %}
- publicationTitle: [[{{publicationTitle}}]]
{% endif %}
{% if publisher %}
- publisher: [[{{publisher}}]]
{% endif %}
{% if place %}
- place: [[{{place}}]]
{% endif %}
{% if date %}
- date: [[{{date | format('YYYY')}}]]
{% endif %}
{% if seriesTitle %}
- seriesTitle: [[{{seriesTitle}}]]
{% endif %}
{% endif %}

{% if isFirstImport %}
<!-- Any additional notes or comments -->
{% endif %}
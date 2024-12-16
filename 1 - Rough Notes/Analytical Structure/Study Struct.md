---
creation date: 2024-11-17 19:11
aliases: 
tags:
  - baby
modification date: Sunday, 17th November 2024, 19:11:33
id:
---
---

## Parent note
[[Source Data Folders]]---
## Backlinking


---
# Study Struct
The `study` struct is a structured representation of essential information about a specific study. It contains dataset metadata, directories' information, and equipment-specific information about the employed neuroscientific methods for data collection. This struct should be general enough to always be called for both preprocessing and analysing procedures.
## Fields

### `dataset_description`

- **Purpose**: Contains metadata about the dataset used in the study.
- **Fields**:
    - `short`: A short identifier or abbreviation for the dataset (e.g., `'exp2'`).

### `path`

- **Purpose**: Specifies file system paths relevant to the study, including scripts and analysis directories.
- **Fields**:
    - `scripts`: Path to the directory containing analysis scripts.
    - `analysis`: Name or identifier of the analysis being performed.
    - `specific`: Specific path to the analysis directory, often combining the scripts path and analysis name.

### `eeg`

- **Purpose**: Holds information related to EEG data, including channel groupings.
- **Fields**:
    - `channels`:
        - **Fields**:
            - `clusters`:
                - **Purpose**: Groups EEG channels into clusters based on anatomical regions or functional relevance.
                - **Fields**:
                    - `frontal`: A list of channels corresponding to the frontal region.
                    - `central`: Channels located over the central cortex.
                    - `temporal`: Channels over the temporal lobes.
                    - `parietal`: Channels covering the parietal region.
                    - `occipital`: Channels positioned over the occipital lobe.
                    - `midline`: Channels along the midline of the scalp.
                    - `global`: A grouping that may include all channels or be reserved for specific analyses.

---
# Notes

## Definition

## Associations

## Interpretation

---
## Links
- [Google Search](https://www.google.com/search?q=Study+Struct)

---
# Bibliography
+ 
>[!Experiments]+
> - # In-Progress
> 	  ```dataview
> 	  LIST FROM "1 - Rough Notes/Experiments" AND #experiment WHERE contains(status, "in progress")
> 	  SORT file.name
> 	  ```
> - # Done (Last 10)
>   ```dataview
>   LIST FROM "1 - Rough Notes/Experiments" AND #experiment 
>   WHERE contains(status, "done") OR contains(status, "failed")
>   LIMIT 10
> 	  ```

> [!To do]+
> - # Meetings
>   ```tasks
>   not done
>   heading includes To do
>   path does not include Meeting Template
>   path does not include Task Template
>   ```
>- # Various
> 	 ```tasks
> 	 not done
> 	 NOT(heading includes To do)
> 	 path does not include Daily Note Template
> 	 path does not include 2 - Source Material
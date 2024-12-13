<< [[<% fileDate = moment(tp.file.title, 'YYYY MM DD').subtract(1, 'd').format('YYYY MM DD') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY MM DD').add(1, 'd').format('YYYY MM DD') %>|Tomorrow]] >>


## Due Today 
```tasks
not done
due <% tp.file.title %>
sort by priority
hide due date
```

## Overdue
```tasks 
 not done 
 due before <% tp.file.title %>
 sort by priority
 hide due date
 ```

## Completed
```tasks
 done <% tp.file.title %>
 hide done date
 ```

## Calendar
![[Calendar View]]
## New Tasks
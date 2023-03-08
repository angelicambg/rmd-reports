# rmd-reports

- main.Rmd uses report_template_char.Rmd and report_template_numeric.Rmd to create one common pdf report. 
- main.Rmd uses a list `list_to_iterate` defined in the chunks to create a report for each element in the list. 
- one chunk should be used depending on the list; i.e. if it is numeric, character or factor. 
- main.Rmd contains two chunks with examples, but one chunk can be deleted depending on the user case.

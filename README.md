# sh-command-tinkering
## extract a ZIP file into a specific directory
```
unzip example.zip -d /path/to/destination/directory
```
## searches for a specific text within files and counts the number of files containing that text
```
grep -rl "search_text" . | wc -l
```
```
rg -l "search_text" . | wc -l
```

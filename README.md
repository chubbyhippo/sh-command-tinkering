# sh-command-tinkering
## compare all files and subdirectories within the specified directories
```shell
diff -r directory1 directory2
```
## extract a ZIP file into a specific directory
```shell
unzip example.zip -d /path/to/destination/directory
```
## searches for a specific text within files and counts the number of files containing that text
```shell
grep -rl "search_text" . | wc -l
```
```shell
rg -l "search_text" . | wc -l
```

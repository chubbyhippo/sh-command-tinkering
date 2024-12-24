# sh-command-tinkering
## compare all files and subdirectories within the specified directories
```sh
diff -r directory1 directory2
```
## extract a ZIP file into a specific directory
```sh
unzip example.zip -d /path/to/destination/directory
```
## searches for a specific text within files and counts the number of files containing that text
```sh
grep -rl "search_text" . | wc -l
```
```sh
rg -l "search_text" . | wc -l
```

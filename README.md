# Shell-Data-Processing Cheat Sheet
## Some useful powershell commands:

```powershell
cd // to navigate through directories.
ls // List all files in the given directory.
```
* shift + C : Copy
* Shift + V : Paste

## Some useful Bash commands

* shift + insert : Copy
* ctrl + insert : paste


<br>

## Command used to get data from a web page:
```powershell
curl "yourlongurl" -O 
```
### * Command used to get data from a web page with example:
```powershell
curl "https://dev.to/vinodsr/nestjs-a-backend-nodejs-framework-for-the-enterprise-40m6" -O 
```
### * Command used to get data from a web page and write in a text file:
```powershell
curl "https://dev.to/vinodsr/nestjs-a-backend-nodejs-framework-for-the-enterprise-40m6" -O "data.txt"
```
## The Command used to fing the most common words, sorted:
```Bash
tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr
```


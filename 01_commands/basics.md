# Terminal Basics
pwd              → current directory
ls               → list files/directories
ls -la           → list all files, including hidden files
cd <dir>         → change directory
cd ..            → parent directory
cd ~             → home directory

mkdir <dir>      → create directory
mkdir -p <path>  → create directory structure
touch <file>     → create file
cp <src> <dest>  → copy
mv <src> <dest>  → move / rename
rm <file>        → remove file
rm -r <dir>      → remove directory

cat <file>       → display file contents
head <file>      → first lines
tail <file>      → last lines
wc -l <file>     → count lines
find <path>      → find files/directories
grep <text>      → search text

which <command>  → command location
history          → command history
clear            → clear terminal

env              → environment variables
echo $VAR        → show variable value
export VAR=value → set environment variable

|                → pipe output
>                → write output to file
>>               → append output to file


## Common Data Engineering Examples
find . -name "*.csv"
grep "ERROR" application.log
wc -l data.csv
head data.csv
tail data.csv
ls -lah data/
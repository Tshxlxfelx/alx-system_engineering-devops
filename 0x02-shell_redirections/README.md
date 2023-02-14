echo - prints Hellow World
echo \ - prints special characters
cat - diplay content of a file
cat - display content of two files
tail - display the last 10 lines
head - display the first 10 lines
head -3 iacta | tail -1
echo - \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)
ls -la > ls_cwd_content - writes or overwrites an existing file
tail -1 iacta >> iacta - duplicates last file to a direcoctory
find  . -type f -name "*.js" -delete - deletes reqular files
find . -type d ! -path . | wc -z - counts directories and sub directories in the current folder
ls -t . | head - displays 10 new files in directory
sort | uniq -u - takes list of words as input and prints only words that appear only once
egrep "root" /etc/passwd - display lines containing the pattern "root" from the files /etc/passwd
egrep -C "bin" /etc/passwd - display the number of lines that contain the pattern "bin" in the file /etc/passwd
egrep -A 3 "root" /etc/passwd - display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd
egrep -V "bin" /etc/passwd - diplay all the lines in the file /etc/passwd that do not contain the pattern "bin"
megrep ^[[:alpha:]]
/etc/ssh/sshd_confiq - diplay all lines of the direcotry starting with a letter
tr 'Ac' 'Ze' - replace specific characters
tr -d cC - removes specified  characters
rev - reverse

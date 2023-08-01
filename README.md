
## Print a substring between a start and end keyword
sed -n '/[start keyword]/,/[end keyword]/p' [filename]

## Delete everything after a keyword in a file
sed -i '/keyword/q' file

## Delete everything before a keyword in a file
sed -i '1,/keyword/d' file

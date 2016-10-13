# exiv2-notes

# rename file, rewrite timestamp (-t) of file and number files (-F) with same timestamp 
find . -type f -exec exiv2 -t -F rename {} \;

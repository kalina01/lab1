```bash
tail -n 40 file1 > file2
head file2 > file3
grep коко file2 | sed s/коко/куку/g | head -n 3 >> file3
sort file3 | uniq -u > temp
cat temp > file3
rm -f temp
uniq -c file3
```

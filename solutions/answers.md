# solutions

```bash
pwd
ls
cd data
ls
cd ..
head -n 3 data/project.txt
grep -n TODO data/*.txt
grep TODO "data/meeting notes.txt"
grep TODO data/*.txt | wc -l
mkdir practice
cp starter/summary.txt practice/summary.txt
grep -n TODO practice/summary.txt > practice/report.txt
cat practice/report.txt
```

The `grep | wc -l` answer counts matching lines, not total occurrences of the word.

---
title: "Bash Shell Scavenger Hunt solutions"
teaching: 15
exercises: 0
questions:
- ""
objectives:
- "To force you to read and use some useful Bash commands."
- "To create oppotunities that would require Googling: you can't always know everything."
keypoints:
- “Push yourself to incorporate these practices into your daily workflow. Don't be afraid to fail; in fact do try to fail, early and often."
---

## Solutions
#### clue 3: Number of folders in /usr?
On the CINN Neurodebian vm, there are 10 folders in /usr

#### clue 4: content of /etc/hostname
neurodebian-gz005792-fMRI.act.rdg.ac.uk

#### clue 5: man mv, find parameter to prevent overwriting
Anything from that list: ["i","n","-i","-n"]

#### clue 6: first path listed in $PATH
/usr/local/sbin

#### clue 7: which python
/usr/bin/python

#### clue 8: name of the first folder listed in /sys/kernel/debug
Anything from that list: ["acpi", "denied"]

#### clue 9: wc /usr/share/dict/words
99171

#### clue 10: grep tactful /usr/share/dict/words
tactfully

#### clue 11: ls -la /usr | sort -k 5 -n -r
("-k 5 -n -r", "-k 5 -r -n", "-r -k 5 -n", "-r -n -k 5", "-n -r -k 5", "-n -k 5 -r")

#### clue 12: find all the clue files
find ./clues -name "clue" -printf "%s\t%p\n" | sort -nr | head -15

```
2186	./0251/clue
2090	./1234/clue
1687	./2751/clue
1620	./4220/clue
1286	./6767/clue
997	./2233/clue
894	./0870/clue
627	./8922/clue
587	./7365/clue
473	./2187/clue
200	./0298/clue
```


# Locating Restriction Sites

## [Rosalind Problem](https://rosalind.info/problems/revp/){:target="_blank"}

**Given**: A DNA string of length at most 1 kbp in FASTA format.

**Return**: The position and length of every reverse palindrome in the string having length between 4 and 12. You may return these pairs in any order.

### Sample Dataset

```
>Rosalind_24
TCAATGCATGCGGGTCTATATGCAT
```

### Sample Output

```
4 6
5 4
6 6
7 4
17 4
18 4
20 6
21 4
```

## Python Playground

{% include '13_revp.html' %}

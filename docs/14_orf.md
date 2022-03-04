# Open Reading Frames

## [Rosalind Problem](https://rosalind.info/problems/orf/){:target="_blank"}

**Given**: A DNA string $s$ of length at most 1 kbp in FASTA format.

**Return**: Every distinct candidate protein string that can be translated from ORFs of $s$. Strings can be returned in any order.

### Sample Dataset

```
>Rosalind_99
AGCCATGTAGCTAACTCAGGTTACATGGGGATGACCCCGCGACTTGGATTAGAGTCTCTTTTGGAATAAGCCTGAATGATCCGAGTAGCATCTCAG
```

### Sample Output

```
MLLGSFRLIPKETLIQVAGSSPCNLS
M
MGMTPRLGLESLLE
MTPRLGLESLLE
```
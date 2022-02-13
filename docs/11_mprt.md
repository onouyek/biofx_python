# Finding a Protein Motif

## [Rosalind Problem](https://rosalind.info/problems/mprt/){:target="_blank"}

**Given**: At most 15 UniProt Protein Database access IDs. 

**Return**: For each protein possessing the N-glycosylation motif (N{P}[ST]{P}), output its given access ID followed by a list of locations in the protein string where the motif can be found.

### Sample Dataset

```
A2Z669
B5ZC00
P07204_TRBM_HUMAN
P20840_SAG1_YEAST
```

### Sample Output

```
B5ZC00
85 118 142 306 395
P07204_TRBM_HUMAN
47 115 116 382 409
P20840_SAG1_YEAST
79 109 135 248 306 348 364 402 485 501 614
```

## Python Playground

{% include '11_mprt.html' %}

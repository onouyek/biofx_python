# Rabbits and Recurrence Relations

## [Rosalind Problem](https://rosalind.info/problems/fib/){:target="_blank"}

**Given**: 正の整数$n≤40$と$k≤5$

**Return**: 1ペアから始めて、各世代において繁殖年齢のペアのウサギが$k$ペアのウサギの子孫を残すとしたとき、$n$か月後に存在するウサギのペアの総数

![image](https://rosalind.info/media/problems/fib/rabbit_tree.png)

!!! info "Constraints"
    - 個体数は最初の月に生まれたばかりのウサギのペアが存在する時点からカウントする。
    - ウサギは1ヶ月後に生殖年齢に達するとする。
    - 生殖年齢のすべてのウサギは、生殖年齢の別のウサギと交尾する。
    - 2匹のウサギが交尾してからちょうど1か月後に、オス1匹とメス1匹のウサギが生まれる。
    - ウサギが死んだり、繁殖を停止したりすることは考慮しない。

### Sample Dataset

```
5 3
```

### Sample Output

```
19
```

## Python Playground

{% include '04_fib.html' %}

??? hint
    どの月にも、前月に生きていたウサギと新しい子孫が含まれます。すなわち、任意の月における子孫の数が2か月前に生きていたウサギの数に等しくなります。
    その結果、$F_n = F_{n-1} + F_{n-2}$ ($F_1 = F_2 = 1$)という漸化式によって定義されるフィボナッチ数列を得ることになります。 

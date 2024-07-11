## Analytical structure of QCD

Vladi Skokov

North Carolina state University

---

### Yang-Lee edge singularity

<div class="r-stack">

<img class="fragment fade-out" data-fragment-index="0"   src="img/fg.png" >
<img class="fragment fade-in"  data-fragment-index="0"  src="img/fg3d.png">

</div>

--

### Illustration in Ising model

<img src="img/IsingYLE.png"  width=550em>

<div class="cite">
F. Rennecke, G. Johnson, and V.S.,     Phys.Rev.D 107 (2023) 11, 116013
</div>

- In contrast to the critical point, YLE form lines
- YLE are continuously connected to critical point

---

### Results: importance of fluctuations ($N$=1)

<img src="img/etaevo.png" width=65% >

<div class="cite">
F. Rennecke and V. S, Annals Phys. 444 (2022) 169010

</div>

---

### Results: Ising universality class $N=1$

$d$ does not have to be integer in FRG

<img src="img/FRG_8_4.png" width=45% >

| d                                | 1   | 2          | 3        | 4           |
| -------------------------------- | --- | ---------- | -------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma}$ | 1   | 1.32504(2) | 1.621(4) | $3/2^{2/3}$ |

<div class="cite">
G. Johnson, F. Rennecke, and V. S, Phys.Rev.D 107 (2023) 11,
116013 <br>
F. Rennecke and V. S, Annals Phys. 444 (2022) 169010 <br>
A. Connelly, G. Johnson, F. Rennecke, and V. S, Phys.Rev.Lett. 125 19, 191602
(2020) <br>
$d=2$: H.-L. Xu and A. Zamolodchikov, JHEP 08 (2022) 057 H.-L. Xu and A.
Zamolodchikov, 2304.07886

</div>

---

### Arbitrary $N$, $d=3$

<img src="img/zeta.png" width=45% >

| N                                | 1           | 2           | 3           | 4           | 5            |
| -------------------------------- | ----------- | ----------- | ----------- | ----------- | ------------ |
| $ \| z_c \| /R\_\chi^{1/\gamma}$ | 1.621(4)(1) | 1.612(9)(0) | 1.604(7)(0) | 1.597(3)(0) | 1.5925(2)(1) |

<div class="cite">
G. Johnson, F. Rennecke, and V. S, Phys.Rev.D 107 (2023) 11,
116013 <br>
c.f. F. Karsch, C. Schmidt, and S. Singh Phys.Rev.D 109 (2024) 1, 014508

</div>

---

### Tracing YLE in QCD

<img src="img/RW_YLE.png" height=350em >

$$
  z = z_c \to \text{Re} \mu_{YLE} \propto (T_{RM}-T)^{\beta \delta}
$$

<div class="cite">
Christian Schmidt, et. al., 2401.07790
</div>

---

### Tracing YLE in QCD

<div class="smallmath">
Indirect methods to locate YLE was used: input from Im $\mu$ or Taylor series
expansion coefficients of $\ln Z$ at zero $\mu$
</div>

<div class="r-stack">

<div class="fragment fade-out"  data-fragment-index="1"  >
<img src="img/BasarYLE.png" height=350em >
<img src="img/LatticeYLElocation.png" height=350em >
<div class="cite">
G. Basar, 2312.06952 <br>
D. Clarke et. al., 2405.10196
</div>
</div>

<img class="fragment current-visible" data-fragment-index="1" src="img/LatticeQCDPD.png" height=350em >

<div class="cite">
C. Schmidt, CPOD 2024
</div>

</div>

---

### Conformal map

<img src="img/Euler.png" height=350em >

---

### Fourier coefficients

<img src="img/FTfits.png" height=350em >

---

### Conclusions

- Analytic structure of QCD partition function:

  - extrapolate results obtained at zero or imaginary chemical potential to real values of $\mu$

  - locate critical point

- Study of analytic structure is a hard problem

  - as an illustration of this: universal location of YLE singularity was established only recently in 2-d and 3-d systems

  - we are only scratching the surface of the research in this direction

- There are very encouraging results on location of QCD CP coming from analysis of Lattice data

  - two existing studies use different lattice inputs (Taylor series coefficients, imaginary $\mu$ data) but produce similar estimates on the location of CP

  - to-do list: continuum limit, calculations at lower temperatures, ...

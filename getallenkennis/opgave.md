### Controle uit van volgende hamming bits 1110110 
##### Bespreek of deze reeks correct is en bepaal, indien er een fout optreedt, welke bit verkeerd is.


| 1  |  1 |  1 |  0 | 1  |  1 |  0 |
| ---------------------------------|
| H1 | H2 | D3 | H4 | D5 | D6 | D7 |



**P1** = 1 1 1 0 = 1

**P2** = 11 10 = 1

**P4** = 0110 = 0


P1 en P2 zijn niet 0 wat wil zeggen dat er een fout in de code zit.

=> Er zit een `fout` in bit `3`, want de dom van p**1** en p**2** is **3**

De juiste reeks hamming bits is :
`1100110`
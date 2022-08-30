# TinyCORDIC

A 6 bit CORDIC for calculating sin() and cos() functions implemented in verilog for [tinytapeout](https://mailchi.mp/574276e3c9d7/tinytapeout).

Herer are some sample calculations:
| Calculated by tinycordic | actual answer |
| ---- | ---- |
| 0.97 | 0.99 |
| 0.16 | 0.1  |
| 0.68 | 0.68 |
| 0.74 | 0.73 |
| 0.42 | 0.34 |
| 0.9  | 0.94 |
| 0.61 | 0.59 |
| 0.81 | 0.81 |
| 0.23 | 0.28 |
| 0.97 | 0.96 |



Check out the main repo for tests and the 4bit version:
https://github.com/sfmth/tinycordic

- [@Hansem](https://github.com/hansemro) helped with further optimization of the code to make it fit inside 100x100um

### Final GDS for tinytapeout

![multi_macro](https://user-images.githubusercontent.com/23662796/187537880-dde4d504-a0f9-46ad-8423-f5b49b4ca320.png)

# TinyCORDIC

A 6 bit CORDIC for calculating sin() and cos() functions implemented in verilog for [tinytapeout](https://mailchi.mp/574276e3c9d7/tinytapeout).

### Here are some sample calculations:
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

### Check out the simulation waveforms:
![unknown-4](https://user-images.githubusercontent.com/23662796/188503449-fa1b5c26-fd9d-4ccb-9dbf-68c9742cc618.png)

### Check out the main repo for tests and the 4bit version:
https://github.com/sfmth/tinycordic

## Notes
- :heavy_check_mark: Selected as a featured project for the first tinytapeout submission
- :heavy_check_mark: [@Hansem](https://github.com/hansemro) helped with further optimization of the code to make it fit inside 100x100um

## Final GDS for tinytapeout
This design:
![multi_macro](https://user-images.githubusercontent.com/23662796/187537880-dde4d504-a0f9-46ad-8423-f5b49b4ca320.png)

The entire submission:
![20220904_153238](https://user-images.githubusercontent.com/23662796/188503541-62e00fa6-4923-4b8d-ad74-f07c8ceb189b.jpg)




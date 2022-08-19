# Basic Data Generator

Just a very basic data generator for generating datasets for regression tasks. 

Datasets can be exported as `.csv` into `data` directory.

Dependencies for creating own derivatives of the datasets and to run the notebook are saved in `bgd.yml`

## Data
There are three different datasests with three degrees of complexity. 

### A square function based on a single sin function with five frequencies: 

A square function based on a simple sinus function is derived and sampled for 50.000 steps.

<img src="./figures/squ_sin.png" alt="simple square" width="1000"/>

Five of the square functions with varying frequencies are appended to the dataset `sin_squ.csv`.

<img src="./figures/squ_5sin.png" alt="simple square" width="1000"/>


---

### A pulse-width modulated square function based on sin function: 

A pulse width modulated square function based on a simple sinus function is derived and sampled for 50.000 steps.
The parameter `a` influences the modulation.

<img src="./figures/pwm_sin.png" alt="pwm sin" width="1000"/>

Five different frequencies are appended into the dataset `sin_pwm.csv`.

<img src="./figures/pwm_5sin.png" alt="pwm sin" width="1000"/>

---

### A pulse-width modulated function based on sin and tan function: 

A pulse width modulated square function based on a simple sinus and tangens function is derived and sampled for 50.000 steps.
The parameters `a` and `b` influence the modulation.

<img src="./figures/pwm_sin_tan.png" alt="pwm sin tan" width="1000"/>

Five different frequencies are appended into the dataset `sin_tan_pwm.csv`.

<img src="./figures/pwm_5sin_5tan.png" alt="pwm sin tan" width="1000"/>



---
## LICENSE
Licensed under the Apache License, Version 2.0 (the "License"); you may not use it except in compliance with the License. A copy of the License is included in the project, see the file LICENSE.

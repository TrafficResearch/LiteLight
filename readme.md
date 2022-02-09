## Introduction

Official Code for article: **Less is more: Less observation and lightweight reinforcement learning method for traffic signal control**.

### Quick start

For the method in our article:
- PTS-CoLight
```shell
python run_pts_colight.py
```
-PTS-FRAP
```shell
python run_pts_frap.py
```
-LiteLight
```shell
python run_litelight.py
```

For the baseline methods,
- Fixed-Time
```shell
python run_fixedtime.py
```
- Max-Pressure
```shell
python run_maxpressure.py
```
- FRAP
```shell
python run_frap.py
```
- MPLight
```shell
python run_mplight.py
```
- CoLight
```shell
python run_colight.py
```
- Efficient-MPLight
```shell
python run_efficient_mplight.py
```
- Efficient-CoLight
```shell
python run_efficient_colight.py
```

## Rquirements
`tensorflow=2.4`  `cityflow` `python=3.6`

## Code explaination
### structure
- `models`: contains all the models used in our article.
- `utils`: contains all the methods to simulate and train the network.

If you use our method, please cite our article.

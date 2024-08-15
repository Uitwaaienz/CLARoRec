
### Requirements
  * `pip install recbole`
  * `pip install causal-conv1d>=1.4.0`
  * `pip install mamba-ssm`
Our experimental platform is equipped with an NVIDIA V100 GPU, Ubuntu 22.04, PyTorch 2.1.2, and CUDA 12.1.
You can also refer to the required environment specifications in 
### Run CLARoRec

```python run_recbole.py --model=CLARoRec --dataset=ml-1m  --config_files=ml.yaml```
```python run_recbole.py --model=CLARoRec --dataset=amazon-musical-instruments  --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec --dataset=amazon-health-personal-care  --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec --dataset=amazon-electronics --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec --dataset=amazon-office-products --config_files=amazon.yaml```

### Run CLARoRec*

```python run_recbole.py --model=CLARoRec1 --dataset=ml-1m  --config_files=ml.yaml```
```python run_recbole.py --model=CLARoRec1 --dataset=amazon-musical-instruments  --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec1 --dataset=amazon-health-personal-care  --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec1 --dataset=amazon-electronics --config_files=amazon.yaml```
```python run_recbole.py --model=CLARoRec1 --dataset=amazon-office-products --config_files=amazon.yaml```

### Comparative experiment

```python run_recbole.py --model=SASRec --dataset=amazon-office-products  --config_files=ml.yaml```
```python run_recbole.py --model=SASRec --dataset=amazon-musical-instruments  --config_files=amazon.yaml```
```python run_recbole.py --model=SASRec --dataset=amazon-health-personal-care  --config_files=amazon.yaml```
```python run_recbole.py --model=SASRec --dataset=amazon-electronics --config_files=amazon.yaml```
```python run_recbole.py --model=SASRec --dataset=amazon-office-products --config_files=amazon.yaml```



## Acknowledgment

This project is based on [RecBole](https://github.com/RUCAIBox/RecBole). Thanks for their excellent works.

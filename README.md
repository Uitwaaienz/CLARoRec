
### Requirements
  * `pip install recbole`

Our experimental platform is equipped with an NVIDIA V100 GPU, Ubuntu 22.04, PyTorch 2.1.2, and CUDA 12.1.

You can also refer to the required environment specifications in requirements.txt

The first run will download the dataset resources. Once the download is complete, please run it again.
### Run CLARoRec

```python run_recbole.py --model=CLARoRec --dataset=ml-1m  --config_files=ml.yaml```

```python run_recbole.py --model=CLARoRec --dataset=amazon-baby --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec --dataset=amazon-sports-outdoors  --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec --dataset=amazon-tools-home-improvement --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec --dataset=amazon-musical-instruments  --config_files=amazon.yaml```


### Run CLARoRec*

```python run_recbole.py --model=CLARoRec1 --dataset=ml-1m  --config_files=ml.yaml```

```python run_recbole.py --model=CLARoRec1 --dataset=amazon-baby --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec1 --dataset=amazon-sports-outdoors  --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec1 --dataset=amazon-tools-home-improvement --config_files=amazon.yaml```

```python run_recbole.py --model=CLARoRec1 --dataset=amazon-musical-instruments --config_files=amazon.yaml```


## Acknowledgment

This project is based on [RecBole](https://github.com/RUCAIBox/RecBole). Thanks for their excellent works.

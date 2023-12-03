# single_cell_pb
Kaggle's Open Problems – Single-Cell Perturbations competition. 

### Setup 
cuda version - cu121
python 3.8
```bash
pip install -r  requirements.py
```


To train the models modify config_train.yaml and run:

```bash
python train_run.py --config config_train.yaml
```


To run the models modify config_test.yaml and run:

```bash
python predict.py --config config_test.yaml
```
### Hardware
nvidia rtx 3080 mobile, windows 11


## Sources
1. [Single Cell Perturbations Kaggle 2nd place solution](https://www.kaggle.com/competitions/open-problems-single-cell-perturbations/discussion/458738)
2. [Lion PyTorch by lucidrains](https://github.com/lucidrains/lion-pytorch)
3. [Understanding the Competition - Open Problems](https://www.kaggle.com/code/ayushs9020/understanding-the-competition-open-problems)
4. [OP2 EDA Baseline by alexandervc](https://www.kaggle.com/code/alexandervc/op2-eda-baseline-s)


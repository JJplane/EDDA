# EDDA
This is the source code of EDDA in CIKM'23. 

__Paper__: Multi-domain Recommendation with Embedding Disentangling and Domain Alignment (CIKM'23)


### Environment Setup

```
torch~=1.9.0+cu111
dgl-cu111~=0.7.1
numpy~=1.22.2
scipy~=1.7.1
tqdm~=4.62.3
```
```
conda create -n EDDA python=3.9
source activate EDDA
<!-- pip install -r requirements.txt -->
conda install pytorch==2.0.0 torchvision==0.15.0 torchaudio==2.0.0 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install dgl-cu111
pip install scipy==1.7.1
pip install tqdm
pip install scikit-learn
```

### Guideline to run code
To run our EDDA
```
python run_edda.py --dataset AliCCP --tasks d0 d1 d2
```

### Acknowledgements

Part of our codes in `LibMTL/` folder are from [LibMTL](https://github.com/median-research-group/LibMTL).

If you use our datasets or codes, please cite our paper.
```
@inproceedings{EDDA,
    author = {Ning, Wentao and Yan, Xiao and Liu, Weiwen and Cheng, Reynold and Zhang, Rui and Tang, Bo},
    title = {Multi-domain Recommendation with Embedding Disentangling and Domain Alignment},
    booktitle = {CIKM},
    publisher = {ACM},
    year = {2023}
}
```

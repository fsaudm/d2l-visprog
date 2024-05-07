# d2l-visprog
Notebooks per chapter of the D2L book (https://d2l.ai/index.html).



To run these notebooks, I recommend you to **create a venv/conda environment** (as suggested by the authors on the D2l book):

```
conda create --name d2l python=3.9 -y
conda activate d2l
```

These notebooks follow the **PyTorch** implementation, so you would also need to **install the required libraries**:

```
pip install torch==2.0.0 torchvision==0.15.1
pip install d2l==1.0.3
```

If you prefer to use other Deep Learning frameworks, the authors also prepared notes on how to use Tensorflow, JAX, MXNET. 
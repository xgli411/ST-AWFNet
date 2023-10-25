

# ST-AWFNet

## Install
```
pip install -r requirement.txt
echo $CUDA_HOME
cd assets/ops/dcn/
python setup.py build_ext --inplace
```
## Training

```python train.py path-to-yaml-file ```

## Datasets
The root of the dataset directory can be ```ST-AWFNet/datasets/```.

## Testing
```
python eval.py path-to-yaml-directory --resume path-to-model-directory 
```




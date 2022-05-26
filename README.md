### Set up
```python
conda create -n jointdiff python=3.7
conda activate jointdiff
pip install pip==21.0.1
pip install -r requirements.txt
pip install torch==1.10.0+cpu torchvision==0.11.0+cpu torchaudio==0.10.0 -f https://download.pytorch.org/whl/torch_stable.html
```


### Run the examples
```python
python AttControl.py
```

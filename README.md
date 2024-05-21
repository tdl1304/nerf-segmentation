# nerf-segmentation
Run segmentation on an existing nerfstudio data formatted folder

# how-to-run
```pip install -r ./seg/requirements.txt```

```python -m seg.process {folder/to/data}```

Change accordingly to segment out different transient objects
```
FILTER = ["person"]
#FILTER = ["car"]
#FILTER = ['car', 'truck', 'bus', 'train', 'motorcycle', 'bicycle', 'person', 'rider']
```

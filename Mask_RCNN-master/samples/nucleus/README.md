## How to train or test?
Train (weight = imagenet / coco / last)
```
python nucleus.py train --dataset=dataset --subset=train --weights=imagenet
```

Test on stage2_test dataset
```
python nucleus.py detect --dataset=dataset --subset=stage2_test --weights=<last or /path/to/weights.h5>
```

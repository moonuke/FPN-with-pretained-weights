# FPN-with-pretained-weights

The code referred to here(https://github.com/kuangliu/pytorch-fpn/blob/master/fpn.py) 

The mainly difference is the code can utilize the pretrained weights such as reset50,101, and so on.
The Resenet models are same as the offical models only without line 147-150.

```python
        # x = self.avgpool(x)
        # x = x.view(x.size(0), -1)
        # x = self.fc(x)
```

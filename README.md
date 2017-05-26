# SqueezeNet

squeezeNet is a much smaller convolutional network, with vastly less amount of parameters.
queezeNet achieves AlexNet-level accuracy on ImageNet with 50x fewer parameters. 
Additionally, with model compression techniques SqueezeNet can be compress to less than 0.5MB (510x smaller than AlexNet).

# To use SqueezeNet
Do `pip install squeezenet`

```python
from squeezenet import squeezenet

# th -> (channel, width, height)
# tf -> (width, height, channel)

model = squeezenet(input)
# returns the computed tensor
```

# TODO
 - Compression
 - Performance


# References
 - [SqueezeNet Official Github Repo](https://github.com/DeepScale/SqueezeNet)
 - [SqueezeNet Paper](http://arxiv.org/abs/1602.07360)

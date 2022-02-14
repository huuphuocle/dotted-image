# Dotted-image

This is a Python implementation of some algorithms for stippling images.
We use several algorithms for Poisson disk samplings (`poisson.py`) and also implement a method of optimization over a space of measures (`measure.py`).

This is done in a small project with [Ho Thi Minh Ha](https://github.com/tmhho).

To use this script, call 

`./dotted-image [input] [output]` 

where

* `[input]` is the path to the input image 
* `[output]` is the path for the output image

By default, Poisson disk sampling algorithms are used (which produce the output faster).
But the optimization method is very interesting mathematically. ;)

## Example

The command

`./dotted-image ../img/walle.png ../img_out/walle_dotted.png`

will create the following result

<img src="https://github.com/huuphuocle/dotted-image/blob/main/img/walle.png" alt="Input image" width="300"/> <img src="https://github.com/huuphuocle/dotted-image/blob/main/img_out/walle_dotted.png" alt="Output image" width="300"/>

## 

## References

[Fast Poisson Disk Sampling in Arbitrary Dimensions](https://www.cs.ubc.ca/~rbridson/docs/bridson-siggraph07-poissondisk.pdf)
[Poisson Disk Sampling](http://devmag.org.za/2009/05/03/poisson-disk-sampling/)

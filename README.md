# Dotted-image

This is a Python implementation of some algorithms for Poisson disk samplings.

To use this script, call 

`./dotted-image [input] [output]` 

where

* `[input]` is the path to the input image 
* `[output]` is the path for the output image

## Example

The command

`./dotted-image ../img/walle.png ../img_out/walle_dotted.png`

will create the following result

<img src="https://github.com/huuphuocle/dotted-image/blob/main/img/walle.png" alt="Input image" width="400"/> <img src="https://github.com/huuphuocle/dotted-image/blob/main/img_out/walle_dotted.png" alt="Output image" width="400"/>

## References

[Fast Poisson Disk Sampling in Arbitrary Dimensions](https://www.cs.ubc.ca/~rbridson/docs/bridson-siggraph07-poissondisk.pdf)
[Poisson Disk Sampling](http://devmag.org.za/2009/05/03/poisson-disk-sampling/)

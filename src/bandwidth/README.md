# Bandwidth: a memory bandwidth benchmark

Distributed under the terms of the [GNU GPL v2](https://raw.githubusercontent.com/X0rg/CPU-X/master/src/bandwidth/COPYING.txt).


### CPU-X NOTE

This sofware has been patched to be used within CPU-X.  
You can find the official web page of this project here: https://zsmith.co/bandwidth.html  
This is based on bandwidth 1.1.

This software is used to retrieve following data:
* Caches tab
  * L1 cache speed
  * L2 cache speed
  * L3 cache speed

You can reproduce the output of `bandwidth` command by using `cpu-x --bandwidth`.  
It will produce a graph named `bandwidth.bmp` in the current working directory.

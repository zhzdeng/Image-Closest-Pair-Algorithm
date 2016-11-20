# Image-Closest-Pair-Algorithm
A random algorithm to find the cloest pair in a set of Image (handwritten digits)

+ **Ubuntu 16.04**  and  g++ **5.4.0**
+ This link to **download** Dataset: [Link](http://yann.lecun.com/exdb/mnist/)

### Usage

+ Extract all **images** from the dataset

    `make helper`<br>
    `./bin/datasetHelper`<br>
    Images will store in `data/images/*.txt`

+ add standard Normal distribution N(0,1) class
  `#include "util/RandNum.h"`<br>
  `CLCRandNum rand;`<br>
  `rand.SetSeed(0); // get seed by clock`<br>
  `rand.Normal(s, length); // s is double Array, length is s.length()`<br>

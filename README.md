# BSR Benchmark for BSDS 500

This is not official repository! get the real one from [here](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html)


This repo is meant to compile correspondPixels.cpp used for [Edge toolbox in Octave](https://github.com/ardiya/pdollar_edges_octave)

## Usage
```
mkoctfile --mex -DMATLAB_MEX_FILE -o benchmarks/correspondPixels.mex -Isource $(ls source/* | grep .cc)
```

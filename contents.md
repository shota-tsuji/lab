## An Effective Approach for Implementing Sparse Matrix-Vector Multiplication on Graphics Processing Units[2012]
### contents
- BTJADは，highly uniform matrixとhighly non-uniform matrix以外に，高い性能
- BTJADはレジスタまで使って，データ再利用(そうすると性能上がるらしい)

future workは
- auto-tuner to chose optimal storage format&kernel
- more precise BTJADがbest perfomanceになる特徴


## Auto-Tuning CUDA Parameters for Sparse Matrix-Vector Multiplication on GPUs[2010]
### contents
パラメータを調整
- NUM_THREADS & BLOCK_SIZE & WARP_SIZE
- NVIDIAのものと比較して，大幅に上がった(MAXで278%とか)


future workは
- overlapping the execution of CPU and GPUとか最適化したい
- auto-tuning frameworkをhandle other CUDA kernelsにも適用・拡大したい

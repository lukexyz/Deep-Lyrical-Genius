# Lyrical-Genius
BERT Transformer NLP models on Top 40 lyrics database.


### Install Notes

##### `Pytorch`  
* Get CUDA version from `nvcc --version` on windows, or `$ nvidia-smi` on unix.  

For conda on windows and Cuda 9, use pytorch instructions on [https://pytorch.org/](https://pytorch.org/), pip install probably works fine on unix.  

```> conda install pytorch torchvision cudatoolkit=9.2 -c pytorch```



##### `spacy-transformers`
For GPU installation, find your CUDA version add the version in brackets, e.g. spacy-transformers[cuda92] for CUDA9.2 or spacy-transformers[cuda100] for CUDA10.0.   
[spacy-transformers](https://github.com/explosion/spacy-transformers#-quickstart)

```> pip install spacy-transformers[cuda92]```







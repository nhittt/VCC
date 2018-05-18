Vietnamese manual compression dataset from [*Improving Vietnamese Sentence Compression by Segmenting Meaning Chunks*](https://ieeexplore.ieee.org/abstract/document/7371804/)

Please add citation below when using this dataset:

```
@inproceedings{tran2015improving,
  title={Improving vietnamese sentence compression by segmenting meaning chunks},
  author={Tran, Nhi-Thao and Ung, Van-Giau and Luong, An-Vinh and Nghiem, Minh-Quoc and Nguyen, Ngan Luu-Thuy},
  booktitle={Knowledge and Systems Engineering (KSE), 2015 Seventh International Conference on},
  pages={320--323},
  year={2015},
  organization={IEEE}
}
```

The Vietnamese manual compressed dataset is created by using 30 clusters of "Written Vietnamese Cluster Corpus for Document Summarization" of Tran Mai Vu Group, VNU Hanoi University of Engineering and Technology. 

Three annotators were asked to perform three compressed versions.
The data was organized as XML standard with the source sentence followed by three human-compressed versions:
```
	<original> source sentence </original>
	<compressed_human_1> compressed version by human 1 </compressed_human_1>
	<compressed_human_2> compressed version by human 2 </compressed_human_2>
	<compressed_human_3> compressed version by human 3 </compressed_human_3>
```
The compression rate of this manually dataset which refers to the percentage of words retained from the source sentence in the compression is about 67.94%

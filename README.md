# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Team 8
+ Team members
	+ Xia, Tianyi (Presenter)
	+ An, Qu Fei
	+ Guo, Yicheng
	+ Lin, Hongxu
	+ Auld-Griffith, Nicolette

### Project Summary

In this project, we utilized a CNN model to address the noisy label dataset. While achieving 0.48 accuracy on the clean label dataset, we explored several noise reduction methods including Global Average Pooling (GAP), Robust Loss, and Noise Layer.

Following experimentation with these techniques, we found that the GAP method yielded the most promising results in noise reduction. Leveraging GAP, our model attained 0.44 accuracy on the noisy label dataset, closely resembling the performance on the clean label dataset. Consequently, we identify GAP as an effective noise reduction approach, enhancing model performance on noisy datasets and offering a viable solution to similar challenges.
	
**Contribution statement**: 
+ Xia, Tianyi (Presenter):
+ An, Qu Fei
+ Guo, Yicheng
+ Lin, Hongxu is responsible for three models in model2 part. 
+ Auld-Griffith, Nicolette

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

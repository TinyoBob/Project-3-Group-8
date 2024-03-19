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
+ Xia, Tianyi (Presenter) contributed to the team by completing the coding and debugging for Model 1, tuning and adjusting parameters for Model 2 which is created by Hongxu and Nicolette, plotting and outputting test set results, and organizing the PowerPoint presentation which is created by Qu Fei and Yicheng, as well as delivering the speech.
+ An, Qu Fei
+ Guo, Yicheng
+ Lin, Hongxu is responsible for three models in model2 part. 
+ Auld-Griffith, Nicolette organized group meetings for Group 8 and coded Model 2 GAP part based on Model 1, created by Tianyi Xia. After researching the best methods of weakly supervised learning for CNNs, Nicolette decided a global average pooling would help in image classification and based Model 2 on this method. 

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

## Evaluation on salient object detection(Evaluate SOD)

A PYTHON implementation of popular SOD metrics including MAE, F-measure, S-measure, E-measure and weighted F-measure
---
A fast evaluation on salient object detection with GPU implementation including **MAE, Max F-measure, S-measure, E-measure**.

Note that the totally black ground truths are considered in E-measure, weighted F-measure and S-measure; excluded in F-measure (which is consistent with the Matlab code from https://github.com/wenguanwang/SODsurvey).

* GPU implementation with pytorch which can be easier embedding into eval code.


If you find the code useful to your research, please cite the following papers.
```
@inproceedings{fan2017structure,
	title={{Structure-measure: A New Way to Evaluate Foreground Maps}},
	author={Fan, Deng-Ping and Cheng, Ming-Ming and Liu, Yun and Li, Tao and Borji, Ali},
	booktitle={IEEE International Conference on Computer Vision (ICCV)},
	pages = {4548-4557},
	year={2017},
	note={\url{http://dpfan.net/smeasure/}},
	organization={IEEE}
}

@inproceedings{Fan2018Enhanced,
	author={Fan, Deng-Ping and Gong, Cheng and Cao, Yang and Ren, Bo and Cheng, Ming-Ming and Borji, Ali},
	title={{Enhanced-alignment Measure for Binary Foreground Map Evaluation}},
	booktitle={International Joint Conference on Artificial Intelligence (IJCAI)},
	pages={698--704},
	note={\url{http://dpfan.net/e-measure/}},
	year={2018}
}

@article{zhang2020iSOD,
  title={A Fixation-based 360 $\{$$\backslash$deg$\}$ Benchmark Dataset for Salient Object Detection},
  author={Zhang, Yi and Zhang, Lu and Hamidouche, Wassim and Deforges, Olivier},
  journal={arXiv preprint arXiv:2001.07960},
  year={2020}
}
```

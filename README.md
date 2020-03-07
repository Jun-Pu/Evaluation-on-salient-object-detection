## Evaluation on salient object detection(Evaluate SOD)

A PYTHON implementation of popular SOD metrics including MAE, F-measure, S-measure, E-measure and weighted F-measure
---
A fast evaluation on salient object detection with GPU implementation including **MAE, Max F-measure, S-measure, E-measure**.

Code are reimplemented from the matlab version which are available from http://dpfan.net/, modified from https://github.com/Hanqer/Evaluate-SOD.

Note that the totally black ground truths are considered in E-measure, weighted F-measure and S-measure; excluded in F-measure (which is consistent with the Matlab code from https://github.com/wenguanwang/SODsurvey).

* GPU implementation with pytorch which can be easier embedding into eval code.


If you find the code useful to your research, please cite the following papers.
```
@inproceedings{fan2018SOC,
	title={Salient Objects in Clutter: Bringing Salient Object Detection to the Foreground},
	author={Fan, Deng-Ping and Cheng, Ming-Ming and Liu, Jiang-Jiang and Gao, Shang-Hua and Hou, Qibin and Borji, Ali},
	booktitle = {European Conference on Computer Vision (ECCV)},
	year={2018},
	organization={Springer}
}


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
```

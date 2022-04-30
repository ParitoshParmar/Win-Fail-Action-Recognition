# Win-Fail-Action-Recognition (WACV Workshops, 2022)

## Introduction
Current video/action understanding systems have demonstrated impressive performance on large recognition tasks. However, they might be limiting themselves to learning to recognize spatiotemporal patterns, rather than attempting to thoroughly understand the actions. To spur progress in the direction of a truer, deeper understanding of videos, we introduce the task of win-fail action recognition -- differentiating between successful and failed attempts at various activities. We introduce a first of its kind **paired** win-fail action understanding dataset with samples from the following domains: "General Stunts," "Internet Wins-Fails," "Trick Shots," and "Party Games." Unlike existing action recognition datasets, intra-class variation is high making the task challenging, yet feasible. We systematically analyze the characteristics of the win-fail task/dataset with prototypical action recognition networks and a novel video retrieval task. While current action recognition methods work well on our task/dataset, they still leave a large gap to achieve high performance. We hope to motivate more work towards the true understanding of actions/videos.

## Dataset
Dataset can be downloaded from: https://drive.google.com/drive/folders/1q_El9GQJQgG8Agl8eUY3JUJvsYyb8UOP?usp=sharing. Please 7-zip to uncompress the dataset.

### Annotation format
1. All the samples are pairwise -- win and the corresponding fail.
2. 'g' stands for a good execution or win; while 'b' stands for a bad execution or failure.
3. 'label_0', 'start_0', 'stop_0' belong to clip_0 (win or fail) of a paired sample. Likewise, 'label_1', 'start_1', 'stop_1' belong to clip_1 (opposite of clip_0) of a paired sample. 
4. Sample annotation explanation:
<p align="left"> <img src="annotation_sample.png?raw=true" alt="win-fail action recognition annotation sample" width="400"/> </p>

If you find this dataset useful, please consider citing:
```
@article{parmar2021win,
  title={Win-Fail Action Recognition},
  author={Parmar, Paritosh and Morris, Brendan},
  journal={arXiv preprint arXiv:2102.07355},
  year={2021}
}
```

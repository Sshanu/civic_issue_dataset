# Adversarial Adaptation of Scene Graph Models for Understanding Civic Issues

Accepted at [[WWW 2019 Short](https://www2019.thewebconf.org)]

#####  [[Project  Page Link ]](https://sshanu.github.io/civic_issue_dataset/)     [[Paper Link ]](https://homes.cs.washington.edu/~mohitj/pdfs/c26-www-2019.pdf)

#### Abstract 
Citizen engagement and technology usage are two emerging trends driven by smart city initiatives. Governments around the world are adopting technology for faster resolution of civic issues. Typically, citizens report issues, such as broken roads, garbage dumps, etc. through web portals and mobile apps, in order for the government authorities to take appropriate actions. Several mediums -- text, image, audio, video -- are used to report these issues. Through a user study with 13 citizens and 3 authorities, we found that image is the most preferred medium to report civic issues. However, analyzing civic issue related images is challenging for the authorities as it requires manual effort. Moreover, previous works have been limited to identifying a specific set of issues from images. In this work, given an image, we propose to generate a Civic Issue Graph consisting of a set of objects and the semantic relations between them, which are representative of the underlying civic issue. We also release two multi-modal (text and images) datasets, that can help in the further analysis of civic issues from images. We present a novel approach for adversarial adaptation of existing scene graph models that enables the use of scene graphs for new applications in the absence of any labeled training data. We conduct several experiments to analyze the efficacy of our approach, and using human evaluation, we establish the appropriateness of our model at representing different civic issues.


### civic_issue_dataset

Dataset contains object labels and bounding boxes for civic issues (garbage, cracks and roads on road, manholes).

Download images from the [drive link](https://drive.google.com/open?id=1fvXn-SHSCu5jY4LPy79jeSdWrMhPkYPo) and extract them in the main folder.

Dataset contains four json files: garabage_coco.json, new_images_coco.json, pothole_coco.json, road_coco.json, which contain images, objects and, object's class and bounding box in mscoco dataset format.


### Reference

If you use this code as part of any published research, please acknowledge the following paper

```
@InProceedings{kumar2019adversarial,
author = {Kumar, Shanu and Atreja, Shubham and Singh, Anjali and Jain, Mohit},
title = {Adversarial Adaptation of Scene Graph Models forUnderstanding Civic Issues},
booktitle = {Proceedings of the 2019 World Wide Web Conference on World Wide Web},
year={2019},
organization={International World Wide Web Conferences Steering Committee}
```

## Contributors
* [Shanu Kumar][1] (sshanukr@gmail.com)



[1]: https://github.com/Sshanu

# SOS-Match

**Segmentation for Open-Set Robust Correspondence Search and Robot Localization in Unstructured Environments** is a research project aimed at achieving efficient and accurate frame alignment between agents using sparsity.

## Authors

- [Annika Thomas*](https://www.annikathomas.com)
- [Jouko Kinnari*](https://www.linkedin.com/in/jouko-kinnari/)
- [Parker Lusk](https://plusk01.github.io/)
- [Kota Kondo](https://www.linkedin.com/in/kkondo/?locale=en_US)
- [Jonathan How](https://www.mit.edu/~jhow/)

## Links

- **Code**: [GitHub Repository](https://github.com/yourusername/sos-slam)
- **Paper**: [Research Paper](https://drive.google.com/file/d/1b7TZhalVafbWrrrUepgkYl8vfeb106AZ/view?usp=sharing)
- **Datasets**: [Dataset Repository](https://www.dropbox.com/scl/fo/he8rq4ucgywmoha2y95zp/h?rlkey=cwt7q9whl4koelo4raiaptlfg&dl=0)

## Abstract

We present SOS-Match, a novel framework for detecting and matching objects in unstructured environments. Our system consists of 1) a front-end mapping pipeline using a zero-shot segmentation model to extract object masks from images and track them across frames and 2) a frame alignment pipeline that uses the geometric consistency of object relationships to efficiently localize across a variety of conditions. We evaluate SOS-Match on the Batvik seasonal dataset which includes drone flights collected over a coastal plot of southern Finland during different seasons and lighting conditions. Results show that our approach is more robust to changes in lighting and appearance than classical image feature-based approaches or global descriptor methods, and it provides more viewpoint invariance than learning-based feature detection and description approaches. SOS-Match localizes within a reference map up to 46x faster than other feature-based approaches and has a map size less than 0.5% the size of the most compact other maps. SOS-Match is a promising new approach for landmark detection and correspondence search in unstructured environments that is robust to changes in lighting and appearance and is more computationally efficient than other approaches, suggesting that the geometric arrangement of segments is a valuable localization cue in unstructured environments. We release our datasets at https://acl.mit.edu/SOS-Match/. 

<!-- ## Image -->

<!-- Insert an image here that represents the SOS-SLAM project. -->

<!-- ![SOS-SLAM Image](image.jpg) -->

<!-- ## Demo -->

<!-- You can view a live demo of SOS-SLAM [here](https://yourdemo.com). -->

<!-- ## Video Links -->

<!-- - [Introduction Video](https://www.youtube.com/watch?v=your-intro-video) -->
<!-- - [Tutorial Video](https://www.youtube.com/watch?v=your-tutorial-video) -->
  
# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

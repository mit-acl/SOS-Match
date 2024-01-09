# SOS-SLAM

**Segmentation for Open-Set Simultaneous Localization and Mapping in Unstructured Environments** is a research project aimed at achieving efficient and accurate SLAM using sparsity.

## Authors

- [Jouko Kinnari*](https://www.linkedin.com/in/jouko-kinnari/)
- [Annika Thomas*](https://www.annikathomas.com)
- [Parker Lusk](https://plusk01.github.io/)
- [Kota Kondo](https://www.linkedin.com/in/kkondo/?locale=en_US)
- [Jonathan How](https://www.mit.edu/~jhow/)

## Links

- **Code**: [GitHub Repository](https://github.com/yourusername/sos-slam)
- **Paper**: [Research Paper](https://drive.google.com/file/d/1b7TZhalVafbWrrrUepgkYl8vfeb106AZ/view?usp=sharing)
- **Datasets**: [Dataset Repository](https://www.dropbox.com/scl/fo/he8rq4ucgywmoha2y95zp/h?rlkey=cwt7q9whl4koelo4raiaptlfg&dl=0)

## Abstract

We present a novel framework for open-set Simultaneous Localization and Mapping (SLAM) in unstructured environments that uses segmentation to create a map of objects and geometric relationships between objects for localization. Our system consists of 1) a front-end mapping pipeline using a zero-shot segmentation model to extract object masks from images and track them across frames to generate an object-based map and 2) a frame alignment pipeline that uses the geometric consistency of objects to efficiently localize within maps taken in a variety of conditions. This approach is shown to be more robust to changes in lighting and appearance than traditional feature-based SLAM systems or global descriptor methods. This is established by evaluating SOS-SLAM on the Batvik seasonal dataset which includes drone flights collected over a coastal plot of southern Finland during different seasons and lighting conditions. Across flights during varying environmental conditions, our approach achieves higher recall than benchmark methods with precision of 1.0. SOS-SLAM localizes within a reference map up to 14x faster than other feature-based approaches and has a map size less than 0.4% the size of the most compact other maps. When considering localization performance from varying viewpoints, our approach outperforms all benchmarks from the same viewpoint and most benchmarks from different viewpoints. SOS-SLAM is a promising new approach for SLAM in unstructured environments that is robust to changes in lighting and appearance and is more computationally efficient than other approaches. We release our code and datasets: https://acl.mit.edu/SOS-SLAM/.

## Image

Insert an image here that represents the SOS-SLAM project.

![SOS-SLAM Image](image.jpg)

<!-- ## Demo -->

<!-- You can view a live demo of SOS-SLAM [here](https://yourdemo.com). -->

<! -- ## Video Links -->

<!-- - [Introduction Video](https://www.youtube.com/watch?v=your-intro-video) -->
<!-- - [Tutorial Video](https://www.youtube.com/watch?v=your-tutorial-video) -->
  
# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

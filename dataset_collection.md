##  Kinect Tracking Precision Dataset
- **Hyperlink**: [KLT](http://www.dei.unipd.it/~munaro/KTP-dataset.html)
![ImageShow](http://www.dei.unipd.it/~munaro/images/research_images/KTPdataset/AllScenarios.jpg)
- **Description**:  <p>The Kinect Tracking Precision Dataset (KTP Dataset) has been realized to measure 2D/3D accuracy and precision of people tracking algorithms based on data coming from consumer RGB-D sensors. It contains 8475 frames acquired with a Microsoft Kinect at 640x480 pixel resolution and at 30Hz, for a total of 14766 instances of people.
We provide both image and metric ground truth for people position. People 2D position has been manually annotated on the RGB images. People 3D position has been obtained by placing one infrared marker on every person's head and tracking them with a BTS motion capture system. The dataset has been acquired from a mobile robot and consists of four videos. In each video, five people are present and five different situations are created, but with different movements of the robot. Here below, a pictorial representation of the motion capture room, of the position of the robot and of its movement in the four videos is reported. At this page, a description of the sequences present in the dataset can be found.
![Still](http://www.dei.unipd.it/~munaro/images/research_images/KTPdataset/robotMotion2.png)</p>
- **Download**:To download the dataset as ROS bags containing synchronized RGB-D stream and robot pose, click [here](http://robotics.dei.unipd.it/reid/dataset/KTP_Dataset/KTP_dataset_bags.zip).
To download the dataset as RGB and depth images with timestamp and the robot pose written in a text file, please click [here](http://robotics.dei.unipd.it/reid/dataset/KTP_Dataset/KTP_dataset_images.zip).
- **References**: <pre>If you use this dataset, please cite the following articles:
M. Munaro and E. Menegatti. [Fast RGB-D people tracking for service robots](http://robotics.dei.unipd.it/images/Papers/Conferences/MunaroAURO14.pdf). Journal on Autonomous Robots, Springer, vol. 37, no. 3, pp. 227-242, ISSN: 0929-5593, doi: 10.1007/s10514-014-9385-0, 2014.
M. Munaro, F. Basso, and E. Menegatti. "[People tracking within groups with RGB-D data](http://robotics.dei.unipd.it/images/Papers/Conferences/munaro_iros12)". In Proceedings of the International Conference on Intelligent Robots and Systems (IROS), Algarve (Portugal), pp. 2101-2107, 2012.</pre>

## Cornell Activity Datasets: CAD-60 & CAD-120
- **Hyperlink**: [Cornell Activity Datasets](http://pr.cs.cornell.edu/humanactivities/data.php)
- **Description**:  ![ImageShow](http://pr.cs.cornell.edu/humanactivities/images/all_activity_pic_combined.jpg)
  - Data
    The CAD-60 and CAD-120 data sets comprise of RGB-D video sequences of humans performing activities which are recording using the Microsoft Kinect sensor.
    - CAD-60
      - CAD-60 dataset features:
        - 60 RGB-D videos
        - 4 subjects: two male, two female, one left-handed
        - 5 different environments: office, kitchen, bedroom, bathroom, and living room
        - 12 activities: rinsing mouth, brushing teeth, wearing contact lens, talking on the phone, drinking water, opening pill container, cooking (chopping), cooking (stirring), talking on couch, relaxing on couch, writing on whiteboard, working on computer
      tracked skeletons
      
      Each video come with RGB images, Depth images, and the tracked skeletons.

      1|2|3|4|5 
      ------------ | ------------- | ------------- | ------------- | -------------
      Information | 	[README](http://pr.cs.cornell.edu/humanactivities/data/README_CAD60.txt)  | [Sample Images](http://pr.cs.cornell.edu/humanactivities/images/cad60_pic.jpg) | [State of the art results](http://pr.cs.cornell.edu/humanactivities/results.php) |
      Download RGB-D + Skeleton: | 	[Person 1](http://pr.cs.cornell.edu/humanactivities/data/data1.zip)  | [Person 2](http://pr.cs.cornell.edu/humanactivities/data/data2.zip) | [Person 3](http://pr.cs.cornell.edu/humanactivities/data/data3.zip) | [Person 4](http://pr.cs.cornell.edu/humanactivities/data/data4.zip)
      
    - CAD-120
      CAD-120 dataset features:
      - 120 RGB-D videos of long daily activities
      - 4 subjects: two male, two female, one left-handed
      - 10 high-level activities: making cereal, taking medicine, stacking objects, unstacking objects, microwaving food, picking objects, cleaning objects, taking food, arranging objects, having a meal
      - 10 sub-activity labels: reaching, moving, pouring, eating, drinking, opening, placing, closing, scrubbing, null
      - 12 object affordance labels: reachable, movable, pourable, pourto, containable, drinkable, openable, placeable, closable, scrubbable, scrubber, stationary
      - tracked skeletons
      
      Click here for samle images.
      
      |    RGB-D images |   [Person 1](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject1_rgbd_images.tar.gz)  | [Person 2](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject3_rgbd_images.tar.gz)    | [Person 3](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject4_rgbd_images.tar.gz)    | [Person 4](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject5_rgbd_images.tar.gz)    | [README](http://pr.cs.cornell.edu/humanactivities/data/README_images.txt)      |
      |----------------:|:-------------------------------------------------------------------------------------:|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
      | RGB-D text data |  [Person 1](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject1_rgbd_rawtext.tar.gz) | [Person 2](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject3_rgbd_rawtext.tar.gz)   | [Person 3](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject4_rgbd_rawtext.tar.gz)   | [Person 4](http://pr.cs.cornell.edu/web3/CAD-120/data/Subject5_rgbd_rawtext.tar.gz)   | [README](http://pr.cs.cornell.edu/humanactivities/data/README_raw.txt)         |
      |     Annotations | [Person 1](http://pr.cs.cornell.edu/humanactivities/data/Subject1_annotations.tar.gz) | [Person 2](http://pr.cs.cornell.edu/humanactivities/data/Subject3_annotations.tar.gz) | [Person 3](http://pr.cs.cornell.edu/humanactivities/data/Subject4_annotations.tar.gz) | [Person 4](http://pr.cs.cornell.edu/humanactivities/data/Subject5_annotations.tar.gz) | [README](http://pr.cs.cornell.edu/humanactivities/data/README_annotations.txt) |
      |        Features |         [Features](http://pr.cs.cornell.edu/humanactivities/data/features.tar)        | [README](http://pr.cs.cornell.edu/humanactivities/data/README_features.txt)           |                                                                                       |                                                                                       |                                                                                |
      
      

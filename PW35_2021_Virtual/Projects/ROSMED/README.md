Back to [Projects List](../../README.md#ProjectsList)

# ROS-MED: Integration of 3D Slicer and ROS2 for Image-Guided Robot-Assisted Interventions

## Key Investigators

- Junichi Tokuda (Brigham and Women's Hospital)
- Tamas Ungi (Queen’s University)
- Axel Krieger (Johns Hopkins University) 
- Simon Leonard (Johns Hopkins University)
- Mark Fuge (University of Maryland)
- Lydia Al-Zogbi (Johns Hopkins University)
- Pedro Moreira (Brigham and Women's Hospital)

# Project Description

The ultimate goal of this project is to provide a software platform to integrate medical image computing
software (3D Slicer) into a system for image-guided robot-assisted interventions, in which 2D/3D medical
images are used for planning, navigation, monitoring, and validation. 
Examples of such robot-assisted systems include image-guided robotic needle-guide systems and surgical
CAD/CAM systems. Those systems often require a wide range of image computing capabilities such as
segmentation of anatomical structures, registration of multiple images, 2D/3D image visualization,
image-based planning, and data sharing with the robot controller and the hospital’s picture archiving
and communication systems (PACS). Integration of a solid medical image computing platform into a robotic
system is becoming more important than ever with the growing interest in AI-based treatment planning and guidance. 

However, the engineering effort to implement those features is often underestimated in academic research
due to limited engineering resources or the scope of the project. Fortunately, many of those features have
already been implemented and validated in the research community and often distributed as open-source software. 
Therefore it has become essential for academic researchers to take advantage of those existing tools and
incorporate them into their own research instead of reinventing the wheel. 

Our team has been integrating 3D Slicer and Robot Operating System using OpenIGTLink to achieve the above goal
following [our first project](https://www.na-mic.org/wiki/2016_Winter_Project_Week/Projects/SlicerROSIntegration),
and recently received a grant from National Institutes of Health (2R01EB020667). In this year, we will focus on
transition to the new ROS platform (ROS2).

<!-- Add a short paragraph describing the project. -->

## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Objective A. Architecture design
1. Objective B. Prototype ROS-IGTL-Bridge2 for data exchange between 3D Slicer and ROS2

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

1. Describe specific steps of **what you plan to do** to achieve the above described objectives.
1. ...
1. ...

## Progress and Next Steps

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE. If there are specific steps that you could not complete then you can describe them here, too. -->

1. Describe specific steps you **have actually done**.
1. ...
1. ...

# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

# Background and References
- Frank T, Krieger A, Leonard S, Patel NA, Tokuda J. ROS-IGTL-Bridge: an open network interface for image-guided therapy using the ROS environment. Int J Comput Assist Radiol Surg. 2017 Aug;12(8):1451-1460. doi: 10.1007/s11548-017-1618-1. Epub 2017 May 31. PMID: 28567563; [PMCID: PMC5543207](https://www-ncbi-nlm-nih-gov.ezp-prod1.hul.harvard.edu/pmc/articles/PMC5543207/).
<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->

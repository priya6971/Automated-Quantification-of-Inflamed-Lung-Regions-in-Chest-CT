# Automated Quantification of Inflamed Lung Regions in Chest CT by UNet++ and SegCaps: A Comparative Analysis in COVID-19 Cases

## Problem Statement
In order to help the treating clinician during the present COVID-19 pandemic, a significant amount of lung imaging has been produced. It is crucial to accurately quantify the severity of lung inflammation since it is linked to the course of the disease. When lung inflammation is quantified in a chest CT scan, it can be difficult to produce consistent and accurate reporting in high-demand situations without sacrificing patient care. 

## Solution Approach
In this context, automated segmentation was recently attempted using UNet++, a convolutional neural network (CNN), with results comparable to manual methods. In this project, we hypothesise that using capsule networks with fewer parameters, an advanced vector representation of information, and dynamic routing, we can perform the desired task with comparable efficiency. We validate this hypothesis in this project using SegCaps, a capsule network, through direct comparison, individual comparison with CT severity score, and comparing the relative effect on an ML(machine learning)-based prognosis model developed elsewhere. We also present a scenario in which the combination of UNet++ and SegCaps outperforms the individual models.

## Tech Stack

**Models:** UNet++, SegCaps

**Dependences:** Python, Pytorch, Tensorflow, Seaborn, Numpy, Pandas, 
Seaborn


**Performance Metrics:** Dice Score, IOU Score

## Project Architecture

[
![Proposed Approach Poster](https://user-images.githubusercontent.com/29665085/210376208-384fd3ae-1460-443b-b44b-905e23dd730a.png)
](url)

## Results
| Region of Interest      | Inflammation Segmentation using UNet++      | Inflammation Segmentation using Capsule Networks |
|------------|-------------|-------------|
| ![Result3-27-extracted](https://user-images.githubusercontent.com/29665085/210382750-4e525495-350f-4fd5-bc29-511bb4a1154b.jpg) | ![Result3-27-unet](https://user-images.githubusercontent.com/29665085/210382807-52050171-d93d-45fb-a2c9-0a5125cd541b.jpg) |![Result3-27-capsnet](https://user-images.githubusercontent.com/29665085/210382839-4d1541e4-7f43-446f-8abc-a1d533b418da.jpg) |

## Research Paper Link
The paper can be found at: https://ieeexplore.ieee.org/document/9870901

## Authors

- [@Priya Bhatia](https://github.com/priya6971)

- [@Abhishar Sinha](https://github.com/abhisharsinha)


## License

[MIT](https://choosealicense.com/licenses/mit/)

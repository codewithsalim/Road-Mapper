# Road Mapper - Extraction of Road Topology from Aerial Images
This project estimates road topology from aerial images using Image Processing and Deep Learning model ResNet.

Creating road maps is essential for applications such as autonomous driving and city planning. Most approaches in industry focus on leveraging expensive sensors mounted on top of a fleet of cars. This results in very accurate estimates when exploiting a user in the loop. However, these solutions are very expensive and have small coverage.

We propose an approach that directly estimates road topology from aerial images. This provides us with an affordable solution with large coverage. Towards this goal, we take advantage of the latest developments in deep learning to have an initial segmentation of the aerial images.

We then propose an algorithm that reasons about missing connections in the extracted road topology as a shortest path problem that can be solved efficiently.

**Sample Input:** Aerial Image

<img align="left" alt="Aerial Image" width="250px" src=https://github.com/codewithsalim/Road-Mapper/blob/main/resources/input_sample/input_image.png>

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

**Sample Output:** Target Map and final output

<img align="left" alt="Aerial Image" width="250px" src=https://github.com/codewithsalim/Road-Mapper/blob/main/resources/output_sample/output_target_map.png>
<img align="left" alt="Aerial Image" width="250px" src=https://github.com/codewithsalim/Road-Mapper/blob/main/resources/output_sample/output_imposed_on_image.png>


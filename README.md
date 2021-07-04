# Road Mapper - Extraction of Road Topology from Aerial Images
This project estimates road topology from aerial images using Image Processing and Deep Learning model ResNet.

Creating road maps is essential for applications such as autonomous driving and city planning. Most approaches in industry focus on leveraging expensive sensors mounted on top of a fleet of cars. This results in very accurate estimates when exploiting a user in the loop. However, these solutions are very expensive and have small coverage.

We propose an approach that directly estimates road topology from aerial images. This provides us with an affordable solution with large coverage. Towards this goal, we take advantage of the latest developments in deep learning to have an initial segmentation of the aerial images.

We then propose an algorithm that reasons about missing connections in the extracted road topology as a shortest path problem that can be solved efficiently.

Sample Input: Aerial Image
![Aeril Image](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

Sample Output:
![Output](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

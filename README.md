# Application of Graph segmentation algorithm for image segmentation.

This algorithm for graph-segmentation was originally developed by Pedro F. Felzenszwalb. Its C++ implementation is freely available under the terms of the GNU General Public License.

If you use this software for research purposes, you should cite Efficient Graph-Based Image Segmentation by Pedro F. Felzenszwalb and Daniel P. Huttenlocher, International Journal of Computer Vision, Volume 59, Number 2, September 2004. You can find more details and access the work via the link: http://cs.brown.edu/~pff/segment/

This code is modified by the current owner pmcafo, motivated to make this algorithm compatible with different image formats. Furthermore, OpenCV is one of the most widely used computer vision libraries, which enhances the algorithm's flexibility.

Aside from this, as robot vision platforms rarely use raw image formats(.ppm, .pgm etc) and more often use compressed image formats (say .jpg), this algorithm is integrated with robot platform ROS(Robot Operating System).

To run this version of Software, dependencies of OpenCV and cmake must be installed.

Compilation Instructions:

a. cd GraphSegmentation (folder_ containing_GraphSegmentation_source)

b. mkdir build

c. cm
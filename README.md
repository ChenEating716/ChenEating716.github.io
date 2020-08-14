# ChenEating716.github.io
Description for CYT_Dataset
This dataset consists of five parts(RGBImages,DepthImages,SegImages,BaseandOrien and PointCloud)

RGBImages:
100000 512*512 PNG files,containing color information.
Generated by PyBullet Synthetic Camera Rendering.

DepthImages:
100000 512*512 PNG files,containing depth information.
Generated by PyBullet Synthetic Camera Rendering.

SegImages:
100000 512*512 PNG files,containing segmetation information.
Segmentation Images automaticly generated by PyBullet

BaseandOrien:
100000 .csv files,containing base and orientation information for each object.

Pointcloud:
100000 .ply files,containing colorful 3D point cloud information,generated from DepthImages and RGBImages.

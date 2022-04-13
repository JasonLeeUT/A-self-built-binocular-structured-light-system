# A-self-built-binocular-structured-light-system
Describe the algorithms in SL-based 3D reconstruction in details.
<div align=center>
![系统结构图](https://user-images.githubusercontent.com/32419924/163164854-973fe81f-3bdd-4044-ac7f-45e2599ee6c6.png)
</div>

A self-built structured light scanner mounted on a robot arm is utilized in this work. The system was built by the AMNL 3D vision team. I have done the camera assembly, lens cleaning and system maintaining work. It includes one projector (Texas Instruments DLPLCR4500EVM) and two cameras (Basler acA2440-20gm GigE with the Sony IMX 264 CMOS chip). The working distance of the 3D scanner is 900 mm and the scanner resolution is 2448×2048 pixels. In each measurement, 12 different fringe patterns are projected on object surface subsequently, and then 13 pairs of gray images (12 pairs of images with fringes, 1 pair of images under blue light) are collected.

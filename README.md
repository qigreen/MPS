----------------------------------------------------------------
Maximal Poisson-disk Sampling via Sampling Radius Optimization

----------------------------------------------------------------
Usage example (see run.bat):
  gx_mps.exe square.line 300
  
Input:
"square.line" is the boundary, namely, the unit square.
"300" is the number of points to be sampled, and you can change it according to your applications.

Output: 
The sampled points in the format of .pts, which is located in ./data folder.

Note that, this release is only available on 64-bit systems.

----------------------------------------------------------------
If you use this code, please cite the following paper:

@inproceedings{Quan2016MAXMPS,
 author = {Quan, Weize and Yan, Dong-Ming and Guo, Jianwei and Meng, Weiliang and Zhang, Xiaopeng},
 title = {Maximal Poisson-disk Sampling via Sampling Radius Optimization},
 booktitle = {SIGGRAPH ASIA 2016 Posters},
 series = {SA '16},
 year = {2016},
 pages = {22:1--22:2}
}

----------------------------------------------------------------
If you have any questions, please feel free to contact qweizework@gmail.com
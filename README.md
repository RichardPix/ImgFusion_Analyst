# ImgFusion Analyst
ImgFusion Analyst is an ArcMap-based Add-In software to conduct satellite image fusion and the corresponding fusion accuracy evaluation.

The installation steps of the software ImgFusion Analyst are as follows:
1.	Please double click the ArcMap AddIn installation file “USIF.esriAddIn”, then it will be installed into your ArcMap software.
2.	In ArcMap, check the box of ImgFusion Analyst in the "Extensions" window to activate the Add-In software. 
3.	Check the box of ImgFusion Analyst after right clicking in the blank area beside the toolbars. Then a floating toolbar of the software will appear, you can dock it in the blank area beside the toolbars. Installation done! 

PS: This AddIn file can only be installed on ArcMap version 10.0 or above.

Currently, this software was only tested for MODIS and Landsat image fusion, and the input images must be registered and clipped to have the same geographic coverage. Moreover, the bands configuration of the input MODIS and Landsat images must be corresponding with each other. For more specific operations, please refer to the image fusion tutorials in the help file. Additionally, we attached a set of test data for users to get familiar with ImgFusion Analyst.

Should you have any questions or find any bugs, please contact Bo Huang (bohuang@cuhk.edu.hk) or Yongquan Zhao (yqzhao@link.cuhk.edu.hk) freely. We will be continuing to improve the software. Welcome feedbacks!

References about the spaital-temporal image fusion algorithm in ImgFusion Analyst:
1. Zhao, Y., Huang, B., & Song, H. (2018). A robust adaptive spatial and temporal image fusion model for complex land surface changes. Remote sensing of environment, 208, 42-62. doi:10.1016/j.rse.2018.02.009
2. Zhao, Y., Liu, D., & Wei, X. (2020). Monitoring cyanobacterial harmful algal blooms at high spatiotemporal resolution by fusing Landsat and MODIS imagery. Environmental Advances, 2, 100008. doi:10.1016/j.envadv.2020.100008

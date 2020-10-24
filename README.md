<big>**1. Requirements and Installation:**</big>

</big>Requirements</big>

Users can run &#39;GNSS-TS-NRS&#39; under any operating system with MATLAB software installed. MATLAB2020b should be the most suitable version.When MATLAB2020b has been installed on the computer, there is no need for other toolboxes. 

</big>Installation</big>

When MATLAB2020b has been installed on the computer, you can run this program as follows：

- Download &#39;GNSS-TS-NRS&#39; software installation package
- Add sub-folders of &#39;GNSS-TS-NRS&#39; package to the current path of MATLAB
- Run &quot;GNSS\_TS\_NRS.m&quot; or enter &quot;GNSS\_TS\_NRS&quot; on the command line to run the main interface of the software

</big>**2. Description:**</big>

&#39;GNSS-TS-NRS&#39; is a software package that can be used to process GNSS time series, composed of 5 modules:

- Time series noise reduction module:

Data input: Real times series and simulated times series (white noise &amp; colored noise);

Noise reduction algorithms: EMD, EEMD, three new algorithms (details in the paper);

Draw figures: Time series before and after noise reduction, IMFs, correlation coefficient.

Precision assessment: correlation coefficient Root mean square error (RMSE), signal noise ratio (SNR);

- Common mode error (CME) mitigation module:

Data input: Daily solution time series and coordinate

Algorithms: Stacking filtering, weighted stacking filtering, correlation weighted stacking filtering, distance weighted filtering, principal component analysis

Draw figures: Time series before and after CME mitigation, root mean square (RMS)

Precision assessment: RMS

- Time series plot and statistical analysis module:

The module can plot the following figure: RMS, correlation coefficient, power spectral density (PSD), norm and alpha-stable distribution fitting, Box-whisker plot and Violin plot.

- Time series processing tools module:

Outlier detection: Eliminate gross errors of observation data in batches, using n\*sigma, n\* IQR and MAD criterion

Format tool: convert the file format from CMONOC and SOPAC to the\*.mom in batches

- Nearby sites and find co-located sites module:

Nearby sites: Enter site latitude and longitude or site name to search for nearby sites.

Co-located sites: Search for collocated stations based on reference distance between GNSS stations and Tide gauge.

Also, the station database can be changed by user.

The following diagram shows is the main interface of GNSS-TS-NRS and the procedure of data analysis can be seen in the user
operation video guide. 

![Image text](https://github.com/CL-Xiong/img-folder/blob/main/main.png)

</big></big>**3. How to cite:**</big></big>

If you find the GNSS-TS-NRS program is useful, **please cite it in your work as:X. He, K. Yu, J.P. Montillet, C. Xiong, T. Lu, S. Zhou, X. Ma, H. Cui, F. Ming. GNSS-TS-NRS: An Open-source MATLAB Based GNSS Time Series Noise Reduction Software, Remote Sensing, 2020, accepted to appear.**

</big>**4. Contact information:**</big>

If you have any comments or questions on GNSS-TS-NRS, please don't hesitate to contact Dr. He (hexiaoxing@whu.edu.cn) or Mr. Xiong (cl-xiong@qq.com), Thanks for your attention.

# 158888_Group5_project
The code part and the data part of 158888 Group 5 project Research on the compatibility between economic growth and Sustainable Development Goals by using the data warehousing

Usage details about this project:
Statement: This project is a project of the fifth group of Massey University's 158888 IT professional project course. The paper coordinator is Professor Sanjay Mathrani, and the project members are Kaipeng Han, Shengliang  Zou, Yixuan Niu, and Zhangrui Ren. Any commercial activities are prohibited.
The original data of the project comes from: https://dashboards.sdgindex.org/downloads.

This part is the virtual machine used in the project.

https://masseyuni-my.sharepoint.com/:f:/g/personal/23019676_massey_ac_nz/EiJS7uQA0NtGnBopB6h5rAcBrYXHEm8irNRcHJNKNIwTjg?e=xaT9Sl

This link comes from Massey University's Onedrive. The permissions set are editable by Massey University users. You can access it through this link.

About virtual machines:
Why upload to Onedrive?
Because this virtual machine is too large (about 80GB), it contains the Hadoop cluster and database installed by our team (the database has been uploaded in this project), which is the key to running the data warehouse.
Of course, it is not necessary to run this virtual machine completely, because we only perform the data processing part on the virtual machine. You can view the processed data and SQL code in the library I uploaded.
If you are not running a Hadoop cluster, you can download SDGs_analysis.sql directly. This file contains the tables to be processed. After uploading this sql file to MySQL and running the SQL code in 158888_SQL_code.txt, you can also get the data processing results (but the processing speed is much slower than the Hadoop cluster).

If you want to use a virtual machine to view the data processing process, please refer to the "Virtual Machine Usage Document" we uploaded, which contains detailed virtual machine account passwords, how to use the cluster startup script, how to start Hive, etc.Not all data in this project is processed through Hive, and some are also processed through Excel. Please refer to the uploaded chart for details.

Please refer to the 158888_group_5.ipynb file to view the algorithm used in this project.

The data tables used in 158888_group_5.ipynb are all in the data file folder. The code of this project runs using Google's managed Jupyter notebook service - Colab. It can also be run using Jupyter Notebook but the necessary libraries need to be installed. For details, please refer to the detailed code.

In this project, all data and virtual machine resources are managed by "158888 Group 5 Team". No individual or group is allowed to use these resources for commercial profit or academic research activities without the express authorization of the team.

All data within the "Data Package-Shengliang Zou" folder is processed and managed by Shengliang Zou. No individual or group may use the data in this folder for profit-making activities or academic research without the express authorization of Shengliang Zou.

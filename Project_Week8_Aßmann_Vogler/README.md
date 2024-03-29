## Before running the notebook
1. Create two data sets in your Google Cloud Platform, one called StudentLife_Stress and one called StudentLife_Activity. For each data set create two tables by uploading the stress response and activity data for the IDs 10 and 16 into the respective data set. Set the environment variable in code cell 3 to your Google Cloud project id with string quotes. In code cells 4 and 7 replace PROJECTID by your Google Cloud project id wihtout quotes.
2. Place the Stress and Sleep folders from EMA/response into your Google drive. Do the same for sensing/activity and sensing/conversation. Now set the basepath variable in code cell 3 to the full path of the Google drive directory where you placed the data files.
3. Please mind that in code cells 1 and 2 your are asked to mount your Google drive and provide your credentials before beeing able to run the cells below.

## Improved Report and Notebook
Figure 1 of the report showed identical time series for the student's u10 and u16 because of a typo in the notebook when loading the data from GCP. 
This was fixed and the report was adapted correspondingly. Also the measure that was used to assess the performance of the implemented student's state prediction
was described better. Find the updated version in IPADS\_report8\_v2\_latex.pdf and IPADS\_Project\_Week8\_v2.ipynb.
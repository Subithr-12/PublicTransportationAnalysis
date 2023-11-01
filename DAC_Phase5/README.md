__Dataset link:__ https://www.kaggle.com/datasets/rednivrug/unisys?select=20140711.CSV
To run the code snippets in these notebooks (DAC_Phase2, DAC_Phase3 and DAC_Phase4), download this dataset and the notebooks and integrate them in your Jupyter workspace. 
Alternatively, open a notebook in the kaggle dataset itself using your kaggle account and try running these snippets in order.

__To produce visualisations:__

Sign up or Sign in to your IBM Cognos account: https://www.ibm.com/account/reg/us-en/signup?formid=urx-34710
Compress the cleaned dataset and upload it into “My Content”
Create dashboard and explore visualisations
Just drag and drop columns onto visualisation fields.

__Sample visualisations:__

A bar chart visualizing the noOfBoardings for each route for RouteID ranging from 100 to 288:

![image](https://github.com/Subithr-12/PublicTransportationAnalysis/assets/112576292/036aca1d-4864-420a-807a-c0df7dfac995)

__Insights:__

RouteID 222.0 has the highest total NumberOfBoardings due to WeekBeginning 2013-07-21.
NumberOfBoardings is unusually high when RouteID is 222 and 300.
Visualizing NoOfBoardings by StopName:

![image](https://github.com/Subithr-12/PublicTransportationAnalysis/assets/112576292/e8114fe6-7349-4b0c-a678-c63cca865d04)


__Insight:__

NumberOfBoardings is unusually high when StopName is X1 King William St.
A heat map representing NoOfBoardings by TripID for the WeekBeginning from 7/7/2013 to 8/25/2013:

![image](https://github.com/Subithr-12/PublicTransportationAnalysis/assets/112576292/993dfd14-315d-41a1-9bd7-598e952e99a2)



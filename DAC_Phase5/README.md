Dataset link: https://www.kaggle.com/datasets/rednivrug/unisys?select=20140711.CSV
To run the code snippets in these notebooks (DAC_Phase2, DAC_Phase3 and DAC_Phase4), download this dataset and the notebooks and integrate them in your Jupyter workspace. 
Alternatively, open a notebook in the kaggle dataset itself using your kaggle account and try running these snippets in order.

__To produce visualisations:__
Sign up or Sign in to your IBM Cognos account: https://www.ibm.com/account/reg/us-en/signup?formid=urx-34710
Compress the cleaned dataset and upload it into “My Content”
Create dashboard and explore visualisations
Just drag and drop columns onto visualisation fields.


__Sample visualisations:__
A bar chart visualizing the noOfBoardings for each route for RouteID ranging from 100 to 288:

![image](https://github.com/Sreenithi2004/Public-Transportation-Analysis/assets/138644158/1e978a27-47c6-4d39-80a8-1e843762a7d4)

__Insights:__
RouteID 222.0 has the highest total NumberOfBoardings due to WeekBeginning 2013-07-21.
NumberOfBoardings is unusually high when RouteID is 222 and 300.
Visualizing NoOfBoardings by StopName:
![image](https://github.com/Sreenithi2004/Public-Transportation-Analysis/assets/138644158/e253a749-346e-40eb-9c6b-882e376a2b8c)


__Insight:__
NumberOfBoardings is unusually high when StopName is X1 King William St.
A heat map representing NoOfBoardings by TripID for the WeekBeginning from 7/7/2013 to 8/25/2013:
![image](https://github.com/Sreenithi2004/Public-Transportation-Analysis/assets/138644158/3819e76a-0d26-43ae-aab9-a4c9acc89fce)

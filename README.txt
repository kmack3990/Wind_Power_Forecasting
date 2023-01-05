Structure and Outline Wind Power Forecasting Project by Kiley Mack

Report - Filename: Kiley_Mack_Capstone_Final_Report.pdf
- Introduction
- Data Structure and Processing
- EDA
- Initial Modeling
- Machine Learning
- Deep Learning
- Conclusion
- References

Notebook 1 - filename:  capstone_notebook1.ipynb - Large file size due to ploty visualizations. Needed be compressed to upload.  Apologize. 
- Environment - “timeseries” Conda Environment - contains - Python = 3.8, numpy, pandas, matplotlib, seaborn, statsmodels, scikit-learn = 0.24.1, jupyter, jupyter lab, plotly - 4.14.3, fbprophet = 0.7.1
- Workflow - Initial EDA --> Data Cleaning and Processing --> More EDA --> SARIMAX Model --> VAR Model


Notebook 2 - filename:  capstone_notebook2.ipynb
- Environment - “timeseries” Conda Environment
- Workflow - Data processing/Feature Engineer --> RFR Model with wind and power --> RFR Model with Time Lag for One step Predictions --> FBProphet model


Notebook 3 - filename:  capstone_notebook3.ipynb
- Environment - “deeplearning” Conda Environment - contains - Python = 3.8, numpy=1.19.2, pandas, matplotlib, jupyter, jupyterlab, pydot, pillow, seaborn, tensorflow==2.7.0, scikit-learn=0.24.1, nltk gensim=3.8.3, pytorch=1.4, torchvision=0.5.0, tqdm
-Workflow - Vanilla LSTM on Daily Time Series--> Bidirectional LSTM on Daily Time Series --> Vanilla LSTM on Hourly Time Series --> LSTM/CNN on Hourly Time Series --> Optimization of Vanilla LSTM on Hourly Time Series

Data
- Raw Data
  - Meterological Data
      - wind-farm-1-metmast-2016.csv (Wind Farm 1 Meterological Data for 2016)
      - wind-farm-1-metmast-2017.csv (Wind Farm 1 Meterological Data for 2017)
  - Power and Meterological Data
      - Data files too large to upload even when compressed.  Found here --> 
              https://opendata.edp.com/pages/challenges/
      - wind-farm-1-signals-2016.csv (Wind Farm 1 Power Data for 2016)
      - wind-farm-1-signals-2017.csv (Wind Farm 1 Power Data for 2017)
- Processed Data
      - hourly_df.csv (Mean of all four turbine's grid power output and wind speed for each hour of 2016)
      - daily_df.csv (Mean of all four turbine's grid power output for each day of 2016)
      - final_2016df.csv (Cleaned, processed, and pertinent power and meterological features for 2016)

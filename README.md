# ReverseChiSquared
Data generation by Reversing the Chi Squared technique.

Paper in the process of revision and submittion.

Streamlit demo for generating data for your own datasets:
Online demo:

https://share.streamlit.io/arm627/reversechisquared/main/app.py

To run this yourself:

1. Clone this repo
2. pip install -r requirements.txt
3. streamlit run app.py

Inside the demo:
1. Upload your dataset (.csv)
2. Choose which columns you want to generate more data of (Warning: Currently percentages get the best results since the primary application was built for that, however more testing and support for discrete, non- percentage values will come in the future)
![Columns](static/1.PNG?raw=true "Choose Columns")
3. Choose the percentage you want to split the dataset (into training and testing)
![Split](static/2.PNG?raw=true "Choose Split Amount")
4. Choose how much new data you want to generate (Warning: bugs exist here so the exact amount you select will not be generated. This will be fixed, but is not a breaking bug. Just experiment with this value). (Also: part of the original dataset is included in this generated amount)
![Generate](static/3.PNG?raw=true "Choose Generate Amoutn")
5. Download the test and generated datasets for use
6. Explore the datasets distribution (compares the distribution of generated data to the original data)
![Explore](static/4.PNG?raw=true "Explore Generated Data")

---
title: "Yunex Intern Challenge 2022"
excerpt: "Used Machine Learning and Data Analytics to explore the influence of weather regimes on energy production and demand"
collection: portfolio
---

As part of the final stage of the [Yunex Intern Challenge](https://github.com/jacobrstone/Yunex-Intern-Challenge-2022) for my application to Yunex Traffic as **Artificial Intelligence & Machine Learning Intern**, I used Machine Learning and Data Analytics to explore the influence of weather regimes and energy production and demand. I used **Matplotlib** and **Seaborn** to explore seasonal trends within data sourced from the UK GOV website on UK electricity consumption per month. I created a line plot with lines coloured by source from years 1980-2020. I explored the distribution of those sources with pie charts also. Further on, I focused solely on the UK's renewable sources and compared those with a stacked bar chart to show how hydroelectricity and wind were popularised over time. I went on to explore how electricity demand in the UK changed over time. 

After analysing the data I started the pre-processing for time-series forecasting to implement an **LSTM (Long-Short Term Memory) model** to predict the future demand of the electricity in the UK. I created functions for train/test split and to print the results, plotting the loss, and plotting the results. Using **Seaborn** I plotted the true electricity consumption in TWh, and analysed a seasonal decomposition of the data. Then, using a TimeSeriesGenerator from **Tensorflow** I creatd train and test sets. I made a simple RNN model in **Keras** with a single 10 neuron layer using relu activation, and an output layer with Tanh. I trained for 15 epochs achieving a final loss of 0.0075 and a Sqaured MSE of 1.15 in training and 1.28 in testing.

I created an 18-minute presentation outlinging my findings and work, and answered a 20 minute Q&A session with the assessors.
# crypto-clustering

## Description
The task is to find cryptocurrencies that differ from bitcoin (BTC2) at different time intervals.

The closing prices for available cryptocurrencies are considered for three different time intervals:
- for the last 30 days with a daily frequency
- for the last 3 days with an hourly frequency
- for the last hour with a minute frequency
Cluster analysis was performed for each of the time groups using KMeans and DTW.

## Requirements
`cryptocompare`

`tslearn`

## Algorithms & Techniques
KMeans & DTW time series clustering

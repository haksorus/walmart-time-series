# Walmart stock price prediction (LSTM vs GRU)

<p align="center">
 <img width="800" alt="image" src="https://user-images.githubusercontent.com/69139386/185232355-3bcba7b5-0d82-48e3-b25e-f534aadd102b.png">
</p> 


## About work
In this project I used two recurrent neural network (**RNN**) to predict **Walmart stock price**:
* with long short term memory (**LSTM**) 
* with gated recurrent unit (**GRU**)

Also, model inference was compared (**LSTM** vs **GRU**)

## Data

Dataset was collected from [investing.com](https://www.investing.com/)

It consists data from **2013** to **2022** year (**Walmart daily stock price values and other additional features**)

If you want to use it, you can find my dataset [here](https://www.kaggle.com/datasets/haksorus/wallmartstockprice)

## LSTM vs GRU

<p align="center">
 <img width="800" alt="image" src="https://user-images.githubusercontent.com/69139386/185227103-55fa9681-6836-413e-bde0-42ae55feb144.png">
</p> 

For each of this units, I've trained a simple RNN using **MAE loss** and **Adam optimizer** in **50 epochs**

After training both of networks inference (prediction + 30-day forecast) was compared 

In this case, **LSTM** works better (**MAE = 1.42**) than **GRU** (**MAE = 2.49**)

## Demo 

### LSTM inference:

<p align="center">
 <img alt="image" src="https://user-images.githubusercontent.com/69139386/185231491-edf27cd4-35fe-4ed7-9d7b-7b4040b9c65a.png">
</p> 


### GRU inference:

<p align="center">
 <img alt="image" src="https://user-images.githubusercontent.com/69139386/185231713-15e5723b-748a-4f21-9358-c839814ad510.png">
</p> 


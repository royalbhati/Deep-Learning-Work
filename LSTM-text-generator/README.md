# LSTM Text Generation

This project allows you to train a Long Short-Term Memory neural network to generate text using any TXT file that contains more than 100 characters

## Training

To train the network you run **lstm.py**.

E.g.

```
python lstm.py file-name.txt

python lstm.py r.txt
```

Where:

* **file-name** is the name of the file you want to train on

The network will train for specified epochs which you can change according to you. 

Weights will be saved for every epoch.

## Generating text

Once you have trained the network you can generate text using **predict.py**

E.g.

```
python predict.py file-name no-of-words weights-file

python predict.py r.txt 120 weights-improvement-02-3.2945-bigger.hdf5
```


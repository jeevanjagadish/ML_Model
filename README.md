# ML_Model
Model Prediction: Text generation using a RNN with eager execution



QUEEN ELIZABETH:
But how long have I heard the soul for this world,
And show his hands of life be proved to stand.

PETRUCHIO:
I say he look'd on, if I must be content
To stay him from the fatal of our country's bliss.
His lordship pluck'd from this sentence then for prey,
And then let us twain, being the moon,
were she such a case as fills m

While some of the sentences are grammatical, most do not make sense. The model has not learned the meaning of words, but consider:

The model is character-based. When training started, the model did not know how to spell an English word, or that words were even a unit of text.

The structure of the output resembles a play—blocks of text generally begin with a speaker name, in all capital letters similar to the dataset.

As demonstrated below, the model is trained on small batches of text (100 characters each), and is still able to generate a longer sequence of text with coherent structure.

![Alt text](https://github.com/jeevanjagadish/ML_Model/blob/main/5cec08e9-6a90-4a56-bc47-eaff9bf069d9.png)

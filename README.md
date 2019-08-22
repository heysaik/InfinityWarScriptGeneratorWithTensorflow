# Infinity War Screenplay with Tensorflow
Generates a script for Infinity War (Part 2) by training a RNN on all the scripts of the previous Marvel Cinematic Movies. Built with Python and Tensorflow

![Infinity War](http://cdn.collider.com/wp-content/uploads/2018/04/avengers-infinity-war-imax-social.jpeg "Infinity War")

The basis of this project comes from Martin Gorner, I just added a small portion to it.
Original project: https://github.com/martin-gorner/tensorflow-rnn-shakespeare

Code for the Recurrent Neural Network in the presentation "Tensorflow and deep learning - without a PhD, Part 2" from Google. 
The presentation itself is available here:

* [Video](https://t.co/cIePWmdxVE)
* [Slides](https://goo.gl/jrd7AR)

## Usage

```
> python3 rnn_train.py
```
The script **rnn_train.py** trains a language model on the complete works of William Shakespeare.
This takes hours, so be careful!
Please make sure you redownload the checkpoint files if you don't want to train the model first.

```
> python3 rnn_play.py
``` 
   
The script **rnn_play.py** uses a trained checkpoint to generate a new Marvel Movie script. 
You can see the output in the terminal as well as in the file "output_generated.txt"
Have fun!


## Some lines from the generated script
```
And I'm saying that I'll be the bast on the stone with you.
I was the problem was a counter on a could on this.
I wanted to know what I can tell
me a big bat stop.
I can't be a little one of the world.
I won't know what I'm saying.
I want to go to be to the back.
I'll be a book of the wark.
I would be to take a bit on the word.
I was to get the book.
I can't be this thing is a bot on a company.
That's where you can to the section of the world.
I can see the world with the bost.
I can't be a book and I wouldn't help you a country and the come of the senter.
That was a book and a lot of the stran.
Tony Stone the world was a countron of the way.
I can't be a little bat on the way.
It's a bot a bottle of all the story.
And I'm a serions are a creace and thing it is a bit on the way.
And I want to be the way.
I can see you.
And I'm a complete to this point.
Tony Stark and then when I was the world of the world.
```

## Modifications
You can modify this program to suit your own needs. Simply change the text files in the `marvel` folder and enter the following lines into Terminal.

```
> python3 rnn_train.py
```


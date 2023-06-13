# Perceptrone-and-Adaline-Implementation-from-Scratch

Perceptrone and Adaptive Linear Neuron (Adaline) Implementation from Scratch

This project is inspired by section two of book: “Fundamentals of neural networks” (by Laurene V. Fausett
) and aims to implement the basics of neural networks (NN) from the beginning, without using any libraries for creating built-in NN models. The project focuses on the implementation of Perceptron and Adaline from scratch, which is mainly about understanding the basement of a neural network and understanding the first models of feed-forward neural networks and how these models work in detail. This approach can be an effective way for a researcher to understand basic models with all the details. 

Model and Dataset:
The major goal of the model is to learn the pattern of a set of main characters {A,B,C,…,K} from a set of txt files. Each txt file is a simplified version of an image of a main character that consists of other representative characters. In the train dataset, representative characters are {.,#}). An instance of a train set could be like this:

######.
.#....#
.#....#
.#....#
.#####.
.#....#
.#....#
.#....#
######.

(If the above characters does not seem rational to you, copy on a txt file and split each seven characters with \n-enter or see the ReadMe on code tab)

Which represents character “B”. For the test set we have the same but with some noises, thus, each main characters represented by {.,#,@,O}. The {O, @} in this set represents the noises. Generally, each data is a text file consists of 7*9 characters (with mentioned characters for train and test set) that represent a main character (from A to K.) The final goal of model is to classify main characters by learning from representative characters.

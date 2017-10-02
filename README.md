# Adding 2 numbers by using deeping learning
Adding 2 numbers as a regression problem is fairly simple. But what will happen if we treat it as a classification problem?

Given that, the inputs are in the range [0,100], there will be 201 possible outputs. If we remove number 50 from the training dataset, can we predict the correct result with 50 as the input(s)?

In this project, I achieved 94% accuracy on the training dataset, almost 100% accuracy on testing dataset. Well, the training cost is a little high, a medium GPU EC2 instance spent about 1.5 hours on the training.

The result can defintely improve further with techniques that maybe we can convert the input to binaries instead of just normalize it. Mostly important, this project is really fun!

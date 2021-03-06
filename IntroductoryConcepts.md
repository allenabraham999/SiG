### Understanding Artificial Intelligence
This material is intended to give you an understanding of some of the basic ideas in artificial intelligence - 
specifically, machine learning, deep learning, and AI alignment. To that end, it is divided into four parts, each 
intended to give you a foundation in a different learning area. If one part is too boring for you or another is too 
technical, that's cool - the different parts are for covering different grounds, and if you find even one interesting, 
you'll know what you like.

**Part 1** is to give you an intuitive understanding of the fundamental idea that started machine learning and deep 
learning, as well as an introductory dive into what AI alignment is, and why it's necessary.

This part is meant to give you enough of a conceptual base to not be entirely lost when you move further into 
programming or theory.

### Introduction to AI
Artificial Intelligence is a technique of developing intelligent machines that can think and act as humans do. They are 
machines that can make smart decisions, have visual perception enabling them to see and understand from images and videos, can read the text and understand their content, talk and interact, and translate between languages.

Now the question is how does a machine learn and gain intelligence to perform such tasks?

In earlier days, we used to program logic explicitly that enables machines to make decisions. But modern-day artificial 
intelligence is about machines gaining intelligence by learning from ‘experience’! Let us simplify this for you. Just 
like we learn things from examples, we’ll let computers learn from examples. Essentially, we provide data to the machines 
and ask them to learn from it. We call this process “training” which enables machines to learn from the data and gain 
enough experience. For instance, one of the most interesting domains of AI is computer vision, where machines are trained 
to perform different tasks on visual applications. This could be to identify faces in an image, recognize a famous 
person, identify objects in an image, or track certain objects in a video. In such applications, the data we feed the 
machine for training are images.

### The Tools of Artificial Intelligence
Intelligence is the use of information and logic to solve problems and learn new things. How exactly you do that, is a question with many answers, which is why you might have heard of machine learning, deep learning, and many others.

All of them achieve the same basic goal - making a computer learn how to solve problems - through very different methods. Here, we'll look at what those methods are, and what we can do with them.

* Machine Learning (ML) is the process by which a computer learns and improves from experience, to make predictions or 
decisions, without being explicitly told how to.

* Deep Learning (DL) is the process by which a computer learns through representing data in the form of increasingly 
simplified levels. Does that sound confusing? Don't worry, it'll make sense when it's explained. DL is technically a 
section of ML, but it's grown so large in itself that it's worth mentioning separately.

## Introduction to Machine Learning
Machine Learning comprises a large group of methods by which a computer can learn from data, so here, we'll look at what those methods are doing.

#### Regression And Classification.
The main difference between Regression and Classification algorithms that Regression algorithms are used to predict the continuous values such as price, salary, age, etc. and Classification algorithms are used to predict/Classify the discrete values such as Male or Female, True or False, Spam or Not Spam, etc.

  ##### Classification
   Classification is a process of finding a function which helps in dividing the dataset into classes based on different parameters. In Classification, a computer program is        trained on the training dataset and based on that training, it categorizes the data into different classes.

   The task of the classification algorithm is to find the mapping function to map the input(x) to the discrete output(y).

   Example: The best example to understand the Classification problem is Email Spam Detection. The model is trained on the basis of millions of emails on different parameters,      and whenever it receives a new email, it identifies whether the email is spam or not. If the email is spam, then it is moved to the Spam folder.
  ##### Regression
   Regression is a process of finding the correlations between dependent and independent variables. It helps in predicting the continuous variables such as prediction of Market    Trends, prediction of House prices, etc.

   The task of the Regression algorithm is to find the mapping function to map the input variable(x) to the continuous output variable(y).

   Example: Suppose we want to do weather forecasting, so for this, we will use the Regression algorithm. In weather prediction, the model is trained on the past data, and once    the training is completed, it can easily predict the weather for future days.
***
 At its core, ML is about using algorithms to analyze and predict patterns in data. If a computer is given a set of data about the heights and weights of different people, and    we want to use that to predict someone's height using just their weight, then we train the computer on the data we do have, so that it can have a decent understanding of the    correlation between height and weight. How does it do that?

The answer is Math.

The math is simple at the core. You take a graph of variables and plot a line connecting the points on it. Look at this 
graph, for instance:

![Data Points](https://imgur.com/4qYPbMS.png)   
If you wanted to predict what Y would be for a new value of X, how would you do it?

![Linear Regression](https://imgur.com/coTdD88.png)  
For doing that, you should draw a straight line roughly connecting all the points, and then look at what Y the new X would give on that line, and you can see it comes pretty close to the actual answer (marked with the orange dashed lines).

That is the basic idea of Machine Learning. You give the computer a lot of data like this, and it "understands" it by finding patterns in them.

##### So when does it get more complicated?
You might have noticed that the predicted value of Y isn't *exactly* the same as the actual value. Now, if we need a more 
accurate value, we will have to construct a graph with more complex patterns and the position of individual data points 
will influence our result, which makes the precision more complicated. That is where Machine Learning shows its real colour!

#### Supervised And Unsupervised Learning.
##### Supervised 
Supervised learning as the name indicates the presence of a supervisor as a teacher. Basically supervised learning is a learning in which we teach or train the machine using data which is well labeled that means some data is already tagged with the correct answer. After that, the machine is provided with a new set of examples(data) so that supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labeled data.

##### Unsupervised
Unsupervised learning is the training of machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance. Here the task of machine is to group unsorted information according to similarities, patterns and differences without any prior training of data. 

Unlike supervised learning, no teacher is provided that means no training will be given to the machine. Therefore machine is restricted to find the hidden structure in unlabeled data by our-self. 

For instance, suppose it is given an image having both dogs and cats which have not seen ever. 
Thus the machine has no idea about the features of dogs and cat so we can’t categorize it in dogs and cats. But it can categorize them according to their similarities, patterns, and differences i.e., we can easily categorize the above picture into two parts. First first may contain all pics having dogs in it and second part may contain all pics having cats in it. Here you didn’t learn anything before, means no training data or examples. 

 It allows the model to work on its own to discover patterns and information that was previously undetected. It mainly deals with unlabelled data.

Unsupervised learning classified into two categories of algorithms: 
 

* Clustering: A clustering problem is where you want to discover the inherent groupings in the data, such as grouping customers by purchasing behavior.
* Association: An association rule learning problem is where you want to discover rules that describe large portions of your data, such as people that buy X also tend to buy Y.



#### BIAS AND VARIANCE
##### BIAS
Bias is the difference between the average prediction of our model and the correct value which we are trying to predict. Model with high bias pays very little attention to the training data and oversimplifies the model. It always leads to high error on training and test data.
##### VARIANCE
Variance is the variability of model prediction for a given data point or a value which tells us spread of our data. Model with high variance pays a lot of attention to training data and does not generalize on the data which it hasn’t seen before. As a result, such models perform very well on training data but has high error rates on test data.



#### In the Real World
Of course, in real-world situations, there are way more than 2 variables. The complexity of ML, and the reason it's still growing as a field, is because computer models are growing ever larger and that complexity is what gives us new features every day.

### Introduction to Deep Learning
How would you teach a baby what a "dog" is? I doubt you'd get very far trying to explain to them all the features of a dog, and expecting them to understand. No, you'd point to a dog, and say "That's a dog". Now the baby associates the visual input it gets in that moment with the word "dog". As they grow up and learn that more types of breeds are also called "dogs", their idea of what a dog is becoming more general - they learn to pick up on the unique traits that make up a dog purely from the experience of associating certain things like dogs.

That's the idea behind deep learning. When machine learning first came to the mainstream, it was amazing. It was powerful, and it got great results. But people saw that it didn't quite work as human minds do. Hence, the development of this field, where you teach a computer to associate certain characteristics with a concept through simplifying visual data into simpler forms like you'd simplify the sight of an animal into characteristics such as "four legs", "tail", "dull claws", and simplify those further into "dog".

Look at these two pictures. One contains just one section of solid colour, and the other contains a black section and a white section separated by an invisible line.

|Picture 1|Picture 2|
|---------|---------|
|![Black](https://imgur.com/wkirAQp.png)|![Line](https://imgur.com/FhCvjVe.png)|

Now, how would you make a computer recognize that one has a line and the other doesn't? Well, the images can be represented as:

|Picture 1|Picture 2|
|---------|---------|
|<table> <td>1</td><td>1</td><tr><td>1</td><td>1</td></tr> </table> | <table> <tr><td>1</td><td>1</td></tr><tr><td>0</td><td>0</td></tr> </table>|

Where 1 stand for a black pixel, and 0 for a white pixel. 

Now take this new set of numbers:

|       |         |
|-------|---------|
|100|100|
|-100|-100|

If you simply multiply every number in this new table with the numbers we got from each image, what would we get?

Don't worry, you don't have to think about the math if you don't want to. 
The first picture: 100\*1 + 100\*1 - 100\*1 - 100\*1 = 0   
The second picture: 100\*1 + 100\*1 - 100\*0 - 100\*0 = 200

So, the computer can use this table of numbers and receive a large number for horizontal lines in an image, thus identifying them. In an image with many pixels, this sort of operation is performed on every small set of pixels (like the 2x2 squares we are looking at), and a smaller matrix is obtained from the operation, as every set is reduced to one number each. For example, if the second picture above were part of a larger image, this operation performed on the image would result in that portion reducing from the 2x2 matrix above to the number 200.

If we used a different set of numbers for the operation, say:

|      |        |
|------|--------|
|100|-100|
|100|-100|
Then this operation would identify vertical lines in an image. Like these, deep learning algorithms have many sets of numbers to identify very basic patterns in images.

This kind of operation is called a ​**convolution**​ or a​ **filter**​, used in one of the most popular forms of deep learning, convolutional neural networks (CNNs). In other words, a convolution is an operation done on an image to simplify it into more familiar concepts such as "horizontal line" or "circle" or the like.

When many convolutions like these are stacked together, a computer can, from a group of pixels, understand the presence of complicated images like a vehicle, or a person. This cascading series of convolutions form what's known as a neural net.





#### Other Applications
Imagine if you could apply this principle to a video game. The computer would read the image on the screen, identify obstacles and enemies, and choose movements and actions to optimize its position almost perfectly, at every frame.

A relatively simple example would be Flappy Bird. We all love that game, don't we? A neural network trained to play Flappy Bird, would at first choose entirely random moves, then notice that if it chose to jump when a certain object moved into a certain position of the screen (such as a pipe moving close to you), it would get a higher score. So that object is included in its network, associated with the "jump" option. As the game keeps on training, it gets better and better at identifying ideal times to jump to increase the score. Some models that were trained like this kept on playing forever because it was now too good to lose.

#### In the Real World
Real-world deep learning models have many convolutions stacked together to be able to identify things with better accuracy and efficiency. That face recognition feature on your phone is a deep learning model, trained to recognize human faces. The voice assistant on your phone translates your voice into text with deep learning models.

#### How do I actually use this stuff?
Training and using machine learning and deep learning models is surprisingly easy, and indeed, is nothing more than a few lines of Python code that uses complicated packages that we thankfully don't have to learn anything about. For now, let's look at something I think is slightly more interesting.

#### AI Alignment
When I say an AI ‘S’ is aligned with an operator ‘H’, I mean: S is trying to do what H wants it to do.

The world is not far away from creating one super-intelligent machine which will lead us to the point where we no longer need any more machines. It can do whatever we want it to do! Isn’t it great? But there is a slight problem, the level of AI alignment is about doing things we want, it can either fail or succeed in that mission just like humans, but there is a chance of serious damage in the process. Let me explain that to you with an example.

Imagine you have a super-intelligent car and you asked it to get you to a place at a specified time. The car will try everything in its power to get you there at the time you said, it doesn’t matter how many accidents it causes or rules violated!

This is just an example and it is never going to happen because autonomous cars will be way more careful with traffic rules and the safety of you and others. But the problem is that at some point, the technology will reach the state where it can alter itself, or create new machines smarter than it. This is inevitable in the future of AI research. AI is much faster and more powerful than we are and it can achieve in seconds what we could only in years (This point, if you're interested to know more, is called the Singularity). Once we reach the point of the super-intelligent system, we cannot further research AI safety, because we would already be past the stage where it could have saved us.

The two fundamental problems features of any super-intelligence that lead to failure in commonly suggested methods for Friendly AI are:

* **Power** : The AI is far more powerful than we can even comprehend, and can thus achieve its goals with far more efficient methods than we could dream of. This means that we cannot possibly try to plan for what an AI might do.
* **Literalness** : The AI only cares about the task given to it, not the mindset behind that task. If it's told to cure cancer, it wouldn't understand that what we really mean is the well-being of humanity, it would just enslave humanity to test on and find a cure better.









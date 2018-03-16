# hello-world
About me, Ideas, and Other Spontaneous Stuff

I am an aspiring AI system expert, aficionado of mathematics, with a background in Electical Engineering, mostly just signal processing and communication systems. I think of intelligent behavior as the ultimate form of signal processing and seek to understand how it is developed. My goal is to get started with non-trivial projects that utilizes existing successful techniques.

One idea I had for a while is to build an AI system to do pure math. The scope of the project is yet to be determined. The questions I am currently asking myself include:

what is the definition of "doing math"?
What are the inputs and output of the system?
If my desired output is a valid proof of the Divergence the of Harmonic Series, what kind of training data do I need to provide?
What type of architecture can I use to build a system that can generalize and explore new concepts?
Will such a system eventually be able to solve an open problem such as the Riemann Hypothesis?

One thing I do recognize is that math has many different sub-fields that deal with very different postulates and objects. But I can start with something simple.

If you already have an ongoing project that might fit my interests, please let me know!! I'd love to participate in more knowledgeable groups and talk to others about cool ideas.


Update 1 (March 2018):

It has been a while since I created this GitHub account and kind of forgot about it ever since. 

I have been studying classic machine learning and deep learning, and read a lot about AI in general. Meanwhile I really practiced my programming skills, in particular the ability to create standalone projects by utilising documentations and open-source libraries.

I learned how to implement linear and logistic regression algorithms, using gradient descent to optimize the loss functions. Also I learned the kernel trick of SVM, but concluded SVM is a version of what hidden layers of neural networks can do. Ian Goodfellow's book on deep learning presents a really coherent framework to understand machine learning in terms of probability distributions. If regularizers encode prior beliefs about the probability distributions we want a system to learn, maybe it's the key to solving the AI alignment problem. If future AI systems reach human level of generalization with deep learning, then performance is no longer the problem. In fact, by forcing AI systems to align with human interests, we are necessarily punishing its performance. In this sense, regularizers can be used to force AI systems to find the best solutions that humans find desirable. Current systems are not good enough to warrant such measures, but the considering the amount of money being thrown at solving AI and how fast the field the growing, we should err on the side of caution by starting early. In fact, I can make a good argument for that:

Start with two simple assumptions, 1. The probability that the first AGI is aligned with humanity is very small, since the set of motives that are aligned with human interests is a miniscule fraction of all the possible motives an agent might have. 2. If we know how to build safe AGI, then the first AGI is very likely to be aligned with us:

	  P(first AGI is safe|we know how to build safe AGI)
	
	= P(first AGI is safe AND we know how to build safe AGI)/P(we know how to build safe AGI) = alpha (close to 1)

	< P(first AGI is safe)/P(we know how to build safe AGI)

which means

	P(we know how to build safe AGI)*alpha < P(first AGI is safe) = very small
  
The unconditional probablity of humanity ever knowing how to build AGI safely is very small, which also means that the problem of build AGI safely is VERY difficult.

Right now with deep learning, I don't have a good enough computer to use the available training data sets out there. All I manage to do was training a small network to learn simple non-linear functions. Really hope I get to work on solving more interesting problems someday.

My most recent coding project in a GUI based Java program called Productivity Monitor. The motivation was to make big improvements in my time management. Perhaps is software out there that does exactly that, but I want a free custom-tailored program and the coding practice. The program was designed to record how I spend my time every day, keep track of the status and progress of ongoing tasks, generate and display analytics such as the change of productivity over time. Even if I only manage to do a little better than last week, a strictly increasing curve would still saturate at 100%. So far I have designed the interface for user registration/login, wrote most of the behind-the-scene classes that should make the program work, figured out how to store account data and user data in .xml format and how to retrieve the data for analytics. It even has a feature that displays a random motivational quote. When I finish it I think I'll release the binary for free.

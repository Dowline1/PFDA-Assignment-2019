# PFDA-Assignment-2019
Git repository for Assignment 2019 for module Programming for Data Analysis, investigation in Numpy random number generator. References for Readme.md will be found at the end of the document, references on any code being used will all be referenced as they are used within the Jupyter Notebook.

## Introduciton
### History of Random Numbers
Statistician Francis Galton wrote in his publicaiton of Nature back in the 1890's that “As an instrument for selecting at random, I have found nothing superior to dice,”. Having the ability to on demand create numbers that are distributed in a desired fashion would reduce the time taken up by sampling as you could generate your own with the click of a button. The kind of number generation required to lend itself to more complex statistical analysis for example efficacy of a drug to treat a certain indication or determining the clinical trial size to determine this efficacy could not be generated from a simple roll of the dice unfortunately.


Post Francis Galton's publicaiton on the humble dice however in the mid 1940's the world took a step closer to modern times afirming that more random numbers where required that as mentioned already that the humble dice could not generate. RAND corporation came about with it's machine of the future the random pulse generator which was run for a period of time with results published in there book titled "A Million Random Digits with 100,000 Normal Deviates". What would now seem like a very strange undertaking was back then considered a breakthrough as for the first time there was a sequesnce of high quality random numbers to draw upon for those in need of such.


The Ferranti MK 1 was the first real computer that came pre-built with a random number instruction that generated 20 random bits at a time using electrical noise. This feature was implemented and designed by Alan Turing. The instructions however infuriated programmers at the time as it created to much uncertainty as it was impossible to test with programs as the numbers generated could no create data that demonstrated repeatability.


### Random Number Applications
Random Numbers are generally reffered to in field of staistics whereby they are utilised as a comparisson sample on a general study sample. A feature of random numbers that most individuals may not be aware of is that they need to have certain characteristics in order to be used correctly. These properties include the distribution of the numbers, as once there is an understanding of how the numbers are distributed for example a normal distribution, we can then use this understanding to generate our random numbers to aid in the study we are undertaking.



In this example as reffered to below in the references section the author refers to the life time of tube lights which in itself possess a Gaussian property (symmetric bell shape curve distribution) allowing the funciton to be used to represent the probability density of a normally distributed random variable. Knowing that the life time of these bulbs is normally distributed we can generate our random numbers with a normal distribution to be used as sample data for the study for a sufficiently size sample of say 1,000 bulbs.


The sample data can then be used as a simulation of the data to help determine many charteristics of the life time of the bulbs such as average life time and so on and so fortht that can be used in say the marketing of the bulbs for sale without the cost of using and testing actual bulbs in the data gathering phase of the study. This particular method of analysis is known as the Monte Carlo Method coined by John Von Newman in the 1940's.


There are several different types of variable distribution, in this assignment I will try to explain and represent 5 different kinds of variable distributions and there random number generation using Numpy's .random function.







## Analysis


## Conclusion


## References
- History of Random Numbers [link](https://www.freecodecamp.org/news/a-brief-history-of-random-numbers-9498737f5b6c/)
- Random Number Applications [link](https://analyticstraining.com/random-numbers-applications/)
- Gaussian Property [link](http://users.isr.ist.utl.pt/~mir/pub/probability.pdf)

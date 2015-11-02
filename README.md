### Dear folks at The Data Incubator:


### This challenge process was a blast, and I appreciate the opportunity to be a part of it!

***

Here you will find some scripts that I used to solve the first set of challenge questions.  **I recommend viewing them with IPython Notebook**, or alternateively, you can simply view the code and execute in an IPython environment.

In order to solve for the random walk questions, I imagined what I knew about other random walk scenarios.  I recalled a [story](https://en.wikipedia.org/wiki/Monte_carlo_simulation#History) from the scientists at Los Alamos National Laboratory, and decided a Monte Carlo simulation was a workable idea.


####1. createTheData.ipynb

   This script generates a JSON file which contains the random walks.  I found that random.randint() was significantly less random than random.choice('True','False').

####2. siftAndPlot.ipynb

   I wrote this code to assess my 'random' data and to make sure it simulated what I wanted it to simulate.

####3. calculations.ipynb

   This IPython Notebook contains the expressions that I used to find my actual responses.

***

**NOTE:** Due to the limitations of my laptop, I ran this simulation for 500k trials.  However, this test can be done with many more data points.

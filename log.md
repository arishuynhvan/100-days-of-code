# 100 Days Of Code - Log

### Day 0: 10th May 2019

**Background:** 

I failed this quest back in 2017, but I am determined to finish it this time. The main cause was the lack of focus and numerous distractions from new and exciting technologies. 

I believe such failures are crucial to both my personal and career development despite the pain and costs. Given new understanding about my own strengths and weaknesses, I structure this new quest to focus only a single language and domain. 

Finally, I will acknowledge even the time spent on installing software, since it's often much longer than coding time. It's unproductive, but still part of the learning experience and should be documented.

I must learn to document more quickly and efficiently, but must count such time into this quest to prevent burn-outs and self-blame. 

To balance between learning and health, I commit up to 9 hours/day for this quest. While it's recommended that I have to code 1 hour/day at the minimum, literature review, source code exploration, unforseen technical issues and documentation will all require time and effort. Working for 10 hours/day every day will not be sustainable. 

Thus, I won't let the lack of coding time shame me into failing at the start any more. I will acknowledge my learning effort and treat myself for any milestone because I deserve it.

**Goals:**
Reach intermediate - advanced level of scientific computing using C++

**Priority:**
1. Implement sensitivity analysis libraries for parameters in C++ with minimal dependency
2. Explore & contribute to [Shogun ML](https://github.com/shogun-toolbox/shogun/tree/shogun_6.1.3) 
3. Master common algorithms in C++ 

**Weekend Adventure:**

Sat & Sun are for exploring other technical stacks to stimulate new ideas, challenge my comfort zone, and prepare for a career in my dream field, neuroengineering.

1. Android Development & contribute to [Neurolab](https://github.com/fossasia/neurolab-android)

OR

2. Learn [Analysis of Neural Time Series Data](https://mitpress.mit.edu/books/analyzing-neural-time-series-data) through the author's [lecturelets](http://mikexcohen.com/lectures.html) and [Udemy course](https://www.udemy.com/share/100P9iB0oTeV1WQw==/)

### Day 1: 10th May 2019 

**Today's Progress:** 

I was reading [SALib](https://github.com/SALib/SALib),  its [tutorial](https://github.com/SALib/SATut), and[GSA Module](https://github.com/damar-wicaksono/gsa-module) to understand how Morris's Method should be implemented. 

**Thoughts:** 

The problem is that parameters and independent variables are all treated as inputs in this implementation, but the models I'm dealing with draw a clear distinction. The input type expected for parameters is a 1D array of doubles, with a fixed value for each parameter, while a 2D array is expected for the independent variable. 

Most open source libraries for SA were written in Python or R, so I'm converting them into pseudocode. Trying to understand the examples is quite hard as well since there are often too many parameters without a mathematic representation. I'll trace each line to formulate for my own understanding. Also, I'll probably fork the tutorial repo and offer a PR once I can understand what was going on there. 

I minimized the usage of negative words (1).

**Tomorrow's plan:** 

- [X] Continue to convert SA libraries in Python to pseudocode

- [X] Continue to formulate the models in the examples of the tutorials 

- [ ] Explore if CI/CD is possible without authorization requirement (most likely no... bc Codedacy isn't free for private repo, but Jenkins or TravisCI may provide an option).*

- [ ] Move the content to blog bc this log file is getting too long just by the 1st day.*

_* optional_

**Link to work:** 

[insert the commit number](), but it's not accessible at the moment due to private setting.

**Resources:**
- [SALib](https://github.com/SALib/SALib)
- [SALib tutorial](https://github.com/SALib/SATut)
- [GSA Module](https://github.com/damar-wicaksono/gsa-module)
- [GSA doc](https://gsa-module.readthedocs.io/en/stable/implementation/morris_screening_method.html#)
- [SAFE Toolbox](https://www.sciencedirect.com/science/article/pii/S1364815215001188)
- [Function Pointer C++](https://www.cprogramming.com/tutorial/function-pointers.html)
- [Void Pointer C++](https://www.learncpp.com/cpp-tutorial/613-void-pointers/)
- [Checkbox for Github Markdown](https://help.github.com/en/articles/about-task-lists)
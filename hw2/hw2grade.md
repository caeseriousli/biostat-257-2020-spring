*Caesar Li*

### Overall Grade: 109/110

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline?

    - Yes. `Fri May 1 22:11:48`

* Is the final report in a human readable format html?  
	
    - Yes.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?
    
    - Yes.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?
    
    - Yes.


### Correctness and efficiency of solution: 99/100

* Q1 (10/10 pts)

* Q2 
	
* Q3 (15/15 pts)

* Q4 (30/30 pts)

    - You call `cholesky!` on `obs.storage_qq` several times. This really only needs to happen once. Since `obs.storage_qq` is small, its not very expensive, but this can be problematic if `q` is large.

* Q5 (29/30 pts)

* Q6 (15/15 pts) 

    - See below.


### Usage of Git: 5/5

* Is the hw submission put into the `master` branch?

    - Yes.

* Are there enough commits? Are commit messages clear? 

    - Yes.

* Is the hw2 submission tagged?

    - Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly?

    - Yes.

* Do not put a lot auxillary files into version control.  
    
    - Yes.

### Reproducibility: 5/5

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

    - Yes.

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

    - Yes.


### Julia code style: 5/5

* Rule (4): 4 spaces for indenting. 
    
* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. 

* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them.

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.

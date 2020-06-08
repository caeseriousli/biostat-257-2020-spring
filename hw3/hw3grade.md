*Caesar Li*

### Overall Grade: 119/125

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline?

    - Yes. `Fri May 15 15:55:32`

* Is the final report in a human readable format html?
	
    - Yes.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?
    
    - Yes.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?
    
    - Yes.


### Correctness and efficiency of solution: 91/100

* Q1 (4/5 pts)

    - You wrote **P** = p **BA** + **c1**' / n. You don't need the extra division by n. This looks like a typo? `(-1 pt)`

* Q2 
	
* Q3 (10/10 pts)

* Q4 (5/5 pts) 

* Q5

    * Step 1 (13/15 pts)

        - In your (I - P) * v `mul!` function you have `out .= v .- M.storage_n1 - M.storage_n2`. You need to have `.-` on `M.storage_n1 - M.storage_n2` or else you'll allocate another vector of length n. `(-2 pts)`. It doesn't seem like your html was run all at once, because the memory allocation benchmark doesnt reflect this mistake.

    * Step 2 (20/20 pts)

    * Step 3 (20/20 pts)

        - Not sure why your functions are so slow on your machine. When run on my machine you get full points.

    * Step 4 (20/20 pts)

        - Not sure why your functions are so slow on your machine. When run on my machine you get full points.

* Q6 (2/5 pts)
    
    - You forgot to compare to the pages ranked by in-degree. `(-3 pts)`

* Q7


### Usage of Git: 5/5

* Is the hw submission put into the `master` branch?

    - Yes.

* Are there enough commits? Are commit messages clear? 

    - Yes.

* Is the hw3 submission tagged?

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

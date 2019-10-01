## Build & Deploy ML Models in the Cloud
## Rihad Variawa, Data Scientist
## FinTech Industries


**Motivation for this task**

- Solve a business problem
- Understand the end-to-end approach
- Build a data-driven Machine Learning application on the cloud

**Approach** to take a case-driven task to showcase this. We will aim to go-wide VS. go-deep. The approach will be both practical and scalable. Let's start by understanding the overall steps involved in building a data-driven application.


### Art of Data Science Process

![](static/datascience.png)

This task delves deep into the process and how this can be used to solve the problem end-to-end.


But before we get there, we need the repo - that has the data and code that we want to run in cloud.


The first step is to create a virtual environment. It's good practice to create a separate environment for each project.

    $ pip -h # check to see if your Python installation has pip. If you see the help text for pip, excellent
    $ pip install virtualenv
    $ cd loan-default
    $ virtualenv mlcloud # mlcloud is the name of the virtual environment

    $ source mlcloud/bin/activate # activate the virtual environment

Now, the required libraries need to be installed. The libraries needed for the task are listed at requirements.txt.

    $ pip install -r requirements.txt

Now, the virtual environment needs to be activated for `Jupyter Notebook`

    $ python -m ipykernel install --user --name=mlcloud


We are all set. Now, open the jupyter notebook by entering the URL provided in the welcome message, in the browser


Our 6 Step Problem Solving Roadmap


Gain the best results in solving complex and important problems. We-Do!

### Step 1: Identify the problem
At this stage, you are defining the scope of the problem you have to solve. Points to consider at this stage include: problem origin (if known), problem impact (e.g. on customers, on staff or reputation) and timeline to solve the problem.

Note: the time factor is important to consider because it influences how much time you can dedicate to thinking through the problem. In extreme conditions, you may run through this entire process in less than an hour.

### Step 2: Structure the problem
Putting the problem into a clear structure for analysis is one of the great insights we bring to our work. What does it mean to structure a problem? It means identifying the important issues.

### Step 3: Develop solutions
According to research by Chip and Dan Heath in their book “Decisive,” most managers develop only two solutions: “Do x or do not do X.” It will come as no surprise that this approach rarely delivers success. Binary choices tend to have a 50% or greater failure rate. On the other hand, fifty solutions is probably too many to handle especially if you are working through a problem solving process on your own.

The Solution Sweet Spot: developing three to five solutions is usually enough.

### Step 4: Select a solution to the problem
With a list of possible solutions on the table, it is now time to decide. 
Note: For large scale problem solving, you may have to follow an organizational template or policy if your solution requires a large amount of money.

### Step 5: Implement a solution
In this step, you put the solution into action. Implementation may become a project of its own. In that case, you have a full toolkit of project management tools and processes to call on.

Tip: If you are solving a novel problem, stay humble about your solution. It may not work or there may be a better way.

### Step 6: Monitor for success
Monitoring the solution and situation is a key step to ensure the problem is truly solved. Failing to follow up – especially if you have assigned the task to someone else – is a recipe for disaster. 

Monitoring is also important because problems are sometimes symptom of a deeper problem.

Tip: Increase the quantity and frequency of reporting when you are working through an important problem.




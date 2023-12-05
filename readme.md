
# Alzheimer disease detection project

# Libraries
```
random ->Used for generating random numbers.
math ->Used for mathematical operations, specifically the floor function.
numpy as np ->Used for working with arrays and mathematical operations on arrays.
```
# Variable Initialization:
```
run,Runs = 0,10
-> run is to start the loop from 0 and Runs is to run until the the loop goes to 10
best_val = np.zeros(Runs)
-> it create array
  [0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
```

# While loop
```
while run<Runs:
then it will run loop till 0<10
```

# default values
```
maxfes = 10000
dim = 30
pop_size = 10
max_iter = math.floor(10000/pop_size)
-> 1000
lb = -100*np.ones(dim)
->[-100. -100. -100. -100. -100. -100. -100. -100. -100. -100. -100. -100.
 -100. -100. -100. -100. -100. -100. -100. -100. -100. -100. -100. -100.
 -100. -100. -100. -100. -100. -100.
ub = 100*np.ones(dim)
->[100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100.
 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100. 100.
 100. 100.]


```
# define a function
```
 def fitness(particle):
```

# Default values
```
Positions = np.zeros((pop_size,dim)) #define variable with required size
best_pos = np.zeros(dim) #define population's best position with required size
worst_pos = np.zeros(dim) #population's worst position with required size
finval = np.zeros(max_iter) #store best value for each iteration
f1 = np.zeros(pop_size) #function value of current population
f2 = np.zeros(pop_size) #function value of updated population
```

#Login Crediential
```
username: admin
password: 123
```

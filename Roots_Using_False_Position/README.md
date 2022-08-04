<h2><a href = "https://github.com/LavaHawk0123/Projects/tree/main/Finding%20a%20root%20of%20an%20equation%20using%20false%20positioning%20method"> Estimating roots of an equation using false postion method </a></h2>

```
git pull https://github.com/LavaHawk0123/Projects.git
cd Finding a root of an equation using false positioning method
python FalsePosition-final.py
```
Example Output : 
```
Enter coefficiant of x^3: 1
Enter coefficiant of x^2: 0
Enter coefficiant of x: -4
Enter constant value: -9
Enter coefficiant of cosx: 0
Enter coefficiant of sinx: 0
Enter coefficiant of tanx: 0
Enter tolerable error: 0.001

The Equation is f(x) = (1) x^3+ (0) x^2+ (-4) x+( -9)+ (0)cos(x)+ (0)sin(x)+ (0)tan(x)



Initial value of (a,b) = (2,3).
Initial value of f(2)= -9.0 and f(3)= 6.0

Iteration 1:	
value of f(a) and f(b) is f(2) = -9.0 and f(3) = 6.0
Value of x is 2.6 and f(x) = -1.824	
Since the value is lesser than 0, We replace the lower limit of the interval
Now, the roots lie between  (2.6,3).


Iteration 2:	
value of f(a) and f(b) is f(2.6) = -1.824 and f(3) = 6.0
Value of x is 2.69325153374 and f(x) = -0.237226510807	
Since the value is lesser than 0, We replace the lower limit of the interval
Now, the roots lie between  (2.69325153374,3).


Iteration 3:	
value of f(a) and f(b) is f(2.69325153374) = -0.237226510807 and f(3) = 6.0
Value of x is 2.70491839693 and f(x) = -0.0289121838676	
Since the value is lesser than 0, We replace the lower limit of the interval
Now, the roots lie between  (2.70491839693,3).


Iteration 4:	
value of f(a) and f(b) is f(2.70491839693) = -0.0289121838676 and f(3) = 6.0
Value of x is 2.70633348696 and f(x) = -0.00349541816072	
Since the value is lesser than 0, We replace the lower limit of the interval
Now, the roots lie between  (2.70633348696,3).


Iteration 5:	
value of f(a) and f(b) is f(2.70633348696) = -0.00349541816072 and f(3) = 6.0
Value of x is 2.70650446856 and f(x) = -0.000422175861667	


The root is : 2.70650446856
```

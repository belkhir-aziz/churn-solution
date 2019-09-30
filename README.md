# Churn-solution
This project provides a real solution for companies which suffer from the churn:Nowadays, many entrepreneurs have tended to use the ML model to detect client with bad behavior, in order to give them new offers and opportunities to convince not leaving. This act appears simple and worth it, but it can cost much resource without getting advantages. So choosing a good strategy to give offers is so important as it can lead to a successful process.

### Prerequisites
-machine learning model (tree solution)

-some basics of python
```
pandas library
```
The most importent issue to succesfuly upload this algorithm and to have a good result.You have to correctly evaluate 
features.
A company has to invest to improve customer behavior and each offer  has of course a cost.So in my case features are:

number-of-calls:the number of calls for a user
number-of-neighbors:other customer whom  the actuel customer communicate with
flag-data:is customer using data offers

![Capture](https://user-images.githubusercontent.com/54355576/65855632-56d57380-e357-11e9-9cec-53aa6b8462cc.PNG)

Remarques:
```
To increase number-of-calls with one unit company should invest 3$.
```
```
If increasing or decreasing such beahavior is impossible putting very high cost is worth it.
```
```
In the case of categorical variable. Put the cost of changing varaible's category in the increasing field.
```
## Running the tests
```
class SolutionTreeForChurner:
  def __init__(self,tree,guestCost,goal,feature_names)
```
This is the declaraiton of the class you are going to use and their essential attribute.
tree :is the model you are using to detect churner.
guestCost:is the data frame which we talk about earlier.
goal: is the class you want to reach in my case the target is flag-churn (flag-churn= 1:client who's going to quit ,0:client with good behaviors) so the goal=1

### Break down into end to end tests
the most important method is:
```
def bestPractice(self,users,budget)
```
input:  1-all users of the company 2-budget that the company planify to invest
output: the number of cutomers to protect with the budget given as input

### Tips for rigorous persons
This images can give an idea about how this algorithm work.But if you still wondering to know more contact me for more details




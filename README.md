## Optimization methods

This repo will contains the brief introduction to Optimization methods along with some solved examples using various Python libraries.

### Optimization method
Optimization is the process of finding the best result of a particular problem. Optimization methods are all those methods that are utilized to find the optimal/best result for that problem.
#### Optimization method types
Optimization methods can generally be classified into two types based on the constraint it is subjected to -
1. **Optimization with no constraints** - These types of methods deals with problem having the objective function only, which has to be optimized either to gets its maximum value or minimum value.
2. **Optimization with constraints** -These types of methods deals with the problems having objective function which is subjected to certain boundation or constraints to get the optimal value in those set of conditions.

Any optimization can be bounded or unbounded, bounded are those problems in which input (design) variables are restricted in a certain range.
Bounds differ from the constraints in the fact that, bounds acts on the input variables only, whereas constraints acts on the optimization function.  
_Both types of optimization methods have been shown with solved examples in python._

| Title                       | Description                                                  | Remark |
| --------------------------- | ------------------------------------------------------------ | ------ |
| 1_Using-fsolve              | The optimization is done using `fsolve` function of  `scipy ` library, here the derivative of the function is fed to find the stationary points, and on those points function value is evaluated. |        |
| 2_Using_Minimize            | The optimization is done using `minimze` function of  `scipy ` library, that is dedicated for the optimization problems. Here single and multi-variable function is fed directly with or without  derivative (Jacobian) and double derivate (double derivative). |        |
| 3_Using_MMA_solver          | Here predefined MMA solver (`MMA.py`) is used for finding the optimal value. Function along derivative and bounds is fed. |        |
| 4_Using_lagrange_multiplier | The constrained optimization problem is divided into unconstrained optimization problem through Lagrange multipliers, and is solved using different approaches. |        |
|                             |                                                              |        |


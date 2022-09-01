# Equations-Solver
Can beautify, simplify, and solve equations that are given as texts.
<br/><br/>


An example of a usage:

```python
# Beautifying an equation
BeautifiedEquationText = BeautifyEquationText("a*b/(a * (c / d / (a / b)) * b)")

# Simplifying an equation
SimplifiedEquationText = SimplifyEquationText("a*b/(a * (c / d / (a / b)) * b)")

# Solving an equation
Equation = CheckEquation("x^2 + 3*x + 2")
Solution = RunEquation(Equation, {'X': 5})
```

the "BeautifiedEquationText" variable will get "a * b / (a * (c / d / (a / b)) * b)".

The "SimplifiedEquationText" variable will get "a * d / (b * c)".

The "Solution" variable will get 42, which is the solution to this equation if X is set as 5.
<br/><br/>


Included the file "requirements_installation.bat" to install the packages from the requirements text file, from this other repo of mine:

https://github.com/xSpecialFoodx/Requirements-Manager

# OPTIMIZATION LECTURES - 150 MCQ QUESTIONS WITH SOLUTIONS

---

## LECTURE 1: INTRODUCTION & BASICS (Q1-Q40)

### Q1: Optimization can be defined as the process of finding:
A) Maximum value only
B) Minimum value only
C) Maximum or minimum value of a function
D) Average value of a function

**✓ Answer: C**
Optimization is the act of obtaining the best result (maximum or minimum value) of a function under given circumstances.

---

### Q2: If x* corresponds to the minimum value of f(x), then x* also corresponds to the maximum of:
A) f(x)/2
B) -f(x)
C) f(x) + c
D) c·f(x) where c > 0

**✓ Answer: B**
The maximum of -f(x) corresponds to the minimum of f(x). This allows converting maximization to minimization.

---

### Q3: Which operations on the objective function will NOT change the optimum solution x*?
A) Multiplication by negative constant
B) Multiplication by positive constant
C) Addition of constant
D) Both B and C

**✓ Answer: D**
Multiplying by positive c or adding constant c to f(x) preserves the location of optimum.

---

### Q4: Operations Research originated from:
A) Industrial manufacturing
B) World War II military problems
C) Early banking systems
D) Transportation planning

**✓ Answer: B**
OR began in World War II when British military needed to allocate scarce resources (aircraft, radar, submarines) efficiently.

---

### Q5: Linear Programming is a technique from which category of mathematical programming?
A) Calculus methods
B) Dynamic programming
C) Both A and B
D) Stochastic methods

**✓ Answer: A**
LP is classified under Calculus methods in the hierarchy of mathematical programming techniques.

---

### Q6: In optimization, design variables can be:
A) Only real numbers
B) Only integers
C) Real, discrete, binary, or integer types
D) Only binary values

**✓ Answer: C**
Design variables can take various forms: real numbers, discrete values, binary, or integers depending on problem requirements.

---

### Q7: Which of the following is NOT an example of an optimization problem from aerospace?
A) Minimum weight design
B) Optimal payload maximization
C) Cost minimization
D) Propellant fraction optimization

**✓ Answer: C**
Weight minimization and payload maximization are typical aerospace objectives; cost minimization is more manufacturing-focused.

---

### Q8: The standard form of optimization problem includes:
A) Only objective function
B) Objective function and equality constraints only
C) Objective function, equality, inequality constraints, and bounds
D) Only inequality constraints

**✓ Answer: C**
Complete optimization formulation includes objective f(x), inequality g(x)≤0, equality h(x)=0, and variable bounds.

---

### Q9: If a point satisfies all constraints and non-negativity restrictions, it is called:
A) An optimal point
B) A feasible point
C) A corner point
D) An infeasible point

**✓ Answer: B**
A feasible point is a solution that satisfies all constraints, including non-negativity restrictions.

---

### Q10: A linear programming problem is an optimization problem where:
A) Only objective function is linear
B) Objective and all constraints are linear
C) Constraints are linear but objective may be nonlinear
D) At least some variables are integers

**✓ Answer: B**
LP requires both the objective function and all constraints to be linear functions of variables.

---

### Q11: What is the main difference between bounded and unbounded feasible regions?
A) Bounded has more constraints
B) Bounded can be enclosed in circle; unbounded cannot
C) Unbounded always has no solution
D) Bounded means no variables are allowed

**✓ Answer: B**
Bounded region can be enclosed in a finite circle; unbounded extends to infinity.

---

### Q12: Modeling in optimization refers to:
A) Creating physical prototypes
B) Expressing problem observations in mathematical form
C) Running computer simulations
D) Collecting experimental data

**✓ Answer: B**
Modeling converts observations about a problem into mathematical form using functions and operations.

---

### Q13: Newton's Law of Cooling is represented as:
A) T = kT
B) dT/dt = -k(T - Ta)
C) T(t) = Ta + (T0 - Ta)e^(-kt)
D) Both B and C

**✓ Answer: D**
B is differential equation form; C is the closed-form solution. Both represent Newton's cooling law.

---

### Q14: In the diet problem example, the objective function is to:
A) Maximize nutritional value
B) Minimize cost while meeting nutritional requirements
C) Maximize food quantities
D) Minimize nutritional intake

**✓ Answer: B**
Diet problem formulation: minimize cost subject to nutritional constraints.

---

### Q15: A critical point occurs where the derivative is:
A) Positive
B) Negative
C) Zero or undefined
D) Greater than 1

**✓ Answer: C**
Critical points are where f'(x) = 0 or undefined - these are candidates for local and global optima.

---

### Q16: A local minimum is a point where:
A) f(x*) is smallest over entire domain
B) f(x*) ≤ f(x) for all x in neighborhood
C) f'(x*) > 0
D) f(x*) is average value

**✓ Answer: B**
Local minimum: f(x*) ≤ f(x) for all x with |x - x*| < δ.

---

### Q17: A strong (strict) local minimizer is:
A) Point with zero derivative
B) Point that uniquely minimizes f in neighborhood
C) Any local minimum
D) Always a global minimum

**✓ Answer: B**
Strict local min: f(x*) < f(x) whenever x* ≠ x and |x - x*| < δ.

---

### Q18: An inflection point is where:
A) First derivative is zero
B) Function has local minimum
C) Sign of second derivative changes
D) Function increases monotonically

**✓ Answer: C**
Inflection point: second derivative changes sign (f'' changes from positive to negative or vice versa).

---

### Q19: The derivative f'(x) represents:
A) The function value at x
B) The rate of change of f at x
C) The second derivative
D) The integral of f

**✓ Answer: B**
Derivative is the rate at which function value changes - it's the slope of tangent line at point x.

---

### Q20: The forward difference approximation of derivative is:
A) lim[h→0] [f(x-h) - f(x)]/h
B) lim[h→0] [f(x+h) - f(x)]/h
C) lim[h→0] [f(x+h/2) - f(x-h/2)]/h
D) [f(x) - 0]/x

**✓ Answer: B**
Forward difference: f'(x) = lim[h→0] [f(x+h) - f(x)]/h uses next point.

---

### Q21: Proportionality assumption in LP means:
A) All constraints are proportional
B) Contribution from each variable is proportional to its value
C) All variables must be equal
D) Objective function must be constant

**✓ Answer: B**
LP proportionality: contribution to objective from variable xi is proportional to value of xi.

---

### Q22: Divisibility assumption in LP requires:
A) Integer values only
B) Variables can take fractional values
C) Constraints must be divided
D) Objective divided equally

**✓ Answer: B**
Divisibility: decision variables can assume any fractional values.

---

### Q23: An integer programming problem occurs when:
A) All variables are continuous
B) Some/all variables must be non-negative integers
C) Only equality constraints exist
D) Objective is minimization

**✓ Answer: B**
Integer LP: one or more decision variables restricted to integer values.

---

### Q24: Certainty assumption means:
A) All constraints are certain to be satisfied
B) Solution is always feasible
C) All parameters (coefficients, RHS) known with certainty
D) Problem has unique solution

**✓ Answer: C**
Certainty: each LP parameter known with certainty (no uncertainty/risk).

---

### Q25: In the Furnco desk/chair problem, the constraint 'chairs ≥ 2×desks' represents:
A) Production constraint
B) Resource constraint
C) Marketing requirement
D) Cost constraint

**✓ Answer: C**
This is a marketing/sales constraint: at least twice as many chairs must be produced as desks.

---

### Q26: The optimal solution in LP occurs:
A) In interior of feasible region
B) At corner point(s) of feasible region
C) On constraint boundary
D) Outside feasible region

**✓ Answer: B**
Fundamental LP theorem: optimal solution occurs at one or more corner points (vertices).

---

### Q27: A linear function f(x1, x2, ..., xn) has form:
A) c1x1² + c2x2 + ...
B) c1x1 + c2x2 + ... + cnxn
C) x1·x2 + x3
D) sin(x1) + x2

**✓ Answer: B**
Linear function: weighted sum of variables with constant coefficients, no powers or products.

---

### Q28: A linear inequality constraint has form:
A) x1² + x2 ≤ 5
B) x1·x2 ≥ 10
C) a1x1 + a2x2 ≤ b (or ≥)
D) e^x1 ≤ 100

**✓ Answer: C**
Linear inequality: linear expression with ≤, ≥, or = relation (no nonlinear terms).

---

### Q29: Non-negativity constraints x ≥ 0 are included because:
A) Mathematically required
B) Make problem easier
C) Variables (items) cannot be negative in practice
D) Required by law

**✓ Answer: C**
Cannot produce -5 chairs or -10 units - quantities are non-negative by nature.

---

### Q30: Which is NOT a typical objective function in optimization problems?
A) Cost minimization
B) Profit maximization
C) Efficiency maximization
D) Variable duplication

**✓ Answer: D**
Typical objectives: minimize cost/weight, maximize profit/output/efficiency. Duplication is not.

---

### Q31: Design variables in optimization are also called:
A) Constraints
B) Parameters
C) Decision variables
D) Objective coefficients

**✓ Answer: C**
Design/decision variables are the quantities we choose to optimize.

---

### Q32: In constrained optimization, the set of all feasible solutions is called:
A) Corner region
B) Feasible region
C) Boundary
D) Optimal set

**✓ Answer: B**
Feasible region = collection of all points satisfying all constraints and non-negativity.

---

### Q33: An unconstrained optimization problem has:
A) No feasible region
B) No objective function
C) No constraints
D) No variables

**✓ Answer: C**
Unconstrained: only objective function, no constraints other than variable bounds.

---

### Q34: Optimization technique suitable for engineering design is:
A) Game theory only
B) Simulation only
C) Mathematical programming
D) Statistical methods only

**✓ Answer: C**
Mathematical programming techniques are suitable for engineering design optimization.

---

### Q35: A function f(x1, x2) = 2x1 + x2 is:
A) Nonlinear
B) Quadratic
C) Linear
D) Cubic

**✓ Answer: C**
Linear function: first-degree terms with constant coefficients.

---

### Q36: Multi-objective programming involves:
A) Single objective only
B) Two or more objectives simultaneously
C) Multiple constraints
D) Integer variables

**✓ Answer: B**
Multi-objective: optimize 2+ conflicting objectives.

---

### Q37: Dynamic programming is used for problems with:
A) Only linear constraints
B) Sequential decision structure
C) Continuous variables
D) Unique solutions

**✓ Answer: B**
Dynamic programming exploits sequential/recursive structure.

---

### Q38: Geometric programming solves problems with:
A) Linear objective
B) Monomial/polynomial terms
C) Integer constraints
D) No bounds

**✓ Answer: B**
Geometric programming: handles posynomial objective and constraints.

---

### Q39: The objective function in optimization is also called:
A) Constraint
B) Performance index
C) Variable
D) Feasible point

**✓ Answer: B**
Objective function / performance index: the function being optimized.

---

### Q40: Corner points of feasible region are also known as:
A) Edges
B) Vertices
C) Boundaries
D) Interior points

**✓ Answer: B**
Corner points = vertices of feasible region (where constraints intersect).

---

## LECTURE 2: LINEAR PROGRAMMING (Q41-Q90)

### Q41: Linear programming is concerned with finding:
A) Optimal value of linear objective only
B) Feasible region only
C) Optimal value of linear objective subject to linear constraints
D) All constraint intersections

**✓ Answer: C**
LP: find optimal value of linear objective function subject to linear constraints and non-negativity.

---

### Q42: The term 'programming' in LP refers to:
A) Computer programming
B) Linear functions only
C) Method of determining a program/plan
D) Scheduling only

**✓ Answer: C**
'Programming' = determining a specific program or plan of action.

---

### Q43: Which is NOT an application area of LP?
A) Production scheduling
B) Transportation
C) Portfolio analysis
D) Nonlinear curve fitting

**✓ Answer: D**
LP applications: scheduling, transportation, allocation. Curve fitting is nonlinear.

---

### Q44: Limited resources in LP context means:
A) No constraints
B) Only one constraint
C) Scarce labour, material, equipment, finance
D) No variables

**✓ Answer: C**
Essential LP condition: limited number of labor, materials, equipment, and finance.

---

### Q45: Homogeneity assumption in LP means:
A) All variables are equal
B) All constraints identical
C) Products, workers' efficiency, machines are identical
D) No diversity allowed

**✓ Answer: C**
Homogeneity: products/workers/machines assumed identical.

---

### Q46: The graphical method for LP requires:
A) Any number of variables
B) At most two variables
C) At least 3 variables
D) Integer variables

**✓ Answer: B**
Graphical method: feasible only for 2-variable problems (R² plane).

---

### Q47: In graphical LP solution, the feasible region is obtained by:
A) Plotting objective function
B) Plotting constraint boundaries and shading feasible areas
C) Finding corner points only
D) Solving system of equations

**✓ Answer: B**
Graphical method: plot each constraint as line, shade regions satisfying inequalities.

---

### Q48: For inequality x + y ≤ 20, the feasible region includes:
A) Only the line x + y = 20
B) Region below and on line
C) Region above the line
D) Only points on axes

**✓ Answer: B**
For ≤ inequality: region below line (including the line) is feasible.

---

### Q49: For inequality x + y ≥ 6, the feasible region includes:
A) Only the line x + y = 6
B) Region below the line
C) Region above and on line
D) Only origin

**✓ Answer: C**
For ≥ inequality: region above line (including the line) is feasible.

---

### Q50: The intersection point of two constraint lines is found by:
A) Adding the equations
B) Solving system of two equations
C) Graphical approximation
D) Using calculus

**✓ Answer: B**
Corner point: solve 2×2 system of equations formed by two intersecting constraint lines.

---

### Q51: In LP, the objective function is evaluated at:
A) All interior points
B) Random points only
C) All corner points of feasible region
D) Origin only

**✓ Answer: C**
Optimal LP solution occurs at corner point(s). Evaluate objective at each corner.

---

### Q52: A unique optimal solution in LP occurs at:
A) Multiple corner points equally
B) Single corner point
C) Interior point
D) Unbounded point

**✓ Answer: B**
Unique optimal solution: occurs at single corner point with distinct objective value.

---

### Q53: Multiple optimal solutions in LP occur when:
A) No feasible region exists
B) Objective function is parallel to constraint edge
C) Problem is unbounded
D) Constraints contradict

**✓ Answer: B**
Multiple optima: objective function parallel to constraint edge.

---

### Q54: An infeasible LP problem occurs when:
A) Objective value is infinity
B) Constraints are contradictory (no feasible region)
C) All solutions are identical
D) Only one variable exists

**✓ Answer: B**
Infeasible: no point satisfies all constraints simultaneously.

---

### Q55: An unbounded LP problem occurs when:
A) More variables than constraints
B) Variables can become arbitrarily large without violating constraints
C) Solution is always feasible
D) Only equality constraints

**✓ Answer: B**
Unbounded (maximization): objective can increase indefinitely while remaining feasible.

---

### Q56: The Simplex method can solve LP problems with:
A) Only 2 variables
B) Any number of variables
C) Integer variables only
D) Nonlinear constraints

**✓ Answer: B**
Simplex method: algebraic algorithm handling any number of variables.

---

### Q57: In the example Max Z = 4x + 5y subject to x + y ≤ 20, 3x + 4y ≤ 72, the corner points are:
A) (0,0), (20,0), (0,18)
B) (0,0), (20,0), (0,20), (8,12)
C) Only (20,20)
D) (0,0), (24,0), (0,18)

**✓ Answer: B**
Corner points: origin (0,0), intercepts, and intersection (8,12).

---

### Q58: Feasible solution satisfies:
A) Only objective function
B) Only some constraints
C) All constraints and non-negativity
D) Optimization condition

**✓ Answer: C**
Feasible solution: values satisfying all constraints and non-negativity.

---

### Q59: In linear programming, a corner point of feasible region is:
A) Any point in region
B) Intersection of constraint boundaries
C) Interior point
D) Boundary edge

**✓ Answer: B**
Corner point: vertex where constraint boundaries intersect.

---

### Q60: The non-negativity constraint x, y ≥ 0 ensures solutions are in:
A) Entire R² plane
B) First quadrant only
C) Negative quadrants
D) On axes only

**✓ Answer: B**
x ≥ 0, y ≥ 0 restricts feasible region to first quadrant.

---

### Q61: In maximization problem, if objective increases without bound, the problem is:
A) Infeasible
B) Unbounded
C) Degenerate
D) Overdetermined

**✓ Answer: B**
Unbounded maximization: objective can increase indefinitely.

---

### Q62: In the Giapetto woodcarving problem, the profit from soldiers vs trains is:
A) Same for both
B) $3 per soldier, $2 per train
C) $40 per soldier, $21 per train
D) Equal with taxes

**✓ Answer: B**
Profit = Revenue - Costs: soldier ($27-10-14=$3), train ($21-9-10=$2).

---

### Q63: In LP formulation, if solution x = 8, y = 12 gives Z = 92, this solution is:
A) Always optimal
B) Optimal if it maximizes Z among corner points
C) Infeasible
D) Interior point

**✓ Answer: B**
Optimal solution: corner point with maximum Z value.

---

### Q64: The constraint 'demand for product ≤ 40' is a:
A) Non-negativity constraint
B) Resource constraint
C) Demand/marketing constraint
D) Equality constraint

**✓ Answer: C**
Market/demand constraints: limit maximum production based on customer demand.

---

### Q65: In graphical method, which constraint form requires shading ABOVE the line?
A) ≤ inequality
B) ≥ inequality
C) = equality
D) > strict inequality

**✓ Answer: B**
≥ inequality: shade above line (region where expression is greater than RHS).

---

### Q66: The optimal value in problem Max Z = 100x₁ + 40x₂ with multiple optima at (200,0) and (125,187.5) is:
A) 10000
B) 20000
C) 25000
D) 30000

**✓ Answer: B**
Both corner points give Z = 20000.

---

### Q67: A bounded feasible region guarantees:
A) No optimal solution
B) Only one optimal solution
C) Both maximum and minimum values exist
D) Problem is infeasible

**✓ Answer: C**
Bounded region: ensures both max and min values are attained.

---

### Q68: When constraints are x + y ≤ 1 AND x + y ≥ 3, the feasible region is:
A) Empty (no solution)
B) Single point
C) Bounded region
D) Unbounded region

**✓ Answer: A**
Contradictory constraints: no point can satisfy both simultaneously.

---

### Q69: In LP, if objective Z = 4x + 5y has optimal value 92 at (8,12):
A) 4(8) + 5(12) = 32 + 60 = 92
B) Other corner points have lower Z
C) Both A and B
D) Neither A nor B

**✓ Answer: C**
Check: 4(8) + 5(12) = 92, and 92 is higher than other corners.

---

### Q70: Variables in LP that are unrestricted in sign (urs) can be:
A) Only positive
B) Only negative
C) Positive, zero, or negative
D) Only zero

**✓ Answer: C**
Unrestricted variables (urs): can take any real value.

---

### Q71: Additivity assumption in LP means:
A) Variables are added to constraints
B) Total effect is sum of individual effects
C) All coefficients must add to 1
D) Constraints must be in sum form

**✓ Answer: B**
Additivity: contribution to objective from each variable is independent of others' values.

---

### Q72: In LP, the constraint 2x₁ + x₂ = 10 is:
A) Inequality constraint
B) Equality constraint
C) Non-negativity constraint
D) Objective function

**✓ Answer: B**
Equality constraint (h_j(x) = 0): exact relationship must hold.

---

### Q73: Which case occurs when LP has infinite optimal solutions?
A) Case 1
B) Case 2 (Alternative/Multiple optimal solutions)
C) Case 3
D) Case 4

**✓ Answer: B**
Case 2: LP has more than one (infinite) optimal solutions.

---

### Q74: The simplex method is an:
A) Graphical technique
B) Algebraic iterative algorithm
C) Trial-and-error method
D) Manual calculation

**✓ Answer: B**
Simplex: algebraic iterative method moving from corner to corner.

---

### Q75: In LP, if two constraint boundaries are parallel to objective function, result is:
A) Unbounded solution
B) Multiple optimal solutions
C) Infeasible problem
D) Unique solution

**✓ Answer: B**
Parallel: objective has same slope as constraint edge.

---

### Q76: Objective function coefficients in LP are also called:
A) Decision variables
B) Right-hand side values
C) Profit/cost coefficients
D) Constraint values

**✓ Answer: C**
Objective coefficients (c_i): represent profit per unit or cost per unit.

---

### Q77: The feasible region in LP is always a:
A) Circle
B) Convex polygon
C) Triangle
D) Random shape

**✓ Answer: B**
Feasible region from linear constraints: convex polygon.

---

### Q78: If corner point gives negative values for some variables in LP:
A) It's an optimal solution
B) It violates non-negativity, not feasible
C) It's interior point
D) Problem is unbounded

**✓ Answer: B**
Non-negativity constraints required: must have x ≥ 0 for all variables.

---

### Q79: In LP solving by graphical method, we test corner points because:
A) They are closest to origin
B) Optimal solution guaranteed at corner point
C) They are easiest to calculate
D) All points are tested

**✓ Answer: B**
Fundamental LP theorem: optimal solution occurs at corner point(s).

---

### Q80: A solution that violates at least one constraint is called:
A) Optimal
B) Feasible
C) Infeasible
D) Corner point

**✓ Answer: C**
Infeasible solution: violates one or more constraints or non-negativity.

---

### Q81: When objective function Z = ax + by and constraint line 3x + 4y = 72 are NOT parallel, optimal occurs at:
A) Entire constraint boundary
B) Single corner point
C) Interior point
D) Origin

**✓ Answer: B**
Non-parallel: unique corner point where objective is optimized.

---

### Q82: In LP, the right-hand side (RHS) values of constraints represent:
A) Objective coefficients
B) Available resources/requirements
C) Variable names
D) Decision variables

**✓ Answer: B**
RHS values (b_i): represent resource availability or requirement limits.

---

### Q83: The constraint matrix A in LP contains:
A) Objective coefficients
B) RHS values
C) Constraint coefficients
D) Variable bounds

**✓ Answer: C**
Constraint matrix A: coefficients of variables in constraints.

---

### Q84: In LP, x-intercept of line 3x + 4y = 12 is found by setting:
A) x = 0
B) y = 0
C) Both zero
D) x = y

**✓ Answer: B**
x-intercept: set y = 0, solve for x → 3x = 12 → x = 4, point (4,0).

---

### Q85: In LP, y-intercept of line 3x + 4y = 12 is found by setting:
A) x = 0
B) y = 0
C) Both zero
D) x = y

**✓ Answer: A**
y-intercept: set x = 0, solve for y → 4y = 12 → y = 3, point (0,3).

---

### Q86: The intersection of constraints 5x + 2y = 1000 and x + 2y = 500 gives corner point:
A) (0,0)
B) (200,0)
C) (125, 187.5)
D) (500,0)

**✓ Answer: C**
Subtracting: 4x = 500 → x=125; then y = (500-125)/2 = 187.5.

---

### Q87: Slack variables in LP represent:
A) Objective value
B) Unused resource or constraint violation
C) Decision variables
D) Feasibility measure

**✓ Answer: B**
Slack variable (simplex): amount of resource unused in inequality constraint.

---

### Q88: Surplus variables in LP represent:
A) Extra resources
B) Amount constraint exceeded (for ≥)
C) Used resources
D) Objective coefficients

**✓ Answer: B**
Surplus variable: amount by which ≥ constraint is exceeded.

---

### Q89: An LP problem with at most 2 decision variables is best solved by:
A) Simplex only
B) Graphical method
C) Calculus only
D) Random search

**✓ Answer: B**
Graphical method: suitable and practical for 2-variable LP problems.

---

### Q90: The term 'Pareto optimal' refers to:
A) Single objective optimization
B) Linear programming only
C) Multi-objective trade-off solutions
D) Simplex method

**✓ Answer: C**
Pareto optimality: solution where improving one objective worsens another.

---

## LECTURE 3: STOCHASTIC GRADIENT DESCENT (Q91-Q120)

### Q91: Stochastic Gradient Descent (SGD) is an optimization algorithm for:
A) Linear programming
B) Minimizing empirical risk on dataset
C) Integer programming
D) LP graphical method

**✓ Answer: B**
SGD: iterative algorithm to minimize empirical risk L(θ).

---

### Q92: Main difference between Gradient Descent and SGD is:
A) GD uses all samples, SGD uses one sample per update
B) Same algorithm
C) SGD is always faster
D) GD is nonlinear

**✓ Answer: A**
GD: uses full gradient; SGD: uses single sample gradient.

---

### Q93: Advantage of SGD over full Gradient Descent is:
A) Higher accuracy always
B) Guaranteed convergence
C) Faster updates per iteration
D) No noise in gradients

**✓ Answer: C**
SGD advantage: faster iterations (computes gradient using one sample).

---

### Q94: Disadvantage of SGD is:
A) Always diverges
B) Cannot find optimal solution
C) Updates are noisy (high variance)
D) Needs all data at once

**✓ Answer: C**
SGD disadvantage: noisy gradient updates lead to less stable convergence.

---

### Q95: The stochastic gradient g_t = ∇_θl(θ_t; x_it, y_it) is:
A) Always equal to true gradient
B) Unbiased estimator of true gradient
C) Always larger than true gradient
D) Never matches true gradient

**✓ Answer: B**
E[g_t|θ] = ∇L(θ): expected value equals true gradient (unbiased).

---

### Q96: In SGD update θ_{t+1} = θ_t - ηg_t, η is the:
A) Gradient value
B) Learning rate
C) Loss function
D) Sample size

**✓ Answer: B**
Learning rate (η): controls step size in parameter update direction.

---

### Q97: Mini-batch SGD uses:
A) Single sample
B) All samples
C) Small batch of samples
D) No samples

**✓ Answer: C**
Mini-batch: computes gradient on batch of size b.

---

### Q98: Advantage of mini-batch over pure SGD is:
A) Always faster
B) Reduced gradient variance, exploits parallel hardware
C) No noise
D) Guarantees optimality

**✓ Answer: B**
Mini-batch: reduces variance, enables GPU/parallel computation.

---

### Q99: In linear regression with SGD, the loss function is typically:
A) l(θ; xi, yi) = |θxi - yi|
B) l(θ; xi, yi) = (θxi - yi)²/2
C) l(θ; xi, yi) = e^(θxi - yi)
D) l(θ; xi, yi) = ln(1 + |θxi - yi|)

**✓ Answer: B**
Linear regression: squared error loss l(θ; xi, yi) = (1/2)(θxi - yi)².

---

### Q100: Gradient of squared loss (1/2)(θx - y)² with respect to θ is:
A) θx - y
B) (θx - y)x
C) (θx - y)/x
D) x² - y

**✓ Answer: B**
∇_θ[(1/2)(θx - y)²] = (θx - y)·x.

---

### Q101: In SGD example with linear regression, true gradient ∇L(θ) = 2.5θ - 5 when:
A) Only one sample
B) Average over two samples (1,2) and (2,4)
C) Infinite samples
D) No samples

**✓ Answer: B**
Average gradient: (1/2)[(θ-2) + (4θ-8)] = 2.5θ-5.

---

### Q102: In SGD, if we pick first sample (x₁=1, y₁=2), stochastic gradient is:
A) 4θ - 8
B) θ - 2
C) 2.5θ - 5
D) 0

**✓ Answer: B**
g₁ = (θ·1 - 2)·1 = θ - 2.

---

### Q103: In SGD, if we pick second sample (x₂=2, y₂=4), stochastic gradient is:
A) θ - 2
B) 2.5θ - 5
C) 4θ - 8
D) 2θ

**✓ Answer: C**
g₂ = (θ·2 - 4)·2 = 4θ - 8.

---

### Q104: Expected stochastic gradient E[g] in two-sample example is:
A) θ - 2
B) 4θ - 8
C) 2.5θ - 5
D) 0

**✓ Answer: C**
E[g] = (1/2)(θ-2) + (1/2)(4θ-8) = 2.5θ - 5.

---

### Q105: In SGD linear regression model y = wx + b, the goal is to learn:
A) Only w
B) Only b
C) Both w and b
D) Only x

**✓ Answer: C**
Linear model parameters: w (weight/slope) and b (bias/intercept).

---

### Q106: Mean Squared Error (MSE) in SGD is defined as:
A) (1/N)Σ(yi - ŷi)
B) (1/N)Σ(yi - ŷi)²
C) Σ(yi - ŷi)²
D) max|yi - ŷi|

**✓ Answer: B**
MSE: L = (1/N)Σ(yi - (wxi + b))².

---

### Q107: In SGD with learning rate η, smaller η means:
A) Faster convergence
B) Larger steps
C) Slower convergence, more stability
D) Random updates

**✓ Answer: C**
Small learning rate: slower convergence but more stable.

---

### Q108: In SGD with learning rate η, larger η means:
A) Slower convergence
B) Larger update steps, faster convergence but possible overshoot
C) More stable
D) Better accuracy

**✓ Answer: B**
Large learning rate: larger steps, faster convergence but risk overshooting.

---

### Q109: Epochs in SGD training refers to:
A) Number of variables
B) Number of constraints
C) Complete passes through entire dataset
D) Single sample

**✓ Answer: C**
Epoch: one complete iteration through all training samples.

---

### Q110: In SGD implementation, shuffling data means:
A) Sort samples
B) Remove samples
C) Randomize sample order
D) Duplicate samples

**✓ Answer: C**
Shuffle: randomize order of samples for each epoch.

---

### Q111: Stochastic gradient is 'unbiased' means:
A) Never wrong
B) Expected value equals true gradient
C) Always equals true gradient
D) No variance

**✓ Answer: B**
Unbiased: E[g_t|θ] = ∇L(θ), but individual g_t may differ.

---

### Q112: Convergence in SGD is more difficult than GD because:
A) Uses fewer samples
B) Noisy gradient estimates
C) Always diverges
D) No local minima

**✓ Answer: B**
SGD harder to analyze: stochastic gradient noise causes oscillations.

---

### Q113: Empirical risk L(θ) = (1/n)Σl(θ;xi,yi) represents:
A) Average loss over single sample
B) Average loss over all training samples
C) Maximum loss
D) Loss at origin

**✓ Answer: B**
Empirical risk: average of per-sample loss over entire training dataset.

---

### Q114: In linear regression with SGD, ŷ_i = wxi + b is:
A) Actual label
B) Predicted value
C) Loss function
D) Learning rate

**✓ Answer: B**
ŷ_i: model's prediction given input x_i and parameters w, b.

---

### Q115: In SGD gradient update dw = -2·x_i·(y_i - ŷ_i), the negative sign indicates:
A) Always decrease w
B) Direction of steepest descent
C) Loss is negative
D) No change

**✓ Answer: B**
Negative gradient: direction of steepest descent (reduces loss).

---

### Q116: Batch gradient descent is preferred when:
A) Dataset is huge
B) Real-time updates needed
C) Dataset is small, accuracy critical
D) Memory unlimited

**✓ Answer: C**
Full batch GD: accurate gradients, better convergence guarantee.

---

### Q117: SGD is preferred in machine learning when:
A) Dataset is small
B) Accuracy critical
C) Dataset is huge
D) No convergence needed

**✓ Answer: C**
SGD: efficient for large datasets, widely used in deep learning.

---

### Q118: Variance of stochastic gradient g_t is typically:
A) Zero
B) Infinite
C) Non-zero (higher than batch gradient)
D) Negative

**✓ Answer: C**
Var(g_t) > 0: stochastic gradient has non-zero variance (noisy).

---

### Q119: Adaptive learning rate methods in SGD (like Adam) adjust learning rate by:
A) Using same fixed η
B) Based on gradient magnitude/history
C) Randomly
D) Never changing

**✓ Answer: B**
Adaptive methods: adjust learning rate per parameter based on statistics.

---

### Q120: Momentum in SGD helps by:
A) Increasing noise
B) Accumulating gradient history for smooth updates
C) Reducing dataset size
D) Removing samples

**✓ Answer: B**
Momentum: accumulates past gradients, reduces oscillations.

---

## LECTURE 4: OPTIMIZATION ALGORITHMS CLASSIFICATION (Q121-Q150)

### Q121: Optimization algorithms can be broadly classified as:
A) Only linear
B) Only nonlinear
C) Deterministic and Probabilistic
D) Only heuristic

**✓ Answer: C**
Two basic classes: Deterministic (systematic search) and Probabilistic.

---

### Q122: Deterministic algorithms work best when:
A) No relation between solution and fitness
B) Clear relation between solution characteristics and utility
C) Very high dimensional
D) Unknown problem structure

**✓ Answer: B**
Deterministic: used when solution characteristics relate to fitness.

---

### Q123: Probabilistic algorithms trade:
A) Speed for accuracy
B) Guaranteed correctness for shorter runtime
C) Constraints for variables
D) Linearity for nonlinearity

**✓ Answer: B**
Probabilistic: sacrifice guaranteed optimality for faster computation.

---

### Q124: Monte Carlo methods are:
A) Deterministic
B) Based on artificial intelligence
C) Probabilistic approaches
D) Always exact

**✓ Answer: C**
Monte Carlo: probabilistic methods trading correctness for speed.

---

### Q125: A heuristic in optimization is:
A) The objective function
B) A constraint
C) Guidance to decide which solution to test next
D) The optimal solution

**✓ Answer: C**
Heuristic: uses current algorithm info to decide next candidate.

---

### Q126: Heuristics are usually:
A) Problem independent
B) Problem class dependent
C) Always optimal
D) Never used

**✓ Answer: B**
Heuristics: tailored to specific problem classes.

---

### Q127: A metaheuristic is:
A) Single heuristic
B) Method combining heuristics for general problem classes
C) Exact method only
D) Linear programming

**✓ Answer: B**
Metaheuristic: combines heuristics for broad problem classes.

---

### Q128: Evolutionary Computation is a class of:
A) Deterministic algorithms
B) Linear programming
C) Probabilistic Monte Carlo metaheuristics
D) LP simplex variants

**✓ Answer: C**
EC: probabilistic Monte Carlo methods with population.

---

### Q129: Genetic Algorithms (GA) are inspired by:
A) Physics
B) Calculus
C) Natural evolution
D) Linear systems

**✓ Answer: C**
GA: copy behavior of natural evolution.

---

### Q130: Swarm Intelligence algorithms include:
A) Only GA
B) Particle Swarm Optimization (PSO), Ant Colony Optimization (ACO)
C) Simplex method
D) LP only

**✓ Answer: B**
Swarm Intelligence: PSO, ACO (collective behavior).

---

### Q131: Simulated Annealing is based on:
A) Evolutionary concept
B) Swarm behavior
C) Physical process of metal solidifying
D) Linear equations

**✓ Answer: C**
SA: models annealing process of metal solidifying.

---

### Q132: Tabu Search is a:
A) Nature-inspired algorithm
B) Physical process model
C) Technique without direct real-world role model
D) Evolutionary algorithm

**✓ Answer: C**
Tabu Search: no direct real-world inspiration.

---

### Q133: Particle Swarm Optimization is inspired by:
A) Bird flocking
B) Ant colonies
C) Genetic evolution
D) Metal cooling

**✓ Answer: A**
PSO: models bird flock or fish school behavior.

---

### Q134: Ant Colony Optimization is inspired by:
A) Bird behavior
B) Genetic evolution
C) Ant pheromone trails
D) Physical annealing

**✓ Answer: C**
ACO: models ant foraging behavior using pheromone.

---

### Q135: Online optimization problems are typically:
A) Time-critical (need quick solution)
B) Can wait days for solution
C) Off-line only
D) No time pressure

**✓ Answer: A**
Online: must be solved quickly (milliseconds to minutes).

---

### Q136: Offline optimization problems typically:
A) Need instant solution
B) Time not critical, can wait for optimal solution
C) Only design
D) Real-time only

**✓ Answer: B**
Offline: time not critical, willing to wait.

---

### Q137: Robot localization is an example of:
A) Offline optimization
B) Online optimization
C) Linear programming
D) Unconstrained problem

**✓ Answer: B**
Robot localization: must update quickly (real-time, online).

---

### Q138: Design optimization (e.g., aircraft design) is typically:
A) Online optimization
B) Offline optimization
C) Linear problem
D) Real-time

**✓ Answer: B**
Design optimization: offline (can take time), not real-time.

---

### Q139: In global optimization, Pareto frontier is used in:
A) Single objective problems
B) Multi-objective optimization
C) LP only
D) Unconstrained problems

**✓ Answer: B**
Pareto front: trade-off curve in multi-objective.

---

### Q140: A global optimum is:
A) Local optimum only
B) Best solution over entire domain
C) Average solution
D) Any feasible point

**✓ Answer: B**
Global optimum: f(x*) ≥ f(x) for all x in domain.

---

### Q141: A local optimum is:
A) Best overall
B) Best in neighborhood
C) Any point
D) Constraint boundary

**✓ Answer: B**
Local optimum: f(x*) ≥ f(x) for all x in neighborhood.

---

### Q142: Hill Climbing is a:
A) Metaheuristic
B) Nature-inspired algorithm
C) Greedy local search heuristic
D) Deterministic exact method

**✓ Answer: C**
Hill Climbing: greedy heuristic moving to best neighbor.

---

### Q143: Genetic Algorithms maintain:
A) Single solution
B) Population of solutions
C) All possible solutions
D) No solutions

**✓ Answer: B**
GA: population-based (multiple candidates).

---

### Q144: Evolution Strategy (ES) differs from GA in:
A) Population size
B) Recombination/mutation operators
C) Representation and operators adapted to continuous spaces
D) Not an algorithm

**✓ Answer: C**
ES: adapted for continuous variables.

---

### Q145: Differential Evolution (DE) is:
A) Linear programming variant
B) Evolutionary algorithm for continuous optimization
C) Simplex method
D) Gradient descent

**✓ Answer: B**
DE: evolutionary algorithm using vector differences.

---

### Q146: Genetic Programming (GP) evolves:
A) Parameter values
B) Computer programs/functions
C) Linear models
D) Constraints

**✓ Answer: B**
GP: evolves tree-structured programs.

---

### Q147: Soft Computing is:
A) Only linear methods
B) Only iterative methods
C) Field including EC, fuzzy, neural networks
D) Only deterministic

**✓ Answer: C**
Soft Computing: includes EC, fuzzy logic, neural networks.

---

### Q148: Computational Intelligence (CI) encompasses:
A) Only classical methods
B) Evolutionary algorithms, fuzzy systems, neural networks
C) LP only
D) Simplex method

**✓ Answer: B**
CI: includes EC, fuzzy systems, artificial neural networks.

---

### Q149: State Space Search is a:
A) Probabilistic method
B) Metaheuristic
C) Deterministic search method
D) LP variant

**✓ Answer: C**
State Space Search: deterministic exploration of solution space.

---

### Q150: The main advantage of hybrid optimization (combining methods) is:
A) Always slower
B) Leverages strengths of multiple methods (e.g., local search + global)
C) More expensive
D) No benefit

**✓ Answer: B**
Hybrid: combines deterministic/probabilistic methods for better performance.

---

## END OF QUESTIONS

**Summary:**
- ✅ Total: 150 MCQ Questions
- ✅ Lecture 1 (Introduction): Q1-Q40
- ✅ Lecture 2 (Linear Programming): Q41-Q90
- ✅ Lecture 3 (Stochastic Gradient Descent): Q91-Q120
- ✅ Lecture 4 (Optimization Algorithms): Q121-Q150
- ✅ Each question includes: Question, 4 Options, Correct Answer, Detailed Explanation

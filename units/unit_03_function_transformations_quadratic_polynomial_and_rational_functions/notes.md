# Unit 3 - Function Transformations, Quadratic, Polynomial and Rational Functions

<!-- TOC -->
* [Unit 3 - Function Transformations, Quadratic, Polynomial and Rational Functions](#unit-3---function-transformations-quadratic-polynomial-and-rational-functions)
* [General Notes](#general-notes)
* [Module 10 - Function Transformation & Quadratic Functions](#module-10---function-transformation--quadratic-functions)
  * [Transformations Activity](#transformations-activity)
  * [Writing a Function In Terms of a Function](#writing-a-function-in-terms-of-a-function)
    * [When setting _a = 2_:](#when-setting-a--2-)
    * [When setting _d = 2_:](#when-setting-d--2-)
    * [When setting _c = 1_:](#when-setting-c--1-)
  * [Vertex of a Function](#vertex-of-a-function)
    * [Vertex Example 1](#vertex-example-1)
    * [Vertex Example 2](#vertex-example-2)
* [Module 11 - Function Transformation and Quadratic Functions](#module-11---function-transformation-and-quadratic-functions)
  * [Quadratic Functions](#quadratic-functions)
  * [Vertex Form of a Quadratic Function](#vertex-form-of-a-quadratic-function)
  * [Different Forms of a Quadratic Function](#different-forms-of-a-quadratic-function)
    * [Standard Form](#standard-form)
    * [Factored Form](#factored-form)
    * [Vertex Form](#vertex-form)
  * [Problems In Different Forms](#problems-in-different-forms)
    * [Problem in Vertex Form](#problem-in-vertex-form)
    * [Problem in Factored Form](#problem-in-factored-form)
    * [Problem in Standard Form](#problem-in-standard-form)
  * [Concavity](#concavity)
  * [Inflection Point](#inflection-point)
  * [Cubic Functions](#cubic-functions)
    * [Cubic Function Example 1](#cubic-function-example-1)
    * [Cubic Function Example 2](#cubic-function-example-2)
    * [Cubic Function Example 3](#cubic-function-example-3)
  * [Polynomial Functions](#polynomial-functions)
    * [Polynomial Function Examples](#polynomial-function-examples)
      * [Polynomial Example 1](#polynomial-example-1)
      * [Polynomial Example 2](#polynomial-example-2)
      * [Polynomial Example 3](#polynomial-example-3)
      * [Polynomial Example 4](#polynomial-example-4)
      * [Polynomial Example 5](#polynomial-example-5)
  * [Graphs of Polynomial Functions](#graphs-of-polynomial-functions)
  * [End Behavior of Polynomial Functions](#end-behavior-of-polynomial-functions)
    * [Determining End-Behavior](#determining-end-behavior)
      * [Function 1](#function-1)
      * [Function 2](#function-2)
      * [Function 3](#function-3)
      * [Function 4](#function-4)
      * [Function 5](#function-5)
  * [Relative and Absolute Extrema of Polynomial Functions](#relative-and-absolute-extrema-of-polynomial-functions)
    * [Relative Extrema of Polynomial Functions](#relative-extrema-of-polynomial-functions)
    * [Absolute Extrema of Polynomial Functions](#absolute-extrema-of-polynomial-functions)
  * [Identifying All Points On a Graph](#identifying-all-points-on-a-graph)
    * [Example 1](#example-1)
    * [Example 2](#example-2)
  * [Computing and Graphing a Cubic Function](#computing-and-graphing-a-cubic-function)
* [Module 12 - Rational Functions](#module-12---rational-functions)
* [Module 13 - Power Functions](#module-13---power-functions)
<!-- TOC -->

# General Notes

# Module 10 - Function Transformation & Quadratic Functions

## Transformations Activity

- [Overall Guide](assets/function_transformations_big_ideas.pdf)

Functions can be transformed in various ways:

- Stretched or compressed vertically or horizontally
- Shifted up or down, or left or right

<u>Transformation Activity:</u> <https://www.desmos.com/calculator/fneiikwfiy>

Two defined functions:

1. **f(x) = x<sup>2</sup>**
2. **g(x) = af(x - c) + d)**

![](assets/transformation_activity_001.png)

- **a**, **c**, and **d** are parameters.
- In this scenario, **f** is the **parent function** and **g** is the
  **transformed / image function**.
- **d** moves the vertical offset by **d** and shifts the graph up or down.
- **a** is the slope and stretches or compresses the graph vertically by a
  factor of **a** and can create a **vertical reflection**.
    - **1 < a:** The graph is stretched vertically (narrower than original)
    - **0 < a < 1:** The graph is compressed vertically (wider than original
      graph)
    - **a < 0:** Creates a vertical reflection.
- **c** moves the horizontal intercept by **c** and shifts the graph left or
  right.
    - **c < 0:** The shift is to the left.
    - **c > 0:** The shift is to the right.
    - In a table, the output of the parent function is moved by **c** places
      down or up.

## Writing a Function In Terms of a Function

### When setting _a = 2_:

|  x  | f(x) | g(x) |
|:---:|:----:|:----:|
| -5  |  25  |  50  |
| -4  |  16  |  32  |
| -3  |  9   |  18  |
| -2  |  4   |  8   |
| -1  |  1   |  2   |
|  0  |  0   |  0   |
|  1  |  1   |  2   |
|  2  |  4   |  8   |
|  3  |  9   |  18  |
|  4  |  16  |  32  |
|  5  |  25  |  50  |

- A formula for the function **g** in terms of **f**:  
  **g(x) = 2f(x)**
- Given that **f(x) = x<sup>2</sup>**, a formula for the function **g** in
  terms of **f**:  
  **g(x) = 2x<sup>2</sup>**

---

### When setting _d = 2_:

|  x  | f(x) | g(x) |
|:---:|:----:|:----:|
| -5  |  25  |  27  |
| -4  |  16  |  18  |
| -3  |  9   |  11  |
| -2  |  4   |  6   |
| -1  |  1   |  3   |
|  0  |  0   |  2   |
|  1  |  1   |  3   |
|  2  |  4   |  6   |
|  3  |  9   |  11  |
|  4  |  16  |  18  |
|  5  |  25  |  27  |

- A formula for the function **g** in terms of **f**:  
  **g(x) = f(x) + 2**
- Given that **f(x) = x<sup>2</sup>**, a formula for the function **g** in
  terms of **f**:  
  **g(x) = x<sup>2</sup> + 2**

---

### When setting _c = 1_:

|  x  | f(x) | g(x) |
|:---:|:----:|:----:|
| -5  |  25  |  36  |
| -4  |  16  |  25  |
| -3  |  9   |  16  |
| -2  |  4   |  9   |
| -1  |  1   |  4   |
|  0  |  0   |  1   |
|  1  |  1   |  0   |
|  2  |  4   |  1   |
|  3  |  9   |  4   |
|  4  |  16  |  9   |
|  5  |  25  |  16  |

- A formula for the function **g** in terms of **f**:  
  **g(x) = f(x - 1)**
- Given that **f(x) = x<sup>2</sup>**, a formula for the function **g** in
  terms of **f**:  
  **g(x) = (x - 1)<sup>2</sup>**

---

## Vertex of a Function

The vertex is the point where the maximum or minimum occurs of the function.

![](assets/transformation_activity_003.png)

### Vertex Example 1

**g(x) = 2f(x) + 3**

- Vertical stretch by a factor of **2**
- Vertical stretch up **3**
- Vertex: **(0, 3)**

### Vertex Example 2

**h(x) = f(x + 2) - 1**

- Horizontal shift left **2**
- Vertical shift down **1**
- Vertex: **(-2, -1)**

# Module 11 - Function Transformation and Quadratic Functions

> - **Google Slides:
    ** [Link to slides](https://docs.google.com/presentation/d/e/2PACX-1vRZf0--QHmeWmMDxhLi4GE_0n-5RLGXaWfmuEAwhrSxwA0pRx8f_fumb9DhNeP-wsUpVrkG2Xer3kSz/embed?start=false&loop=false&delayms=3000)
>
> <a href="https://docs.google.com/presentation/d/e/2PACX-1vRZf0--QHmeWmMDxhLi4GE_0n-5RLGXaWfmuEAwhrSxwA0pRx8f_fumb9DhNeP-wsUpVrkG2Xer3kSz/embed?start=false&loop=false&delayms=3000"><img src="assets/module_11_preview.png" width="300px" height="200px" alt="Google Slides for Module 11"></a>

## Quadratic Functions

Basic quadratic function: **f(x) = x<sup>2</sup>**

- Graph is called **parabolic**
- Shape is open _up_ if **f(x) = x<sup>2</sup>**
- Shape is open _down_ if **f(x) = -x<sup>2</sup>**
- Both ends point in the same direction
- The graph will have a maximum or a minimum
    - This occurs at the vertex
- They are symmetric
    - The axis of symmetry passes through the vertex

There are two types of parabolas:

- **Concave down**
    - Has a maximum value at the vertex
    - Does not have a minimum
- **Concave up**
    - Has a minimum value at the vertex
    - Does not have a maximum

## Vertex Form of a Quadratic Function

**y = a(x - h)<sup>2</sup> + k**

- The function above with **a != 0** is in **vertex form**.
- The point _(h, k)_ is called the **vertex** of the parabola.
- The effect of the different variables:
    - **a** is a vertical stretch/compression/reflection
    - **h** is a horizontal shift left/right
    - **k** is a vertical shift up/down
- **h** is the input reference and **k** is the output reference
    - _(h, k)_ is the reference point

## Different Forms of a Quadratic Function

* In some forms, the **vertex** of a function is easier to determine.
* In other forms, vertical/horizontal intercept are easier to determine.

### Standard Form

> **y = ax<sup>2</sup> + bx + c**

- In this form, **c** will always be the **vertical intercept**.

### Factored Form

> **y = a(x - x<sub>1</sub>)(x - x<sub>2</sub>)**

- In this form, **x - x<sub>1</sub> = 0** and **x - x<sub>2</sub> = 0** can be
  used to find the **horizontal intercepts** _(or **zeros**)_ of the graph.

### Vertex Form

> **y = a(x - h)<sup>2</sup> + k**

- In this form, **(h, k)** will always be the **vertex** of the function and
  either the **minimum** or the **maximum** depending on if the graph is 
  **concave up** or **concave down**.
  - The concavity can be determined by the sign of **a**. 
    - **-x** is concave down
    - **x** is concave up

## Problems In Different Forms

### Problem in Vertex Form

According to the CDC, the number of AIDS cases among people aged 21 or younger
in the US is finally starting to decline after seeing many years of increase.

The function that models the number of cases with respect to the number of years
since 2004 is:  
**N(x) = -692.614(x - 6.829)<sup>2</sup> + 41099.728**

![](assets/vertex_form_graph_001.png)

1. Determine approximately when the number of AIDS cases was at its peak.
   What was the maximum number?
    1. Identify whether the graph is concave up or concave down based off if
       **a** is negative. **It's concave down**.
    2. Determine the maximum (because it's concave down) by finding the
       vertex
    3. Vertex is **[6.829, 41099.728]**, so the answer is **6.829**
2. Identify and explain the vertical intercept of the function.
    - **Option 1**
        1. Graph the function
        2. Create another entry using **0** as **f(x)**: **f(0)**
    - **Option 2**
        1. Substitute **0** into the equation, because it turns into:
           **f(0) = -692.614(x - 6.829)<sup>2</sup> + 41099.728**
        2. **f(0) = -692.614(0 - 6.829)<sup>2</sup> + 41099.728**
        3. **f(0) = -692.614(6.829)<sup>2</sup> + 41099.728**
        4. **f(0) = -692.614(46.635) + 41099.728**
        5. **f(0) = -32300.221 + 41099.728**
        6. **f(0) = 8799.507**
        7. **f(0) = 8799.51** _&larr; Rounded Up_
3. Determine when the model would predict AIDS cases is zero.
    1. Graph the function
    2. Find the horizontal intercepts
    3. Answer: **~1 year before 2004 and ~14.5 years after 2004**
4. Determine the range of years we would expect the number of cases to be at
   least 10,000.
    1. Graph the function
    2. Plot a separate line that is 10,000
    3. Determine where the line intersects with the graph
    4. _Optional: Use inequalities to create a section visualizing it._
    5. **Answer: 0.128 <= x <= 13.53**

### Problem in Factored Form

A water rocket can be purchased at many toy stores. One company claims that
the height above the ground (in feet) for their rocket _t_ seconds after it is
launched can be modeled by:
> **s(t) = -16(t + 0.03)(t - 4.03)**

![](assets/factored_form_graph_001.png)

1. Determine the vertical intercept of the function and explain its meaning
   (if any) in the context of the problem.
    1. Graph the chart
    2. Find the vertical intercept
    3. **[0, 1.934]**
    4. At the start of the launch, before it has taken off, it is **1.934**
       feet above the ground.
2. Determine the horizontal intercepts of the function and explain their
   meaning (if any) in the context of the problem.
    - **Option 1:** **s(t)** will equal 0 when any of the factors equal 0, so
      when **t + 0.03 = 0** or **t - 4.03 = 0**:
        1. Get the intercepts from the formula.
        2. **+0.03** **&rarr;** **-0.03** and **4.03**
        3. **[-0.03, 0]** and **[4.03, 0]**
    - **Option 2**
        1. Graph the chart
        2. Find the horizontal intercepts
        3. **[-0.03, 0]** and **[4.03, 0]**
    - The first intercept has no meaning _**[-0.03, 0]**_, the second intercept
      means that the rocket will hit the ground **4.03 seconds** after
      launching.
3. Determine the vertex of the function and explain its meaning in the context
   of the problem.
    - **Option 1**
        1. Graph the function
        2. Find the vertex
        3. **[2, 65.934]**
        4. After 2 seconds from launching, the rocket will be at its highest
           point
           of 65.934 feet in the air.
        5. Due to symmetry, the vertex will occur halfway between the two zeros:
            1. **<sup>4.03-0.03</sup>/<sub>2</sub> = 2**
            2. **s(2) = 65.934** is the vertex.
    - **Option 2**
        1. Due to symmetry, the vertex will occur halfway between the 2 zeros
           and
           can be found by:<br/>
           **<sup>4.03 + (-0.03)</sup>/<sub>2</sub> = 2**
        2. **s(2) = 65.934** _&larr; After plugging **2** into the formula_
        3. **[2, 65.934]** is the vertex

The horizontal intercepts (**[0.03, 0]** and **[4.03, 0]**) are often referred
to as the **zeros** of the function.

### Problem in Standard Form

First, convert the previous Factored form to standard form:

1. **s(t) = -16(t + 0.03)(t - 4.03)**
2. **s(t) = -16(t<sup>2</sup> - 4.03t + 0.03t - 0.1209)**
3. **s(t) = -16t<sup>2</sup> + 64t + 1.9344**

<u>Getting the vertical intercept <b>s(0):</b></u>

The **c** value is always the output of the vertical intercept. In this
case **1.9344**, so: **[0, 1.9344]**

You can determine the horizontal intercept and vertex by graphing the function:

![](assets/standard_form_graph_001.png)

## Concavity

![](assets/concavity.png)

## Inflection Point

The point on a graph where the function changes concavity is called the
inflection point.

Consider the following: **x<sup>3</sup>**

![](assets/concavity_002.png)

- An inflection point is a point where the curve changes from bending
  one way to bending the other way _(like the top of a hill)_.
- The point where rate of change of the function changes from increasing to
  decreasing, or from decreasing to increasing.

## Cubic Functions

Cubic functions are functions that have two concavities and one inflection
point.

### Cubic Function Example 1

![](assets/cubic_function_001.png)

### Cubic Function Example 2

![](assets/cubic_function_002.png)

### Cubic Function Example 3

![](assets/cubic_function_003.png)

## Polynomial Functions

Linear, quadratic, and cubic are all types of **polynomial functions**,
defined as follows:

![](assets/polynomial_functions_001.png)

- **a<sub>n</sub>x<sup>n</sup>** is the **<u>leading term</u>** of the
  polynomial.
- **n** is the **<u>degree</u>** of the polynomial.
- **a<sub>n</sub>** is the **<u>leading coefficient</u>** of the polynomial.
- The leading term is **_always_** the term with the largest exponent.

### Polynomial Function Examples

#### Polynomial Example 1

> **f(x) = 2x<sup>2</sup> + 3x - 10**
> - **2x<sup>2</sup>** is the leading term
> - **2** is the LC (Leading Coefficient)
> - **<sup>2</sup>** is the degree

#### Polynomial Example 2

> **g(x) = 2x<sup>5</sup> + 4x<sup>4</sup> - 13x<sup>2</sup> + 8**
> 
> - **2x<sup>5</sup>** is the leading term
> - **2** is the LC
> - **<sup>5</sup>** is the degree

#### Polynomial Example 3
> **h(x) = -8x<sup>2</sup> + 3x<sup>5</sup> - 7x<sup>7</sup> - 9**
> 
> - **-7x<sup>7</sup>** is the leading term
> - **-7** is the LC
> - **<sup>7</sup>** is the degree

#### Polynomial Example 4

> **j(x) = 14x<sup>2</sup> - 6x<sup>2</sup> - x**
> 
> - **14x<sup>2</sup>** is the leading term
> - **14** is the LC
> - **<sup>2</sup>** is the degree

#### Polynomial Example 5

> **k(x) = 2 + 6x + 18x<sup>2</sup> - 2x<sup>6</sup>**
> 
> - **-2x<sup>6</sup>** is the leading term
> - **-2** is the LC
> - **<sup>6</sup>** is the degree
## Graphs of Polynomial Functions

> ### Polynomial Summary
>
> [Polynomial Summary PDF](assets/polynomial_summary.pdf)
> [![](assets/polynomial_summary.png)](assets/polynomial_summary.pdf)
>
> ---
>
> ### Regression Usng Desmos
>
> [![Regression Using Desmos](assets/regression_preview.png)](assets/regression_using_desmos.pdf)

- Because polynomial functions are fairly predictable, we can summarize
  the characteristics and appearance of the graphs of polynomial functions
  of the first through fifth degree.

## End Behavior of Polynomial Functions

For any polynomial function, as **x** approaches **&pm;&infin;**, **f(x)**
approaches **&pm;&infin;**.

- As the magnitude (absolute value) of x gets larger and larger, the magnitude
  of the function values will also get larger and larger.
- Symbolically, we write: 
  > **as x &rarr; &pm;&infin;, f(x) &rarr; &pm;&infin;**

### Determining End-Behavior

Rather than graphing out each individual polynomial function, instead locate
the leading term and determine the end-behavior based off it.

Some general rules for the end behavior of polynomial functions:

- If the degree of the polynomial is even, the end behavior will be the same,
  going to either positive or negative infinity, based on the sign of the
  leading coefficient.
- If the degree of the polynomial is odd, the function will have opposite
  end-behavior of the sign of the leading coefficient, going to either positive
  or
  negative infinity, based on the sign of the leading coefficient.

The value of the output is impacted the most by the leading term of the
function.

- Because of this, **<u>you only need to graph the leading term</u>**.
- The end-behaviors are referring to each concavity and how the end-behaviors
  will be either the same or opposite of each-other.

#### Function 1

<img src="assets/end_behavior_graph_001.png" width="600" height="400" alt="">

> **f(x) = 2x<sup>2</sup> + 3x - 10**<br/>
> > As **x &rarr; &pm;&infin;, f(x) &thickapprox; 2x<sup>2</sup>**  <br/>
> > As **x &rarr; &pm;&infin;, f(x) &rarr; &infin;**
> 
> - Only **2x<sup>2</sup>** was graphed because it is the leading term.

---

#### Function 2

<img src="assets/end_behavior_graph_002.png" width="600" height="400" alt="">

> **g(x) = 2x<sup>5</sup> + 4x<sup>4</sup> - 13x<sup>2</sup> + 8**<br/>
> > As **x &rarr; &pm;&infin;, g(x) &thickapprox; 2x<sup>5</sup>**<br/>
> > As **x &rarr; +&infin;, g(x) &rarr; &infin;**<br/>
> > As **x &rarr; &ndash;&infin;, g(x) &rarr; &ndash;&infin;**
> 
> - Only **2x<sup>5</sup>** was graphed because it is the leading term.

---

#### Function 3

<img src="assets/end_behavior_graph_003.png" width="600" height="400" alt="">

> **h(x) = -8x<sup>2</sup> - 3x<sup>5</sup> - 7x<sup>7</sup> - 9**<br/>
> > As **x &rarr; &pm;&infin;, h(x) &thickapprox; -7x<sup>7</sup>**<br/>
> > As **x &rarr; +&infin;, g(x) &rarr; &ndash;&infin;**<br/>
> > As **x &rarr; &ndash;&infin;, g(x) &rarr; &infin;**
> 
> - Only **7x<sup>7</sup>** was graphed because it is the leading term.

---

#### Function 4

<img src="assets/end_behavior_graph_004.png" width="600" height="400" alt="">

> **j(x) = 14x<sup>4</sup> - 6x<sup>2</sup> - x**<br/>
> > As **x &rarr; &pm;&infin;, j(x) &thickapprox; 14x<sup>4</sup>**<br/>
> > As **x &rarr; &pm;&infin;, j(x) &rarr; &infin;**
> 
> - Only **14x<sup>4</sup>** was graphed because it is the leading term.

---

#### Function 5

<img src="assets/end_behavior_graph_005.png" width="600" height="400" alt="">

> **k(x) = 2 + 6x + 18x<sup>2</sup> - 2x<sup>6</sup>**<br/>
> > As **x &rarr; &pm;&infin;, k(x) &thickapprox; -2x<sup>6</sup>**<br/>
> > As **x &rarr; &pm;&infin;, k(x) &rarr; &ndash;&infin;**
> 
> - Only **2x<sup>6</sup>** was graphed because it is the leading term.

---

## Relative and Absolute Extrema of Polynomial Functions

- The term **relative extrema** is used to refer to maxima and minima
  simultaneously.
- The graph of a polynomial function of degree **_n_** will have at most
  **_n - 1_** relative extrema but it may have fewer.
- An **odd** function will **never** have an absolute max or min
- An **even** function will **always** have an absolute max or min

### Relative Extrema of Polynomial Functions

- A **relative maximum** occurs at the point where a graph changes from
  increasing to decreasing.
- A **relative minimum** occurs at the point where a graph changes from
  decreasing to increasing.

### Absolute Extrema of Polynomial Functions

- A relative maximum is called an **absolute maximum** if the function value is
  never larger than at this point for all inputs.
- A relative minimum is called an **absolute minimum** if the function value is
  never smaller than at this point for all inputs.

## Identifying All Points On a Graph

### Example 1

![](assets/fully_detailed_graph.png)

- This could be a 5<sup>th</sup> degree polynomial because the function has
  opposite end behavior (so the degree must be odd), there are 4 concavities, 3
  inflection points, and 4 relative extrema.
- The inflection points are halfway between each extrema

### Example 2

![](assets/fully_detailed_graph_002.png)

- This could be a 4<sup>th</sup> degree polynomial because the function has the
  same end
  behavior (so the degree must be even), there are 3 concavities, 2 inflection
  points, and 3 relative extrema (one absolute)

## Computing and Graphing a Cubic Function

Use the following formula to graph a cubic function:

> **y<sub>1</sub> ~ ax<sub>1</sub><sup>3</sup> + bx<sub>1</sub><sup>2</sup> +
cx<sub>1</sub> + d**

![](assets/cubic_function_regression.png)

# Module 12 - Rational Functions

# Module 13 - Power Functions


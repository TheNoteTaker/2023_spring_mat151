# MAT151 - Unit 2 Notes

# Module 6 - Exponential Functions

- [Google Slide Notes](https://docs.google.com/presentation/d/e/2PACX-1vRiJOQNi7YVfoQlYTg99eu4oC018eSmkMfaK_ZV67jTYosFndZK_SaWhUj2wJF-fBmyZ_kq6_0op-eV/embed?start=false&loop=false&delayms=3000)

## Observing Rate of Change

![](assets/rate_of_change_001.png)

- Notice that the rate of change of McDonald's US sales with respect to time is
  constant.
- Notice that the rate of change of In-N-Out US sales with respect to time is
  increasing.
    - This should be your first indicator to check for percentage increases and
      possibly an exponential function.
- First you need to find the percentage that it is increasing by. This is done
  by getting the rate of change between each output, and then dividing rate of
  change by **y<sub>1</sub>**.
    - **To get the percent change: <sup>y<sub>2</sub> - y<sub>1</sub></sup>
      /y<sub>1</sub>**
    - **To get the change factor: <sup>y<sub>2</sub></sup>/<sub>y<sub>
      1</sub></sub>**
- The table on the left is **Linear** and the table on the right is
  **Exponential**.
- The general formula for an exponential function is: **y = a * b<sup>x</sup>**

![](assets/rate_of_change_002.png)

### Breakdown

![](assets/rate_of_change_004.png)

### How To Solve

![](assets/rate_of_change_003.png)

## Change Factor & Percent Change

Although previously _change_ was discussed in terms of _amount of change_ or
_average rate of change_, exponential change is discussed in terms of a _change
factor_ or in terms of _percentage change_.

- **A function is exponential if: For equal changes in the input, the output
  changes by the _same factor_ (or the same percent).**
    - Another way to describe this: **For equal changes in input, the ratio of
      consecutive outputs is constant (and that ratio is the Change Factor).**

### Factor Change vs Percent Change (Independent Research)

A factor change is a ratio of the new value to the old value, while a percent
change is the difference between the new value and the old value, expressed as a
percentage of the old value.

<u>A factor change can be expressed as follows:</u>

- **factor change = new value / old value**

For example, if the _old value_ is **100** and the _new value_ is **150**, the
factor change would be **150/100 = 1.5**.

<u>A percent change can be expressed as follows:</u>

- **percent change = (new value - old value) / old value * 100%**

For example, if the _old value_ is **100** and the _new value_ is **150**, the
percent change would be **(150 - 100) / 100 * 100% = 50%**.

- Percent change is often used to measure the relative change in a quantity,
  while factor change is used to measure the absolute change in a quantity.
- In general, percent change is more useful when comparing changes in different
  quantities, while factor change is more useful when comparing changes in the
  same quantity.

### Example

|  x  |   y   |
|:---:|:-----:|
|  0  |   8   |
|  1  |   6   |
|  2  |  4.5  |
|  3  | 3.375 |

- There is a constant ratio of 0.75 between each output, therefore it is
  exponential.
- **Change Factor: 0.75**
- **Percent Change: -25%**
- **y = 8(0.75)<sup>x</sup>**

### Completing a Table

![](assets/exponential_functions_001.png)

- The final input was found by repeatedly multiplying **222.7758** by **1.3**
  until the value lined up with **636.27**.

### General Form of Exponential Function

![](assets/general_form_of_exponential_function_001.png)

## The Exponential Formula and Graphs

**f(x) = ab<sup>x</sup>**

### Effect 1

- As the value of the function of **x -> infinity** (gets larger and larger):
    - **f(x)** gets closer and closer to **0**
    - As **x -> infinity**, **f(x) -> 0**
- As the value of the function of **x -> -infinity** (gets more and more
  negative):
    - **f(x)** gets larger and larger
    - As **x -> -infinity**, **f(x) -> infinity**

### Effect 2

- The effect that **a** has on the function of the graph:
    - The **vertical intercept** output value
    - If **a < 0** then there is a vertical reflection.
- The effect that **b** has on the function of the graph:
    - Determines growth or decay:
        - If **b > 1** then growth
        - If **0 < b < 1** then decay

### Effect 3

- If the coefficient **a** in an exponential formula is 0, it means that the
  exponential function will always evaluate to 0, regardless of the value of
  the exponent.
    - For example, if the exponential function is **f(x) = 0 * b^x**, then **f(
      x) =
      0** for any value of **x**. This means that the exponential function is
      not
      increasing or decreasing, but stays constant at a value of **0**.
- If the base **b** is also **0**, then the exponential function is undefined,
  since it would involve dividing by **0**.

# Module 7 - Exponential Functions Continued

[Google Slides](https://docs.google.com/presentation/d/e/2PACX-1vQmiaoilQcgkqIcmyH17lHoJ1LHSm94B_dzSJha7p6vvYkbkRJj9YZeGDFNZu1a1OaMz7jQzSaTwodd/embed?start=false&loop=false&delayms=3000)

## Recall - General Form of an Exponential Function

![](assets/exponential_function_form.png)

## One-Year Change Factor

![](assets/one_year_change_factor.png)

## Three-Year Change Factor (Multi-year Change Factor / Percent Change)

![](assets/three_year_change_factor.png)

- You get the change factor of several years worth by getting the one-year 
  change factor first (**1.0483**), and then putting it to the power of the change
  in input.

In order to use the 3-year change factor of **1.1520** to get the 6-year and the
10-year changes:

1. **6-year: 1.1520<sup>2</sup> = (1.0483<sup>3</sup>)<sup>2</sup> = 1.3271**
2. **10-year: 1.1520<sup>10/3</sup> = (1.1520<sup>1/3</sup>)<sup>10</sup> =
   1.6027**

- _It's important to note that there can be a difference in value when using
  multi-year change factors due to rounding._

## General Exponential Forms

### Exponential Function Using One-Unit Change Factor

![](assets/exponential_function_form.png)

### Exponential Function Using _n_-Unit Change Factor

![](assets/exponential_function_form_002.png)

## Half Life

The **half-life** of a substance is the amount of time it takes for half of the
intial amount of the substance to remain.

- When given the half-life, the _n_-unit change factor is **always 0.5** and 
  _n_ is always the size of the half-life.

### Example

A car has a value of **$24,000** with a half-life of **7 years**.

#### Calculating the depreciation rate per-year

1. **(0.5)<sup>1/7</sup>**
2. **Change Factor = 0.9057**
3. **Percent Change = -9.43%**

#### Calculating the value after 10 years

1. **24000(0.5)<sup>10/7</sup>**
2. **8915.97 dollars**

### Example 2

After starting with 78 micrograms, the mass of bacteria decreases by
35% every 2 hours.

Determine the half life of the bacteria.

#### Method 1

- The 2-hour change factor: **0.65**
- The 1-hour change factor: **(0.65)<sup>1/2</sup> = 0.8062**

The formula: **(0.8062)<sup>x</sup> = 0.5**

We will solve this graphically:

![](assets/half_life_001.png)

#### Method 2

1. Define variables
   - **_t_ = time elapsed in hours**
   - **_m_ = mass of bacteria in micrograms**
2. Write a formula: **m = 78(0.65)<sup>_t_/2</sup>**
3. Find half the amount of the original amount: **78(0.5) = 39**
4. Substitute the found value into the formula: 
   **39 = 78(0.65)<sup>_t_/2</sup>**
5. Solve it graphically

![](assets/half_life_002.png)

## Doubling Time

**Doubling time** is the amount of time it takes for something that is growing
to double.

- When given the doubling time, the _n_-unit change factor is **always** 2 and
  _n_ is always the size of the doubling time.

### Example

Suppose you have bacteria with a mass of 12 micrograms and that the doubling
time of this bacteria was 8 hours.

1. Determine the percent that the mass of bacteria increase by each hour. 
2. Define a formula for the function that gives the mass of bacteria m in
   micrograms after ¢ hours.

Since the doubling time is 8 hours, the 8-hour change factor is **2**.

- The 1-hour change factor: **(2)<sup>1/8</sup>= 1.0905**
- the 1-hour percent change: **9.05%**.

The formula would be: **m = 12(2)<sup>t/8</sup>**

## Exponential Regression

In the real world, there are datasets that aren't quite exponential but are
close. When this happens, we create an **exponential model** _(an exponential
funciton that models the data)_.

- We do this using **Exponential Regression**.

_How to do exponential regression in desmos:_ <https://www.youtube.com/watch?v=XnOzmfdbaXU>

- Be sure to select **Log Mode** on Desmos for Exponential Regression. If you
  forget to do so, your models will be slightly different.
# Mat151 Web Assign Notes

# Section 1.1

## Decision-Factor Equation

**Decision-factor equations** help to model the decision process in real world
situations when deciding on multiple options that each have multiple variables.

In the table below, a decision-factor equation will be used to decide which car
to buy:

| Car | Mileage |  Price  | Color  |
|:---:|:-------:|:-------:|:------:|
|  1  | 61,671  | $11,495 |  Grey  |
|  2  | 23,258  | $15,997 |  Red   | 
|  3  | 14,865  | $15,995 | Silver | 
|  4  |  5,295  | $16,495 | Silver |
|  5  | 35,671  | $11,995 |  Red   |
|  6  |  3,446  | $16,495 |  Grey  |

1. Assign values to the non-numeric values (In this case, _color_). Red will be
   the first choice, grey the second, and silver the third.
    1. _red = 1_
    2. _grey = 2_
    3. _silver = 3_
2. Create a decision-factor equation: **mileage + price + color**
3. Modify the decision-factor equation to increase the effect that small numbers
   have on the over all equation:  
   **mileage + (4 * price) + (1000 * color)**
4. Create a table if necessary for vizualization

| Car | Mileage | Price   | Color    | DecisionFactor | Rank |
|-----|---------|---------|----------|----------------|------|
| 1   | 61,671  | $11,495 | Grey=2   | 109,651        | 6    |
| 2   | 23,258  | $15,997 | Red=1    | 88,246         | 5    |
| 3   | 14,865  | $15,995 | Silver=3 | 81,845         | 3    | 
| 4   | 5,295   | $16,495 | Silver=3 | 74,275         | 2    | 
| 5   | 35,671  | $11,995 | Red=1    | 84,651         | 4    | 
| 6   | 3,446   | $16,495 | Grey=2   | 71,426         | 1    | 

5. Find the highest or lowest ranked one based off how you created your equation.

A decision-factor equation is a **symbolic form**, while a table of data is in
**numeric form**.

A **mathematical model** is an abstract description of a concrete system using
mathematical concepts and language. The process of developing a mathematical
model is termed **mathematical modeling**.

- Mathematical models are helpful in making predictions or solving problems in 
  real-world situations.

# Section 1.2
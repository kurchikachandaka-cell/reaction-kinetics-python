
# First-Order Reaction Kinetics Analysis using Python

## Objective
To determine the reaction order and rate constant of a chemical reaction using integrated rate laws and regression analysis.

## Theory
For a first-order reaction:
ln[A] = ln[A0] − kt

A linear plot of ln[A] versus time with a high R² value confirms first-order kinetics, where the slope equals −k.

## Methodology
- Time–concentration data were analyzed using Python.
- Concentration data were transformed to ln[A].
- Linear regression was applied to obtain the rate constant.
- R² was used to validate the kinetic model.

## Tools Used
- Python
- NumPy
- Matplotlib
- SciPy

## Results
- The ln[A] vs time plot was linear.
- R² ≈ 0.99995, confirming first-order kinetics.
- The rate constant was obtained from the slope.

## Conclusion
The reaction follows first-order kinetics, as validated by the linear ln[A] vs time plot and a near-unity R² value.

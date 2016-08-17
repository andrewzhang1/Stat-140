# Stat-140
Some resource files for Stat 140

Current working on:
### Content for Bivariate Normal
Building interactive widgets to explore properties of correlation in bivariate normal variables. Data is pulled from Karl Pearson's father/son height dataset.

A couple current widgets:
#### Visualizing Correlation
Widget to explore correlation as the projection of two independent, standard normal variables projected at an angle
![Visualizing Correlation](/screenshots/visualizing_correlation.gif?raw=true)

#### Visualizing Conditional Expectation of Normal RV
Comparing the expected and actual of conditioning son's height on father's height
![Correlation Expectation](/screenshots/correlation_expectation.gif?raw=true)

#### Visualizing Correlated Variables as Sum of Independent RV

Widget to explore slope of projected axis to create independent normal variables
![Correlation Conversion to Standard](/screenshots/correlation_converting_to_standard.gif?raw=true)

### Error handling
Overrides default Jupyter error handling, allowing injection of custom error messages. Currently allows switching between Simple and the three default exception handlers Plain, Context, and Verbose. Changing error handlers saves between cells.

![Simple Error Handler](/screenshots/error_handling.PNG?raw=true)

![Verbose Error Handler](/screenshots/error_handling_verbose.PNG?raw=true)

Simple currently shows syntax error locations
![Error Handler Syntax](/screenshots/error_handling_syntax_errors.PNG?raw=true)

To do:
* Line numbers for simple mode
* Syntax highlighting for simple mode

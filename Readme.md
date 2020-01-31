# Diet Problem

## Objective & Summary

**Solve [Diet Problem](https://en.wikipedia.org/wiki/Stigler_diet "Diet Problem") using Column Generation**

There are 7146 kinds of food listed, and 30 nutrients. We want to find a diet that has the minimum  level of cholesterol intake and at the same time satisfies all the nutritional requirement. Since  the student (free) version of Xpress cannot handle 7146 variables, we apply column generation to  the problem.

## Files

File : diet.colgen.partial.mos
Description: Mosel (Xpress) Code for the project 

File : diet.xls
Description: Data containing foods & nutrients

## Execution:

Language: mosel

1. Download Xpress IVE (https://www.fico.com/en/products/fico-xpress-optimization)
2. Open the diet.colgen.partial.mos in Xpress and run 


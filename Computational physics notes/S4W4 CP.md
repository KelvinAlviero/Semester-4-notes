# WEEK 4
## Integral and derivatives

### PART 1
- Indefinite and definite
![image](https://github.com/user-attachments/assets/d1594ef5-312c-41ed-a1f1-df960ed3b635)

- Derivative
  - Used for the slope (Slooooop)
 
- OH MY GOD HOW DO I EVEN WRITE THIS, I'LL JUST SS IT OML
- (Kelvin)

### Trapezoidal rule
- ![image](https://github.com/user-attachments/assets/ac1dd925-73d9-4bf8-ad14-32574ea2589c)
-  A better approach, involing less work where the area is divided into trapezoids instead of rectangles
- Trapezoids under the area are usually *better* aproximation rather than the straight up area of the curve
- More slices mean more accuracy
- *BUT* more slices mean more work, **including** when ran by a *code/program*, use when necesarry.
- 
- ![image](https://github.com/user-attachments/assets/7d3a36a3-f747-41a2-a5cf-24d53791505f)
- ![image](https://github.com/user-attachments/assets/e6bda1c7-992f-43b0-89c5-4cfbb9c406fd)

### Simpson Rule
![image](https://github.com/user-attachments/assets/05e89bfe-fa37-40a6-991a-f0e493b67fa8)
- Best suited when high accuracy isn't needed
- Significantly shorter and more simpler than Trapezoid rule
- Note : The formula is SUPER long though, highly advise a youtube video

### Choosing step size
- Steps are the "N" in formulas, we call em steps because it's the number of times we loop it
- Quick calculations may use *Round numbers*, more complex calculations need more complex numbers like decimals or fractions
- We have to take into account the time a computer needs to do the calculation, round numbers are much better due to their simplicity

#### Process
(Super watered down un-seasoned method)
- Choose an "N1"
- Calculate the first approximation with N1 and the Trapezoid rule, name it "I1"
- Double the N, to find the better estimate
- Calculalte the error (Any error type works I think, approximation error is used mostly)
- 

### Error types
- Absolute Error
``` True value -  Approximate Value ```
- Relative Error
``` ((True Value -  Approximate value)/True Value)*100% ```
- Approximation Error
``` ((True value -  Approximate Value)/Approximate Value)*100%```
- Rounding Error
``` Computer limit, not our fault usually```
#### Error estimators
- Eurler-Maclaurin formula
- Simpson's rule

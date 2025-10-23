# ICS-Quadratic-Grader-Musonda-Shimpa-Florence
Quadratic solver and Grade converter for ICT251
# ICS Quadratic & Grading Web App

This is a single-page web application built using **HTML** and **JavaScript**.  
It performs two main tasks:

1. **Quadratic Equation Solver**  
   - Solves equations of the form **ax² + bx + c = 0**  
   - Displays the discriminant (D = b² - 4ac)  
   - Shows the nature of roots:
     - D > 0 → two real roots  
     - D = 0 → one real repeated root  
     - D < 0 → two complex roots  
   - Includes error messages if `a = 0` or if any input is missing.

2. **Score to Grade Converter**  
   - Converts a numeric score (0–100) into a letter grade using the scale:  
     - A+: 85–100  
     - A: 75–84  
     - B+: 65–74  
     - B: 60–64  
     - C+: 55–59  
     - C: 50–54  
     - D: 0–49  
   - Validates input so only numbers between 0 and 100 are accepted.

---

##  How to Run

1. Download the file **`index.html`**.  
2. Double-click it or open it in any web browser (e.g., Chrome, Edge, Firefox).  
3. The page runs completely **offline** — no internet connection needed.

---

##  Test Cases

### Quadratic Solver
| a | b | c | Expected Result |
|---|---|---|----------------|
| 1 | -3 | 2 | D=1, Roots 2 and 1 (two real roots) |
| 1 | 2 | 1 | D=0, Root = -1 (one repeated root) |
| 1 | 2 | 5 | D<0, Complex roots (-1 ± 2i) |

### Grading Converter
| Score | Expected Grade |
|--------|----------------|
| 100 | A+ |
| 85 | A+ |
| 75 | A |
| 65 | B+ |
| 60 | B |
| 55 | C+ |
| 50 | C |
| 49 | D |
| 0  | D |

---

##  Repository Structure

---
## Author
**Musonda Shimpa Florence**
ICT251 - Web Tchnologies Assigment 
Mulungushi University




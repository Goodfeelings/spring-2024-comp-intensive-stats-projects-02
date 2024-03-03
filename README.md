# Computational Intensive Stats: Project 02

__Course Code: STA 6106__
__Period: Spring 2024__ \
__Instructor: Dr. Ping Sa__ \
__Textbook: Simulation, 6th Ed. by Sheldon M. Ross__


The Course description and other information can be found among the following links: 
* Degree Requirements: https://www.unf.edu/catalog/programs/gr/coas/COAS-MSAMATMAT1.html 
* Course Catalogue: https://www.unf.edu/catalog/courses/?level=gr#
* Textbook: https://shop.elsevier.com/books/simulation/ross/978-0-323-85738-3

# Assignment Statement

__Problem Focus:__ How Much Did You Spend on Your Last Haircut?

__Goal:__ Use this data to construct a bootstrap interval for the average number of dollars that a student at this college spends on a haircut.
* Use 500 bootstrap samples to construct the interval by the Percentile method.
* Use either the double bootstrap method or the bootstrap-t method to construct the confidence interval.
  - Use $\text{B}1 = 500$ and $\text{B}2 = 500$ to construct the interval by the dobule bootstrap method.
  - Use 500 bootstrap samples to construct the interval by the bootstrap-t method.
* Use $90\%$ as the confidence level. Write a detailed report on how you get the bootstrap samples and find the confidence intervals.
* Compare the results based on the two methods.
* Type the report.

__Context:__ We were given the following information in class:
* Data were collected from the class participants, with some generating more than one number due to the small class size. These are given below.
* We were told to draw randomly from an envelope to determine if our secondary bootstrap method would be the double bootstrap or the bootstrap-t method. I drew bootstrap-t.

__Collected Data:__
| Student ID | Response (In Dollars) |
|------------|-----------------------|
| 1 | 0 |
| 2 | 65 |
| 3 | 25 |
| 4 | 0 |
| 5 | 25 |
| 6 | 35 |
| 7 | 50 |
| 8 | 36 |
| 9 | 44 |
| 10 | 170 |
| 11 | 87 |
| 12 | 96 |
| 13 | 100 |
| 14 | 65 |
| 15 | 48 |

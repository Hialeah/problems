<h2 id="61"> 61. Overloaded Hospital </h2>

Write a program that computes and displays the charges for a patient’s hospital stay. First, the program should ask if the patient was admitted as an in-patient or an out-patient. If the patient was an in-patient the following data should be entered: 

- The number of days spent in the hospital 
- The daily rate 
- Charges for hospital services (lab tests, etc.) 
- Hospital medication charges. If the patient was an out-patient the following data should be entered: 
- Charges for hospital services (lab tests, etc.)
- Hospital medication charges. The program should use two overloaded functions to calculate the total charges. One of the functions should accept arguments for the in-patient data, while the other function accepts arguments for out-patient data. Both functions should return the total charges. Input Validation: Do not accept negative numbers for any information.


- [ ] Answer in C++
- [ ] Answer in Java

<h2 id="62"> 62. Population </h2>

In a population, the birth rate is the percentage increase of the population due to births and the death rate is the percentage decrease of the population due to deaths. Write a program that asks for the following: 

- The starting size of a population 
- The annual birth rate 
- The annual death rate 
- The number of years to display The program should then display the starting population and the projected population at the end of each year. It should use a function that calculates and returns the projected new size of the population after a year. The formula is

```
N = P(1 + B)(1 - D)
```

where N is the new population size, P is the previous population size, B is the birth rate, and D is the death rate.

Input Validation: Do not accept numbers less than 2 for the starting size. Do not accept negative numbers for birth rate or death rate. Do not accept numbers less than 1 for the number of years.

- [x] [Answer in C++](https://github.com/MDCblue/cpp/blob/master/61-62/population.cpp)
- [ ] Answer in Java

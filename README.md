# Bactalysis
Algorithm that optimizes MFC design by finding the best material combinations to maximize electricity output.

# More Info
Hemodialysis is a costly procedure, making it unaffordable to those who are economically disadvantaged. A large portion of healthcare costs are solely due to hemodialysis, and a patient can be charged $500 or more for a single treatment. Because kidney failure results in the patient requiring repeated weekly treatments, these costs can accumulate over time. Microbial fuel cells are bioelectrochemical devices that can produce electricity by obtaining electrons through a series of anaerobic oxidation reactions of substrates initiated by bacteria. Similar to batteries, these fuel cells consist of an anode and a cathode which are separated by a proton exchange membrane. By adapting existing technology and using dialysis effluent that is disposed of as sewage, we can generate electricity to repower hemodialysis, thus making it more affordable for both the hemodialysis center and the patients who require dialysis to survive.

This code and dataset aims to optimize a microbial fuel cell design optimization through skipy optimize.
By setting the constraints of the algorithm to minimize electricity output and maximize cost, the objective function becomes Maximize (Electricity).
Essentially, it aims to find the best balance between generating more electricity using the data provided. From a mathematical perspective, this ratio can be viewed as the efficiency of the system. The algorithm would attempt to adjust the weights of the differing materials used, expressed as integers, to find an optimal solution for the ratio and thereby provide us with an ideal design for the microbial fuel cell.

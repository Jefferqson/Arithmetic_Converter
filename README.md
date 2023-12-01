# Arithmetic_Converter

Passing code for FreeCodeCamp's first Scientific Computing with Python <a href="https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/arithmetic-formatter">certification test</a>.
The goal of the assignment was to take a list of strings of arithmetic problems and output them vertically, like they would appear in an elementary school workbook. The function that did this was also required to take an optional parameter which requested the answer to the problem. The function was also required to output one of four error messages under certain conditions.

The arithmetic_arranger function first separates the problems into first number, second number, and operator variables, returning the four error messages as required. It then generates four empty lists which correspond to the first number, second number, separating dashed line, and answer rows. The variables for every inputted problem are appended to the string in the list as the function iterates through them and spacing adjustments are made for the required formatting. Finally, the four lists are outputted as four formatted strings, if the optional parameter is inputted, and as three formatted strings without the answer if not. 

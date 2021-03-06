# Application for polynomial approximation using nodes

## Setup
Clone the project
```bash
 pip install -r requirements.txt
```
```bash
python main.py
```

To be honest, I'm writing this readme after 15 months when the project was written;
The project is a part of a course work from the university I study in 

This is the ui-based application that uses computational mathematics' methods for polynomial 
approximation

The main goal of the app is next: you have set of (x, y) nodes, but you don't know
the function and the application is trying to approximate function and to calculate approximated function 
at specified x  

When the app is started, you see three tabs

First tab is for manual data input: you manually input set of (x, y) nodes 
and the x you wanna calculate at;

There are two options for nodes - optimal (Chebyshev's ) and uniform distribution </br>
Choose any and input data, click the button and you'll see the result
The app will also paint the approximated function 

![alt text](./images/app_example1.png)

Second tab demonstrates comparing the result between optimal and uniform nodes using 
already specified function

![alt text](./images/app_example2.png)
The third tab demonstrates a possibility to input data via a file


![alt text](./images/app_example3.png)


P.S. I wanted to refactor this project, but It was a bit hard so I decided not to do it bkz it's not so important or 
just laziness

This project should have had the next structure, but refactoring didn't happen

![alt text](./images/future_past_project_structure_scr1.png)

![alt text](./images/future_past_project_structure_scr2.png)

![alt text](./images/future_past_project_structure_scr3.png)

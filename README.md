# Linear and Discrete Models: Energy Production Optimization Using Python Pyomo
Optimize energy production across 25 regions in a country, balancing renewable and non-renewable sources, seasonal demand fluctuations, and government constraints for cost-effective and environmentally friendly solutions.

### 📊 Project Steps

1. **Data Generation**
- We have created a Python function to randomly generate data such as the availability of each energy source depending on the region and time period, the environmental impact, and the production cost of each energy source.
  
2. **Defining the problem**
- Using the Pyomo package, we create the Sets, Variables, and Parameters to finally establish the Objective function, which aims to minimize the cost of energy production.

3. **Establishing constraints**
- We define the constraints that we want the model to consider, which are explained in the files (such as environmental impact, fulfilling demand in each region, etc.)

4. **Solve the model**
- We solve the proposed model using the "glpk" solver, which is used for linear models.

5. **Discrete Models**
- We will undertake a similar process but include discrete models, such as using binary variables to determine whether a particular energy source is used. This way, we will redefine the model by adapting the objective function and adding new constraints (e.g., limiting the maximum number of non-renewable energy types).

6. **Interpretation and Conclusions**
- The insights and conclusions are detailed in the .ipynb and .html files.

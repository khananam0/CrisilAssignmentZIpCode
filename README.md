# Credit Rating Calculation for Residential Mortgage-Backed Securities (RMBS)

## Project Overview
This project implements a Python solution to calculate credit ratings for Residential Mortgage-Backed Securities (RMBS). The rating is determined based on the risk attributes of individual mortgages within the RMBS. These attributes include credit scores, loan-to-value (LTV) ratio, debt-to-income (DTI) ratio, loan type, and property type.
The final credit rating can be:
    AAA: Low risk, highly secure for investment.
    BBB: Medium risk, suitable for cautious investors.
    C: High risk, speculative investment.



The solution is developed in Python and includes a function `calculate_credit_rating()` that evaluates mortgages and calculates the overall credit rating for the RMBS.

## Installation
1. Clone this repository:
   ```bash
  
   git clone https://github.com/khananam0/CrisilAssignmentZIpCode.git 
   cd credit_rating_mock

2. Setup Python Envirnoment. Create virtual Env.
    ```bash
    python -m venv venv

3. Activate the virtual environment:
    => On Windows: ```bash``` - venv\Scripts\activate
    => On Linux/Mac: ```bash``` - source venv/bin/activate

4. Install Dependencies
    ```bash
    pip install -r requirements.txt

5. Running the Code:
    1. One way is using example 1 usage which is to import json data and run the code.
    2. Second way is in the same file adding the json data and runing the function using eample 2 uasge and comment down eample 1 usage.

        ```In bash execute for 1 and 2 use command```
        python credit_rating.py
    3. Third way is i have imported the code in python file (runfile.py) and run that file directly. 
        ```bash exceute the runfile.py```
        python runfile.py


6. Testing
    Run unit tests to validate the logic in :
    ```bash
    python -m unittest test_credit_rating.py


7. Install dependencies from requirements.txt:
    ```bash
    pip install -r requirements.txt




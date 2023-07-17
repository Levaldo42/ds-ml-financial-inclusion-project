# EDA project for ML

Our second project dealt with the topic of financial inclusion (FI) in East African countries(Kenya, Rwanda, Tanzania and Uganda). The data set was provided in a competition on Zindi [Financial Inclusion in Africa](https://zindi.africa/competitions/financial-inclusion-in-africa).

Financial inclusion is considered as a main topic for poverty reduction in poor countries in the world.
[For more information about FI read here](https://www.gpfi.org/why-financial-inclusion)

The slides for the presentation are under: [Slides for our presentation](https://docs.google.com/presentation/d/13g0cf4CojeH_SqUUQ84opw7_dplkrl_nZlCcmJoBrco/edit#slide=id.g1e4c24518d3_0_1)

This is what we did:

1. Data preparation and minimal data cleaning
2. EDA
3. Creating a baseline model that should be able to predict if a person has a bank account or not.
4. Try out different models (KNN, Decision Tree, Logistik Regression, Random Forest)
5. Chose the best model based on accuracy. Accuracy was chosen because this metric is easy to explain to non technical stakeholders. 
6. Present our results to a stakeholder (we chose the UN) to give them a basic overview over the banking situation in Africa and which factors  influence the likelihood of having a bank account.

---

## Requirements and Environment

**Requirements:**
- pyenv with Python: 3.11.3

**Environment:** 

For installing the virtual environment you can install it manually with the following commands: 

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```


## Libraries used
For data analysis tasks we used the following libraries.
```Bash
import numpy as np
import pandas as pd
import seaborn as sns
```
To train our model, predict and finally evaluate our results, we used libraries of sklearn and scipy.

```Bash
sklearn.metrics
sklearn.neighbors
sklearn.model_selection
sklearn.ensemble
scipy.stats
```




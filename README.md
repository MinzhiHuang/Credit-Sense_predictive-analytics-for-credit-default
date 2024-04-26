
# Credit Sense: Predictive Analytics for Credit Default

## Project Introdution:

**Data Set:** [Default of Credit Card Clients Dataset](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset). 

**Summary:** This Kaggle data set includes 30,000 examples and 24 features, and the goal is to estimate whether a person will default (fail to pay) their credit card bills; this column is labeled "default.payment.next.month" in the data. 
The rest of the columns can be used as features. 

**Related Research:**  [The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients](https://www.sciencedirect.com/science/article/pii/S0957417407006719).

**Stakeholders:** Chloe Huang, Yimeng Xia, Yiwei Zhang

## Local Conda Environment Setup

### Creating a New Environment
- **Create a new conda environment** using the provided YAML file:
  ```sh
  conda env create --name 573credit --file=environment.yaml
  ```

- **Activate the `573credit` environment** by selecting `avalon` from the Jupyter notebook's kernel dropdown:
  ![Environment Selection Dropdown](https://media.github.ubc.ca/user/2897/files/a5429de2-34f6-4e1f-a2e7-e77ce2a032ae)


### Updating the Environment
- **Update your local environment** with any changes made to the YAML file:
  ```sh
  conda env update --name 573credit --file=environment.yaml
  ```

- Verify that the new environment runs smoothly and all packages load correctly.

### Troubleshooting
- There is generally no need to switch to the `573credit` environment in your terminal. Ensure that the Jupyter notebook is running under the `573credit` environment.
- To use the `573credit` environment locally from Terminal, execute:
  ```sh
  conda activate 573credit
  ```
- If Jupyter does not recognize the new conda environment, install the `ipykernel` kernel spec:
  ```sh
  conda activate 573credit
  python -m ipykernel install --user --name 573credit --display-name "Python (573credit)"
  ```

### License

All reports contained herein are licensed under the [Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License](https://creativecommons.org/licenses/by-sa/4.0/).
 See [the license file](LICENSE.md) for more information.

If re-using/re-mixing please provide attribution and link to this webpage.

The software code contained within this repository is licensed under the
MIT license. See [the license file](LICENSE.md) for more information.

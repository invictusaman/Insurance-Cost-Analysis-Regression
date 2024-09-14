# Project Scenario

You have to perform data analytics on a medical insurance charges dataset. This is a filtered and modified version of the [Medical Insurance Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction?resource=download) dataset, available under the [CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/legalcode) on the Kaggle website.

## About the dataset

Download it from the `Dataset` folder.

## Getting the notebok

You can find the `Jupyter` notebook under Jupyter Notebook folder.

I have also created a `Quarto` notebook to generate my report.

## Report and Finding

View the report and analysis of this dataset under `Report` folder. It was generated using `Quarto`.

## Parameters

The parameters used in the dataset are:

- **Age**: Age of the insured. Integer quantity.
- **Gender**: Gender of the insured. This parameter has been mapped to numerical values as follows:

  | Gender | Assigned Value |
  | ------ | -------------- |
  | Female | 1              |
  | Male   | 2              |

- **BMI**: Body Mass Index of the insured. Float value quantity.
- **No_of_Children**: Number of children the insured person has. Integer quantity.
- **Smoker**: Whether the insured person is a smoker or not. This parameter has been mapped to numerical values as follows:

  | Smoker     | Assigned Value |
  | ---------- | -------------- |
  | Smoker     | 1              |
  | Non smoker | 2              |

- **Region**: Which region of the USA does the insured belong to. This parameter has been mapped to numerical values as follows:

  | Region    | Assigned Value |
  | --------- | -------------- |
  | Northwest | 1              |
  | Northeast | 2              |
  | Southwest | 3              |
  | Southeast | 4              |

- **Charges**: Charges for the insurance in USD. Floating value quantity.

## Objectives

1. Load the data as a pandas dataframe.
2. Clean the data, taking care of the blank entries.
3. Run exploratory data analysis (EDA) and identify the attributes that most affect the charges.
4. Develop single variable and multi-variable Linear Regression models for predicting the charges.
5. Use Ridge Regression to refine the performance of Linear Regression models.

### Hey, [Visit my portfolio](https://amanbhattarai.com.np)

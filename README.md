# DSI Assessment Task 2 - Data Analysis Project

## Project Overview
This repository contains the **DSI Assessment Task 2** project for the Data Science and Innovation program.  
The project involves **dataset exploration, literature review, problem definition, and approach planning**, covering all stages of the assignment.  

---
## Dataset Selected

> Credit score classification
https://www.kaggle.com/datasets/parisrohan/credit-score-classification
---
## Data Dictionary
# Diccionario de Datos - Credit Score Classification

| Columna                     | Tipo de Dato       | Descripción                                                                                 |
|------------------------------|------------------|---------------------------------------------------------------------------------------------|
| **ID**                        | Identificador     | ID único de cada registro/fila.                                                            |
| **Customer_ID**               | Identificador     | ID único del cliente (puede repetirse si hay múltiples registros por cliente).             |
| **Month**                     | Temporal          | Mes del año correspondiente al registro.                                                   |
| **Name**                      | Categórico        | Nombre del cliente.                                                                        |
| **Age**                       | Numérico          | Edad del cliente.                                                                          |
| **SSN**                       | Identificador     | Número de Seguridad Social del cliente.                                                   |
| **Occupation**                | Categórico        | Ocupación del cliente.                                                                     |
| **Annual_Income**             | Numérico          | Ingreso anual del cliente.                                                                 |
| **Monthly_Inhand_Salary**     | Numérico          | Salario mensual neto (“in-hand”).                                                         |
| **Num_Bank_Accounts**         | Numérico          | Número de cuentas bancarias que posee el cliente.                                          |
| **Num_Credit_Card**           | Numérico          | Número de tarjetas de crédito en posesión del cliente.                                     |
| **Interest_Rate**             | Numérico          | Tasa de interés aplicada al cliente (sobre préstamos o tarjetas).                         |
| **Num_of_Loan**               | Numérico          | Número de préstamos que tiene el cliente.                                                 |
| **Type_of_Loan**              | Categórico        | Tipos de préstamos que tiene el cliente (personal, estudiantil, hipotecario, etc.).       |
| **Delay_from_due_date**       | Numérico          | Días de retraso promedio respecto a la fecha de pago.                                      |
| **Num_of_Delayed_Payment**    | Numérico          | Número de pagos realizados con retraso.                                                   |
| **Changed_Credit_Limit**      | Numérico          | Porcentaje de cambio en el límite de crédito del cliente.                                 |
| **Num_Credit_Inquiries**      | Numérico          | Cantidad de consultas de crédito realizadas sobre el cliente.                              |
| **Credit_Mix**                | Categórico        | Composición de tipos de crédito del cliente (tarjetas, préstamos, hipotecas, etc.).       |
| **Outstanding_Debt**          | Numérico          | Deuda pendiente total del cliente.                                                        |
| **Credit_Utilization_Ratio**  | Numérico          | Porcentaje de crédito utilizado en comparación con el disponible.                         |
| **Credit_History_Age**        | Temporal/Número   | Antigüedad del historial crediticio del cliente (en años o meses).                        |
| **Payment_of_Min_Amount**     | Categórico        | Indica si el cliente pagó solo el monto mínimo (Yes) o pagó más (No).                     |
| **Total_EMI_per_month**       | Numérico          | Total de cuotas mensuales (EMI) que paga el cliente.                                      |
| **Amount_invested_monthly**   | Numérico          | Monto que el cliente invierte mensualmente.                                               |
| **Payment_Behaviour**         | Categórico        | Comportamiento de pago del cliente (puntualidad, retrasos frecuentes, etc.).              |
| **Monthly_Balance**           | Numérico          | Saldo mensual restante en su cuenta bancaria.                                             |
| **Credit_Score** *(Target)*   | Categórico        | Variable a predecir: calificación crediticia del cliente en categorías como Poor, Standard, Good. |

## How to open this project with Google Colab

### 1. Open Colab Notebook from GitHub
To open a Jupyter Notebook from GitHub in Google Colab, follow these steps:

![Open Notebook](https://raw.githubusercontent.com/Nelkit/DSI-AT2-data-analysis-project/master/images/open_notebook.gif)

### 2. Copy Dataset to the Notebook Folder in Google Colab
To use a dataset in the notebook, follow these steps:

![Add Data](https://raw.githubusercontent.com/Nelkit/DSI-AT2-data-analysis-project/master/images/add_data_to_notebook2.png)

### 3. Commit Changes to the Correct Branch in GitHub
Once you have made modifications, commit them to the branch that has your name.

![Commit Changes](https://raw.githubusercontent.com/Nelkit/DSI-AT2-data-analysis-project/master/images/commit_changes.gif)

Now your modifications are successfully saved in the repository!

---

## Stage 1 – Report
The Stage 1 report includes:  
- **Problem Definition**: Context, research questions, and business/research need.  
- **Literature Review**: Summary of 5–7 relevant papers.  
- **Approach**: Planned methodology, tools, and Stage 2 timeline.  
- **Data**: Dataset description, exploratory analysis, and data preparation steps.  

---

## File Structure (Example)
```
DSI-AT2-data-analysis-project/
│
├── notebooks/ # Google Colab notebooks
│ └── DSI_AT2_data_analysis_project.ipynb
├── data/ # Raw and processed datasets
├── images/ # Instruction images and figures
└── README.md
```


---

## Usage Notes
- Always work in your **own branch** and commit changes regularly.  
- Keep datasets in the `data/` folder for consistency.  
- Use Colab’s runtime with Python 3 and necessary libraries (listed in each notebook).  
- Merge notebooks and code into the main branch only after peer review.

---

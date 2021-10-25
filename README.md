## Demand sensing example project

> Important: these data are from an actual client and must remain confidential

### The business scenario

Cliente-X has given you a sample of their data.  Inside of the data folder are data
corresponding to seven of their points of sale (POS) that they regularly work with.  To
keep everything confidential we just refer to the products and the points of sale
by their numeric identifiers.

The client has stated that they have around 30,000 individual POSs all throughout
Mexico.  The ultimate goal of the client is to build an intelligent system that
will help them predict the suggested order quantity of each product.  To achieve this
the final solution would incorporate demand with real-time inventory and other factors.

The goal of this project is not to produce a final solution.  The Cliente-X is asking that
you carry out some EDA and some initial modeling to get to know the data better and to
help ensure the overall project gets started on the right foot.

> The goal of the project is not to create something complicated--
it is to do something specific, do it well and be able to explain what you did

### Business opportunities

Cliente-X has asked you to create a forecasting model.  Forecasting is the process of
making predictions based on past and present data.

There are two ways that you can do this:

1. Opportunity 1 - For a given time window say 7 days be predict the ‘composite demand’ or total number of ‘piezas’.   
2. Opportunity 2 - For a given time window say 7 days be able to predict the demand for any SKU.

### Becoming specialized

Everyone will load the data, transform it, run a model and visualize the results.
You do not have to do this with equal emphesis though.  If you want focus on a
specific area of data science here are some suggestions.

* **Data Engineer track** - Build a data pipeline, create a feature store, use Kedro and Docker to organize
* **ML track** - Try to solve opportunity 2, use a method that will allow SHAP
* **Data Translator track** - Focus on visualization and interpretation of results (build a dashboard with plotly dash)

### Getting started

1. Clone the repository to your machine by clicking on the **code** button.

```bash
~$ git clone https://github.com/neoris-ai/semana-i-project.git
```

Now you are ready to go.

> Please be reminded that we are asking not to reproduce or make any of the data used here public


### Useful Resources

* [Github guides](https://guides.github.com/activities/hello-world/)
* [Time-series data in pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html)
* [Getting started with prophet](https://facebook.github.io/prophet/docs/quick_start.html)
* [Parquet files](https://databricks.com/glossary/what-is-parquet)
* [plotly time-series](https://plotly.com/python/time-series/)


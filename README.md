The aim of this task is to build an interactive dashboard for a company's sales and profits metrics. This project is a build up of the skills acquired to build the Adidas Sales dashboard in Excel  as the data used to complete it is not from one, but multiple data sources making it more complex to build as more tools such as Power Query and Power Pivot are leveraged. Firstly, the Power Query editor is launched and the datasets are loaded into different queries. The data was cleaned/transformed by changing column data types as well as adding/removing columns. A 'Calendar' table in a separate query was created using Power Query to make the dashboard dynamic by performing time intelligent calculations with DAX in order to compare metrics such as sales in one year versus sales in the previous year. The queries are then loaded into the data model and then relationships were created between the tables in ERD form using Rob Collie methodology putting the 'Sales' table at the bottom and the other dimension tables at the top. The dimension tables were all linked to the 'Sales' table using the keys that they have in common with it. For example, the 'Products' and 'Sales' tables are connected using the the product key column which is contained in both tables. Pivot tables and measures using DAX are created in order to create the visualisations that are on the dashboard. Finally, the relevant slicers are inserted their connections are reported.

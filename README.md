# Carbon-Emission-Analysis

Now, let's look up the data

- # Product_emissions

  







## Which products contribute the most to carbon emissions?




```
SELECT product_name,carbon_footprint_pcf FROM product_emissions GROUP BY product_name
ORDER BY carbon_footprint_pcf DESC LIMIT 10;
```

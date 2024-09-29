# Carbon-Emission-Analysis

Now, let's look up the data

- ## Product_emissions
```
SELECT * FROM product_emissions LIMIT 5;
```


  







## Which products contribute the most to carbon emissions?




```
SELECT product_name,carbon_footprint_pcf FROM product_emissions GROUP BY product_name
ORDER BY carbon_footprint_pcf DESC LIMIT 10;
```

| product_name                                                                                                                       | carbon_footprint_pcf | 
| ---------------------------------------------------------------------------------------------------------------------------------: | -------------------: | 
| Wind Turbine G128 5 Megawats                                                                                                       | 3718044              | 
| Wind Turbine G132 5 Megawats                                                                                                       | 3276187              | 
| Wind Turbine G114 2 Megawats                                                                                                       | 1532608              | 
| Wind Turbine G90 2 Megawats                                                                                                        | 1251625              | 
| Land Cruiser Prado. FJ Cruiser. Dyna trucks. Toyoace.IMV def unit.                                                                 | 191687               | 
| Retaining wall structure with a main wall (sheet pile): 136 tonnes of steel sheet piles and 4 tonnes of tierods per 100 meter wall | 167000               | 
| TCDE                                                                                                                               | 99075                | 
| Mercedes-Benz GLE (GLE 500 4MATIC)                                                                                                 | 91000                | 
| Mercedes-Benz S-Class (S 500)                                                                                                      | 85000                | 
| Mercedes-Benz SL (SL 350)                                                                                                          | 72000                | 

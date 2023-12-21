# PacWest-ETL-CF
Using the HIV/AIDS Supply Chain Shipment Pricing Data https://data.usaid.gov/HIV-AIDS/Supply-Chain-Shipment-Pricing-Data/a3rc-nmf6 create an ETL application that

Loads CSV data into a landing table.
Stages the data in the landing table and applies the following transformations
Line item value sum by country 
Delivery date variance (Delivery to Client Date – Delivery Recorded Date) 
Scheduled delivery date variance (Delivery recorded date – Scheduled delivery date) 
Line item total per country per month 
Molecule/test type by country
Loads the data into a final table and can detect new and updated records based on a “last updated” column.

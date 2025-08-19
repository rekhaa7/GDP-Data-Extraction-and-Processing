# GDP-Data-Extraction-and-Processing
This project extracts data on the nominal GDP of the top 10 economies in the world from a Wikipedia page (archived version) and processes it into a clean dataset saved as a CSV file. The data is sourced from the International Monetary Fund (IMF) estimates for 2023, and the final output is a CSV file named Largest_economies.csv containing the country names and their GDP in billion USD, rounded to two decimal places.

Steps:

Scrapes GDP data from Wikipedia using pandas. 

Selects the top 10 economies and IMF 2023 estimates. 

Converts GDP from million USD to billion USD, rounds to two decimal places. 

Saves the data to Largest_economies.csv.

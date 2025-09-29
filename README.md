# What-s-in-an-Avocado-Toast-A-Supply-Chain-Analysis

conduct a supply chain analysis of three ingredients used in avocado toast using the Open Food Facts database. This database contains extensive, openly-sourced information on various foods, including their origins. Through this analysis, you will gain an in-depth understanding of the complex supply chain involved in producing a single dish.

Three pairs of files are provided in the data folder:

A CSV file for each ingredient, such as avocado.csv, with data about each food item and countries of origin.
A TXT file for each ingredient, such as relevant_avocado_categories, containing only the category tags of interest for that food.
Here are some other key points about these files:

Some of the rows of data in each of the three CSV files do not contain relevant data for your investigation. In each dataset, you will need to filter out rows with irrelevant data, based on values in the categories_tags column. Examples of categories are fruits, vegetables, and fruit-based oils. Filter the DataFrame to include only rows where categories_tags contains one of the tags in the relevant categories for that ingredient.
Each row of data usually has multiple category tags in the categories_tags column. There is a column in each CSV file called origins_tags, which contains strings for the country of origin of each item.

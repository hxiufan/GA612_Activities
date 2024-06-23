Webscraping done on three websites: https://www.juk.co.nz/collections/all-meals, https://freshchef.nz/collections/frontpage, https://www.ripedeli.co.nz/collections/instore-pickup-freezer-meals-bbq-packs-cookbooks-gift-cards

Data cleasing on the three datasets

Merge the three dataframes using concat(), because there is no common columns, so I merged them using outer type

Then indexing the merged dataframe using "Product ID", as it contains all unique values

Create a new dataframe with the 10 items on top of the list from each website.

Multi-level?

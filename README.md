# Ulabox datasets

## Usage Terms and Conditions
Thank you for your interest in Ulabox datasets.
The public datasets in this repository are provided as-is for non-commercial use.
They contain anonymized but real information from a set of purchases and other processes on Ulabox's website.

If you have any question or issue related to these datasets, please open an Issue here.

## About Ulabox
Ulabox is the most successful pure-player online grocery in Spain. It picks up more than €1 million in monthly revenue and asserts a customer satisfaction above 95%. It currently serves Madrid and Barcelona with fresh food and the rest of Spain's peninsula with non perishable items.

## Datasets
### Ulabox orders with categories' partials 2017
File: [ulabox_orders_with_categories_partials_2017.csv](https://github.com/ulabox/datasets/blob/master/data/ulabox_orders_with_categories_partials_2017.csv)

Analysis: [Example analysis in jupyter](https://github.com/ulabox/datasets/blob/master/analysis/ulabox_orders_with_categories_partials_2017.ipynb)

The __ulabox_orders_with_categories_partials_2017__ dataset includes a subset of anonymized __30k orders__ from the beginning of 2017. All kind of customers (around 10k) are represented in this dataset: from urban and rural areas, from first-timers to loyal customers.

#### Data dictionary
The dataset contains 30k samples with the following features:
* __customer__: Anonymized customer's id.
* __order__: Order id, starting from zero.
* __total_items__ : The number of items purchased in the order.
* __discount%__ : The percent of total discount received. For instance, if the customer saves €20 in a €100 order (that is, he had to pay €80), this field will contain a 20.
* __weekday__ : Day of the week when the order was paid. 1=Monday, 7=Sunday.
* __hour__ : The hour of the day the purchase was done. From 00 to 23.
* __Categories' partials__ : Percent of money spent in each of the 8 website's main categories:
  * __Food%__ : Non perishable food, for example: rice, cooking oil, snacks, cookies, sauces, canned food.
  * __Fresh%__ : Fresh and frozen food, for example: fresh tuna, fruits, frozen pizza, salads, meat.
  * __Drinks%__ : All kind of beverages, like: water, juices, wine, alcoholic drinks, milk, soy drinks.
  * __Home%__ : Products for home, from toilet paper to small appliances.
  * __Beauty%__ : Items for cleaning your body and makeup; for example: shampoo, shaving foam, cosmetics.
  * __Health%__ : Medicinal solutions that can be sold in Spain without medic prescription: diet pills, condoms, tooth paste.
  * __Baby%__ : Useful articles if you have a baby: diapers, baby food, baby care.
  * __Pets%__ : Items related with dogs, cats and other pets; like food, toys, sanitary sand.

#### Citation
If you make use of this dataset, please use the following citation:

_The Ulabox Online Supermarket Dataset 2017, accessed from https://www.github.com/ulabox/datasets_


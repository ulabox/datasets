# Ulabox datasets

## Usage Terms and Conditions
Thank you for your interest in Ulabox datasets.
The public datasets in this repository are provided as-is for non-commercial use.
They contain anonymized but real information from purchashes and other processes on Ulabox's website.

## About Ulabox
Ulabox is the most successful pure-player online grocery in Spain. It picks up more than €1 million in monthly revenue and asserts a customer satisfacion above 95%. It currently serves Madrid and Barcelona with fresh food and the rest of Spain's peninsula with non perishable items.

## Datasets
### Ulabox orders with categories' partials 2017
The ulabox-orders-with-partials-2017 dataset includes 30k orders from the beginning of 2017. All kind of customers (around 10k) are represented in this dataset: from urban and rural areas, from first-timers to loyal customers.

#### Data dictionary
The dataset contains the following fields:
* __customer__: Anonymized customer's id.
* __order__: Order id, starting from zero.
* __total_items__ : The number of items purchashed in the order.
* __discount%__ : The percent of total discount received. For instance, if the customer saves €10 in a €100 order (that is, he had to pay €80), this field will contain a 20.
* __weekday__ : Day of the week when the order was paid. 1=Monday, 7=Sunday.
* __hour__ : The hour of the day the purchase was done. From 00 to 23.
* __Categories' partials__ : Percent of money spent in each of the main categories.
  * __Food%__ : Non perishable food, for example: rice, cooking oil, snacks, cookies, sauces, canned food.
  * __Fresh%__ : Fresh and frozen food, for example: fresh tuna, fruits, frozen pizza, salads, meat.
  * __Drinks%__ : All kind of beverages, like: water, juices, wine, alcoholic drinks, milk, soya drinks.
  * __Home%__ : Products for home, from toilet paper to small appliances.
  * __Beauty%__
  * __Health%__
  * __Baby%__
  * __Pets%__

#### Citation
If you make use of this dataset, please use the following citation:

_The Ulabox Online Supermarket Dataset 2017, accessed from https://www.github.com/ulabox/datasets_


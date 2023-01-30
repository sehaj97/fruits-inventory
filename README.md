# fruits-inventory

## Deployed Link
[https://sehaj97.github.io/fruits-inventory/](https://sehaj97.github.io/fruits-inventory/)

## Problem:

Jim Ryan owns a banana themed grocery store in Toronto and orders fresh produce from two
main suppliers: Vasani Fresh and Zeni Fruits. Jim Ryan is looking to improve the store’s
financials by ordering produce from the cheapest supplier. The problem is that Vasani Fresh
and Zeni Fruits change their prices almost every day. Luckily both suppliers have crafty tech
departments that built a consumable API that lists their produce prices. See appendix 1.1.
Jim Ryan has the idea to hire a front-end developer that can build a beautiful dashboard to
display the API data. He has the two following mandatory needs:

1. Build two separate tables to differentiate the produce prices from Vasani Fresh and Zeni
Fruits

2. For each table highlight each row that has the cheaper price, if an item exists for one
supplier and not the other, you may mark that item as the cheaper one. 

Jim Ryan said, if possible, he’d also like the following “flex” features so he can better control
inventory management between the suppliers.

1. Sort functionality between the columns

2. Jim Ryan loves to see his fruit before he buys, create an image previewer of the fruit
that only appears when clicking on a particular row.

3. Sometimes Jim doesn’t want to see particular fruit, create a filter that removes fruits
from appearing in both tables.

4. Create an order estimate for a particular fruit by entering a quantity. The order must not
exceed the limit of both suppliers. When calculating the estimate, you must first order
from the cheaper supplier until the inventory is empty then any remaining estimates
must use the more expensive supplier. Calculate the total cost of the estimate.

a. Example of calculating an estimate of 25 Bananas. 22 would come from Vasani
Fresh since they’re less expensive, but the remaining 3 would come from Zeni
Fruits since Vasani Fresh doesn’t have enough inventory for your order.


Appendix 1.1

[
        {
          fruit_name: "Banana",
          price: 0.75,
          last_updated: "2022-Jan-01",
          inventory_count: 7,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Banana",
          price: 0.79,
          last_updated: "2022-Mar-01",
          inventory_count: 66,
          supplier: "Zeni Fruits",
        },
        {
          fruit_name: "Apple",
          price: 3.0,
          last_updated: "2022-Jan-01",
          inventory_count: 66,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Apple",
          price: 1.77,
          last_updated: "2022-June-02",
          inventory_count: 13,
          supplier: "Zeni Fruits",
        },
        {
          fruit_name: "Dragon Fruit",
          price: 9.0,
          last_updated: "1999-Feb-26",
          inventory_count: 4,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Dragon Fruit",
          price: 8.0,
          last_updated: "2001-Nov-02",
          inventory_count: 5,
          supplier: "Zeni Fruits",
        },
        {
          fruit_name: "Kiwi",
          price: 0.25,
          last_updated: "1996-Jan-25",
          inventory_count: 301,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Kiwi",
          price: 4.0,
          last_updated: "2021-Oct-11",
          inventory_count: 19,
          supplier: "Zeni Fruits",
        },
        {
          fruit_name: "Orange",
          price: 0.99,
          last_updated: "2020-Jun-06",
          inventory_count: 67,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Orange",
          price: 1.25,
          last_updated: "2019-Apr-09",
          inventory_count: 45,
          supplier: "Zeni Fruits",
        },
        {
          fruit_name: "Mango",
          price: 3.29,
          last_updated: "2014-Sep-20",
          inventory_count: 30,
          supplier: "Vasani Fresh",
        },
        {
          fruit_name: "Peaches",
          price: 2.79,
          last_updated: "2015-Oct-14",
          inventory_count: 45,
          supplier: "Zeni Fruits",
        },
      ];
# fruits-inventory

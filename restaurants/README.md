## A restaurant recommendation system.

Based on the data that we have in `restaurants.txt`, create a restaurant recommendation system, by providing the following reports:

1. First five best rated restaurants:
```
   Georgie Porgie: 87
   Mexican Grill: 85
   Queen St. Cafe: 82
   Dumplings R Us: 71
   Deep Fried Everything: 52
```

2. Restaurants grouped by their price:
```
   $: "Queen St. Cafe", "Dumplings R Us", "Deep Fried Everything"
   $$: "Mexican Grill"
   $$$: "Georgie Porgie"
   $$$$: <none>
```

3. Restaurants grouped by their cuisine:
```
   Canadian: "Georgie Porgie"
   Pub Food: "Georgie Porgi, Deep Fried Everything"
   Malaysian: "Queen St. Cafe"
   Thai: "Queen St. Cafe"
   Chinese: "Dumplings R Us", "Flavour Fusion", "Eat In, Take Out"
   Mexican: "Mexican Grill"
```

### Implementation requirements

* We need a Python command-line program.
* OOP required. We need to use classes for representing the restaurant and the cuisine. A reference should be set between the two entities.
* The program should run in two modes:
   1. When giving no parameters: All the above reports should be listed
   2. When giving a restaurant name as parameter: A restaurant representation should be showed
      ```
      Name: Steak House
      Ratting: 82%
      Pricing Category: $$$$
      Cuisine: Steakhouse
      ```

# burke_corp_pizza

The measurements from the Burke Corporation pizza guide, as JSON and Javascript



<br/><br/>

## The what now?

Inevitably, at some time in your life, you will attempt to Google how much of some or another topping, most often cheese, to put on the pizza you're about to make.  It is part of the human condition.  You may hate pizza, and be allergic to every ingredient; you will still do this, at least twice.  Accept your fate.

Once you do, you will be confronted with a range of opinions 3x wide.

Eventually, you'll come to some or another pizza-specific forum.  They, in turn, will point to an older version of a pizza proportioning guide given by a vendor of, amongst other things, pizza toppings, called The Burke Corporation.  We defer to an older version because [the contemporary version](https://www.burkecorp.com/wp-content/uploads/2019/05/Portion-Guide.pdf) has sadly been simplified; older versions have "low medium high" columns, whereas the contemporary only has "medium," and has removed the guides for half-pan and full-pan rectangular pizzas (weirdly, just as they're becoming popular, under the name "Detroit style.")

This dataset is pulled from [the 2011 edition](https://cdn2.hubspot.net/hub/37985/docs/pizzatoppingportionguide_2011.pdf), instead.  None of the retained numbers were changed.



<br/><br/>

## Why this one?

So, look.  There's actually a good reason that pizza recommendations are so different.  It turns out, by example, that CostCo uses about double the per-inch cheese that Domino's does.

And you know what?  Those produce very different results, and they cook differently, and different people like different things.

My opinion is that the Burke Corporation numbers produce a "stereotypical American pizza."  That is, not a New York or a Chicago pizza, but rather the kind of pizza that you'll get in a better generic pizza shop in any random city in the country.  I find this to be an acceptable norm.  I will, subsequently, look for similar datasets for "style" pizzas - New York style, Chicago style, Neapolitan, &amp;c.

This guide provides amounts for

* Sauce
* Cheese
* 25 toppings, two (pepperoni and mushrooms) each in two different forms

Annoyingly, it does not give dough guidance.



<br/><br/>

## Save me some time - put it here

A lot of people are just looking for numbers, and the code is a waste of their time, so, the numbers are also in this document.

Burke vends meats, has good ingredients, and is geared for small restaurants.  You've probably eaten a lot of their food.  [If you're making a pizza shop, look them up](https://www.burkecorp.com/fully-cooked-meats/).



<br/><br/>

# PIZZA TOPPINGS PORTION GUIDE

<table>

  <tr class="headings">
    <th rowspan="2">Topping</th>
    <th rowspan="2">Unit</th>
    <th colspan="3">6 inch</th>
    <th colspan="3">8 inch</th>
    <th colspan="3">10 inch</th>
    <th colspan="3">12 inch</th>
    <th colspan="3">14 inch</th>
    <th colspan="3">16 inch</th>
    <th colspan="3">18 inch</th>
    <th colspan="3">Half pan</th>
    <th colspan="3">Full pan</th>
  </tr>

  <tr class="headings">
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
    <th>Low</th><th>Mid</th><th>Hi</th>
  </tr>

  <tr class="topping PizzaSauce">
    <th class="kind">Pizza Sauce</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1.25</td><td class="s6  wh">2.75</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.75</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">3</td><td class="s12 wm">4</td><td class="s12 wh">5</td>
    <td class="s14 wl">3.75</td><td class="s14 wm">5.75</td><td class="s14 wh">7.5</td>
    <td class="s16 wl">4.75</td><td class="s16 wm">7</td><td class="s16 wh">9</td>
    <td class="s18 wl">6</td><td class="s18 wm">8.25</td><td class="s18 wh">10.25</td>
    <td class="shp wl">5.25</td><td class="shp wm">7.5</td><td class="shp wh">9.5</td>
    <td class="sfp wl">9.25</td><td class="sfp wm">13</td><td class="sfp wh">16.5</td>
  </tr>

  <tr class="topping Cheese">
    <th class="kind">Cheese</th><th class="unit">oz.</th>
    <td class="s6  wl">1</td><td class="s6  wm">1.25</td><td class="s6  wh">2.75</td>
    <td class="s8  wl">1.5</td><td class="s8  wm">2</td><td class="s8  wh">2.75</td>
    <td class="s10 wl">2.5</td><td class="s10 wm">3.25</td><td class="s10 wh">4.5</td>
    <td class="s12 wl">4</td><td class="s12 wm">6</td><td class="s12 wh">7.5</td>
    <td class="s14 wl">5.75</td><td class="s14 wm">7</td><td class="s14 wh">9.25</td>
    <td class="s16 wl">7.25</td><td class="s16 wm">10.5</td><td class="s16 wh">14</td>
    <td class="s18 wl">7.5</td><td class="s18 wm">12</td><td class="s18 wh">15.5</td>
    <td class="shp wl">6.25</td><td class="shp wm">9.5</td><td class="shp wh">12.75</td>
    <td class="sfp wl">13.5</td><td class="sfp wm">20</td><td class="sfp wh">27</td>
  </tr>

  <tr class="topping Pepperoni">
    <th class="kind">Pepperoni</th><th class="unit">slices</th>
    <td class="s6  wl">4</td><td class="s6  wm">5</td><td class="s6  wh">12</td>
    <td class="s8  wl">5</td><td class="s8  wm">8</td><td class="s8  wh">12</td>
    <td class="s10 wl">8</td><td class="s10 wm">16</td><td class="s10 wh">20</td>
    <td class="s12 wl">16</td><td class="s12 wm">20</td><td class="s12 wh">28</td>
    <td class="s14 wl">20</td><td class="s14 wm">28</td><td class="s14 wh">40</td>
    <td class="s16 wl">24</td><td class="s16 wm">40</td><td class="s16 wh">48</td>
    <td class="s18 wl">32</td><td class="s18 wm">48</td><td class="s18 wh">64</td>
    <td class="shp wl">32</td><td class="shp wm">44</td><td class="shp wh">60</td>
    <td class="sfp wl">64</td><td class="sfp wm">88</td><td class="sfp wh">116</td>
  </tr>

  <tr class="topping Pepperoni">
    <th class="kind">Pepperoni</th><th class="unit">oz.</th>
    <td class="s6  wl">0.25</td><td class="s6  wm">0.33</td><td class="s6  wh">0.75</td>
    <td class="s8  wl">0.33</td><td class="s8  wm">0.5</td><td class="s8  wh">0.75</td>
    <td class="s10 wl">0.5</td><td class="s10 wm">1</td><td class="s10 wh">1.25</td>
    <td class="s12 wl">1</td><td class="s12 wm">1.25</td><td class="s12 wh">1.75</td>
    <td class="s14 wl">1.25</td><td class="s14 wm">1.75</td><td class="s14 wh">2.5</td>
    <td class="s16 wl">1.5</td><td class="s16 wm">2.5</td><td class="s16 wh">3</td>
    <td class="s18 wl">2</td><td class="s18 wm">3</td><td class="s18 wh">4</td>
    <td class="shp wl">1.75</td><td class="shp wm">2.75</td><td class="shp wh">3.75</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">5.5</td><td class="sfp wh">7.25</td>
  </tr>

  <tr class="topping CookedSausage">
    <th class="kind">Cooked Sausage</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping RawSausage">
    <th class="kind">Raw Sausage</th><th class="unit">oz</th>
    <td class="s6  wl">1</td><td class="s6  wm">1.25</td><td class="s6  wh">3.25</td>
    <td class="s8  wl">1.5</td><td class="s8  wm">2.5</td><td class="s8  wh">3.25</td>
    <td class="s10 wl">2.5</td><td class="s10 wm">4</td><td class="s10 wh">5.25</td>
    <td class="s12 wl">4</td><td class="s12 wm">6</td><td class="s12 wh">7.5</td>
    <td class="s14 wl">2.25</td><td class="s14 wm">8</td><td class="s14 wh">10.5</td>
    <td class="s16 wl">7</td><td class="s16 wm">10.5</td><td class="s16 wh">14</td>
    <td class="s18 wl">8.5</td><td class="s18 wm">13.25</td><td class="s18 wh">17.5</td>
    <td class="shp wl">8</td><td class="shp wm">12</td><td class="shp wh">16</td>
    <td class="sfp wl">16</td><td class="sfp wm">24</td><td class="sfp wh">32</td>
  </tr>

  <tr class="topping CookedBeef">
    <th class="kind">Cooked Beef</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping Bacon">
    <th class="kind">Bacon</th><th class="unit">oz.</th>
    <td class="s6  wl">0.25</td><td class="s6  wm">0.5</td><td class="s6  wh">1.5</td>
    <td class="s8  wl">0.5</td><td class="s8  wm">1</td><td class="s8  wh">1.5</td>
    <td class="s10 wl">1</td><td class="s10 wm">1.5</td><td class="s10 wh">2.25</td>
    <td class="s12 wl">1.5</td><td class="s12 wm">2.5</td><td class="s12 wh">3.5</td>
    <td class="s14 wl">1.75</td><td class="s14 wm">3.5</td><td class="s14 wh">4.25</td>
    <td class="s16 wl">2.25</td><td class="s16 wm">4.25</td><td class="s16 wh">6.25</td>
    <td class="s18 wl">3.25</td><td class="s18 wm">6</td><td class="s18 wh">7.5</td>
    <td class="shp wl">2.75</td><td class="shp wm">5</td><td class="shp wh">7</td>
    <td class="sfp wl">5.75</td><td class="sfp wm">9.5</td><td class="sfp wh">13</td>
  </tr>

  <tr class="topping Canadian-StyleBacon">
    <th class="kind">Canadian-Style Bacon</th><th class="unit">oz.</th>
    <td class="s6  wl">0.25</td><td class="s6  wm">0.33</td><td class="s6  wh">0.75</td>
    <td class="s8  wl">0.33</td><td class="s8  wm">0.5</td><td class="s8  wh">0.75</td>
    <td class="s10 wl">0.5</td><td class="s10 wm">1</td><td class="s10 wh">1.25</td>
    <td class="s12 wl">1</td><td class="s12 wm">1.25</td><td class="s12 wh">1.75</td>
    <td class="s14 wl">1.25</td><td class="s14 wm">1.75</td><td class="s14 wh">2.5</td>
    <td class="s16 wl">1.5</td><td class="s16 wm">2.5</td><td class="s16 wh">3</td>
    <td class="s18 wl">2</td><td class="s18 wm">3</td><td class="s18 wh">4</td>
    <td class="shp wl">1.75</td><td class="shp wm">2.75</td><td class="shp wh">3.75</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">5.5</td><td class="sfp wh">7.25</td>
  </tr>

  <tr class="topping DicedHam">
    <th class="kind">Diced Ham</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping GenoaSalami">
    <th class="kind">Genoa Salami</th><th class="unit">oz.</th>
    <td class="s6  wl">0.25</td><td class="s6  wm">0.33</td><td class="s6  wh">0.75</td>
    <td class="s8  wl">0.33</td><td class="s8  wm">0.5</td><td class="s8  wh">0.75</td>
    <td class="s10 wl">0.5</td><td class="s10 wm">1</td><td class="s10 wh">1.25</td>
    <td class="s12 wl">1</td><td class="s12 wm">1.25</td><td class="s12 wh">1.75</td>
    <td class="s14 wl">1.25</td><td class="s14 wm">1.75</td><td class="s14 wh">2.5</td>
    <td class="s16 wl">1.5</td><td class="s16 wm">2.5</td><td class="s16 wh">3</td>
    <td class="s18 wl">2</td><td class="s18 wm">3</td><td class="s18 wh">4</td>
    <td class="shp wl">1.75</td><td class="shp wm">2.75</td><td class="shp wh">3.75</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">5.5</td><td class="sfp wh">7.25</td>
  </tr>

  <tr class="topping ChickenStrips">
    <th class="kind">Chicken Strips</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping Meatballs">
    <th class="kind">Meatballs</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.25</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.25</td>
    <td class="s10 wl">2</td><td class="s10 wm">2.5</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">2.5</td><td class="s12 wm">3.75</td><td class="s12 wh">5</td>
    <td class="s14 wl">3.5</td><td class="s14 wm">5</td><td class="s14 wh">6.75</td>
    <td class="s16 wl">4.5</td><td class="s16 wm">6.75</td><td class="s16 wh">8.75</td>
    <td class="s18 wl">5.5</td><td class="s18 wm">8.5</td><td class="s18 wh">11</td>
    <td class="shp wl">5</td><td class="shp wm">7.5</td><td class="shp wh">10</td>
    <td class="sfp wl">10</td><td class="sfp wm">15</td><td class="sfp wh">20</td>
  </tr>

  <tr class="topping TacoMeatCrumbles">
    <th class="kind">Taco Meat Crumbles</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping ChorizoCrumbles">
    <th class="kind">Chorizo Crumbles</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping ShreddedBeef">
    <th class="kind">Shredded Beef</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">2.5</td>
    <td class="s8  wl">1.25</td><td class="s8  wm">2</td><td class="s8  wh">2.5</td>
    <td class="s10 wl">2</td><td class="s10 wm">3</td><td class="s10 wh">4</td>
    <td class="s12 wl">3</td><td class="s12 wm">4.5</td><td class="s12 wh">5.75</td>
    <td class="s14 wl">4</td><td class="s14 wm">6</td><td class="s14 wh">8</td>
    <td class="s16 wl">5.25</td><td class="s16 wm">7.75</td><td class="s16 wh">10.5</td>
    <td class="s18 wl">6.5</td><td class="s18 wm">10</td><td class="s18 wh">13.25</td>
    <td class="shp wl">6</td><td class="shp wm">9</td><td class="shp wh">12</td>
    <td class="sfp wl">12</td><td class="sfp wm">18</td><td class="sfp wh">24</td>
  </tr>

  <tr class="topping Andouille">
    <th class="kind">Andouille</th><th class="unit">slices</th>
    <td class="s6  wl">3</td><td class="s6  wm">4</td><td class="s6  wh">8</td>
    <td class="s8  wl">3</td><td class="s8  wm">5</td><td class="s8  wh">8</td>
    <td class="s10 wl">5</td><td class="s10 wm">11</td><td class="s10 wh">13</td>
    <td class="s12 wl">11</td><td class="s12 wm">13</td><td class="s12 wh">19</td>
    <td class="s14 wl">13</td><td class="s14 wm">19</td><td class="s14 wh">27</td>
    <td class="s16 wl">16</td><td class="s16 wm">27</td><td class="s16 wh">32</td>
    <td class="s18 wl">21</td><td class="s18 wm">32</td><td class="s18 wh">43</td>
    <td class="shp wl">21</td><td class="shp wm">29</td><td class="shp wh">40</td>
    <td class="sfp wl">43</td><td class="sfp wm">59</td><td class="sfp wh">77</td>
  </tr>

  <tr class="topping Anchovy">
    <th class="kind">Anchovy</th><th class="unit">pc.</th>
    <td class="s6  wl">2</td><td class="s6  wm">3</td><td class="s6  wh">6</td>
    <td class="s8  wl">3</td><td class="s8  wm">4</td><td class="s8  wh">6</td>
    <td class="s10 wl">4</td><td class="s10 wm">6</td><td class="s10 wh">8</td>
    <td class="s12 wl">7</td><td class="s12 wm">8</td><td class="s12 wh">10</td>
    <td class="s14 wl">9</td><td class="s14 wm">10</td><td class="s14 wh">12</td>
    <td class="s16 wl">11</td><td class="s16 wm">13</td><td class="s16 wh">16</td>
    <td class="s18 wl">13</td><td class="s18 wm">16</td><td class="s18 wh">18</td>
    <td class="shp wl">14</td><td class="shp wm">17</td><td class="shp wh">20</td>
    <td class="sfp wl">28</td><td class="sfp wm">34</td><td class="sfp wh">45</td>
  </tr>

  <tr class="topping Peppers">
    <th class="kind">Peppers</th><th class="unit">oz.</th>
    <td class="s6  wl">0.5</td><td class="s6  wm">1</td><td class="s6  wh">2</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">2</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">1.75</td><td class="s12 wm">2.75</td><td class="s12 wh">4.25</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">4</td><td class="s14 wh">5.25</td>
    <td class="s16 wl">3.25</td><td class="s16 wm">5.75</td><td class="s16 wh">7.5</td>
    <td class="s18 wl">4.75</td><td class="s18 wm">8</td><td class="s18 wh">11.5</td>
    <td class="shp wl">3.5</td><td class="shp wm">6</td><td class="shp wh">8</td>
    <td class="sfp wl">7</td><td class="sfp wm">11.75</td><td class="sfp wh">15.5</td>
  </tr>

  <tr class="topping Onions">
    <th class="kind">Onions</th><th class="unit">oz.</th>
    <td class="s6  wl">0.5</td><td class="s6  wm">1</td><td class="s6  wh">2</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">2</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">1.75</td><td class="s12 wm">2.75</td><td class="s12 wh">4.25</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">4</td><td class="s14 wh">5.25</td>
    <td class="s16 wl">3.25</td><td class="s16 wm">5.75</td><td class="s16 wh">7.5</td>
    <td class="s18 wl">4.75</td><td class="s18 wm">8</td><td class="s18 wh">11.5</td>
    <td class="shp wl">3.5</td><td class="shp wm">6</td><td class="shp wh">8</td>
    <td class="sfp wl">7</td><td class="sfp wm">11.75</td><td class="sfp wh">15.5</td>
  </tr>

  <tr class="topping CannedMushrooms">
    <th class="kind">Canned Mushrooms</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1.25</td><td class="s6  wh">2.25</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.75</td><td class="s8  wh">2.25</td>
    <td class="s10 wl">1.25</td><td class="s10 wm">2.25</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">1.5</td><td class="s12 wm">3</td><td class="s12 wh">4.5</td>
    <td class="s14 wl">2.25</td><td class="s14 wm">4.5</td><td class="s14 wh">7.25</td>
    <td class="s16 wl">4.25</td><td class="s16 wm">6</td><td class="s16 wh">8.5</td>
    <td class="s18 wl">4.75</td><td class="s18 wm">7.25</td><td class="s18 wh">11</td>
    <td class="shp wl">3.75</td><td class="shp wm">6.5</td><td class="shp wh">7.25</td>
    <td class="sfp wl">8.5</td><td class="sfp wm">9.5</td><td class="sfp wh">12.75</td>
  </tr>

  <tr class="topping FreshSlicedMushrooms">
    <th class="kind">Fresh Sliced Mushrooms</th><th class="unit">oz.</th>
    <td class="s6  wl">0.25</td><td class="s6  wm">0.5</td><td class="s6  wh">1</td>
    <td class="s8  wl">0.5</td><td class="s8  wm">0.75</td><td class="s8  wh">1</td>
    <td class="s10 wl">0.75</td><td class="s10 wm">1.25</td><td class="s10 wh">2</td>
    <td class="s12 wl">1</td><td class="s12 wm">1.75</td><td class="s12 wh">2.75</td>
    <td class="s14 wl">1.5</td><td class="s14 wm">2.75</td><td class="s14 wh">3.75</td>
    <td class="s16 wl">1.75</td><td class="s16 wm">2.75</td><td class="s16 wh">4.75</td>
    <td class="s18 wl">2.75</td><td class="s18 wm">4.75</td><td class="s18 wh">7.5</td>
    <td class="shp wl">1.75</td><td class="shp wm">3.25</td><td class="shp wh">5</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">6.5</td><td class="sfp wh">10.5</td>
  </tr>

  <tr class="topping DicedTomatoes">
    <th class="kind">Diced Tomatoes</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1.25</td><td class="s6  wh">2</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.75</td><td class="s8  wh">2</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.5</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">2.25</td><td class="s12 wm">3.5</td><td class="s12 wh">5.25</td>
    <td class="s14 wl">2.75</td><td class="s14 wm">4.25</td><td class="s14 wh">6</td>
    <td class="s16 wl">3</td><td class="s16 wm">5.5</td><td class="s16 wh">8.5</td>
    <td class="s18 wl">3.25</td><td class="s18 wm">6.25</td><td class="s18 wh">10</td>
    <td class="shp wl">3</td><td class="shp wm">5.5</td><td class="shp wh">8.25</td>
    <td class="sfp wl">4</td><td class="sfp wm">10</td><td class="sfp wh">16</td>
  </tr>

  <tr class="topping SlicedOlives">
    <th class="kind">Sliced Olives</th><th class="unit">oz.</th>
    <td class="s6  wl">0.5</td><td class="s6  wm">1</td><td class="s6  wh">2</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">2</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">1.75</td><td class="s12 wm">2.75</td><td class="s12 wh">4.25</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">4</td><td class="s14 wh">5.25</td>
    <td class="s16 wl">3.25</td><td class="s16 wm">5.75</td><td class="s16 wh">7.5</td>
    <td class="s18 wl">4.75</td><td class="s18 wm">8</td><td class="s18 wh">11.5</td>
    <td class="shp wl">3.5</td><td class="shp wm">6</td><td class="shp wh">8</td>
    <td class="sfp wl">7</td><td class="sfp wm">11.75</td><td class="sfp wh">15.5</td>
  </tr>

  <tr class="topping Pineapple">
    <th class="kind">Pineapple</th><th class="unit">oz.</th>
    <td class="s6  wl">0.5</td><td class="s6  wm">1</td><td class="s6  wh">2.25</td>
    <td class="s8  wl">0.75</td><td class="s8  wm">1.25</td><td class="s8  wh">2.25</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.75</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">2</td><td class="s12 wm">3.5</td><td class="s12 wh">5.25</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">4</td><td class="s14 wh">6</td>
    <td class="s16 wl">3</td><td class="s16 wm">5.5</td><td class="s16 wh">8.25</td>
    <td class="s18 wl">3.5</td><td class="s18 wm">6.25</td><td class="s18 wh">10.5</td>
    <td class="shp wl">3</td><td class="shp wm">5.5</td><td class="shp wh">8.5</td>
    <td class="sfp wl">5.5</td><td class="sfp wm">10</td><td class="sfp wh">16</td>
  </tr>

  <tr class="topping BananaPeppers">
    <th class="kind">Banana Peppers</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">1.75</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">1.75</td>
    <td class="s10 wl">1.25</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">2</td><td class="s12 wm">3</td><td class="s12 wh">4.5</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">3.5</td><td class="s14 wh">5</td>
    <td class="s16 wl">2.5</td><td class="s16 wm">4.75</td><td class="s16 wh">7</td>
    <td class="s18 wl">2.75</td><td class="s18 wm">5.25</td><td class="s18 wh">8.25</td>
    <td class="shp wl">2.5</td><td class="shp wm">4.75</td><td class="shp wh">7</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">8.25</td><td class="sfp wh">13.25</td>
  </tr>

  <tr class="topping ArtichokeHearts">
    <th class="kind">Artichoke Hearts</th><th class="unit">oz.</th>
    <td class="s6  wl">0.5</td><td class="s6  wm">1</td><td class="s6  wh">2.25</td>
    <td class="s8  wl">0.75</td><td class="s8  wm">1.25</td><td class="s8  wh">2.25</td>
    <td class="s10 wl">1.5</td><td class="s10 wm">2.75</td><td class="s10 wh">3.5</td>
    <td class="s12 wl">2</td><td class="s12 wm">3.5</td><td class="s12 wh">5.25</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">4</td><td class="s14 wh">6</td>
    <td class="s16 wl">3</td><td class="s16 wm">5.5</td><td class="s16 wh">8.25</td>
    <td class="s18 wl">3.5</td><td class="s18 wm">6.25</td><td class="s18 wh">10.5</td>
    <td class="shp wl">3</td><td class="shp wm">5.5</td><td class="shp wh">8.5</td>
    <td class="sfp wl">5.5</td><td class="sfp wm">10</td><td class="sfp wh">16</td>
  </tr>

  <tr class="topping Corn">
    <th class="kind">Corn</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">1.75</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">1.75</td>
    <td class="s10 wl">1.25</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">2</td><td class="s12 wm">3</td><td class="s12 wh">4.5</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">3.5</td><td class="s14 wh">5</td>
    <td class="s16 wl">2.5</td><td class="s16 wm">4.75</td><td class="s16 wh">7</td>
    <td class="s18 wl">2.75</td><td class="s18 wm">5.25</td><td class="s18 wh">8.25</td>
    <td class="shp wl">2.5</td><td class="shp wm">4.75</td><td class="shp wh">7</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">8.25</td><td class="sfp wh">13.25</td>
  </tr>

  <tr class="topping BlackBeans">
    <th class="kind">Black Beans</th><th class="unit">oz.</th>
    <td class="s6  wl">0.75</td><td class="s6  wm">1</td><td class="s6  wh">1.75</td>
    <td class="s8  wl">1</td><td class="s8  wm">1.5</td><td class="s8  wh">1.75</td>
    <td class="s10 wl">1.25</td><td class="s10 wm">2.25</td><td class="s10 wh">3</td>
    <td class="s12 wl">2</td><td class="s12 wm">3</td><td class="s12 wh">4.5</td>
    <td class="s14 wl">2.5</td><td class="s14 wm">3.5</td><td class="s14 wh">5</td>
    <td class="s16 wl">2.5</td><td class="s16 wm">4.75</td><td class="s16 wh">7</td>
    <td class="s18 wl">2.75</td><td class="s18 wm">5.25</td><td class="s18 wh">8.25</td>
    <td class="shp wl">2.5</td><td class="shp wm">4.75</td><td class="shp wh">7</td>
    <td class="sfp wl">3.5</td><td class="sfp wm">8.25</td><td class="sfp wh">13.25</td>
  </tr>

</table>

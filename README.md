## **Introduce 🍺**

APIs free with nearly 700 dishes and 15 menus. You can interact with them simply!
<br />

#### **Demo:** https://food-g-app.web.app/shop/best-foods

<br />

## **Our best menu 🍔**

- BBQ
- Breads
- Drinks
- Ice cream
- Porks
- etc...
  <br />
  <br />

## **How to use? 🕵️**

Because this api is built on top of **Json Server** you can use methods like **sort, title_like, q**, etc. 👏

**🍩 Read more:**

```
https://github.com/typicode/json-server#routes
```

**🍞 Using:**

```
https://ig-food-menus.herokuapp.com/<params>
```

**🍕 Examples:**

```js
// use fetch
fetch('https://ig-food-menus.herokuapp.com/burgers')
  .then((response) => response.json())
  .then((data) => console.log(data));

// what we have?
[
  {
    id: ...,
    img: ...,
    name: ...,
    dsc: ...,
    price: ...,
    rate: ...,
    country: ...
  },
  {
    ...
  },
  ...
  // and so on!
]
```

**🍣 Params bonus**

```js
// get all data of existing dishes
/our-foods

// take the number object of dishes according to the menu
// use for pagination, infinite scrolling
/pagination

// and something look like
{
  "bbqs": 59,
  "best-foods": 60,
  ...
}
```

**🍻 Usable params**

```js
/bbqs
/best-foods
/breads
/burgers
/chocolates
/desserts
/drinks
/fried-chicken
/ice-cream
/pizzas
/porks
/sandwiches
/sausages
/steaks
// and if you like any other menus or dishes, please comment
// I will try to add them as soon as possible. Enjoy!!
```

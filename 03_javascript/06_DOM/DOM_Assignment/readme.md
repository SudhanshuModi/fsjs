# Solution set

## Assignment 1

### task1

```javascript
let const = document.querySelector("footer>ul")
let const = ul.querySelectorAll("li")
li.forEach( (item) => item.remove() )
```

### task2

```javascript
const text = document.querySelector("input[type='text']");
text.placeholder = "Search My Project";
```

### task3

```javascript
const p = document.querySelector("p");
p.querySelectorAll("span")[1].innerText = "an Employee";
p.querySelectorAll("span")[2].innerText = "iNeuron Intelligence Pvt Ltd.";
```

### task4

```javascript
const image = document.querySelector("img");
image.src =
    "https://hiteshchoudhary.com/static/a8d73d1aac4c79e9bb689640e6090367/2eaab/person-image.jpg";
```

### task5

```javascript
const buttonContainer = document.querySelector(".hero-right-section-btns");
const button = document.createElement("button");
button.innerText = "Support Me";
buttonContainer.appendChild(button);
```

## Assignment 2

### task 1

```javascript
const h3 = document.querySelectorAll(".accordian>h3");
h3.forEach((item) => (item.style.background = "#dedae6"));

const para = document.querySelectorAll(".accordian>p");
para[2].style.display = "block";
para[3].style.display = "block";
```

### task 2

```javascript
const h3 = document.querySelectorAll(".accordian>h3");
h3.forEach((item) => (item.style.background = "#dedae6"));

const cloneH3 = document.querySelectorAll(".accordian")[0].cloneNode(true);
cloneH3.querySelector("h3").innerText = "Skills";
cloneH3.querySelector("p").innerText =
    "I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github.";
cloneH3.querySelector("p").style.display = "block";
document.querySelector(".accordian-wrapper").appendChild(cloneH3);
```

## Assignment 3

```javascript
const text = document.querySelectorAll(".mainWrapper input[type='text']");
text.forEach((item) => {
    item.placeholder = "FSJS 2.0";
});

const email = document.querySelectorAll(".mainWrapper input[type='email']");
email.forEach((item) => {
    item.placeholder = "fsjs@ineuron.ai";
});

const textArea = document.querySelectorAll(".mainWrapper textarea");
textArea.forEach((item) => {
    item.placeholder = "Hello World";
});
```

## Assignment 4

```javascript
document.querySelector(".barbarian").lastElementChild.style.background =
    "#EDBF69";
document.querySelector(".archer").lastElementChild.style.background = "#E6425E";
document.querySelector(".giant").lastElementChild.style.background = "#F4BE2C";
document.querySelector(".goblin").lastElementChild.style.background = "#4DD637";
document.querySelector(".wizard").lastElementChild.style.background = "#12B0E8";

const oneThird = document.querySelectorAll(".one-third");
oneThird.forEach((items) => {
    items.style.color = "white";
});
```

## Assignment 5

```javascript
const element = document.querySelector(".nav-links + div");
const proSubscription = element.querySelector("a").cloneNode(true);
proSubscription.innerText = "Pro Subscription";
element.appendChild(proSubscription);

const aContainer = document.querySelector(".tags-container > div");
const a = document.createElement("a");
a.innerText = "Chinese (7)";
aContainer.appendChild(a);

const recipeGallery = document.querySelector(".recipe-gallery");
const div = document.createElement("div");
div.classList.add("card");
div.innerHTML = "<h1>add 6th card here</h1>";
recipeGallery.appendChild(div);

const recipeText = document.querySelectorAll(".recipe-text");
recipeText.forEach((item) => {
    item.style.color = "#2827CC";
});
```

## Assignment 6

### task 1

```javascript
document.querySelector("header img").src = "./assets/ineuron-logo.png";
```

### task 2

```javascript
document.querySelector(".app_price span").innerText = "$10";
```

## Assignment 7

### task 1

```javascript
const language = document.querySelectorAll(".main__languages a");
language.forEach((item) => {
    if (item.innerText.includes("2.0")) {
        item.remove();
    }
});
```

### task 2

```javascript
const input = document.querySelector(".main__form-input");
input.disabled = false;
input.value = "iNeuron";
const btn = document.querySelector(".main__form-btn");
btn.disabled = false;
btn.onclick = location.reload();
```

## Assignment 8

### task 1

```javascript
const newDiv = document.querySelector(".new");
newDiv.style.overflowY = "scroll";
```

### task 2

```javascript
document.body.style.background = "white";
```

### task 3

```javascript
const navbarTogglerDemo01 = document.querySelector("#navbarTogglerDemo01");
const navbarToggler = document.querySelector(".navbar-toggler");
navbarToggler.onclick = () => {
    navbarTogglerDemo01.style.display = "block";
};
```

## Assignment 9

### task 1

```javascript
const title = document.querySelector("h1.title");
title.style.color = "red";
title.style.fontSize = "2.5em";
```

### task 2

```javascript
const button = document.querySelector("button.add-to-cart");
const style = document.createElement("style");
style.type = "text/css";
style.innerHTML = ".hoverRed:hover { background-color:red }";
document.getElementsByTagName("head")[0].appendChild(style);
button.classList.add("hoverRed");
```

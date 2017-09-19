# class-exercise

3
let hh = document.getElementsByClassName('item-page__main-title is-truncated');

undefined

hh

[h1.item-page__main-title.is-truncated]0: h1.item-page__main-title.is-truncatedlength: 1textContent: "Always Awakening"__proto__: HTMLCollection
hh.textContent = "Always Awakening";
"Always Awakening"

hh.textContent = 'Always Awakening';

"Always Awakening"


4
let coverpicture = document.querySelector('.product-image__image--single');

undefined

coverpicture

<img class=​"product-image__image--single" src=​"https:​/​/​dynamic.indigoimages.ca/​books/​3791354701.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=27&lang=en" data-a8n=​"product-image__image" alt=​"The Idea Of North:​ The Paintings Of Lawren Harris by Steve Martin">​

coverpicture.src

"https://dynamic.indigoimages.ca/books/3791354701.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=27&lang=en"

coverpicture.src = "http://www.gettyimages.ca/gi-

5
let allnav = ['one' , 'two' , 'three' , 'four' , 'five' , 'six' , 'seven' ,  'eight' , 'nine' , 'ten'];
undefined
let n = document.querySelectorAll('[class^=top-nav__list-link]');
undefined
let pagenav = document.querySelectorAll('[class^=top-nav__list-link]');
undefined
pagenav
(10) [a.top-nav__list-link, a.top-nav__list-link--active, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link]
pagenav = Array.from(document.querySelectorAll('[class^=top-nav__list-link]'));
(10) [a.top-nav__list-link, a.top-nav__list-link--active, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link]
pagenav.map( (navitem, idx) => navitem.textContent = n[idx]);
(10) [a.top-nav__list-link, a.top-nav__list-link--active, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link]

6
"logo"
let logo = document.querySelector('[data-a8n-indigo-logo]');

 logo = document.querySelector('[data-a8n=indigo-logo]');

<a href=​"https:​/​/​www.chapters.indigo.ca/​en-ca/​?link-usage=Header%3A%20https%3A%2F%2Fwww.chapters.indigo.ca%2Fen-ca%2F" class=​"indigo-logo" data-a8n=​"indigo-logo">​…​</a>​

let ownEl = document.createElement('img');


ownEl
<img>​
ownEl.src = 'https://i.pinimg.com/736x/65/a5/65/65a565ca06d684e63a5be65132f05c69--music-logo-logo-development.jpg';
"https://i.pinimg.com/736x/65/a5/65/65a565ca06d684e63a5be65132f05c69--music-logo-logo-development.jpg"
ownEl
let oldEl = document.querySelector('[data-a8n=indigo-logo] svg');

undefined
oldEl
<svg xmlns=​"http:​/​/​www.w3.org/​2000/​svg" width=​"130" height=​"66" viewBox=​"0 0 130 66">​…​</svg>​
logo.replaceChild(ownEl, oldEl);
<svg xmlns=​"http:​/​/​www.w3.org/​2000/​svg" width=​"130" height=​"66" viewBox=​"0 0 130 66">​…​</svg>​

10
let button =document.getElementById("add-to-cart-button");

bv-primary.js:74 scout-to-render: 3650ms
btn
<button type=?"button" id=?"add-to-cart-button" data-a8n=?"item-page__button-add-to-cart" class=?"common-button add-to-cart-button__primary ">?add to cart?</button>?
btn.addEventListener('click',function(){document.documentElement.innerHTML-" ";});

	

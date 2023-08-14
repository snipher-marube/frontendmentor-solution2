# Frontend Mentor - News homepage solution

This was a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](https://github.com/snipher-marube/frontendmentor-solution2/blob/main/static/assets/screennshot/Screenshot%20from%202023-08-14%2011-06-59.png)



### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-news-homepage-using-django-and-tailwind-css-sldGXCcrpF)
- Live Site URL: [Add live site URL here](https://frontendmentor-solution2.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Tailwind CSS
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/) - Tailwind CSS
- [Django](https://www.djangoproject.com/) - For structure and routing



### What I learned

I learnt how to use tailwind css to style my webpages. I also learnt how to use django to structure my webpages and route them. 

```html
<div class="flex flex-col items-center justify-center h-screen bg-gray-100">
  <h1 class="text-6xl font-bold text-gray-900">Hello Tailwind</h1>
  <button class="px-4 py-2 mt-4 text-white bg-indigo-500 rounded hover:bg-indigo-600">Get Started</button>
</div>
```
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
```js
module.exports = {
  purge: [],
  darkMode: false, // or 'media' or 'class'
  theme: {
    extend: {},
  },
  variants: {
    extend: {},
  },
  plugins: [],
}
```
```python
from django.urls import path
from . import views

urlpatterns = [
    path('', views.index, name='index'),
    path('about', views.about, name='about'),
    path('contact', views.contact, name='contact'),
    path('news', views.news, name='news'),
    path('news/<int:news_id>', views.news, name='news'),
]
```

### Continued development

I will continue to learn more about tailwind css and django. I will also learn how to use react js and node js.




## Author

-
- Frontend Mentor - [@snipher-marube](https://www.frontendmentor.io/profile/snipher-marube)
- Twitter - [@snipherdev](https://www.twitter.com/snipherdev)



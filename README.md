# ReactDev

Declerative vs imperative

![Capture d’écran 2024-03-24 à 3 10 28 PM](https://github.com/ahamedfo/ReactDev/assets/45969089/b73f7f58-c777-463d-86bd-38c07eeb53f5)

vanilla JS is very step by step

React akes the multiple lines we would have written explicitly and performs the actions implicitly. "You want to create an H1 in this root? no problem, i'll handle it's creation and classes under the hood."

JSX allows us this flexibility thorugh writing html in the JS

![Capture d’écran 2024-03-24 à 3 14 21 PM](https://github.com/ahamedfo/ReactDev/assets/45969089/5e5a60d1-709e-490c-b8e1-f8517630c396)

Before to affect the HTML in JS, we had to write much more to affect HTML in JS whereas JSX allows us to essentially just write the HTML.!

2 child elements cannot be rendered at 1 time using react. There must always be an overarching parent element. below for example, these could be wrapped in a Div

[Capture d’écran 2024-03-24 à 3 23 11 PM](https://github.com/ahamedfo/ReactDev/assets/45969089/9c6f6d93-d53c-4d9c-9161-906ceab59445)

CDN's - 

![Capture d’écran 2024-03-26 à 3 44 53 PM](https://github.com/ahamedfo/ReactDev/assets/45969089/36e70c8c-a683-47e3-ad51-9a7971911bfb)

React 18 - We first instatiate the root and then after that we render using said root.

![Capture d’écran 2024-03-26 à 4 44 39 PM](https://github.com/ahamedfo/ReactDev/assets/45969089/a28e4277-d7c6-4ca8-b9fe-46e3aa9f6911)

fragments can bypass the need for storing everything in a JSX render call in 1 element through using empty brackets - <>


<img width="901" alt="Capture d’écran 2024-03-27 à 3 03 58 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/1d00fdea-5b12-4e45-bfb1-6909ec171c93">

A function in react that returns react elements is what a component is and builds on the reusability of react

We use pascal case for components (meaning capitalize the first letter )

We also wrap it in angle brackets similar to an HTML element. Below is the final product

<img width="925" alt="Capture d’écran 2024-03-27 à 3 06 32 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/283bc33b-b51f-4d29-bb9f-405866808290">


-------------------


First attempt 

<img width="934" alt="Capture d’écran 2024-03-27 à 4 50 51 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/57383463-440a-405a-808a-1c37e5756c11">

-------

Creating an instance of a component - 

<Header /> creates an instance of the component within the DOM


<img width="921" alt="Capture d’écran 2024-03-27 à 5 05 34 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/7ca0fbe3-53f6-4a63-b157-e7a77f107607">

Parent components vs child components

<img width="938" alt="Capture d’écran 2024-03-27 à 5 25 05 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/551d4433-363f-4518-977c-fd16cdc943fd">

className is the equivalent to class in react. Under the hood it uses the JS API

<img width="912" alt="Capture d’écran 2024-03-27 à 5 33 07 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/c4a0dad4-6ee7-4341-b2df-1f801a0ef578">

<img width="664" alt="Capture d’écran 2024-03-27 à 5 50 16 PM" src="https://github.com/ahamedfo/ReactDev/assets/45969089/241abefe-7f8e-41f2-8650-60416cf0ae8e">





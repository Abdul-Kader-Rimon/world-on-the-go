 Countries API
A simple project demonstrating the usage of the Programming Hero Countries API endpoints. Provides information about all countries, specific country by code or name, or by language.
Table of Contents
APIs Used

Endpoints

https://openapi.programming-hero.com/api/all

https://openapi.programming-hero.com/api/alpha/116

https://openapi.programming-hero.com/api/lang/english

https://openapi.programming-hero.com/api/name/bangladesh



Usage

Here’s how you might use these endpoints in your app (JavaScript / fetch example):

// Fetch all countries

fetch("https://openapi.programming-hero.com/api/all")
  .then((res) => res.json())
  .then((data) => console.log(data));
  

// Fetch country by ISO code

fetch("https://openapi.programming-hero.com/api/alpha/116")
  .then((res) => res.json())
  .then((data) => console.log(data));
  


// Fetch countries by language

fetch("https://openapi.programming-hero.com/api/lang/english")
  .then((res) => res.json())
  .then((data) => console.log(data));
  

// Fetch country by name

fetch("https://openapi.programming-hero.com/api/name/bangladesh")
  .then((res) => res.json()) 
  .then((data) => console.log(data));
 

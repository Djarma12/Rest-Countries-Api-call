# Rest-Countries-API-call

![desktop-preview](https://user-images.githubusercontent.com/112414082/210043070-03de1969-2ef7-490d-b337-18c6a4942cd8.jpg)

Rest countries is an application where we can view and search data about all countries. Clicking on the country itself opens a field with detailed information about it.

You can view the project live here:
[Rest-Countries-API-call](https://dusan-rest-countries-api-call.netlify.app/)

---

### Table of Contents

- [Description](#description)
- [Getting Started](#getting-started)
- [References](#references)
- [License](#license)

---

## Description

Application users are able to:

- See all countries from the API on the homepage
- Search for a country using the `input` field, which dynamically displays countries starting with that name
- Filter countries by region
- Click on a country to see more detailed information on a separate page
- Click through to the border countries on the detail page
- Toggle the color scheme between light and dark mode

#### Technologies

- HTML
- CSS (Grid, Flexbox, Custom Properties)
- JS (API call, OOP)

[Back To The Top](#rest-countries-api-call)

---

## Getting Started

To start the project, it is necessary to download the files from the github repository and run them on the live server.

[Back To The Top](#rest-countries-api-call)

---

## References

- You can view my profile on the platform where I downloaded the template here: [Frontend Mentor Profile](https://www.frontendmentor.io/profile/Djarma12)
- You can see the specific work with this project here: [Frontend Mentor Project](https://www.frontendmentor.io/solutions/html-css-js-3Q8S28Uod_)

### Method References

- This input method takes a parameter that the user entered in the input. Through it, it searches the array with all the countries. If you find one, it will show the details of that country: <br>
  `foundCountry(countryInput){...};`

- The method displays all border countries, regardless of how many there are for the country for which the user has viewed details: <br>
  `borderCountries(){...};`

- Each time the user returns from the country details page to the page showing all countries, this method clears the DOM data for the country itself so that two or more countries are not displayed the next time: <br>
  `deleteCountryItself(){...};`

[Back To The Top](#rest-countries-api-call)

---

## License

MIT License

Copyright (c) [2022] [Dušan Mađar]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

[Back To The Top](#rest-countries-api-call)

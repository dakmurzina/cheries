<!-- PROJECT -->
<br />
<div align="center">
  <h3 align="center">Website Development</h3>
  <p align="center">
    Online Store CHERIES
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#explore-and-test">Explore and Test</a></li>
        <li><a href="#customization">Custamization</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The Online Store CHERIES is a learning project as part of Website Development course. CHERIES is a web-based e-commerce platform using Flask, a Python web framework. This platform offers a range of products, including clothing, shoes, and accessories, and allows users to browse, add items to their cart, and proceed to checkout.

The product information, encompassing details such as type, ID, name, price, image, and description, is structured in a list of dictionaries named products. Each product is categorized into clothing, shoes, or accessories.

Navigation within the application is facilitated through different routes. The home page (/) and an about page (/about) provide general information, while specific pages for clothing (/clothing), shoes (/shoes), and accessories (/accessories) allow users to explore products in these categories.

Cart management is a key feature, allowing users to add products to their cart, with the quantity of each item being tracked. The cart information is stored in the user's session, leveraging Flask's session functionality.

Product information is displayed dynamically on various pages (products.html and product.html) based on the product type. Users can view their cart (/cart), which displays the items, total price, and provides a link to the checkout page (/checkout).

The application features dynamic product detail pages (/clothing/<id>, /shoes/<id>, /accessories/<id>), where users can add items to their cart. The backend calculates the total price of items in the cart.

A checkout page (/checkout) is provided, though the specific details of the checkout process are not implemented in this code snippet.

<p align="right">(<a href="#about-the-project">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [```Python```](https://www.python.org/)
* [```Flask```](https://flask.palletsprojects.com/en/3.0.x/)
* ```HTML```
* ```CSS```
* ```Bootstrap```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->

## Getting Started

### Installation

Clone the repository: git clone https://github.com/dakmurzina/cheries.git
Navigate to the project directory: cd cheries
Run the Application

Execute the following command: ```python app.py```
Open a web browser and go to http://localhost:5000/ to access the platform.

### Explore and Test

Explore different sections of the platform, including clothing, shoes, and accessories.
Add products to the cart and review the cart page.
Test the dynamic product detail pages and the checkout process.

### Customization

Customize the product catalog by modifying the products list in the app.py file.

<p align="right">(<a href="#about-the-project">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Dinara Akmurzina - [@dinara-almurzina](https://www.linkedin.com/in/dinara-akmurzina/) - dakmurzinab@gmail.com

Project Link: [https://github.com/dakmurzina/cheries](https://github.com/dakmurzina/cheries)

<p align="right">(<a href="#about-the-project">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew





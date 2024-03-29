<a name="ecommerce"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/luk3mn/ecommerce">
    <img src="assets/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">E-Commerce API</h3>

  <p align="center">
    Back-End application built with Python and Flask to use REST API in e-commerce application.
    <br />
    <a href="https://github.com/luk3mn/ecommerce/README.md"><strong>Explore the docs »</strong></a>
    <br />
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
![Home](assets/ecommerce_api.png)


<p align="justify">
  
</p> 

### Utils Module

<p align="right">(<a href="#ecommerce">back to top</a>)</p>



### Built With

Write here

* [![Python][Python]][Python-url]
* [![Flask][Flask]][Flask-url]
<!-- * [![PostgreSQL][PostgreSQL]][PostgreSQL-url] -->

<p align="right">(<a href="#ecommerce">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here are some important topics about this project and how to replay it.

### Prerequisites

* virtualenv
  ```sh
  python3 -m venv .venv
  ```

### Installation

_Before starting this application in your local environment, it'll be necessary to proceed with some tasks to reproduce this project._

1. Get API Access [https://developer.spotify.com](https://developer.spotify.com/documentation/web-api)
2. Clone the repo
   ```sh
   git clone https://github.com/luk3mn/ecommerce.git
   ```
3. Install packages
   ```sh
   pip freeze -r requirements.txt
   ```

<p align="right">(<a href="#ecommerce">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
```sh
flask shell
```

- Drop All Created Tables
```sh
db.drop_all()
```

- Create new tables
```sh
db.create_all()
```

- To create a new user
```sh
user = User(username="admin", password="admin")
```

  - To add new use on database
  ```sh
  db.session.add(user)
  ```

- To save all changes
```sh
db.session.commit()
```

<!-- ROADMAP -->
## Roadmap

- [x] POST /login
- [x] POST /logout
- [x] POST /api/products/add
- [x] DELETE /api/products/add/{product_id}
- [x] GET /api/products/{product_id}
- [x] UPDATE /api/products/update/{product_id}
- [x] GET /api/products
- [x] POST /api/cart/add/{product_id}
- [x] DELETE /api/cart/REMOVE/{item_id}
- [x] GET /api/cart
- [x] POST /api/cart/checkout
- [] GET GET /api/products/search


<p align="right">(<a href="#ecommerce">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#ecommerce">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Lucas Renan - lucasnunes2030@gmail.com

Project Link: [https://github.com/luk3mn/ecommerce](https://github.com/luk3mn/ecommerce)

<p align="right">(<a href="#ecommerce">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I think it would be interesting to sit here some references and other resources that were really useful and helped me to come up with this project.

<p align="right">(<a href="#ecommerce">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/luk3mn/ecommerce.svg?style=for-the-badge
[contributors-url]: https://github.com/luk3mn/ecommerce/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/luk3mn/ecommerce.svg?style=for-the-badge
[issues-url]: https://github.com/luk3mn/ecommerce/issues
[forks-shield]: https://img.shields.io/github/forks/luk3mn/ecommerce.svg?style=for-the-badge
[forks-url]: https://github.com/luk3mn/ecommerce/network/members
[stars-shield]: https://img.shields.io/github/stars/luk3mn/ecommerce.svg?style=for-the-badge
[stars-url]: https://github.com/luk3mn/ecommerce/stargazers
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/luk3mn/ecommerce/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/lucasmaues/
[general-code-screenshot]: assets/general-project.png

<!-- Stack Shields -->
[Python]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffffff
[Python-url]: https://www.python.org/
[Flask]: https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=ffffff
[Flask-url]: https://flask.palletsprojects.com/en/3.0.x/
<!-- [PostgreSQL]: https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=ffffff
[PostgreSQL-url]: https://www.postgresql.org/ -->
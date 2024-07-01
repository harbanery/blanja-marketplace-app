<a name="readme-top"></a>

<div align="center">
  <a href="https://github.com/harbanery/blanja-marketplace-app">
    <img src="./public/brandicon.png" alt="Logo Blanja" width="250">
  </a>

  <h1 align="center">Blanja</h1>

  <p align="center">
    Marketplace Implementation
    <br />
    <br />
    <a href="https://blanja-website-project.netlify.app/" target="_blank">View Demo</a>
    ·
    <a href="https://github.com/harbanery/be-blanja-marketplace-app" target="_blank">View Back-End Repo</a>
  </p>
</div>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Setup Environment Variables](#setup-environment-variables)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
  - [Features](#features)
  - [Screenshots](#screenshots)
- [Contributing](#contributing)
  - [Meet the Contributors](#meet-the-contributors)
  - [How to Contribute](#how-to-contribute)
- [Contacts](#contacts)
- [Acknowledgements](#acknowledgements)

## About The Project

Blanja is a comprehensive e-commerce platform designed to connect customers with a diverse array of products from multiple sellers. Our website offers a seamless shopping experience for customers and robust tools for sellers to manage their storefronts.

### Built With

[![Vite][Vite]][Vite-url]
[![React.js][React.js]][React-url]
[![TailwindCSS][Tailwind]][Tailwind-url]

<!-- - [Vite](https://vitejs.dev/) -->
<!-- - [React.js](https://react.dev/) -->
<!-- - [Tailwind CSS](https://tailwindcss.com/) -->

## Getting Started

### Prerequisites

- npm

  ```sh
    npm install npm@latest -g
  ```

### Installation

Ensure you have the following installed on your local machine:

1. Clone this repository

   ```sh
   git clone https://github.com/harbanery/blanja-marketplace-app.git
   ```

   <!-- ```sh
   git clone --single-branch --branch feature/front-end https://github.com/echestratus/BlanjaWebsiteProject.git
   ``` -->

2. Go to folder directory

   ```bash
   cd blanja-marketplace-app
   ```

3. Install NPM packages

   ```sh
   npm install
   ```

### Setup Environment Variables

1. Create a `.env` or `.env.local` file in your local root directory.

2. Add the following variables to the `.env` or `.env.local` file:

   ```sh
     VITE_BE_URL=YOUR_API_URL
   ```

### Running the Application

1. Start the development server:

   ```sh
    npm run dev
   ```

2. Open your browser and locally navigate to:

   ```sh
   http://localhost:3000
   ```

Run this command for debugging and finding errors

```sh
npm run lint
```

## Usage

### Features

1. **User Authentication**

   - **Role-Based Login and Registration**: Users can register or log in as either a customer or a seller, with functionalities tailored to each role.

2. **Product Discovery**

   - **View Products**: Browse products from various registered sellers.
   - **Search and Filter**: Efficiently search and filter products to find exactly what you're looking for.

3. **Product Details**

   - **Detailed Product View**: Access comprehensive details for each product to make informed purchasing decisions.

4. **Shopping Cart and Checkout**

   - **Add to Cart**: Easily add products to your shopping cart.
   - **Checkout Process**: Proceed to checkout to review and purchase your selected products.

5. **Payment and Shipping**

   - **Secure Payment**: Complete your purchase with secure payment options.
   - **Address Management**: Add, edit, and set a primary shipping address for your orders.

6. **User Profile Management**

   - **Profile Overview and Editing**: View and update your user profile information.
   - **Order History**: View the status and details of past orders.

7. **Seller-Specific Features**

   - **Store Profile Management**: Sellers can view and edit their store profiles.
   - **Product Management for Sellers**:
     - **View Seller's Products**: Access a list of products associated with the seller's account.
     - **Add New Products**: Add new items to the store for sale.
     - **Edit Existing Products**: Update or edit the details of products in the seller's inventory.

### Screenshots

<p align="center" display=flex>
  <table>
  <tr>
    <td>Login</td>
    <td>Register Customer</td>
  </tr>
  <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/LoginPage.png" /></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/RegisterCustomerPage.png"/></td>
  </tr>
  <tr>
    <td>Register Seller</td>
    <td>Home</td>
  </tr>
    <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/RegisterSellerPage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/HomePage.png"/></td>
  </tr>
    <tr>
    <td>Detail Product</td>
    <td>Cart</td>
  </tr>
    <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/DetailProductPage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/CartPage.png"/></td>
  </tr>
  <tr>
    <td>Checkout</td>
    <td>My Profile Customer</td>
  </tr>
  <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/CheckoutPage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/MyProfileCustomerPage.png"/></td>
  </tr>
  <tr>
    <td>Shipping Address</td>
    <td>My Order</td>
  </tr>
  <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/ChooseAddressPage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/MyOrderPage.png"/></td>
  </tr>
  <tr>
    <td>Store Profile</td>
    <td>My Product</td>
  </tr>
  <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/StoreProfilePage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/MyProductPage.png"/></td>
  </tr> 
  <tr>
    <td>Selling Product</td>
    <td>Update Product</td>
  </tr>
  <tr>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/SellinProductPage.png"/></td>
    <td><img src="https://github.com/echestratus/BlanjaWebsiteProject/blob/feature/front-end/public/UpdateProductPage.png"/></td>
  </tr> 
  </table>
</p>

## Contributing

### Meet The Contributors

<table align="center">
  <tr>
    <th colspan="4">Codecraft</th>
  </tr>
  <tr align="center">
    <th>Project Manager / Front-End Developer</th>
    <th>Front-End Developer</th>
    <th>Fullstack Developer</th>
    <th>Back-End Developer</th>
  </tr>
  <tr align="center">
    <td><img width="200" src="https://avatars.githubusercontent.com/u/80629118?v=4"/></td>
    <td><img width="200" src="https://avatars.githubusercontent.com/u/74017000?v=4"/></td>
    <td><img width="200" src="https://avatars.githubusercontent.com/u/137192782?v=4"/></td>
    <td><img width="200" src="https://avatars.githubusercontent.com/u/89146375?v=4"/></td>
  </tr>
  <tr align="center">
    <td><a href="https://github.com/echestratus" target="_blank"><b>Farhan Nur Hakim</b></a></td>
    <td><a href="https://github.com/wafash08" target="_blank"><b>M. Wafa Saeful Haq</b></a></td>
    <td><a href="https://github.com/nizuma666" target="_blank"><b>Syaifulloh Ismail</b></a></td>
    <td><a href="https://github.com/harbanery" target="_blank"><b>Raihan Yusuf</b></a></td>
  </tr>
</table>

### How to Contribute

Contributing project to github is pretty straight forward.

1. **Fork the Repository**: Click the "Fork" button at the top-right corner of this page to create your own copy of the repository.
2. **Installation**: Do the installation process right [here](#installation).
3. **Create a new branch**: Create a new branch to work on your changes.
   ```sh
   git branch -M feature/your-feature-name
   ```
4. **Make changes**: Implement your changes or new features in your branch.
5. **Commit your changes**: After making your changes, commit them with a descriptive message.
   ```sh
   git add .
   git commit -m "Add description of your changes"
   ```
6. **Push to GitHub**: Push your changes to your forked repository.
   ```sh
   git push origin feature/your-feature-name
   ```
7. **Create Pull Request**: Go to the original repository and open a pull request to merge your changes.
   - Navigate to your fork on GitHub.
   - Click on the "New Pull Request" button.
   - Select the base repository and branch you want to merge into.
   - Provide a detailed description of your changes and click "Create Pull Request".

## Contacts

If you have any questions or inquiries regarding this front-end project, feel free to contact at:

[![Farhan Nur Hakim's Email](https://img.shields.io/badge/Farhan%20Nur%20Hakim-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:farhanz.nh.13@gmail.com)
[![Farhan Nur Hakim's LinkedIn](https://img.shields.io/badge/Farhan%20Nur%20Hakim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farhan-nur-hakim/)

[![M. Wafa Saeful Haq's Email](https://img.shields.io/badge/Wafa%20Saeful%20Haq-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saefulhaqwafa@gmail.com)
[![M. Wafa Saeful Haq's LinkedIn](https://img.shields.io/badge/Wafa%20Saeful%20Haq-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mwafasaefulhaq/)

[![Syaifulloh Ismail's Email](https://img.shields.io/badge/Syaifulloh%20Ismail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:syaifullohismail123@gmail.com)
[![Syaifulloh Ismail's LinkedIn](https://img.shields.io/badge/Syaifulloh%20Ismail-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syaifulloh-ismail/)

Or if you just want to get in touch with me, feel free to contact me at:

[![Raihan Yusuf's Email](https://img.shields.io/badge/Raihan%20Yusuf-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ryusuf05@gmail.com)
[![Raihan Yusuf's LinkedIn](https://img.shields.io/badge/Raihan%20Yusuf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raihan-yusuf/)

## Acknowledgements

Feel free to check it out:

- [Img Shields](https://shields.io)
- [GitHub Pages](https://pages.github.com/)

<!-- MARKDOWN LINKS & IMAGES -->

[Node.js]: https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[Node-url]: https://nodejs.org/en
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=white
[React-url]: https://reactjs.org/
[Tailwind]: https://img.shields.io/badge/tailwindcss-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[Tailwind-url]: https://tailwindcss.com/
[Vite]: https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white
[Vite-url]: https://vitejs.dev/

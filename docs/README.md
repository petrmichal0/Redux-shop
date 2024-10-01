## Project Title and Description
Redux-shop is a web application designed to provide a shopping experience with cart management. Users can browse products, add them to their cart, and view the cart's contents.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/013e2a9a-fec9-4912-ac7a-40f4dc8e5ee1" width="700" alt="Redux-shop App Demo">

## Table of Content
- [Project Title and Description](#project-title-and-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Demo (link)](#demo-link)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Third-Party Libraries](#third-party-libraries)
- [License](#license)

## Features
- Browse products
- Add products to cart
- View cart contents
- User-friendly interface

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm (v6 or higher)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/petrmichal0/Redux-shop.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Redux-shop
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the application, run the following command:
```bash
npm run dev
```

After starting, go to [http://localhost:3000](http://localhost:3000) in your web browser.

## Screenshots

<table>
  <tr>
    <th>Homepage</th>
    <th>Cart Management</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
  <a href="https://github.com/user-attachments/assets/aed0fe02-e943-48c4-a911-d609c80f6be0" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/user-attachments/assets/aed0fe02-e943-48c4-a911-d609c80f6be0" width="300" height="300" alt="Homepage">
  </a>
</td>
<td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
  <a href="https://github.com/user-attachments/assets/7c71d73b-09a1-4238-b013-7f08a6115d49" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/user-attachments/assets/7c71d73b-09a1-4238-b013-7f08a6115d49" width="300" height="300" alt="Cart Management">
  </a>
</td>
  </tr>
</table>

## Demo (link)

Check out the live demo of the application [here](https://redux-shop-react-type.netlify.app/).

## Project Structure

```css
Redux-shop/
├── public/
│   ├── logo.png
├── src/
│   ├── assets/
│   │   ├── denim-pioneer.jpg
│   │   ├── dream-gown.jpg
│   │   ├── merlot-suit.jpg
│   │   ├── mocha-overcoat.jpg
│   │   ├── moonlight-dress.jpg
│   │   ├── rain-jacket.jpg
│   ├── components/
│   │   ├── Cart.tsx
│   │   ├── CartItems.tsx
│   │   ├── Header.tsx
│   │   ├── Product.tsx
│   │   ├── Shop.tsx
│   ├── store/
│   │   ├── cart-slice.ts
│   │   ├── hooks.ts
│   │   ├── store.ts
│   ├── App.tsx
│   ├── dummy-products.ts
│   ├── index.css
│   ├── main.tsx
│   ├── vite-env.d.ts
├── .eslintrc.cjs
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Technologies Used

[![React Badge](https://img.shields.io/badge/-React-61DBFB?style=for-the-badge&labelColor=black&logo=react&logoColor=61DBFB)](#)
[![TypeScript Badge](https://img.shields.io/badge/-TypeScript-007ACC?style=for-the-badge&labelColor=black&logo=typescript&logoColor=007ACC)](#)
[![Vite Badge](https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&labelColor=black&logo=vite&logoColor=646CFF)](#)
[![Redux Badge](https://img.shields.io/badge/-Redux-764ABC?style=for-the-badge&labelColor=black&logo=redux&logoColor=764ABC)](#)

## Third-Party Libraries

* React Router
* @reduxjs/toolkit
* react-redux

## License

This project is licensed under the MIT License - see the LICENSE file for details.

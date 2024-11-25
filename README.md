# E Commerce Dummy Application

A React-based application that displays a list of products fetched from an API, providing filtering, sorting, infinite scrolling, and dynamic product details.

## Features

### 1. Product List View

- Fetches and displays products from a given API endpoint.
- Shows essential product details, including:
  - **Title**
  - **Description**
  - **Category**
  - **Price**
  - **Rating**
- Implementes infinite scrolling functionality to load additional products as the user scrolls.

### 2. Filtering and Sorting

- **Filters:**
  - Filter products by:
    - **Category**
    - **Price Range**
    - **Rating**
- **Sorting Options:**
  - Sort products by:
    - **Price (Low-to-High)**
    - **Price (High-to-Low)**
- All filtering and sorting actions are performed seamlessly without reloading the page.

### 3. Product Details Modal

- Click on a product to view additional details in a modal, such as:
  - **Description**
  - **Availability**
  - **Detailed Image**
  - **Title**
  - **Category**
  - **Brand**
  - **Price**
  - **Rating**
  - **Availability (to check out of stock)**
  - **Stock Left(if available)**
- Product details are fetched dynamically to optimize performance.

---

## Getting Started

### Prerequisites

- **Node.js** (v16+ recommended)
- **npm** or **yarn**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/namanbhardwajofficial/ecommerce-dummy1
   cd ecommerce-dummy1
   ```
2. Install dependencies:

```bash
npm install
```

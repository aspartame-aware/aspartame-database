# Open-Source Aspartame Database

The **Open-Source Aspartame Database** is a community-driven project that tracks products containing aspartame, allowing users to search, filter, and contribute new product information. This tool aims to empower consumers with the knowledge they need to make informed decisions about aspartame consumption.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Contributing](#contributing)
- [Getting Started](#getting-started)
- [Technical Details](#technical-details)
- [Resources & References](#resources--references)
- [License](#license)

## Project Description

This database serves as a central hub for information on products containing aspartame. Users can:
- Search and filter products by categories (e.g., food, beverages, medicine, etc.).
- View detailed product information, including aspartame content and user ratings.
- Contribute new products or update existing entries via pull requests.
- Access the database programmatically using an API for integration into other projects.

Our goal is to make this resource as collaborative and transparent as possible to ensure its accuracy and usefulness.

## Features

- **Searchable Database**: Quickly find products containing aspartame by name, category, or ingredient.
- **User Contributions**: Submit new products, suggest edits, or flag inaccuracies.
- **Product Ratings & Comments**: Share your thoughts and experiences with listed products.
- **API Access**: Developers can integrate the database into their own apps or tools.
- **Open-Source & Community-Driven**: Built by contributors from around the world.

## Contributing

We welcome contributions from the community! Here’s how you can get involved:

### How to Contribute:
1. **Fork the Repository**: Create a copy of this repository in your GitHub account.
2. **Clone Your Fork**: Clone your copy of the repository to your local machine.
3. **Create a New Branch**: Work on a separate branch for each feature or fix.
4. **Add or Edit Products**: Update the `products.json` file with new or corrected data.
5. **Commit Your Changes**: Write clear and descriptive commit messages.
6. **Submit a Pull Request**: Once you're ready, submit your changes for review.

### Example Product Entry
All product data is stored in a JSON format. Here’s an example of how to add a new product:
```json
{
  "id": "12345",
  "name": "Diet Cola",
  "category": "Beverages",
  "brand": "Generic Brand",
  "ingredients": ["Carbonated Water", "Aspartame", "Caffeine"],
  "aspartame_content_mg": 180,
  "rating": 4.5,
  "reviews": [
    {
      "user": "johndoe",
      "comment": "Tastes good, but I prefer products without aspartame.",
      "date": "2024-11-18"
    }
  ]
}

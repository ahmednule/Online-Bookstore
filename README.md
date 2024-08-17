# Online Bookstore

An Online Bookstore project built with Django that allows users to browse, purchase books, and manage orders. The project includes functionalities such as a shopping cart, checkout process, order management, and PDF receipt generation.

## Project Structure

```bash
Online-Bookstore/
├── bookstore/       # Main Django project directory
├── cart/            # Shopping cart application
├── order/           # Order management application
├── search/          # Search functionality
├── store/           # Storefront and product listing
├── db.sqlite3       # SQLite database file
├── files/           # Static and media files
├── manage.py        # Django management script
├── README.md        # Project README file
└── requirements.txt # List of dependencies
```

## Project Owner
- **Owner:** Whitney Kageham
- **Institution:** Nairobi Technical Training Institute

## Requirements

- Python 3.12
- Django 5.1
- [Other dependencies listed in `requirements.txt`]

## Installation and Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ahmednule/Online-Bookstore.git
   cd Online-Bookstore
   ```

2. **Set up a virtual environment**
   ```bash
   python -m venv django_env
   source django_env/Scripts/activate  # For Windows
   # or
   source django_env/bin/activate      # For MacOS/Linux
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

6. **Access the application**
   Open your browser and navigate to `http://127.0.0.1:8000/` to view the site.

## Features

- **Bookstore Frontend:** Browse and search for books, view detailed product pages.
- **Shopping Cart:** Add/remove books, view cart summary, and proceed to checkout.
- **Checkout Process:** Enter shipping details and select payment methods.
- **Order Management:** View and manage orders, with order details presented after purchase.
- **PDF Generation:** Download a PDF receipt for completed orders.

## How to Use

1. **Browsing Books:**
   - Visit the home page and browse through available books.

2. **Add to Cart:**
   - Click on the book, select the quantity, and add it to your cart.

3. **Checkout:**
   - Click on the cart icon to review your order. Proceed to checkout by entering your shipping and payment details.

4. **Order Confirmation:**
   - After a successful order, you will be presented with the order summary.
   - You can download the PDF receipt by clicking the download icon next to your order.

5. **PDF Generation:**
   - Click on the download button on the order confirmation page to generate the PDF receipt. This will take you to a new page.

## Testing

To run tests, use the following command:
```bash
python manage.py test
```

## Contributing

1. **Fork the repository**
2. **Create a new feature branch** (`git checkout -b feature-branch`)
3. **Commit your changes** (`git commit -am 'Add new feature'`)
4. **Push to the branch** (`git push origin feature-branch`)
5. **Open a pull request**

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or contributions, contact:
- Whitney Kageham - Nairobi Technical Training Institute
```


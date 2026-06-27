# Mini Catalog

A simple product catalog app I built with Flutter. Made it to practice what I learned during the training.

## What it does

It fetches products from an API, shows them in a grid layout, lets you search, view details, and add items to a cart (simulated).

## Screens

- **Home** – Lists products in a grid, has a search bar
- **Product Detail** – Shows description, specs, and price when you tap a product
- **Cart** – Shows added items, swipe to remove

## Folder Structure

```
lib/
├── main.dart
├── models/
│   └── product.dart
├── screens/
│   ├── home_screen.dart
│   ├── product_detail_screen.dart
│   └── cart_screen.dart
└── widgets/
    ├── product_card.dart
    ├── banner_widget.dart
    └── search_bar_widget.dart
```

## Tech Stack

- Flutter SDK (>=3.0.0)
- Dart
- `http` package (for API calls)
- `google_fonts` package (Poppins font)
- Material Design 3

## How to Run

```bash
flutter pub get
flutter run
```

## API

Product data comes from `https://wantapi.com/products.php`. Banner image is from `https://wantapi.com/assets/banner.png`. These are for educational purposes only, not a real store.

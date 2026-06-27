# Mini Katalog

Flutter ile geliştirdiğim basit bir ürün katalog uygulaması. Eğitim sürecinde öğrendiklerimi pekiştirmek için yaptım.

## Ne işe yarıyor?

Ürünleri listeleyen, arama yapabilen, detay sayfasına gidebilen ve sepete ekleme simülasyonu yapan bir uygulama. API'den veri çekiyor, kartlar halinde gösteriyor.

## Ekranlar

- **Ana Sayfa** – Ürünleri grid halinde listeler, arama yapabilirsin
- **Ürün Detay** – Ürüne tıklayınca açılan sayfa, açıklama ve özellikler var
- **Sepet** – Sepete eklenen ürünleri gösterir, kaydırarak silebilirsin

## Klasör Yapısı

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

## Kullandığım Şeyler

- Flutter SDK (>=3.0.0)
- Dart
- `http` paketi (API çağrısı için)
- Material Design 3

## Nasıl Çalıştırılır

```bash
flutter pub get
flutter run
```

## API

Ürün verileri `https://wantapi.com/products.php` adresinden geliyor. Banner görseli de `https://wantapi.com/assets/banner.png` adresinden çekiliyor. Bunlar tamamen eğitim amaçlı, gerçek bir mağaza değil.

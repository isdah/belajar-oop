Hallo, Nama Saya Isdahlia
saya sedang Mengikuti Kegatan MSIB 6 Data Engineer di Dibimbing
Untuk Project ini saya belajar membuat repository baru dengan menggunakan akun github pribadi saya

Untuk dokumentasi homework ini, saya dapat membuat file `Readme.md` di dalam proyek saya dan menambahkan deskripsi singkat tentang apa yang dilakukan oleh setiap kelas dan metodenya. Berikut adalah  `Readme.md` saya:

```markdown
# Marketing Data ETL

This project includes classes for Extract, Transform, and Load (ETL) operations on marketing data.

## MarketingDataETL Class

This class provides methods to extract data from a CSV file, perform basic data cleaning and transformation, and store the transformed data.

### Methods:
- `extract()`: Reads data from a CSV file (e.g., `marketing_data.csv`).
- `transform()`: Performs simple cleaning and transformation on the data (e.g., converting date format or handling missing values).
- `store()`: Saves the transformed data into a DataFrame structure.

### Usage:
```python
etl = MarketingDataETL('marketing_data.csv')
etl.extract()
etl.transform()
etl.store()
```

## TargetedMarketingETL Class

This class inherits from `MarketingDataETL` and adds methods for customer segmentation based on specific criteria, demonstrating polymorphism by overriding the `transform()` method.

### Additional Methods:
- `segment_customers()`: Groups customers based on certain criteria (e.g., total expenditure or product categories purchased).

### Usage:
```python
target_etl = TargetedMarketingETL('marketing_data.csv')
target_etl.extract()
target_etl.transform()
result = target_etl.transform()
print("Resulting segmented dataframe:")
print(result)
```

Feel free to modify and extend these classes according to your specific requirements.
```

Dengan demikian, Anda telah memberikan dokumentasi yang jelas tentang struktur dan fungsionalitas dari kelas-kelas dan metode-metode yang ada dalam proyek Anda.

# Python Practice Project

Quyida ikkita demo dataset berilgan: **Users** va **Products**. Ushbu ma’lumotlardan foydalanib turli amaliy topshiriqlarni bajarish mumkin.

---

## 📌 Users Data

`users` ro‘yxatida 20 ta foydalanuvchi haqidagi ma’lumot mavjud. Har bir foydalanuvchida quyidagi **kalitlar (keys)** bor:

* **name** → foydalanuvchi ismi
* **email** → elektron pochta manzili
* **age** → yoshi
* **phone** → telefon raqami
* **country** → yashash davlati

**Misol:**

```python
users = [
    {"name": "Ali", "email": "ali0@gmail.com", "age": 25, "phone": "+998901234567", "country": "Uzbekistan"},
    {"name": "Vali", "email": "vali1@yahoo.com", "age": 32, "phone": "+998911112233", "country": "USA"},
    {"name": "Gani", "email": "gani2@hotmail.com", "age": 41, "phone": "+998933334455", "country": "UK"},
    {"name": "Sami", "email": "sami3@mail.ru", "age": 29, "phone": "+998944445566", "country": "Germany"},
    {"name": "Madina", "email": "madina4@outlook.com", "age": 21, "phone": "+998955556677", "country": "France"},
    {"name": "Aziza", "email": "aziza5@gmail.com", "age": 38, "phone": "+998966667788", "country": "Uzbekistan"},
    {"name": "Lola", "email": "lola6@yahoo.com", "age": 27, "phone": "+998977778899", "country": "USA"},
    {"name": "Zarina", "email": "zarina7@hotmail.com", "age": 30, "phone": "+998988889900", "country": "UK"},
    {"name": "Kamol", "email": "kamol8@mail.ru", "age": 22, "phone": "+998901112223", "country": "Germany"},
    {"name": "Umid", "email": "umid9@outlook.com", "age": 35, "phone": "+998912223344", "country": "France"},
    {"name": "Bekzod", "email": "bekzod10@gmail.com", "age": 28, "phone": "+998923334455", "country": "Uzbekistan"},
    {"name": "Dilshod", "email": "dilshod11@yahoo.com", "age": 40, "phone": "+998934445566", "country": "USA"},
    {"name": "Nodir", "email": "nodir12@hotmail.com", "age": 24, "phone": "+998945556677", "country": "UK"},
    {"name": "Shahnoza", "email": "shahnoza13@mail.ru", "age": 26, "phone": "+998956667788", "country": "Germany"},
    {"name": "Nigora", "email": "nigora14@outlook.com", "age": 31, "phone": "+998967778899", "country": "France"},
    {"name": "Sevinch", "email": "sevinch15@gmail.com", "age": 23, "phone": "+998978889900", "country": "Uzbekistan"},
    {"name": "Laziz", "email": "laziz16@yahoo.com", "age": 36, "phone": "+998989990011", "country": "USA"},
    {"name": "Anvar", "email": "anvar17@hotmail.com", "age": 33, "phone": "+998901223344", "country": "UK"},
    {"name": "Javlon", "email": "javlon18@mail.ru", "age": 20, "phone": "+998912334455", "country": "Germany"},
    {"name": "Diyor", "email": "diyor19@outlook.com", "age": 39, "phone": "+998923445566", "country": "France"},
]
```

### 🎯 Tasks

Ushbu dataset yordamida quyidagilarni o‘rganasiz:

* **task 01:** `users` ro‘yxatidan barcha foydalanuvchilarning **name** qiymatlarini ajratib olib, alohida list ko‘rinishida chiqaring.
* **task 02:** `users` ro‘yxatidan barcha foydalanuvchilarning **email** manzillarini list ko‘rinishida chiqaring.
* **task 03:** Har bir email manzilidan **@ belgidan keyin keladigan domen qismini** ajratib oling va ularni list ko‘rinishida chiqaring.
* **task 04:** Foydalanuvchilarning telefon raqamidan foydalanib qidiruv qiling. Funksiyaga berilgan **telefon raqamiga tegishli user ma’lumotini** qaytaring.
* **task 05:** Foydalanuvchilarning email manzilidan foydalanib qidiruv qiling. Funksiyaga berilgan **emailga tegishli user ma’lumotini** qaytaring.
* **task 06:** `users` ro‘yxatidan barcha **country** qiymatlarini ajratib oling va faqatgina **takrorlanmagan (unique)** davlatlar ro‘yxatini chiqaring.
* **task 07:** Foydalanuvchilarni ularning **country** qiymati bo‘yicha guruhlab chiqing. Har bir davlat nomiga tegishli foydalanuvchilar ro‘yxatini yarating.
* **task 08:** Foydalanuvchilarni ularning **age** qiymati bo‘yicha guruhlab chiqing. Har bir yosh qiymati ostida shu yoshdagi userlar chiqsin.
* **task 09:** `users` ro‘yxatidan **eng yosh (min age)** va **eng katta yosh (max age)** foydalanuvchini topib chiqaring. Ikkala user ma’lumotini qaytaring.
* **task 10:** Funksiyaga **min_age** va **max_age** qiymatlari beriladi. Shu oralig‘idagi barcha foydalanuvchilarni ro‘yxat qilib qaytaring.

---

---

## 📌 Products Data

`products` ro‘yxatida 20 ta mahsulot haqidagi ma’lumot mavjud. Har bir mahsulotda quyidagi **kalitlar (keys)** mavjud:

* **name** → mahsulot nomi
* **price** → narxi (USD)
* **category** → mahsulot kategoriyasi

**Misol:**

```python
products = [
    {"name": "iPhone 15", "price": 1200, "category": "Electronics"},
    {"name": "Samsung TV", "price": 800, "category": "Electronics"},
    {"name": "Nike Shoes", "price": 150, "category": "Fashion"},
    {"name": "Adidas Shoes", "price": 120, "category": "Fashion"},
    {"name": "Couch", "price": 500, "category": "Furniture"},
    {"name": "Chair", "price": 100, "category": "Furniture"},
    {"name": "MacBook Pro", "price": 2000, "category": "Electronics"},
    {"name": "T-shirt", "price": 25, "category": "Fashion"},
    {"name": "Desk", "price": 220, "category": "Furniture"},
    {"name": "Monitor", "price": 300, "category": "Electronics"},
    {"name": "Keyboard", "price": 50, "category": "Electronics"},
    {"name": "Mouse", "price": 30, "category": "Electronics"},
    {"name": "Jeans", "price": 80, "category": "Fashion"},
    {"name": "Jacket", "price": 200, "category": "Fashion"},
    {"name": "Bed", "price": 700, "category": "Furniture"},
    {"name": "Lamp", "price": 60, "category": "Furniture"},
    {"name": "iPad", "price": 900, "category": "Electronics"},
    {"name": "Watch", "price": 250, "category": "Fashion"},
    {"name": "Bookshelf", "price": 400, "category": "Furniture"},
    {"name": "Headphones", "price": 180, "category": "Electronics"},
]
```

---

## 🎯 Tasks

Ushbu dataset yordamida quyidagilarni o‘rganasiz:

Zo‘r! Endi `products` dataset uchun ham xuddi `users`dagidek **aniq va tushunarli 10 ta task** yozib beraman. Formatni o‘zgartirmayman:

---

## 🎯 Tasks

Ushbu dataset yordamida quyidagilarni o‘rganasiz:

* **task 11:** `products` ro‘yxatidan barcha mahsulotlarning **name** qiymatlarini ajratib olib, alohida list ko‘rinishida chiqaring.
* **task 12:** `products` ro‘yxatidan barcha mahsulotlarning **price** qiymatlarini list qilib chiqaring.
* **task 13:** `products` ro‘yxatidan barcha mahsulotlarning **category** qiymatlarini ajratib oling va unique ro‘yxat ko‘rinishida chiqaring.
* **task 14:** `products` ichidan **eng qimmat mahsulotni** toping va uning barcha ma’lumotlarini qaytaring.
* **task 15:** `products` ichidan **eng arzon mahsulotni** toping va uning barcha ma’lumotlarini qaytaring.
* **task 16:** Foydalanuvchi tomonidan berilgan **narxdan yuqori mahsulotlarni** ro‘yxat qilib qaytaring.
* **task 17:** Foydalanuvchi tomonidan berilgan **narxdan past mahsulotlarni** ro‘yxat qilib qaytaring.
* **task 18:** `products` ni **category** qiymatlari bo‘yicha guruhlab chiqaring. Har bir kategoriya ichida shu guruhga tegishli mahsulotlar bo‘lsin.
* **task 19:** Funksiyaga **min_price** va **max_price** qiymatlari beriladi. Shu oraliqda bo‘lgan barcha mahsulotlarni ro‘yxat qilib qaytaring.
* **task 20:** Har bir kategoriyaga tegishli mahsulotlarning **o‘rtacha narxini** hisoblang va natijani dictionary ko‘rinishida chiqaring.

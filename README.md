# Formula 1 Ecommerce

JavaFX + SQLite implementation for the customer component.

## Eclipse setup

1. Open Eclipse.
2. Go to `File > Import > Maven > Existing Maven Projects`.
3. Select this folder: `outputs/CustomerApp-F1Merch/F11 CUST`.
4. Let Maven download JavaFX and SQLite JDBC dependencies.
5. Run with:

```bash
mvn javafx:run
```

The app uses `Ecom_Cust.db` in this project folder by default. To use another database file, add this VM argument:

```bash
-Decom.db.path="C:\Users\hp\OneDrive\Desktop\BRUNEL STUFF(CS)\Ecom_Cust.db"
```

## Default login

Customer from the database:

- Email: `caroline.david@gmail.com`
- Password: `123456`

Seed admin created by the app if the Admin table is empty:

- Email: `admin@redline.com`
- Password: `admin123`

## Implemented customer requirements

- Register customer with unique email and ID-card file path.
- Add delivery information after registration.
- Login with session.
- Choose an F1 team from the home screen.
- Open a team merch catalogue and add products to favourites.
- Open a dummy product detail page and add a product to the in-session basket.
- View favourites.
- View read-only order history.
- Update profile and delivery details, while keeping email and ID card locked for customers.
- Deactivate account instead of deleting data.
- Admin login, customer search, edit locked fields, and activate/deactivate accounts.

#### App is live and running at 

### https://nextjs-ecommerce-typescript.vercel.app/


 - don't forget to leave a star ! :)


## Features

#### NOTE
 - Admin Dashboard is only accessible to you if you clone it you can't Signup for Admin Account I have added dummy Product and categories 


#### multi User Login System
- SignIn / SignUp ✔
- Forget Password ✔
- JWT validation on each Authorized Request ✔
- Authorization validation for Admin Access and Customer Access ✔

# ADMIN PANEL
 - Add a product ✔
 - view Product ✔
 - Delete a Product ✔
 - update product ✔
 - Add a Category ✔
 - view Category (Data tables) ✔
 - update Category  ✔
 - Delete category ✔
 - search category By name ✔
 - search product by category Name ✔
 - Handle Order Delivery  ✔
 - Pending Order  List ✔
 - Completed Order List ✔

# Customer
- View Product & Category ✔
- view product related to specific category ✔
- view dynamic pages detail with breadcamp ✔
- Add product to cart ✔
- Remove Product from cart ✔
- Increase Decrease cart Item  Quantity ✔ (IF product Instock Quantity is less then your cart quantity then you are unable to  increase that product Quantity)
- Alert if InStock Quantity isn't Available ✔
- Bookmark favourite Product ✔
- remove product from bookmark ✔
- Order a Product ✔
- After Creating an Order Product Exists in Cart for current User will be Cleared ✔
- track Order Status ✔
- View Order Detail ✔

#### Note 
More Functionality will be added with time



## Tech
- Nextjs 13
- Typescript
- tailwind css
- Redux toolkit
- joi validation
- mongoDB
- SWR hooks for fetching API 

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DB_URI` = Your mongoDB URL

`JWT_SECREAT` = Your custom JWT_SECREAT key

`NEXT_PUBLIC_API_BASE_URL` =  Base URL for localhost  => http://localhost:3000


## Installation

Install my-project with npm

```bash
  npm install
  npm run dev (for development server)
  npm run build (for Production)
  npm run preview (To View Production Server )
```

### Screen shots
####  Admin Dashboard
![1](https://user-images.githubusercontent.com/90745903/236361005-89f40e51-3aff-4e66-8aa2-941138a15316.png)

#### Admin Add Product
![image]([https://private-user-images.githubusercontent.com/90745903/238106828-8c2129fa-bbc4-4d03-b249-a9e4a26ba769.png](https://private-user-images.githubusercontent.com/90745903/238106828-8c2129fa-bbc4-4d03-b249-a9e4a26ba769.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDY4MjgtOGMyMTI5ZmEtYmJjNC00ZDAzLWIyNDktYTllNGEyNmJhNzY5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTU1YTNlOTA0NTBkN2RhNDAxZDU3NGMzZTRmNzVkM2Y0YTg4Mjk5NzVkOTI2NjkwNDA4ODFmY2E2MGMxM2Y5ZjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.GUAjMkxTfqAZZqZjma3n1UfZh4ph3OglSzW5J5zY9d0))

#### Admin Add Category
![image](https://user-images.githubusercontent.com/90745903/236360988-8b7e6307-5365-4486-8404-b8ddaf1ab486.png)

#### Admin View Category
![image](https://private-user-images.githubusercontent.com/90745903/238106722-79d3384f-0aed-4ca0-9bb6-c74a42042cfa.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDY3MjItNzlkMzM4NGYtMGFlZC00Y2EwLTliYjYtYzc0YTQyMDQyY2ZhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTliMWMzMDVhZDFkODM0YzE2ZWY5ZDFlOGJmMWFhYTZhOWE3MDc0MDE5Yjc2ZWIxODMwZTMxN2QzNjBjNDhhMjQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.2-8p78ozHHa1hfvVZgBqR6QvE0Mj_3vgmNiI1qxTMZ8)

#### Admin View Product
![image](https://private-user-images.githubusercontent.com/90745903/238107419-f0a85e4a-891e-4c1f-86fe-206dedb6034c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc0MTktZjBhODVlNGEtODkxZS00YzFmLTg2ZmUtMjA2ZGVkYjYwMzRjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPThmOTI0NzJlZGNmMDkwMmY2Y2UxMTMzY2ZmZTAwZWQ1NWQ5ZGJlMWQ3ZWUyMTBkMzU2YmFkYzE0ODhmN2JkNzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.T-a4XopiQIfgJAojrbfa0YXFY3qB6B3ob6Y1dRt0Ksk)

#### Admin Search Product with category Name
![image](https://private-user-images.githubusercontent.com/90745903/238107434-76f09c2a-4c16-4784-afa0-5f424a42430f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc0MzQtNzZmMDljMmEtNGMxNi00Nzg0LWFmYTAtNWY0MjRhNDI0MzBmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWI4ODUzOTAzZmY0YTViODI0NGZkOTY3YmE1NzI5NzkwNTViYzJjMTMyZGNkMzVlYTY4NWNhYzY2MmE1ZGEyNjkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.fJkX6z2pYik76Q58aJWHT-0oKNYCcO7z3rRnzwdwJiI)

#### Admin Search category with category Name
![image](https://private-user-images.githubusercontent.com/90745903/238107456-600bb84b-9401-48e9-90b8-44891f794b81.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc0NTYtNjAwYmI4NGItOTQwMS00OGU5LTkwYjgtNDQ4OTFmNzk0YjgxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE3NWJhZDQzYTFiODQ0MDc4OTE3NzY5YzlkYzA4M2EyOTU1MTI2NjQwMTBiMjBlMTNmZDExZDAxOWRlZjBjYTYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.d2Pe21kTFyleeSDZYLd5Db4tCKSPC0BApaQyC6myQao)

#### Pending Order List
![image](https://private-user-images.githubusercontent.com/90745903/243026810-66f07720-dc2f-4a05-98fc-d9c422665dc9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDMwMjY4MTAtNjZmMDc3MjAtZGMyZi00YTA1LTk4ZmMtZDljNDIyNjY1ZGM5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTFkMWViNzEyN2FlZDNiMzY0NGY3YjgwZDgyNGIyZTk5YWE3ZDFiYjc5YTkwNTIwZWNhOWVjZDA4MjI2YzRiNTYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.dcdu5GnWW57UoAAhGrOCWS5mp9dWwLRvudbtpaFYwdY)


#### Completed Order List
![image](https://private-user-images.githubusercontent.com/90745903/243026384-278e33ae-b7bb-4cf2-8ed3-18e06d1f368c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDMwMjYzODQtMjc4ZTMzYWUtYjdiYi00Y2YyLThlZDMtMThlMDZkMWYzNjhjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc2NzRhYTYyZjQwMGRlNWM0OTQxYWRiZTAzZmU4ZDU1YjY4MDQ0ZTQ3Mjk3YmUyNGNjMzIzM2QwMzQ2OWE1NDImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.n5ANDYdQIGeI7U-12yfzNpNBRxOL5xAYgdWigCocSSw)



#### Landing Page 

![image](https://private-user-images.githubusercontent.com/90745903/240775451-a4a21833-3f42-479f-99b8-1dba1b459f1b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDA3NzU0NTEtYTRhMjE4MzMtM2Y0Mi00NzlmLTk5YjgtMWRiYTFiNDU5ZjFiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBmMjM3OWJmYTcxZTVkYmE1ZGExMmJmYWY0NWExNjhiNDY4YzUyMWFiYzNlMjRjN2QzYjNiM2M5MGUwZGQ1MzUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.dJOKtaYUlsV6lt-GSBjdJFLE5iMfiCvYYrAClGs4lDw)

![image](https://private-user-images.githubusercontent.com/90745903/238107499-bb8141aa-9ded-4a77-a653-c86733bd7871.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc0OTktYmI4MTQxYWEtOWRlZC00YTc3LWE2NTMtYzg2NzMzYmQ3ODcxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZjZTY3Nzg0NWUwN2RjYmMwOTlkNDg2ZmYwODMwMzM3NTgxY2U4N2QzZjYyMmYwYjI2ZmYzNTIxNjVkNjUyYzAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.J396aZtLc87rRDlnqQVZgiPM5T60a7LU6xQBtaSOT1c)

![image](https://private-user-images.githubusercontent.com/90745903/238107512-9970dabd-eb75-4c6b-8349-d55897a5f9c4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc1MTItOTk3MGRhYmQtZWI3NS00YzZiLTgzNDktZDU1ODk3YTVmOWM0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTA4ZWRjZjAxM2RiOGUzM2I3YTY3ZDlkZjI3MDczM2U2Y2M4NGYwMjJkNGVjOGRhMDBlYTBkZDg4ZGJmMTAwMzgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.vn8GAP4KKeznAgQ0d8yAKqtueKU1nOxaYBDJpkipOfQ)


#### view Product of Specific category with Dynamic Breadcamp 
![image](https://private-user-images.githubusercontent.com/90745903/238107540-7babf0cb-2b67-439d-9859-61f21d2ce453.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc1NDAtN2JhYmYwY2ItMmI2Ny00MzlkLTk4NTktNjFmMjFkMmNlNDUzLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTRkMDVjYjA5N2U2MzY0Y2JiY2M3ZjdjZTZmNWE3YjIzYjEyYjBkOGY3ZWU0ODFiZGE4OTkwNGUwMmQwZDNmZjUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.eCBl681BUzswsPTXVg6q7-MAwB3AzK3ygGEhfhh94gQ)

![image](https://private-user-images.githubusercontent.com/90745903/238107553-df41987a-d2e3-4681-b814-41d1986de7af.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc1NTMtZGY0MTk4N2EtZDJlMy00NjgxLWI4MTQtNDFkMTk4NmRlN2FmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTliNGZjYzk1MDE4MGI4MzE5Y2MyMTY1N2MxMTZmNTdjYjBlNmI5NTRiYmJhZDIxZGNjZWU0NDI3ZWViNTcxOTImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.uqgEB6F9woii0wxfiT1rddqrsnog8cb8o8CMCeSkLoc)

#### view Product of Detail with Dynamic Breadcamp 

![image](https://private-user-images.githubusercontent.com/90745903/238107623-9eda3f30-3a12-4401-952d-3a694b097e77.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzgxMDc2MjMtOWVkYTNmMzAtM2ExMi00NDAxLTk1MmQtM2E2OTRiMDk3ZTc3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI5MDdiNWU5MDg0ZGI0NjM0OTk3ZTIzMDdkYzkwNzQwMzNiZGY4NzI1YzAzYjBiNTQ2YWI1MWQzNGIxOWZmYWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ZpkY8FB3vkjYa8VFH39YdXGFXzxL9iY-hIJ_-P6Tdsc)

#### Cart Page 
![image](https://private-user-images.githubusercontent.com/90745903/239411447-23b08511-0e6e-41c1-8b9d-7f72b5b65952.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzk0MTE0NDctMjNiMDg1MTEtMGU2ZS00MWMxLThiOWQtN2Y3MmI1YjY1OTUyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBhODBkN2NkZDQwYTM3N2JkNmZiMWU4Njk5Y2M1NDIzN2U3OGQ3MDJlODgzZmNlOWE3ZTI3OTM1NDc2MTMzMDEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.kuzSar1GzPNxN2CynMI0HoH0hYZKH_lPOB5uefim8Co)

#### Alert IF Item Quantity isn't available in stock 
![image](https://private-user-images.githubusercontent.com/90745903/239782860-3a129a57-2df3-440a-9b1c-5c43348027f5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yMzk3ODI4NjAtM2ExMjlhNTctMmRmMy00NDBhLTliMWMtNWM0MzM0ODAyN2Y1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWUxMDY5Y2UyMGQwNmE0M2QyNzFhMTIyNzE4YmEyZjA0OTIwN2ZlODJmOGJiZjZmN2UxM2JlYmFhM2U1MmVkNzAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.NQadNtCc13CFZ6DYLYANIno42N-kF0So1ZdXToMHIEs)


#### Favourite Products
![image](https://private-user-images.githubusercontent.com/90745903/240775620-a2debeef-585c-4bc5-bd39-4c6680deee7d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDA3NzU2MjAtYTJkZWJlZWYtNTg1Yy00YmM1LWJkMzktNGM2NjgwZGVlZTdkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWFmYjNhOTJkMzljYTc4NDhiNzhmNTFkZDM5YWVlNWQ2MTIxNTMzZTgzOTA0ZmQ1N2FmMWZmYTdmNmU1ZjVjMDEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.sSZnJfoYmu4Lfd9isFtM9YkmmFFa1PTucjDSFBm2V3k)


#### Delete Favourite Products
![image](https://private-user-images.githubusercontent.com/90745903/240775680-092ce378-7db0-4119-8130-65f5330cd689.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDA3NzU2ODAtMDkyY2UzNzgtN2RiMC00MTE5LTgxMzAtNjVmNTMzMGNkNjg5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJiYjZkNTZkYzQ3NTFiMmQwNDVmYTMyYTUxNzg4Y2Q1NzM3NmE5ZTNjMDZlZGE2OTY4ZWIyMzM3ODFiYmIzZDAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.bw_7xlaOtmeYdqzFPK2vgfzUg7GbJQq0owlwa1aKKHU)


#### Search Favourite Products with product Name
![image](https://private-user-images.githubusercontent.com/90745903/240775765-39e4d3f6-425c-444f-b316-5b2a2b587434.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDA3NzU3NjUtMzllNGQzZjYtNDI1Yy00NDRmLWIzMTYtNWIyYTJiNTg3NDM0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ5ZWYwZGIyMTZiZjUyNmRiYmYzNzJkZWNlZTIwMGI4MGUxNjY5NWE0ZDAwNmZhYzQ3ZTMzMjI0OTkxYWFlMjQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.02JgdRsW3bZ1-FFOdHy1avV3yBlasgWz_pUr7i1r2gs)

#### Order a Product
![image](https://private-user-images.githubusercontent.com/90745903/241601804-a958670a-8d89-411c-af41-901d933920d7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDE2MDE4MDQtYTk1ODY3MGEtOGQ4OS00MTFjLWFmNDEtOTAxZDkzMzkyMGQ3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTU2NWZlNWIxYmY3MWM1NWJiM2IwZGJjNmM4N2M5Mjc2MzI0NDE0NGY3MTc1NWNiZTk1Yzg2YThkNmQ2ZDU0YTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.rEKtuF17aOv8bDqprO5xB7tMEuVJt-fqvXDmh0lUBO8)

#### Track Orders
![image](https://private-user-images.githubusercontent.com/90745903/242449421-8501280b-dbf8-4fdc-abf3-5afb003ac251.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDI0NDk0MjEtODUwMTI4MGItZGJmOC00ZmRjLWFiZjMtNWFmYjAwM2FjMjUxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTFjYjdhNTFjMDQ2NDQ3MzEyNWMwMzA3MGJhNTFiMzJkZTZlOGIwN2I4MjlmZWMyZWQ2ODk5YTg3Y2I3OTczNzQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ns5-aWgGq8W5HK4JvXYz9h-cx-8yDo94cDDH_V2aWOs)


#### Check order Details
![image](https://private-user-images.githubusercontent.com/90745903/242487639-139f02be-806f-4d8c-8cba-51948682277a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk3NzUxODQsIm5iZiI6MTcxOTc3NDg4NCwicGF0aCI6Ii85MDc0NTkwMy8yNDI0ODc2MzktMTM5ZjAyYmUtODA2Zi00ZDhjLThjYmEtNTE5NDg2ODIyNzdhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNjMwVDE5MTQ0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWQ0MGRhODY0NjQ3YzdlY2QyYTYwYmUwZTNjYTFmN2M3YzM3N2FiZjViODA4ZGRhNThlOWJmODI4YzcxYjcxM2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.7S5o7pRWKbCDCQ5j8eZVvW1tQ2ysQK6VJa1x8gElW24)






    

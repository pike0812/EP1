## PHẠM CÔNG THÀNH - 22725811

### 1. Đăng ký tài khoản
* **Method**: `POST`
* **URL**: `http://localhost:3000/register`
* **Body** (`raw`, `JSON`):
    ```json
    {
        "username": "congthanh1",
        "password": "2004"
    }
    ```
![alt text](public/register.jpg)

### 2. Đăng nhập
* **Method**: `POST`
* **URL**: `http://localhost:3000/login`
* **Body** (`raw`, `JSON`):
    ```json
    {
        "username": "congthanh1",
        "password": "2004"
    }
    ```
    ![alt text](public/login.jpg)


### 3. Tạo sản phẩm mới
* **Method**: `POST`
* **URL**: `http://localhost:3003/products/api/products`
* **Body** (`raw`, `JSON`):
    ```json
    {
        "name": "Iphone 14 promax",
        "description": "fsad",
        "price": 17000
    }
    ```
    ![alt text](public/create.jpg)
   

### 4. Mua sản phẩm
* **Method**: `POST`
* **URL**: `http://localhost:3003/products/api/product/buy`
* **Body** (`raw`, `JSON`):
    ```json
    {
        "ids": ["Id"]
    }
    ```
 ![alt text](public/buy.jpg)

---



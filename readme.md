CRUD operations using API
First Run php artisan migrate to create the database

API's

1- Show all product - http://127.0.0.1:8000/api/product

2- Show some particular product api - http://127.0.0.1:8000/api/product/1

3- Store product - http://127.0.0.1:8000/api/product using POST Method and passing "title" and "body" in the body of the request and using content type json.

4- Edit product - http://127.0.0.1:8000/api/product using PUT Method and passing "article_id" , "title" and "body" in the body of the request and using content type json.

5- Delete product - http://127.0.0.1:8000/api/product/1 using DELETE Method.

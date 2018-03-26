CRUD operations using API
First Run php artisan migrate to create the database

API's

1- Show all article - http://127.0.0.1:8000/api/product

2- Show some particular api - http://127.0.0.1:8000/api/product/1

3- Store article - http://127.0.0.1:8000/api/product using POST Method and passing "title" and "body" in the body of the request and using content type json.

4- Edit article - http://127.0.0.1:8000/api/product using PUT Method and passing "article_id" , "title" and "body" in the body of the request and using content type json.

5- Delete article - http://127.0.0.1:8000/api/product/1 using DELETE Method.

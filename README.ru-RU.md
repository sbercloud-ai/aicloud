# Публичный репозиторий AICloud
### Как пользоваться API с помощью Postman:
##### 1. Установка postman 
Удостоверьтесь, что Postman установлен. Postman можно сказать по ссылке ниже:

[Postman Official Website](https://www.postman.com/downloads/)

##### 2. Импорт postman-коллекции AICloud 
1.  Откройте Postman.
2.  В верхнем левом углу кликните на **Import**
3.  Выберите вкладку **Link**, и используйте ссылку ниже для импорта:
    
    ```
    https://raw.githubusercontent.com/sbercloud-ai/aicloud/Docs-for-postman/api.postman-collection.json
    ```

    ![import postman collection1](/doc/img/postman_import1.png)

4.  Затем подтвердите импорт
5.  Теперь установите ваши данные в переменные коллекции
    
    ![import postman collection2](/doc/img/postman_import2.png)
    ![import postman collection3](/doc/img/postman_import3.png)

##### 3. Авторизуйтесь на AICloud
Вызовите самый первый метод коллекции - ```/public/v1/auth/```

![import postman collection4](/doc/img/postman_import4.png)
    
 Все, скрипт установит полученный api-key в переменные коллекции автоматически
 
Теперь можно использовать другие методы коллекции без каких-либо забот об аутентификации - коллекция автоматически подставляет ваши данные

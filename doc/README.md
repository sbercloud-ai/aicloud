# AICloud Public Repo
### How to use the API with Postman:
##### 1. Installing postman 
Make sure you have Postman installed on your machine. The Postman installation package can be downloaded via the link below:

[Postman Official Website](https://www.postman.com/downloads/)

##### 2. Importing the AICloud collection 
1.  Open Postman.
2.  In the top left corner, click **Import**
3.  Select the **Link** tab, and use the following url for import:
    
    ```
    https://raw.githubusercontent.com/sbercloud-ai/aicloud/Docs-for-postman/doc/api.postman-collection.json
    ```

    ![import postman collection1](/doc/img/postman_import1.png)

4.  Next, confirm the import
5.  Now, set your credentials into the collection's variables by editing the collection
    
    ![import postman collection2](/doc/img/postman_import2.png)
    ![import postman collection3](/doc/img/postman_import3.png)

##### 3. Authenticating your account to AICloud with your credentials
Invoke the very first method in collection - ```/public/v1/auth/```

![import postman collection4](/doc/img/postman_import4.png)
    
 Done, the script will set the api key from response in your collection's variables automatically
 
Now you can invoke every other method without worrying about authentication - the collection will take care of it for you

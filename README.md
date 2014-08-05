# Djamin

Djamin a new and clean styles for Django admin based in Google projects styles.

## Quick start

1. Install djamin:
    ```pip install -e git://github.com/hersonls/djamin.git#egg=djamin```

2. Add "djamin" to your INSTALLED_APPS setting, before django admin app 
   like this:
    ```python
       INSTALLED_APPS = (
           'djamin',
           'django.contrib.admin',
           ...
           
       )
    ```

3. Start the development server and visit the http://127.0.0.1:8000/admin/ and enjoy it. 



## Screenshots

![alt tag](https://raw.githubusercontent.com/hersonls/djamin/master/screenshots/dashboard.png)

![alt tag](https://raw.githubusercontent.com/hersonls/djamin/master/screenshots/changelist.png)

![alt tag](https://raw.githubusercontent.com/hersonls/djamin/master/screenshots/changelist_with_inline.png)

![alt tag](https://raw.githubusercontent.com/hersonls/djamin/master/screenshots/changeform.png)

## Contributing

Please, install and give a try to Djamin. Make a pull request with the bugfix or open a new issue with the screenshot's problem.
Any kind of help are welcome!

## Creator

**Hersonls**

- <http://twitter.com/hersonls>
- <http://github.com/hersonls>

## SAML example

> To run `make_metadata.py` you need `python 3.7` won't work on python 3.10

```
cd sp-wsgi/
make_metadata.py sp_conf > sp.xml

cd ../idp2
./idp.py idp_conf 
```

```
cd djangosample/
./manage.py runserver
```

visit: http://localhost:8000/djangosaml/login/

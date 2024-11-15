# REST API

Rest **API** en su mayoria lo que hace es regresar datos **JSON**

# CRUD y métodos http

**Create :** POST -> Crear

**Read :** GET -> Leer

**Update :** PUT/PATCH -> Put actualiza todos los datos de la entidad, Patch -> solo envió los datos que se están actualizando

**Delete :** DELETE -> Eliminar

```Javascript
EndPoint	Method	Body	Response	status
----------------------------------------------------
/products	GET	N/A	[{}, {}, ...]	200
----------------------------------------------------
/products/:id	GET	N/A	{}	200
----------------------------------------------------
/products/categories	GET	N/A	[{}, {}, ...]	200
----------------------------------------------------
/products	POST	{...}	{...}	201
----------------------------------------------------
/products/:id	PATCH	{ }	{ }	201
----------------------------------------------------
/products/:id	DELETE	N/A	true / false	201
----------------------------------------------------
```

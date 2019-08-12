API JWT NODEJS MongoDB

Requisitos:
	Nodejs v10
	Mongodb v3.2.19


Uso

	Autenticarse registrando "user"
		POST:     http://3.82.122.13:3000/auth/register
			body: username, email, password
			imagen demo: https://i.imgur.com/Nyr7aMq.png			

	Login para obtener token jwt.
		POST:     http://3.82.122.13:3000/auth/login
		imagen demo: https://i.imgur.com/NJDa1PX.png

	Traer(GET) contactos "crm" usando el token jwt.
		http://3.82.122.13:3000/contact
		imagen demo: https://i.imgur.com/iaOw77U.png
	
	Crear(POST) un contacto "crm" usando el token jwt.
		http://3.82.122.13:3000/contact
		imagen demo: https://i.imgur.com/7rADdHw.png

	Traer(GET) contactos "crm" usando el token jwt.
		http://3.82.122.13:3000/contact/:contactId
		imagen demo: https://i.imgur.com/iaOw77U.png

	
	Actualizar(PUT) contacto "crm" usando el token jwt, y el id.
		http://3.82.122.13:3000/contact/:contactId
		imagen demo: https://i.imgur.com/fpwxfbe.png

	Borrar(DELETE) contacto "crm" usando el token jwt, y el id.
		http://3.82.122.13:3000/contact/:contactId
		imagen demo: https://i.imgur.com/yS6MpNK.png 

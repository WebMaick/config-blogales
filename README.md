# config-blogales

## Expresiones Regulares

background-image: radial-gradient(circle at top right, rgb(78, 78, 78) 0%, rgb(78, 78, 78) 1%,rgb(72, 72, 72) 1%, rgb(72, 72, 72) 10%,rgb(65, 65, 65) 10%, rgb(65, 65, 65) 22%,rgb(59, 59, 59) 22%, rgb(59, 59, 59) 23%,rgb(53, 53, 53) 23%, rgb(53, 53, 53) 28%,rgb(46, 46, 46) 28%, rgb(46, 46, 46) 37%,rgb(40, 40, 40) 37%, rgb(40, 40, 40) 100%);

EXPRESIONES REGULARES
usuario: /^[a-zA-Z0-9\_\-]{4,16}$/, // Letras, numeros, guion y guion_bajo
	nombre: /^[a-zA-ZÀ-ÿ\s]{1,40}$/, // Letras y espacios, pueden llevar acentos. / => para html no debe contener patter = '^[a-zA-ZÀ-ÿ\s]{1,40}$'
	password: /^.{4,12}$/, // 4 a 12 digitos.
correo: /^[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+$/,
	telefono: /^\d{7,14}$/ // 7 a 14 numeros.
comentarios para textarea: ^.{1,255}$

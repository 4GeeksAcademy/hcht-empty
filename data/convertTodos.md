# Convertir de JSON a TOON

- Objetivo:

## Input: Estructura JSON

```json
[
  {
     "userId": 10,
     "id": 200,
     "title": "ipsam aperiam voluptates qui",
     "completed": false
   }
]
```

## Output: Extructura TOON
```toon
todos[3]{userId,id,title,completed}:
1,1,"delectus aut autem",false
1,2,"quis ut nam facilis et officia qui",false
1,3,"fugiat veniam minus",false
```


```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is my first paragraph.</p>
</body>
</html>
```

## Ejemplo de una función

```js
// Codigo en JavaScript
const myFunc = () => {
  return 'hola'
}

```



```yaml
project:
	name: seamos-emprendedores
	stack:
		- react
		- nextjs
		- typescript
		- tailwindcss

packageManager: npm

install:
	# Opcion recomendada: crear el proyecto desde cero con todo configurado
	createProject:
		command: "npx create-next-app@latest . --ts --tailwind --eslint --app --src-dir --import-alias '@/*'"

	# Opcion para cuando el proyecto ya existe y solo falta instalar dependencias
	existingProject:
		commands:
			- "npm install"
			- "npm install -D tailwindcss postcss autoprefixer"
			- "npx tailwindcss init -p"

run:
	dev: "npm run dev"
	build: "npm run build"
	start: "npm run start"
``
Vamos a utilizar twins para no preocuparnos tanto por los styles components
    npm i autoprefixer postcss tailwindcss

La siguiente sentencia genera los archivos de configuracion "postcss.config.js" y "tailwind.config.js"
    npx tailwindcss init -p

Uiliza:
    routing con "React Router"  ->  npm i react-router-dom

    import { Outlet, Link, useLocation } from "react-router-dom"

    #Nota: Outlet se usa para cambiar dinamicamente el contenido
        Link: es un wrapper de anchor, es mas optimo y no hace refresh
        useLocation: permite ver donde estamos parados cuando se navega
            la url con sus parametros

#Se usa las librerias: Formik y Yup para formularios
    npm i formik yup

#Instalo JSON-Server para la creación de API's
    sudo npm install -g json-server

    Se genera el archivo db.json y se corre el server con el siguiente comando:
    json-server --watch db.json --port 4000

#En el formulario se puede ver como se utiliza async, await y se redirecciona con:
    import { useNavigate } from 'react-router-dom'

    de 'react-router-dom' se puede ver ejemplo de useParam y navegate

Ejemplo de defaultProps en Formulario.jsx
Ejemplo de notacion condicional cliente?.nombre ?? ""

# Uso https://my-json-server.typicode.com/LeonardoAMedina/api_crm/clientes
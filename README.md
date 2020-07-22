# Blog-BackEnd
Back End del blog desarrolado con React Native, usamos ngrok

El front esta en el siguiente repositorio https://github.com/patricioprp/Blog-React-Native
Para correr esto primero entramos a la raiz y corremos npm run db, luego en otra venta de la consola corremos npm run tunnel 
Luego en la ultima consola veremos el primer Forwarding copiamos ese valor y lo pegamos dentro de la carpeta del front src/api/jsonServer.js y se lo asignamos como valor a baseURL,
por ultimo corremos npm start en otra pestaña

# Dockerfile for Frontend (Angular)

# Usamos la imagen oficial de Node.js
FROM node:16

# Definimos el directorio de trabajo
WORKDIR /app

# Copiamos los archivos de la aplicación Angular al contenedor
COPY . /app/

# Instalamos las dependencias de Angular
RUN npm install

# Exponemos el puerto donde Angular servirá la aplicación
EXPOSE 4200

# Ejecutamos la aplicación Angular en modo de desarrollo
CMD ["npm", "start"]

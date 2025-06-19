# Usa la imagen base de Node.js
FROM node:14

# Establece el directorio de trabajo
WORKDIR /app

# Copia los archivos de la app al contenedor
COPY . .

# Instala las dependencias
RUN npm install

# Expone el puerto que usa tu app
EXPOSE 3000

# Comando para ejecutar la app
CMD ["node", "index.js"]

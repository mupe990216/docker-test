#Universidad Internacional de la Rioja
#Contenedores
#Elias Muñoz Primero

#Usa la imagen oficial de Python 3.6 como base
FROM python:3.6

#Copia todos los archivos del directorio actual al directorio /app dentro del contenedor
COPY . /app

#Establece /app como el directorio de trabajo dentro del contenedor
WORKDIR /app

#Instala el paquete Flask usando pip dentro del contenedor
RUN pip install flask

#Define el comando principal que se ejecutará al iniciar el contenedor: el intérprete de Python
ENTRYPOINT ["python"]

#Proporciona los argumentos predeterminados al comando ENTRYPOINT: ejecutar app.py
CMD ["app.py"]
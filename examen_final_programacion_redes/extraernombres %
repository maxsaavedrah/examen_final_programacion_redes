import json

# Ruta al archivo JSON
archivo_json = "usuarios.json"

# Leer el archivo JSON
with open(archivo_json, "r") as archivo:
    datos = json.load(archivo)

# Extraer y mostrar los nombres de los usuarios
print("Nombres de usuarios:")
for usuario in datos:
    print(usuario["nombre"])

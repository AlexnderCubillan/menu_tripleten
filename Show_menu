# Función para crear un nuevo archivo
def create_new_doc():
    # Aquí puedes agregar la lógica para crear un nuevo archivo
    print("Creando un nuevo documento...")

# Función para abrir un documento
def open_doc():
    # Aquí puedes agregar la lógica para abrir un archivo existente
    print("Abriendo un documento...")

# Función para guardar un documento
def save_doc():
    # Aquí puedes agregar la lógica para guardar el archivo actual
    print("Guardando el documento...")

# Función para guardar documento con otro nombre
def save_as_doc():
    # Aquí puedes agregar la lógica para guardar el archivo con un nombre diferente
    print("Guardando el documento con otro nombre...")

# Menú principal
menu = {
    "Menú": {
        "id": "1",
        "value": "Archivo",
        "lista": {
            "items": {
                "new_doc": {
                    "value": "Nuevo",
                    "onclick": create_new_doc
                },
                "open_doc": {
                    "value": "Abrir...",
                    "onclick": open_doc
                },
                "save_doc": {
                    "value": "Guardar",
                    "onclick": save_doc
                },
                "save_as_doc": {
                    "value": "Guardar como...",
                    "onclick": save_as_doc
                },
                "print_option": {
                    "value": "Opciones de impresión",
                    "onclick": {
                        "show_print_option": {
                            "Color": "Saturado",
                            "¿Impresión en blanco y negro?": True,
                            "Tamaño de impresión": "A4"
                        }
                    }
                }
            }
        }
    }
}

# Ejemplo de uso
if __name__ == "__main__":
    print("Bienvenido al menú de opciones:")
    for item in menu["Menú"]["lista"]["items"]:
        print(f"- {menu['Menú']['lista']['items'][item]['value']}")


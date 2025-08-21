def conversor_moneda():
    print("\n--- Conversor de Monedas ---")
    dolares = float(input("Ingrese cantidad en dólares: $"))
    tasa = 8.75  # ejemplo: 1 dólar = 8.75 quetzales
    print(f"{dolares} USD = {dolares * tasa} en moneda local")

def conversor_masa():
    print("\n--- Conversor de Masa ---")
    kg = float(input("Ingrese masa en kilogramos: "))
    print(f"{kg} kg = {kg * 1000} gramos")

def conversor_volumen():
    print("\n--- Conversor de Volumen ---")
    litros = float(input("Ingrese volumen en litros: "))
    print(f"{litros} L = {litros * 1000} mililitros")

def conversor_longitud():
    print("\n--- Conversor de Longitud ---")
    metros = float(input("Ingrese longitud en metros: "))
    print(f"{metros} m = {metros * 100} cm")

def conversor_almacenamiento():
    print("\n--- Conversor de Almacenamiento ---")
    gb = float(input("Ingrese almacenamiento en GB: "))
    print(f"{gb} GB = {gb * 1024} MB")

# Menú principal
def menu():
    while True:
        print("\n===== Conversores =====")
        print("1. Monedas")
        print("2. Masa")
        print("3. Volumen")
        print("4. Longitud")
        print("5. Almacenamiento")
        print("6. Salir")

        opcion = input("Seleccione una opción: ")

        if opcion == "1":
            conversor_monedas()
        elif opcion == "2":
            conversor_masa()
        elif opcion == "3":
            conversor_volumen()
        elif opcion == "4":
            conversor_longitud()
        elif opcion == "5":
            conversor_almacenamiento()
        elif opcion == "6":
            print("¡Gracias por usar el programa!")
            break
        else:
            print("Opción inválida, intente de nuevo.")

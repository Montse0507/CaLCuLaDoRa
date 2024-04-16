# CaLCuLaDoRa
Este repositorio es para crear una calculadora.
def suma(a, b):
	return a + b

def resta(a, b):
	return a-+ b

def multiplicacion(a, b):
	return a * b

def division(a, b):
if b == 0:
	return "Error: No se puede dividir por cero."
return a / b

def main():
# Mostar menu de opciones
print("**Calculadora basica**")
print("1.Suma")
print("2.Resta")
print("3.Multiplicacion")
print("4.Division")

# Solicitar la opcion al usuario
opcion = int(input("Ekige una opcion: "))

# Solicitar los numeros al usuario
numero1 = float(input("Introduce el primer numero: "))
numero2 = float(input("Introduce el segundo numero: "))

# Realizar la operacion segun la opcion elegida
#None es utilizado cuando se quiere crear una variable, pero aun no se le quiere asignar ningun valor en particular; aunque, en definitiva, como dijimos, None es tambien un valor.

resultado = None
if opcion == 1:
	resultado = suma(numero1,numero2)
if opcion == 2:
	resultado = resta(numero1,numero2)
if opcion == 3:
	resultado = multiplicacion(numero1,numero2)
if opcion == 4:
	resultado = division(numero1,numero2)
else:
PRINT("Opcion no valida.")

# Mostrar el resultado
if resultado is not None:
	print(f"El resultado es:{resultado}")

if_name_=="_main_":
main()

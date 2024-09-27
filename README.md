# xmn_factorial
# Programa para calcular el factorial de un número entero
print("")

print(" Nombre: Frias Villa Angel Valentin 3W") #ingresa el nombre del creador 

print(" docente: Escobedo Granados Alejandro.") #ingresa el nombre de nuestro docente  

print("")


# Solicitar al usuario que ingrese un número entero

N = int(input("Ingresa un número entero para calcular su factorial: "))


# Inicializar el factorial en 1

factorial = 1

# Verificar si N es un número no negativo

if N < 0:

   print("El factorial no está definido para números negativos.")
    
else:
    # Calcular el factorial utilizando un bucle
    
 for i in range(1, N + 1):
  
  factorial *= i  # Multiplicar el factorial por cada número desde 1 hasta N
        

 # Imprimir el resultado
 
 print(f"El factorial de {N} es: {factorial}")
 ![image](https://github.com/user-attachments/assets/2672eae6-e868-4b9d-9cd2-e82b6f13b62f)
 ![image](https://github.com/user-attachments/assets/1e6e299b-3fc1-4ef8-a71c-c4f791984fcf)


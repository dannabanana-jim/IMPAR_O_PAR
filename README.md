# IMPAR_O_PAR
 print (" ")
print("Danna Paola Martinez Jimenez")
print (" ")

#Se le pide al usuario que ingrese un numero del 1 al 10
numero1 = input("Ingrese un numero del 1 al 10: ")
num1 = int(numero1)

#Se declaran las variables pares e impares y un 0 para evitar un posible error
a = [2, 4, 6, 8, 10]
b = [1, 3, 5, 7, 9]
c = 0

#Proceso en el que se verifica si es impar o par
if num1 in a:
    print("El numero es par")
elif num1 in b:
    print("El numero es impar")
elif num1 == c:
    print ("El numero equivalente a 0")     #Si el ususario pone el numero 0 el programa mostrara que no esta permitido
else:
    print("El numero esta fuera de los numero permitidos")
    
print (" ")

![image](https://github.com/user-attachments/assets/d664d5f6-0bf0-4c3f-8dcf-a06211ae9743)


# arreglos_jhonatan_franky_-a-ez

print("**********************************************************")
print("Bienvenido a la práctiva de arreglos, funcionalidades: ")
print("----------------------------------------------------------")

numero=[1,2,3,4]
print(numero)
print("----------------------------------------------------------")

arreglo=[1,'hola',3, 'dfsdf',1,2,3,4]
print(arreglo)
print("----------------------------------------------------------")

print(len(arreglo))# Conoce el numero de elementos del estado
print("----------------------------------------------------------")

print(arreglo[len(arreglo)-1])#imprimir el ultimo elemento 
print("----------------------------------------------------------")

print(arreglo[-1])# otra forma de imprimir el ultimo elemento
print("----------------------------------------------------------")

print(arreglo[-2]) #para imprimir el penuntimo numero 
print("----------------------------------------------------------")

arreglo.append("jhonatan")#agregamos un elemento al final 
print(arreglo)
print("----------------------------------------------------------")

arreglo.insert(5,"Ñañez")#insertar en el indice 5, un elemento
print(arreglo)
print("----------------------------------------------------------")

print(arreglo.count("jhonatan"))# count imprime el numero de veces que se encuentra jhonatan
print("----------------------------------------------------------")

arreglolice=arreglo[1:-1] #imprime todos los elementos menos el primero y el último
print(arreglolice)
print("----------------------------------------------------------")

letras=['B','A','E','Z','b']
print(letras)
print("----------------------------------------------------------")

letras.sort()#para ordenar las letras
print(letras)
print("----------------------------------------------------------")

letras.extend(arreglo) #adiciona los elementos de otras arraylis 
print(letras)
print("----------------------------------------------------------")

letras.index('A') #para buscar la letra en la posicion
print(letras)
print("----------------------------------------------------------")

letras.reverse()#invierte los elementos de una lista
print(letras)
print("----------------------------------------------------------")

letras.remove("jhonatan") # elimina un elemento de la lista
print(letras)

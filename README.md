# Sistema-Contable
este codigo esta simulando una tienda de tecnologia basico
--------------------------------------------------------------------
Tienda de tecnologia
-------------------------------------------------------------------
Explicacion del codigo
el codigo esta simulando una tienda que vende 3 productos de tecnologia
que toda persona tiene o tenia y esta echo con programacion basica que 
todos los programador que usan siempre en codigo.
---------------------------------------------------------------------
Informacion Personal
Nombre: Edison Guillermo Gonzalez Vasquez
Curso: 4-i
Especialidad: Programacion
Objetivo profesonal: Mi obejetivo es la de mostrar como se hace un codigo para gente que
sabe programacion basica o ver como se hace un codigo de una tienda basica.
Lenguajes de programacion: Python, Java, Html y JavaScript.
Porque elegi programacion es la facilidad de hoy en dia que puedes estudiar esta carrera y tienes 
mas hermanientas que te facilitan aprender y tambien porque de niño me gustaba mucho.
------------------------------------------------------------------------------------------ 
El código aquí está para que lo vean
________________________________________
nombre= input("ingrese tu nombre")
edad= int(input("ingrese su edad"))
resta=18-edad
if edad >= 18:
    print(f"{nombre}, eres mayor de edad.")
else:
    print(f"{nombre}, te faltan {resta} años para los 18")

#Productos= {
    "Mause": 15000,
   "teclado": 25000,
   "Monitor": 120000
}
usu=str(input("ingrese un nuevo producto: "))
pre=int(input("ingrese el precio del producto: "))
for nombre, precio in Productos.items():
#    print(f"{nombre}: ${precio}")
#    print(f"{usu}: ${pre}")
max=int(input("ingrese el numero maximo pere tienes que ser 1 mayor al maximo : "))
#for i in range(1,max):
    if i % 2 == 0:
        print(i, "es par")
   else:
       print(i, "es impar")
def calcular_iva(precio):
    return precio * 1.19
producto= input("producto: ")
precio= float(input("precio: "))
iva=precio*0.19
print(f"el precio final de {producto} con iva es ${calcular_iva(precio):.0f}")
print(f"el valor del iva es: ${iva} ")

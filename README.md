# Miguel Andres Ortiz Suarez
# IM 165


'''
Aries (21 de marzo-20 de abril) ...3 4
Tauro (21 de abril- 21 de mayo) ...4 5
Géminis (22 de mayo-21 de junio) ...5 6
Cáncer (22 de junio-22 de julio) ...6 7
Leo (23 de julio-23 de agosto) ...7 8
Virgo (24 de agosto-23 de septiembre) ... 8 9
Libra (24 de septiembre-23 de octubre) ... 9 10
Escorpión (24 de octubre-22 de noviembre)... 10 11
Sagitario (23 de noviembre-21 de diciembre)... 11 12
Capricornio (22 de diciembre-20 de enero).. 12 1
Acuario (21 de enero-18 de febrero) ... 1 2
Piscis (19 de febrero-20 de marzo) ... 2 3



'''
while True:  # condicional para hacer un loop , es una forma de reemplazar el do- while en C

    # Variables de mes y dia

    mes = int(input("Ingrese el mes :"))  # Lee la entrada de datos como numero entero
    dia = int(input("Ingrese el dia :"))  # Lee la entrada de datos como numero entero

    # Se comparan para saber si son Aries

    if (mes == 3 and dia >= 21 and dia <= 31) or (mes == 4 and dia <= 20):

        print(" Aries ")

    # Se compara si es Tauro

    elif (mes == 4 and dia >= 21 and dia <= 30) or (mes == 5 and dia <= 21):

        print("Tauro")

    # Se compara si es Geminis

    elif (mes == 5 and dia >= 22 and dia <= 31) or (mes == 6 and dia <= 21):

        print("Geminis")

    # Se compara si es Cancer

    elif (mes == 6 and dia >= 21 and dia <= 30) or (mes == 7 and dia <= 22):

        print("Cancer")

    # Se compara si es Leo

    elif (mes == 7 and dia >= 23 and dia <= 31) or (mes == 8 and dia <= 23):

        print("Leo")

    # Se compara si es Virgo

    elif (mes == 8 and dia >= 24 and dia <= 31) or (mes == 9 and dia <= 23):

        print("Virgo")

    # Se compara si es Libra

    elif (mes == 9 and dia >= 24 and dia <= 30) or (mes == 10 and dia <= 23):

        print("Libra")

    # Se compara si es Escorpion

    elif (mes == 10 and dia >= 24 and dia <= 30) or (mes == 11 and dia <= 23):

        print("Escorpion")


    # Se compara si es Sagitario

    elif (mes == 11 and dia >= 23 and dia <= 30) or (mes == 12 and dia <= 21):

        print("Sagitario")

    # Se compara si es Capricornio

    elif (mes == 12 and dia >= 22 and dia <= 31) or (mes == 1 and dia <= 20):

        print("Capricornio")

    # Se compara si es Acuario

    elif (mes == 1 and dia >= 21 and dia <= 31) or (mes == 2 and dia <= 18):

        print("Acuario")

    # Se compara si es Piscis

    elif (mes == 2 and dia >= 19 and dia <= 28) or (mes == 3 and dia <= 20):

        print("Piscis")


    else:
        print("ni modos carnal , intentalo de nuevo")  # Por si ingreso un valor no apto

    print("\n\n\n Quiere saber otro signo? \n ==>Para SI == 1 \n ==>Para salir == 0")
    out = int(input())

    if out == 0:  # condicional para hacer un loop , es una forma de reemplazar el do- while en C

        break
    else:

        True

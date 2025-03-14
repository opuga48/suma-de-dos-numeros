# suma-de-dos-numeros
def main():
    print("=== SUMADOR DE DOS NÚMEROS ===")
Se define una función main() que contiene la lógica principal del programa.
La línea print() muestra un mensaje de bienvenida.
python
Copiar
Editar
    try:
        num1 = float(input("Introduce el primer número: "))
        num2 = float(input("Introduce el segundo número: "))
El programa solicita dos valores al usuario mediante input().
La función float() convierte el valor introducido en un número decimal.
Si el usuario introduce un valor inválido (como una letra), el programa lanza una excepción (ValueError).
python
Copiar
Editar
        resultado = num1 + num2
        print(f"\nEl resultado de la suma de {num1} + {num2} es: {resultado}\n")
Realiza la suma de los dos números.
Muestra el resultado formateado en la consola.
python
Copiar
Editar
    except ValueError:
        print("\n Error: Por favor introduce solo valores numéricos.\n")
Si el usuario introduce un valor inválido, muestra un mensaje de error amigable.
python
Copiar
Editar
if __name__ == "__main__":
    main()
La línea if __name__ == "__main__": permite que el script se ejecute directamente desde la consola.
Llama a la función main() para iniciar el programa.

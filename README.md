# 🔢 Números del 1 al 10 - Multilenguaje (Pascal + C++ + Python)

## 📌 Descripción

Este proyecto es un programa simple desarrollado en **Pascal**, **C++** y **Python** que imprime en pantalla los números del **1 al 10**.

---

## ⚙️ Funcionamiento

Todas las versiones del programa:

1. Usan un bucle para recorrer del 1 al 10.
2. Imprimen cada número en la misma línea.
3. Separan los valores con espacios.
4. Finalizan con un salto de línea.

---

## 💻 Código en Pascal

```pascal
program numeros1al10;
var i: Integer;
begin
 for i := 1 to 10 do
  write(i, ' ');
 writeLn(' ')
end.
```

---

## 💻 Código en C++

```cpp
#include <iostream>

int main() {
 for(int i = 1; i <= 10; i++) {
  std::cout << i << " ";
 }
 std::cout << "\n";
}
```

---

## 💻 Código en Python

```python
for i in range(1, 11):
    print(i, end=' ')

print()
```

---

## ▶️ Ejecución

### Pascal (Free Pascal)

```bash
fpc numeros1al10.pas
./numeros1al10
```

### C++

```bash
g++ numeros1al10.cpp -o numeros1al10
./numeros1al10
```

### Python

```bash
python numeros1al10.py
```

---

## 🧾 Salida esperada

### Pascal, C++ y Python

```
1 2 3 4 5 6 7 8 9 10
```

---

## 🎯 Objetivo del proyecto

* Comparar sintaxis entre lenguajes
* Practicar bucles (`for`)
* Entender salida por consola
* Introducción a programación básica multilenguaje

---

## 🚀 Futuras mejoras

* Agregar más lenguajes (Java, JavaScript… que esto ya parece un Avengers de código 🧠)
* Permitir al usuario definir el rango
* Modularizar el código en funciones

---

## 📂 Estructura del proyecto

```
/numeros1al10
 ├── numeros1al10.pas
 ├── numeros1al10.cpp
 ├── numeros1al10.py
 └── README.md
```

---

## 📜 Licencia

Uso libre con fines educativos.

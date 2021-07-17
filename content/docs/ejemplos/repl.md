---
title: "Ejemplos de uso de shortcode 'replit' y 'replit-out'"
lead: ''
date: 2021-07-14T21:27:48-04:00
images: []
weight: "200"
menu:
  docs:
    parent: ejemplos
---

## Replit con código:

Ejemplo de uso shortcode para insertar replit

{{< replit name="test" author="@Dav1com" lines=8 >}}

Replit con el numero por defecto de líneas (21):
{{< replit name="test" author="@Dav1com" >}}

Replit con argumentos posicionales:
{{< replit "test" 8 "@Dav1com" >}}

## Solo consola del repl:

{{< replit-out name="test" author="@Dav1com" lines="5" >}}

Bloque de código no modificable, con consola para ejecutar:
```cpp
#include <iostream>

using namespace std;

int main() {
  cout << "Hola Mundo!" << endl;
  return 0;
}
```
{{< replit-out "test" 5  "@Dav1com" >}}

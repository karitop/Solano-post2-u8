# Solano-post2-u8

En este laboratorio se trabajan operaciones aritméticas avanzadas en lenguaje ensamblador x86 usando NASM bajo DOSBox, abarcando tres áreas fundamentales: la aritmética de precisión múltiple de 32 bits mediante las instrucciones ADC y SBB que permiten propagar el acarreo y el préstamo entre palabras de 16 bits; la
aritmética decimal codificada en binario (BCD) empaquetada usando DAA y DAS para corregir resultados tras operaciones de suma y resta; y la construcción de una mini calculadora interactiva que utiliza MUL y DIV con conversión entre representación ASCII y binaria para leer operandos del teclado y mostrar resultados en pantalla.

**Programas**
- post2.asm: Implementa suma y resta de números de 32 bits usando ADC y SBB para propagar el acarreo y el borrow entre las partes alta y baja de los operandos.
- post2b.asm: Realiza sumas y restas en formato BCD empaquetado usando DAA y DAS para ajustar los resultados a dígitos decimales válidos tras cada operación.
- post2c.asm: Calculadora interactiva que lee operandos del teclado, realiza multiplicación o división con MUL y DIV, y muestra el resultado convertido a ASCII.

**Compilación y ejecución**
- nasm -f bin post2.asm -o post2.com
- post2.com
- Reemplaza post2 con post2b o post2c según el programa a ejecutar

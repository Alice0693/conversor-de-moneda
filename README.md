# Conversor de Moneda 💱

Una aplicación Java de consola que permite convertir montos entre diferentes monedas latinoamericanas y el dólar estadounidense, utilizando tasas de cambio actualizadas desde una API externa.

## 🌎 Monedas disponibles

- ARS – Peso argentino 🇦🇷
- BOB – Boliviano boliviano 🇧🇴
- BRL – Real brasileño 🇧🇷
- CLP – Peso chileno 🇨🇱
- COP – Peso colombiano 🇨🇴
- USD – Dólar estadounidense 🇺🇸

## 📋 Menú de opciones

Sea bienvenido(a) al Conversor de Moneda =)

Dólar => Peso argentino

Peso argentino => Dólar

Dólar => Real brasileño

Real brasileño => Dólar

Dólar => Peso colombiano

Peso colombiano => Dólar

Dólar => Boliviano boliviano

Boliviano boliviano => Dólar

Dólar => Peso chileno

Peso chileno => Dólar

Salir 

Seleccione una opción válida:


## 🚀 Cómo ejecutar

1. Cloná el repositorio o copiá los archivos fuente.
2. Asegurate de tener Java 17 o superior instalado.
3. Ejecutá el archivo principal:

```bash
javac ConversorDeMoneda.java
java ConversorDeMoneda

🔗 Dependencias
Gson (para parsear JSON de la API)

Conexión a internet (para obtener las tasas de cambio en tiempo real)

🧠 Estructura del proyecto
ConversorDeMoneda.java: clase principal con el menú y lógica de conversión

ClienteHttp.java: realiza la conexión HTTP a la API de tasas de cambio

RespuestaMonedas.java: modelo para mapear la respuesta JSON

✨ Características
Interfaz clara y amigable en consola

Conversión precisa entre monedas usando tasas actualizadas

Menú interactivo que se repite hasta que el usuario decida salir

Mensajes de bienvenida y separación visual para una mejor experiencia

📌 Próximas mejoras
Validación de entradas no numéricas

Historial de conversiones

Soporte para más monedas y configuraciones regionales


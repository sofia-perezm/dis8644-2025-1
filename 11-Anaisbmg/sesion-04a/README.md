# sesion-04a

01-abril

utilizar kicad -> nos ayudará en las entregas

nota n1
bitacora, encargos, proyecto 01, proyecto 02

*encontrar algo roto*, para ver anatomía, ej: ¿por qué tiene placas distintas? ¿cuáles son sus colores de cable?
ver su carcasa, secciones, funcionalidad, fuente energia, input, output etc.

circuito atari punk console (apc)

circuito generador de sonido con tonos retro similares a las consolas antiguas de atari, en este caso se utilizo dos chips 555, con un ldr c/u, una resistencia c/u y dos capacitadores no polarizados (474, 223, 103, 153)

es un oscilador astable que genera el chip 555 conectado a otro oscilador monostable que genera sonidos más complejos y una salida de audio.

primero se realiza la conexión de un chip, para comprobar que este funcione correctamente.

<https://github.com/user-attachments/assets/6ba4dfb3-29d1-4b5f-a9a2-fba5a45076bc>

luego se conectó el otro chip 555 y conectaron entre estos dos, cada uno con su ldr correspondiente

<https://github.com/user-attachments/assets/d3bf350c-fb34-4923-a0ec-fd045390c40d>

para seguir experimentando se cambio un LDR por un potenciómetro.

<https://github.com/user-attachments/assets/4d1fad82-4ed3-4c98-a48a-088e406926c3>

<https://github.com/user-attachments/assets/33086f25-6561-4c0d-a6a1-809d76dd35c5>

![WhatsApp Image 2025-04-03 at 18 12 40](https://github.com/user-attachments/assets/dcd6d365-d603-434a-83ab-4c31ffb02912)

en el esquematico cuando aparece un . es por que esta conectado, si no aparece este, es por que no lo esta.

## encargo-10

__*1 bit symphony*__
hecha por tristan perich, fue creada en el 2010

la composición es con sonido de 1 bit, bit (binary digit) funciona 0 o 1, apagado o encendido, 0v o 9v, etc.
lo interesante es que es una sinfonía desde un circuito electronico que genera música en tiempo real

la construcción de este cuenta de:

1. bateria cr2032
2. microcontrolador proframado
3. oscilador
4. jack 3.5mm

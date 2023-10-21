# Parcial Domiciliario :page_facing_up:
![Tinkercad](ArduinoTinkercad.jpg)

## Integrantes
- :cowboy_hat_face: Lucas Espindola
- 
---

# Proyecto parte uno: Contador de 0 a 99 con Display 7 Segmentos y Multiplexación
![Tinkercad](ciucuito.jpg)

## Descripción

El proyecto realiza un contador de 0 a 99 utilizando dos displays de 7 segmentos donde se implementa la técnica de multiplexación que permite su funcionamiento. Además cuenta con 3 botones que aumenta, disminuye y resetea el contador.

---
~~~ C
void prendeDigito(int digito)
{ 
    if(digito == UNIDAD)
  {
    digitalWrite(UNIDAD, LOW);
    digitalWrite(DECENA, HIGH);
    delay(TIMEDISPLAYON);
  }
   else if(digito == DECENA)
    {
      digitalWrite(UNIDAD, HIGH);
       digitalWrite(DECENA, LOW);
      delay(TIMEDISPLAYON);
    }
      else
      {
        digitalWrite(UNIDAD,HIGH);
        digitalWrite(DECENA,HIGH);
      }
}
~~~
---

## :computer: Link al proyecto

- [Parte Uno](https://www.tinkercad.com/things/buAP0c983mY)

# Proyecto parte dos: Modificación con Interruptor Deslizante y Números Primos
![Tinkercad](circuito2.jpg)

## Descripcion
> **note**
se agrego tal cosa

## :computer: Link al proyecto parte dos

- [Parte Dos](https://www.tinkercad.com/things/3fFhyDG7J3W)

# Proyecto parte tres: Modificación según el Último Número de Documento
![Tinkercad](circuito3.jpg)

## Descripcion

## :computer: Link al proyecto parte tres
- [Parte Tres](https://www.tinkercad.com/things/gzIJMUw3nne)



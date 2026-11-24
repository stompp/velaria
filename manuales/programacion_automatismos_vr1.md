# Automatismos VR1. Manual de programación

Velaria · Edición 2026 · Documento programacion_automatismos_vr1

Receptor mini y sensor de viento de la línea solar VR1.

## Referencias

- **Receptor mini VR1** (31010013): 1 canal, panel solar
- **Sensor de viento VR1** (31010014): panel solar

## Motores con los que trabaja

Radio VR1. Un emisor VR1 también manda un motor VR2, en modo VR1: sin la confirmación de la posición.

- **Motor T35 Solar 10 Nm VR1** (30010001)
- **Motor T35 Solar 15 Nm VR1** (30010002)
- **Motor T35 Solar 20 Nm VR1** (30010003)

## Emparejar con un motor

1. Sigue los pasos «Emparejar el primer emisor» o «Añadir otro emisor» del manual del motor.
2. En un emisor de varios canales, elige antes el canal con las flechas: cada canal manda un motor.

## Sensores

1. Con el motor (o la central) en modo programación (PROG del emisor 3 segundos), pulsa PROG del sensor un segundo: el motor confirma con dos movimientos cortos.
2. El sensor de viento cierra la cubierta o la puerta a partir del nivel elegido en su rueda: 1 = 20 km/h, 2 = 30 km/h, 3 = 40 km/h, 4 = 50 km/h y 5 = 60 km/h.
3. El sensor de lluvia cierra cuando detecta agua durante 30 segundos seguidos.

## Central y receptores

La central (o el receptor) se empareja con los motores como un emisor más y recibe a su vez los sensores, para dar la misma orden a todos.

## Cambiar la pila

1. Abre la tapa trasera con una moneda y cambia la pila CR2430, con el + hacia arriba.
2. El emisor no pierde los emparejamientos al cambiar la pila.

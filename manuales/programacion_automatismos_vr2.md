# Automatismos VR2. Manual de programación

Velaria · Edición 2026 · Documento programacion_automatismos_vr2

Central de dos motores, sensores de viento y lluvia y pasarela wifi VR2.

## Referencias

- **Central VR2 de dos motores** (31010009): 2 canales, 230 V
- **Sensor de viento VR2** (31010010): 230 V
- **Sensor de lluvia VR2** (31010011): 230 V
- **Pasarela wifi VR2** (31010012): 230 V (en desarrollo)

## Motores con los que trabaja

Radio VR2. Solo con motores VR2: confirma cada orden y enseña si la lona está abierta o cerrada.

- **Motor T45 10 Nm VR2** (30010005)
- **Motor T45 20 Nm VR2** (30010006)
- **Motor T45 30 Nm VR2** (30010008)
- **Motor T45 40 Nm VR2** (30010009)
- **Motor T45 50 Nm VR2** (30010010)
- **Motor T58 60 Nm VR2** (30010011)
- **Motor T58 80 Nm VR2** (30010012)

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

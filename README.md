Sistema de Venta de Pasajes Aéreos
Este proyecto es una aplicación de consola desarrollada en Python que simula un sistema de gestión y venta de pasajes para un vuelo. El programa permite a los usuarios interactuar a través de un menú para realizar diversas operaciones de reserva.

Características Principales
- Visualización de Asientos: Muestra un mapa con los asientos disponibles y ocupados ('X').
- Compra de Pasajes: Permite a los usuarios registrar sus datos (nombre, RUT, teléfono), seleccionar un asiento (Normal o VIP) y realizar la compra.
- Validación de Datos: Incluye validación para el RUT chileno y el formato del número de teléfono.
- Anulación de Vuelos: Un pasajero puede anular su compra, liberando el asiento y eliminando sus datos del sistema.
- Modificación de Datos: Permite a los pasajeros modificar su nombre o teléfono asociados a una reserva existente.
- Descuentos Automáticos: Aplica un 15% de descuento si el pago se realiza con "BANCO DUOC".
- Persistencia de Datos: El estado de todas las reservas se puede guardar en un archivo datos_pasajeros.json y cargarse al iniciar una nueva sesión, manteniendo la continuidad de la información.

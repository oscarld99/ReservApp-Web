# Manual de Administrador de Escenario
## ReservApp · Versión 1.0

---

## ¿Qué puede hacer un administrador?

Como administrador de escenario en ReservApp puedes:
- Publicar y gestionar tus canchas o espacios deportivos.
- Recibir y gestionar solicitudes de reserva.
- Configurar horarios, precios y servicios de cada escenario.
- Ver métricas de reservas e ingresos en tiempo real.
- Contactar directamente a los deportistas que reservan.

---

## Contenido

1. [Registro como administrador](#1-registro-como-administrador)
2. [Dashboard](#2-dashboard)
3. [Gestionar mis escenarios](#3-gestionar-mis-escenarios)
4. [Reservas](#4-reservas)
5. [Ofertas Relámpago ⚡](#5-ofertas-relámpago-)
6. [Configuración del negocio](#6-configuración-del-negocio)
7. [Perfil de administrador](#7-perfil-de-administrador)
8. [Notificaciones](#8-notificaciones)

---

## 1. Registro como administrador

### Crear cuenta

1. Abre la app y toca **Crear cuenta**.
2. Completa todos los campos requeridos.
3. En **Selecciona tu rol**, elige **Administrador de escenario**.
4. Toca **Registrarse**.

> ⚠️ **Importante:** las cuentas de administrador requieren **verificación manual** por parte del equipo de ReservApp antes de poder publicar escenarios. Recibirás confirmación por correo una vez verificada tu cuenta.

### Acceder al panel de administrador

Una vez verificada tu cuenta:
1. Inicia sesión con tu usuario y contraseña.
2. La app te llevará directamente al **panel de administrador** (Dashboard).

### Cambiar entre vista deportista y admin

En cualquier momento puedes cambiar tu vista desde **Perfil → Cambiar a modo deportista** para usar la app como usuario normal y volver al panel desde el mismo menú.

---

## 2. Dashboard

El Dashboard es la pantalla principal del panel de administrador. Muestra un resumen del negocio en tiempo real.

### Métricas principales

| Métrica | Descripción |
|---|---|
| 📅 **Reservas hoy** | Total de reservas programadas para el día de hoy |
| ⏳ **Pendientes** | Reservas que aún no has confirmado ni rechazado |
| 💰 **Ingresos del mes** | Suma del valor total de reservas confirmadas en el mes |
| 🏟️ **Escenarios activos** | Cantidad de escenarios publicados y activos |

### Gráfico semanal

Muestra la cantidad de reservas por día durante los últimos 7 días, útil para identificar los días de mayor demanda.

### Reservas recientes

Lista de las últimas reservas recibidas con estado, deportista, escenario y monto. Toca cualquiera para ver el detalle.

### Alerta de pendientes

Si tienes reservas sin confirmar, aparecerá un aviso en amarillo con el enlace directo a la lista de reservas pendientes.

---

## 3. Gestionar mis escenarios

### Ver mis escenarios

1. Toca **Escenarios** en la barra inferior del panel admin.
2. Verás la lista de tus escenarios con su estado de verificación:
   - 🟢 **Verificado** — visible para todos los usuarios.
   - 🟡 **Pendiente** — en revisión por el equipo de ReservApp.
   - 🔴 **Rechazado** — no cumple los requisitos, revisa el motivo.

### Agregar un nuevo escenario

1. Toca el botón **+ Agregar** en la esquina superior derecha.
2. El formulario tiene 4 pestañas:

---

#### Pestaña: Información

**Fotos**
- Toca **Agregar** para subir fotos desde tu galería.
- La **primera foto** es la portada (badge verde "Portada").
- Puedes subir hasta **8 fotos**.
- Toca la **X** en una foto para eliminarla.

**Información general**
- **Nombre del escenario** *(obligatorio)* — ej: "Cancha El Campeón".
- **Deporte** *(obligatorio)* — selecciona de la lista desplegable.
- **Descripción** — cuéntale a los usuarios qué hace especial tu escenario.
- **Dirección** *(obligatorio)* — dirección completa.
- **Ciudad** — selecciona entre las ciudades disponibles.
- **Barrio** — ej: El Prado, Villa Country.
- **Dimensiones** — ej: "25m x 40m".

**Contacto**
- **WhatsApp** — número para que los deportistas puedan contactarte.
- **Teléfono** — número fijo o celular alternativo.
- **Correo electrónico** — para consultas por correo.

---

#### Pestaña: Horarios

Configura los días y horas en que tu escenario está disponible para reservas.

1. Activa los días disponibles con el interruptor de cada día.
2. Para cada día activo, toca los campos **Apertura** y **Cierre** para seleccionar la hora con el selector.
3. Los días desactivados no aparecerán como disponibles para reservar.

**Ejemplo:**
- Lunes a Viernes: 7:00 am – 10:00 pm ✅
- Sábado: 7:00 am – 11:00 pm ✅
- Domingo: Cerrado ❌

---

#### Pestaña: Precios

Define cuánto cobras por hora según el horario y tipo de día.

**Agregar una franja de precio:**

1. Toca **Agregar franja de precio**.
2. Configura:
   - **Tipo de día** — Todos los días / Lun-Vie / Sábados / Domingos / Sáb+Dom.
   - **Nombre** de la franja *(opcional)* — ej: "Mañana", "Noche", "Fin de semana".
   - **Desde** — hora de inicio de la franja.
   - **Hasta** — hora de fin de la franja.
   - **Precio COP** — valor por hora en pesos colombianos.
3. Repite para cada franja diferente.

**Ejemplo de configuración:**
| Franja | Días | Horario | Precio |
|---|---|---|---|
| Mañana | Lun-Vie | 7:00 – 12:00 | $60.000 |
| Tarde | Lun-Vie | 12:00 – 18:00 | $70.000 |
| Noche | Lun-Vie | 18:00 – 22:00 | $80.000 |
| Fin de semana | Sáb+Dom | 7:00 – 22:00 | $90.000 |

Para eliminar una franja, toca el ícono 🗑️ de esa franja.

---

#### Pestaña: Servicios

Selecciona los servicios disponibles en tu escenario:

| Servicio | | Servicio |
|---|---|---|
| 🚗 Parqueadero | | 💡 Iluminación |
| 🎵 Música | | 👕 Vestidores |
| 📶 WiFi | | 👥 Tribunas |
| 🥤 Refrigerios | | 🚿 Baños |
| 🏠 Cancha cubierta | | 🩺 Primeros auxilios |

Toca cada servicio para activarlo o desactivarlo. Los servicios activos se muestran en el perfil público del escenario.

---

### Guardar el escenario

Toca **Crear escenario** (o **Guardar cambios** si estás editando) en la parte inferior de la pantalla.

El escenario quedará en estado **Pendiente** hasta que sea revisado por el equipo de ReservApp.

### Editar un escenario

1. Toca el escenario en la lista de "Mis Escenarios".
2. En el detalle, toca **Editar**.
3. Modifica los campos que necesites.
4. Toca **Guardar cambios**.

---

## 4. Reservas

### Ver todas las reservas

1. Toca **Reservas** en la barra inferior.
2. Verás la lista de todas las reservas de tus escenarios.

### Filtrar reservas

Usa los filtros disponibles:
- **Por escenario** — si tienes varios escenarios.
- **Por estado** — Pendientes / Confirmadas / Canceladas / Completadas.
- **Por fecha** — selecciona un día específico.

### Gestionar una reserva

Toca cualquier reserva para ver el detalle y las acciones disponibles:

**Confirmar reserva**
- Toca **Confirmar**.
- El deportista recibirá una notificación de confirmación.
- La reserva pasa a estado 🟢 Confirmada.

**Cancelar reserva**
- Toca **Cancelar**.
- Confirma la acción.
- El deportista recibirá una notificación de cancelación.

**Contactar al deportista**
Desde el detalle de la reserva puedes contactar al deportista directamente:
- 💬 **WhatsApp** — abre una conversación de WhatsApp.
- 📞 **Llamar** — marca su número.
- ✉️ **Correo** — abre tu app de correo.

### Badge de pendientes

El ícono de Reservas en la barra inferior muestra un **badge rojo** con el número de reservas que aún no has gestionado. Revísalas a tiempo para no perder clientes.

---

## 5. Ofertas Relámpago ⚡

Las Ofertas Relámpago te permiten publicar horarios disponibles a precio especial para generar reservas inmediatas. Aparecen destacadas en la pantalla de inicio de todos los deportistas con un contador de tiempo.

### Cómo crear una oferta

1. Ve a **Mis Escenarios** → toca el escenario.
2. En el header, toca el botón **⚡** (dorado, al lado del lápiz de editar).
3. Toca **+ Nueva** y completa el formulario:
   - **Título** — ej: "Cancha disponible esta tarde".
   - **Fecha** — el día del horario disponible.
   - **Desde / Hasta** — la franja horaria que quieres ofrecer.
   - **Precio normal** — el precio habitual de esa franja.
   - **Precio oferta** — el precio especial (debe ser menor al normal).
   - **Duración** — cuántas horas estará visible la oferta (1h, 2h, 3h, 6h o 12h).
4. Toca **Publicar oferta relámpago**.

La oferta aparece de inmediato en la sección "Ofertas Relámpago ⚡" del inicio de la app para todos los deportistas.

### Cómo ve la oferta el deportista

- En la pantalla de inicio verá una card con tu escenario, el horario, el precio tachado, el precio de oferta y el tiempo restante.
- Al entrar a reservar tu escenario, el slot con oferta activa aparece con fondo dorado y el ícono ⚡ en la esquina.
- Al confirmar la reserva, se muestra un banner "⚡ Oferta Relámpago aplicada" con el ahorro en pesos.

### Cancelar una oferta

Desde la lista de ofertas del escenario, toca **Cancelar oferta** en cualquier oferta activa.

### Estados de una oferta

| Estado | Significado |
|---|---|
| ⚡ **Activa** | Visible para los deportistas, aún dentro del tiempo de validez |
| ✅ **Reclamada** | Un deportista reservó el horario de la oferta |
| ⏱ **Vencida** | El tiempo de validez expiró sin que nadie reservara |
| ❌ **Cancelada** | Fue cancelada manualmente por el administrador |

---

## 6. Configuración del negocio

1. Toca **Config** en la barra inferior.

### Información del negocio

Actualiza los datos legales de tu negocio:
- **Nombre del negocio**.
- **NIT** (si aplica).
- **Dirección del negocio**.

Toca **Guardar**.

### Métodos de pago aceptados

Indica qué formas de pago recibes. Esta información es visible para los deportistas:
- Efectivo
- Nequi
- Daviplata
- Transferencia bancaria
- Tarjeta de crédito/débito

Activa o desactiva cada método con el interruptor.

### Página pública del negocio

Agrega los canales donde los usuarios pueden encontrar más información:
- **Sitio web** — URL de tu página.
- **Instagram** — usuario de Instagram (ej: `@canchaelcampeon`).

### Notificaciones de administrador

Configura qué notificaciones deseas recibir:
- Nuevas reservas recibidas.
- Cancelaciones de reservas.
- Nuevas reseñas.

---

## 7. Perfil de administrador

1. Toca **Perfil** en la barra inferior.

### Editar foto de perfil

1. Toca la foto de perfil.
2. Selecciona una imagen de tu galería.
3. La foto se actualiza automáticamente.

### Editar información personal

1. Toca el ícono ✏️ junto a tus datos personales.
2. Modifica **nombre** y **teléfono**.
3. Toca **Guardar**.

### Cambiar contraseña

1. Toca **Cambiar contraseña**.
2. Ingresa tu contraseña actual y la nueva.
3. Toca **Confirmar**.

### Cerrar sesión

Toca **Cerrar sesión** al final del perfil.

---

## 8. Notificaciones

Toca el 🔔 en la pantalla principal para ver todas las notificaciones.

### Notificaciones que recibirás

| Notificación | Cuándo llega |
|---|---|
| 📅 Nueva reserva | Un deportista solicita reservar tu escenario |
| ❌ Cancelación | Un deportista cancela su reserva |
| ✏️ Modificación | Una reserva fue modificada |

### Acciones

- Toca una notificación para ir directamente a la reserva relacionada.
- Toca **Marcar todas como leídas** para limpiar el badge.

---

## Buenas prácticas

✅ **Responde rápido** — confirma o rechaza las reservas dentro de las 2 horas siguientes para dar una buena experiencia al deportista.

✅ **Mantén actualizado el calendario** — si un día tu escenario no está disponible, edita los horarios o cancela las reservas con anticipación.

✅ **Fotos de calidad** — escenarios con buenas fotos generan más reservas. Sube imágenes con buena iluminación desde diferentes ángulos.

✅ **Precios claros** — configura franjas de precio detalladas para evitar malentendidos con los deportistas.

✅ **Responde reseñas** — las valoraciones positivas mejoran tu posición en los resultados de búsqueda.

---

*Para soporte o verificación de cuenta escribe a: oscardavidloradesales@gmail.com*

# SegurApp

**SegurApp** es una aplicación diseñada para facilitar el registro de entradas y salidas en colonias residenciales. Su objetivo es mejorar el control y la organización del acceso a visitantes, personal autorizado y residentes, de manera clara, rápida y segura.

---

## Características principales

- Registro de visitantes con nombre, cédula, vehículo, color, modelo y placa.
- Hora de entrada y salida automática (editable en caso de error).
- Acceso separado para:
  - **Soporte Técnico** (control total de la app y respaldo de datos)
  - **Seguridad** (registro de entradas/salidas, gestión de propietarios)
  - **Propietarios** (autorización de visitas solamente)
- Sección de **notas internas** (eventos como cortes de agua, electricidad, etc.).
- **Funciona en celular, tablet y computadora**.
- Cada colonia tiene sus propios datos (no se mezclan con otras).

---

## Tecnología utilizada

- Glide (para versión prototipo funcional sin código)
- React + Firebase (versión web avanzada)
- Google Drive / Firestore (para respaldos y sincronización en la nube)
- Diseño responsivo adaptado a móviles

---

## Estructura de la app

1. **Pantalla de inicio con logo y acceso**
2. **Pantalla de login** por tipo de usuario (Soporte Técnico, Seguridad, Propietario)
3. **Dashboard del personal de seguridad** con:
   - Registro de entradas/salidas
   - Lista de visitantes autorizados
   - Acceso a propietarios y notas
4. **Panel del propietario**:
   - Visualización de su nombre y casa
   - Botón para autorizar visitantes (nombre, cédula, vehículo)
5. **Sección de notas** visibles solo para personal de seguridad
6. **Base de datos segmentada por colonia**

---

## Próximas funciones (opcional)

- Alertas para visitas recurrentes no autorizadas
- Reportes descargables (PDF o Excel)
- Historial por propietario
- Avisos internos automáticos

---

## Cómo usar

1. Inicia sesión con tu rol.
2. Si eres seguridad, registra visitantes al entrar y salir.
3. Si eres propietario, autoriza visitas desde tu perfil.
4. Usa la sección de notas para registrar cualquier situación importante.

---

## Créditos

Desarrollado por **Nixon Z.**, como solución práctica para mejorar el control de acceso en colonias privadas.

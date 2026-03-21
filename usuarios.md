# Gestión de Usuarios en Windows 11

Este documento describe la creación, configuración y administración de usuarios en el sistema operativo Windows 11, tal como se ha aplicado en el Proyecto Intermodular.

---

## 1. Tipos de usuarios creados

### ✔ Administrador
Usuario con permisos completos para instalar software, modificar configuraciones y administrar el sistema.

### ✔ Usuario estándar
Usuarios destinados a los empleados de la empresa.  
Tienen permisos limitados para evitar cambios críticos en el sistema.

---

## 2. Creación de un usuario estándar

1. Abrir **Configuración** desde el menú Inicio.
2. Ir a **Cuentas**.
3. Seleccionar **Familia y otros usuarios**.
4. Clic en **Agregar otra persona a este equipo**.
5. Elegir **No tengo la información de inicio de sesión de esta persona**.
6. Seleccionar **Agregar un usuario sin cuenta Microsoft**.
7. Introducir:
   - Nombre de usuario (ej.: empleado01)
   - Contraseña segura
8. Crear el usuario.

---

## 3. Cambiar tipo de cuenta

1. En **Familia y otros usuarios**, seleccionar el usuario creado.
2. Clic en **Cambiar tipo de cuenta**.
3. Elegir:
   - **Administrador** (solo si es necesario)
   - **Usuario estándar** (recomendado para empleados)

---

## 4. Gestión de contraseñas

### Cambiar contraseña (usuario)
- Pulsar **Ctrl + Alt + Supr**  
- Seleccionar **Cambiar una contraseña**

### Cambiar contraseña (administrador)
1. Abrir **Panel de control**.
2. Ir a **Herramientas administrativas**.
3. Abrir **Administración de equipos**.
4. Ir a **Usuarios y grupos locales → Usuarios**.
5. Clic derecho en el usuario → **Establecer contraseña**.

---

## 5. Permisos básicos

- Los usuarios estándar no pueden instalar software.
- No pueden modificar configuraciones del sistema.
- No pueden acceder a carpetas de otros usuarios.
- El administrador puede cambiar permisos desde:
  - **Propiedades de carpeta → Seguridad**

---

## 6. Conclusión

La gestión de usuarios en Windows 11 permite mantener un entorno seguro y controlado, evitando que los empleados realicen cambios no autorizados y garantizando la estabilidad del sistema.

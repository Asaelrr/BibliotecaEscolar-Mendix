# Biblioteca Escolar

Aplicación web desarrollada en Mendix Studio Pro 11.16.1 para la actividad de Metodologías Ágiles.

## Funcionalidades

- Inicio de sesión nativo de Mendix.
- Consulta, registro, edición y eliminación de libros.
- Gestión de lectores con nombre, matrícula y correo.
- Registro de préstamos con libro, lector, fecha de préstamo, fecha límite y estado de devolución.

## Modelo de datos

- **Libro:** título, autor, ISBN y categoría.
- **Lector:** nombre, matrícula y correo.
- **Prestamo:** fechas y estado de devolución; asociado con un libro y un lector.

Las fichas de lectores y las cuentas de acceso son registros distintos. Las cuentas se gestionan mediante la seguridad de Mendix.

## Ejecución local

1. Clonar o descargar este repositorio conservando su estructura de carpetas.
2. Abrir `BibliotecaEscolar.mpr` con Mendix Studio Pro 11.16.1.
3. Ejecutar la aplicación mediante **Run Locally** y abrir **View App**.
4. Iniciar sesión con una cuenta configurada en la aplicación. La cuenta `MxAdmin` utiliza la contraseña definida en **App > Security > Administrator**. Las cuentas de demostración tienen contraseñas generadas que se pueden copiar desde **App > Security > Demo users**.

La configuración de seguridad utilizada para la práctica es **Prototype/demo**.

## Ramas

- `main`: versión inicial de la biblioteca con login y gestión de información.
- `mejora-biblioteca`: rama creada a partir de `main`; agrega esta documentación como un cambio independiente.

## Evidencias de la práctica

Durante la prueba local se inició sesión, se registró el libro **Padre Rico Padre Pobre** y se creó un préstamo asociado con un lector. Las capturas de estas operaciones se incluyen en el reporte de la actividad.

🚀 Resumen del Proyecto Realizado

En este proyecto se desarrolló una solución para optimizar la gestión de atención en una sucursal bancaria, completando la implementación de la clase principal SucursalBancaria (la cual implementa la interfaz SistemaBancario).

💡 Decisiones de Diseño y TDAs Implementados

    Selección de TDAs: Se analizaron y seleccionaron los Tipos de Datos Abstractos (TDAs) más adecuados para gestionar eficientemente las colas de espera por trámite, la relación entre puestos y trámites, y el historial de llamados de la pantalla.

    Limpieza de TDAs: Se removieron del proyecto todos aquellos TDAs provistos por la cátedra que no fueron utilizados en la solución final, garantizando un repositorio limpio y optimizado.

⚙️ Funcionalidades Desarrolladas (SucursalBancaria)

    Gestión de Puestos y Trámites:

        Implementación de la asociación y desasociación de trámites a puestos específicos.

        Consultas sobre los trámites asociados a un puesto y la cantidad de puestos que atienden un determinado trámite.

    Ingreso de Personas y Asignación de Turnos:

        Modelado de la llegada de clientes y no clientes, aplicando las restricciones correspondientes a los servicios disponibles para cada tipo de persona.

        Generación automática de turnos con numeración secuencial independiente por cada tipo de trámite (ej. C-1, A-1).

        Cálculo y consulta del tiempo de espera estimado.

    Atención y Visualización:

        Implementación del mecanismo de llamado del próximo turno desde los puestos de atención, priorizando el orden de llegada (FIFO) entre los trámites que el puesto atiende.

        Soporte de datos para la pantalla de visualización, registrando y mostrando los últimos 4 llamados realizados (indicando turno y puesto).

✅ Verificación y Calidad

    Testing: Se superaron exitosamente todas las pruebas unitarias automatizadas provistas en SucursalBancariaTest mediante JUnit.

    Integración Continua: Se aseguró la correcta compilación del proyecto y la eliminación de todos los comentarios TODO pendientes, realizando el envío final (push) al repositorio remoto de GitHub Classroom.

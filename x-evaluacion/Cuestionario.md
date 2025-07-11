# Tutorial de Desarrollo de Odoo 16.0

### Evaluacion Capacitacion Odoo 16.0
### Tiempo de presentacion: Hasta las 23:59 del 11/07/2025
### Crear fork y trabajar en ellos la pregunta nro 2

1. Seleccione una de las siguientes afirmaciones y explique la razon de su respuesta.
   - a) Puedo heredar campos de una clase abstracta para construir un modelo persistente
   - b) Puedo heredar campos de un modelo persistente para construir una clase abstracta.
   - c) No puedo realizar ninguna de las anteriores

    Resp.-a) Puedo heredar campos de una clase abstracta para construir un modelo persistente.

    ¿Por qué?
    Porque en Odoo, las clases abstractas son como "plantillas" de código: no crean una tabla en la base de datos, pero sí pueden tener campos y funciones que luego puedes usar en modelos reales (persistentes).

    Esto se hace mucho cuando tienes varios modelos que comparten campos similares y no quieres repetir todo el código. Entonces creas una clase abstracta con esos campos y la heredas desde tus modelos persistentes.

2. Cree los campos necesarios para realizar el requerimiento de un cliente X
    - El cliente requiere que los clientes en el formulario de contactos se puedan agrupar por un contacto padre (cliente padre)
    - Cada cliente padre tendra clientes hijos con su propio codigo correlativo ej.
      - CCP01000    (Cliente padre)
        - CCP01001  (Cliente hijo nro 1)
        - CCP01002  (Cliente hijo nro 2)
      - CCP02000    (Cliente padre 2)
    - Adicionar el nuevo campo en las vistas treeview y formview
    - Un cliente padre no puede tener como hijo a otro cliente padre
    - utilizar nomenclatura segun utilizada en el curso y traducir los campos 
    - Asignar/modificar masivamente clientes padres a clientes hijos (cree la tarea de forma que se puedan replicar en otras bases)
    
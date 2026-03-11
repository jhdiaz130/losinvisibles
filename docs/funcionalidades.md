# Funcionalidades

La siguientes es una lista de las funcionalidades disponibles para el usuario de la aplicación:

FUNCIONALIDADES DE LA APLICACION

Funcionalidades Base:

## 1. Registro de ingresos y gastos

Agregar ingreso (monto, descripción, fecha).

Agregar gasto (monto, categoría, descripción, fecha).

Botón flotante (FAB) para agregar movimientos.

Guardar en Firebase Firestore.

## 2. Categorías básicas

Categorías predefinidas:

Arriendo

Comida

Transporte

Entretenimiento

Servicios

(Puedes usar un Spinner o Dropdown)

## 3.  Pantalla principal (Dashboard)

Mostrar:

Total ingresos del mes

Total gastos del mes

Balance actual (ingresos - gastos)

Esto se puede hacer con consultas simples a Firebase.

## 4. Lista de movimientos

RecyclerView

Mostrar si es ingreso o gasto

Ordenados por fecha

Opción de eliminar

Funcionalidades Intermedias (Aumenta nivel del proyecto)

Estas ya hacen que tu proyecto se vea MUCHO más profesional:

## 5.  Presupuesto mensual por categoría
  
El usuario puede decir:

"Para comida tengo máximo $400.000"

La app:

Lleva el acumulado.

Muestra barra de progreso.

Cambia a rojo cuando supera el límite.

Muestra alerta tipo Toast o Dialog.

## 6.  Gráficas

Puedes usar:

MPAndroidChart

Gráficas recomendadas:

Barras -> Gastos por categoría

Pastel -> Distribución de gastos

Esto hace que tu proyecto suba muchísimo de nivel visual.

## 7.  Filtro por fechas

Ver solo este mes

Ver semana actual

Ver por rango personalizado

 Muy útil y no tan complejo.

## 8. Sistema de autenticación

Con Firebase Authentication:

Registro

Login

Cada usuario ve solo sus datos

Esto lo vuelve más real.

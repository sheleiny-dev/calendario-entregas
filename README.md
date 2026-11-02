# Calendario de entregas para artes gráficas

Aplicación web para organizar las órdenes de una empresa de artes gráficas y cumplir las fechas de entrega.

## ¿Qué hace?

- Registra órdenes con fecha de inicio y fecha de entrega.
- Divide cada orden en etapas (diseño, impresión, corte, cosido, empaque...) y pide cuántos días tarda cada una.
- Calcula automáticamente las fechas de cada etapa a partir de la fecha de inicio.
- Avisa si el plan no alcanza para la fecha de entrega ("En riesgo") o si la orden ya está atrasada.
- Permite marcar las etapas como terminadas.
- Muestra un calendario mensual con las etapas y las entregas.

## Cómo usarla

Abre el archivo `index.html` en el navegador. No necesita instalar nada.
Los datos se guardan en el navegador (`localStorage`).

## Próximos pasos

- [ ] Acceso por código personal (quién ingresa órdenes y quién solo consulta)
- [ ] Códigos especiales temporales para delegar el cierre de etapas
- [ ] Base de datos para compartir la información entre varias personas
- [ ] Ponerle nombre al proyecto

## Tecnologías

HTML, CSS y JavaScript.

## Autora

Sheleiny Gonzalez Valencia — Tecnólogo en Análisis y Desarrollo de Software, SENA.

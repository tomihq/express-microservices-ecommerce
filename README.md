# Objetivo
Los microservicios son un tema bastante importante en los backend grandes. Más que nada para poder optimizar la carga de cada funcionalidad cuando una aplicación es demasiado grande.
El enfoque y objetivo de esto, es hacer un backend simple que contenga: auth, payment y orders, cada uno levantado en un docker distinto y se conecten a través de una network.

Luego, implementar un proxy reverso para ellos tres y redireccionar a un servicio u otro según lo que desee el usuario.

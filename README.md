# PracticaVueJS
Práctica del módulo 5 de LAUNCHX , el tema : VueJS(PASTELERIA)



En esta práctica ponemos en práctica los conocimientos adquiridos de vUEJS en el curso de LAUNCHX. La práctica consiste en crear una página para una pastelería. Se crea una página usando Vuejs la cual tiene varias vistas, las vistas a su vez se crean a partir de componentes. Se pueden pasar datos entre la vista de los clientes y la vista del pastelero por medio de la store con Vuex.

Link de los requerimientos de la pagina ---->>>[LINK](https://github.com/LaunchX-InnovaccionVirtual/FrontEnd-Mision/tree/main/05%20-%20VUEJS/practica)

Link del código desarrollado en VUEJS---->>>[LINK](https://github.com/RobertoPeredo/CodigoPracticaVueJS)

Link de la página desplegada en Github pages --->>> [LINK](https://robertoperedo.github.io/despliegue-Vue-practice/#/)

Capturas de pantalla del funcionamiento del sitio, se muestra la navegación por las distintas vistas del sitio, así como también se observa que el sitio es responsivo

1. Página principal de la pastelería.
![FireShot Capture 002 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160930743-a7545a72-f8c8-4c85-bb82-c1f94baaf850.png)
1.1 Página principal de la pasteleria para dispositivos pequeños. (Se observa como el navbar se contrae)
![FireShot Capture 003 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160930860-718db0bb-3494-4a08-93f6-56f85b325374.png)
2. Vista 'Pasteles' del sitio. En esta página se da a conocer a los clientes los sabores que se manejan en la pasteleria.
![FireShot Capture 004 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160931044-cb9a27d3-b2a6-484b-8a18-f6903088b916.png)
2.1 De igual forma la vista pasteles se muestra en dispositivos pequeños.
![FireShot Capture 005 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160931152-4cc8006e-8970-48c9-b6e9-06f11b777c85.png)
3. Vista 'Realiza tu pedido' del sitio. En esta los clientes pueden realizar su pedido por medio de un formulario, el cual cuenta con validación de datos. Al no llenar cualquiera de los datos aparece una leyenda que pide al usuario llenar el campo y por consiguiente no permite avanzar de pagina
![FireShot Capture 007 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160931482-43657c9b-a40d-4c92-b4e4-26ef9d6ca522.png)
3.1 Vista para dispositivos pequeños, con todos los campos llenados. Las leyendas de 'favor de llenar los campos' son retiradas.
![FireShot Capture 015 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160931616-24e1dd4e-926c-4aec-a002-9931c8f25927.png)
4. Una vez llenado correctamente el formulario se despliega la siguiente vista que es 'Revisar pedido'. En esta vista el usuario puede validar que los datos ingresados hayan sido los correctos, de no ser así puede presionar el botón 'regresar' para volver a la página anterior y modificar cualquier cambio. En caso de que la información esté correcta deberá presionar 'Realizar pedido' el cual lo llevo a la siguiente vista
![FireShot Capture 014 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160931945-82f912ff-597b-4478-a14f-a68b3a00f57e.png)
5. Vista 'PedidoRealizado', esta vista simplemente le indica al usuario que su pedido fue tomado correctamente
![FireShot Capture 016 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160932050-ff37755d-7eae-4911-89d4-57e8699e6ab5.png)
6. Por último la vista 'Inventario' que, en este caso, sería una vista única del pastelero. En esta vista se van registrando todos los pedidos que el usuario vaya haciendo en la vista 'Realiza tu pedido' , también cuenta con un inventario el cual muestra una etiqueta de color rojo cuando el stock es menor a 3. Así mismo se puede ir modificando el stock para cada elemento de forma manual
![FireShot Capture 017 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160933034-f7539eba-027f-47a6-a782-94e677c6ff09.png)
6.1 Vista del inventario para dispositivos pequeños
![FireShot Capture 018 - pasteleria-vue - localhost](https://user-images.githubusercontent.com/99369122/160933064-4b21189f-91d3-478c-b829-0ce086651be2.png)


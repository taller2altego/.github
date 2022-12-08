---
layout: post
title:  "Fiuber App - user guide"
date:   2022-12-07 22:55:57 -0300
categories: jekyll update
---

Para usar la aplicacion, descargar la ultima release desde el [repo](https://github.com/taller2altego/mobileApp).

## Initial Window

Para utilizar la aplicacion, es necesario logearse, o registrarse.

![Landing](/images/landing.png)

## Sign Up

Es necesario completar los siguientes campos para registrarse.

![Sign Up](/images/sign_up.png)

## Log In

Con respecto al Log In, brindamos la posibilidad de conectarse con Google, o si ya se ha creado un usuario previamente, conectarse con sus credenciales.

![Login](/images/login.png)

## Recover Password

Si un usuario se ha olvidado su contraseña, es posible recuperarla a seleccionando la opcion Forgot Password. Se le solicitara al usuario que ingrese su mail, y en caso de coincidir con una cuenta ya existente, se le enviara un Token al usuario.

![Recover Password](/images/send_mail.png)

## Auth Token to Recover Password

Si un usuario posee un Token habilitado para recuperar contraseña, puede ingresarlo en la seccion Have a Token. Luego, se le solicitara que ingrese una nueva contraseña para su cuenta.  

![Auth Token](/images/auth_token.png)

## Reset Password

Luego de validar el Token, el usuario podra ingresar una nueva contraseña para su cuenta.

![Reset Password](/images/reset_password.png)

# Default Location

Una vez registrado es necesario ingresar una direccion predeterminada para el usuario.

![Default Location](/images/default_location.png)


## Home Tab

Una vez que se inicia sesion en la aplicacion, es posible iniciar un viaje o visualizar nuestro perfil. Cada viaje realizado se puede visualizar en esta pestaña. Podemos seleccionar un viaje, y acceder al detalle. 

![Home](/images/home_tab.png)

## Trip Details

En esta seccion es posible puntuar al chofer, y en caso de ser necesario, generar una denuncia contra el mismo. Si estas registrado como conductor, aca tambien podes iniciar tu trabajo, buscando un viaje.

![Trip Details](/images/puntuation_travel.png)

## Report Driver

Contanos tu experiencia, y denuncia al conductor del viaje.

![Report Driver](/images/report_driver.png)

## Profile Visualization

Seleccionando la opcion del perfil, podemos ver y editar nuestros datos. Tambien, podes registrarte como conductor, y trabajar junto a nosotros.

![Profile](/images/profile.png)

## Register as Driver

En caso de querer registrarte como conductor, en esta seccion podremos ingresar nuestros datos.

![Register as Driver](/images/register_driver.png)

## Flujo de un viaje

### Initialization of Travel

Una vez confirmados el origen y destino del viaje, se puede visualizar el tiempo aproximado del viaje, el precio estimado en Ethereum, la distancia a recorrer, y una opcion para elegir si pagar con FIUCreditos, o con Ethereum.

![Confirm Travel](/images/confirm_travel.png)

### Driver Searching

Una vez iniciado el viaje, y confirmada la informacion del mismo, como usuario debera esperar a que un chofer disponible acepte realizar el viaje.

![Searching Driver](/images/searching_driver.png)

### Driver Incoming

Una vez que un chofer acepte el viaje, podremos visualizar en el mapa su posicion, mientras arriba a nuestro origen. Ademas, podremos visualizar el perfil del chofer, y cancelar el viaje.

![Waiting Driver](/images/waiting_driver.png)

### Travel in Progress

Una vez que el chofer llega al origen del viaje, podremos visualizar en el mapa nuestro viaje. A partir de este punto ya no se puede cancelar el viaje.

![Travel in Progress](/images/user_travel_in_progress.png)

### Finish Travel

Al finalizar el viaje, podras volver a la pestaña de inicio.

![Finish Travel](/images/finish_travel.png)

### Conductor

Una vez iniciada la busqueda, se busca un viaje, miestras tanto usted ve la siguiente pantalla.

![Driver Searching Travel](/images/driver_searching_travel.png)

Cuando se encuentra un viaje, se muestra el mapa donde se ve la posicion del origen, donde esta el pasajero y tambien se puede visualizar el perfil del usuario asi como cancelar el viaje. 

VISTA: Waiting driver

Una vez se llega al origen del viaje, la app se ve de la siguiente manera y se puede iniciar el viaje a destino. Una vez iniciado el viaje ya no se puede cancelar.

VISTA: Travel in progress driver

Al finalizar el viaje deberas puntuar el pasajero y podras dejar un comentario.

VISTA: La del viaje terminado para puntuar del driver


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

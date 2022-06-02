Queremos graficar las temperaturas de un termómetro :thermometer: utilizando colores que las representen mediante un código HTML que debe tener:

- una lista desordenada con 11 ítems;
- la lista debe ir de `Temperatura: 0°C` a `Temperatura: 50°C` aumentando de a 5°C;
- poner las temperaturas extremas (0°C y 50°C) en negrita;
- dar a cada temperatura un color distinto, cambiando gradualmente, siendo que:

* para 0°C deberá ser el color `#0000FF` <span> 0°C </span> <span><div class= 'cuadrado'> </div></span>
* para 5°C deberá ser el color `#009AFF` <span style= "color: #009AFF"> 5°C </span>
* para 10°C deberá ser el color `#00CDFF` <span style= "color: #00CDFF"> 10°C </span>
* para 15°C deberá ser el color `#A0E6FE` <span style= "color: #A0E6FE"> 15°C </span>
* para 20°C deberá ser el color `#D0F7FC` <span style= "color: #D0F7FC"> 20°C </span>
* para 25°C deberá ser el color `#FDFEE6` <span style= "color: #FDFEE6"> 25°C </span>
* para 30°C deberá ser el color `#FFFF67` <span style= "color: #FFFF67"> 30°C </span>
* para 35°C deberá ser el color `#FFCA00` <span style= "color: #FFCA00"> 35°C </span>
* para 40°C deberá ser el color `#FE9935` <span style= "color: #FE9935"> 40°C </span>
* para 45°C deberá ser el color `#FF561A` <span style= "color: #FF561A"> 45°C  </span>
* para 50°C deberá ser el color `#FF0000` <span style= "color: #FF0000"> 50°C </span>


[En esta página](https://cdn.shopify.com/s/files/1/2303/2711/files/colour_temperature_kelvin_chart_make_up.jpg?v=1513856014) podés ver un ejemplo.

> Creá el código HTML que acabamos de describir.

<style>
.cuadrado{
  width: 50px;
  height: 10px;
  border-radius: 5px;
  background: #0000FF;
  display: inline-block;

}
</style>
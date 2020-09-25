# Slideshow
Slideshow personalizado usando Provider para comunicar el estado del Pageview

<p>
    <img src="https://res.cloudinary.com/dzgd10ssq/image/upload/v1599273495/Apps/h8g7bujx2czwsdneoiyh.gif" width="200"/ hspace="5"> 
</p>

# Comenzando 🚀

Estas instrucciones te permitirán obtener una copia de la aplicacion para propósitos de desarrollo y pruebas.

## Pre-requisitos 📋

Que plugins necesitas para el funcionamiento de la aplicacion
- [flutter_svg](https://pub.dev/packages/flutter_svg#-installing-tab- "flutter_svg")
- [Provider](https://pub.dev/packages/provider "Provider")

Las imagenes que se utilizan en esta aplicacion se pueden encontrar en [unDraw](https://undraw.co/ "unDraw").

Para personalizar el widget, se le envía los siguientes parámetros:

```
Slideshow(
      colorPrimario: Colors.blue,
      colorSecundario: Colors.grey,
      bulletPrimario: 15.0,
      bulletSecundario: 12.0,
      puntosArriba: false,
      slides: [
        SvgPicture.asset('assets/svgs/slide-1.svg'),
        SvgPicture.asset('assets/svgs/slide-2.svg'),
        SvgPicture.asset('assets/svgs/slide-3.svg'),
        SvgPicture.asset('assets/svgs/slide-4.svg'),
        SvgPicture.asset('assets/svgs/slide-5.svg'),
      ],
    );
  ```
  
  # Construido con 🛠️
  - [Flutter](https://flutter.dev/ "flutter")
  - [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")
  - [unDraw](https://undraw.co/ "unDraw")

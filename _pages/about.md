---
title: "Camino"
layout: default
---

# Nuestro camino

A continuación se listan algunos de los eventos en los que La Olla ha participado. Esto comprende eventos que el colectivo ha ideado e implementado, y aquellos en los que ha sido puente para visibilizar causas compartidas. La lista está en construcción.

## 1. Velatón en la Sinagoga Platz.

<div style="display: flex; align-items: center; max-width: 2000px; margin: auto;">
  <!-- Image Carousel -->
  <div style="position: relative; width: 100%; text-align: center;">
    <!-- Left Arrow -->
    <button onclick="prevImage()" 
            style="position: absolute; top: 50%; left: -40px; transform: translateY(-50%); background: none; border: none; cursor: pointer; font-size: 24px;">
      ◀
    </button>

    <img id="carousel-image" src="{{ site.baseurl }}/assets/images/velaton_06052021.JPG" 
        alt="Evento 1" style="width: 100%; height: auto; display: block; max-width: 1200px; object-fit: contain;">

    <!-- Right Arrow -->
    <button onclick="nextImage()" 
            style="position: absolute; top: 50%; right: -40px; transform: translateY(-50%); background: none; border: none; cursor: pointer; font-size: 24px;">
      ▶
    </button>
  </div>
</div>

  <div style="line-height: 1.1; text-align: justify; margin: 0;">
    
    <!-- Description -->
  <p> <strong>Descripción:</strong> Concentración convocada por la comunidad Colombiana en Freiburg en apoyo a las manifestaciones de 2019 en Colombia ante las profundas desigualdades sociales, agudizadas en el 2021 en el periodo pos-COVID. La concentración surgió principalmente como rechazo a la violencia ejercida por parte de la policía en contra de manifestantes, exacerbada el 28.04.2021 con varios asesinatos de marchantes y decenas de heridos. Esto marcó el inicio del denominado Paro Nacional de 2021 que duraría varios meses y contaría con diversas expresiones artísticas y culturales en Colombia con un gran impacto sociopolítico. La sorprendente participación de la velatón en Freiburg marca el inicio del colectivo <strong>La Olla</strong> como refugío e insumo de un activismo socioambiental y político en Colombia desde Alemania, asi como la busqueda de puentes que beneficien a ambas sociadedes.
  </p>
    <p><strong>Fecha:</strong> Mayo 06 de 2021.</p>
    <p><strong>Lugar:</strong> Platz der Alten Synagoge, Freiburg im Breisgau.</p>
  </div>

<!-- JavaScript for Carousel -->
<script>
  var images = [
    "{{ site.baseurl }}/assets/images/velaton_2.JPG",
    "{{ site.baseurl }}/assets/images/velaton_06052021.JPG",
    "{{ site.baseurl }}/assets/images/velaton_3.JPG",
    "{{ site.baseurl }}/assets/images/velaton_4.JPG",
    "{{ site.baseurl }}/assets/images/velaton_5.JPG",
    "{{ site.baseurl }}/assets/images/velaton_6.JPG"
  ];
  var currentIndex = 0;
  var imgElement = document.getElementById("carousel-image");

  function nextImage() {
    currentIndex = (currentIndex + 1) % images.length;
    imgElement.src = images[currentIndex];
  }

  function prevImage() {
    currentIndex = (currentIndex - 1 + images.length) % images.length;
    imgElement.src = images[currentIndex];
  }
</script>


## 2. Círculo de lectura "Thursdays for Freire". Pensar para la Paz. Educación para el compromiso social.

## 3 Retratos de Resistencia.

## 4. 8M - 2022.

## 5. Bici-bles.

## 6. Encuentro de diásporas - Nurenberg.

## 7. El rio que se robaron.

## 8. Observando con el corazón del mundo.

## 9. Las mujeres Paramunas.

## 10. Hilando altares de la memoria y la verdad.

## 11. Mujeres y minería de carbón en Cesar, Colombia.





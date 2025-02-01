---
title: "Camino"
layout: default
---

## 1. Velatón en la Sinagoga Platz.

<div style="display: flex; align-items: center; max-width: 1200px; margin: auto;">
  <!-- Image Carousel -->
  <div style="position: relative; width: 2000px; margin-right: 20px;">
    <img id="carousel-image" src="{{ site.baseurl }}/assets/images/velaton_06052021.JPG" 
        alt="Evento 1" style="width: 200px; display: block;">
    
    <!-- Left Arrow -->
    <button onclick="prevImage()" 
            style="position: absolute; top: 50%; left: -20px; transform: translateY(-50%); background: none; border: none; cursor: pointer;">
      ◀
    </button>
    
    <!-- Right Arrow -->
    <button onclick="nextImage()" 
            style="position: absolute; top: 50%; right: -20px; transform: translateY(-50%); background: none; border: none; cursor: pointer;">
      ▶
    </button>
  </div>

  <!-- Description -->
  <div style="line-height: 1.1; text-align: justify; margin: 0;">
    <p><strong>Fecha:</strong> Mayo 06 de 2021.</p>
    <p><strong>Lugar:</strong> Platz der Alten Synagoge, Freiburg im Breisgau.</p>
    <p><strong>Descripción:</strong> Concentración convocada por la comunidad Colombiana en apoyo a las manifestaciones realizadas en Colombia ante las profundas desigualdades sociales. Principalmente rechazo a la violencia ejercida por parte de la policía en contra de manifestantes exacerbada el 28.04.2021, con varios asesinatos y decenas de heridos. Esto marcó el inicio del denominado Paro Nacional de 2021, que duraría varios meses y contaría con diversas expresiones artísticas y culturales en Colombia con un gran impacto sociopolítico. A su vez, marca el inicio del colectivo <strong>La Olla</strong> en Freiburg, Alemania.
    </p>
  </div>
</div>

<!-- JavaScript for Carousel -->
<script>
  var images = [
    "{{ site.baseurl }}/assets/images/velaton_06052021.JPG",
    "{{ site.baseurl }}/assets/images/velaton_2.JPG",
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

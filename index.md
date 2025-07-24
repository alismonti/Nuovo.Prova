---
title: Home
layout: default
---

<nav style="
background-color: grey;
padding: 12px 20px;
border-radius: 6px;
font-family: Arial, sans-serif;
box-shadow: 0 2px 5px rgba(0,0,0,0.15);
display: inline-flex;
gap: 10px;
align-items: center;
">
<a href="{{ site.baseurl }}/" style="
color: #ddd;
text-decoration: none;
font-weight: 600;
transition: color 0.3s ease;
" onmouseover="this.style.color='#f0a500'" onmouseout="this.style.color='#ddd'">Home</a>

<span style="color: #888;">|</span>

<a href="{{ site.baseurl }}/italiano/" style="
color: #ddd;
text-decoration: none;
font-weight: 600;
transition: color 0.3s ease;
" onmouseover="this.style.color='#f0a500'" onmouseout="this.style.color='#ddd'">Italiano 🇮🇹</a>

<span style="color: #888;">|</span>

<a href="{{ site.baseurl }}/deutsch/" style="
color: #ddd;
text-decoration: none;
font-weight: 600;
transition: color 0.3s ease;
" onmouseover="this.style.color='#f0a500'" onmouseout="this.style.color='#ddd'">Deutsch 🇩🇪</a>
</nav>

<div style="
  display: grid; 
  grid-template-columns: 180px 180px; 
  grid-template-rows: 180px 180px; 
  gap: 30px; 
  justify-content: center;
  align-items: center;
  margin-bottom: 50px;
  transform: rotate(45deg);
  width: 420px;
  margin-left: auto;
  margin-right: auto;
">
  <img src="{{ site.baseurl }}/assets/images/libro.jpg" alt="img1" style="
    width: 180px; 
    height: 180px; 
    object-fit: cover; 
    border-radius: 18px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.25);
    transform: rotate(-45deg);
  ">
  <img src="{{ site.baseurl }}/assets/images/mani.jpg" alt="img2" style="
    width: 180px; 
    height: 180px; 
    object-fit: cover; 
    border-radius: 18px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.25);
    transform: rotate(-45deg);
  ">
  <img src="{{ site.baseurl }}/assets/images/quaderno.jpg" alt="img3" style="
    width: 180px; 
    height: 180px; 
    object-fit: cover; 
    border-radius: 18px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.25);
    transform: rotate(-45deg);
  ">
  <img src="{{ site.baseurl }}/assets/images/biglietto.jpg" alt="img4" style="
    width: 180px; 
    height: 180px; 
    object-fit: cover; 
    border-radius: 18px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.25);
    transform: rotate(-45deg);
  ">
</div>

<div style="background: lightblue; padding: 0px;">
<table style="
  width: 100%; 
  border-collapse: separate; 
  border-spacing: 0 8px; /* meno spazio verticale */
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
">
  <tr style="
    background: #f9f9f9; 
    box-shadow: 0 2px 8px rgba(0,0,0,0.1); 
    border-radius: 10px;
  ">
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      width: 60%; 
      border-radius: 10px 0 0 10px;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
    ">
      <p>Unsere Kanzlei wurde im Jahre 2007 gegründet mit dem Ziel, 
         ihre Mandanten sowohl in deutscher als auch in italienischer Sprache vertreten zu können.</p>
    </td>
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      border-radius: 0 10px 10px 0;
      background: #fff;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.03);
    ">
      <p>Il nostro studio è nato nel 2007 per seguire i clienti nella loro lingua madre sia in Italia sia in Germania.</p>
    </td>
  </tr>

  <!-- Nuova riga sotto -->
  <tr style="
    background: #f0f0f0; 
    box-shadow: 0 2px 8px rgba(0,0,0,0.05); 
    border-radius: 10px;
  ">
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      width: 60%; 
      border-radius: 10px 0 0 10px;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
    ">
      <p>Unser Team aus vier Rechtsanwälten und acht Mitarbeitern bietet den Mandanten eine effiziente Bearbeitung deutscher und italienischer Rechtsfragen.</p>
    </td>
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      border-radius: 0 10px 10px 0;
      background: #fff;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.03);
    ">
      <p>Il nostro Team di quattro avvocati e otto collaboratori garantisce una consulenza e assistenza efficiente sia in Italia sia in Germania.</p>
    </td>
  </tr>

  <!-- Nuova riga sotto -->
  <tr style="
    background: #f0f0f0; 
    box-shadow: 0 2px 8px rgba(0,0,0,0.05); 
    border-radius: 10px;
  ">
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      width: 60%; 
      border-radius: 10px 0 0 10px;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
    ">
      <p>Wir legen besonderen Wert auf den persönlichen und schnellen Kontakt und eine konstante Unterrichtung unserer Mandanten.</p>
    </td>
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      border-radius: 0 10px 10px 0;
      background: #fff;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.03);
    ">
      <p>Di particolare importanza per lo studio è il contatto personale, la reperibilità e l'informazione costante del cliente. </p>
    </td>
  </tr>
<!-- Nuova riga sotto -->
  <tr style="
    background: #f0f0f0; 
    box-shadow: 0 2px 8px rgba(0,0,0,0.05); 
    border-radius: 10px;
  ">
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      width: 60%; 
      border-radius: 10px 0 0 10px;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
    ">
      <p>
        <a href="{{ site.baseurl }}/deutsch/" style="
          display: inline-block;
          padding: 12px 25px; 
          background-color: grey; 
          color: white; 
          text-decoration: none; 
          border-radius: 6px;
          font-weight: 600;
          transition: background-color 0.3s ease;
        " onmouseover="this.style.backgroundColor='#FF0000'" onmouseout="this.style.backgroundColor='#808080'">Approfondisci in tedesco</a>
      </p>    
    </td>
    <td style="
      vertical-align: top; 
      padding: 15px 30px; /* padding verticale ridotto */
      border-radius: 0 10px 10px 0;
      background: #fff;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.03);
    ">
      <p>
        <a href="{{ site.baseurl }}/italiano/" style="
          display: inline-block;
          padding: 12px 25px; 
          background-color: grey; 
          color: white; 
          text-decoration: none; 
          border-radius: 6px;
          font-weight: 600;
          transition: background-color 0.3s ease;
        " onmouseover="this.style.backgroundColor='#FF0000'" onmouseout="this.style.backgroundColor='#808080'">Approfondisci in italiano</a>
      </p>    
    </td>
  </tr>
</table>
</div>

<div style="width: 100%; text-align: center;">
  <div style="position: relative; display: inline-block; text-align: center;">
<img src="{{ site.baseurl }}/assets/images/campanile.jpg" alt="immagine" style="display: block; width: 80%; max-width: 800px; height: auto; border-radius: 8px;">
    <a href="{{ site.baseurl }}/italiano/" style="
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-weight: bold;
      font-size: 2rem;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
      text-decoration: none;
      background-color: rgba(220, 53, 69, 0.85);
      padding: 8px 16px;
      border-radius: 6px;
      min-width: 120px;
      text-align: center;
    ">
      Richiesta
    </a>
  </div>
</div>




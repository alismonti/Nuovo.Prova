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


<div>
<table style="
  width: 100%; 
  border-collapse: separate; 
  border-spacing: 0 15px; 
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
">
  <tr style="
    background: #f9f9f9; 
    box-shadow: 0 2px 8px rgba(0,0,0,0.1); 
    border-radius: 10px;
  ">
    <td style="
      vertical-align: top; 
      padding: 25px 30px; 
      width: 60%; 
      border-radius: 10px 0 0 10px;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
    ">
      <p>Unsere Kanzlei wurde im Jahre 2007 gegründet mit dem Ziel, 
         ihre Mandanten sowohl in deutscher als auch in italienischer Sprache vertreten zu können.</p>
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
        " onmouseover="this.style.backgroundColor='#218838'" onmouseout="this.style.backgroundColor='#28a745'">Approfondisci in tedesco</a>
      </p>
    </td>
    <td style="
      vertical-align: top; 
      padding: 25px 30px; 
      border-radius: 0 10px 10px 0;
      background: #fff;
      color: #333;
      font-size: 1rem;
      line-height: 1.5;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.03);
    ">
      <p>Il nostro studio è nato nel 2007 per seguire i clienti nella loro lingua madre sia in Italia sia in Germania.</p>
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
        " onmouseover="this.style.backgroundColor='#218838'" onmouseout="this.style.backgroundColor='#28a745'">Approfondisci in italiano</a>
      </p>
    </td>
  </tr>
</table>
</div>
<div>
<a href="{{ site.baseurl }}/" style="padding: 10px 20px; background-color: #007bff; color: white; text-decoration: none; border-radius: 5px;">Fai una richiesta - Anfrage</a>
</div>


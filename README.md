# Optimization of Laparoscopic Images Using Artificial Intelligence Models

⚠️ SEGUIMOS EN CONSTRUCCIÓN, AGRADECEMOS SU PACIENCIA
---

# 🩺 Abstract

In this proyect we introduce Desmoke-RGAN a conditional GAN that incorporates a red-excess channel to remove smoke from laparoscopic images. By training on a four-channel input map, the network reconstructs smoke-free scenes. In evaluations with both synthetic and real data, it demonstrates significant improvements over state-of-the-art methods, achieving uniform smoke attenuation while preserving anatomical details.

---

## 🎯 Objetive

Develop and validate a deep learning model capable of removing smoke from laparoscopic images, evaluated using both reference-based and non-reference-based metrics to ensure competitiveness with the state of the art, robustness, and reliability in clinical settings.

---
## 🖥️ Database
Our database was validated by 38 surgians, If you want to view the questionnaire, you can access it by scanning the QR code below.

<div align="center">
  <img src="comparacion/sample_edsedi_pair.png" width="500">
</div>

a) Are real laparoscopic images
b) Are syntetic smoke laparoscopic images
c) Are real smoke laparoscopic images

---

## 📊 Qualitative results

---

<h3 align="center">🧪 Modelo 1 – Desmokenet</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmokenet_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>

---
<h3 align="center">🧪 Modelo 2 – Desmoking-colores</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke-colores_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>

----

<h3 align="center">🧪 Modelo 3 – Dehazing model</h3>

<div align="center">
  <img src="comparaciones/comparacion_dcp_dehaze_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>


---

<h3 align="center">🧪 Modelo 4 – Desmoke-Lap</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke-LAP_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>

---
<h3 align="center">🧪 Modelo 5 – Desmoke-RGAN(a)</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke_RGAN_a_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>

----
<h3 align="center">🧪 Modelo 6 – Desmoke-RGAN(b)</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke_RGAN_b_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Entrada</strong></sub></td>
    <td align="center" width="384"><sub><strong>Salida</strong></sub></td>
  </tr>
</table>
----








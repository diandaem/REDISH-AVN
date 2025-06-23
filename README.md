# Optimization of Laparoscopic Images Using Artificial Intelligence Models

⚠️ WE ARE STILL UNDER CONSTRUCTION, WE APPRECIATE YOUR PATIENCE
---

# 🩺 Abstract

In this proyect we introduce Desmoke-RGAN a conditional GAN that incorporates a red-excess channel to remove smoke from laparoscopic images. By training on a four-channel input map, the network reconstructs smoke-free scenes. In evaluations with both synthetic and real data, it demonstrates significant improvements over state-of-the-art methods, achieving uniform smoke attenuation while preserving anatomical details.

---

## 🎯 Objetive

Develop and validate a deep learning model capable of removing smoke from laparoscopic images, evaluated using both reference-based and non-reference-based metrics to ensure competitiveness with the state of the art, robustness, and reliability in clinical settings.

---
## 🖥️ Database

<div align="center">
  <img src="comparaciones/sample_edsedi_pair.png" width="900">
</div>

<div align="center">
(a) Are real laparoscopic images
(b) Are synthetic smoke laparoscopic images
(c) Are real smoke laparoscopic images
</div>

Our sythetic database was validated by 38 surgeons, If you want to view the questionnaire, you can access here: https://docs.google.com/forms/d/e/1FAIpQLSePzA2Y4RCd-25frgxneRq8XsyyNm43KJMPWswdY2zGdqaQRQ/viewform?usp=header

The results of surgeons evaluation were analyzed statistically.



---

## 📊 Qualitative results

---

<h3 align="center">🧪 Modelo 1 – Desmokenet</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmokenet_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>

---
<h3 align="center">🧪 Modelo 2 – Desmoking-colores</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke-colores_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>

----

<h3 align="center">🧪 Modelo 3 – Dehazing model</h3>

<div align="center">
  <img src="comparaciones/comparacion_dcp_dehaze_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>


---

<h3 align="center">🧪 Modelo 4 – Desmoke-Lap</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke-LAP_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>

---
<h3 align="center">🧪 Modelo 5 – Desmoke-RGAN(a)</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke_RGAN_a_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>

----
<h3 align="center">🧪 Modelo 6 – Desmoke-RGAN(b)</h3>

<div align="center">
  <img src="comparaciones/comparacion_desmoke_RGAN_b_192.gif" width="768">
</div>

<table align="center" width="768">
  <tr>
    <td align="center" width="384"><sub><strong>Input</strong></sub></td>
    <td align="center" width="384"><sub><strong>Output</strong></sub></td>
  </tr>
</table>

----








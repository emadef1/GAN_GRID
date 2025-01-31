# GAN_GRID
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/GAN_GRID/tree/main">
    <img src="Figures/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h1 align="center">GAN_GRID</h1>

  <p align="center">
    GAN-GRID: A Novel Adversarial Attack on Smart Grid Stability Prediction
    <br />
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-70879-4_19"><strong>Papaer Available»</strong></a>
    <br />
    <br />
    <a href="https://www.dei.unipd.it/persona/1373bd29c9ef0140e39d53ec9add14d2">Emad Efatinasab</a>
    ·
    <a href="https://www.math.unipd.it/~abrighen/">Alessandro Brighente</a>
    ·
    <a href="https://www.dei.unipd.it/persona/95DDDDA0C518D43822ADC0338BD38073">Mirco Rampazzo</a>
    .
    <a href="?????">Nahal Azadi</a>
    ·
    <a href="https://www.math.unipd.it/~conti/">Mauro Conti</a>
  </p>
</div>

<p align="right"><a href="#top">(back to top)</a></p>
<div id="citation"></div>

## 🗣️ Citation

Please, cite this work when referring to GAN_GRID.

```
@misc{efatinasab2024gangrid,
      title={GAN-GRID: A Novel Generative Attack on Smart Grid Stability Prediction}, 
      author={Emad Efatinasab and Alessandro Brighente and Mirco Rampazzo and Nahal Azadi and Mauro Conti},
      year={2024},
      eprint={2405.12076},
      archivePrefix={arXiv},
      primaryClass={id='cs.CR' full_name='Cryptography and Security' is_active=True alt_name=None in_archive='cs' is_general=False description='Covers all areas of cryptography and security including authentication, public key cryptosytems, proof-carrying code, etc. Roughly includes material in ACM Subject Classes D.4.6 and E.3.'}
}
```
<div id="abstract"></div>

## 🧩 Abstract

>The smart grid represents a pivotal innovation in modernizing the electricity sector, offering an intelligent, digitalized energy network capable of optimizing energy delivery from source to consumer. Central to its operation are goals encompassing grid stability, enhanced power system performance, security, and reduced operational costs. Accurate energy demand prediction is paramount, ensuring optimal energy availability and mitigating costly production or usage errors. Leveraging state-of-the-art machine learning algorithms, including the chosen XGBoost model and a proposed LSTM-based deep learning model, we explore the publicly available smart grid dataset for the stability prediction task. However, the stability of a smart grid is intricately linked to its resilience against cyberattacks. In this study, we propose GAN-GRID a novel adversarial attack targeting the stability prediction system, tailored to real-world constraints. Our findings reveal that an adversary armed solely with the stability model's output, devoid of data or model knowledge, can craft data classified as stable with an Attack Success Rate (ASR) of 0.99. Also by manipulating authentic data and sensor values, the attacker can amplify grid issues, potentially undetected due to a compromised stability prediction system. These results underscore the imperative of fortifying smart grid security mechanisms against adversarial manipulation to uphold system stability and reliability.

<p align="right"><a href="#top">(back to top)</a></p>
<div id="usage"></div>

## ⚙️ Usage

To execute the attacks or to deploy the FaultGuard framework, start by cloning the repository:

```bash
git clone https://github.com/emadef1/GAN_GRID.git
cd GAN_GRID
```
<sup>NOTE: if you're accessing this data from the anonymized repository, the above command might not work..</sup>

<p align="right"><a href="#top">(back to top)</a></p>
<div id="models"></div>


HTML

<!DOCTYPE html>
<html>
<head>
  <title>Tragétoria do Athletico Paranaense na Copa Sul-Americana 2018</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Tragétoria do Athletico Paranaense na Copa Sul-Americana 2018</h1>
    <div class="timeline">
      <div class="timeline-item">
        <h2>1ª Fase</h2>
        <p>O Athletico Paranaense avançou para a 2ª Fase após vencer o Newell's Old Boys (ARG) por 3-0 no agregado.</p>
        <p>Gols:</p>
        <ul>
          <li>Nikão (2)</li>
          <li>Thonny Anderson</li>
        </ul>
      </div>
      <div class="timeline-item">
        <h2>2ª Fase</h2>
        <p>O Athletico Paranaense avançou para as oitavas de final após vencer o Peñarol (URU) por 4-2 no agregado.</p>
        <p>Gols:</p>
        <ul>
          <li>Pablo (2)</li>
          <li>Renan Lodi</li>
          <li>Marcelo Cirino</li>
          <li>Thiago Heleno</li>
        </ul>
      </div>
      <div class="timeline-item">
        <h2>Oitavas de Final</h2>
        <p>O Athletico Paranaense avançou para as quartas de final após vencer o Caracas (VEN) por 4-2 no agregado.</p>
        <p>Gols:</p>
        <ul>
          <li>Bergson (2)</li>
          <li>Renan Lodi</li>
          <li>Raphael Veiga</li>
        </ul>
      </div>
      <div class="timeline-item">
        <h2>Quartas de Final</h2>
        <p>O Athletico Paranaense avançou para as semifinais após vencer o Bahia (BRA) por 4-0 no agregado.</p>
        <p>Gols:</p>
        <ul>
          <li>Raphael Veiga (2)</li>
          <li>Pablo</li>
          <li>Rony</li>
        </ul>
      </div>
      <div class="timeline-item">
        <h2>Semifinais</h2>
        <p>O Athletico Paranaense avançou para a final após empatar em 1-1 no agregado e vencer o Fluminense (BRA) por 7-6 nos pênaltis.</p>
        <p>Gols:</p>
        <ul>
          <li>Bruno Guimarães</li>
        </ul>
        <p>Pênaltis:</p>
        <ul>
          <li>Raphael Veiga (convertido)</li>
          <li>Bruno Guimarães (convertido)</li>
          <li>Rony (convertido)</li>
          <li>Thiago Heleno (convertido)</li>
          <li>Léo Pereira (convertido)</li>
          <li>



css 

body {
  background-color: black;
  color: red;
  font-family: Arial, sans-serif;
}

.container {
  margin: 0 auto;
  max-width: 800px;
  padding: 20px;
}

h1 {
  text-align: center;
}

.timeline {
  position: relative;
  margin-top: 40px;
  padding-left: 50px;
}

.timeline:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 2px;
  height: 100%;
  background-color: yellow;
}

.timeline-item {
  position: relative;
  margin-bottom: 40px;
}

.timeline-item:before {
  content: "";
  position: absolute;
  left: -6px;
  top: 0;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: yellow;
}

.timeline-item .timeline-content {
  margin-left: 20px;
}

.timeline-item h2 {
  margin-top: 0;
}

.timeline-item p {
  margin: 5px 0;
}



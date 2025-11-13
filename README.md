<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>NorthRiders</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    background: #000;
    color: #fff;
    text-align: center;
    margin: 0;
    padding: 20px;
    position: relative;
    overflow-x: hidden;
    }
	
	/* ✅ IMMAGINE FISSA, TRASPARENTE E LEGGERA */
    body::before {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    width: 500px; /* Larghezza fascia laterale */
    height: 100%;
    background: url("NORTH_RIDERS.png") no-repeat center;
    background-size: contain;
    opacity: 0.15; /* ✅ trasparenza (0.05 – 0.3 consigliato) */
    pointer-events: none; /* non blocca click */
    }
	
	  /* ✅ IMMAGINE FISSA LATO DESTRO */
  body::after {
    content: "";
    position: fixed;
    top: 0;
    right: 0;
    width: 500px;
    height: 100%;
    background: url("NORTH_RIDERS.png") no-repeat center;
    background-size: contain;
    opacity: 0.15;
    pointer-events: none;
  }

    .container {
      max-width: 500px;
      margin: auto;
    }

    .member-card {
      background: #1a1a1a;         /* ✅ Box leggermente più chiaro per contrasto */
      border-radius: 12px;
      padding: 20px;
      margin: 10px 0;
      box-shadow: 0 4px 10px rgba(255,255,255,0.08);
    }

    .logo {
      width: 400px;   /* cambia qui: 100px, 150px, 300px... */
      margin-bottom: -50px;
    }

    a {                    	\\bottone instagram
      display: inline-block;
      background: #ff00ff;
      color: #fff;
      padding: 10px 18px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover { 			\\colore piu scuro bottone instagram passaggio mouse
      background: #cc00cc;
    }
  </style>
</head>
<body>
  
  <!-- ✅ LOGO DEL GRUPPO QUI -->
   <img src="NR_LOGO5.png" alt="Logo del Gruppo" class="logo">

  <h1>North Riders</h1>
    
  <div class="container">

    <div class="member-card">
      <h3>BRUTALITY_ITA</h3>
      <a href="https://instagram.com/brutality_ita" target="_blank">Instagram</a>
    </div>

    <div class="member-card">
      <h3>IM.BREZ</h3>
      <a href="https://instagram.com/brutality_ita" target="_blank">Instagram</a>
    </div>

    <div class="member-card">
      <h3>BERTAGNOLLIDANIEL</h3>
      <a href="https://instagram.com/bertagnollidaniel" target="_blank">Instagram</a>
    </div>

    <div class="member-card">
      <h3>STOFFO13</h3>
      <a href="https://instagram.com/stoffo13" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>SNIP3RITA</h3>
      <a href="https://instagram.com/snip3rita" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>_MARTINA_BRANDO_</h3>
      <a href="https://instagram.com/_martina_brando_" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>FOLGHE_81</h3>
      <a href="https://instagram.com/folghe_81" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>VIKING.OF.TORQUE</h3>
      <a href="https://instagram.com/viking.of.torque" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>THEITALIANR1DER</h3>
      <a href="https://instagram.com/theitalianr1der" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>TRENTIN ALESSANDRO</h3>
      <a href="https://instagram.com/trentin_alessandro" target="_blank">Instagram</a>
    </div>
	
	<div class="member-card">
      <h3>LADY.ON.Z650</h3>
      <a href="https://instagram.com/lady.on.z650" target="_blank">Instagram</a>
    </div>

    <!-- Copia e incolla questo blocco per ogni membro -->

  </div>

</body>
</html>

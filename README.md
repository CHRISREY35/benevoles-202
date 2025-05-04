<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Inscriptions Bénévoles – Juin 2025</title>
  <style>
    html, body {margin:0; padding:0 10px; font-family:Arial,sans-serif;}
    .section-wrapper {border:2px solid #2e8b57; border-radius:8px; padding:15px; margin:30px 0;}
    .mobile-date {display:none; position:sticky; top:0; background:#fff; color:#2e8b57; font-weight:bold; text-align:center; padding:8px 0; border-bottom:1px solid #2e8b57; z-index:10;}
    .slot-button {background:green; color:#fff; padding:8px 15px; margin:4px; border:none; border-radius:5px; cursor:pointer;}
    .button-disabled {background:red !important; cursor:not-allowed;}
    .table-wrapper {overflow-x:auto;}
    table {width:100%; border-collapse:collapse; margin-top:20px;}
    th, td {border:1px solid #ccc; padding:12px; text-align:center;}
    th {background:#f2f2f2;}
    .section-header {color:#2e8b57; margin-top:0; font-size:1.2em;}
    .post-header {font-weight:bold; text-align:left;}
    .button-container {display:flex; gap:10px; flex-wrap:wrap; justify-content:center;}
    @media (max-width:767px) {
      .mobile-date {display:block;}
      table, thead, tbody, th, td, tr {display:block; width:100%;}
      thead {display:none;}
      tr {margin-bottom:20px; border:1px solid #ccc; border-radius:8px; padding:10px;}
      td {text-align:left; padding:8px; border:none; position:relative;}
      td::before {content:attr(data-label); font-weight:bold; display:block; margin-bottom:6px;}
      .button-container {justify-content:flex-start;}
    }
  </style>
  <script>
    const formBase = 'https://docs.google.com/forms/d/e/1FAIpQLSc0V4hSS8pM7BgeUI6TYmPpwtSIy7OuiVbT3L1EFcvVKKrK1Q/viewform';
    function openFormAndDisable(btn, poste, creneau) {
      const params = '?entry.1853743372=' + encodeURIComponent(poste) +
                     '&entry.1838914985=' + encodeURIComponent(creneau);
      window.open(formBase + params, '_self');
      btn.classList.add('button-disabled');
      btn.disabled = true;
    }
  </script>
</head>
<body>
  <h2>📋 Inscriptions Bénévoles – Juin 2025</h2>

  <!-- Samedi 21 juin 2025 -->
  <div class="section-wrapper">
    <div class="mobile-date">Samedi 21 juin 2025</div>
    <h3 class="section-header">📅 Samedi 21 juin 2025</h3>
    <div class="table-wrapper">
      <table>
        <thead>
          <tr><th>Poste</th><th>Matin (8h‑13h)</th><th>Après‑midi (13h‑19h)</th><th>Soirée (19h‑00h)</th></tr>
        </thead>
        <tbody>
          <tr>
            <td class="post-header" data-label="Poste">👨‍🍳 Cuisine</td>
            <td data-label="Matin (8h‑13h)"><div class="button-container"><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Matin 8h-13h')">1</button><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Matin 8h-13h')">2</button></div></td>
            <td data-label="Après‑midi (13h‑19h)"><div class="button-container"><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Après-midi 13h-19h')">1</button><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Après-midi 13h-19h')">2</button></div></td>
            <td data-label="Soirée (19h‑00h)"><div class="button-container"><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Soirée 19h-00h')">1</button><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Soirée 19h-00h')">2</button><button class="slot-button" onclick="openFormAndDisable(this,'Cuisine','Soirée 19h-00h')">3</button></div></td>
          </tr>
          <tr>
            <td class="post-header" data-label="Poste">🍽️ Service</td>
            <td data-label="Matin (8h‑13h)"><button class="slot-button" onclick="openFormAndDisable(this,'Service','Matin 8h-13h')">1</button></td>
            <td data-label="Après‑midi (13h‑19h)"><button class="slot-button" onclick="openFormAndDisable(this,'Service','Après-midi 13h-19h')">1</button></td>
            <td data-label="Soirée (19h‑00h)"><button class="slot-button" onclick="openFormAndDisable(this,'Service','Soirée 19h-00h')">1</button></td>
          </tr>
        </tbody>
      </table>
      <!-- Table 2 -->
      <table>
        <thead><tr><th>Poste</th><th>Matin (8h‑12h)</th><th>Après‑midi (13h30‑19h)</th></tr></thead>
        <tbody>
          <tr><td class="post-header" data-label="Poste">🛡️ Sécurité porte</td><td data-label="Matin (8h‑12h)"><button class="slot-button" onclick="openFormAndDisable(this,'Sécurité porte','Matin 8h-12h')">1</button></td><td data-label="Après‑midi (13h30‑19h)"><button class="slot-button" onclick="openFormAndDisable(this,'Sécurité porte','Après-midi 13h30-19h')">1</button></td></tr>
          <tr><td class="post-header" data-label="Poste">📋 Secrétaire de tir</td><td data-label="Matin (8h‑12h)"><div class="button-container"><button class="slot-button" onclick="openFormAndDisable(this,'Secrétaire de tir','Matin 8h-12h')">1</button><button class="slot-button" onclick="openFormAndDisable(this,'Secrétaire de tir','Matin 8h-12h')">2</button><button class="slot-button" onclick="openFormAndDisable(this,'Secrétaire de tir','Matin 8h-12h')">3</button>...</div></td><td data-label="Après‑midi (13h30‑19h)"><div class="button-container"><button class="slot-button" onclick="openFormAndDisable(this,'Secrétaire de tir','Après-midi 13h30-19h')">1</button>...</div></td></tr>
        </tbody>
      </table>
    </div>
  </div>
  <!-- (Continue similarly for 28 juin…) -->
</body>
</html>

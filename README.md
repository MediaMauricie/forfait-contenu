<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Forfaits de contenu mensuel — Média Mauricie 2026</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Montserrat',sans-serif;background:#f0f0f0;color:#2d2d2d;min-height:100vh;}
a{color:inherit;text-decoration:none;}
.wrap{max-width:960px;margin:0 auto;padding:48px 24px 64px;}
.header{display:flex;align-items:center;justify-content:space-between;margin-bottom:52px;}
.header-badge{background:#2d2d2d;color:#fff;font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;padding:6px 16px;border-radius:20px;}
.hero{margin-bottom:44px;}
.hero-eyebrow{font-size:9px;font-weight:800;letter-spacing:3px;text-transform:uppercase;color:#c0392b;margin-bottom:14px;}
.hero-title{font-size:62px;font-weight:800;color:#2d2d2d;line-height:.95;letter-spacing:-3px;margin-bottom:16px;}
.hero-sub{font-size:12px;font-weight:500;color:#888;line-height:1.7;}
.eyebrow{font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#2d2d2d;border:2px solid #2d2d2d;display:inline-flex;align-items:center;padding:5px 16px;border-radius:20px;margin-bottom:18px;}
.plans{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px;}
.plan{border-radius:14px;overflow:hidden;background:#fff;border:1.5px solid #e0e0e0;display:flex;flex-direction:column;}
.plan.pro{border:1.5px solid #e0e0e0;position:relative;}
.plan-ribbon{background:#c0392b;color:#fff;font-size:8.5px;font-weight:800;letter-spacing:2px;text-transform:uppercase;text-align:center;padding:7px 16px;}
.plan-head{padding:22px 24px 18px;}
.plan-badge{background:#2d2d2d;color:#fff;font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;padding:5px 14px;border-radius:20px;display:inline-block;margin-bottom:14px;}
.plan.pro .plan-badge{background:#c0392b;}
.plan-price-row{display:flex;align-items:baseline;gap:6px;margin-bottom:8px;}
.plan-price{font-size:40px;font-weight:800;color:#2d2d2d;line-height:1;letter-spacing:-2px;}
.plan-price-unit{font-size:11px;font-weight:600;color:#999;}
.plan-pill{background:#f0f0f0;border:1.5px solid #ddd;color:#555;font-size:9px;font-weight:700;letter-spacing:1px;padding:3px 10px;border-radius:20px;display:inline-block;margin-left:4px;}
.plan-tag{font-size:10.5px;font-weight:600;color:#888;margin-top:4px;}
.plan-body{padding:0 24px 22px;flex:1;display:flex;flex-direction:column;}
.shoot{display:flex;align-items:center;gap:10px;background:#f7f7f7;border-radius:8px;padding:10px 14px;margin-bottom:16px;}
.shoot-icon{font-size:18px;}
.shoot-title{font-size:11.5px;font-weight:700;color:#2d2d2d;}
.shoot-sub{font-size:10px;font-weight:500;color:#999;margin-top:2px;}
.items{list-style:none;display:flex;flex-direction:column;gap:8px;margin-bottom:16px;}
.items li{font-size:11px;font-weight:500;color:#555;display:flex;align-items:flex-start;gap:8px;line-height:1.55;}
.ci{color:#c0392b;font-weight:800;font-size:11px;flex-shrink:0;margin-top:1px;}
.ci-plus{color:#aaa;font-weight:800;font-size:11px;flex-shrink:0;margin-top:1px;}
.equiv{font-size:9.5px;color:#bbb;font-weight:500;display:block;margin-top:2px;}
.item-link a{color:#c0392b;font-weight:700;}
.photos-note{background:#fff;border:1.5px solid #e0e0e0;border-radius:10px;padding:14px 18px;font-size:11px;font-weight:500;color:#666;line-height:1.65;margin-bottom:28px;}
.photos-note strong{color:#2d2d2d;}
.photos-note .sep{display:block;margin-top:6px;color:#aaa;font-size:10.5px;}
.engage-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:14px;}
.eng-card{border-radius:14px;overflow:hidden;background:#fff;border:1.5px solid #e0e0e0;}
.eng-card.best{border-color:#c0392b;}
.best-bar{background:#c0392b;color:#fff;font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;text-align:center;padding:6px;}
.eng-head{background:#2d2d2d;padding:14px 18px;}
.eng-tag{font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,0.4);margin-bottom:4px;}
.eng-dur{font-size:32px;font-weight:800;color:#fff;line-height:1;letter-spacing:-1px;}
.eng-body{padding:16px 18px;}
.eng-plan{margin-bottom:14px;padding-bottom:14px;border-bottom:1px solid #ebebeb;}
.eng-plan:last-of-type{border-bottom:none;margin-bottom:0;padding-bottom:0;}
.eng-label{font-size:8px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;color:#777;margin-bottom:5px;}
.eng-price-row{display:flex;align-items:baseline;gap:5px;margin-bottom:6px;}
.eng-price{font-size:24px;font-weight:800;color:#2d2d2d;letter-spacing:-1px;}
.eng-unit{font-size:11px;font-weight:600;color:#666;}
.eng-none{font-size:11px;color:#999;background:#f5f5f5;border-radius:5px;padding:5px 10px;display:inline-block;margin-top:2px;}
.eng-bonus-item{display:flex;align-items:flex-start;gap:6px;font-size:12px;font-weight:700;color:#2d2d2d;line-height:1.5;margin-top:4px;}
.eng-icon{color:#c0392b;font-size:10px;margin-top:3px;}
.eng-val{font-size:10px;color:#888;display:block;margin-top:3px;font-weight:500;}
.free-box{background:#c0392b;border-radius:8px;padding:10px 12px;margin-top:6px;}
.free-title{font-size:11px;font-weight:800;color:#fff;line-height:1.4;}
.free-sub{font-size:9.5px;color:rgba(255,255,255,0.75);margin-top:4px;}
.billing-label{font-size:8px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;color:#777;margin-bottom:5px;margin-top:14px;padding-top:14px;border-top:1px solid #ebebeb;}
.billing-text{font-size:11px;font-weight:600;color:#444;margin-top:4px;}
.delais{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:14px;}
.delai{border-radius:14px;overflow:hidden;background:#fff;border:1.5px solid #e0e0e0;}
.delai.urgent{border-color:#c0392b;}
.delai-head{background:#2d2d2d;padding:16px 18px;}
.delai-label{font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,0.45);margin-bottom:4px;}
.delai-time{font-size:22px;font-weight:800;color:#fff;line-height:1.1;letter-spacing:-1px;}
.delai-body{padding:16px 18px;}
.delai-items{list-style:none;display:flex;flex-direction:column;gap:8px;}
.delai-items li{font-size:11px;font-weight:600;color:#2d2d2d;display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid #f5f5f5;gap:8px;}
.delai-items li span:first-child{white-space:nowrap;font-size:11px;}
.delai-items li:last-child{border-bottom:none;}
.dp{font-weight:700;color:#c0392b;white-space:nowrap;}
.dp.incl{color:#27ae60;}
.delai-note{font-size:10px;font-weight:500;color:#bbb;margin-top:10px;font-style:italic;}
.options{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:14px;}
.opt{background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;overflow:hidden;display:flex;flex-direction:column;}
.opt-head{background:#2d2d2d;padding:14px 18px;display:flex;align-items:center;gap:10px;}
.opt-icon{font-size:20px;}
.opt-label{font-size:10px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;color:#fff;}
.opt-body{padding:14px 18px;flex:1;}
.opt-row{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid #f5f5f5;}
.opt-row:last-child{border-bottom:none;}
.opt-name{font-size:11.5px;font-weight:600;color:#2d2d2d;}
.opt-note{font-size:9.5px;color:#aaa;margin-top:2px;}
.opt-price{font-size:14px;font-weight:800;color:#2d2d2d;white-space:nowrap;}
.opt-price.sm{font-size:11px;font-weight:600;color:#aaa;}
.opt-cta{padding:0 18px 16px;}
.opt-btn{display:block;background:#2d2d2d;color:#fff;font-size:9px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;padding:8px 14px;border-radius:6px;text-align:center;text-decoration:none;}
.transport{background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;overflow:hidden;margin-bottom:14px;display:grid;grid-template-columns:1fr 1fr;}
.transport-info{padding:24px 26px;display:flex;flex-direction:column;justify-content:center;gap:14px;}
.transport-badge{background:#2d2d2d;color:#fff;font-size:9px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;padding:5px 14px;border-radius:20px;display:inline-block;align-self:flex-start;}
.transport-title{font-size:16px;font-weight:800;color:#2d2d2d;line-height:1.3;}
.transport-sub{font-size:11px;font-weight:500;color:#888;}
.transport-horezone{background:#f5f5f5;border:1.5px solid #e0e0e0;border-radius:8px;padding:10px 14px;display:flex;align-items:center;justify-content:space-between;}
.transport-horezone-label{font-size:10px;font-weight:600;color:#555;}
.transport-horezone-price{font-size:15px;font-weight:800;color:#2d2d2d;}
.transport-map img{width:100%;height:100%;object-fit:cover;display:block;}
.mel{background:#2d2d2d;border-radius:14px;overflow:hidden;margin-bottom:14px;}
.mel-hero{padding:28px 28px 24px;display:flex;align-items:center;justify-content:space-between;gap:24px;}
.mel-eyebrow{font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#999;margin-bottom:10px;}
.mel-title{font-size:26px;font-weight:800;color:#fff;letter-spacing:-1px;margin-bottom:10px;}
.mel-desc{font-size:11.5px;font-weight:500;color:rgba(255,255,255,0.55);line-height:1.7;max-width:480px;}
.mel-desc strong{color:rgba(255,255,255,0.85);}
.mel-right{display:flex;flex-direction:column;align-items:center;gap:12px;flex-shrink:0;}
.mel-badge{background:#fff;border:2px solid #2d2d2d;border-radius:12px;padding:16px 20px;text-align:center;}
.mel-amount{font-size:30px;font-weight:800;color:#2d2d2d;line-height:1;}
.mel-badge-label{font-size:9px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#666;margin-top:4px;}
.mel-btn{display:inline-block;background:#fff;color:#2d2d2d;font-size:9px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;padding:9px 18px;border-radius:7px;text-decoration:none;white-space:nowrap;}
.mel-steps{background:rgba(255,255,255,0.05);border-top:1px solid rgba(255,255,255,0.08);padding:18px 28px;display:flex;gap:16px;}
.mel-step{flex:1;display:flex;align-items:flex-start;gap:10px;font-size:10.5px;font-weight:500;color:rgba(255,255,255,0.6);line-height:1.55;}
.mel-num{background:#fff;color:#2d2d2d;font-size:9px;font-weight:800;width:20px;height:20px;border-radius:50%;display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:1px;}
.notes{display:flex;flex-direction:column;gap:12px;margin-bottom:14px;}
.note-bloc{border-radius:14px;padding:22px 24px;}
.note-bloc.dark{background:#2d2d2d;}
.note-bloc.light{background:#fff;border:1.5px solid #e0e0e0;}
.note-bloc.mid{background:#3a3a3a;}
.note-bloc-title{font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;margin-bottom:14px;}
.note-bloc.dark .note-bloc-title,.note-bloc.mid .note-bloc-title{color:#777;}
.note-bloc.light .note-bloc-title{color:#888;}
.note-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.note-item{display:flex;align-items:flex-start;gap:8px;font-size:11px;line-height:1.6;padding:8px 0;border-bottom:1px solid;}
.note-bloc.dark .note-item{color:rgba(255,255,255,0.75);border-color:rgba(255,255,255,0.07);}
.note-bloc.mid .note-item{color:rgba(255,255,255,0.75);border-color:#4a4a4a;}
.note-bloc.light .note-item{color:#555;border-color:#f0f0f0;}
.note-item:last-child{border-bottom:none;}
.ni{color:#c0392b;font-weight:800;font-size:11px;flex-shrink:0;margin-top:2px;}
.note-bloc.dark .note-item strong,.note-bloc.mid .note-item strong{color:#fff;}
.note-bloc.light .note-item strong{color:#2d2d2d;}
.note-link{color:#e87060 !important;}
.clauses{background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;padding:20px 24px;margin-bottom:14px;}
.clauses-label{font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#aaa;margin-bottom:12px;}
.clause-item{display:flex;align-items:flex-start;gap:8px;font-size:11px;color:#555;line-height:1.6;padding:8px 0;border-bottom:1px solid #f0f0f0;}
.clause-item:last-child{border-bottom:none;}
.clause-item strong{color:#2d2d2d;}
.table-wrap{background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;overflow:hidden;margin-bottom:14px;}
table{width:100%;border-collapse:collapse;}
th{background:#2d2d2d;color:#fff;font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;padding:12px 16px;text-align:center;}
th:first-child{text-align:left;background:#1a1a1a;}
th.pro-col{border-left:3px solid #c0392b;}
tr{border-bottom:1px solid #f0f0f0;}
tr:last-child{border-bottom:none;}
tr:nth-child(even){background:#fafafa;}
td{padding:10px 16px;font-size:11px;font-weight:600;color:#2d2d2d;}
td:not(:first-child){text-align:center;font-size:13px;}
td.pro-col{border-left:3px solid #c0392b;}
.check{color:#27ae60;font-weight:800;}
.cross{color:#ddd;font-size:10px;}
.green-row td{color:#1a7a4a;font-weight:700;}
.green-row{background:#eafaf2 !important;}
tfoot td{padding:12px 16px;background:#2d2d2d;color:rgba(255,255,255,0.5);font-size:10px;font-weight:600;}
tfoot .tfoot-btns{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;}
tfoot .tfoot-btn{display:inline-block;background:#fff;color:#2d2d2d;font-size:9px;font-weight:800;letter-spacing:1px;text-transform:uppercase;padding:6px 14px;border-radius:5px;text-decoration:none;white-space:nowrap;}
.taxes{background:#2d2d2d;color:rgba(255,255,255,0.4);font-size:10px;font-weight:600;text-align:center;padding:10px 20px;border-radius:8px;margin-bottom:12px;}
.taxes strong{color:rgba(255,255,255,0.75);}
.footer{padding-top:22px;border-top:1.5px solid #ddd;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px;margin-bottom:48px;}
.footer img{height:32px;}
.footer-info{font-size:10px;font-weight:500;color:#aaa;text-align:right;line-height:1.8;}
.footer-info a{color:#555;font-weight:700;}
@media(max-width:700px){
  .plans,.engage-grid,.delais,.options,.recap-grid{grid-template-columns:1fr;}
  .transport{grid-template-columns:1fr;}
  .transport-map{height:200px;}
  .hero-title{font-size:42px;}
  .note-grid{grid-template-columns:1fr;}
  .mel-hero{flex-direction:column;}
  .mel-steps{flex-direction:column;}
  .header{flex-direction:column;align-items:flex-start;gap:12px;}
  .footer{flex-direction:column;align-items:flex-start;}
  .footer-info{text-align:left;}
  .delai-time{font-size:18px;}
  .delai-items li{font-size:10px;}
  .dp{font-size:11px;}
  .opt-row{flex-wrap:nowrap;}
  .opt-name{font-size:10.5px;}
  .opt-price{font-size:13px;white-space:nowrap;}
  .plans-cta{grid-template-columns:1fr !important;}
  .plan-price{font-size:32px;}
  .plan-price-row{flex-wrap:wrap;gap:4px;}
}
@media(max-width:500px){
  .delais,.options,.engage-grid{grid-template-columns:1fr;}
  .wrap{padding:20px 14px 48px;}
  .plan-head{padding:16px 16px 12px;}
  .plan-body{padding:0 16px 18px;}
  .eng-head{padding:12px 14px;}
  .eng-body{padding:12px 14px;}
  .opt-head{padding:12px 14px;}
  .opt-body{padding:12px 14px;}
  .opt-cta{padding:0 14px 14px;}
  .delai-head{padding:14px 14px;}
  .delai-body{padding:12px 14px;}
  .note-bloc{padding:16px 16px;}
  .process-box{padding:18px 16px;}
  .partenaire{padding:16px 14px;}
  .inclus-strip{padding:12px 14px;}
  .clauses{padding:14px 16px;}
  .mel-hero{padding:20px 16px 16px;}
  .mel-steps{padding:14px 16px;}
}

/* ── FORM SECTION ── */
.form-section{background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;padding:28px 28px 0 28px;margin-bottom:12px;}
.form-eyebrow{font-size:9px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#c0392b;margin-bottom:8px;}
.form-title{font-size:20px;font-weight:800;color:#2d2d2d;letter-spacing:-0.5px;margin-bottom:8px;}
.form-sub{font-size:12px;font-weight:500;color:#666;line-height:1.75;margin-bottom:0;max-width:560px;}
.form-sub strong{color:#2d2d2d;}
@media(max-width:700px){.form-section{padding:22px 16px 0 16px;}}

/* ═══════════════════════════════════════════════════
   HOVER FIXES — couleurs préservées au survol
   Le problème : a{color:inherit} sans :hover explicite
   laisse le navigateur appliquer bleu/violet par défaut
   ═══════════════════════════════════════════════════ */
a:hover{color:inherit;}

/* Boutons .opt-btn — fond #2d2d2d, texte blanc */
.opt-btn{color:#fff !important;}
.opt-btn:hover{background:#1a1a1a !important;color:#fff !important;}

/* Boutons tfoot — fond blanc, texte #2d2d2d */
tfoot .tfoot-btn{color:#2d2d2d !important;}
tfoot .tfoot-btn:hover{background:#e8e8e8 !important;color:#2d2d2d !important;}

/* Bouton MEL — fond blanc sur dark, texte #2d2d2d */
.mel-btn{color:#2d2d2d !important;}
.mel-btn:hover{background:#e8e8e8 !important;color:#2d2d2d !important;}

/* Boutons inline dans les td (style inline avec background:#2d2d2d) */
td a{color:#fff !important;}
td a:hover{opacity:.85;color:#fff !important;}

/* Liens item-link — rouge */
.item-link a{color:#c0392b !important;}
.item-link a:hover{color:#c0392b !important;text-decoration:underline;}

/* Liens note-link — rouge clair sur dark bg */
.note-link{color:#e87060 !important;}
.note-link:hover{color:#e87060 !important;text-decoration:underline;}

/* Liens footer */
.footer-info a{color:#555 !important;}
.footer-info a:hover{color:#555 !important;text-decoration:underline;}

/* Liens inline dans .items (style="color:#c0392b") */
.items a{color:#c0392b !important;}
.items a:hover{color:#c0392b !important;text-decoration:underline;}

</style>
</head><body>
<div class="wrap">

<div class="header">
  <img src="https://mediamauricie.com/wp-content/uploads/2026/03/Media-Mauricie_logo_M-coul.png" alt="Média Mauricie" style="height:48px;">
  <div class="header-badge">📍 Forfaits mensuels · 2026</div>
</div>

<div class="hero">
  <div class="hero-eyebrow">Forfaits de contenu mensuel · Média Mauricie · 2026</div>
  <div class="hero-title">Restez visible.<br>Chaque mois.</div>
  <div class="hero-sub">Offres valides jusqu'au 31 décembre 2026 · Tous les prix sont + taxes applicables</div>
</div>

<div class="eyebrow">Forfaits mensuels</div>
<div class="plans">

  <div class="plan">
    <div class="plan-head">
      <div class="plan-badge">Forfait Essentiel</div>
      <div class="plan-price-row">
        <div class="plan-price">2 000$</div>
        <div class="plan-price-unit">/ mois + tx</div>
        <div class="plan-pill">📍 2h sur place</div>
      </div>
      <div class="plan-tag">Présence régulière · impact constant</div>
    </div>
    <div class="plan-body">
      <div class="shoot"><span class="shoot-icon">🎥</span><div><div class="shoot-title">Tournage & shooting — 2h sur place</div><span class="shoot-sub">Équipe Média Mauricie · photo & vidéo inclus</span></div></div>
      <ul class="items">
        <li><span class="ci">✓</span><span>Reels cinématiques — 3×15s <span style="color:#bbb;font-size:10px;">OU</span> 1×30s & 1×15s<span class="equiv">≈ 6–10h de montage · approche storytelling</span></span></li>
        <li><span class="ci">✓</span>Sous-titres optimisés & logo animé inclus</li>
        <li><span class="ci">✓</span>25 photos lifestyle HD retouchées</li>
        <li><span class="ci">✓</span>Drone inclus si applicable — photo & vidéo · selon conditions & nature du tournage</li>
        <li><span class="ci">✓</span>Musique sous licence — banque Média Mauricie disponible</li>
        <li><span class="ci">✓</span><span>📸 Photos remises sur <strong>album Pixpa privé</strong> — accès jusqu'à la fin du contrat<br><span style="display:inline-block;">🎬 Vidéos & reels remis sur <strong>Dropbox</strong> avec image de couverture suggérée</span></span></li>
        <li><span class="ci">✓</span>Rencontre de planification 30 min incluse</li>
        <li><span class="ci">✓</span><span>Espace client <strong>ClickUp</strong> inclus — approbations, suivi des révisions & communications centralisées<br><span style="font-size:10px;color:#aaa;">Optimise le temps, les échanges et l'expérience pour tous</span><br><span style="font-size:10px;color:#c0392b;font-weight:600;">+ Calendrier de contenu partagé inclus si forfait <a href="https://www.mediamauricie.com/gestion-reseaux-sociaux" target="_blank" style="color:#c0392b;font-weight:700;">publications réseaux sociaux</a> jumelé</span></span></li>
      </ul>
    </div>
  </div>

  <div class="plan pro">
    <div class="plan-head">
      <div class="plan-badge">Forfait Pro ★</div>
      <div class="plan-price-row">
        <div class="plan-price">3 500$</div>
        <div class="plan-price-unit">/ mois + tx</div>
        <div class="plan-pill">📍 4h sur place</div>
      </div>
      <div class="plan-tag">Contenu intensif · impact maximal</div>
    </div>
    <div class="plan-body">
      <div class="shoot"><span class="shoot-icon">🎥</span><div><div class="shoot-title">Tournage & shooting — 4h sur place</div><span class="shoot-sub">Équipe Média Mauricie · photo & vidéo</span></div></div>
      <ul class="items">
        <li><span class="ci">✓</span><span>Reels cinématiques — 4×15s & 1×30s<span class="equiv">≈ 10–16h de montage · approche storytelling</span></span></li>
        <li><span class="ci">✓</span>Sous-titres optimisés & logo animé inclus</li>
        <li><span class="ci">✓</span>50 photos lifestyle HD retouchées</li>
        <li><span class="ci">✓</span>Drone inclus si applicable — photo & vidéo · selon conditions & nature du tournage</li>
        <li><span class="ci">✓</span>Musique sous licence — banque Média Mauricie disponible</li>
        <li><span class="ci">✓</span><span>📸 Photos remises sur <strong>album Pixpa privé</strong> — accès jusqu'à la fin du contrat<br><span style="display:inline-block;">🎬 Vidéos & reels remis sur <strong>Dropbox</strong> avec image de couverture suggérée</span></span></li>
        <li><span class="ci">✓</span>Rencontre de planification 30 min incluse</li>
        <li><span class="ci">✓</span><span>Espace client <strong>ClickUp</strong> inclus — approbations, suivi des révisions & communications centralisées<br><span style="font-size:10px;color:#aaa;">Optimise le temps, les échanges et l'expérience pour tous</span><br><span style="font-size:10px;color:#c0392b;font-weight:600;">+ Calendrier de contenu partagé inclus si forfait <a href="https://www.mediamauricie.com/gestion-reseaux-sociaux" target="_blank" style="color:#c0392b;font-weight:700;">publications réseaux sociaux</a> jumelé</span></span></li>
      </ul>
    </div>
  </div>

</div>

<!-- BOUTONS SOUS LES PLANS -->
<div class="plans-cta" style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:28px;">
  <a href="https://www.mediamauricie.com/banques-dheures" target="_blank" style="display:flex;align-items:center;justify-content:space-between;background:#2d2d2d;color:#fff !important;text-decoration:none;padding:16px 20px;border-radius:10px;">
    <div>
      <div style="font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.45);margin-bottom:4px;">Option complémentaire</div>
      <div style="font-size:13px;font-weight:800;color:#fff;">Voir nos banques d'heures de montage</div>
    </div>
    <div style="font-size:20px;color:rgba(255,255,255,.5);flex-shrink:0;margin-left:12px;">→</div>
  </a>
  <a href="https://www.mediamauricie.com/gestion-reseaux-sociaux" target="_blank" style="display:flex;align-items:center;justify-content:space-between;background:#c0392b;color:#fff !important;text-decoration:none;padding:16px 20px;border-radius:10px;">
    <div>
      <div style="font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.55);margin-bottom:4px;">Option complémentaire</div>
      <div style="font-size:13px;font-weight:800;color:#fff;">Voir nos forfaits réseaux sociaux</div>
    </div>
    <div style="font-size:20px;color:rgba(255,255,255,.5);flex-shrink:0;margin-left:12px;">→</div>
  </a>
</div>

<div class="photos-note">📸 <strong>Photos lifestyle incluses :</strong> portraits sur place, ambiance de travail, équipe en action, environnement, extérieur & drone.<span class="sep">Sur soumission séparée : photos de produits, portraits studio formels, photos d'équipe structurées, conférences de presse, immobilier, culinaire.</span></div>

<div class="eyebrow">Durée d'engagement — mêmes tarifs, bonus croissants</div>
<div class="engage-grid">

  <div class="eng-card">
    <div class="eng-head"><div class="eng-tag">Minimum requis</div><div class="eng-dur">3 mois</div></div>
    <div class="eng-body">
      <div class="eng-plan">
        <div class="eng-label">Forfait Essentiel</div>
        <div class="eng-price-row"><span class="eng-price">2 000$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="eng-none">Tarif standard — aucun bonus</div>
      </div>
      <div class="eng-plan">
        <div class="eng-label">Forfait Pro</div>
        <div class="eng-price-row"><span class="eng-price">3 500$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="eng-none">Tarif standard — aucun bonus</div>
      </div>
      <div class="billing-label">Facturation</div>
      <div class="billing-text">2 mois à la signature · dernier mois en fin de contrat</div>
    </div>
  </div>

  <div class="eng-card">
    <div class="eng-head"><div class="eng-tag">Populaire</div><div class="eng-dur">6 mois</div></div>
    <div class="eng-body">
      <div class="eng-plan">
        <div class="eng-label">Forfait Essentiel</div>
        <div class="eng-price-row"><span class="eng-price">2 000$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="eng-bonus-item"><span class="eng-icon">✦</span><span>+2 reels <strong>bonus produits</strong> au 6e mois<span class="eng-val">valeur estimée 400–800$ · non inclus dans le forfait</span></span></div>
      </div>
      <div class="eng-plan">
        <div class="eng-label">Forfait Pro</div>
        <div class="eng-price-row"><span class="eng-price">3 500$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="eng-bonus-item"><span class="eng-icon">✦</span><span>+4 reels <strong>bonus produits</strong> au 6e mois<span class="eng-val">valeur estimée 800–1 600$ · non inclus dans le forfait</span></span></div>
      </div>
      <div class="billing-label">Facturation</div>
      <div class="billing-text">2 mois à la signature · puis aux 2 mois</div>
    </div>
  </div>

  <div class="eng-card best">
    <div class="best-bar">★ Meilleure valeur — Engagement annuel</div>
    <div class="eng-head"><div class="eng-tag">Engagement annuel</div><div class="eng-dur">12 mois</div></div>
    <div class="eng-body">
      <div class="eng-plan">
        <div class="eng-label">Forfait Essentiel</div>
        <div class="eng-price-row"><span class="eng-price">2 000$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="eng-bonus-item"><span class="eng-icon">✦</span><span>+2 reels <strong>bonus produits</strong> au 6e mois<span class="eng-val">valeur estimée 400–800$ · non inclus dans le forfait</span></span></div>
        <div class="eng-bonus-item"><span class="eng-icon">✦</span><span>+2 reels <strong>bonus produits</strong> au 12e mois<span class="eng-val">valeur estimée 400–800$ · non inclus dans le forfait</span></span></div>
      </div>
      <div class="eng-plan">
        <div class="eng-label">Forfait Pro</div>
        <div class="eng-price-row"><span class="eng-price">3 500$</span><span class="eng-unit">/ mois + tx</span></div>
        <div class="free-box"><div class="free-title">🎁 1 MOIS COMPLET GRATUIT au 12e mois</div><div class="free-sub">Valeur 3 500$ + tx · Renouvellement recommence après</div></div>
      </div>
      <div class="billing-label">Facturation</div>
      <div class="billing-text">2 mois à la signature · puis aux 2 mois jusqu'à la fin</div>
    </div>
  </div>

</div>

<div class="eyebrow">Délais de livraison</div>
<div class="delais">
  <div class="delai">
    <div class="delai-head"><div class="delai-label">Standard</div><div class="delai-time">10–20 jours ouvrables</div></div>
    <div class="delai-body">
      <ul class="delai-items">
        <li><span>Photos retouchées</span><span class="dp incl">✓ Inclus</span></li>
        <li><span>Reels montés & optimisés</span><span class="dp incl">✓ Inclus</span></li>
      </ul>
    </div>
  </div>
  <div class="delai">
    <div class="delai-head"><div class="delai-label">Rush</div><div class="delai-time">5 jours ouvrables</div></div>
    <div class="delai-body">
      <ul class="delai-items">
        <li><span>Photos rush</span><span class="dp">+150$</span></li>
        <li><span>Reel rush</span><span class="dp">+150$ / reel</span></li>
      </ul>
      <div class="delai-note">Sous réserve de disponibilité</div>
    </div>
  </div>
  <div class="delai urgent">
    <div class="delai-head"><div class="delai-label">Urgent — 48–72h</div><div class="delai-time">48 à 72 heures</div></div>
    <div class="delai-body">
      <ul class="delai-items">
        <li><span>Photos urgentes</span><span class="dp">+300$</span></li>
        <li><span>Reel urgent</span><span class="dp">+350$ / reel</span></li>
      </ul>
      <div class="delai-note">Sous réserve de disponibilité · Priorité absolue</div>
    </div>
  </div>
</div>

<div class="eyebrow">Options à la carte</div>
<div class="options">
  <div class="opt">
    <div class="opt-head"><div class="opt-icon">📸</div><div class="opt-label">Photos additionnelles</div></div>
    <div class="opt-body">
      <div class="opt-row"><div><div class="opt-name">+15 photos</div><div class="opt-note">Dans votre album</div></div><div class="opt-price">300$</div></div>
      <div class="opt-row"><div><div class="opt-name">+25 photos</div><div class="opt-note">Dans votre album</div></div><div class="opt-price">500$</div></div>
      <div class="opt-row"><div><div class="opt-name" style="color:#888;">Produits · studio · spécialisé</div><div class="opt-note">Sur soumission séparée</div></div></div>
    </div>
    <div class="opt-cta"><a href="https://mediamauricie.com/contact" target="_blank" class="opt-btn">Demander une soumission</a></div>
  </div>
  <div class="opt">
    <div class="opt-head"><div class="opt-icon">🎬</div><div class="opt-label">Banques d'heures de montage</div></div>
    <div class="opt-body">
      <div class="opt-row"><div><div class="opt-name">15 heures</div><div class="opt-note">100$/h · 12 mois</div></div><div class="opt-price">1 500$</div></div>
      <div class="opt-row"><div><div class="opt-name">25 heures ★</div><div class="opt-note">95$/h · éco. 125$</div></div><div class="opt-price">2 375$</div></div>
      <div class="opt-row"><div><div class="opt-name">50 heures</div><div class="opt-note">90$/h · éco. 500$</div></div><div class="opt-price">4 500$</div></div>
    </div>
    <div class="opt-cta"><a href="https://www.mediamauricie.com/banques-dheures" target="_blank" class="opt-btn">Voir les forfaits</a></div>
  </div>
  <div class="opt">
    <div class="opt-head"><div class="opt-icon">📁</div><div class="opt-label">Fichiers bruts & colorisation</div></div>
    <div class="opt-body">
      <div class="opt-row"><div><div class="opt-name">Remise LOG — 2h</div><div class="opt-note">Tournage Essentiel</div></div><div class="opt-price">175$</div></div>
      <div class="opt-row"><div><div class="opt-name">Remise LOG — 4h</div><div class="opt-note">Tournage Pro</div></div><div class="opt-price">250$</div></div>
      <div class="opt-row"><div><div class="opt-name" style="color:#888;">Colorisation équipe</div><div class="opt-note">Pour votre montage interne</div></div><div class="opt-price sm">Voir page</div></div>
    </div>
    <div class="opt-cta"><a href="https://mediamauricie.com/remise-des-fichiers-bruts" target="_blank" class="opt-btn">Voir nos offres</a></div>
  </div>
</div>

<div class="transport">
  <div class="transport-info">
    <div class="transport-badge">🚗 Déplacement inclus</div>
    <div class="transport-title">Déplacement inclus dans la zone au cœur de la Mauricie</div>
    <div class="transport-sub">Zone couverte — en vert sur la carte</div>
    <div class="transport-horezone">
      <div class="transport-horezone-label">Hors zone</div>
      <div class="transport-horezone-price">+1$ / km A/R</div>
    </div>
  </div>
  <div class="transport-map"><img src="https://mediamauricie.com/wp-content/uploads/2026/03/map.jpg" alt="Zone transport Mauricie"></div>
</div>

<div class="taxes">Tous les prix <strong>+ taxes applicables</strong></div>
<div class="footer">
  <img src="https://mediamauricie.com/wp-content/uploads/2026/03/Media-Mauricie_logo_coul.png" alt="Média Mauricie">
  <div class="footer-info">
    <a href="https://www.mediamauricie.com">www.mediamauricie.com</a> · <a href="/cdn-cgi/l/email-protection#8de4e3ebe2cde0e8e9e4ece0ecf8ffe4eee4e8a3eee2e0"><span class="__cf_email__" data-cfemail="84edeae2ebc4e9e1e0ede5e9e5f1f6ede7ede1aae7ebe9">[email&#160;protected]</span></a> · (819) 852-0851<br>
    © Média Mauricie Inc. 2026 · Prix sujets à changement
  </div>
</div>

<div class="mel">
  <div class="mel-hero">
    <div class="mel-left">
      <div class="mel-eyebrow">✨ Offre exclusive · Plateforme régionale</div>
      <div class="mel-title">Mauricie en lumière ✨</div>
      <div class="mel-desc">Vos photos rejoignent une banque de visuels professionnels accessible aux médias, entreprises et organismes de la Mauricie. <strong>Aucun effort de votre part</strong> — notre équipe sélectionne les images. Une simple décharge suffit.</div>
    </div>
    <div class="mel-right">
      <div class="mel-badge"><div class="mel-amount">−50$</div><div class="mel-badge-label">/ mois sur votre forfait</div></div>
      <a href="https://www.mediamauricie.com/mauricie-en-lumiere" target="_blank" class="mel-btn">Découvrir la plateforme →</a>
    </div>
  </div>
  <div class="mel-steps">
    <div class="mel-step"><span class="mel-num">1</span>Signature d'une décharge d'utilisation d'images sélectionnées</div>
    <div class="mel-step"><span class="mel-num">2</span>Notre équipe intègre les images choisies dans la banque régionale</div>
    <div class="mel-step"><span class="mel-num">3</span>Le rabais de 50$/mois est appliqué dès le mois suivant</div>
  </div>
</div>

<div class="eyebrow">Conditions, modalités & clauses importantes</div>
<div class="notes">
  <div class="note-bloc dark">
    <div class="note-bloc-title">Contrat & facturation</div>
    <div class="note-grid">
      <div class="note-item"><span class="ni">✓</span><span><strong>Contrat signé + dépôt requis</strong> avant le démarrage. 2 premiers mois facturés à la signature, puis aux 2 mois.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Annulation :</strong> préavis 30 jours par écrit. Aucun remboursement sur mois produits ou en cours.</span></div>
    </div>
  </div>
  <div class="note-bloc light">
    <div class="note-bloc-title">Livraison & révisions</div>
    <div class="note-grid">
      <div class="note-item"><span class="ni">✓</span><span><strong>1 révision mineure incluse</strong> par livraison. Révisions majeures via banques d'heures ou 100$/h.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Stockage inclus</strong> pendant le contrat + 6 mois après. Prolongation sur demande.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Reports & intempéries :</strong> tournages reportés sans frais en cas de circonstances exceptionnelles.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Pouvoir décisionnel :</strong> concepts développés en collaboration — vous conservez le dernier mot.</span></div>
    </div>
  </div>
  <div class="note-bloc mid">
    <div class="note-bloc-title">Droits & licences</div>
    <div class="note-grid">
      <div class="note-item"><span class="ni">✓</span><span><strong>Droits commerciaux illimités</strong> — réseaux sociaux, pub payante, web, affichage, imprimé. Média Mauricie conserve le droit de portfolio. <a href="https://mediamauricie.com/remise-des-fichiers-bruts" target="_blank" class="note-link">Conditions complètes →</a></span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Musique sous licence</strong> banque Média Mauricie incluse. Musique client acceptée — droits & licences à sa charge.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Fichiers bruts LOG</strong> disponibles séparément. <a href="https://mediamauricie.com/remise-des-fichiers-bruts" target="_blank" class="note-link">Voir offres →</a></span></div>
    </div>
  </div>
  <div class="note-bloc light">
    <div class="note-bloc-title">Opérations & logistique</div>
    <div class="note-grid">
      <div class="note-item"><span class="ni">✓</span><span><strong>Drone :</strong> inclus selon les conditions météo, réglementations Transport Canada et la nature du tournage. Permis zone avancée sur demande.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Assurances :</strong> responsabilité civile professionnelle complète — photo, vidéo & drone (police distincte).</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Permis de tournage :</strong> autorisations spéciales à la charge du client.</span></div>
      <div class="note-item"><span class="ni">✓</span><span><strong>Accès au site & coordination</strong> avec le personnel sur place — à la charge du client.</span></div>
    </div>
  </div>
</div>

<div class="clauses">
  <div class="clauses-label">Clauses spécifiques — Clients hors zone / longue distance</div>
  <div class="clause-item"><span class="ni">→</span><span><strong>Déplacement hors zone :</strong> +1$/km A/R. Facturé séparément ou intégré à la soumission.</span></div>
  <div class="clause-item"><span class="ni">→</span><span><strong>Hébergement & repas :</strong> entente séparée pour tournages nécessitant une nuitée.</span></div>
  <div class="clause-item"><span class="ni">→</span><span><strong>Accès au site :</strong> coordination et accès aux installations à la charge du client.</span></div>
  <div class="clause-item"><span class="ni">→</span><span><strong>Événements saisonniers :</strong> demandes spéciales à communiquer lors de la rencontre de planification mensuelle.</span></div>
</div>

<div class="eyebrow">Tableau récapitulatif</div>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:14px;" class="recap-grid">

  <!-- Essentiel -->
  <div style="background:#fff;border:1.5px solid #e0e0e0;border-radius:14px;overflow:hidden;">
    <div style="background:#2d2d2d;padding:14px 18px;">
      <div style="font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.4);margin-bottom:6px;">Forfait</div>
      <div style="font-size:16px;font-weight:800;color:#fff;line-height:1.2;">Essentiel</div>
      <div style="font-size:20px;font-weight:800;color:#fff;letter-spacing:-1px;margin-top:2px;">2 000$ <span style="font-size:10px;font-weight:600;color:rgba(255,255,255,.45);">/ mois</span></div>
    </div>
    <div style="padding:12px 18px;display:flex;flex-direction:column;gap:0;">
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Photos HD retouchées</div><div style="font-size:13px;font-weight:800;color:#2d2d2d;">25 photos</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Reels cinématiques</div><div style="font-size:13px;font-weight:800;color:#2d2d2d;">3×15s ou 1×30s + 1×15s</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Tournage sur place</div><div style="font-size:13px;font-weight:800;color:#2d2d2d;">2h</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Drone</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Stockage Pixpa + Dropbox</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">ClickUp — gestion projet</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Révision mineure</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Montages additionnels</div><a href="https://www.mediamauricie.com/banques-dheures" target="_blank" style="display:inline-block;margin-top:4px;font-size:9px;font-weight:800;letter-spacing:1px;text-transform:uppercase;background:#2d2d2d;color:#fff !important;padding:5px 10px;border-radius:5px;text-decoration:none;">Banques d'heures →</a></div>
      <div style="padding:10px 0;background:#eafaf2;border-radius:6px;margin-top:2px;padding:10px 10px;"><div style="font-size:10px;font-weight:600;color:#1a7a4a;margin-bottom:2px;">Transport Mauricie</div><div style="font-size:13px;font-weight:800;color:#1a7a4a;">✓ Inclus</div></div>
    </div>
  </div>

  <!-- Pro -->
  <div style="background:#fff;border:1.5px solid #e0e0e0;border-top:3px solid #c0392b;border-radius:14px;overflow:hidden;">
    <div style="background:#2d2d2d;padding:14px 18px;">
      <div style="font-size:8px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.4);margin-bottom:6px;">Forfait</div>
      <div style="font-size:16px;font-weight:800;color:#fff;line-height:1.2;">Pro</div>
      <div style="font-size:20px;font-weight:800;color:#fff;letter-spacing:-1px;margin-top:2px;">3 500$ <span style="font-size:10px;font-weight:600;color:rgba(255,255,255,.45);">/ mois</span></div>
    </div>
    <div style="padding:12px 18px;display:flex;flex-direction:column;gap:0;">
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Photos HD retouchées</div><div style="font-size:13px;font-weight:800;color:#c0392b;">50 photos</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Reels cinématiques</div><div style="font-size:13px;font-weight:800;color:#c0392b;">4×15s & 1×30s</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Tournage sur place</div><div style="font-size:13px;font-weight:800;color:#c0392b;">4h</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Drone</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Stockage Pixpa + Dropbox</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">ClickUp — gestion projet</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Révision mineure</div><div style="font-size:13px;font-weight:800;color:#27ae60;">✓ Inclus</div></div>
      <div style="padding:10px 0;border-bottom:1px solid #f0f0f0;"><div style="font-size:10px;font-weight:600;color:#999;margin-bottom:2px;">Montages additionnels</div><a href="https://www.mediamauricie.com/banques-dheures" target="_blank" style="display:inline-block;margin-top:4px;font-size:9px;font-weight:800;letter-spacing:1px;text-transform:uppercase;background:#2d2d2d;color:#fff !important;padding:5px 10px;border-radius:5px;text-decoration:none;">Banques d'heures →</a></div>
      <div style="padding:10px 0;background:#eafaf2;border-radius:6px;margin-top:2px;padding:10px 10px;"><div style="font-size:10px;font-weight:600;color:#1a7a4a;margin-bottom:2px;">Transport Mauricie</div><div style="font-size:13px;font-weight:800;color:#1a7a4a;">✓ Inclus</div></div>
    </div>
  </div>

</div>
<!-- Note engagement -->
<div style="background:#2d2d2d;border-radius:8px;padding:10px 18px;margin-bottom:14px;font-size:10px;font-weight:600;color:rgba(255,255,255,.5);text-align:center;">
  Engagement min. 3 mois · + taxes applicables &nbsp;·&nbsp;
  <a href="https://www.mediamauricie.com/banques-dheures" target="_blank" style="color:#fff !important;text-decoration:none;font-weight:800;">🎬 Banques d'heures →</a> &nbsp;·&nbsp;
  <a href="https://www.mediamauricie.com/gestion-reseaux-sociaux" target="_blank" style="color:#fff !important;text-decoration:none;font-weight:800;">📱 Réseaux sociaux →</a>
</div>



<div class="taxes">Tous les prix <strong>+ taxes applicables</strong> · © Média Mauricie Inc. 2026</div>
<div class="footer">
  <img src="https://mediamauricie.com/wp-content/uploads/2026/03/Media-Mauricie_logo_coul.png" alt="Média Mauricie">
  <div class="footer-info">
    <a href="https://www.mediamauricie.com">www.mediamauricie.com</a> · <a href="/cdn-cgi/l/email-protection#3c55525a537c

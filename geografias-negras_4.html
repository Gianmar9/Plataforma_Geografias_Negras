<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Geografías Negras</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400;1,600&family=Jost:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --cream: #F5F0E8;
    --cream-dark: #EDE6D6;
    --brown-deep: #3D2B1F;
    --brown-mid: #6B4A32;
    --brown-light: #A0785A;
    --brown-warm: #8B6347;
    --sand: #C9B99A;
    --green-finca: #5A7A4A;
    --green-light: #7A9B6A;
    --blue-river: #4A7A9B;
    --gray-urban: #8A8A8A;
    --overlay-dark: rgba(30,18,10,0.55);
    --overlay-modal: rgba(30,18,10,0.7);
    --sidebar-w: 260px;
    --navbar-h: 56px;
    --subbar-h: 44px;
    --footer-h: 48px;
  }

  * { margin:0; padding:0; box-sizing:border-box; }

  body {
    font-family: 'Jost', sans-serif;
    background: var(--cream);
    color: var(--brown-deep);
    height: 100vh;
    overflow: hidden;
  }

  /* ──────────────── NAVBAR ──────────────── */
  #navbar {
    position: fixed; top:0; left:0; right:0; z-index:1000;
    height: var(--navbar-h);
    background: var(--brown-deep);
    display: flex; align-items: stretch;
    border-bottom: 2px solid var(--brown-mid);
  }
  .nav-logo {
    display:flex; align-items:center; gap:10px;
    padding: 0 18px;
    cursor:pointer;
    border-right: 1px solid var(--brown-mid);
    transition: background .2s;
    text-decoration:none;
  }
  .nav-logo:hover { background: rgba(255,255,255,.06); }
  .nav-logo-icon {
    width:34px; height:34px; border-radius:50%;
    background: var(--brown-mid);
    display:flex; align-items:center; justify-content:center;
    font-size:16px; border: 2px solid var(--sand);
  }
  .nav-logo span {
    font-family:'Cormorant Garamond',serif;
    font-size:17px; font-weight:600; letter-spacing:.5px;
    color:var(--cream);
  }
  .nav-items { display:flex; align-items:stretch; flex:1; }
  .nav-item {
    display:flex; align-items:center; gap:6px;
    padding: 0 18px;
    font-size:11px; font-weight:500; letter-spacing:1.2px;
    text-transform:uppercase; color:var(--sand);
    cursor:pointer; border-right: 1px solid rgba(255,255,255,.06);
    transition: all .2s; position:relative;
    white-space:nowrap;
  }
  .nav-item:hover, .nav-item.active { color:var(--cream); background: rgba(255,255,255,.07); }
  .nav-item .arrow-icon { font-size:8px; opacity:.7; }
  /* dropdown */
  .nav-dropdown {
    position:absolute; top:100%; left:0;
    background: var(--brown-deep);
    border: 1px solid var(--brown-mid);
    border-top:none; min-width:220px;
    display:none; flex-direction:column;
    z-index:2000;
    box-shadow: 0 8px 24px rgba(0,0,0,.4);
  }
  .nav-item:hover .nav-dropdown { display:flex; }
  .nav-dropdown-item {
    padding:10px 16px;
    font-size:11px; letter-spacing:.8px; text-transform:uppercase;
    color:var(--sand); cursor:pointer;
    border-bottom: 1px solid rgba(255,255,255,.05);
    transition: all .15s;
    display:flex; align-items:center; gap:8px;
  }
  .nav-dropdown-item:hover { color:var(--cream); background:rgba(255,255,255,.06); padding-left:22px; }
  .nav-dropdown-item .sub-arrow { font-size:8px; opacity:.5; }

  /* ──────────────── SUB-HEADER (section pages) ──────────────── */
  #subheader {
    position:fixed; top:var(--navbar-h); left:0; right:0; z-index:900;
    height:var(--subbar-h);
    background: var(--cream-dark);
    border-bottom: 1px solid var(--sand);
    display:none; align-items:center; gap:12px;
    padding: 0 20px;
  }
  .subheader-icon { width:28px; height:28px; border-radius:50%; background:var(--brown-light); display:flex; align-items:center; justify-content:center; font-size:14px; }
  .subheader-title { font-family:'Cormorant Garamond',serif; font-size:18px; font-weight:600; color:var(--brown-deep); }

  /* ──────────────── FOOTER BAR ──────────────── */
  #footerbar {
    position:fixed; bottom:0; left:0; right:0; z-index:1000;
    height:var(--footer-h);
    background: var(--brown-deep);
    display:flex; align-items:center; justify-content:space-between;
    padding: 0 20px;
    border-top: 1px solid var(--brown-mid);
  }
  .footer-btn {
    display:flex; align-items:center; gap:8px;
    padding:6px 14px; border:1px solid var(--brown-mid);
    background:transparent; color:var(--cream); cursor:pointer;
    font-family:'Jost',sans-serif; font-size:11px; letter-spacing:1px;
    text-transform:uppercase; transition:all .2s; border-radius:2px;
  }
  .footer-btn:hover { background:var(--brown-mid); }
  .footer-btn .btn-icon { font-size:14px; }
  .timeline-dots { display:flex; gap:4px; align-items:center; }
  .tdot { width:10px; height:8px; border:1px solid var(--sand); border-radius:1px; }

  /* ──────────────── MAIN CONTENT AREA ──────────────── */
  #content {
    position:fixed;
    top:var(--navbar-h); left:0; right:0; bottom:var(--footer-h);
    overflow:hidden;
  }
  #content.with-subheader { top: calc(var(--navbar-h) + var(--subbar-h)); }

  /* ──────────────── SCREENS ──────────────── */
  .screen { position:absolute; inset:0; display:none; overflow:hidden; }
  .screen.active { display:block; }

  /* BG image wrapper */
  .screen-bg {
    position:absolute; inset:0;
    background-size:cover; background-position:center;
    background-color: #2a1a10; /* placeholder dark until image loads */
  }
  .screen-bg::after {
    content:''; position:absolute; inset:0;
    background: linear-gradient(to bottom, rgba(20,12,6,.4) 0%, rgba(20,12,6,.2) 60%, rgba(20,12,6,.5) 100%);
  }
  .bg-placeholder { width:100%; height:100%; display:flex; align-items:center; justify-content:center; font-size:13px; color:rgba(255,255,255,.3); letter-spacing:1px; text-transform:uppercase; }

  /* ──────────────── HOME SCREEN ──────────────── */
  #screen-home .screen-bg {
    background-color: #1e1208;
  }
  .home-sidebar {
    position:absolute; left:20px; top:50%; transform:translateY(-50%);
    z-index:10; display:flex; flex-direction:column; gap:10px;
  }
  .consejo-btn {
    display:flex; align-items:center; gap:10px;
    padding:10px 16px; min-width:200px;
    background: rgba(245,240,232,.12); backdrop-filter:blur(8px);
    border:1px solid rgba(245,240,232,.25); border-radius:3px;
    cursor:pointer; transition:all .22s; color:var(--cream);
  }
  .consejo-btn:hover {
    background:rgba(245,240,232,.22); border-color:rgba(245,240,232,.5);
    transform: translateX(4px);
  }
  .consejo-icon { width:32px; height:32px; border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:15px; flex-shrink:0; }
  .consejo-btn span { font-size:12px; letter-spacing:.6px; }

  /* Map pins */
  .map-pins { position:absolute; inset:0; z-index:5; pointer-events:none; }
  .pin {
    position:absolute; pointer-events:all; cursor:pointer;
    display:flex; align-items:center; gap:6px;
  }
  .pin-dot {
    width:22px; height:22px; border-radius:50%;
    border:2px solid rgba(255,255,255,.8);
    display:flex; align-items:center; justify-content:center;
    font-size:9px; transition:all .2s;
    box-shadow: 0 2px 8px rgba(0,0,0,.4);
  }
  .pin:hover .pin-dot { transform:scale(1.2); }
  .pin-label {
    background:rgba(245,240,232,.9); color:var(--brown-deep);
    padding:4px 10px; font-size:11px; letter-spacing:.5px; border-radius:2px;
    box-shadow:0 2px 8px rgba(0,0,0,.3);
    white-space:nowrap;
  }
  .pin-arrow { width:0; height:0; border-left:5px solid transparent; border-right:5px solid transparent; border-top:8px solid rgba(245,240,232,.9); position:absolute; bottom:-8px; left:50%; transform:translateX(-50%); display:none; }

  /* Colombia mini-map */
  .minimap {
    position:absolute; top:12px; right:20px; z-index:10;
    width:150px; height:150px; border-radius:50%;
    border: 2px solid rgba(200,180,150,.5);
    overflow:hidden; background:rgba(245,240,232,.1); backdrop-filter:blur(4px);
  }
  .minimap svg { width:100%; height:100%; }

  /* ──────────────── CONSEJO SCREEN ──────────────── */
  .consejo-screen .screen-bg {
    background-color: #1a2810;
    position: absolute;
    inset: 0;
    overflow: hidden;
  }
  #consejo-bg-img {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }
  .consejo-title-area {
    position:absolute; inset:0; display:flex; align-items:above; justify-content:center;
    z-index:5;
  }
  .consejo-title-inner { text-align:center; color:var(--cream); }
  .consejo-title-inner .subtitle { font-size:13px; letter-spacing:3px; text-transform:uppercase; opacity:.8; margin-bottom:8px; }
  .consejo-title-inner h1 { font-family:'Cormorant Garamond',serif; font-size:80px; font-weight:300; line-height:1; letter-spacing:-1px; }

  .consejo-tab-bar {
    position:absolute; bottom: 0; left:50%; transform:translateX(-50%);
    z-index:20; display:flex; gap:2px;
  }
  .ctab {
    display:flex; align-items:center; gap:8px;
    padding:10px 28px; background:rgba(30,18,10,.7); backdrop-filter:blur(8px);
    border:1px solid rgba(200,170,130,.2); color:var(--sand);
    cursor:pointer; font-size:11px; letter-spacing:1px; text-transform:uppercase;
    transition:all .2s;
  }
  .ctab:hover, .ctab.active { background:rgba(245,240,232,.15); color:var(--cream); border-color:rgba(200,170,130,.5); }
  .ctab-icon { font-size:16px; }

  /* Consejo side panel */
  .consejo-panel {
    position:absolute; right:0; top:0; bottom:0; width:44%;
    background:var(--cream); z-index:15; overflow-y:auto;
    transform:translateX(100%); transition:transform .35s ease;
    box-shadow:-4px 0 24px rgba(0,0,0,.3);
  }
  .consejo-panel.open { transform:translateX(0); }
  .panel-close {
    position:absolute; top:14px; right:14px;
    width:32px; height:32px; border-radius:50%;
    background:var(--brown-deep); color:var(--cream);
    border:none; cursor:pointer; font-size:16px;
    display:flex; align-items:center; justify-content:center;
    z-index:5;
  }
  .panel-header {
    padding:28px 28px 16px;
    border-bottom:1px solid var(--sand);
  }
  .panel-title { font-family:'Cormorant Garamond',serif; font-size:28px; color:var(--brown-deep); }
  .panel-body { padding:24px 28px; }

  /* Location card */
  .location-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:4px; padding:16px; margin-bottom:20px; }
  .location-card .map-placeholder { height:240px; background:var(--sand); border-radius:3px; display:flex; align-items:center; justify-content:center; font-size:28px; margin-bottom:12px; overflow:hidden; }
  .location-card .map-placeholder img { width:100%; height:100%; object-fit:cover; border-radius:3px; }
  .location-coords { font-size:12px; color:var(--brown-light); margin-bottom:10px; letter-spacing:.5px; }
  .location-text { font-size:13px; line-height:1.7; color:var(--brown-deep); }

  .panel-section-title { font-family:'Cormorant Garamond',serif; font-size:20px; font-style:italic; color:var(--brown-mid); margin-bottom:12px; }

  /* Audio player */
  .audio-card { background:var(--brown-deep); border-radius:4px; overflow:hidden; margin-bottom:16px; }
  .audio-wave { height:80px; background: linear-gradient(135deg, var(--brown-mid), var(--brown-deep)); display:flex; align-items:center; justify-content:center; position:relative; }
  .audio-wave-title { font-family:'Cormorant Garamond',serif; font-style:italic; font-size:18px; color:var(--sand); }
  .wave-bars { display:flex; align-items:center; gap:2px; position:absolute; bottom:10px; left:50%; transform:translateX(-50%); }
  .wave-bar { width:3px; background:rgba(200,180,150,.4); border-radius:2px; }
  .audio-controls { padding:12px 16px; }
  .audio-track { display:flex; align-items:center; gap:10px; }
  .play-btn { width:32px; height:32px; border-radius:50%; background:var(--brown-light); border:none; cursor:pointer; display:flex; align-items:center; justify-content:center; color:white; font-size:12px; transition:all .2s; }
  .play-btn:hover { background:var(--brown-warm); }
  .track-info { flex:1; }
  .track-name { font-size:12px; color:var(--cream); letter-spacing:.5px; }
  .track-time { font-size:11px; color:var(--sand); }
  .track-progress { height:2px; background:rgba(255,255,255,.2); border-radius:1px; margin-top:6px; }
  .track-fill { height:100%; width:0%; background:var(--brown-light); border-radius:1px; }
  .fragment-text { font-size:12px; line-height:1.7; color:var(--brown-deep); font-style:italic; border-left:3px solid var(--brown-light); padding-left:12px; margin-top:12px; }

  /* Image gallery */
  .gallery-main { position:relative; background:var(--brown-mid); border-radius:4px; overflow:hidden; height:320px; margin-bottom:8px; display:flex; align-items:center; justify-content:center; }
  .gallery-main img { width:100%; height:100%; object-fit:cover; display:block; }
  .gallery-placeholder { font-family:'Cormorant Garamond',serif; font-style:italic; font-size:20px; color:rgba(245,240,232,.4); }
  .gallery-nav { position:absolute; top:50%; transform:translateY(-50%); width:32px; height:32px; background:rgba(30,18,10,.5); border:none; color:white; cursor:pointer; border-radius:2px; display:flex; align-items:center; justify-content:center; font-size:16px; }
  .gallery-nav.prev { left:8px; }
  .gallery-nav.next { right:8px; }
  .gallery-expand { position:absolute; bottom:8px; right:8px; width:24px; height:24px; background:rgba(30,18,10,.5); border:none; color:white; cursor:pointer; border-radius:2px; font-size:12px; }
  .gallery-caption { font-size:11px; color:var(--brown-light); letter-spacing:.5px; }

  /* ──────────────── FINCA SCREEN ──────────────── */
  #screen-finca .screen-bg {
    /* REEMPLAZA CON: background-image: url('tu-imagen-finca.jpg'); */
    background-image: url(la\ finca\ tradicional.png);
  }
  .finca-layout { position:absolute; inset:0; display:flex; }
  .finca-sidebar {
    width:var(--sidebar-w); background:var(--cream); border-right:1px solid var(--sand);
    overflow-y:auto; z-index:10; padding-bottom:20px;
    flex-shrink:0;
  }
  .sidebar-section { border-bottom:1px solid var(--sand); }
  .sidebar-section-header {
    display:flex; align-items:center; gap:10px;
    padding:14px 16px; cursor:pointer;
    font-size:11px; letter-spacing:1px; text-transform:uppercase;
    font-weight:600; color:var(--brown-mid);
  }
  .sidebar-section-icon { width:28px; height:28px; border-radius:50%; background:var(--cream-dark); display:flex; align-items:center; justify-content:center; font-size:13px; }
  .sidebar-item {
    display:flex; align-items:center; gap:10px;
    padding:8px 16px 8px 24px; cursor:pointer;
    font-size:12px; color:var(--brown-deep); transition:all .15s;
  }
  .sidebar-item:hover { background:var(--cream-dark); color:var(--brown-mid); }
  .sidebar-item.active { color:var(--brown-mid); font-weight:600; }
  .sidebar-radio { width:14px; height:14px; border-radius:50%; border:2px solid var(--sand); flex-shrink:0; display:flex; align-items:center; justify-content:center; }
  .sidebar-radio.checked::after { content:''; width:6px; height:6px; border-radius:50%; background:var(--green-finca); display:block; }

  .sidebar-btn {
    display:flex; align-items:center; gap:10px;
    padding:12px 16px; cursor:pointer; transition:all .2s;
    border:1px solid var(--sand); margin:8px 12px; border-radius:3px;
  }
  .sidebar-btn:hover { background:var(--cream-dark); }
  .sidebar-btn-label { font-size:11px; font-weight:600; letter-spacing:.8px; text-transform:uppercase; color:var(--brown-mid); }
  .sidebar-btn-sub { font-size:11px; color:var(--brown-light); }

  .finca-map-area { flex:1; position:relative; background:var(--cream-dark); overflow:hidden; }
  .finca-map-placeholder { position:absolute; inset:0; display:flex; align-items:center; justify-content:center; background:var(--cream-dark); }

  .finca-conventions { width:200px; background:var(--cream); border-left:1px solid var(--sand); padding:20px 16px; z-index:10; overflow-y:auto; flex-shrink:0; }
  .conv-title { font-family:'Cormorant Garamond',serif; font-style:italic; font-size:18px; color:var(--brown-deep); margin-bottom:16px; }
  .conv-item { display:flex; align-items:center; gap:10px; margin-bottom:12px; }
  .conv-color { width:22px; height:16px; border-radius:2px; flex-shrink:0; border:1px solid rgba(0,0,0,.1); }
  .conv-label { font-size:11px; color:var(--brown-deep); line-height:1.4; }

  /* Map pins finca */
  .finca-pins { position:absolute; inset:0; }
  .finca-pin {
    position:absolute; display:flex; flex-direction:column; align-items:center;
    cursor:pointer; pointer-events:all;
  }
  .finca-pin-label {
    background:white; border:1px solid var(--sand); border-radius:2px;
    padding:3px 8px; font-size:11px; white-space:nowrap; box-shadow:0 2px 6px rgba(0,0,0,.15);
    display:flex; align-items:center; gap:5px;
  }
  .finca-pin-dot { width:14px; height:14px; border-radius:50%; border:2px solid white; }

  /* Consejo popup in finca */
  .consejo-popup {
    position:absolute; background:var(--cream); border:1px solid var(--sand);
    border-radius:4px; z-index:20; width:520px;
    box-shadow:0 4px 24px rgba(0,0,0,.2);
    display:none;
  }
  .consejo-popup.open { display:block; }
  .popup-header { padding:14px 20px; border-bottom:1px solid var(--sand); }
  .popup-subtitle { font-size:11px; color:var(--brown-light); letter-spacing:1px; text-transform:uppercase; margin-bottom:2px; }
  .popup-title { font-family:'Cormorant Garamond',serif; font-size:22px; }
  .popup-tabs { display:flex; border-bottom:1px solid var(--sand); }
  .popup-tab {
    padding:8px 16px; font-size:11px; letter-spacing:.8px; text-transform:uppercase;
    cursor:pointer; color:var(--brown-light); border-bottom:2px solid transparent;
    display:flex; align-items:center; gap:6px; transition:all .15s;
  }
  .popup-tab:hover { color:var(--brown-mid); }
  .popup-tab.active { color:var(--brown-deep); border-bottom-color:var(--brown-mid); }
  .popup-body { padding:20px; max-height:380px; overflow-y:auto; }

  /* stats */
  .stat-chart-donut { display:flex; align-items:center; gap:20px; margin-bottom:16px; }
  .donut-placeholder { width:80px; height:80px; border-radius:50%; background: conic-gradient(var(--brown-mid) 0% 55%, var(--sand) 55% 80%, #8B7355 80% 95%, #5A4030 95% 100%); display:flex; align-items:center; justify-content:center; }
  .donut-hole { width:48px; height:48px; border-radius:50%; background:var(--cream); }
  .donut-legend { display:flex; flex-direction:column; gap:5px; }
  .legend-item { display:flex; align-items:center; gap:8px; font-size:11px; color:var(--brown-deep); }
  .legend-dot { width:10px; height:10px; border-radius:2px; flex-shrink:0; }

  .bar-chart { margin-bottom:16px; }
  .bar-item { display:flex; align-items:center; gap:8px; margin-bottom:8px; }
  .bar-label { font-size:11px; color:var(--brown-deep); width:80px; flex-shrink:0; }
  .bar-track { flex:1; height:8px; background:var(--cream-dark); border-radius:4px; overflow:hidden; }
  .bar-fill { height:100%; border-radius:4px; }
  .bar-pct { font-size:11px; color:var(--brown-light); width:30px; text-align:right; }

  /* comparator — EFECTO CORTINA FUNCIONAL */
  .comparator {
    position:absolute; inset:0; z-index:25; display:none;
    background:#1a1208; flex-direction:column;
  }
  .comparator.open { display:flex; }
  .comp-area { flex:1; position:relative; overflow:hidden; user-select:none; }

  /* Las dos imágenes del comparador */
  .comp-img-left,
  .comp-img-right {
    position:absolute; inset:0;
    background-size:cover; background-position:center;
  }
  /* La imagen derecha se recorta con clip-path según el slider */
  .comp-img-right { clip-path: inset(0 0 0 50%); }

  /* Colores de fondo por defecto (hasta que pongas imágenes reales) */
  .comp-img-left  { background-color:#6B4A32; }
  .comp-img-right { background-color:#3D6B3D; }

  /* Etiquetas de año */
  .comp-label-left,
  .comp-label-right {
    position:absolute; top:16px; z-index:4;
    background:rgba(245,240,232,.92); border:1px solid var(--sand);
    padding:8px 18px; border-radius:3px; pointer-events:none;
  }
  .comp-label-left  { left:16px; }
  .comp-label-right { right:16px; }
  .comp-label-left h3, .comp-label-right h3 { font-family:'Cormorant Garamond',serif; font-style:italic; font-size:20px; color:var(--brown-deep); }
  .comp-label-left p,  .comp-label-right p  { font-size:11px; color:var(--brown-light); }

  /* Línea divisoria + manija */
  .comp-divider {
    position:absolute; top:0; bottom:0; z-index:5;
    width:3px; background:white;
    transform:translateX(-50%);
    left:50%;
    cursor:ew-resize;
    box-shadow:0 0 12px rgba(0,0,0,.5);
  }
  .comp-handle {
    position:absolute; top:50%; left:50%;
    transform:translate(-50%,-50%);
    width:46px; height:46px; border-radius:50%;
    background:white; box-shadow:0 2px 14px rgba(0,0,0,.35);
    display:flex; align-items:center; justify-content:center;
    cursor:ew-resize; font-size:15px; color:var(--brown-mid);
    border:2px solid var(--sand);
  }

  .comp-footer { padding:10px 20px; background:var(--brown-deep); display:flex; align-items:center; gap:20px; flex-shrink:0; }
  .comp-legend-item { display:flex; align-items:center; gap:6px; font-size:11px; color:var(--sand); }
  .comp-legend-color { width:16px; height:10px; border-radius:2px; }
  .comp-close-btn { margin-left:auto; background:transparent; border:1px solid var(--sand); color:var(--cream); padding:5px 14px; cursor:pointer; font-size:11px; letter-spacing:.8px; border-radius:2px; }

  /* ──────────────── RIO HUMEDALES SCREEN ──────────────── */
  #screen-rio .screen-bg {
    /* REEMPLAZA CON: background-image: url('tu-imagen-rio.jpg'); */
    background-image: url(rio\ cauca\ y\ huemedales.png);
  }
  .rio-layout { position:absolute; inset:0; display:flex; }

  /* ──────────────── QUIENES SOMOS / CONTRAMAPEO / RECURSOS (text sections) ──────────────── */
  .text-screen { position:absolute; inset:0; display:flex; }
  .text-sidebar {
    width:var(--sidebar-w); background:var(--cream); border-right:1px solid var(--sand);
    overflow-y:auto; padding:20px 0; flex-shrink:0;
  }
  .text-sidebar-brand { padding:16px 16px 20px; border-bottom:1px solid var(--sand); margin-bottom:4px; }
  .text-sidebar-brand .brand-name { font-family:'Cormorant Garamond',serif; font-size:22px; line-height:1.2; color:var(--brown-deep); }
  .text-sidebar-brand .brand-tagline { font-size:11px; color:var(--brown-light); line-height:1.5; margin-top:4px; }
  .text-nav-group { border-bottom:1px solid var(--cream-dark); padding:6px 0; }
  .text-nav-item {
    display:flex; align-items:center; gap:10px;
    padding:10px 16px; cursor:pointer; transition:all .15s;
    color:var(--brown-deep);
  }
  .text-nav-item:hover { background:var(--cream-dark); }
  .text-nav-item.active { background:var(--cream-dark); font-weight:600; }
  .text-nav-icon { width:30px; height:30px; border-radius:50%; background:var(--cream-dark); display:flex; align-items:center; justify-content:center; font-size:14px; flex-shrink:0; }
  .text-nav-label { font-size:12px; }
  .text-nav-sub { font-size:10px; color:var(--brown-light); }
  .institutions-row { display:flex; gap:10px; align-items:center; flex-wrap:wrap; padding:16px; }
  .inst-badge { background:var(--brown-deep); color:var(--cream); padding:5px 10px; border-radius:2px; font-size:10px; letter-spacing:.5px; font-weight:600; }

  .text-main { flex:1; overflow-y:auto; padding:30px 40px; background:var(--cream); }
  .section-tag { font-size:10px; letter-spacing:2px; text-transform:uppercase; color:var(--brown-light); margin-bottom:8px; display:flex; align-items:center; gap:8px; }
  .section-tag::before { content:'——'; }
  .section-heading { font-family:'Cormorant Garamond',serif; font-size:34px; font-style:italic; color:var(--brown-deep); margin-bottom:6px; }
  .section-subheading { font-size:12px; letter-spacing:1.5px; text-transform:uppercase; color:var(--brown-light); margin-bottom:24px; }
  .section-body { font-size:14px; line-height:1.8; color:var(--brown-deep); max-width:680px; }
  .section-body p { margin-bottom:16px; }

  /* Stats row */
  .stats-row { display:flex; gap:16px; margin-bottom:28px; }
  .stat-card { flex:1; background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:20px; }
  .stat-number { font-family:'Cormorant Garamond',serif; font-size:48px; font-weight:300; color:var(--brown-deep); line-height:1; }
  .stat-label { font-size:10px; letter-spacing:1.5px; text-transform:uppercase; color:var(--brown-light); margin-top:4px; }
  .stat-desc { font-size:11px; color:var(--brown-mid); margin-top:8px; line-height:1.5; }

  .video-placeholder { background:var(--sand); border-radius:4px; height:280px; max-width:560px; display:flex; align-items:center; justify-content:center; cursor:pointer; position:relative; overflow:hidden; }
  .video-placeholder img { width:100%; height:100%; object-fit:cover; position:absolute; inset:0; }
  .video-play { width:60px; height:60px; border-radius:50%; background:rgba(30,18,10,.65); display:flex; align-items:center; justify-content:center; font-size:24px; color:white; position:relative; z-index:1; }
  .video-caption { font-size:12px; color:var(--brown-light); margin-top:8px; }

  /* Consejos community cards */
  .community-grid { display:grid; grid-template-columns:1fr 1fr; gap:12px; margin-bottom:24px; max-width:680px; }
  .community-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:16px; }
  .community-card .cc-header { display:flex; align-items:center; gap:8px; margin-bottom:8px; }
  .cc-dot { width:14px; height:14px; border-radius:50%; }
  .cc-name { font-family:'Cormorant Garamond',serif; font-size:18px; color:var(--brown-deep); }
  .cc-desc { font-size:11px; color:var(--brown-mid); line-height:1.6; }

  /* Team grid */
  .team-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:8px; margin-bottom:20px; }
  .team-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:14px; }
  .team-name { font-size:13px; font-weight:600; color:var(--brown-deep); margin-bottom:2px; }
  .team-role { font-size:10px; color:var(--brown-light); letter-spacing:.5px; }
  .team-section-label { font-size:10px; text-transform:uppercase; letter-spacing:1px; color:var(--brown-light); margin-bottom:8px; margin-top:16px; padding-bottom:4px; border-bottom:1px solid var(--sand); }
  .community-banner { background:var(--brown-deep); color:var(--cream); padding:14px 20px; border-radius:3px; margin-bottom:20px; }
  .community-banner strong { display:block; font-size:13px; margin-bottom:4px; }
  .community-banner p { font-size:11px; color:var(--sand); line-height:1.5; }

  /* Taller tabs */
  .taller-list { display:flex; flex-direction:column; gap:0; }
  .taller-item {
    display:flex; align-items:center; gap:12px;
    padding:12px 16px; cursor:pointer; border-bottom:1px solid var(--cream-dark);
    transition:all .15s;
  }
  .taller-item:hover, .taller-item.active { background:var(--cream-dark); }
  .taller-num { width:32px; height:32px; border-radius:50%; background:var(--brown-light); color:white; display:flex; align-items:center; justify-content:center; font-size:12px; font-weight:600; flex-shrink:0; }
  .taller-item.active .taller-num { background:var(--brown-deep); }
  .taller-info .t-title { font-size:12px; font-weight:600; color:var(--brown-deep); }
  .taller-info .t-loc { font-size:10px; color:var(--brown-light); margin-top:2px; }

  .inner-tabs { display:flex; gap:0; border-bottom:1px solid var(--sand); margin-bottom:20px; }
  .inner-tab { padding:8px 16px; font-size:11px; letter-spacing:.8px; text-transform:uppercase; cursor:pointer; color:var(--brown-light); border-bottom:2px solid transparent; display:flex; align-items:center; gap:6px; transition:all .15s; }
  .inner-tab:hover { color:var(--brown-mid); }
  .inner-tab.active { color:var(--brown-deep); border-bottom-color:var(--brown-mid); }

  /* objectives grid */
  .obj-grid { display:grid; grid-template-columns:1fr 1fr; gap:10px; }
  .obj-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:14px; }
  .obj-num { font-family:'Cormorant Garamond',serif; font-size:22px; color:var(--brown-light); margin-bottom:6px; }
  .obj-text { font-size:12px; color:var(--brown-deep); line-height:1.6; }

  /* Results stats */
  .results-stats { display:flex; gap:12px; margin-bottom:20px; }
  .res-stat { flex:1; background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:16px; text-align:center; }
  .res-num { font-family:'Cormorant Garamond',serif; font-size:42px; color:var(--brown-deep); }
  .res-label { font-size:10px; text-transform:uppercase; letter-spacing:1px; color:var(--brown-light); }

  /* Normativa */
  .norm-key-findings { display:grid; grid-template-columns:1fr 1fr; gap:10px; margin-bottom:20px; }
  .finding-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:14px; }
  .finding-num { font-size:10px; font-weight:700; color:var(--brown-light); letter-spacing:1px; margin-bottom:6px; }
  .finding-text { font-size:12px; color:var(--brown-deep); line-height:1.6; }

  .norm-item { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:14px; margin-bottom:8px; display:flex; gap:14px; }
  .norm-name { font-family:'Cormorant Garamond',serif; font-style:italic; font-size:15px; color:var(--brown-mid); min-width:140px; flex-shrink:0; }
  .norm-desc { font-size:12px; color:var(--brown-deep); line-height:1.6; }

  /* References */
  .ref-item { border-bottom:1px solid var(--cream-dark); padding:16px 0; display:flex; gap:16px; }
  .ref-badge { background:var(--brown-light); color:white; padding:3px 8px; border-radius:2px; font-size:10px; letter-spacing:.5px; height:fit-content; flex-shrink:0; margin-top:3px; }
  .ref-content { flex:1; }
  .ref-title { font-size:14px; font-weight:600; color:var(--brown-deep); margin-bottom:3px; }
  .ref-author { font-size:12px; color:var(--brown-light); font-style:italic; margin-bottom:6px; }
  .ref-tags { display:flex; gap:6px; flex-wrap:wrap; margin-bottom:8px; }
  .ref-tag { background:var(--cream-dark); border:1px solid var(--sand); padding:2px 8px; border-radius:10px; font-size:10px; color:var(--brown-mid); }
  .ref-dl { display:flex; align-items:center; gap:6px; font-size:11px; color:var(--brown-mid); cursor:pointer; letter-spacing:.5px; text-transform:uppercase; }
  .ref-dl:hover { color:var(--brown-deep); }

  /* Download cards */
  .dl-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:12px; }
  .dl-card { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:16px; }
  .dl-icon-area { width:40px; height:40px; background:var(--cream); border:1px solid var(--sand); border-radius:3px; display:flex; align-items:center; justify-content:center; font-size:20px; margin-bottom:12px; }
  .dl-title { font-size:13px; font-weight:600; color:var(--brown-deep); margin-bottom:3px; }
  .dl-sub { font-size:11px; color:var(--brown-light); margin-bottom:8px; }
  .dl-meta { display:flex; justify-content:space-between; align-items:center; margin-bottom:10px; }
  .dl-format { font-size:10px; color:var(--brown-light); }
  .dl-size { font-size:10px; color:var(--brown-light); }
  .dl-btn { display:flex; align-items:center; gap:6px; font-size:11px; color:var(--brown-mid); cursor:pointer; letter-spacing:.5px; text-transform:uppercase; }
  .dl-btn:hover { color:var(--brown-deep); }

  /* Arma tu mapa */
  .map-builder { display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-bottom:16px; }
  .builder-section { background:var(--cream-dark); border:1px solid var(--sand); border-radius:3px; padding:20px; }
  .builder-num { font-family:'Cormorant Garamond',serif; font-size:28px; color:var(--brown-light); margin-bottom:8px; }
  .builder-title { font-size:10px; text-transform:uppercase; letter-spacing:1.5px; color:var(--brown-light); margin-bottom:14px; }
  .check-item { display:flex; align-items:center; justify-content:space-between; padding:8px 10px; background:white; border:1px solid var(--sand); border-radius:2px; margin-bottom:6px; font-size:12px; cursor:pointer; }
  .check-item:hover { border-color:var(--brown-light); }
  .check-box { width:16px; height:16px; border:2px solid var(--sand); border-radius:2px; display:flex; align-items:center; justify-content:center; }
  .check-box.checked { background:var(--green-finca); border-color:var(--green-finca); color:white; font-size:10px; }
  .check-dot { width:10px; height:10px; border-radius:50%; margin-right:8px; }
  .format-row { display:flex; gap:10px; }
  .format-btn { flex:1; padding:10px; background:white; border:2px solid var(--sand); border-radius:2px; font-family:'Cormorant Garamond',serif; font-size:22px; font-weight:600; cursor:pointer; text-align:center; color:var(--brown-deep); }
  .format-btn:hover, .format-btn.selected { border-color:var(--brown-mid); background:var(--brown-mid); color:white; }
  .summary-section { background:white; border:1px solid var(--sand); border-radius:3px; padding:16px; margin-bottom:16px; }
  .summary-row { display:flex; justify-content:space-between; font-size:12px; padding:4px 0; border-bottom:1px solid var(--cream-dark); }
  .summary-row:last-child { border:none; }
  .summary-key { color:var(--brown-light); }
  .summary-val { color:var(--brown-deep); font-weight:600; }
  .generate-btn { width:100%; padding:14px; background:var(--brown-deep); color:var(--cream); border:none; cursor:pointer; font-family:'Jost',sans-serif; font-size:12px; letter-spacing:2px; text-transform:uppercase; display:flex; align-items:center; justify-content:center; gap:10px; border-radius:3px; transition:all .2s; }
  .generate-btn:hover { background:var(--brown-mid); }

  /* ──────────────── MODAL ──────────────── */
  #modal-overlay {
    position:fixed; inset:0; z-index:5000;
    background:var(--overlay-modal);
    display:none; align-items:center; justify-content:center;
    backdrop-filter:blur(4px);
    padding: 20px;
  }
  #modal-overlay.open { display:flex; }
  .modal {
    background:var(--cream); max-width:820px; width:95%;
    max-height: 88vh;
    border-radius:6px; overflow:hidden;
    display:flex; flex-direction:column;
    box-shadow:0 24px 80px rgba(0,0,0,.6);
    animation: modalIn .3s ease;
  }
  @keyframes modalIn { from { transform:translateY(24px); opacity:0; } to { transform:translateY(0); opacity:1; } }
  .modal-header { padding:32px 40px 20px; text-align:center; border-bottom:2px solid var(--sand); position:relative; flex-shrink:0; }
  .modal-ornament { display:flex; align-items:center; justify-content:center; gap:14px; margin-bottom:14px; }
  .modal-ornament-line { width:70px; height:1px; background:var(--sand); }
  .modal-ornament-icon { width:44px; height:44px; border-radius:50%; background:var(--brown-light); display:flex; align-items:center; justify-content:center; font-size:20px; }
  .modal-title { font-family:'Cormorant Garamond',serif; font-size:38px; font-style:italic; color:var(--brown-deep); margin-bottom:6px; }
  .modal-divider { width:50px; height:2px; background:var(--sand); margin:14px auto 0; }
  .modal-close { position:absolute; top:14px; right:18px; background:transparent; border:none; font-size:26px; cursor:pointer; color:var(--brown-light); transition:color .2s; }
  .modal-close:hover { color:var(--brown-deep); }
  .modal-body { padding:30px 40px; font-size:16px; line-height:2; color:var(--brown-deep); overflow-y:auto; flex:1; }
  .modal-footer { padding:20px 40px 28px; border-top:1px solid var(--cream-dark); display:flex; justify-content:flex-end; flex-shrink:0; }
  .modal-explore-btn {
    display:flex; align-items:center; gap:12px;
    padding:12px 32px; background:transparent;
    border:2px solid var(--brown-mid); color:var(--brown-mid);
    cursor:pointer; font-family:'Jost',sans-serif;
    font-size:13px; letter-spacing:2px; text-transform:uppercase;
    transition:all .2s; border-radius:3px;
  }
  .modal-explore-btn:hover { background:var(--brown-deep); color:var(--cream); border-color:var(--brown-deep); }

  /* ──────────────── TUTORIAL MODAL ──────────────── */
  .tutorial-video { background:var(--brown-mid); height:300px; display:flex; align-items:center; justify-content:center; flex-direction:column; gap:14px; color:var(--cream); border-radius:4px; margin-bottom:16px; }
  .tutorial-play { width:72px; height:72px; border-radius:50%; border:2px solid var(--cream); display:flex; align-items:center; justify-content:center; font-size:28px; cursor:pointer; }
  .tutorial-label { font-size:14px; letter-spacing:1px; opacity:.8; }

  /* ──────────────── TIMELINE MODAL ──────────────── */
  .timeline-scroll { overflow-x:auto; padding:24px 0; }
  .timeline-track { display:flex; align-items:center; min-width:700px; }
  .tl-node { display:flex; flex-direction:column; align-items:center; flex-shrink:0; }
  .tl-circle { width:48px; height:48px; border-radius:50%; display:flex; align-items:center; justify-content:center; font-weight:700; font-size:14px; color:white; }
  .tl-line { flex:1; height:2px; min-width:30px; }
  .tl-events { display:flex; margin-top:18px; }
  .tl-event { text-align:center; padding:0 14px; }
  .tl-month { font-size:12px; font-weight:700; letter-spacing:.8px; color:var(--brown-mid); margin-bottom:5px; }
  .tl-title { font-size:13px; color:var(--brown-deep); line-height:1.4; }

  /* ──────────────── ACERCA MODAL ──────────────── */
  /* same as modal */

  /* ──────────────── OVERLAY LAYERS ──────────────── */
  .overlay-layer {
    position:absolute; inset:0; z-index:2;
    width:100%; height:100%; object-fit:cover;
    opacity:0; transition: opacity .35s ease;
    pointer-events:none;
  }
  .overlay-layer.visible { opacity:1; }

  /* Info icon for variables */
  .var-info-icon {
    width:18px; height:18px; border-radius:50%;
    background:var(--brown-light); color:white;
    display:inline-flex; align-items:center; justify-content:center;
    font-size:10px; font-weight:700; font-style:italic;
    font-family:'Cormorant Garamond',serif;
    cursor:pointer; flex-shrink:0;
    transition: all .2s;
    position:relative;
  }
  .var-info-icon:hover { background:var(--brown-deep); transform:scale(1.15); }
  .var-info-tooltip {
    position:absolute; bottom:calc(100% + 8px); left:50%; transform:translateX(-50%);
    background:var(--brown-deep); color:var(--cream);
    padding:10px 14px; border-radius:4px;
    font-size:11px; font-style:normal; font-family:'Jost',sans-serif;
    font-weight:400; letter-spacing:.3px;
    line-height:1.5; width:220px;
    box-shadow:0 4px 16px rgba(0,0,0,.3);
    display:none; z-index:200;
  }
  .var-info-tooltip.open { display:block; }
  .var-info-tooltip::before {
    content:''; position:absolute; bottom:-6px; left:50%; transform:translateX(-50%);
    border-top:6px solid var(--brown-deep);
    border-left:5px solid transparent;
    border-right:5px solid transparent;
  }

  /* Rio/Humedal checkbox toggle style */
  .sidebar-check {
    width:14px; height:14px; border-radius:3px;
    border:2px solid var(--sand); flex-shrink:0;
    display:flex; align-items:center; justify-content:center;
    font-size:9px; color:white; transition:all .15s;
  }
  .sidebar-check.checked { background:var(--blue-river); border-color:var(--blue-river); }
  .sidebar-check.checked::after { content:'✓'; }

  /* ──────────────── ZOOM CONTROLS ──────────────── */
  .zoom-controls {
    position:absolute; bottom:16px; right:16px; z-index:10;
    display:flex; flex-direction:column; gap:2px;
  }
  .zoom-btn {
    width:36px; height:36px;
    background:rgba(245,240,232,.92); border:1px solid var(--sand);
    display:flex; align-items:center; justify-content:center;
    cursor:pointer; font-size:18px; color:var(--brown-deep);
    transition: all .15s; user-select:none;
  }
  .zoom-btn:first-child { border-radius:4px 4px 0 0; }
  .zoom-btn:last-child { border-radius:0 0 4px 4px; }
  .zoom-btn:hover { background:var(--cream); }
  .zoom-btn:active { background:var(--sand); }
  .zoom-btn.disabled { opacity:.4; cursor:default; pointer-events:none; }
  .map-zoomable {
    position:absolute; inset:0;
    transform-origin: center center;
    transition: transform .3s ease;
  }

  /* ──────────────── SCROLLBAR ──────────────── */
  ::-webkit-scrollbar { width:6px; height:6px; }
  ::-webkit-scrollbar-track { background:transparent; }
  ::-webkit-scrollbar-thumb { background:var(--sand); border-radius:3px; }

  /* ──────────────── UTILITY ──────────────── */
  .hidden { display:none !important; }
  .italic { font-style:italic; }
  .bold { font-weight:600; }
</style>
</head>
<body>

<!-- ═══════════════ NAVBAR ═══════════════ -->
<nav id="navbar">
  <a class="nav-logo" onclick="goHome()">
    <div class="nav-logo-icon">🌿</div>
    <span>Geografías negras</span>
  </a>
  <div class="nav-items">

    <!-- Quiénes Somos -->
    <div class="nav-item" onclick="showSection('quienes')">
      ¿Quiénes somos?
      <span class="arrow-icon">▾</span>
      <div class="nav-dropdown">
        <div class="nav-dropdown-item" onclick="showSection('quienes','proyecto')">De qué trata el proyecto</div>
        <div class="nav-dropdown-item" onclick="showSection('quienes','consejos')">Los Consejos Comunitarios</div>
        <div class="nav-dropdown-item" onclick="showSection('quienes','equipo')">Equipo de investigación</div>
      </div>
    </div>

    <!-- Finca Tradicional -->
    <div class="nav-item" onclick="showSection('finca')">
      La Finca Tradicional
      <span class="arrow-icon">▾</span>
      <div class="nav-dropdown">
        <div class="nav-dropdown-item" onclick="showSection('finca','variables')">Variables de la encuesta</div>
        <div class="nav-dropdown-item" onclick="showSection('finca','datos')">Datos e imágenes por consejo</div>
        <div class="nav-dropdown-item" onclick="showSection('finca','cambios')">Cambios de cobertura 1960–2022</div>
        <div class="nav-dropdown-item" onclick="showSection('finca','audio')">Audio de la finca tradicional</div>
      </div>
    </div>

    <!-- Contramapeo -->
    <div class="nav-item" onclick="showSection('contramapeo')">
      Contramapeo
      <span class="arrow-icon">▾</span>
      <div class="nav-dropdown">
        <div class="nav-dropdown-item" onclick="showSection('contramapeo','talleres')">Talleres <span class="sub-arrow">▸</span></div>
        <div class="nav-dropdown-item" onclick="showSection('contramapeo','normativa')">Normativa <span class="sub-arrow">▸</span></div>
        <div class="nav-dropdown-item" onclick="showSection('contramapeo','mapas')">Mapas <span class="sub-arrow">▸</span></div>
      </div>
    </div>

    <!-- Río Cauca -->
    <div class="nav-item" onclick="showSection('rio')">
      Río Cauca y Humedales
      <span class="arrow-icon">▾</span>
      <div class="nav-dropdown">
        <div class="nav-dropdown-item" onclick="showSection('rio','multitemporal')">Multitemporalidad del río Cauca</div>
        <div class="nav-dropdown-item" onclick="showSection('rio','humedales')">Multitemporalidad de humedales</div>
        <div class="nav-dropdown-item" onclick="showSection('rio','cambios')">Cambios 1960–2022</div>
        <div class="nav-dropdown-item" onclick="showSection('rio','erosion')">Erosión del río Cauca</div>
        <div class="nav-dropdown-item" onclick="showSection('rio','audio')">Audio sobre los humedales</div>
      </div>
    </div>

    <!-- Recursos -->
    <div class="nav-item" onclick="showSection('recursos')">
      Recursos
      <span class="arrow-icon">▾</span>
      <div class="nav-dropdown">
        <div class="nav-dropdown-item" onclick="showSection('recursos','referencias')">Referencias <span class="sub-arrow">▸</span></div>
        <div class="nav-dropdown-item" onclick="showSection('recursos','armamapa')">Arma tu mapa <span class="sub-arrow">▸</span></div>
        <div class="nav-dropdown-item" onclick="showSection('recursos','descargas')">Descarga de capas y archivos <span class="sub-arrow">▸</span></div>
      </div>
    </div>

  </div>
</nav>

<!-- Sub-header (shown in non-home sections) -->
<div id="subheader">
  <div class="subheader-icon" id="subheader-icon">🌿</div>
  <div class="subheader-title" id="subheader-title">Sección</div>
</div>

<!-- ═══════════════ CONTENT ═══════════════ -->
<div id="content">

  <!-- ─── HOME ─── -->
  <div id="screen-home" class="screen active">
    <div class="screen-bg" style="background-color:#1e1208;">
      <!-- ▼ REEMPLAZA src con la ruta de tu imagen, ej: src="img/home.jpg" -->
      <img id="home-bg-img" src="Fondo geografias negras.png"
        alt="Imagen de fondo Home"
        style="width:100%;height:100%;object-fit:cover;display:block;"
        onerror="this.style.display='none';document.getElementById('home-bg-fallback').style.display='flex';">
      <div id="home-bg-fallback" style="display:flex;width:100%;height:100%;align-items:center;justify-content:center;font-size:12px;color:rgba(255,255,255,.25);letter-spacing:1.5px;text-transform:uppercase;position:absolute;inset:0;">
        Coloca la ruta de tu imagen en src de #home-bg-img
      </div>
    </div>

    <!-- Overlay images for hover interactions -->
    <img id="home-overlay-finca" class="overlay-layer" src="" alt="Capa Finca Tradicional">
    <img id="home-overlay-rio" class="overlay-layer" src="capa_riocauca.png" alt="Capa Río Cauca">
    <img id="home-overlay-humedales" class="overlay-layer" src="" alt="Capa Humedales">
    <!-- Overlay images for each consejo hover -->
    <img id="home-overlay-consejo" class="overlay-layer" src="" alt="Capa Consejo">

    <!-- Colombia minimap -->
    <!-- ▼ REEMPLAZA src con la ruta de tu imagen del minimap, ej: src="img/minimap-colombia.png" -->
    <div class="minimap">
      <img src="mapa de localizacion.png"
        alt="Minimap Colombia"
        style="width:100%;height:100%;object-fit:cover;display:block;"
        onerror="this.style.display='none';this.nextElementSibling.style.display='flex';">
      <div style="display:none;width:100%;height:100%;align-items:center;justify-content:center;flex-direction:column;gap:4px;color:rgba(200,180,150,0.6);font-size:9px;letter-spacing:1px;text-transform:uppercase;text-align:center;">
        🗺️<br>Minimap
      </div>
    </div>

    <!-- Left sidebar buttons (Consejos) -->
    <div class="home-sidebar">
      <div class="consejo-btn" onclick="openConsejo('finca')"
           onmouseenter="showHomeOverlay('finca')" onmouseleave="hideHomeOverlay('finca')">
        <div class="consejo-icon" style="background:rgba(90,122,74,.5);">🌿</div>
        <span>La Finca tradicional</span>
      </div>
      <div class="consejo-btn" onclick="showSection('rio')"
           onmouseenter="showHomeOverlay('rio')" onmouseleave="hideHomeOverlay('rio')">
        <div class="consejo-icon" style="background:rgba(74,122,155,.4);">〰️</div>
        <span>Río Cauca y humedales</span>
      </div>
    </div>

    <!-- Map pins (consejos comunitarios) -->
    <div class="map-pins">
      <div class="pin" style="top:14%;left:67%;" onclick="openConsejoDetail('Bocas del Palo')"
           onmouseenter="showConsejoOverlay('Bocas del Palo')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#8A8A8A;"></div>
        <div class="pin-label">Bocas del Palo</div>
      </div>
      <div class="pin" style="top:35%;left:57%;" onclick="openConsejoDetail('Paso de La Bolsa')"
           onmouseenter="showConsejoOverlay('Paso de La Bolsa')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#4A7A9B;"></div>
        <div class="pin-label">Paso de La Bolsa</div>
      </div>
      <div class="pin" style="top:55%;left:55%;" onclick="openConsejoDetail('La Ventura')"
           onmouseenter="showConsejoOverlay('La Ventura')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#C0392B;"></div>
        <div class="pin-label">La Ventura</div>
      </div>
      <div class="pin" style="top:68%;left:49%;" onclick="openConsejoDetail('Villa Paz')"
           onmouseenter="showConsejoOverlay('Villa Paz')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#27AE60;"></div>
        <div class="pin-label">Villa Paz</div>
      </div>
      <div class="pin" style="top:82%;left:43%;" onclick="openConsejoDetail('Quinamayo')"
           onmouseenter="showConsejoOverlay('Quinamayo')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#C9B99A;"></div>
        <div class="pin-label">Quinamayo</div>
      </div>
      <div class="pin" style="top:70%;left:30%;" onclick="openConsejoDetail('Robles')"
           onmouseenter="showConsejoOverlay('Robles')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#C9B99A;"></div>
        <div class="pin-label">Robles</div>
      </div>
      <div class="pin" style="top:82%;left:25%;" onclick="openConsejoDetail('Chagres')"
           onmouseenter="showConsejoOverlay('Chagres')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#C9B99A;"></div>
        <div class="pin-label">Chagres</div>
      </div>
      <div class="pin" style="top:58%;left:30%;" onclick="openConsejoDetail('Varejonal')"
           onmouseenter="showConsejoOverlay('Varejonal')" onmouseleave="hideConsejoOverlay()">
        <div class="pin-dot" style="background:#4A7A9B;"></div>
        <div class="pin-label">Varejonal</div>
      </div>
    </div>
  </div>

  <!-- ─── CONSEJO DETAIL SCREEN ─── -->
  <div id="screen-consejo" class="screen consejo-screen">
    <div class="screen-bg" id="consejo-bg" style="background-color:#1a2810;">
      <img id="consejo-bg-img" src="" alt="Imagen consejo"
        onerror="this.style.display='none';">
    </div>
    <div class="consejo-title-area" id="consejo-title-area">
      <div class="consejo-title-inner">
        <div class="subtitle">Consejo Comunitario</div>
        <h1 id="consejo-name-display">Robles</h1>
      </div>
    </div>
    <!-- Tab bar -->
    <div class="consejo-tab-bar">
      <div class="ctab active" id="ctab-loc" onclick="openConsejoPanelTab('loc')">
        <span class="ctab-icon">📄</span> Localización e Historia
      </div>
      <div class="ctab" id="ctab-audio" onclick="openConsejoPanelTab('audio')">
        <span class="ctab-icon">🎤</span> Audio del Consejo
      </div>
      <div class="ctab" id="ctab-imgs" onclick="openConsejoPanelTab('imgs')">
        <span class="ctab-icon">📷</span> Imágenes
      </div>
    </div>
    <!-- Side panel -->
    <div class="consejo-panel" id="consejo-panel">
      <button class="panel-close" onclick="closeConsejoPanel()">✕</button>
      <!-- Location tab -->
      <div id="panel-loc">
        <div class="panel-header">
          <div class="panel-title">Localización e historia</div>
        </div>
        <div class="panel-body">
          <div class="location-card">
            <div class="map-placeholder" id="localizacion-map-img">
              <!-- REEMPLAZA src con la ruta de tu imagen de localización -->
              <img id="loc-map-img" src="" alt="Mapa de localización"
                style="width:100%;height:100%;object-fit:cover;border-radius:3px;display:none;"
                onerror="this.style.display='none';document.getElementById('loc-map-fallback').style.display='flex';">
              <div id="loc-map-fallback" style="display:flex;flex-direction:column;align-items:center;gap:6px;color:var(--brown-light);">
                <span style="font-size:28px;">📍</span>
                <span style="font-size:10px;letter-spacing:.8px;text-transform:uppercase;">Imagen de localización</span>
              </div>
            </div>
            <div class="location-coords">3°06′N 76°32′O · Jamundí, Valle del Cauca</div>
            <div class="location-text">El consejo comunitario se ubica en el municipio de Jamundí, en el sur del Valle del Cauca, sobre la margen izquierda del río Cauca. Su territorio integra zonas de finca tradicional, monte bajo y humedales que han sostenido la vida de las comunidades afrodescendientes durante más de cuatro generaciones.</div>
          </div>
          <div class="panel-section-title">Historia y memoria</div>
          <p style="font-size:13px;line-height:1.7;color:var(--brown-deep);">Las familias llegaron al territorio en el siglo XIX, tras la abolición de la esclavitud. Con el tiempo construyeron un modelo de vida basado en la finca diversificada: plátano, yuca, maíz, chontaduro y plantas medicinales convivían en el mismo predio con el monte y el río.</p>
          <p style="font-size:13px;line-height:1.7;color:var(--brown-deep);margin-top:12px;">Desde los años noventa, la expansión del monocultivo de caña de azúcar ha transformado históricamente el paisaje del territorio.</p>
        </div>
      </div>
      <!-- Audio tab -->
      <div id="panel-audio" class="hidden">
        <div class="panel-header">
          <div class="panel-title">Audio del consejo</div>
        </div>
        <div class="panel-body">
          <!--
            AUDIO DEL CONSEJO:
            Reemplaza src="" en el elemento <audio id="consejo-audio-el"> con la ruta real de tu archivo.
            Puedes usar .mp3, .ogg o .wav.
            El reproductor personalizado se conecta a este elemento automáticamente.
            Si tienes un audio diferente por consejo, usa el objeto consejoAudios en JS (al final).
          -->
          <audio id="consejo-audio-el" src="" preload="metadata"></audio>
          <div class="audio-card">
            <div class="audio-wave">
              <div class="audio-wave-title">Memoria del territorio</div>
              <div class="wave-bars" id="wave-bars"></div>
            </div>
            <div class="audio-controls">
              <div class="audio-track">
                <button class="play-btn" id="consejo-play-btn" onclick="toggleConsejoPlay()">▶</button>
                <div class="track-info">
                  <div class="track-name">Relato — <span id="audio-consejo-name">Consejo</span></div>
                  <div class="track-time" id="consejo-audio-time">0:00</div>
                </div>
              </div>
              <div class="track-progress" onclick="seekConsejoAudio(event)" style="cursor:pointer;">
                <div class="track-fill" id="consejo-audio-fill"></div>
              </div>
            </div>
          </div>
          <div class="fragment-text">"Las familias llegaron al territorio en el siglo XIX, tras la abolición de la esclavitud. Con el tiempo construyeron un modelo de vida basado en la <em>finca diversificada</em>: plátano, yuca, maíz, chontaduro y plantas medicinales convivían en el mismo predio con el monte y el río."</div>
        </div>
      </div>
      <!-- Images tab -->
      <div id="panel-imgs" class="hidden">
        <div class="panel-header">
          <div class="panel-title">Imágenes del consejo</div>
        </div>
        <div class="panel-body">
          <!--
            IMÁGENES DEL PANEL CONSEJO — hasta 4 imágenes por consejo:
            Reemplaza cada src="" con la ruta de tu imagen real.
            Puedes agregar más objetos al array consejoImages en JS (al final del archivo).
          -->
          <div class="gallery-main" id="consejo-gallery-main">
            <img id="consejo-img-current" src="" alt="Imagen del consejo"
              style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;"
              onerror="this.style.display='none';document.getElementById('consejo-img-fallback').style.display='flex';">
            <div id="consejo-img-fallback" style="display:flex;flex-direction:column;align-items:center;gap:8px;color:rgba(245,240,232,.5);">
              <span style="font-size:36px;">📷</span>
              <span style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:16px;">Imagen 01 del consejo</span>
            </div>
            <button class="gallery-nav prev" onclick="consejoGalleryNav(-1)">‹</button>
            <button class="gallery-nav next" onclick="consejoGalleryNav(1)">›</button>
            <button class="gallery-expand" onclick="expandConsejoImage()">⤢</button>
          </div>
          <div style="display:flex;justify-content:center;gap:6px;margin:8px 0;" id="consejo-gallery-dots"></div>
          <div class="gallery-caption" id="consejo-gallery-caption">Imagen 01 del consejo comunitario</div>
        </div>
      </div>
    </div>
  </div>

  <!-- ─── FINCA TRADICIONAL ─── -->
  <div id="screen-finca" class="screen">
    <div class="finca-layout">
      <div class="finca-sidebar">
        <!-- Variables -->
        <div class="sidebar-section">
          <div class="sidebar-section-header">
            <div class="sidebar-section-icon">📊</div>
            Variables Encuesta
          </div>
          <div id="variables-list">
            <!-- generated by JS -->
          </div>
        </div>
        <!-- Cambio de cobertura -->
        <div class="sidebar-section">
          <div class="sidebar-btn" onclick="openComparator()">
            <div class="sidebar-section-icon">🗂</div>
            <div>
              <div class="sidebar-btn-label">Cambio de cobertura</div>
              <div class="sidebar-btn-sub">(1961–2022)</div>
            </div>
          </div>
        </div>
        <!-- Audio -->
        <div class="sidebar-section">
          <div class="sidebar-btn">
            <div class="play-btn" onclick="togglePlay(this)" style="flex-shrink:0;">▶</div>
            <div>
              <div class="sidebar-btn-label">Relato finca tradicional</div>
              <div class="sidebar-btn-sub">0:00</div>
              <div class="track-progress" style="margin-top:4px;"><div class="track-fill"></div></div>
            </div>
          </div>
        </div>
      </div>

      <!-- Map area -->
      <div class="finca-map-area">
        <div class="map-zoomable" id="finca-zoomable">
        <div class="screen-bg" style="position:absolute;inset:0;">
          <!-- REEMPLAZA CON: background-image: url('tu-imagen-mapa-finca.jpg'); en .screen-bg -->
          <div class="bg-placeholder" style="color:var(--brown-light);"></div>
        </div>
        <!-- Variable overlay layer -->
        <img id="finca-variable-overlay" class="overlay-layer" src="" alt="Capa de variable" style="z-index:1;">
        <!-- Pins on map -->
        <div class="finca-pins" style="z-index:4;">
          <div class="finca-pin" style="top:22%;left:58%;" onclick="openFincaConsejo('Bocas del Palo')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#8A8A8A;"></div> Bocas del Palo</div>
          </div>
          <div class="finca-pin" style="top:38%;left:55%;" onclick="openFincaConsejo('Paso de La Bolsa')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#4A7A9B;"></div> Paso de La Bolsa</div>
          </div>
          <div class="finca-pin" style="top:44%;left:53%;" onclick="openFincaConsejo('La Ventura')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C0392B;"></div> La Ventura</div>
          </div>
          <div class="finca-pin" style="top:50%;left:50%;" onclick="openFincaConsejo('Villa Paz')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#27AE60;"></div> Villa Paz</div>
          </div>
          <div class="finca-pin" style="top:80%;left:46%;" onclick="openFincaConsejo('Quinamayo')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Quinamayo</div>
          </div>
          <div class="finca-pin" style="top:78%;left:38%;" onclick="openFincaConsejo('Robles')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Robles</div>
          </div>
          <div class="finca-pin" style="top:87%;left:34%;" onclick="openFincaConsejo('Chagres')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Chagres</div>
          </div>
          <div class="finca-pin" style="top:70%;left:32%;" onclick="openFincaConsejo('Varejonal')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#4A7A9B;"></div> Varejonal</div>
          </div>
        </div>
        <!-- Consejo popup in finca -->
        <div class="consejo-popup" id="finca-popup" style="top:60px;left:280px;">
          <div class="popup-header">
            <div class="popup-subtitle">Consejo Comunitario</div>
            <div class="popup-title" id="popup-consejo-name">Robles</div>
            <button class="panel-close" style="top:10px;right:10px;" onclick="closeFincaPopup()">✕</button>
          </div>
          <div class="popup-tabs">
            <div class="popup-tab active" onclick="switchPopupTab(this,'tab-imgs')">
              🖼 Imágenes
            </div>
            <div class="popup-tab" onclick="switchPopupTab(this,'tab-stats')">
              📊 Estadísticas
            </div>
          </div>
          <div class="popup-body">
            <div id="tab-imgs">
              <!--
                IMÁGENES DEL POPUP FINCA — hasta 3 imágenes por consejo:
                Reemplaza cada src="" con la ruta de tu imagen real.
                Puedes agregar más <img> dentro de gallery-main usando el mismo estilo.
              -->
              <div class="gallery-main" style="height:280px;" id="finca-gallery-main">
                <!-- Imagen 1 (visible por defecto) -->
                <img id="finca-img-1" src="" alt="Imagen 1 del consejo"
                  style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;"
                  onerror="this.style.display='none';">
                <!-- Imagen 2 -->
                <img id="finca-img-2" src="" alt="Imagen 2 del consejo"
                  style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;"
                  onerror="this.style.display='none';">
                <!-- Imagen 3 -->
                <img id="finca-img-3" src="" alt="Imagen 3 del consejo"
                  style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;"
                  onerror="this.style.display='none';">
                <div class="gallery-placeholder" id="finca-img-placeholder">Imagen de Cultivos</div>
                <button class="gallery-nav prev" onclick="fincaGalleryNav(-1)">‹</button>
                <button class="gallery-nav next" onclick="fincaGalleryNav(1)">›</button>
              </div>
              <div style="display:flex;justify-content:center;gap:6px;margin:8px 0;" id="finca-gallery-dots">
                <span class="gdot active" data-i="0" style="width:8px;height:8px;border-radius:50%;background:var(--brown-mid);display:inline-block;cursor:pointer;" onclick="fincaGalleryGoto(0)"></span>
                <span class="gdot" data-i="1" style="width:8px;height:8px;border-radius:50%;background:var(--sand);display:inline-block;cursor:pointer;" onclick="fincaGalleryGoto(1)"></span>
                <span class="gdot" data-i="2" style="width:8px;height:8px;border-radius:50%;background:var(--sand);display:inline-block;cursor:pointer;" onclick="fincaGalleryGoto(2)"></span>
              </div>
              <div class="gallery-caption" id="finca-gallery-caption">Cultivos de plátano del consejo.</div>
            </div>
            <div id="tab-stats" class="hidden">
              <div class="panel-section-title">Tenencia de la tierra</div>
              <div class="stat-chart-donut">
                <div class="donut-placeholder"><div class="donut-hole"></div></div>
                <div class="donut-legend">
                  <div class="legend-item"><div class="legend-dot" style="background:var(--brown-mid);"></div>Colectiva – 55%</div>
                  <div class="legend-item"><div class="legend-dot" style="background:var(--sand);"></div>Arrendada – 25%</div>
                  <div class="legend-item"><div class="legend-dot" style="background:#8B7355;"></div>Individual – 15%</div>
                  <div class="legend-item"><div class="legend-dot" style="background:#5A4030;"></div>Prestada – 5%</div>
                </div>
              </div>
              <div class="panel-section-title">Cultivos presentes</div>
              <div class="bar-chart">
                <div class="bar-item"><div class="bar-label">Plátano</div><div class="bar-track"><div class="bar-fill" style="width:95%;background:var(--green-finca);"></div></div><div class="bar-pct">95%</div></div>
                <div class="bar-item"><div class="bar-label">Naranja</div><div class="bar-track"><div class="bar-fill" style="width:80%;background:var(--brown-mid);"></div></div><div class="bar-pct">80%</div></div>
                <div class="bar-item"><div class="bar-label">Limón</div><div class="bar-track"><div class="bar-fill" style="width:65%;background:#D4A843;"></div></div><div class="bar-pct">65%</div></div>
                <div class="bar-item"><div class="bar-label">Mandarina</div><div class="bar-track"><div class="bar-fill" style="width:35%;background:var(--sand);"></div></div><div class="bar-pct">35%</div></div>
              </div>
            </div>
          </div>
        </div>

        <!-- Comparator overlay — EFECTO CORTINA -->
        <!--
          ════════════════════════════════════════════════════════
          CÓMO PONER TUS IMÁGENES EN EL COMPARADOR FINCA:
          1. Imagen lado IZQUIERDO (año 1961):
             Busca la línea con id="finca-comp-left" y agrega:
             style="background-image:url('tu-imagen-1961.jpg')"
          2. Imagen lado DERECHO (año 2024):
             Busca la línea con id="finca-comp-right" y agrega:
             style="background-image:url('tu-imagen-2024.jpg')"
          ════════════════════════════════════════════════════════
        -->
        <div class="comparator" id="finca-comparator">
          <div class="comp-area" id="finca-comp-area">
            <!-- IMAGEN IZQUIERDA (1961) — reemplaza background-image -->
            <div class="comp-img-left" id="finca-comp-left"
              style="background-image:url('finca\ tradicional\ 1961.png');">
            </div>
            <!-- IMAGEN DERECHA (2024) — reemplaza background-image -->
            <div class="comp-img-right" id="finca-comp-right"
              style="background-image:url('finca\ tradicional\ 2024.png');">
            </div>
            <!-- Etiquetas -->
            <div class="comp-label-left"><h3>1961</h3><p>Cobertura de consejos comunitarios</p></div>
            <div class="comp-label-right"><h3>2024</h3><p>Cobertura de consejos comunitarios</p></div>
            <!-- Línea divisoria draggable -->
            <div class="comp-divider" id="finca-comp-divider">
              <div class="comp-handle">⇔</div>
            </div>
          </div>
          <div class="comp-footer">
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:#C9B99A;"></div>Monocultivo de caña</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:var(--green-finca);"></div>Entorno de la finca</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:var(--blue-river);"></div>Río Cauca</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:var(--gray-urban);"></div>Zonas urbanas</div>
            <button class="comp-close-btn" onclick="closeComparator()">✕ Cerrar comparador</button>
          </div>
        </div>
      </div><!-- end map-zoomable -->
        <!-- Zoom controls -->
        <div class="zoom-controls">
          <div class="zoom-btn" id="finca-zoom-in" onclick="zoomMap('finca',1)">+</div>
          <div class="zoom-btn" id="finca-zoom-out" onclick="zoomMap('finca',-1)">−</div>
        </div>
      </div>

      <!-- Conventions -->
      <div class="finca-conventions">
        <div class="conv-title">Convenciones</div>
        <div class="conv-item"><div class="conv-color" style="background:var(--green-finca);"></div><div class="conv-label">Entorno de la finca tradicional</div></div>
        <div class="conv-item"><div class="conv-color" style="background:#F5F0E8;border-color:var(--sand);"></div><div class="conv-label">Monocultivo de caña de azúcar</div></div>
        <div class="conv-item"><div class="conv-color" style="background:var(--gray-urban);"></div><div class="conv-label">Zonas urbanas</div></div>
        <div class="conv-item"><div class="conv-color" style="background:var(--blue-river);"></div><div class="conv-label">Río Cauca</div></div>
      </div>
    </div>
  </div>

  <!-- ─── RÍO CAUCA Y HUMEDALES ─── -->
  <div id="screen-rio" class="screen">
    <div class="rio-layout">
      <div class="finca-sidebar">
        <div class="sidebar-section">
          <div class="sidebar-section-header">
            <div class="sidebar-section-icon">〰️</div>
            Multitemporal río Cauca
          </div>
          <div id="rio-years">
            <!-- generated by JS with checkboxes -->
          </div>
        </div>
        <div class="sidebar-section">
          <div class="sidebar-section-header">
            <div class="sidebar-section-icon">💧</div>
            Multitemporal humedales
          </div>
          <div id="humedal-years">
            <!-- generated by JS with checkboxes -->
          </div>
        </div>
        <div class="sidebar-section">
          <div class="sidebar-btn" onclick="openHumedalesComparator()">
            <div class="sidebar-section-icon">🗂</div>
            <div>
              <div class="sidebar-btn-label">Humedales perdidos</div>
              <div class="sidebar-btn-sub">(1961–2024)</div>
            </div>
          </div>
        </div>
        <div class="sidebar-section">
          <div class="sidebar-btn" onclick="openErosionModal()">
            <div class="sidebar-section-icon">🌊</div>
            <div>
              <div class="sidebar-btn-label">Erosión del río Cauca</div>
              <div class="sidebar-btn-sub">en la finca tradicional</div>
            </div>
          </div>
        </div>
        <div class="sidebar-section">
          <div class="sidebar-btn">
            <div class="play-btn" onclick="togglePlay(this)" style="flex-shrink:0;">▶</div>
            <div>
              <div class="sidebar-btn-label">Relato de los humedales</div>
              <div class="sidebar-btn-sub">0:00</div>
              <div class="track-progress" style="margin-top:4px;"><div class="track-fill"></div></div>
            </div>
          </div>
        </div>
      </div>

      <!-- Map area -->
      <div class="finca-map-area">
        <div class="map-zoomable" id="rio-zoomable">
        <div class="screen-bg" style="position:absolute;inset:0;background-color:#c8d8e8;">
          <!-- REEMPLAZA CON: background-image: url('tu-imagen-mapa-rio.jpg'); -->
          <div class="bg-placeholder" style="color:var(--blue-river);"></div>
        </div>
        <!-- Overlay layers for rio years (multiple can be active) -->
        <div id="rio-overlays-container" style="position:absolute;inset:0;z-index:1;pointer-events:none;"></div>
        <!-- Overlay layers for humedal years (multiple can be active) -->
        <div id="humedal-overlays-container" style="position:absolute;inset:0;z-index:1;pointer-events:none;"></div>
        <!-- Pins -->
        <div class="finca-pins" style="z-index:4;">
          <div class="finca-pin" style="top:22%;left:58%;" onclick="openHumedalConsejo('Bocas del Palo')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#8A8A8A;"></div> Bocas del Palo</div>
          </div>
          <div class="finca-pin" style="top:36%;left:55%;" onclick="openHumedalConsejo('Paso de La Bolsa')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#4A7A9B;"></div> Paso de La Bolsa</div>
          </div>
          <div class="finca-pin" style="top:44%;left:52%;" onclick="openHumedalConsejo('La Ventura')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C0392B;"></div> La Ventura</div>
          </div>
          <div class="finca-pin" style="top:50%;left:49%;" onclick="openHumedalConsejo('Villa Paz')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#27AE60;"></div> Villa Paz</div>
          </div>
          <div class="finca-pin" style="top:54%;left:42%;" onclick="openHumedalConsejo('Quinamayo')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Quinamayo</div>
          </div>
          <div class="finca-pin" style="top:58%;left:37%;" onclick="openHumedalConsejo('Robles')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Robles</div>
          </div>
          <div class="finca-pin" style="top:62%;left:30%;" onclick="openHumedalConsejo('Chagres')">
            <div class="finca-pin-label"><div class="finca-pin-dot" style="background:#C9B99A;"></div> Chagres</div>
          </div>
        </div>

        <!-- Humedal popup -->
        <div class="consejo-popup" id="rio-popup" style="top:60px;left:280px;">
          <div class="popup-header">
            <div class="popup-subtitle">Consejo Comunitario</div>
            <div class="popup-title" id="rio-popup-name">Robles</div>
            <button class="panel-close" style="top:10px;right:10px;" onclick="closeRioPopup()">✕</button>
          </div>
          <div class="popup-tabs">
            <div class="popup-tab active">💧 HUMEDALES</div>
          </div>
          <div class="popup-body">
            <!--
              IMÁGENES DEL POPUP HUMEDAL — hasta 3 imágenes:
              Reemplaza src="" con la ruta de tu imagen real.
            -->
            <div class="gallery-main" style="height:280px;">
              <img id="rio-gallery-img" src="" alt="Imagen del humedal"
                style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;"
                onerror="this.style.display='none';">
              <div class="gallery-placeholder" id="rio-gallery-placeholder">Imagen del humedal</div>
              <button class="gallery-nav prev">‹</button>
              <button class="gallery-nav next">›</button>
            </div>
            <div style="display:flex;justify-content:center;gap:6px;margin:8px 0;">
              <span style="width:8px;height:8px;border-radius:50%;background:var(--blue-river);display:inline-block;"></span>
              <span style="width:8px;height:8px;border-radius:50%;background:var(--sand);display:inline-block;"></span>
              <span style="width:8px;height:8px;border-radius:50%;background:var(--sand);display:inline-block;"></span>
            </div>
            <div class="gallery-caption">Humedal Cabezón: Tiene un área de 31,7 ha. Su relación con la comunidad es fundamental para su sostenimiento.</div>
          </div>
        </div>

        <!-- Humedales lost comparator — EFECTO CORTINA -->
        <!--
          ════════════════════════════════════════════════════════
          CÓMO PONER TUS IMÁGENES EN EL COMPARADOR HUMEDALES:
          1. Imagen lado IZQUIERDO (1961):
             Busca id="rio-comp-left" y agrega style="background-image:url('tu-imagen-1961.jpg')"
          2. Imagen lado DERECHO (2024):
             Busca id="rio-comp-right" y agrega style="background-image:url('tu-imagen-2024.jpg')"
          ════════════════════════════════════════════════════════
        -->
        <div class="comparator" id="rio-comparator">
          <div class="comp-area" id="rio-comp-area">
            <!-- IMAGEN IZQUIERDA (1961) — reemplaza background-image -->
            <div class="comp-img-left" id="rio-comp-left"
              style="background-image:url('');">
            </div>
            <!-- IMAGEN DERECHA (2024) — reemplaza background-image -->
            <div class="comp-img-right" id="rio-comp-right"
              style="background-image:url('');">
            </div>
            <!-- Etiquetas -->
            <div class="comp-label-left"><h3>1961</h3><p>Humedales</p></div>
            <div class="comp-label-right"><h3>2024</h3><p>Humedales</p></div>
            <!-- Línea divisoria draggable -->
            <div class="comp-divider" id="rio-comp-divider">
              <div class="comp-handle">⇔</div>
            </div>
          </div>
          <div class="comp-footer">
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:#C9B99A;"></div>Monocultivo de caña</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:var(--blue-river);"></div>Humedales</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:#4A7A9B;"></div>Río Cauca</div>
            <div class="comp-legend-item"><div class="comp-legend-color" style="background:var(--gray-urban);"></div>Zonas urbanas</div>
            <button class="comp-close-btn" onclick="closeRioComparator()">✕ Cerrar comparador</button>
          </div>
        </div>

        <!-- Erosion modal inside map -->
        <div class="consejo-popup" id="erosion-popup" style="top:40px;left:60px;width:560px;display:none;">
          <div class="popup-header">
            <div class="popup-title">Erosión del río Cauca en la finca tradicional</div>
            <button class="panel-close" style="top:10px;right:10px;" onclick="document.getElementById('erosion-popup').style.display='none'">✕</button>
          </div>
          <div class="popup-body">
            <!-- REEMPLAZA CON imagen del mapa de erosión real -->
            <div style="background:var(--sand);border-radius:4px;height:220px;display:flex;align-items:center;justify-content:center;margin-bottom:10px;">
              <span style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:16px;color:rgba(61,43,31,.5);">Mapa de erosión · imagen real aquí</span>
            </div>
            <div style="font-size:12px;color:var(--brown-light);">Zonas afectadas por la erosión del río Cauca en las fincas de Quinámayo y Villa Paz.</div>
          </div>
        </div>
      </div><!-- end rio map-zoomable -->
        <!-- Zoom controls -->
        <div class="zoom-controls">
          <div class="zoom-btn" id="rio-zoom-in" onclick="zoomMap('rio',1)">+</div>
          <div class="zoom-btn" id="rio-zoom-out" onclick="zoomMap('rio',-1)">−</div>
        </div>
      </div>

      <!-- Conventions -->
      <div class="finca-conventions">
        <div class="conv-title">Convenciones</div>
        <div class="conv-item"><div class="conv-color" style="background:var(--green-finca);"></div><div class="conv-label">Entorno de la finca tradicional</div></div>
        <div class="conv-item"><div class="conv-color" style="background:#F5F0E8;border-color:var(--sand);"></div><div class="conv-label">Monocultivo de caña de azúcar</div></div>
        <div class="conv-item"><div class="conv-color" style="background:var(--gray-urban);"></div><div class="conv-label">Zonas urbanas</div></div>
        <div class="conv-item"><div class="conv-color" style="background:var(--blue-river);"></div><div class="conv-label">Río Cauca</div></div>
        <div class="conv-item"><div class="conv-color" style="background:#A8C8D8;"></div><div class="conv-label">Humedales</div></div>
      </div>
    </div>
  </div>

  <!-- ─── QUIÉNES SOMOS ─── -->
  <div id="screen-quienes" class="screen">
    <div class="text-screen">
      <div class="text-sidebar">
        <div class="text-sidebar-brand">
          <div class="brand-name">Geografías<br>negras</div>
          <div class="brand-tagline">Visibilizando cartografías y prácticas territoriales, agua y memoria de los consejos comunitarios afrodescendientes de Jamundí, Valle del Cauca.</div>
        </div>
        <div class="text-nav-group">
          <div class="text-nav-item active" id="qs-nav-proyecto" onclick="switchQSTab('proyecto')">
            <div class="text-nav-icon">🗺</div>
            <div><div class="text-nav-label">El proyecto</div><div class="text-nav-sub">De qué trata · Contexto · Datos clave</div></div>
          </div>
          <div class="text-nav-item" id="qs-nav-consejos" onclick="switchQSTab('consejos')">
            <div class="text-nav-icon">👥</div>
            <div><div class="text-nav-label">Consejos Comunitarios</div><div class="text-nav-sub">Territorios participantes</div></div>
          </div>
          <div class="text-nav-item" id="qs-nav-equipo" onclick="switchQSTab('equipo')">
            <div class="text-nav-icon">🔬</div>
            <div><div class="text-nav-label">Equipo de investigación</div><div class="text-nav-sub">Investigadores y apoyo</div></div>
          </div>
        </div>
        <div style="padding:16px;">
          <div style="font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--brown-light);margin-bottom:10px;">Instituciones</div>
          <div class="institutions-row" style="padding:0;">
            <div class="inst-badge">UniValle</div>
            <div class="inst-badge">UAO</div>
            <div class="inst-badge">Queen's</div>
          </div>
        </div>
      </div>
      <div class="text-main">
        <!-- proyecto tab -->
        <div id="qs-proyecto">
          <div class="section-tag">Sobre el proyecto</div>
          <div class="section-heading">El proyecto</div>
          <div class="section-body">
            <p>Geografías negras es una plataforma cartográfica participativa que documenta las prácticas territoriales de las comunidades afrodescendientes de Jamundí, en el sur del Valle del Cauca. El proyecto nace de la necesidad de visibilizar y defender los saberes, los usos del agua y las formas de vida de la finca tradicional frente al avance del monocultivo de caña de azúcar.</p>
            <p>A través de encuestas comunitarias, talleres participativos y trabajo cartográfico colaborativo, el equipo construyó junto con los consejos un atlas territorial que recoge variables de tenencia de la tierra, biodiversidad productiva, fuentes de agua y presión territorial, entre otras dimensiones críticas para la autonomía comunitaria.</p>
            <p>La plataforma es a la vez un instrumento de contramapeo, una herramienta de incidencia política y un archivo vivo de la memoria territorial afrodescendiente en Jamundí, ejecutada en alianza entre Queen's University, la Universidad del Valle y la Universidad Autónoma de Occidente.</p>
          </div>
          <div class="stats-row">
            <div class="stat-card"><div class="stat-number">5</div><div class="stat-label">Consejos Comunitarios</div><div class="stat-desc">Participantes activos en la construcción colectiva de mapas, encuestas y contenidos territoriales.</div></div>
            <div class="stat-card"><div class="stat-number">233</div><div class="stat-label">Fincas encuestadas</div><div class="stat-desc">Fincas que aportaron datos sobre sus prácticas agrícolas y percepción de presión territorial.</div></div>
            <div class="stat-card"><div class="stat-number">3</div><div class="stat-label">Instituciones aliadas</div><div class="stat-desc">Queen's University, Universidad del Valle y Universidad Autónoma de Occidente.</div></div>
          </div>
          <div class="video-placeholder">
            <!-- REEMPLAZA CON: <video src="tu-video.mp4" controls></video> -->
            <div class="video-play">▶</div>
          </div>
          <div class="video-caption">Metodologías y acuerdos</div>
        </div>
        <!-- consejos tab -->
        <div id="qs-consejos" class="hidden">
          <div class="section-tag">Territorios y comunidades</div>
          <div class="section-heading">Consejos comunitarios participantes</div>
          <div class="section-body">
            <p>Seis consejos comunitarios afrodescendientes de Jamundí participaron en la construcción colectiva de esta plataforma, aportando su conocimiento territorial, su historia y su voz a través de talleres, encuestas y relatos.</p>
          </div>
          <div class="community-grid">
            <div class="community-card"><div class="cc-header"><div class="cc-dot" style="background:var(--green-finca);"></div><div class="cc-name">Robles</div></div><div class="cc-desc">Finca tradicional con más de cuatro generaciones de arraigo. Plátano, yuca, maíz, chontaduro y plantas medicinales conviven con el monte y los humedales.</div></div>
            <div class="community-card"><div class="cc-header"><div class="cc-dot" style="background:var(--gray-urban);"></div><div class="cc-name">Quinámayo</div></div><div class="cc-desc">Prácticas ancestrales del agua y el río Cauca. La finca integra huerta, monte y pesca como un sistema productivo y espiritual.</div></div>
            <div class="community-card"><div class="cc-header"><div class="cc-dot" style="background:var(--blue-river);"></div><div class="cc-name">Varejonal</div></div><div class="cc-desc">Alta biodiversidad productiva con más de doce especies cultivadas. Líder en procesos de contramapeo para documentar sus límites históricos.</div></div>
            <div class="community-card" style="grid-column:1/2;"><div class="cc-header"><div class="cc-dot" style="background:var(--gray-urban);"></div><div class="cc-name">Villa Paz</div></div><div class="cc-desc">Activo en defensa territorial con titulación colectiva en curso. El acceso al agua es el principal eje de tensión con los ingenios azucareros.</div></div>
            <div class="community-card"><div class="cc-header"><div class="cc-dot" style="background:var(--blue-river);"></div><div class="cc-name">Chagres</div></div><div class="cc-desc">Mayor arraigo generacional del estudio. Los mayores son custodios de relatos sobre el origen del asentamiento y las transformaciones del paisaje.</div></div>
          </div>
          <div class="video-placeholder" style="max-width:360px;">
            <!-- REEMPLAZA CON video de Armando Vásquez -->
            <div class="video-play">▶</div>
          </div>
          <div class="video-caption">Expectativas de los participantes — Armando Vásquez, Consejo Comunitario Quinamayo</div>
        </div>
        <!-- equipo tab -->
        <div id="qs-equipo" class="hidden">
          <div class="section-tag">Equipo de trabajo</div>
          <div class="section-heading">Equipo de investigación</div>
          <div class="community-banner">
            <strong>Consejos comunitarios de Robles, Quinamayó, Varejonal, Bocas del Palo, Villa Paz y Chagres</strong>
            <p>Participación en talleres, construcción colectiva de contenidos territoriales y levantamiento de encuestas comunitarias. Sin su voz y su territorio, este proyecto no existe.</p>
          </div>
          <div class="team-section-label">Dirección</div>
          <div class="team-grid" style="grid-template-columns:1fr;">
            <div class="team-card"><div class="team-name">Diana Córdoba</div><div class="team-role">Directora del proyecto · Queen's University</div></div>
          </div>
          <div class="team-section-label">Coordinación académica e investigativa</div>
          <div class="team-grid" style="grid-template-columns:1fr 1fr;">
            <div class="team-card"><div class="team-name">Renata Moreno</div><div class="team-role">Profesora investigadora · Universidad del Valle</div></div>
            <div class="team-card"><div class="team-name">Lilian Carrillo</div><div class="team-role">Profesora investigadora · Univ. Autónoma de Occidente</div></div>
            <div class="team-card"><div class="team-name">José Bedoya</div><div class="team-role">Profesor investigador · Univ. Autónoma de Occidente</div></div>
          </div>
          <div class="team-section-label">Coordinación equipo cartográfico</div>
          <div class="team-grid">
            <div class="team-card"><div class="team-name">Gian Marlon Cifuentes</div><div class="team-role">Profesional en Geografía</div></div>
            <div class="team-card"><div class="team-name">Myriam Zuluaga</div><div class="team-role">Profesional en Geografía</div></div>
            <div class="team-card"><div class="team-name">Karem Correa</div><div class="team-role">Profesional en Geografía</div></div>
          </div>
          <div class="team-section-label">Apoyo técnico y visual</div>
          <div class="team-grid">
            <div class="team-card"><div class="team-name">Kennet Morales</div><div class="team-role">Apoyo en programación</div></div>
            <div class="team-card"><div class="team-name">Neyder Sanzhes</div><div class="team-role">Apoyo en diseño</div></div>
            <div class="team-card"><div class="team-name">Mauricio Cardona</div><div class="team-role">Apoyo en diseño</div></div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ─── CONTRAMAPEO ─── -->
  <div id="screen-contramapeo" class="screen">
    <div class="text-screen">
      <div class="text-sidebar">
        <div class="text-sidebar-brand">
          <div class="brand-name">Contramapeo</div>
        </div>
        <div class="text-nav-group">
          <div class="text-nav-item active" id="cm-nav-talleres" onclick="switchCMTab('talleres')">
            <div class="text-nav-icon">📋</div>
            <div class="text-nav-label">Talleres</div>
          </div>
          <div class="text-nav-item" id="cm-nav-normativa" onclick="switchCMTab('normativa')">
            <div class="text-nav-icon">⚖️</div>
            <div class="text-nav-label">Normativa</div>
          </div>
          <div class="text-nav-item" id="cm-nav-mapas" onclick="switchCMTab('mapas')">
            <div class="text-nav-icon">🗺</div>
            <div class="text-nav-label">Mapas</div>
          </div>
        </div>
      </div>
      <div class="text-main">
        <!-- Talleres -->
        <div id="cm-talleres" style="display:flex;gap:0;height:100%;margin:-30px -40px;">
          <div style="width:220px;background:var(--cream-dark);border-right:1px solid var(--sand);overflow-y:auto;flex-shrink:0;">
            <div class="taller-list" id="taller-list"></div>
          </div>
          <div style="flex:1;padding:28px 32px;overflow-y:auto;">
            <div class="section-tag" id="taller-tag">Taller 01</div>
            <div class="section-heading" id="taller-heading">Socialización y relacionamiento de los Consejos comunitarios de Jamundí</div>
            <div style="font-size:11px;color:var(--brown-light);margin-bottom:20px;">
              <span id="taller-date">FECHA: 12/12/2024</span>&nbsp;&nbsp;&nbsp;<span id="taller-lugar">LUGAR: Universidad Autónoma de Occidente</span>
            </div>
            <div class="inner-tabs">
              <div class="inner-tab active" onclick="switchTallerTab(this,'tt-obj')">📄 Objetivos</div>
              <div class="inner-tab" onclick="switchTallerTab(this,'tt-mem')">📝 Memoria</div>
              <div class="inner-tab" onclick="switchTallerTab(this,'tt-res')">🎯 Resultados</div>
              <div class="inner-tab" onclick="switchTallerTab(this,'tt-imgs')">🖼 Imágenes y Videos</div>
            </div>
            <!-- Obj -->
            <div id="tt-obj">
              <p style="font-size:13px;color:var(--brown-deep);margin-bottom:16px;line-height:1.7;">Este taller se centró en visibilizar y documentar las prácticas territoriales de los consejos participantes como parte del proceso de contramapeo y construcción de soberanía geográfica.</p>
              <div class="obj-grid">
                <div class="obj-card"><div class="obj-num">01</div><div class="obj-text">Construir colectivamente el mapa mental del territorio comunitario desde la perspectiva de los habitantes.</div></div>
                <div class="obj-card"><div class="obj-num">02</div><div class="obj-text">Identificar los lugares significativos, límites percibidos y zonas de conflicto no registradas en mapas oficiales.</div></div>
                <div class="obj-card"><div class="obj-num">03</div><div class="obj-text">Establecer una metodología participativa de levantamiento de información geográfica.</div></div>
                <div class="obj-card"><div class="obj-num">04</div><div class="obj-text">Fortalecer los lazos entre los diferentes consejos comunitarios a través del reconocimiento mutuo del territorio.</div></div>
              </div>
            </div>
            <!-- Mem -->
            <div id="tt-mem" class="hidden" style="max-height:400px;overflow-y:auto;">
              <div style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:18px;color:var(--brown-mid);margin-bottom:12px;">Bienvenida y contextualización</div>
              <p style="font-size:13px;line-height:1.7;color:var(--brown-deep);margin-bottom:16px;">Alfredo Lucumí León, de Chagres, compartió su vínculo ancestral con el humedal La Guinea, sustento de la región durante generaciones y espacio de recreación donde convergían Robles, Villa Paz, Quinamayó, Timba y Chagres.</p>
              <div style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:18px;color:var(--brown-mid);margin-bottom:12px;">Actividad 1</div>
              <p style="font-size:13px;line-height:1.7;color:var(--brown-deep);margin-bottom:16px;">Cartografía participativa del territorio: los asistentes identificaron y nombraron lugares significativos, fuentes de agua comunitaria y zonas de conflicto territorial no registradas en cartografía oficial.</p>
              <div style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:18px;color:var(--brown-mid);margin-bottom:12px;">Conclusiones</div>
              <p style="font-size:13px;line-height:1.7;color:var(--brown-deep);">La sesión evidenció la brecha entre los mapas oficiales y las territorialidades vividas, sentando las bases para el proceso de contramapeo comunitario.</p>
            </div>
            <!-- Resultados -->
            <div id="tt-res" class="hidden">
              <div class="results-stats">
                <div class="res-stat"><div class="res-num">12</div><div class="res-label">Participantes</div></div>
                <div class="res-stat"><div class="res-num">5</div><div class="res-label">Consejos Comunitarios</div></div>
              </div>
              <div style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:18px;color:var(--brown-mid);margin-bottom:12px;">Acuerdo de relacionamiento</div>
              <div style="background:var(--sand);border-radius:4px;height:160px;display:flex;align-items:center;justify-content:center;">
                <!-- REEMPLAZA CON PDF real o imagen del acuerdo -->
                <span style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:16px;color:rgba(61,43,31,.5);">PDF o Mapa del taller</span>
              </div>
            </div>
            <!-- Imgs -->
            <div id="tt-imgs" class="hidden">
              <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;">
                <div>
                  <div style="background:var(--sand);border-radius:4px;height:200px;display:flex;align-items:center;justify-content:center;position:relative;">
                    <!-- REEMPLAZA CON galería real de imágenes del taller -->
                    <span style="font-family:'Cormorant Garamond',serif;font-style:italic;font-size:16px;color:rgba(61,43,31,.5);">Imágenes</span>
                    <button class="gallery-nav prev" style="position:absolute;">‹</button>
                    <button class="gallery-nav next" style="position:absolute;">›</button>
                  </div>
                  <div class="gallery-caption" style="margin-top:6px;">Encuentro con los Consejos</div>
                </div>
                <div>
                  <div style="background:#8B7355;border-radius:4px;height:200px;display:flex;align-items:center;justify-content:center;cursor:pointer;">
                    <!-- REEMPLAZA CON video real -->
                    <div class="video-play" style="border-color:white;color:white;">▶</div>
                  </div>
                  <div class="gallery-caption" style="margin-top:6px;">Video del taller</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Normativa -->
        <div id="cm-normativa" class="hidden">
          <div class="section-tag">Sistematización normativa</div>
          <div class="section-heading">Normativa territorial colombiana</div>
          <div class="section-subheading">Marco normativo del ordenamiento territorial colombiano</div>
          <div class="text-nav-group" style="display:flex;gap:0;margin-bottom:24px;border-bottom:1px solid var(--sand);">
            <div class="inner-tab active" onclick="switchNormTab(this,'norm-general')">Marco normativo general</div>
            <div class="inner-tab" onclick="switchNormTab(this,'norm-negras')">Comunidades negras</div>
            <div class="inner-tab" onclick="switchNormTab(this,'norm-agua')">Ordenamiento del agua</div>
          </div>
          <div id="norm-general">
            <p style="font-size:13px;line-height:1.8;color:var(--brown-deep);margin-bottom:20px;">Esta sección resume el proceso de sistematización realizado para identificar cómo el ordenamiento territorial ha sido pensado desde categorías técnicas, administrativas y sectoriales que muchas veces no logran nombrar la complejidad de los territorios afrodescendientes.</p>
            <div class="stats-row">
              <div class="stat-card"><div class="stat-number">10</div><div class="stat-label">Normas revisadas</div><div class="stat-desc">Ley 388/97, Ley 1454/11, CONPES 3870, Decreto 1232/20, Ley 614/00, Decreto 1640/12, Ley 70/93, Decreto 3600/07 y más.</div></div>
              <div class="stat-card"><div class="stat-number">18</div><div class="stat-label">Campos de análisis</div><div class="stat-desc">Nombre, contexto histórico, año, autores, escala, participación, categorías territoriales, sesgos, supuestos y más.</div></div>
            </div>
            <div style="font-size:11px;text-transform:uppercase;letter-spacing:1.5px;color:var(--brown-light);margin-bottom:12px;">Lecturas clave</div>
            <div class="norm-key-findings">
              <div class="finding-card"><div class="finding-num">01</div><div class="finding-text">Predomina una visión del territorio como espacio físico a ordenar, zonificar, controlar y desarrollar.</div></div>
              <div class="finding-card"><div class="finding-num">02</div><div class="finding-text">La participación aparece nombrada de forma reiterada, pero bajo dispositivos formales que no garantizan incidencia efectiva.</div></div>
              <div class="finding-card"><div class="finding-num">03</div><div class="finding-text">Las categorías estatales no alcanzan a recoger territorialidades relacionales, históricas y comunitarias.</div></div>
              <div class="finding-card"><div class="finding-num">04</div><div class="finding-text">Lo comunitario suele ser aceptado en el discurso, pero traducido a marcos técnicos externos para poder ser reconocido.</div></div>
            </div>
            <div style="font-size:11px;text-transform:uppercase;letter-spacing:1.5px;color:var(--brown-light);margin-bottom:12px;">Normas e instrumentos destacados</div>
            <div class="norm-item"><div class="norm-name">Ley 388 de 1997</div><div class="norm-desc">Organiza el territorio desde clases de suelo, zonificación y regulación del desarrollo urbano-rural. Fuerte énfasis técnico y urbano, con limitada capacidad para reconocer territorialidades afro.</div></div>
            <div class="norm-item"><div class="norm-name">Ley 1454 de 2011</div><div class="norm-desc">Propone la organización político-administrativa del territorio y valora la autonomía regional, pero se mueve dentro de escalas institucionales predefinidas.</div></div>
            <div class="norm-item"><div class="norm-name">CONPES 3870 de 2016</div><div class="norm-desc">Impulsa la formulación de POT desde la modernización institucional con confianza marcada en la estandarización técnica como solución general.</div></div>
          </div>
          <div id="norm-negras" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Contenido sobre normatividad específica para comunidades negras · <em>próximamente</em></p></div>
          <div id="norm-agua" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Contenido sobre ordenamiento territorial alrededor del agua · <em>próximamente</em></p></div>
        </div>

        <!-- Mapas -->
        <div id="cm-mapas" class="hidden">
          <div class="section-tag">Mapa de invisibilización</div>
          <div class="section-heading">Invisibilización de la finca tradicional</div>
          <div class="section-subheading">Zonificación oficial vs. realidad territorial</div>
          <div class="text-nav-group" style="display:flex;gap:0;margin-bottom:24px;border-bottom:1px solid var(--sand);">
            <div class="inner-tab active" onclick="switchMapasTab(this,'map-invis')">Invisibilización finca</div>
            <div class="inner-tab" onclick="switchMapasTab(this,'map-agua')">Borrado cuerpos de agua</div>
            <div class="inner-tab" onclick="switchMapasTab(this,'map-terr')">Territorios sin reconocimiento</div>
          </div>
          <div id="map-invis">
            <div class="video-placeholder" style="max-width:100%;height:280px;">
              <!-- REEMPLAZA CON video o imagen de invisibilización -->
              <div class="video-play">▶</div>
            </div>
            <div class="video-caption" style="margin-top:8px;">Video: Proceso de invisibilización de la finca tradicional</div>
            <div style="margin-top:20px;">
              <div style="font-size:11px;text-transform:uppercase;letter-spacing:1.5px;color:var(--brown-light);margin-bottom:12px;">Mapas y anexos</div>
              <div style="display:flex;gap:12px;flex-wrap:wrap;">
                <div class="ref-dl">▸ Mapa de clasificación del suelo PBOT de Jamundí 2002</div>
                <div class="ref-dl">▸ Mapa de clasificación del suelo POT del Valle del Cauca 2014</div>
                <div class="ref-dl">▸ Mapa de cobertura de tierras IDEAM 2002</div>
              </div>
            </div>
          </div>
          <div id="map-agua" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Contenido sobre borrado de los cuerpos de agua · <em>próximamente</em></p></div>
          <div id="map-terr" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Contenido sobre territorios sin reconocimiento · <em>próximamente</em></p></div>
        </div>
      </div>
    </div>
  </div>

  <!-- ─── RECURSOS ─── -->
  <div id="screen-recursos" class="screen">
    <div class="text-screen">
      <div class="text-sidebar">
        <div class="text-sidebar-brand">
          <div class="brand-name">Recursos<br><span style="font-size:16px;opacity:.8;">y archivos</span></div>
        </div>
        <div class="text-nav-group">
          <div class="text-nav-item active" id="rec-nav-ref" onclick="switchRecTab('referencias')">
            <div class="text-nav-icon">📚</div>
            <div class="text-nav-label">Referencias</div>
          </div>
          <div class="text-nav-item" id="rec-nav-mapa" onclick="switchRecTab('armamapa')">
            <div class="text-nav-icon">🗺</div>
            <div class="text-nav-label">Arma tu mapa</div>
          </div>
          <div class="text-nav-item" id="rec-nav-dl" onclick="switchRecTab('descargas')">
            <div class="text-nav-icon">⬇</div>
            <div class="text-nav-label">Descargas</div>
          </div>
        </div>
      </div>
      <div class="text-main">
        <!-- Referencias -->
        <div id="rec-referencias">
          <div class="section-tag">Biblioteca del proyecto</div>
          <div class="section-heading">Artículos académicos</div>
          <div class="inner-tabs">
            <div class="inner-tab active" onclick="switchRefTab(this,'ref-art')">Artículos académicos</div>
            <div class="inner-tab" onclick="switchRefTab(this,'ref-web')">Páginas y recursos web</div>
            <div class="inner-tab" onclick="switchRefTab(this,'ref-met')">Metodologías</div>
          </div>
          <div id="ref-art">
            <div class="ref-item">
              <div class="ref-badge">ARTÍCULO</div>
              <div class="ref-content">
                <div class="ref-title">Ontologías relacionales y mundos plurales: más allá de la naturaleza–cultura</div>
                <div class="ref-author">Escobar, A. · Current Anthropology, 48(1), 2007</div>
                <div class="ref-tags"><div class="ref-tag">Ontología</div><div class="ref-tag">Territorio</div><div class="ref-tag">Pluriverso</div></div>
                <div class="ref-dl">⬇ Descargar artículo</div>
              </div>
            </div>
            <div class="ref-item">
              <div class="ref-badge">ARTÍCULO</div>
              <div class="ref-content">
                <div class="ref-title">Territorios de diferencia: lugar, movimientos, vida, redes</div>
                <div class="ref-author">Escobar, A. · Envión Editores, 2010</div>
                <div class="ref-tags"><div class="ref-tag">Territorio</div><div class="ref-tag">Comunidad</div><div class="ref-tag">Diferencia</div></div>
                <div class="ref-dl">⬇ Descargar artículo</div>
              </div>
            </div>
            <div class="ref-item">
              <div class="ref-badge">ARTÍCULO</div>
              <div class="ref-content">
                <div class="ref-title">La construcción del territorio: lugar, política y conocimiento</div>
                <div class="ref-author">Agnew, J. · Estudios Socioterritoriales, 2011</div>
                <div class="ref-tags"><div class="ref-tag">Territorio</div><div class="ref-tag">Política</div><div class="ref-tag">Conocimiento</div></div>
                <div class="ref-dl">⬇ Descargar artículo</div>
              </div>
            </div>
          </div>
          <div id="ref-web" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Páginas y recursos web · <em>próximamente</em></p></div>
          <div id="ref-met" class="hidden"><p style="font-size:13px;color:var(--brown-deep);line-height:1.7;">Metodologías · <em>próximamente</em></p></div>
        </div>

        <!-- Arma tu mapa -->
        <div id="rec-armamapa" class="hidden">
          <div class="section-tag">Herramienta de descarga</div>
          <div class="section-heading">Arma tu mapa</div>
          <p style="font-size:13px;color:var(--brown-deep);margin-bottom:20px;">Selecciona uno o varios consejos comunitarios de Jamundí y las capas que necesitas. Descarga tu mapa en el formato de tu preferencia para uso en SIG, análisis o presentaciones.</p>
          <div class="map-builder">
            <div class="builder-section">
              <div class="builder-num">01</div>
              <div class="builder-title">Selección del consejo</div>
              <div class="check-item" onclick="toggleCheck(this,'todos')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-todos"></div>Todos los consejos</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Robles')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Robles"></div>Robles</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Quinamayo')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Quinamayo"></div>Quinámayo</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Bocas')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Bocas"></div>Bocas del Palo</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Villa')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Villa"></div>Villa Paz</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Varejonal')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Varejonal"></div>Varejonal</span></div>
              <div class="check-item" onclick="toggleCheck(this,'Chagres')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-Chagres"></div>Chagres</span></div>
            </div>
            <div class="builder-section">
              <div class="builder-num">02</div>
              <div class="builder-title">Elige las capas</div>
              <div class="check-item" onclick="toggleCheck(this,'limites')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-limites"></div><div class="check-dot" style="background:var(--green-finca);"></div>Límites de Consejos Comunitarios</span></div>
              <div class="check-item" onclick="toggleCheck(this,'red_hidrica')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-red_hidrica"></div><div class="check-dot" style="background:var(--blue-river);"></div>Red hídrica</span></div>
              <div class="check-item" onclick="toggleCheck(this,'monocultivo')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-monocultivo"></div><div class="check-dot" style="background:#D4A843;"></div>Monocultivo de caña de azúcar</span></div>
              <div class="check-item" onclick="toggleCheck(this,'red_vial')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-red_vial"></div><div class="check-dot" style="background:var(--brown-deep);"></div>Red vial</span></div>
              <div class="check-item" onclick="toggleCheck(this,'urbanas')"><span style="display:flex;align-items:center;gap:8px;"><div class="check-box" id="chk-urbanas"></div><div class="check-dot" style="background:var(--gray-urban);"></div>Zonas urbanas</span></div>
            </div>
          </div>
          <div class="builder-section" style="margin-bottom:16px;">
            <div class="builder-num">03</div>
            <div class="builder-title">Formato de descarga</div>
            <div class="format-row">
              <button class="format-btn" onclick="selectFormat(this,'PDF')">PDF</button>
              <button class="format-btn" onclick="selectFormat(this,'PNG')">PNG</button>
            </div>
          </div>
          <div class="summary-section">
            <div style="font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--brown-light);margin-bottom:10px;">Resumen de tu selección</div>
            <div class="summary-row"><div class="summary-key">Consejos</div><div class="summary-val" id="sum-consejos">Ninguno seleccionado</div></div>
            <div class="summary-row"><div class="summary-key">Capas</div><div class="summary-val" id="sum-capas">Ninguno seleccionado</div></div>
            <div class="summary-row"><div class="summary-key">Formato</div><div class="summary-val" id="sum-formato">Ninguno seleccionado</div></div>
          </div>
          <button class="generate-btn">⬇ Generar y descargar mapa</button>
        </div>

        <!-- Descargas -->
        <div id="rec-descargas" class="hidden">
          <div class="section-tag">Herramienta de descarga</div>
          <div class="section-heading">Capas y archivos</div>
          <div class="inner-tabs">
            <div class="inner-tab active" onclick="switchDlTab(this,'dl-capas')">Capas geoespaciales</div>
            <div class="inner-tab" onclick="switchDlTab(this,'dl-mapas')">Mapas temáticos</div>
            <div class="inner-tab" onclick="switchDlTab(this,'dl-instr')">Instrumentos y datos</div>
          </div>
          <div id="dl-capas">
            <div class="dl-grid">
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Límites de consejos comunitarios</div><div class="dl-sub">Polígonos oficiales y comunitarios de los 6 consejos</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">2.4 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Red hídrica</div><div class="dl-sub">Ríos, quebradas y zanjones</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">3.6 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Red vial</div><div class="dl-sub">Vías, caminos y trochas</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">7.2 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Humedales</div><div class="dl-sub">Lagunas y madreviejas</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">9.6 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Finca tradicional</div><div class="dl-sub">Entorno de finca por consejo</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">4.8 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📁</div><div class="dl-title">Monocultivo de caña</div><div class="dl-sub">Cobertura caña 1961–2022</div><div class="dl-meta"><div class="dl-format">SHP / GeoJSON</div><div class="dl-size">5.1 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
            </div>
          </div>
          <div id="dl-mapas" class="hidden">
            <div class="dl-grid">
              <div class="dl-card"><div class="dl-icon-area">🗺</div><div class="dl-title">Mapa de cobertura 1961 vs 2024</div><div class="dl-sub">Cambio de cobertura de finca y caña en 2 décadas</div><div class="dl-meta"><div class="dl-format">PDF A2 300dpi</div><div class="dl-size">2.4 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">🗺</div><div class="dl-title">Mapa de invisibilización</div><div class="dl-sub">Contraste catastro oficial vs levantamiento comunitario</div><div class="dl-meta"><div class="dl-format">PDF A2 300dpi</div><div class="dl-size">3.6 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">🗺</div><div class="dl-title">Mapa hídrico comunitario</div><div class="dl-sub">Red de acequias y puntos de conflicto sobre el agua</div><div class="dl-meta"><div class="dl-format">PDF A2 300dpi</div><div class="dl-size">7.2 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">🗺</div><div class="dl-title">Borramiento de humedales</div><div class="dl-sub">Lagunas y madreviejas perdidas</div><div class="dl-meta"><div class="dl-format">PDF A2 300dpi</div><div class="dl-size">9.6 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
            </div>
          </div>
          <div id="dl-instr" class="hidden">
            <div class="dl-grid">
              <div class="dl-card"><div class="dl-icon-area">📋</div><div class="dl-title">Instrumento de encuesta</div><div class="dl-sub">Fincas tradicionales</div><div class="dl-meta"><div class="dl-format">PDF</div><div class="dl-size">2.4 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">📊</div><div class="dl-title">Base de datos encuesta</div><div class="dl-sub">Datos crudos de 233 fincas</div><div class="dl-meta"><div class="dl-format">XLSX</div><div class="dl-size">3.6 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
              <div class="dl-card"><div class="dl-icon-area">⚖️</div><div class="dl-title">Sistematización normativa</div><div class="dl-sub">Matriz comparativa de 10 normas</div><div class="dl-meta"><div class="dl-format">PDF</div><div class="dl-size">7.2 MB</div></div><div class="dl-btn">⬇ Descargar</div></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</div><!-- end #content -->

<!-- ═══════════════ FOOTER BAR ═══════════════ -->
<div id="footerbar">
  <button class="footer-btn" onclick="openTutorial()">
    <span class="btn-icon">🎬</span> Tutorial
  </button>
  <div id="footer-acerca" style="display:none;">
    <button class="footer-btn" onclick="openAcerca()">
      <span class="btn-icon">📄</span> Acerca de esta sección
    </button>
  </div>
  <button class="footer-btn" style="margin-left:auto;" onclick="openTimeline()">
    Línea de Tiempo
    <div class="timeline-dots">
      <div class="tdot"></div><div class="tdot"></div><div class="tdot"></div>
    </div>
  </button>
</div>

<!-- ═══════════════ MODAL OVERLAY ═══════════════ -->
<div id="modal-overlay">
  <div class="modal" id="modal-box">
    <div class="modal-header">
      <div class="modal-ornament">
        <div class="modal-ornament-line"></div>
        <div class="modal-ornament-icon">🌿</div>
        <div class="modal-ornament-line"></div>
      </div>
      <button class="modal-close" onclick="closeModal()">✕</button>
      <div class="modal-title" id="modal-title">Bienvenido</div>
      <div class="modal-divider"></div>
    </div>
    <div class="modal-body" id="modal-body"></div>
    <div class="modal-footer" id="modal-footer">
      <button class="modal-explore-btn" onclick="closeModal()">Explorar →</button>
    </div>
  </div>
</div>

<!-- ═══════════════ JAVASCRIPT ═══════════════ -->
<!-- ═══════════════ JAVASCRIPT ═══════════════ -->
<script>
// ── State ──
let currentScreen = 'home';
let currentConsejo = '';
let selectedConsejosMap = {};
let selectedCapas = {};
let selectedFormat = '';

// ════════════════════════════════════════════════════════════════
// DATOS DE CONFIGURACIÓN — IMÁGENES OVERLAY HOME
// Reemplaza '' con la ruta de tus imágenes (mismas dimensiones que el fondo)
// ════════════════════════════════════════════════════════════════
const homeOverlayImages = {
  finca: 'capa_fincatradicional.png',       // ej: 'overlays/home-finca.png'
  rio: 'capa_riocauca.png',         // ej: 'overlays/home-rio.png'
  humedales: 'capa_riocauca.png',   // ej: 'overlays/home-humedales.png'
};

// Imágenes overlay por consejo al hacer hover en el home
const homeConsejoOverlayImages = {
  'Bocas del Palo':   'capa bocas del palo.png',  // ej: 'overlays/home-bocas.png'
  'Paso de La Bolsa': 'capa paso de la bolsa.png',
  'La Ventura':       'capa la ventura.png',
  'Villa Paz':        'capa villa paz.png',
  'Quinamayo':        'capa quinamayo.png',
  'Robles':           'capa robles.png',
  'Chagres':          'capa chagres.png',
  'Varejonal':        '',
  'San Isidro':       '',
};

// ════════════════════════════════════════════════════════════════
// DATOS — IMÁGENES OVERLAY FINCA VARIABLES
// Cada variable tiene una imagen overlay y una descripción
// ════════════════════════════════════════════════════════════════
const variableOverlayImages = {
  'Tenencia de la tierra':      'capa_riocauca.png',   // ej: 'overlays/finca-tenencia.png'
  'Área de la finca':           '',
  'Cultivos presentes':         '',
  'Uso del suelo':              '',
  'Fuentes de agua':            '',
  'Presión territorial':        '',
  'Uso de monte':               '',
  'Trabajo comunitario':        '',
  'Tiempo de ocupación':        '',
  'Biodiversidad productiva':   '',
  'Acceso a servicios':         '',
};

const variableDescriptions = {
  'Tenencia de la tierra':      'Tipo de propiedad o posesión del terreno: colectiva, individual, arrendada o prestada dasdasdad.',
  'Área de la finca':           'Extensión en hectáreas de cada finca encuestada dentro del territorio del consejo.',
  'Cultivos presentes':         'Diversidad de especies cultivadas: plátano, yuca, maíz, chontaduro, frutales y medicinales.',
  'Uso del suelo':              'Distribución del suelo entre cultivos, monte, potrero, vivienda y zonas de descanso.',
  'Fuentes de agua':            'Acceso a ríos, quebradas, acequias, pozos y otros cuerpos de agua dentro de la finca.',
  'Presión territorial':        'Grado de amenaza percibida por expansión de monocultivo, urbanización o conflicto armado.',
  'Uso de monte':               'Práctica de aprovechamiento del monte para leña, plantas medicinales, frutos y fauna.',
  'Trabajo comunitario':        'Participación en mingas, convites y otras formas de trabajo colectivo en el territorio.',
  'Tiempo de ocupación':        'Años de permanencia de la familia en la finca y el territorio del consejo.',
  'Biodiversidad productiva':   'Número y variedad de especies animales y vegetales presentes en la finca.',
  'Acceso a servicios':         'Disponibilidad de servicios básicos: agua potable, electricidad, salud y educación.',
};

// ════════════════════════════════════════════════════════════════
// DATOS — IMÁGENES OVERLAY RÍO Y HUMEDALES
// Múltiples capas pueden estar activas simultáneamente
// ════════════════════════════════════════════════════════════════
const rioYearOverlayImages = {
  '1960': 'capa_riocauca.png',  '1970': '',  '1980': 'capa_riocauca.png',  '1990': '',
  '2000': '',  '2010': '',  '2020': '',
};

const humedalYearsList = ['1960','1970','1980','1990','2000','2010','2020','2024'];
const humedalYearOverlayImages = {
  '1960': 'capa_riocauca.png',  '1970': '',  '1980': '',  '1990': '',
  '2000': '',  '2010': '',  '2020': '',  '2024': '',
};

// ════════════════════════════════════════════════════════════════
// MODAL CONTENTS
// ════════════════════════════════════════════════════════════════
const modalContents = {
  home: { title:'Bienvenido', body:`Bienvenido a este el espacio donde las comunidades afrodescendientes de Jamundí han sostenido su vida durante generaciones. Un lugar de siembra, de memoria y de resistencia frente al avance del monocultivo de caña de azúcar.<br><br>En esta sección puedes explorar los consejos comunitarios, la línea de tiempo del proyecto y navegar por las secciones de la plataforma a través del menú superior.` },
  finca:{ title:'La finca tradicional', body:`La finca tradicional es el espacio donde las comunidades afrodescendientes de Jamundí han sostenido su vida durante generaciones. Un lugar de siembra, de memoria y de resistencia frente al avance del monocultivo de caña de azúcar.<br><br>En esta sección puedes explorar las variables de la encuesta comunitaria. Selecciona una variable para ver su capa correspondiente sobre el mapa. Cada variable incluye un ícono ⓘ con información detallada.` },
  rio:{ title:'El río y los humedales', body:`El río y los humedales es el espacio donde las comunidades afrodescendientes de Jamundí han sostenido su vida durante generaciones.<br><br>En esta sección puedes explorar la multitemporalidad del río Cauca y los humedales. Puedes activar varias capas a la vez para comparar diferentes períodos.` },
  quienes:{ title:'¿Quiénes somos?', body:`Geografías negras es una plataforma cartográfica participativa que documenta las prácticas territoriales de las comunidades afrodescendientes de Jamundí, en el sur del Valle del Cauca.<br><br>En esta sección encontrarás información sobre el proyecto, los consejos comunitarios participantes y el equipo de investigación.` },
  contramapeo:{ title:'Contramapeo', body:`El contramapeo es una práctica colectiva de producción de conocimiento geográfico desde las comunidades. En esta sección encontrarás los talleres realizados, la sistematización normativa y los mapas.` },
  recursos:{ title:'Recursos y archivos', body:`En esta sección encontrarás la biblioteca de referencias académicas, la herramienta para construir tu mapa y los archivos disponibles para descarga.` },
};

function showModal(key, extraBtn){
  const m = modalContents[key]; if(!m) return;
  document.getElementById('modal-title').textContent = m.title;
  document.getElementById('modal-body').innerHTML = m.body;
  const footer = document.getElementById('modal-footer');
  footer.innerHTML = `<button class="modal-explore-btn" onclick="closeModal()">Explorar &rarr;</button>`;
  if(extraBtn) footer.insertAdjacentHTML('afterbegin', extraBtn);
  document.getElementById('modal-overlay').classList.add('open');
}
function closeModal(){ document.getElementById('modal-overlay').classList.remove('open'); }

// ════════════════════════════════════════════════════════════════
// HOME — OVERLAY INTERACTIONS
// ════════════════════════════════════════════════════════════════
function showHomeOverlay(type){
  const src = homeOverlayImages[type] || '';
  const el = document.getElementById('home-overlay-'+type);
  if(el && src){ el.src = src; el.classList.add('visible'); }
}
function hideHomeOverlay(type){
  const el = document.getElementById('home-overlay-'+type);
  if(el) el.classList.remove('visible');
}
function showConsejoOverlay(name){
  const src = homeConsejoOverlayImages[name] || '';
  const el = document.getElementById('home-overlay-consejo');
  if(el && src){ el.src = src; el.classList.add('visible'); }
}
function hideConsejoOverlay(){
  const el = document.getElementById('home-overlay-consejo');
  if(el) el.classList.remove('visible');
}

// ════════════════════════════════════════════════════════════════
// NAVIGATION
// ════════════════════════════════════════════════════════════════
function showScreen(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.getElementById('screen-'+id).classList.add('active');
  currentScreen = id;
  const subheaderMap = { finca:{icon:'🌿',title:'La finca tradicional'}, rio:{icon:'〰️',title:'Río Cauca y humedales'}, quienes:{icon:'👥',title:'¿Quiénes somos?'}, contramapeo:{icon:'🗺',title:'Contramapeo'}, recursos:{icon:'📚',title:'Recursos y archivos'} };
  const sh = document.getElementById('subheader');
  const acercaBtn = document.getElementById('footer-acerca');
  if(subheaderMap[id]){
    sh.style.display='flex';
    document.getElementById('subheader-icon').textContent = subheaderMap[id].icon;
    document.getElementById('subheader-title').textContent = subheaderMap[id].title;
    document.getElementById('content').classList.add('with-subheader');
    acercaBtn.style.display='block';
  } else {
    sh.style.display='none';
    document.getElementById('content').classList.remove('with-subheader');
    acercaBtn.style.display='none';
  }
}
function goHome(){ showScreen('home'); }
function showSection(section, sub){
  const s = {quienes:'quienes',finca:'finca',contramapeo:'contramapeo',rio:'rio',recursos:'recursos'}[section] || section;
  showScreen(s);
  if(!sub) showModal(s);
  if(sub){
    if(section==='quienes') switchQSTab(sub);
    if(section==='finca' && sub==='cambios') openComparator();
    if(section==='contramapeo') switchCMTab(sub);
    if(section==='recursos') switchRecTab(sub);
  }
}
function openConsejo(type){ showSection('finca'); }

// ── Consejo detail ──
function openConsejoDetail(name){
  currentConsejo = name;
  document.getElementById('consejo-name-display').textContent = name;
  document.getElementById('audio-consejo-name').textContent = name;
  showScreen('consejo');
  openConsejoPanelTab('loc');
  generateWaveBars();
  updateConsejoBackground(name);
  updateLocImage(name);
  loadConsejoGallery(name);
  loadConsejoAudio(name);
}
function openConsejoPanelTab(tab){
  ['loc','audio','imgs'].forEach(t=>{ document.getElementById('panel-'+t).classList.add('hidden'); document.getElementById('ctab-'+t).classList.remove('active'); });
  document.getElementById('panel-'+tab).classList.remove('hidden');
  document.getElementById('ctab-'+tab).classList.add('active');
  document.getElementById('consejo-panel').classList.add('open');
}
function closeConsejoPanel(){ document.getElementById('consejo-panel').classList.remove('open'); }
function generateWaveBars(){
  const c = document.getElementById('wave-bars'); c.innerHTML='';
  for(let i=0;i<30;i++){ const b=document.createElement('div'); b.className='wave-bar'; b.style.height=Math.floor(Math.random()*28+4)+'px'; c.appendChild(b); }
}

// ════════════════════════════════════════════════════════════════
// FINCA — VARIABLES LIST WITH INFO ICONS & OVERLAY
// ════════════════════════════════════════════════════════════════
const variables = ['Tenencia de la tierra','Área de la finca','Cultivos presentes','Uso del suelo','Fuentes de agua','Presión territorial','Uso de monte','Trabajo comunitario','Tiempo de ocupación','Biodiversidad productiva','Acceso a servicios'];
let activeVariable = '';

function buildVariablesList(){
  const c = document.getElementById('variables-list'); c.innerHTML='';
  variables.forEach((v,i)=>{
    const d = document.createElement('div');
    d.className = 'sidebar-item';
    d.style.cssText = 'display:flex;align-items:center;gap:8px;justify-content:space-between;';
    const left = document.createElement('div');
    left.style.cssText = 'display:flex;align-items:center;gap:10px;flex:1;cursor:pointer;';
    left.innerHTML = `<div class="sidebar-radio"></div><span>${v}</span>`;
    const info = document.createElement('div');
    info.className = 'var-info-icon';
    info.innerHTML = `i<div class="var-info-tooltip">${variableDescriptions[v]||'Información sobre esta variable.'}</div>`;
    info.onclick = (e) => { e.stopPropagation(); toggleVarInfo(info); };
    left.onclick = () => selectVariable(v, d);
    d.appendChild(left);
    d.appendChild(info);
    c.appendChild(d);
  });
}

function toggleVarInfo(iconEl){
  const tooltip = iconEl.querySelector('.var-info-tooltip');
  if(!tooltip) return;
  const wasOpen = tooltip.classList.contains('open');
  document.querySelectorAll('.var-info-tooltip.open').forEach(t => t.classList.remove('open'));
  if(!wasOpen) tooltip.classList.add('open');
}
document.addEventListener('click', function(e){
  if(!e.target.closest('.var-info-icon')){
    document.querySelectorAll('.var-info-tooltip.open').forEach(t => t.classList.remove('open'));
  }
});

function selectVariable(varName, el){
  const c = document.getElementById('variables-list');
  c.querySelectorAll('.sidebar-item').forEach(item=>{ item.classList.remove('active'); const r=item.querySelector('.sidebar-radio'); if(r) r.classList.remove('checked'); });
  const overlay = document.getElementById('finca-variable-overlay');
  if(activeVariable === varName){ activeVariable=''; if(overlay) overlay.classList.remove('visible'); return; }
  activeVariable = varName;
  el.classList.add('active');
  const radio = el.querySelector('.sidebar-radio'); if(radio) radio.classList.add('checked');
  const src = variableOverlayImages[varName] || '';
  if(overlay){ if(src){ overlay.src=src; overlay.classList.add('visible'); } else { overlay.classList.remove('visible'); } }
}

// ════════════════════════════════════════════════════════════════
// FINCA — POPUP & COMPARATOR
// ════════════════════════════════════════════════════════════════
function openFincaConsejo(name){
  document.getElementById('popup-consejo-name').textContent = name;
  document.getElementById('finca-popup').classList.add('open');
  switchPopupTab(document.querySelector('#finca-popup .popup-tab'),'tab-imgs');
  loadFincaGallery(name);
}
function closeFincaPopup(){ document.getElementById('finca-popup').classList.remove('open'); }
function switchPopupTab(el, tabId){
  const popup = el.closest('.consejo-popup');
  popup.querySelectorAll('.popup-tab').forEach(t=>t.classList.remove('active'));
  el.classList.add('active');
  popup.querySelectorAll('.popup-body > div').forEach(d=>{ d.classList.add('hidden'); if(d.id===tabId) d.classList.remove('hidden'); });
}
function openComparator(){ document.getElementById('finca-comparator').classList.add('open'); }
function closeComparator(){ document.getElementById('finca-comparator').classList.remove('open'); }

// ════════════════════════════════════════════════════════════════
// RÍO — MULTITEMPORAL WITH CHECKBOXES (multiple active)
// ════════════════════════════════════════════════════════════════
const rioYears = ['1960','1970','1980','1990','2000','2010','2020'];
let activeRioYears = {};
let activeHumedalYears = {};

function buildRioYears(){
  const c = document.getElementById('rio-years'); if(!c) return;
  rioYears.forEach(y=>{
    const d = document.createElement('div');
    d.className = 'sidebar-item'; d.style.cursor='pointer';
    d.innerHTML = `<div class="sidebar-check" id="rio-chk-${y}"></div>${y} <span style="margin-left:6px;font-size:14px;opacity:.6;">〰️</span>`;
    d.onclick = () => toggleRioYear(y);
    c.appendChild(d);
  });
}

function toggleRioYear(year){
  const chk = document.getElementById('rio-chk-'+year); if(!chk) return;
  if(activeRioYears[year]){
    delete activeRioYears[year]; chk.classList.remove('checked');
    const ov = document.getElementById('rio-overlay-'+year); if(ov) ov.remove();
  } else {
    activeRioYears[year] = true; chk.classList.add('checked');
    const src = rioYearOverlayImages[year] || '';
    if(src){
      const container = document.getElementById('rio-overlays-container');
      const img = document.createElement('img');
      img.id='rio-overlay-'+year; img.className='overlay-layer'; img.src=src; img.alt='Río Cauca '+year;
      img.style.cssText='position:absolute;inset:0;width:100%;height:100%;object-fit:cover;';
      container.appendChild(img);
      requestAnimationFrame(()=>img.classList.add('visible'));
    }
  }
}

function buildHumedalYears(){
  const c = document.getElementById('humedal-years'); if(!c) return;
  humedalYearsList.forEach(y=>{
    const d = document.createElement('div');
    d.className='sidebar-item'; d.style.cursor='pointer';
    d.innerHTML = `<div class="sidebar-check" id="hum-chk-${y}"></div>${y} <span style="margin-left:6px;font-size:14px;opacity:.6;">💧</span>`;
    d.onclick = () => toggleHumedalYear(y);
    c.appendChild(d);
  });
}

function toggleHumedalYear(year){
  const chk = document.getElementById('hum-chk-'+year); if(!chk) return;
  if(activeHumedalYears[year]){
    delete activeHumedalYears[year]; chk.classList.remove('checked');
    const ov = document.getElementById('hum-overlay-'+year); if(ov) ov.remove();
  } else {
    activeHumedalYears[year] = true; chk.classList.add('checked');
    const src = humedalYearOverlayImages[year] || '';
    if(src){
      const container = document.getElementById('humedal-overlays-container');
      const img = document.createElement('img');
      img.id='hum-overlay-'+year; img.className='overlay-layer'; img.src=src; img.alt='Humedales '+year;
      img.style.cssText='position:absolute;inset:0;width:100%;height:100%;object-fit:cover;';
      container.appendChild(img);
      requestAnimationFrame(()=>img.classList.add('visible'));
    }
  }
}

// ── Rio popup ──
function openHumedalConsejo(name){ document.getElementById('rio-popup-name').textContent=name; document.getElementById('rio-popup').classList.add('open'); }
function closeRioPopup(){ document.getElementById('rio-popup').classList.remove('open'); }
function openHumedalesComparator(){ document.getElementById('rio-comparator').classList.add('open'); }
function closeRioComparator(){ document.getElementById('rio-comparator').classList.remove('open'); }
function openErosionModal(){ document.getElementById('erosion-popup').style.display='block'; }

// ════════════════════════════════════════════════════════════════
// TUTORIAL / ACERCA / TIMELINE
// ════════════════════════════════════════════════════════════════
function openTutorial(){
  document.getElementById('modal-title').textContent = 'Tutorial';
  document.getElementById('modal-body').innerHTML = `<div class="tutorial-video"><div class="tutorial-play">▶</div><div class="tutorial-label">Haz clic para reproducir el tutorial</div></div><p style="margin-top:16px;font-size:13px;line-height:1.7;">Este video te explica cómo navegar la plataforma Geografías Negras.</p>`;
  document.getElementById('modal-footer').innerHTML = `<button class="modal-explore-btn" onclick="closeModal()">Cerrar</button>`;
  document.getElementById('modal-overlay').classList.add('open');
}
function openAcerca(){ showModal(currentScreen in modalContents ? currentScreen : 'home'); }
function openTimeline(){
  let html = `<div class="timeline-scroll"><div style="display:flex;flex-direction:column;gap:0;">`;
  html += `<div style="display:flex;align-items:center;gap:0;min-width:640px;">`;
  html += `<div style="display:flex;flex-direction:column;align-items:center;"><div style="width:44px;height:44px;border-radius:50%;background:#3D2B1F;display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:12px;">2024</div></div>`;
  html += `<div style="flex:1;height:2px;background:var(--sand);"></div>`;
  html += `<div style="display:flex;flex-direction:column;align-items:center;"><div style="font-family:'Cormorant Garamond',serif;font-size:22px;font-weight:600;color:var(--brown-deep);padding:0 12px;">2025</div></div>`;
  html += `<div style="flex:1;height:2px;background:var(--sand);"></div>`;
  html += `<div style="display:flex;flex-direction:column;align-items:center;"><div style="width:44px;height:44px;border-radius:50%;background:#B5541C;display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:12px;">2026</div></div></div>`;
  html += `<div style="display:flex;gap:0;min-width:640px;margin-top:16px;padding:0 22px;">`;
  html += `<div style="min-width:120px;"><div style="font-size:10px;font-weight:700;color:var(--brown-mid);">Inicio</div><div style="font-size:11px;color:var(--brown-deep);">Sistematización<br>Normativa</div></div>`;
  [{m:'Feb',t:'Taller de Protocolo'},{m:'Feb–Jul',t:'Entrevistas'},{m:'Marzo',t:'Taller de Identificación Territorial'},{m:'Abril',t:'Taller de Encuesta'},{m:'Julio',t:'Taller de Etnodesarrollo'},{m:'Sep',t:'Taller de Territorio Ancestral'}].forEach(e=>{
    html+=`<div style="flex:1;text-align:center;"><div style="font-size:10px;font-weight:700;color:var(--brown-mid);">${e.m}</div><div style="font-size:11px;color:var(--brown-deep);line-height:1.3;">${e.t}</div></div>`;
  });
  html+=`<div style="min-width:120px;text-align:right;"><div style="font-size:10px;font-weight:700;color:#B5541C;">2026</div><div style="font-size:11px;color:var(--brown-deep);">Producción<br>Cartográfica<br>Plataforma</div></div></div></div></div>`;
  document.getElementById('modal-title').textContent = 'Línea de Tiempo';
  document.getElementById('modal-body').innerHTML = html;
  document.getElementById('modal-footer').innerHTML = `<button class="modal-explore-btn" onclick="closeModal()">Cerrar</button>`;
  document.getElementById('modal-overlay').classList.add('open');
}

// ════════════════════════════════════════════════════════════════
// TABS
// ════════════════════════════════════════════════════════════════
function switchQSTab(tab){ ['proyecto','consejos','equipo'].forEach(t=>{ document.getElementById('qs-'+t).classList.add('hidden'); document.getElementById('qs-nav-'+t).classList.remove('active'); }); document.getElementById('qs-'+tab).classList.remove('hidden'); document.getElementById('qs-nav-'+tab).classList.add('active'); }
function switchCMTab(tab){ ['talleres','normativa','mapas'].forEach(t=>{ const el=document.getElementById('cm-'+t); if(el) el.classList.add('hidden'); const nav=document.getElementById('cm-nav-'+t); if(nav) nav.classList.remove('active'); }); const el=document.getElementById('cm-'+tab); if(el) el.classList.remove('hidden'); const nav=document.getElementById('cm-nav-'+tab); if(nav) nav.classList.add('active'); if(tab==='talleres') el.style.display='flex'; }
function switchTallerTab(el,tabId){ el.closest('.inner-tabs').querySelectorAll('.inner-tab').forEach(t=>t.classList.remove('active')); el.classList.add('active'); ['tt-obj','tt-mem','tt-res','tt-imgs'].forEach(t=>{ const d=document.getElementById(t); if(d) d.classList.add('hidden'); }); const target=document.getElementById(tabId); if(target) target.classList.remove('hidden'); }
function switchNormTab(el,tabId){ el.closest('.text-nav-group').querySelectorAll('.inner-tab').forEach(t=>t.classList.remove('active')); el.classList.add('active'); ['norm-general','norm-negras','norm-agua'].forEach(t=>{ const d=document.getElementById(t); if(d) d.classList.add('hidden'); }); document.getElementById(tabId).classList.remove('hidden'); }
function switchMapasTab(el,tabId){ el.closest('.text-nav-group').querySelectorAll('.inner-tab').forEach(t=>t.classList.remove('active')); el.classList.add('active'); ['map-invis','map-agua','map-terr'].forEach(t=>{ const d=document.getElementById(t); if(d) d.classList.add('hidden'); }); document.getElementById(tabId).classList.remove('hidden'); }
function switchRecTab(tab){ ['referencias','armamapa','descargas'].forEach(t=>{ const el=document.getElementById('rec-'+t); if(el) el.classList.add('hidden'); const nav=document.getElementById('rec-nav-'+({referencias:'ref',armamapa:'mapa',descargas:'dl'}[t])); if(nav) nav.classList.remove('active'); }); document.getElementById('rec-'+tab).classList.remove('hidden'); const navKey={referencias:'ref',armamapa:'mapa',descargas:'dl'}[tab]; const nav=document.getElementById('rec-nav-'+navKey); if(nav) nav.classList.add('active'); }
function switchRefTab(el,tabId){ el.closest('.inner-tabs').querySelectorAll('.inner-tab').forEach(t=>t.classList.remove('active')); el.classList.add('active'); ['ref-art','ref-web','ref-met'].forEach(t=>{ const d=document.getElementById(t); if(d) d.classList.add('hidden'); }); document.getElementById(tabId).classList.remove('hidden'); }
function switchDlTab(el,tabId){ el.closest('.inner-tabs').querySelectorAll('.inner-tab').forEach(t=>t.classList.remove('active')); el.classList.add('active'); ['dl-capas','dl-mapas','dl-instr'].forEach(t=>{ const d=document.getElementById(t); if(d) d.classList.add('hidden'); }); document.getElementById(tabId).classList.remove('hidden'); }

// ════════════════════════════════════════════════════════════════
// TALLER LIST
// ════════════════════════════════════════════════════════════════
const talleres = [
  {n:'01',t:'Taller 1',loc:'Univ. Autónoma de Occidente',title:'Socialización y relacionamiento',date:'12/12/2024'},
  {n:'02',t:'Taller 2',loc:'Univ. Autónoma de Occidente',title:'Cartografía participativa',date:'15/01/2025'},
  {n:'03',t:'Taller 3',loc:'Univ. Autónoma de Occidente',title:'Identificación territorial',date:'20/02/2025'},
  {n:'04',t:'Taller 4',loc:'Univ. Autónoma de Occidente',title:'Encuesta comunitaria',date:'10/03/2025'},
  {n:'05',t:'Taller 5',loc:'Univ. Autónoma de Occidente',title:'Etnodesarrollo',date:'05/04/2025'},
  {n:'06',t:'Taller 6',loc:'Univ. Autónoma de Occidente',title:'Capacitación en SIG',date:'18/05/2025'},
  {n:'07',t:'Taller 7',loc:'Univ. Autónoma de Occidente',title:'Territorio ancestral',date:'10/09/2025'},
];
function buildTallerList(){
  const c=document.getElementById('taller-list'); if(!c) return;
  talleres.forEach((t,i)=>{ const d=document.createElement('div'); d.className='taller-item'+(i===0?' active':''); d.innerHTML=`<div class="taller-num">${t.n}</div><div class="taller-info"><div class="t-title">${t.t}</div><div class="t-loc">${t.loc}</div></div>`; d.onclick=()=>{ c.querySelectorAll('.taller-item').forEach(el=>el.classList.remove('active')); d.classList.add('active'); document.getElementById('taller-tag').textContent='Taller '+t.n; document.getElementById('taller-heading').textContent=t.title; document.getElementById('taller-date').textContent='FECHA: '+t.date; }; c.appendChild(d); });
}

// ════════════════════════════════════════════════════════════════
// CONSEJO IMAGES / BG / LOC / AUDIO
// ════════════════════════════════════════════════════════════════
const consejoLocImages = {'Robles':'','Quinamayo':'','Varejonal':'','Villa Paz':'','Chagres':'','Bocas del Palo':'','Paso de La Bolsa':'','La Ventura':'','San Isidro':''};
const consejoBgImages = {'Robles':'consejo_de_robles.png','Quinamayo':'','Varejonal':'','Villa Paz':'','Chagres':'','Bocas del Palo':'','Paso de La Bolsa':'','La Ventura':'','San Isidro':''};

function updateConsejoBackground(name){
  const src=consejoBgImages[name]||''; const img=document.getElementById('consejo-bg-img');
  if(src){ img.src=src.split('/').map(s=>encodeURIComponent(s)).join('/'); img.style.display='block'; }
  else { img.src=''; img.style.display='none'; }
}
function updateLocImage(name){
  const src=consejoLocImages[name]||''; const img=document.getElementById('loc-map-img'); const fb=document.getElementById('loc-map-fallback');
  if(src){ img.src=src; img.style.display='block'; fb.style.display='none'; } else { img.style.display='none'; fb.style.display='flex'; }
}
function togglePlay(btn){ if(btn.textContent.trim()==='▶') btn.textContent='⏸'; else btn.textContent='▶'; }

// ════════════════════════════════════════════════════════════════
// MAP BUILDER
// ════════════════════════════════════════════════════════════════
function toggleCheck(el,key){ const box=el.querySelector('.check-box')||document.getElementById('chk-'+key); const isChecked=box.classList.toggle('checked'); if(isChecked) box.textContent='✓'; else box.textContent=''; updateSummary(); }
function selectFormat(btn,fmt){ document.querySelectorAll('.format-btn').forEach(b=>b.classList.remove('selected')); btn.classList.add('selected'); selectedFormat=fmt; updateSummary(); }
function updateSummary(){
  const checked=[]; document.querySelectorAll('[id^="chk-"]:not(#chk-todos)').forEach(b=>{ if(b.classList.contains('checked')){ const key=b.id.replace('chk-',''); if(['Robles','Quinamayo','Bocas','Villa','Varejonal','Chagres'].includes(key)) checked.push(key); } });
  const capas=[]; ['limites','red_hidrica','monocultivo','red_vial','urbanas'].forEach(k=>{ const b=document.getElementById('chk-'+k); if(b&&b.classList.contains('checked')) capas.push(k.replace('_',' ')); });
  const todosChk=document.getElementById('chk-todos');
  document.getElementById('sum-consejos').textContent = (todosChk&&todosChk.classList.contains('checked'))?'Todos':(checked.length?checked.join(', '):'Ninguno seleccionado');
  document.getElementById('sum-capas').textContent = capas.length?capas.join(', '):'Ninguno seleccionado';
  document.getElementById('sum-formato').textContent = selectedFormat||'Ninguno seleccionado';
}

// ════════════════════════════════════════════════════════════════
// IMÁGENES POR CONSEJO
// ════════════════════════════════════════════════════════════════
const fincaConsejoImages = {'Bocas del Palo':['','',''],'Paso de La Bolsa':['','',''],'La Ventura':['','',''],'Villa Paz':['','',''],'Quinamayo':['','',''],'Robles':['','',''],'Chagres':['','',''],'Varejonal':['','','']};
const fincaConsejoCaptions = {'Bocas del Palo':['Cultivos en Bocas del Palo','Vista del territorio','Finca tradicional'],'Paso de La Bolsa':['Cultivos en Paso de La Bolsa','Vista del territorio','Finca tradicional'],'La Ventura':['Cultivos en La Ventura','Vista del territorio','Finca tradicional'],'Villa Paz':['Cultivos en Villa Paz','Vista del territorio','Finca tradicional'],'Quinamayo':['Cultivos en Quinamayo','Vista del territorio','Finca tradicional'],'Robles':['Cultivos en Robles','Vista del territorio','Finca tradicional'],'Chagres':['Cultivos en Chagres','Vista del territorio','Finca tradicional'],'Varejonal':['Cultivos en Varejonal','Vista del territorio','Finca tradicional']};
const consejoImages = {'Bocas del Palo':[{src:'',cap:'Imagen 01 — Bocas del Palo'},{src:'',cap:'Imagen 02'},{src:'',cap:'Imagen 03'}],'San Isidro':[{src:'',cap:'Imagen 01 — San Isidro'},{src:'',cap:'Imagen 02'}],'Paso de La Bolsa':[{src:'',cap:'Imagen 01 — Paso de La Bolsa'},{src:'',cap:'Imagen 02'}],'La Ventura':[{src:'',cap:'Imagen 01 — La Ventura'},{src:'',cap:'Imagen 02'}],'Villa Paz':[{src:'',cap:'Imagen 01 — Villa Paz'},{src:'',cap:'Imagen 02'}],'Quinamayo':[{src:'',cap:'Imagen 01 — Quinamayo'},{src:'',cap:'Imagen 02'}],'Robles':[{src:'',cap:'Imagen 01 — Robles'},{src:'',cap:'Imagen 02'}],'Chagres':[{src:'',cap:'Imagen 01 — Chagres'},{src:'',cap:'Imagen 02'}],'Varejonal':[{src:'',cap:'Imagen 01 — Varejonal'},{src:'',cap:'Imagen 02'}]};
const consejoAudios = {'Bocas del Palo':'','San Isidro':'','Paso de La Bolsa':'','La Ventura':'','Villa Paz':'','Quinamayo':'','Robles':'','Chagres':'','Varejonal':''};

// ════════════════════════════════════════════════════════════════
// GALLERIES
// ════════════════════════════════════════════════════════════════
let fincaGalleryIdx=0, fincaGalleryTotal=3, currentFincaConsejoName='';
function loadFincaGallery(name){ currentFincaConsejoName=name; fincaGalleryIdx=0; const imgs=fincaConsejoImages[name]||['','','']; fincaGalleryTotal=imgs.length; imgs.forEach((src,i)=>{ const el=document.getElementById('finca-img-'+(i+1)); if(el){el.src=src;el.style.display='none';} }); fincaGalleryShow(0); }
function fincaGalleryShow(idx){ const imgs=fincaConsejoImages[currentFincaConsejoName]||[]; const captions=fincaConsejoCaptions[currentFincaConsejoName]||[]; [1,2,3].forEach(i=>{const el=document.getElementById('finca-img-'+i);if(el)el.style.display='none';}); const ph=document.getElementById('finca-img-placeholder'); const src=imgs[idx]||''; const el=document.getElementById('finca-img-'+(idx+1)); if(el&&src){el.src=src;el.style.display='block';if(ph)ph.style.display='none';} else{if(ph)ph.style.display='flex';} const cap=document.getElementById('finca-gallery-caption'); if(cap)cap.textContent=captions[idx]||('Imagen '+(idx+1)+' del consejo'); document.querySelectorAll('#finca-gallery-dots .gdot').forEach((d,i)=>{d.style.background=i===idx?'var(--brown-mid)':'var(--sand)';}); }
function fincaGalleryNav(dir){ const imgs=fincaConsejoImages[currentFincaConsejoName]||[]; fincaGalleryIdx=(fincaGalleryIdx+dir+imgs.length)%imgs.length; fincaGalleryShow(fincaGalleryIdx); }
function fincaGalleryGoto(idx){ fincaGalleryIdx=idx; fincaGalleryShow(idx); }

let consejoGalleryIdx=0, currentConsejoGallery=[];
function loadConsejoGallery(name){ currentConsejoGallery=consejoImages[name]||[{src:'',cap:'Imagen del consejo'}]; consejoGalleryIdx=0; buildConsejoGalleryDots(); consejoGalleryShow(0); }
function buildConsejoGalleryDots(){ const c=document.getElementById('consejo-gallery-dots'); if(!c)return; c.innerHTML=''; currentConsejoGallery.forEach((_,i)=>{ const s=document.createElement('span'); s.style.cssText='width:8px;height:8px;border-radius:50%;display:inline-block;cursor:pointer;'; s.style.background=i===0?'var(--brown-mid)':'var(--sand)'; s.onclick=()=>{consejoGalleryIdx=i;consejoGalleryShow(i);}; c.appendChild(s); }); }
function consejoGalleryShow(idx){ const item=currentConsejoGallery[idx]||{src:'',cap:''}; const img=document.getElementById('consejo-img-current'); const fb=document.getElementById('consejo-img-fallback'); const cap=document.getElementById('consejo-gallery-caption'); if(img){if(item.src){img.src=item.src;img.style.display='block';if(fb)fb.style.display='none';}else{img.style.display='none';if(fb)fb.style.display='flex';}} if(cap)cap.textContent=item.cap||('Imagen '+(idx+1)); document.querySelectorAll('#consejo-gallery-dots span').forEach((d,i)=>{d.style.background=i===idx?'var(--brown-mid)':'var(--sand)';}); }
function consejoGalleryNav(dir){ consejoGalleryIdx=(consejoGalleryIdx+dir+currentConsejoGallery.length)%currentConsejoGallery.length; consejoGalleryShow(consejoGalleryIdx); }
function expandConsejoImage(){ const item=currentConsejoGallery[consejoGalleryIdx]; if(item&&item.src) window.open(item.src,'_blank'); }

// ════════════════════════════════════════════════════════════════
// AUDIO PLAYER
// ════════════════════════════════════════════════════════════════
function loadConsejoAudio(name){
  const src=consejoAudios[name]||''; const audio=document.getElementById('consejo-audio-el'); if(!audio)return;
  audio.src=src; audio.load();
  const btn=document.getElementById('consejo-play-btn'); const fill=document.getElementById('consejo-audio-fill'); const time=document.getElementById('consejo-audio-time');
  if(btn)btn.textContent='▶'; if(fill)fill.style.width='0%'; if(time)time.textContent='0:00';
  audio.ontimeupdate=()=>{ if(audio.duration){ if(fill)fill.style.width=(audio.currentTime/audio.duration*100)+'%'; if(time)time.textContent=fmtTime(audio.currentTime)+' / '+fmtTime(audio.duration); } };
  audio.onended=()=>{if(btn)btn.textContent='▶';};
}
function fmtTime(s){ return Math.floor(s/60)+':'+((s%60)<10?'0':'')+Math.floor(s%60); }
function toggleConsejoPlay(){ const audio=document.getElementById('consejo-audio-el'); const btn=document.getElementById('consejo-play-btn'); if(!audio)return; if(audio.paused){audio.play();if(btn)btn.textContent='⏸';}else{audio.pause();if(btn)btn.textContent='▶';} }
function seekConsejoAudio(e){ const audio=document.getElementById('consejo-audio-el'); if(!audio||!audio.duration)return; const rect=e.currentTarget.getBoundingClientRect(); audio.currentTime=((e.clientX-rect.left)/rect.width)*audio.duration; }

// ════════════════════════════════════════════════════════════════
// COMPARADOR DRAGGABLE
// ════════════════════════════════════════════════════════════════
function initComparator(areaId,dividerId,rightImgId){
  const area=document.getElementById(areaId),divider=document.getElementById(dividerId),rightImg=document.getElementById(rightImgId);
  if(!area||!divider||!rightImg)return;
  let dragging=false;
  function setPos(cx){ const r=area.getBoundingClientRect(); let p=(cx-r.left)/r.width*100; p=Math.max(2,Math.min(98,p)); divider.style.left=p+'%'; rightImg.style.clipPath=`inset(0 0 0 ${p}%)`; }
  divider.addEventListener('mousedown',e=>{dragging=true;e.preventDefault();});
  window.addEventListener('mousemove',e=>{if(dragging)setPos(e.clientX);});
  window.addEventListener('mouseup',()=>{dragging=false;});
  divider.addEventListener('touchstart',e=>{dragging=true;e.preventDefault();},{passive:false});
  window.addEventListener('touchmove',e=>{if(dragging)setPos(e.touches[0].clientX);},{passive:true});
  window.addEventListener('touchend',()=>{dragging=false;});
}

// ════════════════════════════════════════════════════════════════
// ZOOM CONTROLS — max 150%, min 100%
// ════════════════════════════════════════════════════════════════
const zoomState = { finca: 100, rio: 100 };
const ZOOM_STEP = 10;
const ZOOM_MIN = 100;
const ZOOM_MAX = 150;

function zoomMap(section, dir){
  const current = zoomState[section];
  const next = Math.max(ZOOM_MIN, Math.min(ZOOM_MAX, current + dir * ZOOM_STEP));
  if(next === current) return;
  zoomState[section] = next;
  const el = document.getElementById(section + '-zoomable');
  if(el) el.style.transform = 'scale(' + (next / 100) + ')';
  // Update button states
  const btnIn = document.getElementById(section + '-zoom-in');
  const btnOut = document.getElementById(section + '-zoom-out');
  if(btnIn){ if(next >= ZOOM_MAX) btnIn.classList.add('disabled'); else btnIn.classList.remove('disabled'); }
  if(btnOut){ if(next <= ZOOM_MIN) btnOut.classList.add('disabled'); else btnOut.classList.remove('disabled'); }
}

// ── Init ──
document.addEventListener('DOMContentLoaded',()=>{
  buildVariablesList();
  buildTallerList();
  buildRioYears();
  buildHumedalYears();
  initComparator('finca-comp-area','finca-comp-divider','finca-comp-right');
  initComparator('rio-comp-area','rio-comp-divider','rio-comp-right');
  setTimeout(()=>showModal('home'),400);
});

document.getElementById('modal-overlay').addEventListener('click',function(e){ if(e.target===this) closeModal(); });
</script>
</body>
</html>

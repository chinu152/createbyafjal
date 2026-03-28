<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Aashirwad Amruttulya</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Yatra+One&family=Nunito:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/18.2.0/umd/react-dom.production.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-standalone/7.23.2/babel.min.js"></script>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
    :root {
      --red: #8B0000;
      --red-dark: #5c0000;
      --red-mid: #6b0000;
      --gold: #D4943A;
      --gold-light: #f0b96a;
      --gold-dim: rgba(212,148,58,0.18);
      --amber: #C0622A;
      --bg: #fdf6ec;
      --bg2: #f5e8d0;
      --card: rgba(255,255,255,0.82);
      --glass: rgba(255,255,255,0.55);
      --text: #2e1000;
      --text2: #5a3010;
      --muted: #9a8060;
      --border: rgba(212,148,58,0.18);
      --shadow: 0 4px 24px rgba(139,0,0,0.10);
      --shadow-lg: 0 8px 40px rgba(139,0,0,0.18);
    }
    html, body, #root { height: 100%; width: 100%; overflow: hidden; }
    body { font-family: 'Nunito', sans-serif; background: var(--bg); color: var(--text); }
    ::-webkit-scrollbar { width: 0; }

    /* ── Animations ── */
    @keyframes fadeUp   { from{opacity:0;transform:translateY(18px)} to{opacity:1;transform:translateY(0)} }
    @keyframes fadeIn   { from{opacity:0} to{opacity:1} }
    @keyframes scaleIn  { from{opacity:0;transform:scale(0.88)} to{opacity:1;transform:scale(1)} }
    @keyframes float    { 0%,100%{transform:translateY(0) rotate(-2deg)} 50%{transform:translateY(-6px) rotate(2deg)} }
    @keyframes steam    { 0%{opacity:0;transform:translateY(0) scaleX(1)} 50%{opacity:0.7} 100%{opacity:0;transform:translateY(-22px) scaleX(1.4)} }
    @keyframes pulse    { 0%,100%{transform:scale(1)} 50%{transform:scale(1.06)} }
    @keyframes shimmer  { 0%{background-position:-200% 0} 100%{background-position:200% 0} }
    @keyframes slideIn  { from{opacity:0;transform:translateX(-12px)} to{opacity:1;transform:translateX(0)} }
    @keyframes tagPop   { 0%{transform:scale(0.7);opacity:0} 60%{transform:scale(1.12)} 100%{transform:scale(1);opacity:1} }

    .au  { animation: fadeUp  0.5s ease-out both; }
    .af  { animation: fadeIn  0.4s ease-out both; }
    .asi { animation: scaleIn 0.35s ease-out both; }
    .d1{animation-delay:.08s} .d2{animation-delay:.16s} .d3{animation-delay:.24s}
    .d4{animation-delay:.32s} .d5{animation-delay:.4s}

    /* ── Layout ── */
    .app   { display:flex; flex-direction:column; height:100%; }
    .scroll{ flex:1; overflow-y:auto; padding-bottom:76px; }

    /* ── Bottom Nav ── */
    .nav { position:fixed; bottom:0; left:0; right:0; z-index:30;
           background:var(--red-dark);
           border-top:1.5px solid rgba(212,148,58,0.22);
           box-shadow:0 -4px 24px rgba(0,0,0,0.22); }
    .nav-row { display:flex; align-items:stretch; height:62px; }
    .nav-btn { flex:1; display:flex; flex-direction:column; align-items:center; justify-content:center; gap:3px;
               background:none; border:none; cursor:pointer; color:rgba(253,246,236,0.45);
               transition:color 0.2s, background 0.2s; padding:0; position:relative; }
    .nav-btn.on { color:var(--gold); }
    .nav-btn.on::after { content:''; position:absolute; bottom:0; left:20%; right:20%; height:2.5px;
                          background:var(--gold); border-radius:2px 2px 0 0; }
    .nav-lbl { font-size:9.5px; font-weight:700; letter-spacing:0.03em; }

    /* ── Hero ── */
    .hero { position:relative; background:linear-gradient(160deg, var(--red-dark) 0%, var(--red) 60%, #a01515 100%); overflow:hidden; }
    .hero-bg-pattern {
      position:absolute; inset:0;
      background-image: radial-gradient(circle at 20% 30%, rgba(212,148,58,0.15) 0%, transparent 50%),
                        radial-gradient(circle at 80% 70%, rgba(192,98,42,0.18) 0%, transparent 50%);
    }
    .hero-dots {
      position:absolute; inset:0; overflow:hidden; pointer-events:none;
    }
    .hero-dots::before {
      content:''; position:absolute; inset:0;
      background-image: radial-gradient(circle, rgba(212,148,58,0.12) 1px, transparent 1px);
      background-size:20px 20px;
    }
    .hero-body { position:relative; padding:22px 20px 0; }
    .hero-top { display:flex; align-items:center; gap:14px; }
    .chai-wrap { position:relative; flex-shrink:0; }
    .steam-line { position:absolute; top:-2px; border-radius:4px; animation:steam 1.8s ease-in-out infinite; background:rgba(253,246,236,0.6); width:3px; }
    .s1{left:22%;height:14px;animation-delay:0s}
    .s2{left:45%;height:18px;animation-delay:.5s}
    .s3{left:68%;height:12px;animation-delay:1s}
    .hero-name { color:var(--gold); font-size:22px; font-family:'Yatra One',cursive; line-height:1.2; }
    .hero-roman { color:rgba(253,246,236,0.55); font-size:10.5px; font-weight:600; margin-top:1px; letter-spacing:0.04em; }
    .hero-badge { display:inline-flex; align-items:center; gap:5px; margin-top:8px;
                  background:rgba(212,148,58,0.18); border:1px solid rgba(212,148,58,0.35);
                  border-radius:999px; padding:4px 12px; }
    .hero-badge-txt { color:var(--gold-light); font-size:11px; font-weight:700; letter-spacing:0.06em; }
    .hero-info { margin:14px 0 0; background:rgba(255,255,255,0.08); border:1px solid rgba(212,148,58,0.2);
                 border-radius:14px; padding:12px 14px; backdrop-filter:blur(6px); }
    .hero-wave { width:100%; display:block; margin-bottom:-1px; margin-top:16px; }

    /* ── Stats card ── */
    .stats-wrap { padding:0 16px; margin-top:-2px; }
    .stats-card { background:linear-gradient(135deg, #6b0000 0%, #8B0000 50%, #a01010 100%);
                  border-radius:18px; padding:14px 16px;
                  box-shadow:0 6px 28px rgba(139,0,0,0.35);
                  border:1px solid rgba(212,148,58,0.2); }
    .stats-grid { display:grid; grid-template-columns:1fr 1px 1fr 1px 1fr 1px 1fr; align-items:center; }
    .stat { text-align:center; padding:4px 0; }
    .stat-n { color:var(--bg); font-size:21px; font-weight:800; line-height:1; }
    .stat-l { color:rgba(253,246,236,0.45); font-size:9.5px; font-weight:600; margin-top:3px; letter-spacing:0.04em; }
    .stat-sep { background:rgba(253,246,236,0.12); height:36px; }

    /* ── Section ── */
    .sec { padding:0 16px; margin-top:22px; }
    .sec-hd { display:flex; align-items:center; gap:8px; margin-bottom:14px; }
    .sec-title { font-family:'Yatra One',cursive; font-size:19px; color:var(--text); }
    .sec-count { background:var(--gold-dim); color:var(--amber); font-size:11px; font-weight:700;
                 padding:2px 8px; border-radius:999px; margin-left:auto; }

    /* ── Tab row ── */
    .tab-row { display:flex; gap:8px; margin-bottom:14px; }
    .tab { padding:9px 18px; border-radius:12px; font-size:12.5px; font-weight:700;
           border:1.5px solid transparent; cursor:pointer; font-family:'Nunito',sans-serif;
           transition:all 0.2s; }
    .tab.on { background:var(--red); color:var(--gold); border-color:rgba(212,148,58,0.25);
               box-shadow:0 3px 12px rgba(139,0,0,0.25); }
    .tab.off { background:rgba(192,98,42,0.08); color:var(--amber); border-color:rgba(192,98,42,0.15); }

    /* ── Menu list ── */
    .menu-card { background:var(--card); border:1px solid var(--border); border-radius:18px;
                 overflow:hidden; box-shadow:var(--shadow); }
    .menu-row { display:flex; justify-content:space-between; align-items:center; padding:11px 16px;
                border-bottom:1px solid rgba(212,148,58,0.09); transition:background 0.15s; }
    .menu-row:last-child { border-bottom:none; }
    .menu-row:active { background:rgba(212,148,58,0.07); }
    .menu-nm { font-size:13px; font-weight:600; color:var(--text); }
    .menu-pr { font-size:13.5px; font-weight:800; color:var(--amber);
               background:rgba(192,98,42,0.1); padding:2px 9px; border-radius:8px; }

    /* ── Review card ── */
    .r-card { background:var(--card); border:1px solid var(--border); border-radius:18px; padding:15px;
              box-shadow:var(--shadow); backdrop-filter:blur(4px);
              opacity:0; animation:fadeUp 0.45s ease-out both; }
    .r-top { display:flex; align-items:flex-start; justify-content:space-between; gap:10px; }
    .r-avatar { width:38px; height:38px; border-radius:50%; background:linear-gradient(135deg,var(--red),var(--amber));
                display:flex; align-items:center; justify-content:center; flex-shrink:0;
                font-size:15px; font-weight:800; color:white; text-transform:uppercase; }
    .r-meta { flex:1; min-width:0; }
    .r-name { font-size:13.5px; font-weight:700; color:var(--text); overflow:hidden; text-overflow:ellipsis; white-space:nowrap; }
    .r-when { font-size:10.5px; color:var(--muted); margin-top:1px; }
    .r-order { font-size:11px; color:var(--amber); font-weight:700; margin-top:3px;
               background:rgba(192,98,42,0.09); display:inline-block; padding:1px 8px; border-radius:6px; }
    .r-body { font-size:13px; color:var(--text2); margin-top:11px; line-height:1.65; }
    .r-tags { display:flex; flex-wrap:wrap; gap:6px; margin-top:10px; }
    .t-pill { display:inline-flex; align-items:center; gap:4px; font-size:11px; font-weight:700;
              padding:4px 10px; border-radius:999px; }
    .t-ci  { background:rgba(192,98,42,0.1); color:var(--amber); }
    .t-ppl { background:rgba(139,0,0,0.09); color:var(--red); }
    .t-tag { background:var(--gold-dim); color:#7a5a00; }
    .del-btn { width:34px; height:34px; border-radius:10px; background:rgba(139,0,0,0.08); color:var(--red);
               border:none; cursor:pointer; display:flex; align-items:center; justify-content:center;
               flex-shrink:0; transition:background 0.15s; }
    .del-btn:active { background:rgba(139,0,0,0.18); }
    .more-btn { margin-top:10px; width:100%; padding:8px; border-radius:10px;
                background:rgba(212,148,58,0.07); border:1px solid rgba(212,148,58,0.15);
                color:var(--text2); font-size:11px; font-weight:700; font-family:'Nunito',sans-serif;
                cursor:pointer; display:flex; align-items:center; justify-content:center; gap:5px;
                transition:background 0.15s; }
    .more-btn:active { background:rgba(212,148,58,0.14); }
    .photo-grid { display:grid; gap:4px; border-radius:12px; overflow:hidden; margin-top:10px; }
    .pg1{grid-template-columns:1fr} .pg2{grid-template-columns:1fr 1fr}
    .pg3{grid-template-columns:1fr 1fr} .pg4{grid-template-columns:1fr 1fr}
    .ph-item { aspect-ratio:1; background:#e8dcc6; position:relative; overflow:hidden; }
    .ph-item img { width:100%; height:100%; object-fit:cover; }
    .ph-del { position:absolute; top:5px; right:5px; width:24px; height:24px;
              background:rgba(0,0,0,0.52); border-radius:50%; border:none; cursor:pointer;
              color:white; display:flex; align-items:center; justify-content:center; }

    /* ── Stars ── */
    .stars { display:flex; gap:5px; }
    .star { background:none; border:none; cursor:pointer; padding:0; transition:transform 0.1s; }
    .star:active { transform:scale(0.8); }

    /* ── Page header ── */
    .pg-hd { background:linear-gradient(160deg, var(--red-dark) 0%, var(--red) 100%); padding:18px 20px 20px;
             text-align:center; position:relative; overflow:hidden; }
    .pg-hd::before { content:''; position:absolute; inset:0;
                      background-image:radial-gradient(circle at 80% 20%, rgba(212,148,58,0.12) 0%, transparent 60%); }
    .pg-title { display:flex; align-items:center; justify-content:center; gap:9px;
                font-family:'Yatra One',cursive; font-size:20px; color:var(--gold); margin-bottom:3px; position:relative; }
    .pg-sub { color:rgba(253,246,236,0.45); font-size:11px; font-weight:600; letter-spacing:0.04em; }

    /* ── Rate form ── */
    .rate-star-box { background:var(--card); border:1px solid var(--border); border-radius:18px; padding:20px;
                     text-align:center; box-shadow:var(--shadow); }
    .flabel { font-size:11.5px; color:#7a5a00; font-weight:700; margin-bottom:7px; display:block;
              letter-spacing:0.04em; }
    .finput { width:100%; background:var(--glass); border:1.5px solid var(--border); border-radius:12px;
              padding:12px 15px; font-size:13px; font-family:'Nunito',sans-serif; color:var(--text);
              outline:none; transition:border-color 0.2s; -webkit-appearance:none; }
    .finput:focus { border-color:var(--gold); background:rgba(255,255,255,0.9); }
    .fta { resize:none; }
    .chip-row { display:flex; flex-wrap:wrap; gap:7px; }
    .chip { font-size:11.5px; padding:6px 13px; border-radius:999px; font-weight:700;
            border:1.5px solid rgba(212,148,58,0.18); cursor:pointer;
            background:rgba(255,255,255,0.6); color:var(--text2);
            font-family:'Nunito',sans-serif; transition:all 0.15s;
            animation:tagPop 0.25s ease-out both; }
    .chip:active { transform:scale(0.93); }
    .chip.co { background:var(--amber); color:white; border-color:transparent;
               box-shadow:0 2px 8px rgba(192,98,42,0.3); }
    .chip.ct { background:var(--red); color:var(--gold); border-color:transparent;
               box-shadow:0 2px 8px rgba(139,0,0,0.3); }
    .custom-tag-row { display:flex; gap:8px; margin-top:8px; }
    .custom-tag-input { flex:1; background:var(--glass); border:1.5px dashed rgba(212,148,58,0.35);
                        border-radius:12px; padding:9px 13px; font-size:12.5px; font-family:'Nunito',sans-serif;
                        color:var(--text); outline:none; transition:border-color 0.2s; }
    .custom-tag-input:focus { border-color:var(--gold); border-style:solid; }
    .custom-tag-input::placeholder { color:var(--muted); }
    .add-tag-btn { background:var(--red); color:var(--gold); border:none; border-radius:12px;
                   padding:0 14px; cursor:pointer; font-size:18px; display:flex; align-items:center;
                   justify-content:center; flex-shrink:0; }
    .action-row { display:flex; gap:8px; }
    .action-btn { flex:1; display:flex; justify-content:center; align-items:center; gap:7px;
                  padding:12px; border-radius:14px; border:1.5px solid var(--border);
                  font-size:12.5px; font-weight:700; font-family:'Nunito',sans-serif;
                  cursor:pointer; background:var(--glass); color:var(--text2); transition:all 0.2s; }
    .action-btn:active { transform:scale(0.97); }
    .action-btn.ci { background:var(--amber); color:white; border-color:transparent;
                     box-shadow:0 3px 12px rgba(192,98,42,0.3); }
    .action-btn.tg { background:var(--red); color:var(--gold); border-color:transparent;
                     box-shadow:0 3px 12px rgba(139,0,0,0.3); }
    .submit-btn { width:100%; margin-top:8px; padding:15px; border-radius:16px; border:none;
                  font-size:15px; font-weight:800; font-family:'Nunito',sans-serif; cursor:pointer;
                  display:flex; justify-content:center; align-items:center; gap:9px; transition:all 0.2s; }
    .submit-btn.go { background:linear-gradient(135deg, var(--red-dark), var(--amber));
                     color:white; box-shadow:0 6px 24px rgba(139,0,0,0.35); }
    .submit-btn.go:active { transform:scale(0.97); box-shadow:0 2px 10px rgba(139,0,0,0.25); }
    .submit-btn.no { background:#e9e0d5; color:#bbb; cursor:not-allowed; }

    /* ── Tag input box ── */
    .tag-box { background:var(--glass); border:1.5px solid var(--border); border-radius:16px; padding:12px; }
    .tag-input-row { display:flex; gap:8px; }
    .tag-add-btn { background:var(--red); color:var(--gold); border:none; border-radius:11px;
                   padding:0 12px; cursor:pointer; font-size:18px; display:flex; align-items:center; }
    .ppills { display:flex; flex-wrap:wrap; gap:6px; margin-top:8px; }
    .ppill { display:inline-flex; align-items:center; gap:4px; background:rgba(139,0,0,0.09);
             color:var(--red); font-size:11px; font-weight:700; padding:4px 10px; border-radius:999px; }
    .px { background:none; border:none; cursor:pointer; color:inherit; display:flex; padding:0; }

    /* ── Toast ── */
    .toast { position:fixed; bottom:76px; left:50%; transform:translateX(-50%);
             background:linear-gradient(135deg,var(--red-dark),var(--red));
             color:var(--bg); padding:10px 22px; border-radius:999px; font-size:12.5px; font-weight:700;
             border:1px solid rgba(212,148,58,0.3); box-shadow:0 6px 24px rgba(139,0,0,0.35);
             z-index:999; animation:scaleIn 0.3s ease-out; white-space:nowrap; }

    /* ── Rank badge ── */
    .rank-wrap { position:relative; }
    .rank-badge { position:absolute; top:-5px; left:-5px; z-index:10; width:30px; height:30px;
                  border-radius:50%; display:flex; align-items:center; justify-content:center;
                  font-size:12px; font-weight:800; box-shadow:0 3px 10px rgba(0,0,0,0.25); }
    .rk1{background:linear-gradient(135deg,#e8a020,#f0c060);color:white}
    .rk2{background:linear-gradient(135deg,#9eaab4,#c5d0d8);color:#444}
    .rk3{background:linear-gradient(135deg,#c07040,#d89060);color:white}

    /* ── My reviews summary ── */
    .my-sum { background:linear-gradient(135deg,rgba(192,98,42,0.1),rgba(212,148,58,0.12));
              border:1px solid rgba(212,148,58,0.18); border-radius:18px; padding:16px; margin-bottom:16px;
              display:flex; justify-content:space-between; align-items:center; box-shadow:var(--shadow); }
    .sum-v { font-size:26px; font-weight:800; color:var(--text); }
    .sum-l { font-size:10.5px; color:#7a5a00; font-weight:700; letter-spacing:0.04em; }

    /* ── Empty ── */
    .empty { text-align:center; padding:64px 0; }
    .empty-txt { color:var(--muted); font-size:13px; margin-top:12px; font-weight:600; }

    /* ── Success ── */
    .success { text-align:center; margin-top:12px; animation:scaleIn 0.3s ease-out; }

    /* ── Wave ── */
    .wave { width:100%; display:block; margin-bottom:-1px; }

    /* ── Form section card ── */
    .fsec { background:var(--card); border:1px solid var(--border); border-radius:18px; padding:15px;
            box-shadow:var(--shadow); }
  </style>
</head>
<body>
<div id="root"></div>
<script type="text/babel">
const { useState, useEffect, useCallback, createContext, useContext, useRef } = React;

const SKEY = 'aam_reviews_v2';
const UKEY = 'aam_user_id';
const CKEY = 'aam_checkins';

function uid() {
  let id = localStorage.getItem(UKEY);
  if (!id) { id='u_'+Date.now()+'_'+Math.random().toString(36).substr(2,8); localStorage.setItem(UKEY,id); }
  return id;
}

function initials(name='') { const w=name.trim().split(' '); return w.length>=2?w[0][0]+w[1][0]:name[0]||'C'; }

async function compressImage(file,maxW=800,q=0.72){
  return new Promise(res=>{
    const r=new FileReader();
    r.onload=e=>{
      const img=new window.Image();
      img.onload=()=>{
        const c=document.createElement('canvas');
        const ratio=Math.min(maxW/img.width,maxW/img.height,1);
        c.width=img.width*ratio; c.height=img.height*ratio;
        c.getContext('2d').drawImage(img,0,0,c.width,c.height);
        res(c.toDataURL('image/jpeg',q));
      };
      img.src=e.target.result;
    };
    r.readAsDataURL(file);
  });
}

/* ── Context ── */
const RCtx = createContext();
function ReviewProvider({children}){
  const [reviews,setReviews]=useState([]);
  

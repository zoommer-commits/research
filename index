<html lang="ka">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>თანამშრომელთა კვლევები</title>
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>📊</text></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Georgian:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F5F4F2; --surface:#FFFFFF; --sunk:#EFEDEA; --ink:#1D1B19; --muted:#6B6762; --line:#E3DFDA;
  --accent:#EC5E2A; --accent-ink:#FFFFFF; --soft:#FDEBE3; --accent-2:#F6B394; --warn:#C0392B; --warn-soft:#FBE5E2; --ok:#2E7D5B;
  color-scheme:light; box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#141312; --surface:#1D1B1A; --sunk:#262321; --ink:#EEEAE6; --muted:#A39E98; --line:#36322F;
    --accent:#EC5E2A; --accent-ink:#FFFFFF; --soft:#3A2219; --accent-2:#8E4326; --warn:#F08B75; --warn-soft:#3A221D; --ok:#5EC09A;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#141312; --surface:#1D1B1A; --sunk:#262321; --ink:#EEEAE6; --muted:#A39E98; --line:#36322F;
  --accent:#EC5E2A; --accent-ink:#FFFFFF; --soft:#3A2219; --accent-2:#8E4326; --warn:#F08B75; --warn-soft:#3A221D; --ok:#5EC09A;
  color-scheme:dark;
}
*,*::before,*::after{box-sizing:border-box}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 130px)}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Noto Sans Georgian","Sylfaen","Segoe UI",system-ui,sans-serif;font-size:16px;line-height:1.6;-webkit-font-smoothing:antialiased}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:10;background:var(--surface)}
button,input,select,textarea{font:inherit;color:inherit}
button{cursor:pointer}
:focus-visible{outline:2px solid var(--accent);outline-offset:2px}

.bar{position:sticky;top:env(safe-area-inset-top,0px);z-index:6;background:var(--surface);border-bottom:1px solid var(--line)}
.bar-in{max-width:1080px;margin:0 auto;padding:12px 20px;display:flex;align-items:center;gap:12px 20px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;font-size:1.05rem;margin-right:auto}
.mark{width:30px;height:30px;border-radius:8px;background:var(--accent);display:grid;place-items:center}
.mark svg{width:18px;height:18px}
.nav{display:flex;gap:4px;flex-wrap:wrap}
.nav button{border:0;background:transparent;padding:7px 12px;border-radius:8px;font-size:.9rem;font-weight:600;color:var(--muted)}
.nav button:hover{color:var(--accent)}
.nav button[aria-current="page"]{background:var(--soft);color:var(--accent)}
.nav .sep{width:1px;background:var(--line);margin:4px 4px}

main{max-width:1080px;margin:0 auto;padding:28px 20px 90px}
.narrow{max-width:740px;margin:0 auto}
h1{font-size:1.75rem;line-height:1.3;margin:0 0 6px;font-weight:800;letter-spacing:-.01em}
h2{font-size:1.2rem;line-height:1.4;margin:0 0 4px;font-weight:700}
h3{font-size:1rem;margin:0;font-weight:600}
p{margin:0}
.muted{color:var(--muted)}
.small{font-size:.875rem}
.head{display:flex;align-items:flex-end;justify-content:space-between;gap:16px;flex-wrap:wrap;margin-bottom:24px}
.back{border:0;background:none;color:var(--accent);padding:0;margin-bottom:14px;font-size:.9rem;font-weight:600}

/* buttons — all in #EC5E2A */
.btn{border:1.5px solid var(--accent);background:transparent;color:var(--accent);padding:9px 16px;border-radius:10px;font-weight:700;font-size:.92rem;display:inline-flex;align-items:center;gap:8px;white-space:nowrap}
.btn:hover{background:var(--soft)}
.btn.primary{background:var(--accent);color:var(--accent-ink)}
.btn.primary:hover{background:#D9511F;border-color:#D9511F}
.btn.ghost{border-color:transparent}
.btn.armed{background:var(--accent);color:var(--accent-ink)}
.btn:disabled{opacity:.45;cursor:not-allowed;background:transparent}
.btn.primary:disabled{background:var(--accent)}
.btn.sm{padding:6px 11px;font-size:.85rem}
.btn.lg{padding:13px 26px;font-size:1rem}
.link{border:0;background:none;color:var(--accent);font-weight:600;padding:0;text-decoration:underline;text-underline-offset:3px}

.panel{background:var(--surface);border:1px solid var(--line);border-radius:14px}
.pad{padding:20px 22px}
.rows{display:flex;flex-direction:column}
.row{display:grid;grid-template-columns:1fr auto;gap:12px 20px;align-items:center;padding:18px 22px;border-top:1px solid var(--line)}
.row:first-child{border-top:0}
.row.click{cursor:pointer}
.row.click:hover{background:var(--sunk)}
.row .meta{display:flex;gap:14px;flex-wrap:wrap;font-size:.85rem;color:var(--muted);margin-top:4px}
.row .acts{display:flex;gap:8px;flex-wrap:wrap;justify-content:flex-end}
@media (max-width:640px){.row{grid-template-columns:1fr}.row .acts{justify-content:flex-start}}

.pill{display:inline-flex;align-items:center;gap:6px;font-size:.8rem;font-weight:600;padding:2px 10px;border-radius:999px;background:var(--sunk);color:var(--muted)}
.pill::before{content:"";width:7px;height:7px;border-radius:50%;background:currentColor}
.pill.active{background:var(--soft);color:var(--accent)}
.pill.closed{background:var(--sunk);color:var(--muted)}
.pill.ok{background:transparent;color:var(--ok);padding-left:0}
.done{color:var(--ok);font-weight:600;font-size:.9rem;display:inline-flex;gap:6px;align-items:center}
.done svg{width:18px;height:18px;stroke:currentColor}
.empty{text-align:center;padding:56px 24px}
.empty p{max-width:440px;margin:8px auto 18px}
.note{background:var(--soft);border-radius:10px;padding:11px 15px;font-size:.9rem}
.err{background:var(--warn-soft);color:var(--warn);padding:12px 16px;border-radius:10px;font-size:.92rem}
.loading{padding:80px 20px;text-align:center;color:var(--muted)}

/* intro */
.intro{padding:36px 36px 30px}
.intro .txt{white-space:pre-wrap;line-height:1.75;margin:18px 0 26px;font-size:1.02rem}
.consent{display:flex;gap:12px;align-items:flex-start;padding:16px 18px;border:1.5px solid var(--line);border-radius:12px;cursor:pointer;font-weight:600}
.consent:has(input:checked){border-color:var(--accent);background:var(--soft)}
.consent input{accent-color:var(--accent);width:20px;height:20px;margin:2px 0 0;flex:none}
@media (max-width:520px){.intro{padding:24px 20px}}

/* taking */
.progwrap{position:sticky;top:calc(env(safe-area-inset-top,0px) + var(--barh,57px));z-index:4;background:var(--bg);padding:14px 0 16px;margin-bottom:6px}
.progtop{display:flex;justify-content:space-between;font-size:.85rem;color:var(--muted);margin-bottom:7px;font-variant-numeric:tabular-nums}
.progtop b{color:var(--accent)}
.progress{height:8px;background:var(--sunk);border-radius:99px;overflow:hidden}
.progress i{display:block;height:100%;background:#EC5E2A;border-radius:99px;transition:width .3s ease}
.q{display:grid;grid-template-columns:44px 1fr;gap:4px 14px;padding:24px 0;border-top:1px solid var(--line)}
.q.first{border-top:0}
.q[hidden]{display:none}
.q.followup{animation:reveal .3s ease}
@keyframes reveal{from{opacity:0;transform:translateY(-6px)}to{opacity:1;transform:none}}
.qn{font-size:1.5rem;font-weight:800;color:var(--accent);line-height:1.25;font-variant-numeric:tabular-nums}
.qt{font-weight:600;font-size:1.05rem;line-height:1.5}
.qh{grid-column:2;color:var(--muted);font-size:.9rem;margin-top:2px}
.req{color:var(--accent);margin-left:3px}
.qbody{grid-column:2;margin-top:12px}
.q.missing .qt{color:var(--warn)}
.q.missing .qbody::after{content:"ამ კითხვაზე პასუხი სავალდებულოა";display:block;color:var(--warn);font-size:.85rem;margin-top:8px}
@media (max-width:520px){.q{grid-template-columns:1fr}.qbody,.qh{grid-column:1}.qn{font-size:1.15rem}}
.opt{display:flex;align-items:center;gap:12px;padding:11px 14px;border:1.5px solid var(--line);border-radius:10px;margin-bottom:8px;cursor:pointer;background:var(--surface)}
.opt:hover{border-color:var(--accent-2)}
.opt input{accent-color:var(--accent);width:18px;height:18px;margin:0;flex:none}
.opt:has(input:checked){border-color:var(--accent);background:var(--soft)}
.opt:has(input:disabled){opacity:.5;cursor:not-allowed}
.limit{font-size:.82rem;color:var(--muted);margin-bottom:8px}
.scale{display:flex;gap:6px;flex-wrap:wrap}
.scale button{min-width:46px;height:46px;border:1.5px solid var(--line);background:var(--surface);border-radius:10px;font-weight:700;font-variant-numeric:tabular-nums}
.scale button:hover{border-color:var(--accent)}
.scale button[aria-pressed="true"]{background:var(--accent);border-color:var(--accent);color:var(--accent-ink)}
.scale-labels{display:flex;justify-content:space-between;font-size:.82rem;color:var(--muted);margin-top:6px;gap:12px}
.field{width:100%;padding:11px 13px;border:1.5px solid var(--line);border-radius:10px;background:var(--surface)}
.field:focus{border-color:var(--accent);outline:none;box-shadow:0 0 0 3px var(--soft)}
textarea.field{min-height:110px;resize:vertical;line-height:1.55}
select.field{appearance:auto}
.other{margin:-2px 0 8px 44px}
.other[hidden]{display:none}
.thanks{text-align:center;padding:64px 24px}
.tick{width:64px;height:64px;border-radius:50%;background:var(--soft);display:grid;place-items:center;margin:0 auto 18px}
.tick svg{width:30px;height:30px;stroke:var(--accent)}

/* editor */
.sec{margin-top:26px}
.sec > h2{margin-bottom:10px}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.grid3{display:grid;grid-template-columns:110px 1fr 1fr;gap:12px;margin-top:10px}
@media (max-width:640px){.grid2,.grid3{grid-template-columns:1fr}}
label.lbl{display:block;font-size:.85rem;font-weight:600;color:var(--muted);margin:14px 0 6px}
label.lbl:first-child{margin-top:0}
.check{display:flex;align-items:center;gap:10px;font-size:.92rem;cursor:pointer}
.check input{accent-color:var(--accent);width:17px;height:17px;margin:0}
.eq{border:1px solid var(--line);border-radius:12px;background:var(--surface);margin-top:12px}
.eq.cond{border-left:4px solid var(--accent)}
.eq-h{display:flex;align-items:center;gap:10px;padding:10px 12px;border-bottom:1px solid var(--line);background:var(--sunk);border-radius:12px 12px 0 0;flex-wrap:wrap}
.eq.cond .eq-h{border-radius:0 12px 0 0}
.eq-h .num{font-weight:800;color:var(--accent);min-width:22px}
.eq-h select{padding:6px 10px;border:1.5px solid var(--line);border-radius:8px;background:var(--surface);font-weight:600}
.eq-h .sp{margin-left:auto;display:flex;gap:2px}
.condtag{font-size:.8rem;color:var(--accent);font-weight:600;overflow-wrap:anywhere}
.icon{border:0;background:transparent;width:32px;height:32px;border-radius:8px;display:grid;place-items:center;color:var(--accent)}
.icon:hover{background:var(--soft)}
.icon:disabled{opacity:.3;cursor:default;background:transparent}
.icon svg{width:16px;height:16px}
.eq-b{padding:14px}
.optrow{display:flex;gap:8px;margin-top:8px;align-items:center}
.optrow .dot{width:14px;height:14px;border:2px solid var(--muted);border-radius:50%;flex:none;opacity:.6}
.optrow .dot.sq{border-radius:4px}
.optrow .fixed{flex:1;padding:9px 13px;background:var(--sunk);border-radius:10px}
.follow{border:1.5px dashed var(--accent-2);background:transparent;color:var(--accent);border-radius:8px;padding:6px 10px;font-size:.8rem;font-weight:700;white-space:nowrap}
.follow:hover{background:var(--soft);border-style:solid}
.condbox{margin-top:14px;padding:12px 14px;background:var(--soft);border-radius:10px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
.chip{display:inline-flex;align-items:center;gap:7px;padding:5px 11px;border:1.5px solid var(--accent-2);border-radius:999px;font-size:.88rem;cursor:pointer;background:var(--surface)}
.chip:has(input:checked){background:var(--accent);border-color:var(--accent);color:var(--accent-ink)}
.chip input{position:absolute;opacity:0;pointer-events:none}
.warnline{color:var(--warn);font-size:.85rem;margin-top:8px}
.addq{display:flex;gap:8px;flex-wrap:wrap;margin-top:16px;padding:16px;border:1.5px dashed var(--line);border-radius:12px}
.savebar{position:sticky;bottom:calc(env(safe-area-inset-bottom,0px) + 12px);margin-top:24px;display:flex;align-items:center;gap:10px;justify-content:flex-end;flex-wrap:wrap;background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:10px 12px;box-shadow:0 6px 24px rgba(0,0,0,.08);z-index:3}
.savebar .msg{margin-right:auto;font-size:.88rem;color:var(--muted);padding-left:6px}

/* results */
.tabs{display:flex;gap:4px;border-bottom:1px solid var(--line);margin-bottom:22px;overflow-x:auto}
.tabs button{border:0;background:none;padding:10px 14px;color:var(--muted);font-weight:600;border-bottom:2.5px solid transparent;margin-bottom:-1px;white-space:nowrap}
.tabs button[aria-selected="true"]{color:var(--accent);border-bottom-color:var(--accent)}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:var(--line);border:1px solid var(--line);border-radius:14px;overflow:hidden;margin-bottom:22px}
.stat{background:var(--surface);padding:16px 18px}
.stat b{display:block;font-size:1.6rem;font-weight:800;line-height:1.2;font-variant-numeric:tabular-nums}
.stat span{font-size:.85rem;color:var(--muted)}
@media (max-width:720px){.stats{grid-template-columns:repeat(2,1fr)}}
.rq{margin-bottom:16px}
.rq-h{display:flex;gap:12px;align-items:baseline;justify-content:space-between;flex-wrap:wrap;margin-bottom:14px}
.rq-h .t{display:flex;gap:10px}
.rq-h .t .n{font-weight:800;color:var(--accent)}
.hbar{display:grid;grid-template-columns:minmax(90px,34%) 1fr 80px;gap:12px;align-items:center;margin-bottom:9px;font-size:.92rem}
.hbar .track{height:22px;background:var(--sunk);border-radius:6px;overflow:hidden}
.hbar .fill{display:block;height:100%;background:var(--accent-2);border-radius:6px;min-width:2px}
.hbar.top .fill{background:var(--accent)}
.hbar .v{text-align:right;font-variant-numeric:tabular-nums;color:var(--muted)}
.hbar .v b{color:var(--ink)}
.hbar .lab{overflow-wrap:anywhere}
.avg{display:flex;align-items:baseline;gap:8px;margin-bottom:14px;flex-wrap:wrap}
.avg b{font-size:2rem;font-weight:800;line-height:1;color:var(--accent)}
.cols{display:flex;align-items:flex-end;gap:6px;height:130px;padding-top:18px}
.col{flex:1;display:flex;flex-direction:column;align-items:center;gap:4px;height:100%;justify-content:flex-end;min-width:0}
.col .c{width:100%;max-width:56px;background:var(--accent);border-radius:6px 6px 2px 2px;min-height:2px;position:relative}
.col .c em{position:absolute;top:-19px;left:0;right:0;text-align:center;font-style:normal;font-size:.78rem;color:var(--muted)}
.col small{font-weight:700;font-variant-numeric:tabular-nums}
.texts{display:flex;flex-direction:column;gap:8px;max-height:340px;overflow-y:auto;padding-right:4px}
.texts blockquote{margin:0;padding:10px 14px;background:var(--sunk);border-radius:10px;font-size:.93rem;white-space:pre-wrap;overflow-wrap:anywhere}
.texts blockquote cite{display:block;font-style:normal;font-size:.8rem;color:var(--muted);margin-top:4px}
.subh{font-size:.85rem;font-weight:600;color:var(--muted);margin:14px 0 8px}
.timeline{display:flex;align-items:flex-end;gap:3px;height:70px;margin-top:10px}
.timeline i{flex:1;background:var(--accent);border-radius:3px 3px 0 0;min-height:2px}
.tl-l{display:flex;justify-content:space-between;font-size:.78rem;color:var(--muted);margin-top:6px}
.scroll{overflow-x:auto}
table{border-collapse:collapse;width:100%;font-size:.88rem}
th,td{text-align:left;padding:10px 12px;border-bottom:1px solid var(--line);vertical-align:top;min-width:140px;max-width:320px;overflow-wrap:anywhere}
th{font-weight:600;color:var(--muted);background:var(--sunk)}
tbody tr{cursor:pointer}
tbody tr:hover td{background:var(--sunk)}
.ans{padding:16px 0;border-top:1px solid var(--line)}
.ans:first-child{border-top:0;padding-top:0}
.ans .a{margin-top:6px;white-space:pre-wrap;overflow-wrap:anywhere;font-weight:500}
.ans .a.none{color:var(--muted);font-weight:400}
.ai{white-space:pre-wrap;line-height:1.7;font-size:.95rem}
.ai-box{border-left:3px solid var(--accent);padding-left:16px}
.filter{display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-bottom:16px}
.filter select{max-width:360px}
.adminform{display:flex;gap:10px;flex-wrap:wrap}
.adminform input{flex:1;min-width:220px}
.toast{position:fixed;left:50%;bottom:calc(env(safe-area-inset-bottom,0px) + 20px);transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:10px 18px;border-radius:10px;font-size:.9rem;z-index:20;opacity:0;pointer-events:none;transition:opacity .2s;max-width:90vw;text-align:center}
.toast.show{opacity:1}
.steps{margin:10px 0 0;padding-left:20px;font-size:.92rem}
.steps li{margin-bottom:4px}
@media (prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
.nav a{padding:7px 12px;border-radius:8px;font-size:.9rem;font-weight:600;color:var(--muted);text-decoration:none}
.nav a:hover{color:var(--accent)}
.auth{max-width:460px;margin:40px auto}
.auth .panel{padding:30px}
.setup{max-width:760px;margin:0 auto}
.setup ol{padding-left:22px}
.setup li{margin-bottom:10px}
.setup code{background:var(--sunk);padding:1px 6px;border-radius:5px;font-size:.88em;overflow-wrap:anywhere}
.userchip{font-size:.82rem;color:var(--muted);display:flex;gap:10px;align-items:center}
</style>
</head>
<body>
<header class="bar" id="bar"><div class="bar-in">
  <div class="brand"><span class="mark"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.4" stroke-linecap="round"><path d="M5 19V11M12 19V5M19 19v-6"/></svg></span><span>თანამშრომელთა კვლევები</span></div>
  <nav class="nav" id="nav" hidden></nav>
</div></header>
<main id="app"><div class="loading">იტვირთება…</div></main>
<div class="toast" id="toast" role="status"></div>
<script type="module">
/* =========================================================
   ⚙️ კონფიგურაცია — შეავსეთ Firebase-ის პროექტის მონაცემებით
   (Firebase Console → Project settings → Your apps → Web app)
   ========================================================= */
const FIREBASE_CONFIG = {
  apiKey: "AIzaSyCfD0MBONk5J01SH3BN3wP-eVH-P-lEdtc",
  authDomain: "researchzoommer.firebaseapp.com",
  projectId: "researchzoommer",
  storageBucket: "researchzoommer.firebasestorage.app",
  messagingSenderId: "702095945098",
  appId: "1:702095945098:web:70ad2c51fd5d69b0086c73"
};
// მფლობელის (მთავარი ადმინის) მეილი(ები). იგივე მეილი ჩაწერეთ firestore.rules ფაილშიც.
const OWNER_EMAILS = ["ssharikadze@zoommer.ge"];
/* ========================================================= */

import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-app.js";
import { getAuth, onAuthStateChanged, signInAnonymously, sendSignInLinkToEmail, isSignInWithEmailLink, signInWithEmailLink, signOut } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-auth.js";
import { getFirestore, collection, doc, getDoc, setDoc, updateDoc, deleteDoc, onSnapshot, query, where } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-firestore.js";

const TYPES = { text: "ღია პასუხი — მოკლე", long: "ღია პასუხი — ვრცელი", single: "ერთი არჩევანი", multi: "მრავალი არჩევანი", dropdown: "ჩამოსაშლელი სია", yesno: "კი / არა", scale: "შკალა" };
const CHOICE = ["single", "multi", "dropdown", "yesno"];
const STATUS = { draft: "მონახაზი", active: "აქტიური", closed: "დახურული" };
const OTHER = "სხვა";
const DEFAULT_CONSENT = "გავეცანი ზემოთ მოცემულ ინფორმაციას და ვეთანხმები კვლევაში მონაწილეობას";
const ICON = {
  up: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M6 15l6-6 6 6"/></svg>',
  down: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M6 9l6 6 6-6"/></svg>',
  copy: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="8" y="8" width="12" height="12" rx="2"/><path d="M16 8V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2"/></svg>',
  del: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M4 7h16M10 11v6M14 11v6M6 7l1 13h10l1-13M9 7V4h6v3"/></svg>',
  x: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M6 6l12 12M18 6L6 18"/></svg>',
  tick: '<svg viewBox="0 0 24 24" fill="none" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12.5l4.5 4.5L19 7"/></svg>'
};

const params = new URLSearchParams(location.search);
const BASE_URL = location.origin + location.pathname;
const S = {
  adminMode: params.has("admin"), auth: null, db: null, fbUser: null, email: null,
  role: "none", // none | invited | active | owner
  authState: "loading", // loading | signedout | needEmail | linkSent | noaccess | confirm | ready
  linkEmail: "", mode: "employee",
  surveys: [], surveysReady: false, resp: [], admins: [],
  route: { view: "list" }, draft: {}, ack: {}, ident: {}, editor: null, error: null
};
const app = document.getElementById("app");
const esc = s => String(s ?? "").replace(/[&<>"']/g, c => ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" }[c]));
const nid = () => Date.now().toString(36) + Math.random().toString(36).slice(2, 8);
const clone = o => JSON.parse(JSON.stringify(o));
const fmtDate = t => t ? new Date(t).toLocaleDateString("ka-GE", { day: "numeric", month: "short", year: "numeric" }) : "—";
const fmtDT = t => t ? new Date(t).toLocaleString("ka-GE", { day: "numeric", month: "short", hour: "2-digit", minute: "2-digit" }) : "—";
const pct = (a, b) => b ? Math.round(a / b * 100) : 0;
const isEmpty = v => v === undefined || v === null || (typeof v === "string" && v.trim() === "") || (Array.isArray(v) && v.length === 0);
const lc = s => String(s || "").trim().toLowerCase();
const validEmail = e => /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(e);
const ls = { get: k => { try { return localStorage.getItem(k); } catch (e) { return null; } }, set: (k, v) => { try { localStorage.setItem(k, v); } catch (e) { } }, del: k => { try { localStorage.removeItem(k); } catch (e) { } } };
function toast(msg) { const t = document.getElementById("toast"); t.textContent = msg; t.classList.add("show"); clearTimeout(toast.t); toast.t = setTimeout(() => t.classList.remove("show"), 3000); }
const isAdmin = () => S.role === "owner" || S.role === "active";
const isOwner = () => S.role === "owner";
const linkSettings = email => ({ url: `${BASE_URL}?admin&email=${encodeURIComponent(email)}`, handleCodeInApp: true });

/* ---------- model ---------- */
function newQuestion(type) {
  const q = { id: nid(), type, text: "", help: "", required: true };
  if (type === "single" || type === "multi" || type === "dropdown") { q.options = ["ვარიანტი 1", "ვარიანტი 2"]; q.allowOther = false; }
  if (type === "multi") q.maxSelect = 0;
  if (type === "yesno") q.options = ["კი", "არა"];
  if (type === "scale") { q.scaleMax = 5; q.minLabel = "სრულიად არ ვეთანხმები"; q.maxLabel = "სრულიად ვეთანხმები"; }
  return q;
}
function choicesOf(q) { const o = [...(q.options || [])]; if (q.allowOther && q.type !== "yesno") o.push(OTHER); return o; }
function visibleQs(qs, vals) {
  const shown = new Set();
  return (qs || []).filter(q => {
    const c = q.showIf;
    if (!c || !c.qid) { shown.add(q.id); return true; }
    if (!shown.has(c.qid)) return false;
    const v = vals[c.qid], set = c.values || [];
    const ok = Array.isArray(v) ? v.some(x => set.includes(x)) : set.includes(v);
    if (ok) shown.add(q.id);
    return ok;
  });
}
function answered(q, vals) {
  const v = vals[q.id];
  if (isEmpty(v)) return false;
  const hasOther = Array.isArray(v) ? v.includes(OTHER) : v === OTHER;
  if (q.allowOther && hasOther && isEmpty(vals[q.id + "__o"])) return false;
  return true;
}
function fmtVal(q, vals) {
  const v = vals[q.id];
  if (isEmpty(v)) return "";
  const o = vals[q.id + "__o"];
  const one = x => (x === OTHER && q.allowOther && o) ? `${OTHER}: ${o}` : String(x);
  if (Array.isArray(v)) return v.map(one).join(", ");
  if (q.type === "scale") return `${v} / ${q.scaleMax || 5}`;
  return one(v);
}
const named = s => s.identify === "name";
function responsesFor(sid) { return S.resp.filter(r => r.surveyId === sid).sort((a, b) => (a.submittedAt || 0) - (b.submittedAt || 0)); }
function getSurvey(id) { if (S.route.useEditor && S.editor && S.editor.id === id) return S.editor; return S.surveys.find(x => x.id === id); }
const doneKey = sid => "kv_done_" + sid;

/* ---------- header / router ---------- */
function renderHeader() {
  const nav = document.getElementById("nav");
  if (!S.adminMode || S.authState !== "ready" || !isAdmin()) {
    nav.hidden = !(S.adminMode && S.fbUser && !S.fbUser.isAnonymous);
    nav.innerHTML = nav.hidden ? "" : `<span class="userchip">${esc(S.email || "")}<button class="btn ghost sm" data-act="signout">გასვლა</button></span>`;
  } else {
    const v = S.route.view;
    const cur = ["responses", "response"].includes(v) ? "responses" : v === "admins" ? "admins" : "surveys";
    const items = [["surveys", "კვლევები"], ["responses", "პასუხები"]];
    if (isOwner()) items.push(["admins", "ადმინები"]);
    nav.hidden = false;
    nav.innerHTML = items.map(([k, l]) => `<button data-nav="${k}" ${cur === k ? 'aria-current="page"' : ""}>${l}</button>`).join("") +
      `<span class="sep"></span><a href="${esc(BASE_URL)}" target="_blank" rel="noopener">თანამშრომლის ხედი ↗</a><span class="sep"></span><button data-act="signout" title="${esc(S.email || "")}">გასვლა</button>`;
  }
  requestAnimationFrame(() => document.documentElement.style.setProperty("--barh", document.getElementById("bar").offsetHeight + "px"));
}
function render() {
  renderHeader();
  if (S.error) { app.innerHTML = `<div class="narrow"><div class="err">${esc(S.error)}</div></div>`; return; }
  if (S.adminMode) {
    if (S.authState !== "ready") return renderAuth();
    if (!S.surveysReady) { app.innerHTML = `<div class="loading">იტვირთება…</div>`; return; }
    const v = S.route.view;
    if (v === "intro") return renderIntro();
    if (v === "take") return renderTake();
    if (v === "edit") return renderEditor();
    if (v === "results") return renderResults();
    if (v === "responses") return renderResponses();
    if (v === "response") return renderResponse();
    if (v === "admins" && isOwner()) return renderAdmins();
    return renderAdminList();
  }
  if (!S.surveysReady) { app.innerHTML = `<div class="loading">იტვირთება…</div>`; return; }
  const v = S.route.view;
  if (v === "intro") return renderIntro();
  if (v === "take") return renderTake();
  return renderEmployeeList();
}
function softRender() { if (["edit", "take", "intro"].includes(S.route.view)) { renderHeader(); return; } render(); }
function go(route) { S.route = route; render(); window.scrollTo({ top: 0 }); }

/* ================= SETUP SCREEN ================= */
function renderSetup() {
  document.getElementById("nav").hidden = true;
  app.innerHTML = `<div class="setup"><div class="panel pad">
    <h1>პლატფორმის დაყენება</h1>
    <p class="muted">ეს გვერდი ჩანს, რადგან Firebase-ის მონაცემები ჯერ არ არის შევსებული. ერთჯერადი დაყენება 15–20 წუთს მოითხოვს.</p>
    <ol style="margin-top:18px">
      <li>გადადით <code>console.firebase.google.com</code>-ზე და შექმენით ახალი პროექტი.</li>
      <li><b>Build → Authentication → Sign-in method</b>: ჩართეთ <b>Anonymous</b> და <b>Email/Password</b>, ამ უკანასკნელში მონიშნეთ <b>Email link (passwordless sign-in)</b>.</li>
      <li><b>Build → Firestore Database</b>: შექმენით ბაზა (production mode), შემდეგ <b>Rules</b> ჩანართში ჩასვით <code>firestore.rules</code> ფაილის შიგთავსი (მასში ჩაწერეთ თქვენი მეილი) და დააჭირეთ Publish.</li>
      <li><b>Project settings → Your apps</b>: დაამატეთ Web app და დააკოპირეთ <code>apiKey</code>, <code>authDomain</code>, <code>projectId</code>, <code>appId</code>.</li>
      <li>გახსენით <code>index.html</code> ტექსტურ რედაქტორში და ფაილის ქვედა ნაწილში, <code>FIREBASE_CONFIG</code>-ში ჩასვით ეს მნიშვნელობები; <code>OWNER_EMAILS</code>-ში ჩაწერეთ თქვენი მეილი.</li>
      <li>ატვირთეთ ფაილი ჰოსტინგზე (მაგ. <code>app.netlify.com/drop</code> — უბრალოდ ჩააგდეთ საქაღალდე, ან Firebase Hosting). მიღებული მისამართი (მაგ. <code>xxx.netlify.app</code>) დაამატეთ <b>Authentication → Settings → Authorized domains</b>-ში.</li>
      <li>თანამშრომლებს გაუგზავნეთ მისამართი, ადმინ პანელისთვის კი გამოიყენეთ იგივე მისამართი ბოლოში <code>?admin</code>-ით.</li>
    </ol>
    <div class="note" style="margin-top:12px">ფაილი უნდა გაიხსნას ვებ-მისამართიდან (https://…). კომპიუტერიდან პირდაპირ გახსნისას (file://) მეილით შესვლა არ იმუშავებს.</div>
  </div></div>`;
}

/* ================= AUTH (admin) ================= */
function renderAuth() {
  const st = S.authState;
  let body = "";
  if (st === "loading") body = `<div class="loading" style="padding:30px">იტვირთება…</div>`;
  else if (st === "signedout") body = `<h1>ადმინ პანელი</h1><p class="muted">შესასვლელად ჩაწერეთ მეილი — მასზე მოვა ერთჯერადი შესვლის ბმული.</p>
      <input class="field" type="email" id="loginEmail" placeholder="name@zoommer.ge" style="margin-top:18px" autocomplete="email" value="${esc(ls.get("kv_email") || "")}">
      <p style="margin-top:14px"><button class="btn primary" data-act="sendLink" style="width:100%;justify-content:center">შესვლის ბმულის გაგზავნა</button></p>
      <p class="muted small" style="margin-top:12px">წვდომა აქვთ მხოლოდ მოწვეულ ადმინისტრატორებს.</p>`;
  else if (st === "linkSent") body = `<div class="tick">${ICON.tick}</div><h1 style="text-align:center">შეამოწმეთ მეილი</h1><p class="muted" style="text-align:center">შესვლის ბმული გაიგზავნა მისამართზე <b>${esc(S.linkEmail)}</b>. გახსენით ბმული იმავე მოწყობილობაზე. თუ ვერ ხედავთ, შეამოწმეთ Spam საქაღალდე.</p>
      <p style="text-align:center;margin-top:18px"><button class="btn sm" data-act="backToLogin">სხვა მეილით შესვლა</button></p>`;
  else if (st === "needEmail") body = `<h1>მეილის დადასტურება</h1><p class="muted">უსაფრთხოებისთვის ჩაწერეთ მეილი, რომელზეც ბმული მიიღეთ.</p>
      <input class="field" type="email" id="confirmEmail" style="margin-top:18px" autocomplete="email">
      <p style="margin-top:14px"><button class="btn primary" data-act="finishLink" style="width:100%;justify-content:center">შესვლა</button></p>`;
  else if (st === "noaccess") body = `<h1>წვდომა არ გაქვთ</h1><p class="muted">მეილი <b>${esc(S.email)}</b> არ არის ადმინისტრატორების სიაში. მიმართეთ პლატფორმის მფლობელს.</p>
      <p style="margin-top:18px"><button class="btn" data-act="signout">გასვლა</button></p>`;
  else if (st === "confirm") body = `<h1>მოწვევა ადმინისტრატორად</h1><p class="muted">თქვენ (<b>${esc(S.email)}</b>) მოგიწვიეს თანამშრომელთა კვლევების პლატფორმის ადმინისტრატორად.</p>
      <label class="consent" style="margin-top:18px"><input type="checkbox" id="regOk"><span>ვადასტურებ, რომ ვიღებ ადმინისტრატორის როლს და დავიცავ თანამშრომელთა პასუხების კონფიდენციალურობას</span></label>
      <p style="margin-top:16px"><button class="btn primary" data-act="acceptRole" id="regBtn" disabled style="width:100%;justify-content:center">რეგისტრაციის დასრულება</button></p>`;
  app.innerHTML = `<div class="auth"><div class="panel">${body}</div></div>`;
}

async function resolveRole(user) {
  S.fbUser = user; S.email = user && user.email ? lc(user.email) : null;
  if (!user || user.isAnonymous || !S.email) { S.role = "none"; S.authState = "signedout"; render(); return; }
  if (OWNER_EMAILS.map(lc).includes(S.email)) { S.role = "owner"; enterDashboard(); return; }
  try {
    const d = await getDoc(doc(S.db, "admins", S.email));
    if (!d.exists()) { S.role = "none"; S.authState = "noaccess"; render(); return; }
    const st = d.data().status;
    if (st === "active") { S.role = "active"; enterDashboard(); return; }
    S.role = "invited"; S.authState = "confirm"; render();
  } catch (e) { S.role = "none"; S.authState = "noaccess"; render(); }
}
let unsubs = [];
function enterDashboard() {
  S.authState = "ready"; S.mode = "admin"; S.route = { view: "list" };
  unsubs.forEach(u => u()); unsubs = [];
  unsubs.push(onSnapshot(collection(S.db, "surveys"), snap => {
    S.surveys = snap.docs.map(d => ({ id: d.id, ...d.data() })).sort((a, b) => (b.updatedAt || 0) - (a.updatedAt || 0));
    S.surveysReady = true; softRender();
  }, e => { S.error = "კვლევების ჩატვირთვა ვერ მოხერხდა: " + (e.code || ""); render(); }));
  unsubs.push(onSnapshot(collection(S.db, "responses"), snap => { S.resp = snap.docs.map(d => ({ id: d.id, ...d.data() })); softRender(); }, () => { }));
  if (isOwner()) unsubs.push(onSnapshot(collection(S.db, "admins"), snap => { S.admins = snap.docs.map(d => ({ id: d.id, ...d.data() })).sort((a, b) => (a.invitedAt || 0) - (b.invitedAt || 0)); softRender(); }, () => { }));
  render();
}

/* ================= EMPLOYEE ================= */
function renderEmployeeList() {
  const list = S.surveys.filter(s => s.status === "active");
  if (!list.length) { app.innerHTML = `<div class="narrow"><div class="panel empty"><h2>ამჟამად აქტიური კვლევა არ არის</h2><p class="muted">როცა ახალი კვლევა გაიხსნება, ის აქ გამოჩნდება.</p></div></div>`; return; }
  app.innerHTML = `<div class="narrow">
    <div class="head"><div><h1>კვლევები</h1><p class="muted">აირჩიეთ კვლევა და შეავსეთ კითხვარი.</p></div></div>
    <div class="panel rows">${list.map(s => {
      const done = ls.get(doneKey(s.id));
      return `<div class="row"><div><h2>${esc(s.title || "უსათაურო")}</h2>${s.description ? `<p class="muted small">${esc(s.description)}</p>` : ""}
        ${!named(s) ? `<div class="meta"><span>ანონიმური</span></div>` : ""}</div>
        <div class="acts">${done ? `<span class="done">${ICON.tick} შევსებულია</span>` : `<button class="btn primary" data-act="start" data-id="${s.id}">დაწყება</button>`}</div></div>`;
    }).join("")}</div></div>`;
}
function backBtn() {
  if (S.route.preview && S.route.useEditor) return `<button class="back" data-act="toEditor">← რედაქტორში დაბრუნება</button>`;
  return `<button class="back" data-act="home">← ${S.route.preview ? "კვლევები" : "ყველა კვლევა"}</button>`;
}
function previewNote() { return S.route.preview ? `<div class="note" style="margin-bottom:16px">გადახედვის რეჟიმი — პასუხები არ შეინახება.</div>` : ""; }

function renderIntro() {
  const s = getSurvey(S.route.id);
  if (!s) return go({ view: "list" });
  if (!S.route.preview && (ls.get(doneKey(s.id)) || s.status !== "active")) return go({ view: "take", id: s.id });
  const it = s.intro || {};
  const txt = (it.text || "").trim() || (s.description || "").trim() || "ეს კვლევა ტარდება სამუშაო გარემოს გასაუმჯობესებლად. გთხოვთ, უპასუხოთ კითხვებს გულწრფელად.";
  const id = S.ident[s.id] || {};
  app.innerHTML = `<div class="narrow">${backBtn()}${previewNote()}
    <div class="panel intro">
      <h1>${esc(it.title || s.title || "შესავალი")}</h1>
      ${it.title && s.title && it.title !== s.title ? `<p class="muted">${esc(s.title)}</p>` : ""}
      <div class="txt">${esc(txt)}</div>
      ${named(s) ? `<div class="grid2" style="margin-bottom:18px"><div><label class="lbl" for="idName">სახელი და გვარი *</label><input class="field" id="idName" value="${esc(id.name || "")}" autocomplete="name"></div>
        ${s.askDept ? `<div><label class="lbl" for="idDept">დეპარტამენტი / ფილიალი</label><input class="field" id="idDept" value="${esc(id.dept || "")}"></div>` : ""}</div>`
      : `<div class="note" style="margin-bottom:16px">კვლევა ანონიმურია — თქვენი ვინაობა არ ფიქსირდება.</div>`}
      <label class="consent"><input type="checkbox" id="ackBox" ${S.ack[s.id] ? "checked" : ""}><span>${esc(it.consent || DEFAULT_CONSENT)}</span></label>
      <p style="margin-top:22px;display:flex;justify-content:flex-end;align-items:center;gap:12px;flex-wrap:wrap"><span class="small" style="color:var(--warn)" id="introMsg"></span><button class="btn primary lg" data-act="ack" id="ackBtn" ${S.ack[s.id] ? "" : "disabled"}>გაგრძელება — კითხვებზე გადასვლა</button></p>
    </div></div>`;
}

function renderTake() {
  const s = getSurvey(S.route.id);
  if (!s) return go({ view: "list" });
  const done = !S.route.preview && ls.get(doneKey(s.id));
  if (done || S.route.sent) {
    app.innerHTML = `<div class="narrow"><div class="panel thanks"><div class="tick">${ICON.tick}</div>
      <h1>მადლობა!</h1><p class="muted">${S.route.preview ? "გადახედვა დასრულდა — პასუხები არ შენახულა." : "თქვენი პასუხები მიღებულია."}</p>
      <p style="margin-top:22px">${S.route.preview && S.route.useEditor ? `<button class="btn" data-act="toEditor">რედაქტორში დაბრუნება</button>` : `<button class="btn" data-act="home">კვლევებზე დაბრუნება</button>`}</p></div></div>`;
    return;
  }
  if (!S.route.preview && s.status !== "active") return go({ view: "list" });
  if (!S.ack[s.id]) return go({ view: "intro", id: s.id, preview: S.route.preview, useEditor: S.route.useEditor });
  const qs = s.questions || [];
  app.innerHTML = `<div class="narrow">${backBtn()}${previewNote()}
    <h1>${esc(s.title || "უსათაურო")}</h1>
    <div class="progwrap"><div class="progtop"><span id="progTxt"></span><b id="progPct">0%</b></div><div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" id="progBar"><i id="prog" style="width:0%"></i></div></div>
    <div class="panel pad" id="form">${qs.length ? qs.map(q => questionInput(q)).join("") : `<p class="muted">ამ კვლევაში კითხვები ჯერ არ არის.</p>`}</div>
    <div style="display:flex;justify-content:flex-end;gap:12px;margin-top:20px;align-items:center;flex-wrap:wrap">
      <span class="small" style="color:var(--warn)" id="formMsg"></span>
      <button class="btn primary lg" data-act="submit" ${qs.length ? "" : "disabled"}>პასუხების გაგზავნა</button></div></div>`;
  applyVisibility(true);
}

function questionInput(q) {
  const v = S.draft[q.id], o = S.draft[q.id + "__o"] || "";
  let body = "";
  const otherField = show => q.allowOther ? `<div class="other" data-otherwrap="${q.id}" ${show ? "" : "hidden"}><input class="field" data-other="${q.id}" value="${esc(o)}" placeholder="მიუთითეთ"></div>` : "";
  if (q.type === "single" || q.type === "yesno") {
    body = choicesOf(q).map(c => `<label class="opt"><input type="radio" name="q_${q.id}" data-q="${q.id}" value="${esc(c)}" ${v === c ? "checked" : ""}><span>${esc(c)}</span></label>`).join("") + otherField(v === OTHER);
  } else if (q.type === "multi") {
    const arr = Array.isArray(v) ? v : [];
    body = `<div class="limit">${q.maxSelect ? `შეგიძლიათ მონიშნოთ არაუმეტეს ${q.maxSelect} ვარიანტისა` : "შეგიძლიათ მონიშნოთ რამდენიმე ვარიანტი"}</div>` +
      choicesOf(q).map(c => `<label class="opt"><input type="checkbox" data-q="${q.id}" data-multi value="${esc(c)}" ${arr.includes(c) ? "checked" : ""}><span>${esc(c)}</span></label>`).join("") + otherField(arr.includes(OTHER));
  } else if (q.type === "dropdown") {
    body = `<select class="field" data-q="${q.id}"><option value="">აირჩიეთ…</option>${choicesOf(q).map(c => `<option ${v === c ? "selected" : ""}>${esc(c)}</option>`).join("")}</select>` +
      (q.allowOther ? `<div class="other" style="margin:10px 0 0" data-otherwrap="${q.id}" ${v === OTHER ? "" : "hidden"}><input class="field" data-other="${q.id}" value="${esc(o)}" placeholder="მიუთითეთ"></div>` : "");
  } else if (q.type === "scale") {
    const max = q.scaleMax || 5;
    body = `<div class="scale" role="group">${Array.from({ length: max }, (_, k) => k + 1).map(n => `<button type="button" data-scale="${q.id}" data-v="${n}" aria-pressed="${v === n}">${n}</button>`).join("")}</div>
      ${(q.minLabel || q.maxLabel) ? `<div class="scale-labels"><span>1 — ${esc(q.minLabel)}</span><span>${max} — ${esc(q.maxLabel)}</span></div>` : ""}`;
  } else if (q.type === "text") {
    body = `<input class="field" data-q="${q.id}" value="${esc(v || "")}" placeholder="თქვენი პასუხი">`;
  } else {
    body = `<textarea class="field" data-q="${q.id}" placeholder="თქვენი პასუხი">${esc(v || "")}</textarea>`;
  }
  return `<div class="q" id="q_${q.id}" data-qid="${q.id}"><div class="qn"></div><div class="qt">${esc(q.text || "კითხვა")}${q.required ? '<span class="req" aria-label="სავალდებულო">*</span>' : ""}</div>${q.help ? `<div class="qh">${esc(q.help)}</div>` : ""}<div class="qbody">${body}</div></div>`;
}
function applyVisibility(initial) {
  const s = getSurvey(S.route.id); if (!s) return;
  const vis = new Set(visibleQs(s.questions || [], S.draft).map(q => q.id));
  let n = 0;
  document.querySelectorAll("#form .q").forEach(el => {
    const show = vis.has(el.dataset.qid), wasHidden = el.hidden;
    el.hidden = !show; el.classList.remove("first");
    if (show) { n++; el.querySelector(".qn").textContent = n; if (n === 1) el.classList.add("first"); if (wasHidden && !initial) el.classList.add("followup"); }
    else el.classList.remove("missing");
  });
  updateProgress();
}
function updateProgress() {
  const s = getSurvey(S.route.id); if (!s) return;
  const vis = visibleQs(s.questions || [], S.draft);
  const done = vis.filter(q => answered(q, S.draft)).length;
  const p = pct(done, vis.length);
  const el = document.getElementById("prog"); if (!el) return;
  el.style.width = p + "%";
  document.getElementById("progPct").textContent = p + "%";
  document.getElementById("progTxt").textContent = `პასუხი გაცემულია ${done} / ${vis.length} კითხვაზე`;
  document.getElementById("progBar").setAttribute("aria-valuenow", p);
}
async function submitSurvey() {
  const s = getSurvey(S.route.id); if (!s) return;
  const vis = visibleQs(s.questions || [], S.draft);
  const missing = vis.filter(q => q.required && !answered(q, S.draft));
  document.querySelectorAll(".q.missing").forEach(e => e.classList.remove("missing"));
  const msg = document.getElementById("formMsg");
  if (missing.length) {
    missing.forEach(q => document.getElementById("q_" + q.id)?.classList.add("missing"));
    document.getElementById("q_" + missing[0].id)?.scrollIntoView({ behavior: "smooth", block: "center" });
    msg.textContent = `შესავსებია ${missing.length} სავალდებულო კითხვა`; return;
  }
  if (S.route.preview) { S.route.sent = true; render(); window.scrollTo({ top: 0 }); return; }
  if (!S.fbUser) { msg.textContent = "კავშირი ვერ დამყარდა — განაახლეთ გვერდი."; return; }
  const btn = document.querySelector('[data-act="submit"]'); btn.disabled = true; btn.textContent = "იგზავნება…";
  const values = {};
  vis.forEach(q => {
    const v = S.draft[q.id]; if (isEmpty(v)) return;
    values[q.id] = typeof v === "string" ? v.trim() : v;
    const hasOther = Array.isArray(v) ? v.includes(OTHER) : v === OTHER;
    if (q.allowOther && hasOther && !isEmpty(S.draft[q.id + "__o"])) values[q.id + "__o"] = S.draft[q.id + "__o"].trim();
  });
  const uid = S.fbUser.uid;
  const data = { surveyId: s.id, uid, values, submittedAt: Date.now(), ackAt: S.ack[s.id] || Date.now() };
  if (named(s)) { const id = S.ident[s.id] || {}; data.name = id.name || ""; if (s.askDept) data.dept = id.dept || ""; }
  try {
    await setDoc(doc(S.db, "responses", uid + "_" + s.id), data);
    ls.set(doneKey(s.id), "1"); S.draft = {}; S.route.sent = true; render(); window.scrollTo({ top: 0 });
  } catch (e) {
    btn.disabled = false; btn.textContent = "პასუხების გაგზავნა";
    if (e.code === "permission-denied") { msg.textContent = "ეს კვლევა ამ მოწყობილობიდან უკვე შევსებულია, ან დახურულია."; ls.set(doneKey(s.id), "1"); }
    else msg.textContent = "გაგზავნა ვერ მოხერხდა, სცადეთ ხელახლა.";
  }
}

/* ================= ADMIN: surveys ================= */
function renderAdminList() {
  const list = S.surveys;
  app.innerHTML = `
    <div class="head"><div><h1>კვლევები</h1><p class="muted">შექმენით კითხვარი, დაამატეთ შესავალი, გაააქტიურეთ და აქვე ნახეთ შედეგები.</p></div>
      <button class="btn primary" data-act="new">+ ახალი კვლევა</button></div>
    ${list.length ? `<div class="stats">
      <div class="stat"><b>${list.length}</b><span>კვლევა სულ</span></div>
      <div class="stat"><b>${list.filter(s => s.status === "active").length}</b><span>აქტიური</span></div>
      <div class="stat"><b>${S.resp.length}</b><span>პასუხი სულ</span></div>
      <div class="stat"><b style="font-size:1rem;padding:8px 0;overflow-wrap:anywhere">${esc(BASE_URL.replace(/^https?:\/\//, ""))}</b><span>თანამშრომლების ბმული <button class="link small" data-act="copyLink">კოპირება</button></span></div></div>
    <div class="panel rows">${list.map(s => {
      const n = responsesFor(s.id).length;
      return `<div class="row"><div>
        <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap"><h2>${esc(s.title || "უსათაურო")}</h2><span class="pill ${s.status}">${STATUS[s.status] || s.status}</span></div>
        <div class="meta"><span>${(s.questions || []).length} კითხვა</span><span>${n} პასუხი${s.targetCount ? ` / ${s.targetCount} (${pct(n, s.targetCount)}%)` : ""}</span><span>${named(s) ? "სახელით" : "ანონიმური"}</span><span>განახლდა ${esc(fmtDate(s.updatedAt))}</span></div></div>
        <div class="acts">
          <button class="btn primary sm" data-act="results" data-id="${s.id}">შედეგები</button>
          <button class="btn sm" data-act="edit" data-id="${s.id}">რედაქტირება</button>
          <button class="btn sm" data-act="preview" data-id="${s.id}">გადახედვა</button>
          <button class="btn ghost sm" data-act="dup" data-id="${s.id}">ასლი</button>
        </div></div>`;
    }).join("")}</div>` : `<div class="panel empty"><h2>ჯერ კვლევა არ გაქვთ</h2><p class="muted">შექმენით პირველი კითხვარი: დაწერეთ შესავალი, დაამატეთ კითხვები და გაააქტიურეთ.</p><button class="btn primary" data-act="new">+ ახალი კვლევა</button></div>`}`;
}

/* ---------- editor ---------- */
function openEditor(id) {
  const s = id ? S.surveys.find(x => x.id === id) : null;
  S.editor = s ? clone(s) : { id: nid(), title: "", description: "", status: "draft", identify: "anonymous", askDept: false, targetCount: null, intro: { title: "", text: "", consent: DEFAULT_CONSENT }, questions: [newQuestion("single")], isNew: true };
  if (!S.editor.intro) S.editor.intro = { title: "", text: "", consent: DEFAULT_CONSENT };
  if (!S.editor.identify) S.editor.identify = "anonymous";
  S.editor.dirty = false;
  go({ view: "edit" });
}
function depthOf(q, qs) { let d = 0, cur = q, g = 0; while (cur && cur.showIf && cur.showIf.qid && g++ < 20) { d++; cur = qs.find(x => x.id === cur.showIf.qid); } return d; }
function isDescendant(q, pid, qs) { let cur = q, g = 0; while (cur && cur.showIf && cur.showIf.qid && g++ < 20) { if (cur.showIf.qid === pid) return true; cur = qs.find(x => x.id === cur.showIf.qid); } return false; }

function renderEditor() {
  const e = S.editor; if (!e) return go({ view: "list" });
  const hasResp = !e.isNew && responsesFor(e.id).length > 0;
  const it = e.intro;
  app.innerHTML = `<div class="narrow">
    <button class="back" data-act="home">← კვლევები</button>
    <div class="head"><h1>${e.isNew ? "ახალი კვლევა" : "კვლევის რედაქტირება"}</h1></div>
    ${hasResp ? `<div class="note" style="margin-bottom:16px">ამ კვლევას უკვე აქვს პასუხები. ტექსტის შესწორება უსაფრთხოა; ვარიანტის გადარქმევისას ძველი პასუხები ძველ სახელს შეინარჩუნებს.</div>` : ""}
    <div class="panel pad">
      <label class="lbl" for="e_title">კვლევის სათაური</label>
      <input class="field" id="e_title" data-ef="title" value="${esc(e.title)}" placeholder="მაგ.: თანამშრომელთა კმაყოფილების კვლევა 2026">
      <label class="lbl" for="e_desc">მოკლე აღწერა (ჩანს კვლევების სიაში)</label>
      <input class="field" id="e_desc" data-ef="description" value="${esc(e.description)}">
      <div class="grid2">
        <div><label class="lbl" for="e_status">სტატუსი</label>
          <select class="field" id="e_status" data-ef="status">${Object.entries(STATUS).map(([k, v]) => `<option value="${k}" ${e.status === k ? "selected" : ""}>${v}</option>`).join("")}</select></div>
        <div><label class="lbl" for="e_target">თანამშრომლების რაოდენობა</label>
          <input class="field" id="e_target" type="number" min="1" data-ef="targetCount" value="${e.targetCount || ""}" placeholder="მონაწილეობის % გამოსათვლელად"></div>
        <div><label class="lbl" for="e_ident">მონაწილის იდენტიფიკაცია</label>
          <select class="field" id="e_ident" data-ef="identify"><option value="anonymous" ${e.identify !== "name" ? "selected" : ""}>ანონიმური</option><option value="name" ${e.identify === "name" ? "selected" : ""}>სახელით (თანამშრომელი წერს სახელს)</option></select></div>
        <div style="display:flex;align-items:flex-end;padding-bottom:12px">${e.identify === "name" ? `<label class="check"><input type="checkbox" data-ef="askDept" ${e.askDept ? "checked" : ""}> ასევე ვკითხოთ დეპარტამენტი</label>` : ""}</div>
      </div>
    </div>
    <div class="sec"><h2>შესავალი გვერდი</h2><p class="muted small" style="margin:-6px 0 10px">თანამშრომელი ჯერ ამ გვერდს ნახავს. კითხვებზე გადასვლა შესაძლებელია მხოლოდ გაცნობის დადასტურების შემდეგ.</p>
      <div class="panel pad">
        <label class="lbl" for="i_title">სათაური</label>
        <input class="field" id="i_title" data-intro="title" value="${esc(it.title)}" placeholder="მაგ.: მოგესალმებით!">
        <label class="lbl" for="i_text">შესავალი ტექსტი</label>
        <textarea class="field" id="i_text" data-intro="text" style="min-height:170px" placeholder="კვლევის მიზანი, ხანგრძლივობა, კონფიდენციალურობა, ვადა…">${esc(it.text)}</textarea>
        <label class="lbl" for="i_consent">დასადასტურებელი წინადადება</label>
        <input class="field" id="i_consent" data-intro="consent" value="${esc(it.consent)}">
      </div></div>
    <div class="sec"><h2>კითხვები</h2><p class="muted small" style="margin:-6px 0 0">არჩევით კითხვებში ყოველ პასუხს შეგიძლიათ მიაბათ შემდეგი კითხვა ღილაკით „↳ კითხვა ამ პასუხზე“ — ის მხოლოდ ამ პასუხის არჩევისას გამოჩნდება.</p>
    <div id="eqs">${e.questions.map((q, i) => editorQuestion(q, i)).join("")}</div>
    <div class="addq"><span class="muted small" style="width:100%">ახალი კითხვის დამატება:</span>
      ${Object.entries(TYPES).map(([k, v]) => `<button class="btn sm" data-act="addq" data-type="${k}">+ ${v}</button>`).join("")}</div></div>
    <div class="savebar"><span class="msg" id="saveMsg">${e.dirty ? "შეუნახავი ცვლილებები" : ""}</span>
      ${e.isNew ? "" : `<button class="btn sm" data-act="delete">წაშლა</button>`}
      <button class="btn" data-act="previewEditor">გადახედვა</button>
      <button class="btn" data-act="home">გაუქმება</button>
      <button class="btn primary" data-act="save">შენახვა</button></div>
  </div>`;
}
function editorQuestion(q, i) {
  const qs = S.editor.questions, n = qs.length, depth = depthOf(q, qs), isChoice = CHOICE.includes(q.type);
  let b = `<input class="field" data-qf="text" data-qi="${i}" value="${esc(q.text)}" placeholder="კითხვის ტექსტი">
    <input class="field small" style="margin-top:8px;padding:8px 12px" data-qf="help" data-qi="${i}" value="${esc(q.help || "")}" placeholder="განმარტება (არასავალდებულო)">`;
  if (isChoice) {
    const editable = q.type !== "yesno";
    b += (q.options || []).map((o, k) => `<div class="optrow"><span class="dot ${q.type === "multi" ? "sq" : ""}"></span>
      ${editable ? `<input class="field" data-opt="${k}" data-qi="${i}" value="${esc(o)}">` : `<span class="fixed">${esc(o)}</span>`}
      <button class="follow" data-act="follow" data-qi="${i}" data-val="${esc(o)}" title="კითხვა, რომელიც მხოლოდ ამ პასუხზე გამოჩნდება">↳ კითხვა ამ პასუხზე</button>
      ${editable ? `<button class="icon" data-act="delopt" data-qi="${i}" data-k="${k}" title="ვარიანტის წაშლა" ${q.options.length <= 1 ? "disabled" : ""}>${ICON.x}</button>` : ""}</div>`).join("");
    if (q.allowOther && editable) b += `<div class="optrow"><span class="dot ${q.type === "multi" ? "sq" : ""}"></span><span class="fixed">${OTHER} (ტექსტური ველით)</span><button class="follow" data-act="follow" data-qi="${i}" data-val="${OTHER}">↳ კითხვა ამ პასუხზე</button></div>`;
    if (editable) b += `<div style="display:flex;gap:16px;align-items:center;flex-wrap:wrap;margin-top:10px">
      <button class="btn ghost sm" data-act="addopt" data-qi="${i}">+ ვარიანტი</button>
      <label class="check"><input type="checkbox" data-qf="allowOther" data-qi="${i}" ${q.allowOther ? "checked" : ""}> „სხვა“ ვარიანტი ტექსტური ველით</label>
      ${q.type === "multi" ? `<label class="check">მაქს. მოსანიშნი: <select class="field" style="width:auto;padding:5px 8px" data-qf="maxSelect" data-qi="${i}"><option value="0">შეზღუდვის გარეშე</option>${Array.from({ length: Math.max(1, choicesOf(q).length - 1) }, (_, k) => k + 1).map(m => `<option value="${m}" ${q.maxSelect == m ? "selected" : ""}>${m}</option>`).join("")}</select></label>` : ""}</div>`;
  }
  if (q.type === "scale") b += `<div class="grid3">
      <div><label class="lbl" style="margin-top:0">მაქსიმუმი</label><select class="field" data-qf="scaleMax" data-qi="${i}">${[5, 7, 10].map(m => `<option ${q.scaleMax == m ? "selected" : ""}>${m}</option>`).join("")}</select></div>
      <div><label class="lbl" style="margin-top:0">1 ნიშნავს</label><input class="field" data-qf="minLabel" data-qi="${i}" value="${esc(q.minLabel)}"></div>
      <div><label class="lbl" style="margin-top:0">მაქსიმუმი ნიშნავს</label><input class="field" data-qf="maxLabel" data-qi="${i}" value="${esc(q.maxLabel)}"></div></div>`;
  b += `<label class="check" style="margin-top:12px"><input type="checkbox" data-qf="required" data-qi="${i}" ${q.required ? "checked" : ""}> სავალდებულო</label>`;
  const sources = qs.slice(0, i).filter(x => CHOICE.includes(x.type));
  let condTag = "";
  if (q.showIf && q.showIf.qid) {
    const src = qs.find(x => x.id === q.showIf.qid), srcIdx = qs.indexOf(src), vals = q.showIf.values || [];
    condTag = src ? `ჩანს, თუ ${srcIdx + 1}-ზე პასუხია: ${vals.length ? vals.map(v => "„" + esc(v) + "“").join(" ან ") : "—"}` : "პირობის კითხვა წაშლილია";
    b += `<div class="condbox"><div style="display:flex;justify-content:space-between;gap:10px;align-items:center;flex-wrap:wrap">
        <strong class="small">ჩვენების პირობა</strong><button class="btn ghost sm" data-act="delcond" data-qi="${i}">პირობის მოხსნა</button></div>
      <label class="lbl" style="margin-top:6px">აჩვენე ეს კითხვა, თუ კითხვაზე</label>
      <select class="field" data-cond-src data-qi="${i}">${!src ? `<option value="">— აირჩიეთ —</option>` : ""}${sources.map(x => `<option value="${x.id}" ${src && x.id === src.id ? "selected" : ""}>${qs.indexOf(x) + 1}. ${esc(x.text || "უსათაურო კითხვა")}</option>`).join("")}</select>
      ${src ? `<label class="lbl">არჩეულია ერთ-ერთი პასუხი:</label><div class="chips">${choicesOf(src).map(c => `<label class="chip"><input type="checkbox" data-cond-val data-qi="${i}" value="${esc(c)}" ${vals.includes(c) ? "checked" : ""}>${esc(c)}</label>`).join("")}</div>` : ""}
      ${src && srcIdx > i ? `<div class="warnline">პირობის კითხვა ამ კითხვის შემდეგაა — გადაიტანეთ ეს კითხვა ქვემოთ.</div>` : ""}
      ${src && !vals.length ? `<div class="warnline">მონიშნეთ მინიმუმ ერთი პასუხი, თორემ კითხვა არასოდეს გამოჩნდება.</div>` : ""}
      ${src && !CHOICE.includes(src.type) ? `<div class="warnline">პირობის კითხვა აღარ არის არჩევითი ტიპის.</div>` : ""}</div>`;
  } else if (sources.length) b += `<button class="btn ghost sm" style="margin-top:10px;padding-left:0" data-act="addcond" data-qi="${i}">+ ჩვენების პირობა</button>`;
  return `<div class="eq ${depth ? "cond" : ""}" style="margin-left:${Math.min(depth, 4) * 22}px" data-eq="${i}"><div class="eq-h"><span class="num">${i + 1}</span>
    <select data-qf="type" data-qi="${i}" aria-label="კითხვის ტიპი">${Object.entries(TYPES).map(([k, v]) => `<option value="${k}" ${q.type === k ? "selected" : ""}>${v}</option>`).join("")}</select>
    ${condTag ? `<span class="condtag">${condTag}</span>` : ""}
    <span class="sp"><button class="icon" data-act="mvq" data-qi="${i}" data-d="-1" title="ზემოთ" ${i === 0 ? "disabled" : ""}>${ICON.up}</button>
    <button class="icon" data-act="mvq" data-qi="${i}" data-d="1" title="ქვემოთ" ${i === n - 1 ? "disabled" : ""}>${ICON.down}</button>
    <button class="icon" data-act="dupq" data-qi="${i}" title="დუბლირება">${ICON.copy}</button>
    <button class="icon" data-act="delq" data-qi="${i}" title="წაშლა">${ICON.del}</button></span></div>
    <div class="eq-b">${b}</div></div>`;
}
function markDirty() { if (!S.editor) return; S.editor.dirty = true; const m = document.getElementById("saveMsg"); if (m) m.textContent = "შეუნახავი ცვლილებები"; }
function rerenderEditor(focusIdx) {
  const y = window.scrollY; renderEditor(); window.scrollTo({ top: y });
  if (focusIdx !== undefined) { const el = document.querySelector(`[data-eq="${focusIdx}"]`); if (el) { el.scrollIntoView({ behavior: "smooth", block: "center" }); el.querySelector('[data-qf="text"]')?.focus({ preventScroll: true }); } }
}
function validateEditor(e) {
  if (!e.title.trim()) return "მიუთითეთ კვლევის სათაური";
  if (!e.questions.length) return "დაამატეთ მინიმუმ ერთი კითხვა";
  for (let i = 0; i < e.questions.length; i++) {
    const q = e.questions[i];
    if (!q.text.trim()) return `კითხვა ${i + 1}: დაწერეთ კითხვის ტექსტი`;
    if (["single", "multi", "dropdown"].includes(q.type) && !(q.options || []).filter(x => x.trim()).length) return `კითხვა ${i + 1}: დაამატეთ პასუხის ვარიანტები`;
    if (q.showIf && q.showIf.qid) {
      const si = e.questions.findIndex(x => x.id === q.showIf.qid);
      if (si < 0) return `კითხვა ${i + 1}: აირჩიეთ პირობის კითხვა ან მოხსენით პირობა`;
      if (si >= i) return `კითხვა ${i + 1}: პირობის კითხვა (${si + 1}) უნდა იყოს მის ზემოთ`;
      if (!CHOICE.includes(e.questions[si].type)) return `კითხვა ${i + 1}: პირობის კითხვა უნდა იყოს არჩევითი ტიპის`;
      if (!(q.showIf.values || []).length) return `კითხვა ${i + 1}: მონიშნეთ პასუხი, რომელზეც უნდა გამოჩნდეს`;
    }
  }
  return null;
}
async function saveEditor() {
  const e = S.editor, err = validateEditor(e); if (err) { toast(err); return; }
  const d = {
    title: e.title.trim(), description: (e.description || "").trim(), status: e.status, identify: e.identify === "name" ? "name" : "anonymous", askDept: e.identify === "name" && !!e.askDept,
    targetCount: e.targetCount ? Number(e.targetCount) : null,
    intro: { title: (e.intro.title || "").trim(), text: (e.intro.text || "").trim(), consent: (e.intro.consent || "").trim() || DEFAULT_CONSENT },
    questions: e.questions.map(q => {
      const o = { id: q.id, type: q.type, text: q.text.trim(), help: (q.help || "").trim(), required: !!q.required };
      if (CHOICE.includes(q.type)) o.options = q.type === "yesno" ? ["კი", "არა"] : (q.options || []).map(x => x.trim()).filter(Boolean);
      if (["single", "multi", "dropdown"].includes(q.type)) o.allowOther = !!q.allowOther;
      if (q.type === "multi") o.maxSelect = Number(q.maxSelect) || 0;
      if (q.type === "scale") { o.scaleMax = Number(q.scaleMax) || 5; o.minLabel = q.minLabel || ""; o.maxLabel = q.maxLabel || ""; }
      if (q.showIf && q.showIf.qid) o.showIf = { qid: q.showIf.qid, values: q.showIf.values || [] };
      return o;
    }),
    createdAt: e.createdAt || Date.now(), updatedAt: Date.now(), createdBy: e.createdBy || S.email || null
  };
  const btn = document.querySelector('[data-act="save"]'); btn.disabled = true;
  try { await setDoc(doc(S.db, "surveys", e.id), d); S.editor = null; toast("კვლევა შენახულია"); go({ view: "list" }); }
  catch (er) { btn.disabled = false; toast(er.code === "permission-denied" ? "შენახვის უფლება არ გაქვთ" : "შენახვა ვერ მოხერხდა"); }
}

/* ================= ADMIN: results ================= */
function shownCount(q, s, R) { return R.filter(r => visibleQs(s.questions, r.values || {}).some(x => x.id === q.id)).length; }
function whoCell(s, r, idx) { return named(s) ? `${esc(r.name || "უსახელო")}${r.dept ? ` <span class="muted small">· ${esc(r.dept)}</span>` : ""}` : `რესპონდენტი #${idx}`; }
function renderResults() {
  const s = S.surveys.find(x => x.id === S.route.id); if (!s) return go({ view: "list" });
  const R = responsesFor(s.id), tab = S.route.tab || "summary", qs = s.questions || [];
  const last = R.length ? R[R.length - 1].submittedAt : null;
  const completion = R.length ? Math.round(R.reduce((a, r) => { const v = visibleQs(qs, r.values || {}); return a + (v.length ? v.filter(q => answered(q, r.values || {})).length / v.length : 1); }, 0) / R.length * 100) : 0;
  let body = "";
  if (!R.length) body = `<div class="panel empty"><h2>პასუხები ჯერ არ არის</h2><p class="muted">${s.status === "active" ? "კვლევა აქტიურია — პასუხები აქ ავტომატურად გამოჩნდება." : "გაააქტიურეთ კვლევა, რომ თანამშრომლებმა შეავსონ."}</p>${s.status !== "active" ? `<button class="btn primary" data-act="activate" data-id="${s.id}">გააქტიურება</button>` : ""}</div>`;
  else if (tab === "summary") body = qs.map((q, i) => resultCard(q, i, R, s)).join("");
  else body = responsesTable(s, R);
  app.innerHTML = `
    <button class="back" data-act="home">← კვლევები</button>
    <div class="head"><div><div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap"><h1>${esc(s.title)}</h1><span class="pill ${s.status}">${STATUS[s.status]}</span></div>
      ${s.description ? `<p class="muted">${esc(s.description)}</p>` : ""}</div>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        ${s.status === "active" ? `<button class="btn sm" data-act="close" data-id="${s.id}">დახურვა</button>` : `<button class="btn sm" data-act="activate" data-id="${s.id}">გააქტიურება</button>`}
        <button class="btn sm" data-act="edit" data-id="${s.id}">რედაქტირება</button>
        ${R.length ? `<button class="btn primary sm" data-act="csv" data-id="${s.id}">CSV ექსპორტი</button>` : ""}</div></div>
    <div class="stats">
      <div class="stat"><b>${R.length}</b><span>პასუხი</span></div>
      <div class="stat"><b>${s.targetCount ? pct(R.length, s.targetCount) + "%" : "—"}</b><span>${s.targetCount ? `მონაწილეობა (${s.targetCount}-დან)` : "მონაწილეობა — მიუთითეთ რაოდენობა"}</span></div>
      <div class="stat"><b>${R.length ? completion + "%" : "—"}</b><span>ნაჩვენები კითხვების შევსება</span></div>
      <div class="stat"><b style="font-size:1.1rem;padding:7px 0">${esc(fmtDT(last))}</b><span>ბოლო პასუხი</span></div></div>
    ${R.length > 1 ? timeline(R) : ""}
    ${R.length ? `<div class="tabs" role="tablist">
      <button role="tab" data-act="tab" data-tab="summary" aria-selected="${tab === "summary"}">შეჯამება</button>
      <button role="tab" data-act="tab" data-tab="responses" aria-selected="${tab === "responses"}">ინდივიდუალური პასუხები</button></div>` : ""}
    ${body}`;
}
function timeline(R) {
  const day = 864e5, start = new Date(R[0].submittedAt); start.setHours(0, 0, 0, 0);
  const end = new Date(); end.setHours(0, 0, 0, 0);
  let days = Math.round((end - start) / day) + 1;
  const from = days > 30 ? end.getTime() - 29 * day : start.getTime();
  days = Math.max(1, Math.min(days, 30));
  const counts = Array(days).fill(0);
  R.forEach(r => { const d = new Date(r.submittedAt); d.setHours(0, 0, 0, 0); const k = Math.round((d - from) / day); if (k >= 0 && k < days) counts[k]++; });
  const max = Math.max(...counts, 1);
  return `<div class="panel pad" style="margin-bottom:22px"><h3>პასუხები დღეების მიხედვით</h3>
    <div class="timeline">${counts.map((c, k) => `<i style="height:${c ? Math.max(4, c / max * 100) : 2}%;${c ? "" : "opacity:.2"}" title="${esc(fmtDate(from + k * day))}: ${c}"></i>`).join("")}</div>
    <div class="tl-l"><span>${esc(fmtDate(from))}</span><span>დღეს</span></div></div>`;
}
function hbars(rows, base) {
  const maxC = Math.max(...rows.map(r => r[1]), 0);
  return rows.map(([lab, c]) => `<div class="hbar ${c && c === maxC ? "top" : ""}"><span class="lab">${esc(lab)}</span><span class="track"><span class="fill" style="width:${pct(c, base)}%"></span></span><span class="v"><b>${pct(c, base)}%</b> · ${c}</span></div>`).join("");
}
function resultCard(q, i, R, s) {
  const base = shownCount(q, s, R), ans = R.filter(r => !isEmpty((r.values || {})[q.id])), n = ans.length;
  const V = r => r.values || {};
  let b = "";
  if (!n) b = `<p class="muted small">ამ კითხვას პასუხი არ აქვს.</p>`;
  else if (CHOICE.includes(q.type)) {
    const opts = choicesOf(q);
    ans.forEach(r => (Array.isArray(V(r)[q.id]) ? V(r)[q.id] : [V(r)[q.id]]).forEach(v => { if (!opts.includes(v)) opts.push(v); }));
    const cnt = o => ans.filter(r => Array.isArray(V(r)[q.id]) ? V(r)[q.id].includes(o) : V(r)[q.id] === o).length;
    b = (q.type === "multi" ? `<p class="muted small" style="margin-bottom:10px">% — მოპასუხეების წილი, ვინც ვარიანტი მონიშნა</p>` : "") + hbars(opts.map(o => [o, cnt(o)]), n);
    const others = ans.map(r => V(r)[q.id + "__o"]).filter(x => !isEmpty(x));
    if (others.length) b += `<div class="subh">„სხვა“ — მითითებული პასუხები (${others.length})</div><div class="texts">${others.map(t => `<blockquote>${esc(t)}</blockquote>`).join("")}</div>`;
  } else if (q.type === "scale") {
    const max = q.scaleMax || 5, vals = ans.map(r => Number(V(r)[q.id]));
    const avg = vals.reduce((a, v) => a + v, 0) / vals.length, so = [...vals].sort((a, b) => a - b);
    const med = so.length % 2 ? so[(so.length - 1) / 2] : (so[so.length / 2 - 1] + so[so.length / 2]) / 2;
    const dist = Array.from({ length: max }, (_, k) => vals.filter(v => v === k + 1).length), dmax = Math.max(...dist, 1);
    b = `<div class="avg"><b>${avg.toFixed(1)}</b><span class="muted">/ ${max} საშუალო · მედიანა ${med} · მაღალი შეფასება ${pct(vals.filter(v => v > max * 0.7).length, n)}%</span></div>
      <div class="cols">${dist.map((c, k) => `<div class="col"><div class="c" style="height:${c ? Math.max(3, c / dmax * 100) : 2}%;${c ? "" : "opacity:.25"}"><em>${c ? pct(c, n) + "%" : ""}</em></div><small>${k + 1}</small></div>`).join("")}</div>
      ${(q.minLabel || q.maxLabel) ? `<div class="scale-labels"><span>${esc(q.minLabel)}</span><span>${esc(q.maxLabel)}</span></div>` : ""}`;
  } else b = `<div class="texts">${ans.slice().reverse().map(r => `<blockquote>${esc(V(r)[q.id])}${named(s) ? `<cite>${esc(r.name || "")} · ${esc(fmtDate(r.submittedAt))}</cite>` : ""}</blockquote>`).join("")}</div>`;
  let cond = "";
  if (q.showIf && q.showIf.qid) { const si = s.questions.findIndex(x => x.id === q.showIf.qid); cond = `<p class="small" style="color:var(--accent);margin:-8px 0 12px">პირობითი: ჩანდა, თუ ${si + 1}-ზე პასუხია ${(q.showIf.values || []).map(v => "„" + esc(v) + "“").join(" ან ")} — ნაჩვენებია ${base} მოპასუხეს</p>`; }
  return `<div class="panel pad rq"><div class="rq-h"><div class="t"><span class="n">${i + 1}</span><h3>${esc(q.text)}</h3></div><span class="muted small">${TYPES[q.type]} · პასუხი ${n}/${base}</span></div>${cond}${b}</div>`;
}
function responsesTable(s, R) {
  const qs = s.questions || [], rows = R.slice().reverse();
  return `<p class="muted small" style="margin-bottom:10px">დააჭირეთ სტრიქონს პასუხის სრულად სანახავად. „·“ ნიშნავს, რომ კითხვა რესპონდენტს არ უჩანდა.</p>
    <div class="panel scroll"><table><thead><tr><th>რესპონდენტი</th><th>თარიღი</th>${qs.map((q, i) => `<th>${i + 1}. ${esc(q.text)}</th>`).join("")}</tr></thead>
    <tbody>${rows.map((r, k) => { const vals = r.values || {}, vis = new Set(visibleQs(qs, vals).map(x => x.id)); return `<tr data-act="openResp" data-rid="${esc(r.id)}"><td>${whoCell(s, r, R.length - k)}</td><td>${esc(fmtDT(r.submittedAt))}</td>${qs.map(q => `<td>${vis.has(q.id) ? (esc(fmtVal(q, vals)) || '<span class="muted">—</span>') : '<span class="muted">·</span>'}</td>`).join("")}</tr>`; }).join("")}</tbody></table></div>`;
}
function renderResponses() {
  const f = S.route.filter || "";
  const all = [];
  S.surveys.forEach(s => { if (f && s.id !== f) return; responsesFor(s.id).forEach((r, k) => all.push({ r, s, idx: k + 1 })); });
  all.sort((a, b) => (b.r.submittedAt || 0) - (a.r.submittedAt || 0));
  app.innerHTML = `<div class="head"><div><h1>პასუხები</h1><p class="muted">ყველა შემოსული პასუხი. დააჭირეთ პასუხს სრულად სანახავად.</p></div></div>
    <div class="filter"><select class="field" id="respFilter"><option value="">ყველა კვლევა</option>${S.surveys.map(s => `<option value="${s.id}" ${f === s.id ? "selected" : ""}>${esc(s.title || "უსათაურო")} (${responsesFor(s.id).length})</option>`).join("")}</select>
      <span class="muted small">${all.length} პასუხი</span></div>
    ${all.length ? `<div class="panel rows">${all.slice(0, 500).map(({ r, s, idx }) => `<div class="row click" data-act="openResp" data-rid="${esc(r.id)}"><div><h3>${whoCell(s, r, idx)}</h3>
      <div class="meta"><span>${esc(s.title || "უსათაურო")}</span><span>${esc(fmtDT(r.submittedAt))}</span></div></div><div class="acts"><span class="btn sm">ნახვა</span></div></div>`).join("")}</div>`
      : `<div class="panel empty"><h2>პასუხები ჯერ არ არის</h2><p class="muted">როცა თანამშრომლები შეავსებენ აქტიურ კვლევას, პასუხები აქ გამოჩნდება.</p></div>`}`;
}
function renderResponse() {
  const r = S.resp.find(x => x.id === S.route.rid); if (!r) return go({ view: "responses" });
  const s = S.surveys.find(x => x.id === r.surveyId); if (!s) return go({ view: "responses" });
  const R = responsesFor(s.id), idx = R.findIndex(x => x.id === r.id), vals = r.values || {};
  const vis = visibleQs(s.questions, vals);
  app.innerHTML = `<div class="narrow"><button class="back" data-act="respBack">← უკან</button>
    <div class="head"><div><h1>${whoCell(s, r, idx + 1)}</h1><p class="muted">${esc(s.title)} · გაგზავნილია ${esc(fmtDT(r.submittedAt))}${r.ackAt ? ` · შესავალი დადასტურდა ${esc(fmtDT(r.ackAt))}` : ""}</p></div>
      <div style="display:flex;gap:8px">${idx > 0 ? `<button class="btn sm" data-act="openResp" data-rid="${esc(R[idx - 1].id)}">← წინა</button>` : ""}${idx < R.length - 1 ? `<button class="btn sm" data-act="openResp" data-rid="${esc(R[idx + 1].id)}">შემდეგი →</button>` : ""}</div></div>
    <div class="panel pad">${vis.map((q, i) => { const v = fmtVal(q, vals); return `<div class="ans"><div class="qt"><span style="color:var(--accent);font-weight:800;margin-right:8px">${i + 1}</span>${esc(q.text)}</div><div class="a ${v ? "" : "none"}">${v ? esc(v) : "პასუხი არ არის"}</div></div>`; }).join("")}</div>
    <p style="margin-top:18px;text-align:right"><button class="btn sm" data-act="delResp" data-rid="${esc(r.id)}">პასუხის წაშლა</button></p></div>`;
}
function exportCSV(sid) {
  const s = S.surveys.find(x => x.id === sid), R = responsesFor(sid), qs = s.questions || [];
  const cell = v => `"${String(v ?? "").replace(/"/g, '""')}"`;
  const head = ["რესპონდენტი", ...(named(s) && s.askDept ? ["დეპარტამენტი"] : []), "გაგზავნის თარიღი", "შესავლის დადასტურება", ...qs.map((q, i) => `${i + 1}. ${q.text}`)];
  const rows = R.map((r, k) => { const vals = r.values || {}, vis = new Set(visibleQs(qs, vals).map(x => x.id));
    return [named(s) ? (r.name || "") : `#${k + 1}`, ...(named(s) && s.askDept ? [r.dept || ""] : []), new Date(r.submittedAt).toLocaleString("ka-GE"), r.ackAt ? new Date(r.ackAt).toLocaleString("ka-GE") : "", ...qs.map(q => vis.has(q.id) ? fmtVal(q, vals) : "(არ უჩანდა)")]; });
  const csv = "\ufeff" + [head, ...rows].map(r => r.map(cell).join(",")).join("\r\n");
  const safe = (s.title || "survey").replace(/[^\p{L}\p{N}\- ]/gu, "").trim().replace(/\s+/g, "-").slice(0, 60) || "survey";
  const a = document.createElement("a"); a.href = URL.createObjectURL(new Blob([csv], { type: "text/csv;charset=utf-8" })); a.download = safe + ".csv";
  document.body.appendChild(a); a.click(); setTimeout(() => { URL.revokeObjectURL(a.href); a.remove(); }, 500);
}

/* ================= ADMIN: admins (owner) ================= */
function renderAdmins() {
  app.innerHTML = `<div class="narrow">
    <div class="head"><div><h1>ადმინისტრატორები</h1><p class="muted">ადმინ პანელს ხედავენ მხოლოდ აქ დამატებული პირები, რომლებმაც მეილზე მისული ბმულით შესვლა და როლი დაადასტურეს.</p></div></div>
    <div class="panel pad"><h2>ადმინის მოწვევა</h2><p class="muted small">მითითებულ მეილზე ავტომატურად გაიგზავნება შესვლის ბმული. ადმინი გახსნის ბმულს, დაადასტურებს როლს და მიიღებს წვდომას.</p>
      <div class="adminform" style="margin-top:14px"><input class="field" type="email" id="invEmail" placeholder="name@zoommer.ge" autocomplete="off"><button class="btn primary" data-act="invite">მოწვევის გაგზავნა</button></div></div>
    <div class="panel rows" style="margin-top:18px">
      ${OWNER_EMAILS.map(e => `<div class="row"><div><h3>${esc(e)}</h3><div class="meta"><span>მფლობელი — სრული წვდომა</span></div></div><div class="acts"><span class="pill ok">აქტიური</span></div></div>`).join("")}
      ${S.admins.map(a => `<div class="row"><div><h3>${esc(a.email || a.id)}</h3><div class="meta"><span>${a.status === "active" ? `დარეგისტრირდა ${esc(fmtDate(a.acceptedAt))}` : `მოწვეულია ${esc(fmtDate(a.invitedAt))} — ელოდება დადასტურებას`}</span></div></div>
        <div class="acts">${a.status === "active" ? `<span class="pill ok">აქტიური</span>` : `<span class="pill">მოწვეული</span><button class="btn sm" data-act="resend" data-email="${esc(a.id)}">ხელახლა გაგზავნა</button>`}<button class="btn sm" data-act="revoke" data-email="${esc(a.id)}">წაშლა</button></div></div>`).join("")}
    </div>
    <p class="muted small" style="margin-top:14px">თუ წერილი არ მოვიდა, სთხოვეთ შეამოწმოს Spam. ასევე შეუძლია თავად გახსნას <b>${esc(BASE_URL)}?admin</b> და იქიდან მოითხოვოს შესვლის ბმული.</p>
  </div>`;
}

/* ================= events ================= */
document.getElementById("nav").addEventListener("click", e => {
  const b = e.target.closest("button"); if (!b) return;
  if (b.dataset.act === "signout") { signOutNow(); return; }
  if (!b.dataset.nav) return;
  S.editor = null; S.draft = {}; go({ view: b.dataset.nav === "surveys" ? "list" : b.dataset.nav });
});
async function signOutNow() { unsubs.forEach(u => u()); unsubs = []; S.surveysReady = false; await signOut(S.auth); S.authState = "signedout"; S.role = "none"; render(); }

app.addEventListener("click", async e => {
  const sc = e.target.closest("[data-scale]");
  if (sc) { S.draft[sc.dataset.scale] = Number(sc.dataset.v); sc.parentElement.querySelectorAll("button").forEach(b => b.setAttribute("aria-pressed", String(b === sc))); sc.closest(".q").classList.remove("missing"); applyVisibility(); return; }
  const t = e.target.closest("[data-act]"); if (!t || t.tagName === "INPUT") return;
  const act = t.dataset.act, id = t.dataset.id, qi = Number(t.dataset.qi), E = S.editor;
  switch (act) {
    case "signout": signOutNow(); break;
    case "sendLink": {
      const em = lc(document.getElementById("loginEmail").value);
      if (!validEmail(em)) { toast("ჩაწერეთ სწორი მეილი"); return; }
      t.disabled = true;
      try { await sendSignInLinkToEmail(S.auth, em, linkSettings(em)); ls.set("kv_email", em); S.linkEmail = em; S.authState = "linkSent"; render(); }
      catch (er) { t.disabled = false; toast("ბმული ვერ გაიგზავნა: " + (er.code || "")); }
      break;
    }
    case "backToLogin": S.authState = "signedout"; render(); break;
    case "finishLink": { const em = lc(document.getElementById("confirmEmail").value); if (!validEmail(em)) { toast("ჩაწერეთ სწორი მეილი"); return; } completeLink(em); break; }
    case "acceptRole":
      try { await updateDoc(doc(S.db, "admins", S.email), { status: "active", uid: S.fbUser.uid, acceptedAt: Date.now() }); S.role = "active"; toast("რეგისტრაცია დასრულდა"); enterDashboard(); }
      catch (er) { toast("ვერ მოხერხდა: " + (er.code || "")); }
      break;
    case "copyLink": try { await navigator.clipboard.writeText(BASE_URL); toast("ბმული დაკოპირდა"); } catch (er) { toast(BASE_URL); } break;
    case "home":
      if (S.route.view === "edit" && E && E.dirty && !t.dataset.sure) { t.dataset.sure = "1"; t.textContent = "გაუქმდეს ცვლილებები?"; return; }
      if (S.route.view === "edit" || !S.route.useEditor) S.editor = null;
      S.draft = {}; go({ view: "list" }); break;
    case "toEditor": S.draft = {}; go({ view: "edit" }); break;
    case "start": S.draft = {}; go({ view: "intro", id }); break;
    case "ack": {
      const s = getSurvey(S.route.id);
      if (named(s)) {
        const name = (document.getElementById("idName").value || "").trim();
        if (!name) { document.getElementById("introMsg").textContent = "ჩაწერეთ სახელი და გვარი"; document.getElementById("idName").focus(); return; }
        S.ident[s.id] = { name, dept: (document.getElementById("idDept")?.value || "").trim() };
      }
      S.ack[s.id] = Date.now(); go({ view: "take", id: s.id, preview: S.route.preview, useEditor: S.route.useEditor }); break;
    }
    case "submit": submitSurvey(); break;
    case "new": openEditor(null); break;
    case "edit": openEditor(id); break;
    case "dup": duplicate(id); break;
    case "preview": S.draft = {}; delete S.ack[id]; go({ view: "intro", id, preview: true }); break;
    case "previewEditor": S.draft = {}; delete S.ack[E.id]; go({ view: "intro", id: E.id, preview: true, useEditor: true }); break;
    case "results": go({ view: "results", id, tab: "summary" }); break;
    case "tab": S.route.tab = t.dataset.tab; render(); break;
    case "activate": setStatus(id, "active"); break;
    case "close": setStatus(id, "closed"); break;
    case "csv": exportCSV(id); break;
    case "openResp": go({ view: "response", rid: t.dataset.rid, from: S.route.view === "response" ? S.route.from : S.route }); break;
    case "respBack": go(S.route.from || { view: "responses" }); break;
    case "delResp":
      if (!t.classList.contains("armed")) { t.classList.add("armed"); t.textContent = "დაადასტურეთ წაშლა"; return; }
      try { await deleteDoc(doc(S.db, "responses", t.dataset.rid)); toast("პასუხი წაიშალა"); go(S.route.from || { view: "responses" }); } catch (er) { toast("წაშლა ვერ მოხერხდა"); }
      break;
    case "save": saveEditor(); break;
    case "delete":
      if (!t.classList.contains("armed")) { t.classList.add("armed"); t.textContent = "დაადასტურეთ წაშლა"; setTimeout(() => { if (t.isConnected) { t.classList.remove("armed"); t.textContent = "წაშლა"; } }, 4000); return; }
      try { await deleteDoc(doc(S.db, "surveys", E.id)); S.editor = null; toast("კვლევა წაიშალა"); go({ view: "list" }); } catch (er) { toast("წაშლა ვერ მოხერხდა"); }
      break;
    case "addq": E.questions.push(newQuestion(t.dataset.type)); markDirty(); rerenderEditor(E.questions.length - 1); break;
    case "follow": {
      const p = E.questions[qi]; let j = qi + 1; while (j < E.questions.length && isDescendant(E.questions[j], p.id, E.questions)) j++;
      const nq = newQuestion("text"); nq.showIf = { qid: p.id, values: [t.dataset.val] }; E.questions.splice(j, 0, nq); markDirty(); rerenderEditor(j); break;
    }
    case "addcond": { const src = E.questions.slice(0, qi).filter(x => CHOICE.includes(x.type)).pop(); E.questions[qi].showIf = { qid: src.id, values: [] }; markDirty(); rerenderEditor(); break; }
    case "delcond": delete E.questions[qi].showIf; markDirty(); rerenderEditor(); break;
    case "delq": {
      const gone = E.questions[qi].id; E.questions.splice(qi, 1); let c = 0;
      E.questions.forEach(q => { if (q.showIf && q.showIf.qid === gone) { delete q.showIf; c++; } });
      if (c) toast(`${c} პირობით კითხვას პირობა მოეხსნა`); markDirty(); rerenderEditor(); break;
    }
    case "dupq": { const c = clone(E.questions[qi]); c.id = nid(); E.questions.splice(qi + 1, 0, c); markDirty(); rerenderEditor(qi + 1); break; }
    case "mvq": { const j = qi + Number(t.dataset.d); [E.questions[qi], E.questions[j]] = [E.questions[j], E.questions[qi]]; markDirty(); rerenderEditor(); break; }
    case "addopt": { const q = E.questions[qi]; q.options.push(`ვარიანტი ${q.options.length + 1}`); markDirty(); rerenderEditor(); const ins = document.querySelectorAll(`[data-opt][data-qi="${qi}"]`); ins[ins.length - 1]?.select(); break; }
    case "delopt": { const q = E.questions[qi]; const [old] = q.options.splice(Number(t.dataset.k), 1); E.questions.forEach(x => { if (x.showIf && x.showIf.qid === q.id) x.showIf.values = (x.showIf.values || []).filter(v => v !== old); }); markDirty(); rerenderEditor(); break; }
    case "invite": {
      const inp = document.getElementById("invEmail"), em = lc(inp.value);
      if (!validEmail(em)) { toast("ჩაწერეთ სწორი მეილი"); inp.focus(); return; }
      if (OWNER_EMAILS.map(lc).includes(em) || S.admins.some(a => a.id === em)) { toast("ეს მეილი უკვე სიაშია"); return; }
      t.disabled = true;
      try {
        await setDoc(doc(S.db, "admins", em), { email: em, status: "invited", invitedAt: Date.now(), invitedBy: S.email });
        await sendSignInLinkToEmail(S.auth, em, linkSettings(em));
        toast("მოწვევა გაიგზავნა " + em + "-ზე");
      } catch (er) { toast("ვერ მოხერხდა: " + (er.code || "")); }
      t.disabled = false; break;
    }
    case "resend": try { await sendSignInLinkToEmail(S.auth, t.dataset.email, linkSettings(t.dataset.email)); toast("ბმული ხელახლა გაიგზავნა"); } catch (er) { toast("ვერ გაიგზავნა: " + (er.code || "")); } break;
    case "revoke":
      if (!t.classList.contains("armed")) { t.classList.add("armed"); t.textContent = "დადასტურება"; return; }
      try { await deleteDoc(doc(S.db, "admins", t.dataset.email)); toast("ადმინი წაიშალა"); } catch (er) { toast("ვერ მოხერხდა"); }
      break;
  }
});

function onField(e) {
  const t = e.target;
  if (t.id === "ackBox") { const b = document.getElementById("ackBtn"); if (b) b.disabled = !t.checked; return; }
  if (t.id === "regOk") { const b = document.getElementById("regBtn"); if (b) b.disabled = !t.checked; return; }
  if (t.id === "respFilter") { S.route.filter = t.value; render(); return; }
  if (S.route.view === "take" && (t.dataset.q || t.dataset.other)) {
    if (t.dataset.other) { S.draft[t.dataset.other + "__o"] = t.value; updateProgress(); return; }
    const qid = t.dataset.q, s = getSurvey(S.route.id), q = (s.questions || []).find(x => x.id === qid);
    if (t.dataset.multi !== undefined) {
      const boxes = [...document.querySelectorAll(`[data-q="${qid}"][data-multi]`)];
      S.draft[qid] = boxes.filter(x => x.checked).map(x => x.value);
      if (q && q.maxSelect) { const full = S.draft[qid].length >= q.maxSelect; boxes.forEach(x => { if (!x.checked) x.disabled = full; }); }
    } else S.draft[qid] = t.value;
    const ow = document.querySelector(`[data-otherwrap="${qid}"]`);
    if (ow) { const v = S.draft[qid]; const show = Array.isArray(v) ? v.includes(OTHER) : v === OTHER; ow.hidden = !show; if (show && e.type === "change") ow.querySelector("input").focus(); }
    t.closest(".q")?.classList.remove("missing"); applyVisibility(); return;
  }
  const E = S.editor; if (!E || S.route.view !== "edit") return;
  if (t.dataset.ef) { E[t.dataset.ef] = t.type === "checkbox" ? t.checked : t.value; markDirty(); if (t.dataset.ef === "identify") rerenderEditor(); return; }
  if (t.dataset.intro) { E.intro[t.dataset.intro] = t.value; markDirty(); return; }
  const qi = Number(t.dataset.qi);
  if (t.dataset.qf) {
    const q = E.questions[qi], f = t.dataset.qf;
    if (f === "type") {
      if (e.type !== "change") return;
      const nq = newQuestion(t.value); nq.id = q.id; nq.text = q.text; nq.help = q.help; nq.required = q.required; if (q.showIf) nq.showIf = q.showIf;
      if (["single", "multi", "dropdown"].includes(t.value) && ["single", "multi", "dropdown"].includes(q.type)) { nq.options = q.options; nq.allowOther = q.allowOther; }
      E.questions[qi] = nq;
      const valid = CHOICE.includes(nq.type) ? choicesOf(nq) : null; let c = 0;
      E.questions.forEach(x => { if (x.showIf && x.showIf.qid === q.id) { if (!valid) { delete x.showIf; c++; } else x.showIf.values = (x.showIf.values || []).filter(v => valid.includes(v)); } });
      if (c) toast(`${c} პირობით კითხვას პირობა მოეხსნა`); markDirty(); rerenderEditor(); return;
    }
    if (f === "allowOther") { q.allowOther = t.checked; if (!t.checked) E.questions.forEach(x => { if (x.showIf && x.showIf.qid === q.id) x.showIf.values = (x.showIf.values || []).filter(v => v !== OTHER); }); markDirty(); rerenderEditor(); return; }
    if (f === "maxSelect" || f === "scaleMax") { q[f] = Number(t.value); markDirty(); return; }
    q[f] = t.type === "checkbox" ? t.checked : t.value; markDirty(); return;
  }
  if (t.dataset.opt !== undefined) {
    const q = E.questions[qi], k = Number(t.dataset.opt), old = q.options[k];
    q.options[k] = t.value;
    E.questions.forEach(x => { if (x.showIf && x.showIf.qid === q.id) x.showIf.values = (x.showIf.values || []).map(v => v === old ? t.value : v); });
    document.querySelectorAll(`[data-act="follow"][data-qi="${qi}"]`)[k]?.setAttribute("data-val", t.value);
    if (e.type === "change") rerenderEditor(); markDirty(); return;
  }
  if (t.dataset.condSrc !== undefined) { if (e.type !== "change") return; E.questions[qi].showIf = { qid: t.value, values: [] }; markDirty(); rerenderEditor(); return; }
  if (t.dataset.condVal !== undefined) { const c = E.questions[qi].showIf, set = new Set(c.values || []); if (t.checked) set.add(t.value); else set.delete(t.value); c.values = [...set]; markDirty(); rerenderEditor(); }
}
app.addEventListener("input", e => { if (e.target.matches("input[type=text], input:not([type]), input[type=email], input[type=number], textarea")) onField(e); });
app.addEventListener("change", e => { if (e.target.matches("input[type=checkbox], input[type=radio], select") || e.target.dataset.opt !== undefined) onField(e); });
app.addEventListener("keydown", e => { if (e.key !== "Enter") return; const id = e.target.id; const map = { loginEmail: "sendLink", confirmEmail: "finishLink", invEmail: "invite" }; if (map[id]) { e.preventDefault(); document.querySelector(`[data-act="${map[id]}"]`)?.click(); } });

async function setStatus(id, status) { try { await updateDoc(doc(S.db, "surveys", id), { status, updatedAt: Date.now() }); toast(status === "active" ? "კვლევა გააქტიურდა" : "კვლევა დაიხურა"); } catch (e) { toast("სტატუსი ვერ შეიცვალა"); } }
async function duplicate(id) {
  const s = S.surveys.find(x => x.id === id); if (!s) return;
  const c = clone(s); delete c.id; c.title = (c.title || "") + " (ასლი)"; c.status = "draft"; c.createdAt = Date.now(); c.updatedAt = Date.now();
  const map = {}; (c.questions || []).forEach(q => { map[q.id] = nid(); });
  c.questions = (c.questions || []).map(q => ({ ...q, id: map[q.id], ...(q.showIf ? { showIf: { ...q.showIf, qid: map[q.showIf.qid] || q.showIf.qid } } : {}) }));
  try { await setDoc(doc(S.db, "surveys", nid()), c); toast("ასლი შეიქმნა"); } catch (e) { toast("ასლი ვერ შეიქმნა"); }
}

/* ================= boot ================= */
async function completeLink(email) {
  S.authState = "loading"; render();
  try { await signInWithEmailLink(S.auth, email, location.href); S.linkPending = false; ls.del("kv_email"); history.replaceState(null, "", BASE_URL + "?admin"); }
  catch (e) { S.linkPending = false; history.replaceState(null, "", BASE_URL + "?admin"); S.authState = "signedout"; render(); toast(e.code === "auth/invalid-action-code" ? "ბმულს ვადა გაუვიდა ან უკვე გამოყენებულია — მოითხოვეთ ახალი" : "შესვლა ვერ მოხერხდა: " + (e.code || "")); }
}
function boot() {
  if (!FIREBASE_CONFIG.apiKey || !FIREBASE_CONFIG.projectId) { renderSetup(); return; }
  if (location.protocol === "file:") { S.error = "გვერდი გახსნილია კომპიუტერიდან (file://). ატვირთეთ ჰოსტინგზე და გახსენით https:// მისამართით."; render(); return; }
  try { const fb = initializeApp(FIREBASE_CONFIG); S.auth = getAuth(fb); S.db = getFirestore(fb); }
  catch (e) { S.error = "Firebase-ის კონფიგურაცია არასწორია."; render(); return; }
  document.title = S.adminMode ? "ადმინ პანელი — კვლევები" : "თანამშრომელთა კვლევები";
  render();
  if (S.adminMode) {
    if (isSignInWithEmailLink(S.auth, location.href)) {
      S.linkPending = true;
      const em = lc(params.get("email") || ls.get("kv_email") || "");
      if (em) completeLink(em); else { S.authState = "needEmail"; render(); }
    }
    onAuthStateChanged(S.auth, user => { if (S.linkPending && (!user || user.isAnonymous)) return; resolveRole(user); });
  } else {
    let started = false;
    onAuthStateChanged(S.auth, user => {
      if (!user) { signInAnonymously(S.auth).catch(e => { S.error = "კავშირი ვერ დამყარდა (" + (e.code || "") + "). შეამოწმეთ, რომ Anonymous შესვლა ჩართულია."; render(); }); return; }
      S.fbUser = user;
      if (started) return; started = true;
      onSnapshot(query(collection(S.db, "surveys"), where("status", "==", "active")), snap => {
        S.surveys = snap.docs.map(d => ({ id: d.id, ...d.data() })).sort((a, b) => (b.updatedAt || 0) - (a.updatedAt || 0));
        S.surveysReady = true; softRender();
      }, e => { S.error = "კვლევების ჩატვირთვა ვერ მოხერხდა (" + (e.code || "") + ")."; render(); });
    });
  }
}
boot();

</script>
</body>
</html>

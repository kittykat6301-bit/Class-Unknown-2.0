<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#070b11">
<title>Class Unknown Character Database</title>
<link id="fav" rel="icon">
<style>
:root{--bg:#03070d;--panel:#07111b;--panel2:#0b1724;--line:#244a70;--line2:#5fb8ff;--text:#f1f8ff;--muted:#8ea9c3;--a:#8fe7ff;--b:#a79dff;--c:#9ef5cb;--gap:16px;--font-size:16px}
*{box-sizing:border-box}html{font-size:var(--font-size);min-height:100%}body{min-height:100%;margin:0;color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,sans-serif;font-size:1rem;line-height:1.4;background:radial-gradient(circle at 50% -10%,rgba(87,171,255,.16),transparent 32%),radial-gradient(circle at 50% 115%,rgba(123,71,255,.09),transparent 24%),linear-gradient(180deg,#03070d 0%,#050a11 45%,#03070d 100%);overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(circle at 50% 50%,rgba(77,159,255,.06),transparent 40%),repeating-linear-gradient(180deg,rgba(170,220,255,.022) 0 1px,transparent 1px 4px)}
body:after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background-image:linear-gradient(rgba(108,188,255,.05) 1px,transparent 1px),linear-gradient(90deg,rgba(108,188,255,.04) 1px,transparent 1px);background-size:44px 44px;mask-image:linear-gradient(to bottom,rgba(0,0,0,.55),transparent 88%)}
button,input,textarea,select{font:inherit}button{color:var(--text);background:linear-gradient(180deg,rgba(10,23,36,.94),rgba(6,13,21,.96));border:1px solid color-mix(in srgb,var(--line2) 30%,var(--line));border-radius:6px;padding:.72rem .88rem;cursor:pointer;box-shadow:inset 0 0 0 1px rgba(255,255,255,.03),0 0 0 1px rgba(95,184,255,.03)}button:hover{border-color:color-mix(in srgb,var(--a) 78%,white 10%);box-shadow:0 0 0 1px rgba(143,231,255,.1),0 0 18px rgba(88,170,255,.12),inset 0 0 0 1px rgba(255,255,255,.04)}button:active{transform:translateY(1px)}
input,textarea,select{width:100%;color:var(--text);background:rgba(4,10,16,.9);border:1px solid color-mix(in srgb,var(--line2) 22%,var(--line));border-radius:4px;padding:.72rem;outline:none;box-shadow:inset 0 0 18px rgba(67,137,255,.04)}input:focus,textarea:focus,select:focus{border-color:var(--a);box-shadow:0 0 0 1px rgba(143,231,255,.2),0 0 14px rgba(77,171,255,.18),inset 0 0 18px rgba(67,137,255,.06)}textarea{min-height:100px;resize:vertical}label{display:block;color:var(--muted);font:700 .68rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;text-transform:uppercase;letter-spacing:.13em;margin-bottom:7px}
.app{display:grid;grid-template-columns:280px 1fr;min-height:100vh}aside{height:100vh;position:sticky;top:0;overflow:auto;padding:18px;border-right:1px solid rgba(106,178,255,.18);background:linear-gradient(180deg,rgba(4,9,15,.94),rgba(3,8,14,.86));backdrop-filter:blur(10px);box-shadow:inset -1px 0 0 rgba(126,223,255,.08),0 0 55px rgba(62,134,255,.08)}main{padding:16px 24px 30px;min-width:0;display:flex;flex-direction:column}.brand{display:flex;gap:11px;align-items:center;margin-bottom:18px}.brand img{width:46px;height:46px;border-radius:12px;box-shadow:0 0 26px rgba(128,230,255,.25),0 0 40px rgba(140,88,255,.12)}.brand h1{font-size:.98rem;margin:0;letter-spacing:.14em;font-weight:800}.brand small,.muted{color:var(--muted)}.row{display:flex;gap:8px;flex-wrap:wrap}.row>*{flex:1}#search{margin:10px 0 12px}#charList{display:grid;gap:7px}.char{text-align:left;background:rgba(6,13,21,.55);border-color:rgba(107,171,255,.1)}.char.active{border-color:var(--a);background:linear-gradient(90deg,rgba(76,170,255,.12),rgba(3,13,22,.82));box-shadow:inset 2px 0 0 var(--a),0 0 18px rgba(79,180,255,.1)}.char b,.char small{display:block}.char small{color:var(--muted)}.sidefoot{margin-top:16px;padding-top:14px;border-top:1px solid rgba(106,178,255,.14);display:grid;gap:8px}.danger{color:#ffdce4;border-color:#763e54;background:linear-gradient(180deg,rgba(45,17,28,.92),rgba(28,10,18,.95))}
.systembar{margin:0 auto 16px;max-width:1180px;width:100%;padding:8px 12px;display:flex;justify-content:space-between;gap:12px;align-items:center;border:1px solid rgba(115,188,255,.2);border-radius:6px;background:linear-gradient(180deg,rgba(7,15,23,.88),rgba(3,8,14,.92));color:var(--muted);font:700 .62rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.14em;text-transform:uppercase;box-shadow:inset 0 0 0 1px rgba(255,255,255,.02),0 0 28px rgba(62,134,255,.08)}#systemPersonalization{color:var(--a);text-align:center}.online{color:var(--c)}.mobile{display:none}
.empty{max-width:1180px;width:100%;margin:0 auto;min-height:68vh;display:grid;place-items:center;text-align:center;color:var(--muted);border:1px solid rgba(109,183,255,.22);border-radius:8px;background:linear-gradient(180deg,rgba(6,13,21,.78),rgba(5,9,15,.92));position:relative;overflow:hidden;box-shadow:0 0 40px rgba(44,110,255,.08),inset 0 0 0 1px rgba(255,255,255,.03)}.empty:before{content:"";position:absolute;inset:14px;border:1px solid rgba(114,195,255,.12);pointer-events:none}
#editor{max-width:1180px;width:100%;margin:0 auto;padding:26px 24px 24px;position:relative;border:1px solid rgba(109,183,255,.22);border-radius:8px;background:linear-gradient(180deg,rgba(5,11,18,.86),rgba(4,9,15,.95));box-shadow:0 0 45px rgba(45,110,255,.12),inset 0 0 0 1px rgba(255,255,255,.02);overflow:hidden}
#editor:before{content:"";position:absolute;inset:12px;border:1px solid rgba(116,197,255,.15);pointer-events:none}
#editor:after{content:"";position:absolute;inset:0;pointer-events:none;background:radial-gradient(circle at 15% 10%,rgba(137,224,255,.08),transparent 22%),radial-gradient(circle at 85% 12%,rgba(125,115,255,.06),transparent 16%),linear-gradient(180deg,rgba(255,255,255,.03),transparent 16%)}
.editor-corners{display:none}
.top,.tabs,.sheet{position:relative;z-index:1}.top{display:flex;justify-content:space-between;gap:16px;align-items:flex-start;margin-bottom:18px;padding:0 0 12px;border-bottom:1px solid rgba(106,178,255,.14)}.top h2{margin:0;font:800 1.55rem/1.15 Inter,system-ui,sans-serif;letter-spacing:.04em;text-shadow:0 0 14px rgba(136,224,255,.12)}.top p{margin:.35rem 0 0;color:var(--muted);max-width:55ch}.record-actions{display:flex;gap:8px;align-items:center;justify-content:flex-end;flex-wrap:wrap}#save{color:var(--c);font-size:.76rem;font-family:ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.07em;text-transform:uppercase}#recordAction{min-width:142px}
.mode-pill{display:inline-flex;align-items:center;gap:6px;padding:4px 8px;border:1px solid rgba(106,178,255,.18);border-radius:999px;color:var(--muted);font:700 .56rem/1 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em;text-transform:uppercase;background:rgba(4,10,16,.55)}.mode-pill:before{content:"●";color:var(--c)}#editor.edit-mode .mode-pill:before{color:var(--b)}
.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}.tabs button{font:700 .72rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.08em;padding:.68rem .8rem;text-transform:uppercase}.tabs button.active{border-color:var(--a);background:linear-gradient(180deg,rgba(18,44,67,.95),rgba(7,15,24,.96));box-shadow:inset 0 0 0 1px rgba(143,231,255,.08),0 0 22px rgba(88,170,255,.14)}
.sheet{display:none}.sheet.active{display:block;animation:sheet .22s ease}@keyframes sheet{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}.grid{display:grid;grid-template-columns:repeat(12,1fr);gap:var(--gap)}.card{grid-column:span 6;padding:16px;border:1px solid rgba(105,177,255,.18);border-radius:6px;background:linear-gradient(180deg,rgba(9,17,27,.92),rgba(5,10,16,.96));box-shadow:0 0 26px rgba(40,99,227,.08),inset 0 0 0 1px rgba(255,255,255,.02);position:relative;overflow:hidden}.card.full{grid-column:1/-1}.card:before{content:"";position:absolute;left:0;right:0;top:0;height:2px;background:linear-gradient(90deg,transparent,rgba(143,231,255,.42),transparent);opacity:.55}.card h3{margin:0 0 12px;color:var(--a);font:750 .76rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.16em;text-transform:uppercase}.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.field.full{grid-column:1/-1}
#editor.view-mode input,#editor.view-mode textarea{border-color:transparent;background:transparent;box-shadow:none;padding-left:0;padding-right:0;color:var(--text);cursor:text}#editor.view-mode textarea{resize:none;overflow:hidden}#editor.view-mode .field{padding:10px 12px;border:1px solid rgba(106,178,255,.12);border-radius:4px;background:linear-gradient(180deg,rgba(4,10,16,.36),rgba(4,10,16,.18))}#editor.view-mode label{color:color-mix(in srgb,var(--a) 72%,var(--muted))}#editor.edit-mode .card{box-shadow:0 0 26px rgba(95,115,255,.08),inset 0 0 0 1px rgba(255,255,255,.02)}
.modal{position:fixed;inset:0;display:none;place-items:center;padding:18px;background:rgba(0,0,0,.7);backdrop-filter:blur(10px);z-index:50}.modal.open{display:grid}.panel{width:min(900px,100%);max-height:90vh;overflow:auto;padding:18px;border:1px solid rgba(109,183,255,.24);border-radius:10px;background:linear-gradient(180deg,rgba(6,13,21,.97),rgba(4,9,15,.98));box-shadow:0 30px 80px rgba(0,0,0,.55),0 0 38px rgba(44,110,255,.12)}.panelhead{display:flex;justify-content:space-between;gap:12px;align-items:center}.panel h2{margin:0}.note{margin:12px 0;padding:10px 12px;border:1px solid rgba(106,178,255,.16);border-radius:6px;background:rgba(5,11,18,.7);color:var(--muted);font-size:.78rem}.note b{color:var(--a)}
.themegrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(145px,1fr));gap:10px;margin:12px 0 18px}.theme{position:relative;min-height:108px;text-align:left;padding:12px;overflow:hidden;background:linear-gradient(145deg,rgba(10,20,31,.96),rgba(4,9,15,.98));border-radius:6px}.theme:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 90% 10%,color-mix(in srgb,var(--s2) 30%,transparent),transparent 48%),linear-gradient(135deg,color-mix(in srgb,var(--s1) 11%,transparent),transparent 60%);pointer-events:none}.theme.active{border-color:var(--s1);box-shadow:0 0 0 1px color-mix(in srgb,var(--s1) 55%,transparent),0 0 18px color-mix(in srgb,var(--s1) 16%,transparent)}.theme.active:after{content:"ACTIVE";position:absolute;right:8px;bottom:7px;color:var(--s1);font:700 .54rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em}.glyph{position:relative;display:grid;place-items:center;width:34px;height:34px;margin-bottom:8px;border:1px solid color-mix(in srgb,var(--s1) 65%,transparent);border-radius:8px;color:var(--s1);background:color-mix(in srgb,var(--s1) 7%,transparent);font-size:1.15rem}.tname{position:relative;display:block;font-weight:800}.tdesc{position:relative;display:block;margin-top:3px;color:var(--muted);font-size:.68rem}.setting{display:grid;grid-template-columns:1fr minmax(180px,260px);gap:12px;align-items:center;padding:11px 0;border-top:1px solid rgba(106,178,255,.13)}.setting small{display:block;color:var(--muted)}.toggle{display:flex;justify-content:flex-end;gap:8px;align-items:center}.toggle input{width:20px;height:20px}
.burst{position:fixed;pointer-events:none;z-index:100;font-size:22px;font-weight:900;animation:burst .6s ease-out forwards;text-shadow:0 0 16px currentColor}@keyframes burst{0%{opacity:0;transform:translate(-50%,-20%) scale(.6)}20%{opacity:1}100%{opacity:0;transform:translate(-50%,-100%) scale(1.35)}}html[data-reduce="1"] *{animation:none!important;transition:none!important}
@media(max-width:900px){.app{grid-template-columns:1fr}aside{position:fixed;z-index:40;left:0;top:0;bottom:0;width:min(86vw,320px);transform:translateX(-105%);transition:.2s}aside.open{transform:none}main{padding:14px}.mobile{display:flex;gap:8px;margin-bottom:12px}.systembar{font-size:.58rem;flex-wrap:wrap}.systembar #systemPersonalization{order:3;width:100%;text-align:left}#editor,.empty{max-width:none}.card{grid-column:1/-1}}
@media(max-width:560px){.fields,.setting{grid-template-columns:1fr}.top{flex-direction:column}.tabs{display:grid}.record-actions{justify-content:flex-start}}
</style>
</head><body>
<div class="app">
<aside id="side">
<div class="brand"><img id="logo" alt="Class Unknown"><div><h1>CLASS UNKNOWN</h1><small>Character Database</small></div></div>
<div class="row"><button id="new">＋ New</button><button id="dup">Duplicate</button></div>
<input id="search" placeholder="Search characters…">
<div id="charList"></div>
<div class="sidefoot">
<button id="exp">Export current JSON</button>
<button id="expAll">Export all JSON</button>
<button id="imp">Import JSON</button><input id="file" type="file" accept=".json,application/json" hidden>
<button id="settings">⚙ Personalization</button>
<button id="del" class="danger">Delete current</button>
<small id="storageNote" class="muted">Autosaves in this browser.</small>
</div>
</aside>

<main>
<div class="systembar"><span>◈ CLASS UNKNOWN // SYSTEM ARCHIVE</span><span id="systemPersonalization">PERSONALIZATION: VAL ALIENCORE</span><span class="online">● LINK STABLE</span></div>
<div class="mobile"><button id="menu">☰ Characters</button><button id="msettings">⚙ Personalization</button></div>

<div id="empty" class="empty"><div><b>No archive file selected.</b><br>Create a new record or import a saved profile.</div></div>

<div id="editor" hidden>
<div class="top">
<div><h2 id="title">Untitled Character</h2><p>Live archive panel synchronized across Hunter, Authority and Personal layers.</p></div>
<div class="record-actions">
<span id="modePill" class="mode-pill">VIEW MODE</span>
<span id="save">Saved</span>
<button id="recordAction">ENTER EDIT MODE</button>
</div>
</div>
<div class="systembar" style="margin:0 0 16px;max-width:none"><span>MODULE // HUNTER STATUS</span><span>ARCHIVE STATE // <span id="archiveStateLabel">LOCKED</span></span><span class="online">● PANEL STABLE</span></div>
<div class="tabs">
<button class="active" data-tab="system">01 // SYSTEM / HUNTER</button>
<button data-tab="authority">02 // AUTHORITY / BODY SCAN</button>
<button data-tab="personal">03 // PERSONAL PROFILE</button>
</div>
<section id="system" class="sheet active"><div class="grid"></div></section>
<section id="authority" class="sheet"><div class="grid"></div></section>
<section id="personal" class="sheet"><div class="grid"></div></section>
</div>
</main>
</div>

<div id="modal" class="modal"><div class="panel">
<div class="panelhead"><div><h2>Archive Personalization</h2><small class="muted">A Class Unknown system shell inspired by in-world holographic panels. Personalizations only change the cosmetic overlay.</small></div><button id="close">✕</button></div>
<div class="note"><b>SYSTEM CORE:</b> fixed holographic shell, navigation, archive modules and record behavior. Personalizations change accent colors, glyphs, visual effects and audio.</div>
<div id="themeGrid" class="themegrid"></div>
<div class="setting"><div><b>Sound effects</b><small>Personalization-matched system tones.</small></div><label class="toggle"><input id="sound" type="checkbox"><span>Enabled</span></label></div>
<div class="setting"><div><b>Volume</b></div><input id="volume" type="range" min="0" max="100"></div>
<div class="setting"><div><b>Visual effects</b></div><select id="fx"><option value="off">Off</option><option value="low">Low</option><option value="full">Full</option></select></div>
<div class="setting"><div><b>UI density</b></div><select id="density"><option value="compact">Compact</option><option value="normal">Comfortable</option><option value="spacious">Spacious</option></select></div>
<div class="setting"><div><b>Text size</b></div><select id="font"><option value="14">Small</option><option value="16">Default</option><option value="18">Large</option><option value="20">Extra large</option></select></div>
<div class="setting"><div><b>Reduce motion</b></div><label class="toggle"><input id="reduce" type="checkbox"><span>Reduce</span></label></div>
<div class="row" style="margin-top:16px"><button id="reset">Reset overlay</button><button id="done">Done</button></div>
</div></div><script>
const ICON="data:image/webp;base64,"+
"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";

const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
$("#logo").src=ICON;
$("#fav").href=ICON;

const SK="classUnknownDB";
const SETK="classUnknownSettings";
const mem=new Map();

const getStore=k=>{
  try{return localStorage.getItem(k)}
  catch{return mem.get(k)||null}
};

const setStore=(k,v)=>{
  try{
    localStorage.setItem(k,v);
    return true;
  }catch{
    mem.set(k,v);
    return false;
  }
};

const THEMES={
system:["Archive Blue","#7feaff","#8aa8c7","#9ef1c4","◇",520,"Neutral archive shell"],
authority:["Authority","#8fc8ff","#628fbd","#83e1b3","▣",460,"Authority oversight skin"],
crimson:["Crimson","#ff9eb2","#c8738b","#f4ce7a","✧",560,"Combat alert skin"],
holo:["Holographic","#bfeaff","#d9c7ff","#e7ffd6","◌",500,"Luminous archive skin"],
cyber:["Cyber Cute","#ff9cc8","#7fe9ff","#ffe57b","♥",880,"Pixel hearts + pastel"],
alien:["Val Aliencore","#86f3ef","#ffabc9","#aef7d7","👽",760,"Val archive skin"],
kang:["Kang / Abyssal","#9d8cff","#65718f","#d7be7a","◆",360,"Kang archive skin"],
slimes:["Roswell + Kepler","#ff9fc9","#6fa9ff","#9be8d0","●",620,"Roswell + Kepler skin"],
matriarch:["Matriarch","#b5f0dc","#d8c6ff","#efd58d","❋",540,"Matriarch resonance skin"],
sanctuary:["Sanctuary","#86ece9","#83c8ff","#9fe6b9","❈",500,"Sanctuary glass skin"],
glitch:["Glitched","#62efff","#ff5db1","#8ff7c3","▥",420,"Corrupted archive skin"]
};

const DEF={
  theme:"alien",
  sound:true,
  volume:32,
  fx:"full",
  density:"normal",
  font:"16",
  reduce:false
};

let settings={
  ...DEF,
  ...JSON.parse(getStore(SETK)||"{}")
};

if(settings.theme==="abyss")settings.theme="kang";
if(settings.theme==="dragon")settings.theme="kang";
if(settings.theme==="valentine")settings.theme="alien";
if(settings.theme==="light")settings.theme="holo";
if(settings.theme==="cybercute")settings.theme="cyber";
if(settings.theme==="roswellkepler")settings.theme="slimes";
if(settings.theme==="glitched")settings.theme="glitch";

if([".9","1","1.1","1.2"].includes(String(settings.font))){
  settings.font={
    ".9":"14",
    "1":"16",
    "1.1":"18",
    "1.2":"20"
  }[String(settings.font)];
}

let db=(()=>{
  try{
    return JSON.parse(
      getStore(SK)||
      '{"characters":[],"activeId":null}'
    )
  }catch{
    return{
      characters:[],
      activeId:null
    }
  }
})();

let active=db.activeId;
let audio=null;
let editMode=false;const FORMS={
system:[
["Hunter Identification",[["Name","identity.name"],["Alias / Codename","identity.alias"],["Age","identity.age"],["Pronouns","identity.pronouns"],["Rank","hunter.rank"],["Class","hunter.class"],["Level","hunter.level"],["Affiliation","hunter.affiliation"]]],
["Core Stats",[["Strength","stats.strength"],["Agility","stats.agility"],["Endurance","stats.endurance"],["Mana","stats.mana"],["Perception","stats.perception"],["Control","stats.control"]]],
["System Classification",[["Type","hunter.type"],["Lineage","hunter.lineage"],["System Notes","hunter.systemNotes","ta"]]],
["Abilities",[["Skills / Authorities","hunter.abilities","ta"]]],
["Equipment",[["Primary Weapon","gear.primaryWeapon"],["Secondary Weapon","gear.secondaryWeapon"],["Armor / Raid Gear","gear.armor","ta"],["Artifacts / Inventory","gear.artifacts","ta"]]]
],
authority:[
["Government Record",[["Registered Name","authority.registeredName"],["Hunter ID","authority.hunterId"],["Nationality","authority.nationality"],["Registration Status","authority.registrationStatus"],["Threat / Watch Status","authority.watchStatus"],["Clearance","authority.clearance"]]],
["Body Scan",[["Height","appearance.height"],["Build","appearance.build"],["Hair","appearance.hair"],["Eyes","appearance.eyes"],["Skin","appearance.skin"],["Distinguishing Features","appearance.features"]]],
["Medical / Mana Scan",[["Mana Signature","authority.manaSignature"],["Scan Reliability","authority.scanReliability"],["Physiological Notes","authority.physiology","ta"]]],
["Authority Notes",[["Restrictions, anomalies, provenance, incident notes, classification warnings","authority.notes","ta"]]]
],
personal:[
["Personality",[["Core Traits","personal.personality","ta"]]],
["Preferences",[["Likes","personal.likes","ta"],["Dislikes","personal.dislikes","ta"]]],
["Habits & Social",[["Habits / Mannerisms","personal.habits","ta"],["Relationships / Social Notes","personal.relationships","ta"]]],
["Voice & Presentation",[["Voice / Accent / Speech","personal.voice","ta"],["Style / Fashion","personal.style","ta"]]],
["Private System Profile",[["Additional Notes","personal.notes","ta"]]]
]};

function blank(){
  return{
    id:crypto.randomUUID
      ?crypto.randomUUID()
      :"c"+Date.now(),

    createdAt:new Date().toISOString(),
    updatedAt:new Date().toISOString(),

    identity:{
      name:"",
      alias:"",
      age:"",
      pronouns:""
    },

    hunter:{
      rank:"",
      class:"",
      level:"",
      affiliation:"",
      type:"",
      lineage:"",
      systemNotes:"",
      abilities:""
    },

    stats:{
      strength:"",
      agility:"",
      endurance:"",
      mana:"",
      perception:"",
      control:""
    },

    gear:{
      primaryWeapon:"",
      secondaryWeapon:"",
      armor:"",
      artifacts:""
    },

    authority:{
      registeredName:"",
      hunterId:"",
      nationality:"",
      registrationStatus:"",
      watchStatus:"",
      clearance:"",
      manaSignature:"",
      scanReliability:"",
      physiology:"",
      notes:""
    },

    appearance:{
      height:"",
      build:"",
      hair:"",
      eyes:"",
      skin:"",
      features:""
    },

    personal:{
      personality:"",
      likes:"",
      dislikes:"",
      habits:"",
      relationships:"",
      voice:"",
      style:"",
      notes:""
    }
  }
}

const read=(o,p)=>
  p.split(".")
   .reduce((a,k)=>a?.[k],o)??"";

const write=(o,p,v)=>{
  const a=p.split(".");
  const last=a.pop();
  let x=o;

  for(const k of a){
    x=x[k]??={};
  }

  x[last]=v;
};

const current=()=>
  db.characters.find(
    c=>c.id===active
  )||null;

function buildForms(){

  for(
    const [sid,groups]
    of Object.entries(FORMS)
  ){

    const grid=
      $("#"+sid+" .grid");

    for(
      const [title,fields]
      of groups
    ){

      const card=
        document.createElement("div");

      card.className=
        "card"+
        (
          fields.length===1
          ?" full"
          :""
        );

      card.innerHTML=
        `<h3>${title}</h3>
         <div class="fields"></div>`;

      const box=
        $(".fields",card);

      for(
        const [label,path,type]
        of fields
      ){

        const field=
          document.createElement("div");

        field.className=
          "field"+
          (
            type==="ta"
            ?" full"
            :""
          );

        field.innerHTML=
          `<label>${label}</label>${
            type==="ta"
            ?`<textarea data-path="${path}"></textarea>`
            :`<input data-path="${path}">`
          }`;

        box.appendChild(field);
      }

      grid.appendChild(card);
    }
  }
}

function saveDB(message){

  db.activeId=active;

  const ok=
    setStore(
      SK,
      JSON.stringify(db)
    );

  if($("#save")){
    $("#save").textContent=
      message||
      (
        editMode
        ?"Draft autosaved"
        :"Saved & locked"
      );
  }

  $("#storageNote").textContent=
    ok
    ?"Autosaves in this browser."
    :"Storage blocked. Export JSON before closing.";

  return ok;
}

function applyPersonalization(){

  const t=
    THEMES[settings.theme]||
    THEMES.system;

  const r=
    document.documentElement;

  r.style.setProperty(
    "--a",
    t[1]
  );

  r.style.setProperty(
    "--b",
    t[2]
  );

  r.style.setProperty(
    "--c",
    t[3]
  );

  r.style.setProperty(
    "--gap",
    settings.density==="compact"
      ?"10px"
      :settings.density==="spacious"
      ?"20px"
      :"16px"
  );

  r.style.setProperty(
    "--font-size",
    (settings.font||"16")+"px"
  );

  r.dataset.reduce=
    settings.reduce
    ?"1"
    :"0";

  $("#systemPersonalization")
    .textContent=
      "PERSONALIZATION: "+
      t[0].toUpperCase();

  $$(".theme").forEach(
    b=>
      b.classList.toggle(
        "active",
        b.dataset.theme===
        settings.theme
      )
  );

  $("#sound").checked=
    settings.sound;

  $("#volume").value=
    settings.volume;

  $("#fx").value=
    settings.fx;

  $("#density").value=
    settings.density;

  $("#font").value=
    String(settings.font);

  $("#reduce").checked=
    settings.reduce;
}

function saveSettings(){

  setStore(
    SETK,
    JSON.stringify(settings)
  );

  applyPersonalization();
}

function renderThemes(){

  const g=
    $("#themeGrid");

  g.innerHTML="";

  for(
    const [key,t]
    of Object.entries(THEMES)
  ){

    const b=
      document.createElement("button");

    b.className="theme";
    b.dataset.theme=key;

    b.style.setProperty(
      "--s1",
      t[1]
    );

    b.style.setProperty(
      "--s2",
      t[2]
    );

    b.innerHTML=
      `<span class="glyph">${t[4]}</span>
       <span class="tname">${t[0]}</span>
       <span class="tdesc">${t[6]}</span>`;

    b.onclick=()=>{

      settings.theme=key;

      saveSettings();

      tone("page");
    };

    g.appendChild(b);
  }
}function renderList(){

  const q=
    $("#search")
    .value
    .toLowerCase();

  const g=
    $("#charList");

  g.innerHTML="";

  const chars=
    db.characters.filter(
      c=>
        (
          (c.identity?.name||"")
          +" "+
          (c.identity?.alias||"")
        )
        .toLowerCase()
        .includes(q)
    );

  for(const c of chars){

    const b=
      document.createElement("button");

    b.className=
      "char"+
      (
        c.id===active
        ?" active"
        :""
      );

    const meta=[
      c.hunter?.rank
      &&
      c.hunter.rank+" Rank",

      c.hunter?.class
    ]
    .filter(Boolean)
    .join(" · ");

    b.innerHTML=
      `<b>${
        c.identity?.name||
        "Untitled Character"
      }</b>
      <small>${
        meta||
        "No class data"
      }</small>`;

    b.onclick=()=>{

      active=c.id;
      editMode=false;

      saveDB(
        "Saved & locked"
      );

      render();

      $("#side")
        .classList
        .remove("open");
    };

    g.appendChild(b);
  }

  if(!g.children.length){

    g.innerHTML=
      '<small class="muted">No characters yet.</small>';
  }
}

function sizeReadouts(){

  $$("#editor.view-mode textarea")
    .forEach(e=>{

      e.style.height="auto";

      e.style.height=
        Math.max(
          42,
          e.scrollHeight
        )+"px";
    });
}

function applyRecordMode(){

  const editor=
    $("#editor");

  if(!editor)return;

  editor.classList.toggle(
    "edit-mode",
    editMode
  );

  editor.classList.toggle(
    "view-mode",
    !editMode
  );

  $$("[data-path]")
    .forEach(e=>{

      e.readOnly=
        !editMode;

      e.tabIndex=
        editMode
        ?0
        :-1;
    });

  $("#recordAction")
    .textContent=
      editMode
      ?"SAVE & LOCK"
      :"ENTER EDIT MODE";

  $("#modePill")
    .textContent=
      editMode
      ?"EDIT MODE"
      :"VIEW MODE";

  if($("#archiveStateLabel")){

    $("#archiveStateLabel")
      .textContent=
        editMode
        ?"EDITING"
        :"LOCKED";
  }

  if(!editMode){
    sizeReadouts();
  }
}

function renderEditor(){

  const c=current();

  $("#empty").hidden=
    !!c;

  $("#editor").hidden=
    !c;

  if(!c)return;

  $("#title").textContent=
    c.identity?.name||
    "Untitled Character";

  $$("[data-path]")
    .forEach(
      e=>
        e.value=
          read(
            c,
            e.dataset.path
          )
    );

  applyRecordMode();
}

function render(){
  renderList();
  renderEditor();
}

function tone(
  kind="click"
){

  if(!settings.sound)return;

  const A=
    window.AudioContext||
    window.webkitAudioContext;

  if(!A)return;

  audio??=
    new A();

  if(
    audio.state===
    "suspended"
  ){

    audio
      .resume()
      .catch(()=>{});
  }

  const t=
    THEMES[settings.theme]||
    THEMES.system;

  const o=
    audio.createOscillator();

  const g=
    audio.createGain();

  const n=
    audio.currentTime;

  o.type=
    settings.theme==="glitch"
    ?"square"
    :settings.theme==="kang"
    ?"sawtooth"
    :"triangle";

  o.frequency.value=
    kind==="page"
    ?t[5]*1.45
    :t[5];

  g.gain.setValueAtTime(
    .0001,
    n
  );

  g.gain
    .exponentialRampToValueAtTime(
      Math.max(
        .0008,
        settings.volume/100*.08
      ),
      n+.01
    );

  g.gain
    .exponentialRampToValueAtTime(
      .0001,
      n+.15
    );

  o.connect(g);

  g.connect(
    audio.destination
  );

  o.start(n);

  o.stop(
    n+.17
  );
}

function burst(x,y){

  if(
    settings.reduce||
    settings.fx==="off"
  )return;

  const t=
    THEMES[settings.theme]||
    THEMES.system;

  const e=
    document.createElement("div");

  e.className=
    "burst";

  e.textContent=
    t[4];

  e.style.left=
    x+"px";

  e.style.top=
    y+"px";

  e.style.color=
    t[1];

  document.body
    .appendChild(e);

  setTimeout(
    ()=>e.remove(),
    650
  );
}

function download(
  data,
  name
){

  const u=
    URL.createObjectURL(
      new Blob(
        [
          JSON.stringify(
            data,
            null,
            2
          )
        ],
        {
          type:"application/json"
        }
      )
    );

  const a=
    document.createElement("a");

  a.href=u;
  a.download=name;

  a.click();

  setTimeout(
    ()=>
      URL.revokeObjectURL(u),
    500
  );
}

buildForms();
renderThemes();
applyPersonalization();

$$("[data-path]")
.forEach(e=>{

  e.oninput=()=>{

    if(!editMode)return;

    const c=current();

    if(!c)return;

    write(
      c,
      e.dataset.path,
      e.value
    );

    c.updatedAt=
      new Date()
      .toISOString();

    if(
      e.dataset.path===
      "identity.name"
    ){

      $("#title")
        .textContent=
          e.value||
          "Untitled Character";
    }

    renderList();

    saveDB(
      "Draft autosaved"
    );
  };
});

$$(".tabs button")
.forEach(b=>{

  b.onclick=()=>{

    $$(".tabs button")
      .forEach(
        x=>
          x.classList
           .remove("active")
      );

    $$(".sheet")
      .forEach(
        x=>
          x.classList
           .remove("active")
      );

    b.classList
      .add("active");

    $("#"+b.dataset.tab)
      .classList
      .add("active");

    tone("page");
  };
});$("#new").onclick=()=>{

  const c=blank();

  db.characters.unshift(c);

  active=c.id;
  editMode=true;

  saveDB(
    "New draft"
  );

  render();

  $('[data-path="identity.name"]')
    .focus();
};

$("#dup").onclick=()=>{

  const c=current();

  if(!c)return;

  const n=
    JSON.parse(
      JSON.stringify(c)
    );

  n.id=
    crypto.randomUUID
    ?crypto.randomUUID()
    :"c"+Date.now();

  n.identity.name=
    (
      n.identity.name||
      "Untitled Character"
    )+
    " Copy";

  db.characters.unshift(n);

  active=n.id;
  editMode=true;

  saveDB(
    "Duplicate draft"
  );

  render();
};

$("#del").onclick=()=>{

  const c=current();

  if(
    c&&
    confirm(
      `Delete "${
        c.identity?.name||
        "Untitled Character"
      }"?`
    )
  ){

    db.characters=
      db.characters.filter(
        x=>x.id!==c.id
      );

    active=
      db.characters[0]?.id||
      null;

    editMode=false;

    saveDB(
      "Saved & locked"
    );

    render();
  }
};

$("#exp").onclick=()=>{

  const c=current();

  if(c){

    download(
      c,
      (
        c.identity?.name||
        "character"
      )
      .replace(
        /[^\w-]+/g,
        "_"
      )
      +".json"
    );
  }
};

$("#expAll").onclick=()=>{

  download(
    {
      characters:
        db.characters
    },
    "class-unknown-character-database.json"
  );
};

$("#imp").onclick=()=>{

  $("#file").click();
};

$("#file").onchange=
async e=>{

  try{

    const p=
      JSON.parse(
        await e.target.files[0]
          .text()
      );

    const arr=
      Array.isArray(p)
      ?p
      :Array.isArray(
        p.characters
      )
      ?p.characters
      :[p];

    for(
      const x
      of arr
    ){

      if(!x.id){

        x.id=
          crypto.randomUUID
          ?crypto.randomUUID()
          :"c"+
           Date.now()+
           Math.random();
      }

      db.characters
        .unshift(x);
    }

    active=
      arr[0]?.id||
      active;

    editMode=false;

    saveDB(
      "Imported & locked"
    );

    render();

  }catch(err){

    alert(
      "Import failed: "+
      err.message
    );
  }

  e.target.value="";
};

$("#search").oninput=
  renderList;

$("#menu").onclick=()=>{

  $("#side")
    .classList
    .toggle("open");
};

$("#recordAction").onclick=()=>{

  if(!current())return;

  if(editMode){

    editMode=false;

    saveDB(
      "Saved & locked"
    );

    applyRecordMode();

    tone("page");

  }else{

    editMode=true;

    $("#save")
      .textContent=
        "Editing draft";

    applyRecordMode();

    tone("page");

    const first=
      $('[data-path="identity.name"]');

    if(first){
      first.focus();
    }
  }
};

const open=()=>{

  $("#modal")
    .classList
    .add("open");
};

const close=()=>{

  $("#modal")
    .classList
    .remove("open");
};

$("#settings").onclick=
  open;

$("#msettings").onclick=
  open;

$("#close").onclick=
  close;

$("#done").onclick=
  close;

$("#modal").onclick=e=>{

  if(
    e.target===
    $("#modal")
  ){

    close();
  }
};

$("#sound").onchange=e=>{

  settings.sound=
    e.target.checked;

  saveSettings();
};

$("#volume").oninput=e=>{

  settings.volume=
    +e.target.value;

  saveSettings();
};

$("#fx").onchange=e=>{

  settings.fx=
    e.target.value;

  saveSettings();
};

$("#density").onchange=e=>{

  settings.density=
    e.target.value;

  saveSettings();
};

$("#font").onchange=e=>{

  settings.font=
    e.target.value;

  saveSettings();
};

$("#reduce").onchange=e=>{

  settings.reduce=
    e.target.checked;

  saveSettings();
};

$("#reset").onclick=()=>{

  settings={
    ...DEF
  };

  saveSettings();
};

document.addEventListener(
  "click",
  e=>{

    const b=
      e.target.closest(
        "button"
      );

    if(!b)return;

    const r=
      b.getBoundingClientRect();

    burst(
      r.left+
      r.width/2,

      r.top+
      r.height/2
    );

    if(
      !b.closest(".tabs")&&
      !b.classList
        .contains("theme")
    ){

      tone(
        b.id==="del"
        ?"danger"
        :"click"
      );
    }
  }
);

if(
  active&&
  !current()
){

  active=
    db.characters[0]?.id||
    null;
}

editMode=false;

render();

saveDB(
  "Saved & locked"
);
</script>
</body>
</html>

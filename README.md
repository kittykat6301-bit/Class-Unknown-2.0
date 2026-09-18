<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#070b11">
<title>Class Unknown Character Database</title>
<link id="fav" rel="icon">
<style>
:root{--bg:#070b11;--panel:#0d141d;--panel2:#111c28;--line:#24364b;--text:#f4f8ff;--muted:#91a5bd;--a:#86f3ef;--b:#ffabc9;--c:#aef7d7;--gap:16px;--font-size:16px}
*{box-sizing:border-box}html{font-size:var(--font-size);min-height:100%}body{min-height:100%;margin:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,sans-serif;font-size:1rem;line-height:1.4;background-image:radial-gradient(circle at 15% 6%,color-mix(in srgb,var(--a) 9%,transparent),transparent 26rem),radial-gradient(circle at 90% 7%,color-mix(in srgb,var(--b) 8%,transparent),transparent 28rem)}
body:before{content:"";position:fixed;inset:0;pointer-events:none;z-index:999;background:repeating-linear-gradient(180deg,rgba(255,255,255,.015) 0 1px,transparent 1px 4px);opacity:.3}
button,input,textarea,select{font:inherit}button{color:var(--text);background:var(--panel2);border:1px solid var(--line);border-radius:10px;padding:.7rem .85rem;cursor:pointer}button:hover{border-color:var(--a)}input,textarea,select{width:100%;color:var(--text);background:#080d14;border:1px solid var(--line);border-radius:9px;padding:.7rem;outline:none}input:focus,textarea:focus,select:focus{border-color:var(--a);box-shadow:0 0 0 3px color-mix(in srgb,var(--a) 12%,transparent)}textarea{min-height:100px;resize:vertical}label{display:block;color:var(--muted);font-size:.72rem;text-transform:uppercase;letter-spacing:.08em;margin-bottom:5px}
.app{display:grid;grid-template-columns:290px 1fr;min-height:100vh}aside{height:100vh;position:sticky;top:0;overflow:auto;padding:18px;border-right:1px solid var(--line);background:rgba(4,8,13,.94);box-shadow:inset -1px 0 color-mix(in srgb,var(--a) 12%,transparent)}main{padding:18px 24px 24px;min-width:0}.brand{display:flex;gap:11px;align-items:center;margin-bottom:18px}.brand img{width:46px;height:46px;border-radius:14px;box-shadow:0 0 24px color-mix(in srgb,var(--a) 22%,transparent)}.brand h1{font-size:1rem;margin:0;letter-spacing:.08em}.brand small,.muted{color:var(--muted)}.row{display:flex;gap:8px;flex-wrap:wrap}.row>*{flex:1}#search{margin:10px 0}#charList{display:grid;gap:7px}.char{text-align:left;background:transparent;border-color:transparent}.char.active{border-color:var(--a);background:color-mix(in srgb,var(--a) 8%,transparent);box-shadow:inset 3px 0 0 var(--a)}.char b,.char small{display:block}.char small{color:var(--muted)}.sidefoot{margin-top:16px;padding-top:14px;border-top:1px solid var(--line);display:grid;gap:8px}.danger{color:#ffdce4;border-color:#6e3446;background:#27121b}
.systembar{margin:0 0 16px;padding:9px 11px;display:flex;justify-content:space-between;gap:12px;align-items:center;border:1px solid var(--line);border-radius:8px;background:#080d14;color:var(--muted);font:700 .66rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.11em;text-transform:uppercase;box-shadow:inset 3px 0 0 var(--a)}#systemPersonalization{color:var(--a);text-align:center}.online{color:var(--c)}.mobile{display:none}.empty{min-height:55vh;display:grid;place-items:center;text-align:center;color:var(--muted);border:1px dashed var(--line);border-radius:16px}.top{display:flex;justify-content:space-between;gap:16px;align-items:flex-start;margin-bottom:16px}.top h2{margin:0}.top p{margin:.3rem 0 0;color:var(--muted)}#save{color:var(--c);font-size:.8rem}.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:16px}.tabs button{font-family:ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.04em}.tabs button.active{border-color:var(--a);background:color-mix(in srgb,var(--a) 10%,#111c28);box-shadow:inset 3px 0 0 var(--a)}
.sheet{display:none}.sheet.active{display:block;animation:sheet .25s ease}@keyframes sheet{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}.grid{display:grid;grid-template-columns:repeat(12,1fr);gap:var(--gap)}.card{grid-column:span 6;padding:16px;border:1px solid var(--line);border-radius:12px;background:linear-gradient(180deg,#0d141d,#080d14);box-shadow:0 16px 38px rgba(0,0,0,.28),inset 3px 0 0 color-mix(in srgb,var(--a) 20%,transparent)}.card.full{grid-column:1/-1}.card h3{margin:0 0 12px;color:var(--a);font:750 .76rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em;text-transform:uppercase}.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.field.full{grid-column:1/-1}
.modal{position:fixed;inset:0;display:none;place-items:center;padding:18px;background:rgba(0,0,0,.68);backdrop-filter:blur(8px);z-index:50}.modal.open{display:grid}.panel{width:min(820px,100%);max-height:90vh;overflow:auto;padding:18px;border:1px solid var(--line);border-radius:18px;background:#0d141d;box-shadow:0 30px 80px rgba(0,0,0,.5)}.panelhead{display:flex;justify-content:space-between;gap:12px;align-items:center}.panel h2{margin:0}.note{margin:12px 0;padding:10px 12px;border:1px solid var(--line);border-radius:9px;background:#080d14;color:var(--muted);font-size:.78rem}.note b{color:var(--a)}
.themegrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(145px,1fr));gap:10px;margin:12px 0 18px}.theme{position:relative;min-height:108px;text-align:left;padding:12px;overflow:hidden;background:linear-gradient(145deg,#111c28,#080d14)}.theme:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 90% 10%,color-mix(in srgb,var(--s2) 30%,transparent),transparent 48%),linear-gradient(135deg,color-mix(in srgb,var(--s1) 9%,transparent),transparent 60%);pointer-events:none}.theme.active{border-color:var(--s1);box-shadow:0 0 0 2px color-mix(in srgb,var(--s1) 22%,transparent)}.theme.active:after{content:"ACTIVE";position:absolute;right:8px;bottom:7px;color:var(--s1);font:700 .54rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em}.glyph{position:relative;display:grid;place-items:center;width:34px;height:34px;margin-bottom:8px;border:1px solid color-mix(in srgb,var(--s1) 65%,transparent);border-radius:9px;color:var(--s1);background:color-mix(in srgb,var(--s1) 7%,transparent);font-size:1.15rem}.tname{position:relative;display:block;font-weight:800}.tdesc{position:relative;display:block;margin-top:3px;color:var(--muted);font-size:.68rem}.setting{display:grid;grid-template-columns:1fr minmax(180px,260px);gap:12px;align-items:center;padding:11px 0;border-top:1px solid var(--line)}.setting small{display:block;color:var(--muted)}.toggle{display:flex;justify-content:flex-end;gap:8px;align-items:center}.toggle input{width:20px;height:20px}
.burst{position:fixed;pointer-events:none;z-index:100;font-size:22px;font-weight:900;animation:burst .6s ease-out forwards;text-shadow:0 0 16px currentColor}@keyframes burst{0%{opacity:0;transform:translate(-50%,-20%) scale(.6)}20%{opacity:1}100%{opacity:0;transform:translate(-50%,-100%) scale(1.35)}}html[data-reduce="1"] *{animation:none!important;transition:none!important}
@media(max-width:900px){.app{grid-template-columns:1fr}aside{position:fixed;z-index:40;left:0;top:0;bottom:0;width:min(86vw,320px);transform:translateX(-105%);transition:.2s}aside.open{transform:none}main{padding:14px}.mobile{display:flex;gap:8px;margin-bottom:12px}.systembar{font-size:.58rem;flex-wrap:wrap}.systembar #systemPersonalization{order:3;width:100%;text-align:left}.card{grid-column:1/-1}}
@media(max-width:560px){.fields,.setting{grid-template-columns:1fr}.top{flex-direction:column}.tabs{display:grid}}
</style>
</head>
<body>
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
<button id="settings">⚙ Personalize System</button>
<button id="del" class="danger">Delete current</button>
<small id="storageNote" class="muted">Autosaves in this browser.</small>
</div>
</aside>

<main>
<div class="systembar"><span>◈ SYSTEM INTERFACE // CHARACTER ARCHIVE</span><span id="systemPersonalization">PERSONALIZATION: VAL ALIENCORE</span><span class="online">● LINK STABLE</span></div>
<div class="mobile"><button id="menu">☰ Characters</button><button id="msettings">⚙ Personalize</button></div>

<div id="empty" class="empty"><div><b>No character selected.</b><br>Create one or import JSON.</div></div>

<div id="editor" hidden>
<div class="top"><div><h2 id="title">Untitled Character</h2><p>System record synchronized across all profile layers.</p></div><div id="save">Saved</div></div>
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
<div class="panelhead"><div><h2>System Personalization</h2><small class="muted">The System stays the System. These change its cosmetic layer.</small></div><button id="close">✕</button></div>
<div class="note"><b>SYSTEM CORE:</b> fixed architecture, navigation, panels and database behavior. Personalizations change accent colors, glyphs, visual effects and audio.</div>
<div id="themeGrid" class="themegrid"></div>
<div class="setting"><div><b>Sound effects</b><small>Personalization-matched system tones.</small></div><label class="toggle"><input id="sound" type="checkbox"><span>Enabled</span></label></div>
<div class="setting"><div><b>Volume</b></div><input id="volume" type="range" min="0" max="100"></div>
<div class="setting"><div><b>Visual effects</b></div><select id="fx"><option value="off">Off</option><option value="low">Low</option><option value="full">Full</option></select></div>
<div class="setting"><div><b>UI density</b></div><select id="density"><option value="compact">Compact</option><option value="normal">Comfortable</option><option value="spacious">Spacious</option></select></div>
<div class="setting"><div><b>Text size</b></div><select id="font"><option value="14">Small</option><option value="16">Default</option><option value="18">Large</option><option value="20">Extra large</option></select></div>
<div class="setting"><div><b>Reduce motion</b></div><label class="toggle"><input id="reduce" type="checkbox"><span>Reduce</span></label></div>
<div class="row" style="margin-top:16px"><button id="reset">Reset personalization</button><button id="done">Done</button></div>
</div></div>

<script>
const ICON="data:image/webp;base64,"+
"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";

const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
$("#logo").src=ICON;$("#fav").href=ICON;

const SK="classUnknownDB",SETK="classUnknownSettings",mem=new Map();
const getStore=k=>{try{return localStorage.getItem(k)}catch{return mem.get(k)||null}};
const setStore=(k,v)=>{try{localStorage.setItem(k,v);return true}catch{mem.set(k,v);return false}};

const THEMES={
system:["System Default","#7feaff","#8aa8c7","#9ef1c4","◇",520,"Clean System baseline"],
authority:["Authority","#8fc8ff","#628fbd","#83e1b3","▣",460,"Government registry tint"],
crimson:["Crimson","#ff9eb2","#c8738b","#f4ce7a","✧",560,"Alert / combat skin"],
holo:["Holographic","#bfeaff","#d9c7ff","#e7ffd6","◌",500,"Pearl hologram skin"],
cyber:["Cyber Cute","#ff9cc8","#7fe9ff","#ffe57b","♥",880,"Pixel hearts + pastel"],
alien:["Val Aliencore","#86f3ef","#ffabc9","#aef7d7","👽",760,"Val's aliencore skin"],
kang:["Kang / Abyssal","#9d8cff","#65718f","#d7be7a","◆",360,"Kang's abyssal skin"],
slimes:["Roswell + Kepler","#ff9fc9","#6fa9ff","#9be8d0","●",620,"Paired slime skin"],
matriarch:["Matriarch","#b5f0dc","#d8c6ff","#efd58d","❋",540,"Organic divine skin"],
sanctuary:["Sanctuary","#86ece9","#83c8ff","#9fe6b9","❈",500,"Soft aqua glass skin"],
glitch:["Glitched","#62efff","#ff5db1","#8ff7c3","▥",420,"Corrupted System skin"]
};

const DEF={theme:"alien",sound:true,volume:32,fx:"full",density:"normal",font:"16",reduce:false};
let settings={...DEF,...JSON.parse(getStore(SETK)||"{}")};
if(settings.theme==="abyss")settings.theme="kang";
if(settings.theme==="dragon")settings.theme="kang";
if(settings.theme==="valentine")settings.theme="alien";
if(settings.theme==="light")settings.theme="holo";
if(settings.theme==="cybercute")settings.theme="cyber";
if(settings.theme==="roswellkepler")settings.theme="slimes";
if(settings.theme==="glitched")settings.theme="glitch";
if([".9","1","1.1","1.2"].includes(String(settings.font))){
  settings.font={".9":"14","1":"16","1.1":"18","1.2":"20"}[String(settings.font)];
}

let db=(()=>{try{return JSON.parse(getStore(SK)||'{"characters":[],"activeId":null}')}catch{return{characters:[],activeId:null}}})();
let active=db.activeId,audio=null;

const FORMS={
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

function blank(){return{id:crypto.randomUUID?crypto.randomUUID():"c"+Date.now(),createdAt:new Date().toISOString(),updatedAt:new Date().toISOString(),identity:{name:"",alias:"",age:"",pronouns:""},hunter:{rank:"",class:"",level:"",affiliation:"",type:"",lineage:"",systemNotes:"",abilities:""},stats:{strength:"",agility:"",endurance:"",mana:"",perception:"",control:""},gear:{primaryWeapon:"",secondaryWeapon:"",armor:"",artifacts:""},authority:{registeredName:"",hunterId:"",nationality:"",registrationStatus:"",watchStatus:"",clearance:"",manaSignature:"",scanReliability:"",physiology:"",notes:""},appearance:{height:"",build:"",hair:"",eyes:"",skin:"",features:""},personal:{personality:"",likes:"",dislikes:"",habits:"",relationships:"",voice:"",style:"",notes:""}}}
const read=(o,p)=>p.split(".").reduce((a,k)=>a?.[k],o)??"";
const write=(o,p,v)=>{const a=p.split("."),last=a.pop();let x=o;for(const k of a)x=x[k]??={};x[last]=v};
const current=()=>db.characters.find(c=>c.id===active)||null;

function buildForms(){
  for(const [sid,groups] of Object.entries(FORMS)){
    const grid=$("#"+sid+" .grid");
    for(const [title,fields] of groups){
      const card=document.createElement("div");
      card.className="card"+(fields.length===1?" full":"");
      card.innerHTML=`<h3>${title}</h3><div class="fields"></div>`;
      const box=$(".fields",card);
      for(const [label,path,type] of fields){
        const field=document.createElement("div");
        field.className="field"+(type==="ta"?" full":"");
        field.innerHTML=`<label>${label}</label>${type==="ta"?`<textarea data-path="${path}"></textarea>`:`<input data-path="${path}">`}`;
        box.appendChild(field);
      }
      grid.appendChild(card);
    }
  }
}function saveDB(){
  db.activeId=active;
  const ok=setStore(SK,JSON.stringify(db));
  $("#save").textContent=ok?"Saved locally":"Session-only save";
  $("#storageNote").textContent=ok?"Autosaves in this browser.":"Storage blocked. Export JSON before closing.";
}

function applyPersonalization(){
  const t=THEMES[settings.theme]||THEMES.system,r=document.documentElement;
  r.style.setProperty("--a",t[1]);
  r.style.setProperty("--b",t[2]);
  r.style.setProperty("--c",t[3]);
  r.style.setProperty("--gap",settings.density==="compact"?"10px":settings.density==="spacious"?"20px":"16px");
  r.style.setProperty("--font-size",(settings.font||"16")+"px");
  r.dataset.reduce=settings.reduce?"1":"0";
  $("#systemPersonalization").textContent="PERSONALIZATION: "+t[0].toUpperCase();
  $$(".theme").forEach(b=>b.classList.toggle("active",b.dataset.theme===settings.theme));
  $("#sound").checked=settings.sound;
  $("#volume").value=settings.volume;
  $("#fx").value=settings.fx;
  $("#density").value=settings.density;
  $("#font").value=String(settings.font);
  $("#reduce").checked=settings.reduce;
}

function saveSettings(){
  setStore(SETK,JSON.stringify(settings));
  applyPersonalization();
}

function renderThemes(){
  const g=$("#themeGrid");
  g.innerHTML="";
  for(const [key,t] of Object.entries(THEMES)){
    const b=document.createElement("button");
    b.className="theme";
    b.dataset.theme=key;
    b.style.setProperty("--s1",t[1]);
    b.style.setProperty("--s2",t[2]);
    b.innerHTML=`<span class="glyph">${t[4]}</span><span class="tname">${t[0]}</span><span class="tdesc">${t[6]}</span>`;
    b.onclick=()=>{
      settings.theme=key;
      saveSettings();
      tone("page");
    };
    g.appendChild(b);
  }
}

function renderList(){
  const q=$("#search").value.toLowerCase();
  const g=$("#charList");
  g.innerHTML="";
  const chars=db.characters.filter(c=>((c.identity?.name||"")+" "+(c.identity?.alias||"")).toLowerCase().includes(q));

  for(const c of chars){
    const b=document.createElement("button");
    b.className="char"+(c.id===active?" active":"");
    const meta=[c.hunter?.rank&&c.hunter.rank+" Rank",c.hunter?.class].filter(Boolean).join(" · ");
    b.innerHTML=`<b>${c.identity?.name||"Untitled Character"}</b><small>${meta||"No class data"}</small>`;
    b.onclick=()=>{
      active=c.id;
      saveDB();
      render();
      $("#side").classList.remove("open");
    };
    g.appendChild(b);
  }

  if(!g.children.length){
    g.innerHTML='<small class="muted">No characters yet.</small>';
  }
}

function renderEditor(){
  const c=current();
  $("#empty").hidden=!!c;
  $("#editor").hidden=!c;
  if(!c)return;

  $("#title").textContent=c.identity?.name||"Untitled Character";
  $$("[data-path]").forEach(e=>e.value=read(c,e.dataset.path));
}

function render(){
  renderList();
  renderEditor();
}

function tone(kind="click"){
  if(!settings.sound)return;

  const A=window.AudioContext||window.webkitAudioContext;
  if(!A)return;

  audio??=new A();

  if(audio.state==="suspended"){
    audio.resume().catch(()=>{});
  }

  const t=THEMES[settings.theme]||THEMES.system;
  const o=audio.createOscillator();
  const g=audio.createGain();
  const n=audio.currentTime;

  o.type=settings.theme==="glitch"?"square":settings.theme==="kang"?"sawtooth":"triangle";
  o.frequency.value=kind==="page"?t[5]*1.45:t[5];

  g.gain.setValueAtTime(.0001,n);
  g.gain.exponentialRampToValueAtTime(Math.max(.0008,settings.volume/100*.08),n+.01);
  g.gain.exponentialRampToValueAtTime(.0001,n+.15);

  o.connect(g);
  g.connect(audio.destination);
  o.start(n);
  o.stop(n+.17);
}

function burst(x,y){
  if(settings.reduce||settings.fx==="off")return;

  const t=THEMES[settings.theme]||THEMES.system;
  const e=document.createElement("div");

  e.className="burst";
  e.textContent=t[4];
  e.style.left=x+"px";
  e.style.top=y+"px";
  e.style.color=t[1];

  document.body.appendChild(e);

  setTimeout(()=>e.remove(),650);
}

function download(data,name){
  const u=URL.createObjectURL(
    new Blob(
      [JSON.stringify(data,null,2)],
      {type:"application/json"}
    )
  );

  const a=document.createElement("a");
  a.href=u;
  a.download=name;
  a.click();

  setTimeout(
    ()=>URL.revokeObjectURL(u),
    500
  );
}

buildForms();
renderThemes();
applyPersonalization();

$$("[data-path]").forEach(e=>{
  e.oninput=()=>{
    const c=current();
    if(!c)return;

    write(
      c,
      e.dataset.path,
      e.value
    );

    c.updatedAt=
      new Date().toISOString();

    if(e.dataset.path==="identity.name"){
      $("#title").textContent=
        e.value||
        "Untitled Character";
    }

    renderList();
    saveDB();
  };
});

$$(".tabs button").forEach(b=>{
  b.onclick=()=>{
    $$(".tabs button").forEach(
      x=>x.classList.remove("active")
    );

    $$(".sheet").forEach(
      x=>x.classList.remove("active")
    );

    b.classList.add("active");

    $("#"+b.dataset.tab)
      .classList
      .add("active");

    tone("page");
  };
});

$("#new").onclick=()=>{
  const c=blank();

  db.characters.unshift(c);
  active=c.id;

  saveDB();
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
    ? crypto.randomUUID()
    : "c"+Date.now();

  n.identity.name=
    (
      n.identity.name||
      "Untitled Character"
    )+
    " Copy";

  db.characters.unshift(n);

  active=n.id;

  saveDB();
  render();
};

$("#del").onclick=()=>{
  const c=current();

  if(
    c &&
    confirm(
      `Delete "${c.identity?.name||"Untitled Character"}"?`
    )
  ){
    db.characters=
      db.characters.filter(
        x=>x.id!==c.id
      );

    active=
      db.characters[0]?.id||
      null;

    saveDB();
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
      )+
      ".json"
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

$("#file").onchange=async e=>{
  try{
    const p=
      JSON.parse(
        await e.target.files[0].text()
      );

    const arr=
      Array.isArray(p)
      ? p
      : Array.isArray(p.characters)
      ? p.characters
      : [p];

    for(const x of arr){
      if(!x.id){
        x.id=
          crypto.randomUUID
          ? crypto.randomUUID()
          : "c"+
            Date.now()+
            Math.random();
      }

      db.characters.unshift(x);
    }

    active=
      arr[0]?.id||
      active;

    saveDB();
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

$("#settings").onclick=open;
$("#msettings").onclick=open;
$("#close").onclick=close;
$("#done").onclick=close;

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
      e.target.closest("button");

    if(!b)return;

    const r=
      b.getBoundingClientRect();

    burst(
      r.left+r.width/2,
      r.top+r.height/2
    );

    if(
      !b.closest(".tabs") &&
      !b.classList.contains("theme")
    ){
      tone(
        b.id==="del"
        ? "danger"
        : "click"
      );
    }
  }
);

if(
  active &&
  !current()
){
  active=
    db.characters[0]?.id||
    null;
}

render();
saveDB();
</script>
</body>
</html>

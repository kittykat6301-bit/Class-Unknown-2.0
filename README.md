<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#0d1020">
<meta name="description" content="Class Unknown Character Database">
<link rel="icon" href="data:image/webp;base64,UklGRgwDAABXRUJQVlA4IAADAAAQDACdASowADAAA8BgJbACpJxKBimlZzz6rMO2k+lMjUw2FbXTy0NJ8zsXq4F4JNp2cC3YeUfu1e/U6/61Dpu8C4ZQclT5/klPBAdLkjJ75cu0+zvmo1IErZ8KJOtbPQQTjYQa86Ef0AAA/vQuVSv1fUnn11YdmG3jl6aoBIwHiu1H84p1fBml2TOMQeFw05GZBilwOcu2UbHzL7dZ9cqPrbnqe5hDcgZ74lGsnpGltessnFSnb6v3TombbZkLdGO+VlXpR/0AkqSuAkmDI18zYgz8hRR55w3ravVIBevK+ydhWJ5z6yfABLXrlMZj5oC1x0gw/3C1XYDJFsf9fIuOJQHldVoR9LIn1TbzleVwJQJ58gsLQT7/6wUoYZbYeMkAgX2ds+xAxFnFggAnacNzxUqQ3VwjnHFfMXNYFIQJNVT+kSmb++i5IisT+21C3DkWviK9aQjgkj3xUD9bFv9yPv3GLAM2XOz0WadldpY5wWvJ5fyg/9i4yLXetYnbNhW2kSYw3HoOa5VnspV7O9uWtj6QtRQTNHMDPbz9uGUVL8c4ShBydvpIZLcesiSaADxjoTqiyUt9hMytyQBSCABxg588DZb/f/XuHivLK+nOkDBfg0RgKzXYHoa4JKPz84JibGhDswwODbVpYf4945afTcNJxvQ1lpqyKgeFi0XenpKEN6eUCuc37cBMk0PI9jYPRttDZnmBjhuatN96+ciWpLh1lJ4We5pPjCp9mdi/d6DIB9nqeQaAsjSfR/BFZ+WHrhcl+s/d6ZsH7iUP415PlPZMTTu5wnaDDKHiR70LpZBR2pWWjgjLzSFmGaojUI2n1Kzo4I3vu9D7NqvNFa8I8oCWYFgT2tkuDeat4VunJ1qn1DPiQRuXp9F76i85rQZQco0OrYI2hPPGqD7qUZHzT1XmYVabwSFJNdApD1BRlJivvNZU7c/PBQG1M97Q5i3F8X1IwfsxcbcIj8tv/+FtT5zJj3HXve+qzDq+IvQFw7RRPO2FsWh0QWLz0qKAAAA=" type="image/webp">
<title>Class Unknown Character Database</title>
<style>
:root{--bg:#0b1020;--panel:#151b2d;--panel2:#1d2540;--line:#344260;--text:#f7fbff;--muted:#9fb0c9;--a:#7feaff;--b:#b69cff;--c:#9ef1c4;--danger:#ff7f9c;--r:18px;--gap:16px;--fs:1}
*{box-sizing:border-box}html,body{min-height:100%}body{margin:0;background:var(--bg);color:var(--text);font:calc(16px*var(--fs))/1.4 Inter,system-ui,-apple-system,Segoe UI,sans-serif;transition:.25s;background-image:radial-gradient(circle at 15% 5%,color-mix(in srgb,var(--a) 16%,transparent),transparent 28rem),radial-gradient(circle at 90% 5%,color-mix(in srgb,var(--b) 15%,transparent),transparent 28rem)}button,input,textarea,select{font:inherit}button{color:var(--text);background:var(--panel2);border:1px solid var(--line);border-radius:12px;padding:.7rem .85rem;cursor:pointer}button:hover{border-color:var(--a)}input,textarea,select{width:100%;color:var(--text);background:color-mix(in srgb,var(--bg) 78%,var(--panel) 22%);border:1px solid var(--line);border-radius:10px;padding:.7rem;outline:none}input:focus,textarea:focus,select:focus{border-color:var(--a);box-shadow:0 0 0 3px color-mix(in srgb,var(--a) 12%,transparent)}textarea{min-height:100px;resize:vertical}label{display:block;color:var(--muted);font-size:.72rem;text-transform:uppercase;letter-spacing:.08em;margin-bottom:5px}
.app{display:grid;grid-template-columns:290px 1fr;min-height:100vh}aside{padding:18px;border-right:1px solid var(--line);background:color-mix(in srgb,var(--bg) 88%,transparent);backdrop-filter:blur(12px);position:sticky;top:0;height:100vh;overflow:auto}main{padding:24px;min-width:0}.brand{display:flex;gap:11px;align-items:center;margin-bottom:18px}.brand img{width:46px;height:46px;border-radius:14px;box-shadow:0 0 24px color-mix(in srgb,var(--a) 20%,transparent)}.brand h1{font-size:1rem;margin:0;letter-spacing:.08em}.brand small{color:var(--muted)}.row{display:flex;gap:8px;flex-wrap:wrap}.row>*{flex:1}#search{margin:10px 0}#charList{display:grid;gap:7px}.char{text-align:left;background:transparent;border-color:transparent}.char.active{background:linear-gradient(135deg,color-mix(in srgb,var(--a) 10%,transparent),color-mix(in srgb,var(--b) 10%,transparent));border-color:var(--line)}.char b,.char small{display:block}.char small{color:var(--muted);margin-top:2px}.sidefoot{margin-top:16px;padding-top:14px;border-top:1px solid var(--line);display:grid;gap:8px}.danger{color:#ffdce4;border-color:#744052;background:#28151d}.status{color:var(--c);font-size:.8rem}.top{display:flex;justify-content:space-between;gap:16px;align-items:flex-start;margin-bottom:16px}.top h2{margin:0}.top p{margin:.3rem 0 0;color:var(--muted)}.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:16px}.tabs button.active{border-color:var(--a);background:linear-gradient(135deg,color-mix(in srgb,var(--a) 13%,transparent),color-mix(in srgb,var(--b) 12%,transparent))}.sheet{display:none}.sheet.active{display:block;animation:in .28s ease}@keyframes in{from{opacity:0;transform:translateY(8px);filter:blur(2px)}to{opacity:1;transform:none;filter:none}}.grid{display:grid;grid-template-columns:repeat(12,1fr);gap:var(--gap)}.card{grid-column:span 6;background:linear-gradient(180deg,color-mix(in srgb,var(--panel) 96%,transparent),color-mix(in srgb,var(--bg) 88%,var(--panel) 12%));border:1px solid var(--line);border-radius:var(--r);padding:16px;box-shadow:0 16px 40px rgba(0,0,0,.28);position:relative;overflow:hidden}.card.full{grid-column:1/-1}.card:after{content:"";position:absolute;right:-15px;top:-15px;width:70px;height:70px;border:1px solid color-mix(in srgb,var(--a) 30%,transparent);border-radius:50%;opacity:.4;pointer-events:none}.card h3{margin:0 0 12px;color:var(--a);font-size:.82rem;text-transform:uppercase;letter-spacing:.1em}.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.field.full{grid-column:1/-1}.empty{min-height:55vh;display:grid;place-items:center;text-align:center;color:var(--muted);border:1px dashed var(--line);border-radius:22px}.modal{position:fixed;inset:0;display:none;place-items:center;padding:18px;background:rgba(0,0,0,.62);backdrop-filter:blur(8px);z-index:50}.modal.open{display:grid}.panel{width:min(760px,100%);max-height:88vh;overflow:auto;background:var(--panel);border:1px solid var(--line);border-radius:22px;padding:18px;box-shadow:0 30px 80px rgba(0,0,0,.45)}.panelhead{display:flex;justify-content:space-between;gap:12px;align-items:center}.panel h2{margin:0}.themegrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(110px,1fr));gap:8px;margin:14px 0 18px}.theme{min-height:76px;text-align:left}.theme.active{outline:2px solid var(--a)}.swatch{display:block;height:28px;border-radius:8px;margin-bottom:7px;background:linear-gradient(90deg,var(--s1),var(--s2),var(--s3))}.setting{display:grid;grid-template-columns:1fr minmax(180px,260px);gap:12px;align-items:center;padding:11px 0;border-top:1px solid var(--line)}.setting small{display:block;color:var(--muted);margin-top:2px}.toggle{display:flex;justify-content:flex-end;gap:8px;align-items:center}.toggle input{width:20px;height:20px}.burst{position:fixed;pointer-events:none;z-index:100;font-size:22px;font-weight:900;animation:burst .65s ease-out forwards;text-shadow:0 0 16px currentColor}@keyframes burst{0%{opacity:0;transform:translate(-50%,-30%) scale(.5)}15%{opacity:1}100%{opacity:0;transform:translate(-50%,-110%) scale(1.4)}}.flash{position:fixed;inset:0;pointer-events:none;z-index:90;background:radial-gradient(circle at var(--x) var(--y),color-mix(in srgb,var(--a) 24%,transparent),transparent 38%);animation:flash .45s ease-out forwards}@keyframes flash{from{opacity:.8}to{opacity:0}}html[data-reduce="1"] *{animation:none!important;transition:none!important}.mobile{display:none}
@media(max-width:900px){.app{grid-template-columns:1fr}aside{position:fixed;z-index:40;left:0;top:0;bottom:0;width:min(86vw,320px);transform:translateX(-105%);transition:.2s}aside.open{transform:none}main{padding:16px}.mobile{display:flex;gap:8px;margin-bottom:12px}.card{grid-column:1/-1}}
@media(max-width:560px){.fields,.setting{grid-template-columns:1fr}.top{flex-direction:column}.tabs{display:grid}}
</style>
</head>
<body>
<div class="app">
<aside id="side">
<div class="brand"><img src="data:image/webp;base64,UklGRgwDAABXRUJQVlA4IAADAAAQDACdASowADAAA8BgJbACpJxKBimlZzz6rMO2k+lMjUw2FbXTy0NJ8zsXq4F4JNp2cC3YeUfu1e/U6/61Dpu8C4ZQclT5/klPBAdLkjJ75cu0+zvmo1IErZ8KJOtbPQQTjYQa86Ef0AAA/vQuVSv1fUnn11YdmG3jl6aoBIwHiu1H84p1fBml2TOMQeFw05GZBilwOcu2UbHzL7dZ9cqPrbnqe5hDcgZ74lGsnpGltessnFSnb6v3TombbZkLdGO+VlXpR/0AkqSuAkmDI18zYgz8hRR55w3ravVIBevK+ydhWJ5z6yfABLXrlMZj5oC1x0gw/3C1XYDJFsf9fIuOJQHldVoR9LIn1TbzleVwJQJ58gsLQT7/6wUoYZbYeMkAgX2ds+xAxFnFggAnacNzxUqQ3VwjnHFfMXNYFIQJNVT+kSmb++i5IisT+21C3DkWviK9aQjgkj3xUD9bFv9yPv3GLAM2XOz0WadldpY5wWvJ5fyg/9i4yLXetYnbNhW2kSYw3HoOa5VnspV7O9uWtj6QtRQTNHMDPbz9uGUVL8c4ShBydvpIZLcesiSaADxjoTqiyUt9hMytyQBSCABxg588DZb/f/XuHivLK+nOkDBfg0RgKzXYHoa4JKPz84JibGhDswwODbVpYf4945afTcNJxvQ1lpqyKgeFi0XenpKEN6eUCuc37cBMk0PI9jYPRttDZnmBjhuatN96+ciWpLh1lJ4We5pPjCp9mdi/d6DIB9nqeQaAsjSfR/BFZ+WHrhcl+s/d6ZsH7iUP415PlPZMTTu5wnaDDKHiR70LpZBR2pWWjgjLzSFmGaojUI2n1Kzo4I3vu9D7NqvNFa8I8oCWYFgT2tkuDeat4VunJ1qn1DPiQRuXp9F76i85rQZQco0OrYI2hPPGqD7qUZHzT1XmYVabwSFJNdApD1BRlJivvNZU7c/PBQG1M97Q5i3F8X1IwfsxcbcIj8tv/+FtT5zJj3HXve+qzDq+IvQFw7RRPO2FsWh0QWLz0qKAAAA=" alt=""><div><h1>CLASS UNKNOWN</h1><small>Character Database</small></div></div>
<div class="row"><button id="new">＋ New</button><button id="dup">Duplicate</button></div>
<input id="search" placeholder="Search characters…">
<div id="charList"></div>
<div class="sidefoot">
<button id="exp">Export current JSON</button><button id="expAll">Export all JSON</button>
<button id="imp">Import JSON</button><input id="file" type="file" accept=".json,application/json" hidden>
<button id="settings">⚙ Settings</button><button id="del" class="danger">Delete current</button>
<small id="storageNote" style="color:var(--muted)">Autosaves in this browser.</small>
</div>
</aside>
<main>
<div class="mobile"><button id="menu">☰ Characters</button><button id="msettings">⚙ Settings</button></div>
<div id="empty" class="empty"><div><b>No character selected.</b><br>Create one or import JSON.</div></div>
<div id="editor" hidden>
<div class="top"><div><h2 id="title">Untitled Character</h2><p>One record, three synchronized in-world sheets.</p></div><div id="save" class="status">Saved</div></div>
<div class="tabs"><button class="active" data-tab="system">01 · System / Hunter</button><button data-tab="authority">02 · Authority / Body Scan</button><button data-tab="personal">03 · Personal Profile</button></div>
<section id="system" class="sheet active"><div class="grid"></div></section>
<section id="authority" class="sheet"><div class="grid"></div></section>
<section id="personal" class="sheet"><div class="grid"></div></section>
</div>
</main>
</div>
<div id="modal" class="modal"><div class="panel">
<div class="panelhead"><div><h2>Site Settings</h2><small style="color:var(--muted)">Theme, sound, effects and layout.</small></div><button id="close">✕</button></div>
<div id="themeGrid" class="themegrid"></div>
<div class="setting"><div><b>Sound effects</b><small>Theme-matched clicks and page tones.</small></div><label class="toggle"><input id="sound" type="checkbox"><span>Enabled</span></label></div>
<div class="setting"><div><b>Volume</b></div><input id="volume" type="range" min="0" max="100"></div>
<div class="setting"><div><b>Visual effects</b></div><select id="fx"><option value="off">Off</option><option value="low">Low</option><option value="full">Full</option></select></div>
<div class="setting"><div><b>UI density</b></div><select id="density"><option value="compact">Compact</option><option value="normal">Comfortable</option><option value="spacious">Spacious</option></select></div>
<div class="setting"><div><b>Text size</b></div><select id="font"><option value=".9">Small</option><option value="1">Default</option><option value="1.1">Large</option><option value="1.2">Extra large</option></select></div>
<div class="setting"><div><b>Reduce motion</b></div><label class="toggle"><input id="reduce" type="checkbox"><span>Reduce</span></label></div>
<div class="row" style="margin-top:16px"><button id="reset">Reset settings</button><button id="done">Done</button></div>
</div></div>
<script>
(()=>{
const $=(s,r=document)=>r.querySelector(s), $$=(s,r=document)=>[...r.querySelectorAll(s)];
const SK="classUnknownDB", SETK="classUnknownSettings", mem=new Map();
const sg=k=>{try{return localStorage.getItem(k)}catch{return mem.get(k)||null}}, ss=(k,v)=>{try{localStorage.setItem(k,v);return true}catch{mem.set(k,v);return false}};
const THEMES={
abyss:["Abyss","#0b1020","#151b2d","#7feaff","#9d8cff","#72f0b3","◈",520],
authority:["Authority","#080b10","#11161d","#8fc8ff","#628fbd","#83e1b3","▣",460],
valentine:["Valentine","#160f20","#211831","#8ff6ef","#c59cff","#ff9ac8","✦",700],
crimson:["Crimson","#12090d","#221119","#ff9eb2","#c8738b","#f4ce7a","✧",560],
light:["Light","#edf3f8","#ffffff","#087ea4","#456bd1","#16875d","✺",500],
cybercute:["Cyber Cute","#120f23","#211a3a","#ff9cc8","#7fe9ff","#ffe57b","♥",880],
alien:["Val Aliencore","#110f20","#211a36","#86f3ef","#ffabc9","#aef7d7","👽",760],
dragon:["Kang / Abyssal","#09080f","#15151e","#9d8cff","#7f89b9","#d7be7a","⟡",360],
roswellkepler:["Roswell + Kepler","#0f1020","#1c1e35","#ff9fc9","#6fa9ff","#9be8d0","♥",620],
matriarch:["Matriarch","#101118","#1a2028","#b5f0dc","#d8c6ff","#efd58d","❋",540],
sanctuary:["Sanctuary","#0b1116","#152229","#86ece9","#83c8ff","#9fe6b9","❈",500],
glitched:["Glitched","#090913","#17172a","#62efff","#ff5db1","#8ff7c3","▥",420]
};
const DEF={theme:"alien",sound:true,volume:32,fx:"full",density:"normal",font:"1",reduce:false};
let settings={...DEF,...JSON.parse(sg(SETK)||"{}")}, db=(()=>{try{return JSON.parse(sg(SK)||'{"characters":[],"activeId":null}')}catch{return {characters:[],activeId:null}}})(), active=db.activeId, audio=null;
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
]
};
function blank(){return{id:crypto.randomUUID?crypto.randomUUID():"c"+Date.now(),createdAt:new Date().toISOString(),updatedAt:new Date().toISOString(),identity:{name:"",alias:"",age:"",pronouns:""},hunter:{rank:"",class:"",level:"",affiliation:"",type:"",lineage:"",systemNotes:"",abilities:""},stats:{strength:"",agility:"",endurance:"",mana:"",perception:"",control:""},gear:{primaryWeapon:"",secondaryWeapon:"",armor:"",artifacts:""},authority:{registeredName:"",hunterId:"",nationality:"",registrationStatus:"",watchStatus:"",clearance:"",manaSignature:"",scanReliability:"",physiology:"",notes:""},appearance:{height:"",build:"",hair:"",eyes:"",skin:"",features:""},personal:{personality:"",likes:"",dislikes:"",habits:"",relationships:"",voice:"",style:"",notes:""}}}
const get=(o,p)=>p.split(".").reduce((a,k)=>a?.[k],o)??"", set=(o,p,v)=>{let a=p.split("."),k=a.pop(),x=o;for(const q of a)x=x[q]??=( {} );x[k]=v};
function buildForms(){for(const [sid,groups] of Object.entries(FORMS)){const g=$("#"+sid+" .grid");for(const [name,fields] of groups){const card=document.createElement("div");card.className="card"+(fields.length===1?" full":"");card.innerHTML="<h3>"+name+"</h3><div class='fields'></div>";const box=$(".fields",card);for(const [lab,path,type] of fields){const f=document.createElement("div");f.className="field"+(type==="ta"?" full":"");f.innerHTML="<label>"+lab+"</label>"+(type==="ta"?`<textarea data-path="${path}"></textarea>`:`<input data-path="${path}">`);box.appendChild(f)}g.appendChild(card)}}}
function cur(){return db.characters.find(c=>c.id===active)||null}
function persist(){db.activeId=active;const ok=ss(SK,JSON.stringify(db));$("#save").textContent=ok?"Saved locally":"Session-only save";$("#storageNote").textContent=ok?"Autosaves in this browser.":"This browser blocked storage. Export JSON before closing.";}
function applyTheme(){const t=THEMES[settings.theme]||THEMES.alien,r=document.documentElement;r.style.setProperty("--bg",t[1]);r.style.setProperty("--panel",t[2]);r.style.setProperty("--panel2",`color-mix(in srgb, ${t[2]} 82%, ${t[4]} 18%)`);r.style.setProperty("--a",t[3]);r.style.setProperty("--b",t[4]);r.style.setProperty("--c",t[5]);r.style.setProperty("--fs",settings.font);r.style.setProperty("--gap",settings.density==="compact"?"10px":settings.density==="spacious"?"20px":"16px");r.dataset.reduce=settings.reduce?"1":"0";document.querySelector('meta[name="theme-color"]').content=t[1];$$(".theme").forEach(b=>b.classList.toggle("active",b.dataset.theme===settings.theme));$("#sound").checked=settings.sound;$("#volume").value=settings.volume;$("#fx").value=settings.fx;$("#density").value=settings.density;$("#font").value=settings.font;$("#reduce").checked=settings.reduce}
function saveSettings(){ss(SETK,JSON.stringify(settings));applyTheme()}
function renderThemes(){const g=$("#themeGrid");g.innerHTML="";for(const [k,t] of Object.entries(THEMES)){const b=document.createElement("button");b.className="theme";b.dataset.theme=k;b.innerHTML=`<span class="swatch" style="--s1:${t[3]};--s2:${t[4]};--s3:${t[5]}"></span><b>${t[0]}</b>`;b.onclick=()=>{settings.theme=k;saveSettings();fxFlash(null,true);sound("page")};g.appendChild(b)}}
function renderList(){const q=$("#search").value.toLowerCase(),g=$("#charList");g.innerHTML="";for(const c of db.characters.filter(c=>((c.identity?.name||"")+" "+(c.identity?.alias||"")).toLowerCase().includes(q))){const b=document.createElement("button");b.className="char"+(c.id===active?" active":"");b.innerHTML=`<b>${c.identity?.name||"Untitled Character"}</b><small>${[c.hunter?.rank&&c.hunter.rank+" Rank",c.hunter?.class].filter(Boolean).join(" · ")||"No class data"}</small>`;b.onclick=()=>{active=c.id;persist();render();$("#side").classList.remove("open")};g.appendChild(b)}if(!g.children.length)g.innerHTML="<small style='color:var(--muted)'>No characters yet.</small>"}
function renderEditor(){const c=cur();$("#empty").hidden=!!c;$("#editor").hidden=!c;if(!c)return;$("#title").textContent=c.identity?.name||"Untitled Character";$$("[data-path]").forEach(e=>e.value=get(c,e.dataset.path))}
function render(){renderList();renderEditor()}
function sound(kind="click"){if(!settings.sound)return;const C=window.AudioContext||window.webkitAudioContext;if(!C)return;audio??=new C();if(audio.state==="suspended")audio.resume().catch(()=>{});const t=THEMES[settings.theme]||THEMES.alien,n=audio.currentTime,o=audio.createOscillator(),g=audio.createGain();o.type=settings.theme==="glitched"?"square":settings.theme==="dragon"?"sawtooth":"triangle";o.frequency.value=(kind==="page"?t[7]*1.45:t[7]);g.gain.setValueAtTime(.0001,n);g.gain.exponentialRampToValueAtTime(Math.max(.0008,settings.volume/100*0.08),n+.01);g.gain.exponentialRampToValueAtTime(.0001,n+.15);o.connect(g);g.connect(audio.destination);o.start(n);o.stop(n+.17)}
function burst(x,y){if(settings.reduce||settings.fx==="off")return;const t=THEMES[settings.theme];const e=document.createElement("div");e.className="burst";e.textContent=t[6];e.style.left=x+"px";e.style.top=y+"px";e.style.color=t[3];document.body.appendChild(e);setTimeout(()=>e.remove(),700)}
function fxFlash(el,strong=false){if(settings.reduce||settings.fx==="off"||(strong&&settings.fx!=="full"))return;const f=document.createElement("div"),r=el?.getBoundingClientRect();f.className="flash";f.style.setProperty("--x",r?((r.left+r.width/2)/innerWidth*100)+"%":"50%");f.style.setProperty("--y",r?((r.top+r.height/2)/innerHeight*100)+"%":"20%");document.body.appendChild(f);setTimeout(()=>f.remove(),500)}
function dl(data,name){const a=document.createElement("a"),u=URL.createObjectURL(new Blob([JSON.stringify(data,null,2)],{type:"application/json"}));a.href=u;a.download=name;a.click();setTimeout(()=>URL.revokeObjectURL(u),500)}
buildForms();renderThemes();applyTheme();
$$("[data-path]").forEach(e=>e.addEventListener("input",()=>{const c=cur();if(!c)return;set(c,e.dataset.path,e.value);c.updatedAt=new Date().toISOString();if(e.dataset.path==="identity.name")$("#title").textContent=e.value||"Untitled Character";renderList();persist()}));
$$(".tabs button").forEach(b=>b.onclick=()=>{$$(".tabs button").forEach(x=>x.classList.remove("active"));$$(".sheet").forEach(x=>x.classList.remove("active"));b.classList.add("active");$("#"+b.dataset.tab).classList.add("active");fxFlash(b);sound("page")});
$("#new").onclick=()=>{const c=blank();db.characters.unshift(c);active=c.id;persist();render();$('[data-path="identity.name"]').focus()};
$("#dup").onclick=()=>{const c=cur();if(!c)return;const n=structuredClone(c);n.id=crypto.randomUUID?crypto.randomUUID():"c"+Date.now();n.identity.name=(n.identity.name||"Untitled Character")+" Copy";db.characters.unshift(n);active=n.id;persist();render()};
$("#del").onclick=()=>{const c=cur();if(!c)return;if(confirm(`Delete "${c.identity?.name||"Untitled Character"}"?`)){db.characters=db.characters.filter(x=>x.id!==c.id);active=db.characters[0]?.id||null;persist();render()}};
$("#exp").onclick=()=>{const c=cur();if(c)dl(c,(c.identity?.name||"character").replace(/[^\w-]+/g,"_")+".json")};$("#expAll").onclick=()=>dl({characters:db.characters},"class-unknown-character-database.json");
$("#imp").onclick=()=>$("#file").click();$("#file").onchange=async e=>{try{const p=JSON.parse(await e.target.files[0].text()),arr=Array.isArray(p)?p:Array.isArray(p.characters)?p.characters:[p];for(const x of arr){if(!x.id)x.id=crypto.randomUUID?crypto.randomUUID():"c"+Date.now()+Math.random();db.characters.unshift(x)}active=arr[0]?.id||active;persist();render()}catch(err){alert("Import failed: "+err.message)}e.target.value=""};
$("#search").oninput=renderList;$("#menu").onclick=()=>$("#side").classList.toggle("open");
const open=()=>$("#modal").classList.add("open"), close=()=>$("#modal").classList.remove("open");$("#settings").onclick=open;$("#msettings").onclick=open;$("#close").onclick=close;$("#done").onclick=close;$("#modal").onclick=e=>{if(e.target===$("#modal"))close()};
$("#sound").onchange=e=>{settings.sound=e.target.checked;saveSettings()};$("#volume").oninput=e=>{settings.volume=+e.target.value;saveSettings()};$("#fx").onchange=e=>{settings.fx=e.target.value;saveSettings()};$("#density").onchange=e=>{settings.density=e.target.value;saveSettings()};$("#font").onchange=e=>{settings.font=e.target.value;saveSettings()};$("#reduce").onchange=e=>{settings.reduce=e.target.checked;saveSettings()};$("#reset").onclick=()=>{settings={...DEF};saveSettings()};
document.addEventListener("click",e=>{const b=e.target.closest("button");if(!b)return;const r=b.getBoundingClientRect();burst(r.left+r.width/2,r.top+r.height/2);if(!b.closest(".tabs")&&!b.classList.contains("theme"))sound(b.id==="del"?"danger":"click")});
if(active&&!cur())active=db.characters[0]?.id||null;render();persist();
})();
</script>
</body>
</html>

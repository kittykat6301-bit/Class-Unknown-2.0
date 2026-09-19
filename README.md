<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#070b11">
<title>Class Unknown Character Database</title>
<link id="fav" rel="icon">
<style>
:root{--bg:#03070d;--panel:#07111b;--panel2:#0b1724;--line:#244a70;--line2:#5fb8ff;--text:#f1f8ff;--muted:#8ea9c3;--a:#8fe7ff;--b:#a79dff;--c:#9ef5cb;--gap:16px;--font-size:16px}
*{box-sizing:border-box}[hidden]{display:none!important}html{font-size:var(--font-size);min-height:100%}body{min-height:100%;margin:0;color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,sans-serif;font-size:1rem;line-height:1.4;background:radial-gradient(circle at 50% -10%,rgba(87,171,255,.16),transparent 32%),radial-gradient(circle at 50% 115%,rgba(123,71,255,.09),transparent 24%),linear-gradient(180deg,#03070d 0%,#050a11 45%,#03070d 100%);overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(circle at 50% 50%,rgba(77,159,255,.06),transparent 40%),repeating-linear-gradient(180deg,rgba(170,220,255,.022) 0 1px,transparent 1px 4px)}
body:after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background-image:linear-gradient(rgba(108,188,255,.05) 1px,transparent 1px),linear-gradient(90deg,rgba(108,188,255,.04) 1px,transparent 1px);background-size:44px 44px;mask-image:linear-gradient(to bottom,rgba(0,0,0,.55),transparent 88%)}
button,input,textarea,select{font:inherit}button{color:var(--text);background:linear-gradient(180deg,rgba(10,23,36,.94),rgba(6,13,21,.96));border:1px solid color-mix(in srgb,var(--line2) 30%,var(--line));border-radius:6px;padding:.72rem .88rem;cursor:pointer;box-shadow:inset 0 0 0 1px rgba(255,255,255,.03),0 0 0 1px rgba(95,184,255,.03)}button:hover{border-color:color-mix(in srgb,var(--a) 78%,white 10%);box-shadow:0 0 0 1px rgba(143,231,255,.1),0 0 18px rgba(88,170,255,.12),inset 0 0 0 1px rgba(255,255,255,.04)}button:active{transform:translateY(1px)}
input,textarea,select{width:100%;color:var(--text);background:rgba(4,10,16,.9);border:1px solid color-mix(in srgb,var(--line2) 22%,var(--line));border-radius:4px;padding:.72rem;outline:none;box-shadow:inset 0 0 18px rgba(67,137,255,.04)}input:focus,textarea:focus,select:focus{border-color:var(--a);box-shadow:0 0 0 1px rgba(143,231,255,.2),0 0 14px rgba(77,171,255,.18),inset 0 0 18px rgba(67,137,255,.06)}textarea{min-height:100px;resize:vertical}label{display:block;color:var(--muted);font:700 .68rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;text-transform:uppercase;letter-spacing:.13em;margin-bottom:7px}
.app{display:grid;grid-template-columns:280px 1fr;min-height:100vh}aside{height:100vh;position:sticky;top:0;overflow:auto;padding:18px;border-right:1px solid rgba(106,178,255,.18);background:linear-gradient(180deg,rgba(4,9,15,.94),rgba(3,8,14,.86));backdrop-filter:blur(10px);box-shadow:inset -1px 0 0 rgba(126,223,255,.08),0 0 55px rgba(62,134,255,.08)}main{padding:16px 24px 30px;min-width:0;display:flex;flex-direction:column}.brand{display:flex;gap:11px;align-items:center;margin-bottom:18px}.brand img{width:46px;height:46px;border-radius:12px;box-shadow:0 0 26px rgba(128,230,255,.25),0 0 40px rgba(140,88,255,.12)}.brand h1{font-size:.98rem;margin:0;letter-spacing:.14em;font-weight:800}.brand small,.muted{color:var(--muted)}.row{display:flex;gap:8px;flex-wrap:wrap}.row>*{flex:1}#search{margin:10px 0 12px}#charList{display:grid;gap:7px}.char{text-align:left;background:rgba(6,13,21,.55);border-color:rgba(107,171,255,.1)}.char.active{border-color:var(--a);background:linear-gradient(90deg,rgba(76,170,255,.12),rgba(3,13,22,.82));box-shadow:inset 2px 0 0 var(--a),0 0 18px rgba(79,180,255,.1)}.char b,.char small{display:block}.char small{color:var(--muted)}.sidefoot{margin-top:16px;padding-top:14px;border-top:1px solid rgba(106,178,255,.14);display:grid;gap:8px}.danger{color:#ffdce4;border-color:#763e54;background:linear-gradient(180deg,rgba(45,17,28,.92),rgba(28,10,18,.95))}
.systembar{margin:0 auto 16px;max-width:1180px;width:100%;padding:8px 12px;display:flex;justify-content:space-between;gap:12px;align-items:center;border:1px solid rgba(115,188,255,.2);border-radius:6px;background:linear-gradient(180deg,rgba(7,15,23,.88),rgba(3,8,14,.92));color:var(--muted);font:700 .62rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.14em;text-transform:uppercase;box-shadow:inset 0 0 0 1px rgba(255,255,255,.02),0 0 28px rgba(62,134,255,.08)}#systemPersonalization{color:var(--a);text-align:center}.online{color:var(--c)}.mobile{display:none}
.empty{max-width:1180px;width:100%;margin:0 auto;min-height:68vh;display:grid;place-items:center;text-align:center;color:var(--muted);border:1px solid color-mix(in srgb,var(--a) 42%,rgba(109,183,255,.22));border-radius:8px;background:linear-gradient(180deg,rgba(6,13,21,.78),rgba(5,9,15,.92));position:relative;overflow:hidden;box-shadow:0 0 40px rgba(44,110,255,.08),inset 0 0 0 1px rgba(255,255,255,.03)}.empty:before{content:"";position:absolute;inset:14px;border:1px solid rgba(114,195,255,.12);pointer-events:none}
#editor{max-width:1180px;width:100%;margin:0 auto;padding:26px 24px 24px;position:relative;border:1px solid rgba(109,183,255,.22);border-radius:8px;background:linear-gradient(180deg,rgba(5,11,18,.86),rgba(4,9,15,.95));box-shadow:0 0 45px rgba(45,110,255,.12),inset 0 0 0 1px rgba(255,255,255,.02);overflow:visible}
#editor:before{content:"";position:absolute;inset:12px;border:1px solid rgba(116,197,255,.15);pointer-events:none}
#editor:after{content:"";position:absolute;inset:0;pointer-events:none;background:radial-gradient(circle at 15% 10%,rgba(137,224,255,.08),transparent 22%),radial-gradient(circle at 85% 12%,rgba(125,115,255,.06),transparent 16%),linear-gradient(180deg,rgba(255,255,255,.03),transparent 16%)}
.editor-corners{display:none}
.top,.tabs,.sheet,.theme-controls,.custom-editor{position:relative;z-index:3}.top{display:flex;justify-content:space-between;gap:16px;align-items:flex-start;margin-bottom:18px;padding:0 0 12px;border-bottom:1px solid rgba(106,178,255,.14)}.top h2{margin:0;font:800 1.55rem/1.15 Inter,system-ui,sans-serif;letter-spacing:.04em;text-shadow:0 0 14px rgba(136,224,255,.12)}.top p{margin:.35rem 0 0;color:var(--muted);max-width:55ch}.record-actions{display:flex;gap:8px;align-items:center;justify-content:flex-end;flex-wrap:wrap}#save{color:var(--c);font-size:.76rem;font-family:ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.07em;text-transform:uppercase}#recordAction{min-width:142px}
.mode-pill{display:inline-flex;align-items:center;gap:6px;padding:4px 8px;border:1px solid rgba(106,178,255,.18);border-radius:999px;color:var(--muted);font:700 .56rem/1 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em;text-transform:uppercase;background:rgba(4,10,16,.55)}.mode-pill:before{content:"●";color:var(--c)}#editor.edit-mode .mode-pill:before{color:var(--b)}
.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}.tabs button{font:700 .72rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.08em;padding:.68rem .8rem;text-transform:uppercase}.tabs button.active{border-color:var(--a);background:linear-gradient(180deg,rgba(18,44,67,.95),rgba(7,15,24,.96));box-shadow:inset 0 0 0 1px rgba(143,231,255,.08),0 0 22px rgba(88,170,255,.14)}
.sheet{display:none}.sheet.active{display:block;animation:sheet .22s ease}@keyframes sheet{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}.grid{display:grid;grid-template-columns:repeat(12,1fr);gap:var(--gap)}.card{grid-column:span 6;padding:16px;border:1px solid rgba(105,177,255,.18);border-radius:6px;background:linear-gradient(180deg,rgba(9,17,27,.92),rgba(5,10,16,.96));box-shadow:0 0 26px rgba(40,99,227,.08),inset 0 0 0 1px rgba(255,255,255,.02);position:relative;overflow:hidden}.card.full{grid-column:1/-1}.card:before{content:"";position:absolute;left:0;right:0;top:0;height:2px;background:linear-gradient(90deg,transparent,rgba(143,231,255,.42),transparent);opacity:.55}.card h3{margin:0 0 12px;color:var(--a);font:750 .76rem/1.2 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.16em;text-transform:uppercase}.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.field.full{grid-column:1/-1}
#editor.view-mode input,#editor.view-mode textarea{border-color:transparent;background:transparent;box-shadow:none;padding-left:0;padding-right:0;color:var(--text);cursor:text}#editor.view-mode textarea{resize:none;overflow:hidden}#editor.view-mode .field{padding:10px 12px;border:1px solid rgba(106,178,255,.12);border-radius:4px;background:linear-gradient(180deg,rgba(4,10,16,.36),rgba(4,10,16,.18))}#editor.view-mode label{color:color-mix(in srgb,var(--a) 72%,var(--muted))}#editor.edit-mode .card{box-shadow:0 0 26px rgba(95,115,255,.08),inset 0 0 0 1px rgba(255,255,255,.02)}

/* Continuous border doodles: the decoration is literally drawn out of the System frame line. */
.border-doodles{position:absolute;inset:0;z-index:3;pointer-events:none;overflow:visible;color:var(--a)}
.border-doodles .doodle{position:absolute;overflow:visible;filter:drop-shadow(0 0 5px currentColor) drop-shadow(0 0 14px color-mix(in srgb,var(--a) 35%,transparent));opacity:.98}
.border-doodles .doodle path,.border-doodles .doodle polyline,.border-doodles .doodle circle,.border-doodles .doodle ellipse{fill:none;stroke:currentColor;stroke-width:2.1;stroke-linecap:round;stroke-linejoin:round;vector-effect:non-scaling-stroke}
.border-doodles .accent{color:color-mix(in srgb,var(--b) 78%,var(--a))}
.border-doodles .signal{color:color-mix(in srgb,var(--c) 80%,white 5%)}
.border-doodles .top-left{width:320px;height:105px;left:44px;top:-82px}
.border-doodles .top-right{width:280px;height:92px;right:44px;top:-68px}
.border-doodles .side-left{width:94px;height:230px;left:-80px;top:155px}
.border-doodles .side-right{width:94px;height:230px;right:-80px;top:185px}
.border-doodles .bottom-left{width:275px;height:90px;left:58px;bottom:-69px}
.border-doodles .bottom-right{width:265px;height:86px;right:58px;bottom:-65px}
.border-doodles .alien-crown{display:none;position:absolute;width:min(520px,48vw);height:128px;left:50%;top:-106px;transform:translateX(-50%);overflow:visible;filter:drop-shadow(0 0 6px color-mix(in srgb,var(--a) 75%,white 5%)) drop-shadow(0 0 20px color-mix(in srgb,var(--b) 28%,transparent));color:color-mix(in srgb,var(--a) 82%,var(--b) 18%)}
.border-doodles .alien-crown path,.border-doodles .alien-crown circle{fill:none;stroke:currentColor;stroke-width:2.15;stroke-linecap:round;stroke-linejoin:round;vector-effect:non-scaling-stroke}
html[data-character-style="alien"] .border-doodles .alien-crown{display:block;animation:doodleGlow 5.6s ease-in-out infinite}
html[data-character-style="alien"] #editor:after{background:radial-gradient(circle at 14% 7%,rgba(134,243,239,.12),transparent 24%),radial-gradient(circle at 84% 10%,rgba(255,171,201,.10),transparent 20%),radial-gradient(circle at 50% 2%,rgba(174,247,215,.08),transparent 20%),linear-gradient(180deg,rgba(255,255,255,.025),transparent 18%)}
html[data-character-style="alien"] #editor{box-shadow:0 0 54px rgba(134,243,239,.15),0 0 116px rgba(255,171,201,.09),inset 0 0 0 1px rgba(255,255,255,.03)}

.border-doodles .motif{display:none}
html[data-character-style="holo"] .border-doodles .m-holo,
html[data-character-style="alien"] .border-doodles .m-alien,
html[data-character-style="abyssal"] .border-doodles .m-abyssal,
html[data-character-style="divine"] .border-doodles .m-divine,
html[data-character-style="cute"] .border-doodles .m-cute,
html[data-character-style="glitch"] .border-doodles .m-glitch{display:block}
.border-doodles .motif{animation:doodleGlow 4.8s ease-in-out infinite}
.border-doodles .top-right,.border-doodles .side-right,.border-doodles .bottom-left{animation-delay:-1.8s}
@keyframes doodleGlow{0%,100%{opacity:.82;filter:brightness(.92)}50%{opacity:1;filter:brightness(1.18)}}
html[data-character-style="alien"] .border-doodles{filter:drop-shadow(0 0 13px rgba(134,243,239,.13)) drop-shadow(0 0 24px rgba(255,171,201,.08))}
html[data-character-style="abyssal"] .border-doodles{filter:drop-shadow(0 0 14px rgba(157,140,255,.14)) drop-shadow(0 0 28px rgba(215,190,122,.07))}
html[data-character-style="divine"] .border-doodles{filter:drop-shadow(0 0 13px rgba(181,240,220,.12)) drop-shadow(0 0 30px rgba(239,213,141,.08))}
html[data-character-style="cute"] .border-doodles{filter:drop-shadow(0 0 12px rgba(255,156,200,.12)) drop-shadow(0 0 26px rgba(127,233,255,.08))}
html[data-character-style="glitch"] .border-doodles .motif{animation:doodleGlitch 2.3s steps(2,end) infinite}
@keyframes doodleGlitch{0%,100%{transform:translate(0,0);opacity:.88}42%{transform:translate(1px,0);opacity:1}45%{transform:translate(-1px,1px);opacity:.72}48%{transform:translate(0,0);opacity:1}}
@media(max-width:700px){
  .border-doodles .top-left{width:230px;left:24px;top:-78px}.border-doodles .top-right{width:205px;right:22px;top:-65px}
  .border-doodles .side-left{left:-76px;top:180px}.border-doodles .side-right{right:-76px;top:205px}
  .border-doodles .bottom-left{width:205px;left:26px}.border-doodles .bottom-right{width:205px;right:24px}.border-doodles .alien-crown{width:300px;top:-104px}
}
.modal{position:fixed;inset:0;display:none;place-items:center;padding:18px;background:rgba(0,0,0,.7);backdrop-filter:blur(10px);z-index:50}.modal.open{display:grid}.panel{width:min(900px,100%);max-height:90vh;overflow:auto;padding:18px;border:1px solid rgba(109,183,255,.24);border-radius:10px;background:linear-gradient(180deg,rgba(6,13,21,.97),rgba(4,9,15,.98));box-shadow:0 30px 80px rgba(0,0,0,.55),0 0 38px rgba(44,110,255,.12)}.panelhead{display:flex;justify-content:space-between;gap:12px;align-items:center}.panel h2{margin:0}.note{margin:12px 0;padding:10px 12px;border:1px solid rgba(106,178,255,.16);border-radius:6px;background:rgba(5,11,18,.7);color:var(--muted);font-size:.78rem}.note b{color:var(--a)}
.themegrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(145px,1fr));gap:10px;margin:12px 0 18px}.theme{position:relative;min-height:108px;text-align:left;padding:12px;overflow:hidden;background:linear-gradient(145deg,rgba(10,20,31,.96),rgba(4,9,15,.98));border-radius:6px}.theme:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 90% 10%,color-mix(in srgb,var(--s2) 30%,transparent),transparent 48%),linear-gradient(135deg,color-mix(in srgb,var(--s1) 11%,transparent),transparent 60%);pointer-events:none}.theme.active{border-color:var(--s1);box-shadow:0 0 0 1px color-mix(in srgb,var(--s1) 55%,transparent),0 0 18px color-mix(in srgb,var(--s1) 16%,transparent)}.theme.active:after{content:"ACTIVE";position:absolute;right:8px;bottom:7px;color:var(--s1);font:700 .54rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em}.glyph{position:relative;display:grid;place-items:center;width:34px;height:34px;margin-bottom:8px;border:1px solid color-mix(in srgb,var(--s1) 65%,transparent);border-radius:8px;color:var(--s1);background:color-mix(in srgb,var(--s1) 7%,transparent);font-size:1.15rem}.tname{position:relative;display:block;font-weight:800}.tdesc{position:relative;display:block;margin-top:3px;color:var(--muted);font-size:.68rem}.setting{display:grid;grid-template-columns:1fr minmax(180px,260px);gap:12px;align-items:center;padding:11px 0;border-top:1px solid rgba(106,178,255,.13)}.setting small{display:block;color:var(--muted)}.toggle{display:flex;justify-content:flex-end;gap:8px;align-items:center}.toggle input{width:20px;height:20px}
.burst{position:fixed;pointer-events:none;z-index:100;font-size:22px;font-weight:900;animation:burst .6s ease-out forwards;text-shadow:0 0 16px currentColor}@keyframes burst{0%{opacity:0;transform:translate(-50%,-20%) scale(.6)}20%{opacity:1}100%{opacity:0;transform:translate(-50%,-100%) scale(1.35)}}html[data-reduce="1"] *{animation:none!important;transition:none!important}
@media(max-width:900px){.app{grid-template-columns:1fr}aside{position:fixed;z-index:40;left:0;top:0;bottom:0;width:min(86vw,320px);transform:translateX(-105%);transition:.2s}aside.open{transform:none}main{padding:14px}.mobile{display:flex;gap:8px;margin-bottom:12px}.systembar{font-size:.58rem;flex-wrap:wrap}.systembar #systemPersonalization{order:3;width:100%;text-align:left}#editor,.empty{max-width:none}.card{grid-column:1/-1}}
@media(max-width:560px){.fields,.setting{grid-template-columns:1fr}.top{flex-direction:column}.tabs{display:grid}.record-actions{justify-content:flex-start}}

/* v3.2 polish */
:root{--ease:cubic-bezier(.2,.8,.2,1)}
html{scroll-behavior:smooth}
button,input,textarea,select,.card,.theme,.char{transition:border-color .18s var(--ease),box-shadow .18s var(--ease),background .18s var(--ease),transform .16s var(--ease),opacity .18s var(--ease)}
button:focus-visible,input:focus-visible,textarea:focus-visible,select:focus-visible{outline:2px solid color-mix(in srgb,var(--a) 75%,white 10%);outline-offset:2px}
#editor{
  background:
    linear-gradient(var(--a),var(--a)) left 10px top 10px/34px 2px no-repeat,
    linear-gradient(var(--a),var(--a)) left 10px top 10px/2px 34px no-repeat,
    linear-gradient(var(--a),var(--a)) right 10px top 10px/34px 2px no-repeat,
    linear-gradient(var(--a),var(--a)) right 10px top 10px/2px 34px no-repeat,
    linear-gradient(var(--a),var(--a)) left 10px bottom 10px/34px 2px no-repeat,
    linear-gradient(var(--a),var(--a)) left 10px bottom 10px/2px 34px no-repeat,
    linear-gradient(var(--a),var(--a)) right 10px bottom 10px/34px 2px no-repeat,
    linear-gradient(var(--a),var(--a)) right 10px bottom 10px/2px 34px no-repeat,
    linear-gradient(180deg,rgba(5,11,18,.88),rgba(4,9,15,.96));
}
#editor:before{inset:15px;border-color:color-mix(in srgb,var(--a) 18%,transparent)}
#editor.view-mode .field{min-height:68px;display:flex;flex-direction:column;justify-content:center}
#editor.view-mode input,#editor.view-mode textarea{font-weight:650;letter-spacing:.01em}
#editor.view-mode input::placeholder,#editor.view-mode textarea::placeholder{color:rgba(180,205,230,.45);opacity:1;font-style:italic}
.card{
  background:
    linear-gradient(var(--a),var(--a)) left 7px top 7px/20px 1px no-repeat,
    linear-gradient(var(--a),var(--a)) left 7px top 7px/1px 20px no-repeat,
    linear-gradient(var(--a),var(--a)) right 7px bottom 7px/20px 1px no-repeat,
    linear-gradient(var(--a),var(--a)) right 7px bottom 7px/1px 20px no-repeat,
    linear-gradient(180deg,rgba(9,17,27,.93),rgba(5,10,16,.97));
}
.card:hover{border-color:color-mix(in srgb,var(--a) 32%,var(--line));box-shadow:0 0 30px color-mix(in srgb,var(--a) 8%,transparent),inset 0 0 0 1px rgba(255,255,255,.025)}
.top h2{color:#f7fbff}.top h2:before{content:"STATUS // ";color:var(--a);font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.14em;display:block;margin-bottom:6px;text-shadow:0 0 14px color-mix(in srgb,var(--a) 25%,transparent)}
.tabs{padding-bottom:2px}
.tabs button{position:relative;overflow:hidden}
.tabs button.active:after{content:"";position:absolute;left:12%;right:12%;bottom:0;height:1px;background:var(--a);box-shadow:0 0 10px var(--a)}
.systembar{backdrop-filter:blur(10px)}
#save{min-width:104px;text-align:right}
#save.saving{color:var(--a)}
#save.warn{color:#ffd27f}
#recordAction{font-weight:800;letter-spacing:.05em}
.sidebar-backdrop{display:none}
.toast{position:fixed;right:20px;bottom:20px;z-index:120;max-width:min(360px,calc(100vw - 40px));padding:11px 14px;border:1px solid color-mix(in srgb,var(--a) 38%,var(--line));border-radius:7px;background:rgba(5,12,20,.94);backdrop-filter:blur(12px);color:var(--text);box-shadow:0 18px 50px rgba(0,0,0,.4),0 0 24px color-mix(in srgb,var(--a) 10%,transparent);font:.74rem/1.35 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.04em;animation:toastIn .22s var(--ease)}
@keyframes toastIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
@media(max-width:900px){
  .sidebar-backdrop{position:fixed;inset:0;z-index:35;background:rgba(0,0,0,.54);backdrop-filter:blur(3px)}
  .sidebar-backdrop.open{display:block}
  aside{box-shadow:16px 0 50px rgba(0,0,0,.48),inset -1px 0 0 rgba(126,223,255,.08)}
  #editor{padding:22px 16px 18px}
}
@media(max-width:560px){
  #editor:before{inset:10px}
  .record-actions{gap:6px}
  #recordAction{width:100%}
  .mode-pill,#save{font-size:.54rem}
}


/* ===== v4.0: character systems, archive index, display mode ===== */
#homeBtn{width:100%;margin:0 0 10px;font-weight:800;letter-spacing:.05em}
.home-screen{max-width:1180px;width:100%;margin:0 auto;position:relative;z-index:1}
.home-head{display:flex;justify-content:space-between;gap:16px;align-items:end;margin:4px 0 18px;padding:0 2px 12px;border-bottom:1px solid rgba(106,178,255,.14)}
.home-head h2{margin:0;font-size:1.55rem;letter-spacing:.04em}.home-head p{margin:.35rem 0 0;color:var(--muted)}
.archive-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(230px,1fr));gap:14px}
.archive-card{position:relative;min-height:190px;text-align:left;padding:16px;border:1px solid rgba(105,177,255,.18);border-radius:7px;background:linear-gradient(145deg,rgba(9,18,29,.95),rgba(4,9,15,.97));overflow:hidden;box-shadow:0 0 24px rgba(37,91,210,.07)}
.archive-card:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 88% 8%,color-mix(in srgb,var(--card2) 24%,transparent),transparent 42%),linear-gradient(135deg,color-mix(in srgb,var(--card1) 9%,transparent),transparent 58%);pointer-events:none}
.archive-card:hover{transform:translateY(-2px);border-color:var(--card1);box-shadow:0 12px 34px rgba(0,0,0,.26),0 0 26px color-mix(in srgb,var(--card1) 13%,transparent)}
.archive-glyph{position:relative;width:42px;height:42px;display:grid;place-items:center;margin-bottom:24px;border:1px solid color-mix(in srgb,var(--card1) 65%,transparent);border-radius:10px;color:var(--card1);font-size:1.35rem;background:color-mix(in srgb,var(--card1) 7%,transparent);box-shadow:0 0 22px color-mix(in srgb,var(--card1) 15%,transparent)}
.archive-name{position:relative;display:block;font-size:1.05rem;font-weight:850}.archive-alias{position:relative;display:block;margin-top:3px;color:var(--muted);font-size:.76rem}.archive-meta{position:relative;display:flex;gap:6px;flex-wrap:wrap;margin-top:12px}.mini-badge{padding:3px 7px;border:1px solid rgba(126,196,255,.16);border-radius:999px;background:rgba(5,11,18,.5);color:#dcecff;font:700 .58rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.06em;text-transform:uppercase}.theme-signature{position:absolute;right:12px;top:12px;display:flex;gap:3px}.theme-signature i{display:block;width:7px;height:20px;border-radius:999px;box-shadow:0 0 9px currentColor}
.profile-hero{position:relative;z-index:1;display:grid;grid-template-columns:92px minmax(0,1fr);gap:16px;margin:0 0 18px;padding:14px;border:1px solid rgba(106,178,255,.17);border-radius:7px;background:linear-gradient(120deg,rgba(8,18,29,.92),rgba(4,10,17,.82));overflow:hidden}
.profile-hero:after{content:"";position:absolute;inset:0;background:radial-gradient(circle at 90% 0,color-mix(in srgb,var(--a) 10%,transparent),transparent 40%);pointer-events:none}
.portrait{position:relative;width:92px;height:112px;border:1px solid color-mix(in srgb,var(--a) 35%,var(--line));border-radius:6px;background:linear-gradient(160deg,color-mix(in srgb,var(--a) 8%,#07101a),#03070d);display:grid;place-items:center;overflow:hidden;box-shadow:inset 0 0 25px color-mix(in srgb,var(--a) 7%,transparent)}
.portrait img{width:100%;height:100%;object-fit:cover}.portrait span{font-size:2rem;color:var(--a);text-shadow:0 0 18px color-mix(in srgb,var(--a) 50%,transparent)}
.hero-info{position:relative;z-index:1;min-width:0}.hero-kicker{color:var(--a);font:700 .62rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.16em;text-transform:uppercase}.hero-name{font-size:1.4rem;font-weight:900;letter-spacing:.035em;margin:4px 0 2px}.hero-alias{color:var(--muted);font-size:.82rem}.hero-chips,.status-chips{display:flex;gap:6px;flex-wrap:wrap;margin-top:10px}.hero-chip,.status-chip{padding:4px 8px;border:1px solid color-mix(in srgb,var(--a) 23%,var(--line));border-radius:999px;background:rgba(4,10,16,.56);font:700 .61rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.055em;text-transform:uppercase}.hero-chip.alert{border-color:rgba(255,110,150,.42);color:#ffb3c7}.status-chip{color:var(--c)}
.view-grid{display:grid}.edit-grid{display:none}#editor.edit-mode .view-grid{display:none}#editor.edit-mode .edit-grid{display:grid}#editor.view-mode .view-grid{display:grid}#editor.view-mode .edit-grid{display:none}
.view-card{grid-column:span 6}.view-card.full{grid-column:1/-1}.readout-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.readout{min-height:66px;padding:10px 12px;border:1px solid rgba(106,178,255,.11);border-radius:4px;background:rgba(4,10,16,.29)}.readout.full{grid-column:1/-1}.readout-label{display:block;color:color-mix(in srgb,var(--a) 70%,var(--muted));font:700 .64rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.11em;text-transform:uppercase;margin-bottom:6px}.readout-value{display:block;color:var(--text);font-weight:650;white-space:pre-wrap;overflow-wrap:anywhere}.readout-value.blank-value{min-height:0;border:0;background:none;display:block;color:rgba(178,203,227,.46);font-style:italic;text-align:left;box-shadow:none}.stat-line{display:grid;grid-template-columns:minmax(85px,.7fr) minmax(90px,1.7fr) auto;gap:10px;align-items:center;padding:8px 0;border-bottom:1px solid rgba(106,178,255,.08)}.stat-line:last-child{border-bottom:0}.stat-name{font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;color:color-mix(in srgb,var(--a) 70%,var(--muted));letter-spacing:.08em;text-transform:uppercase}.stat-track{height:5px;background:rgba(94,145,190,.12);border-radius:99px;overflow:hidden}.stat-fill{height:100%;background:linear-gradient(90deg,var(--a),var(--b));box-shadow:0 0 10px color-mix(in srgb,var(--a) 45%,transparent)}.stat-value{font:800 .74rem ui-monospace,SFMono-Regular,Menlo,monospace;color:var(--text)}
.relationship-list{display:grid;gap:7px}.relationship-row{display:flex;justify-content:space-between;gap:12px;padding:8px 10px;border:1px solid rgba(106,178,255,.1);border-radius:4px;background:rgba(4,10,16,.26)}.relationship-row b{color:var(--text)}.relationship-row span{color:var(--muted);text-align:right}.watch-alert{border-color:rgba(255,112,150,.28)!important;box-shadow:inset 2px 0 0 rgba(255,112,150,.55)}
.theme-shell{position:relative;z-index:1;display:grid;grid-template-columns:minmax(220px,.8fr) minmax(300px,1.2fr);gap:16px}.theme-preview{min-height:300px;padding:18px;border:1px solid color-mix(in srgb,var(--a) 34%,var(--line));border-radius:8px;background:radial-gradient(circle at 50% 0,color-mix(in srgb,var(--b) 18%,transparent),transparent 42%),linear-gradient(180deg,rgba(5,12,20,.94),rgba(3,8,14,.98));box-shadow:0 0 32px color-mix(in srgb,var(--a) 10%,transparent),inset 0 0 0 1px rgba(255,255,255,.02);display:flex;flex-direction:column;justify-content:space-between;overflow:hidden}.preview-glyph{font-size:3rem;color:var(--a);text-shadow:0 0 24px color-mix(in srgb,var(--a) 48%,transparent)}.preview-title{font-weight:900;font-size:1.3rem;letter-spacing:.06em}.preview-sub{color:var(--muted);font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em;text-transform:uppercase}.preview-swatches{display:flex;gap:7px}.preview-swatches i{width:30px;height:7px;border-radius:999px;box-shadow:0 0 12px currentColor}.theme-controls{display:grid;gap:12px}.theme-controls .card{grid-column:auto}.color-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}.color-control input[type=color]{height:44px;padding:4px}.theme-actions{display:flex;gap:8px;flex-wrap:wrap}.theme-actions button{flex:1}.portrait-actions{display:flex;gap:8px;flex-wrap:wrap}.portrait-actions button{flex:1}.character-theme-note{color:var(--muted);font-size:.76rem;line-height:1.45}
.custom-editor{position:relative;z-index:1}.custom-list{display:grid;gap:10px}.custom-row{display:grid;grid-template-columns:150px 1fr 1.4fr auto;gap:8px;align-items:start;padding:10px;border:1px solid rgba(106,178,255,.12);border-radius:6px;background:rgba(4,10,16,.35)}.custom-row button{padding:.7rem}.custom-empty{padding:24px;text-align:center;color:var(--muted);border:1px dashed rgba(106,178,255,.17);border-radius:6px}
html[data-character-style="alien"] body:after{background-size:52px 52px;background-image:radial-gradient(circle,rgba(123,239,229,.08) 1px,transparent 1px),linear-gradient(rgba(105,180,255,.035) 1px,transparent 1px);}
html[data-character-style="abyssal"] body{background:radial-gradient(circle at 65% -10%,rgba(108,76,196,.16),transparent 34%),linear-gradient(180deg,#04050a,#080810 50%,#030408)}
html[data-character-style="divine"] body:after{background-size:70px 70px;background-image:radial-gradient(circle at center,rgba(213,196,126,.06) 0 1px,transparent 2px),linear-gradient(90deg,rgba(144,235,199,.035) 1px,transparent 1px)}
html[data-character-style="cute"] #editor,html[data-character-style="cute"] .card{border-radius:12px}
html[data-character-style="glitch"] body:before{background:repeating-linear-gradient(180deg,rgba(98,239,255,.018) 0 1px,transparent 1px 3px),repeating-linear-gradient(90deg,transparent 0 98px,rgba(255,93,177,.025) 98px 99px)}



#editor[data-module="authority"] .card{border-radius:2px;background:linear-gradient(180deg,rgba(8,16,25,.96),rgba(5,9,14,.98))}#editor[data-module="authority"] .card h3{color:color-mix(in srgb,var(--a) 74%,#dbeaff)}#editor[data-module="authority"] .readout{border-radius:2px}
#editor[data-module="personal"] .card{border-radius:9px}#editor[data-module="personal"] .readout{border-radius:7px}#editor[data-module="personal"] .card:before{opacity:.28}
@media(max-width:800px){.theme-shell{grid-template-columns:1fr}.profile-hero{grid-template-columns:78px minmax(0,1fr)}.portrait{width:78px;height:98px}.custom-row{grid-template-columns:1fr}.archive-grid{grid-template-columns:repeat(auto-fill,minmax(190px,1fr))}}
@media(max-width:560px){.readout-grid{grid-template-columns:1fr}.readout.full{grid-column:auto}.profile-hero{grid-template-columns:64px minmax(0,1fr);padding:11px;gap:11px}.portrait{width:64px;height:82px}.hero-name{font-size:1.15rem}.color-row{grid-template-columns:1fr}.archive-grid{grid-template-columns:1fr}}

</style>
</head>
<body>
<div id="sideBackdrop" class="sidebar-backdrop"></div>
<div class="app">
<aside id="side">
<div class="brand"><img id="logo" alt="Class Unknown"><div><h1>CLASS UNKNOWN</h1><small>Character Database</small></div></div>
<button id="homeBtn">⌂ ARCHIVE HOME</button>
<div class="row"><button id="new">＋ New</button><button id="dup">Duplicate</button></div>
<input id="search" placeholder="Search characters…">
<div id="charList"></div>
<div class="sidefoot">
<button id="exp">Download Character</button>
<button id="expAll">Download All</button>
<button id="imp">Upload File</button><input id="file" type="file" accept=".json,application/json" hidden>
<button id="settings">⚙ Personalization</button>
<button id="del" class="danger">Delete Character</button>
<small id="storageNote" class="muted">Autosaves in this browser.</small>
</div>
</aside>

<main>
<div class="systembar"><span>◈ CLASS UNKNOWN // SYSTEM ARCHIVE</span><span id="systemPersonalization">PERSONALIZATION: ARCHIVE BLUE</span><span class="online">● LINK STABLE</span></div>
<div class="mobile"><button id="menu">☰ Characters</button><button id="msettings">⚙ Personalization</button></div>

<section id="homeScreen" class="home-screen" hidden>
<div class="home-head"><div><h2>Character Archive</h2><p>Select a record to open that character’s System interface and personal theme.</p></div><button id="homeNew">＋ New Record</button></div>
<div id="archiveGrid" class="archive-grid"></div>
</section>
<div id="empty" class="empty"><div><b>No archive file selected.</b><br>Create a new record or import a saved profile.</div></div>

<div id="editor" data-module="system" hidden>
<div class="border-doodles" aria-hidden="true">
  <svg class="alien-crown" viewBox="0 0 520 128" preserveAspectRatio="xMidYMid meet">
    <path d="M0 106 H150 C170 106 183 102 197 92 C211 82 220 69 220 54 C220 38 210 28 197 29 C184 30 174 42 178 55 C184 73 206 88 260 106 C314 88 336 73 342 55 C346 42 336 30 323 29 C310 28 300 38 300 54 C300 69 309 82 323 92 C337 102 350 106 370 106 H520"/>
    <path class="accent" d="M198 90 C214 74 232 59 260 40 C288 59 306 74 322 90" opacity=".6"/>
    <path class="signal" d="M94 105 C102 93 109 85 117 79 M117 79 C123 89 130 96 142 102" opacity=".75"/>
    <circle class="signal" cx="382" cy="104" r="2.4"/><circle class="accent" cx="395" cy="104" r="1.7"/><circle class="signal" cx="408" cy="104" r="1.3"/>
  </svg>
  <svg class="doodle top-left" viewBox="0 0 320 105" preserveAspectRatio="xMidYMid meet">
    <g class="motif m-alien">
      <path d="M0 82 H42 C58 82 70 75 78 63 C86 50 88 36 84 24 C102 31 113 44 113 58 C113 72 103 81 88 82 H320"/>
      <ellipse class="accent" cx="84" cy="55" rx="31" ry="11" transform="rotate(-14 84 55)"/>
      <circle class="signal" cx="84" cy="55" r="18"/>
      <path class="signal" d="M129 35 C132 45 138 51 148 54 C138 57 132 63 129 73 C126 63 120 57 110 54 C120 51 126 45 129 35"/>
      <circle class="accent" cx="160" cy="70" r="2"/><circle class="signal" cx="171" cy="70" r="1.4"/><circle class="accent" cx="181" cy="70" r="1.1"/>
    </g>
    <g class="motif m-cute"><path d="M0 82 H58 C71 82 78 74 77 61 C76 49 68 38 57 38 C47 38 41 47 44 57 C48 69 61 78 77 82 C92 72 104 63 113 51 C120 41 137 41 143 53 C150 67 135 77 116 82 H320"/><path class="accent" d="M167 64 C172 54 186 54 191 64 C196 54 210 54 215 64 C220 76 205 84 191 92 C177 84 162 76 167 64"/></g>
    <g class="motif m-holo"><path d="M0 82 H76 L88 70 L100 82 L112 70 L124 82 H188 L200 74 L212 82 H320"/><polyline class="signal" points="150,82 160,64 170,82 180,64 190,82"/></g>
    <g class="motif m-abyssal"><path d="M0 82 H70 C83 82 91 75 94 64 C98 48 88 35 73 35 C89 24 109 26 119 40 C132 59 119 76 97 82 H180 C195 82 205 74 209 62 C214 47 207 36 195 30 C215 30 229 42 228 58 C227 72 214 81 196 82 H320"/><path class="signal" d="M145 82 L154 66 L163 82 L154 98 Z"/></g>
    <g class="motif m-divine"><path d="M0 82 H72 C84 82 92 74 92 63 C92 52 84 44 74 44 C83 35 95 34 103 42 C111 34 123 35 132 44 C122 44 114 52 114 63 C114 74 122 82 134 82 H320"/><path class="signal" d="M103 25 C106 36 114 44 125 47 C114 50 106 58 103 69 C100 58 92 50 81 47 C92 44 100 36 103 25"/></g>
    <g class="motif m-glitch"><path d="M0 82 H72 V70 H92 V82 H118 V60 H140 V82 H172 V74 H196 V82 H320"/><polyline class="accent" points="106,82 106,48 118,48 118,58 128,58"/></g>
  </svg>

  <svg class="doodle top-right accent" viewBox="0 0 280 92">
    <g class="motif m-alien">
      <path d="M0 69 H92 C110 69 122 61 128 48 C134 35 132 24 124 17 C140 19 151 30 152 43 C153 57 143 67 128 69 H280"/>
      <ellipse class="accent" cx="191" cy="52" rx="27" ry="8"/>
      <path class="signal" d="M170 52 C173 38 181 31 191 31 C201 31 209 38 212 52"/>
      <circle class="signal" cx="184" cy="44" r="1.8"/><circle class="signal" cx="198" cy="44" r="1.8"/>
      <path class="signal" d="M191 31 V21 M191 21 C195 17 198 18 200 21"/>
      <path class="accent" d="M229 34 C234 26 244 27 246 35 C249 27 259 26 264 34 C268 43 257 49 246 56 C235 49 225 43 229 34"/>
    </g>
    <g class="motif m-cute"><path d="M0 69 H86 C96 69 102 63 102 54 C102 45 96 38 87 38 C95 30 106 30 114 38 C122 30 133 30 141 38 C132 38 126 45 126 54 C126 63 132 69 142 69 H280"/></g>
    <g class="motif m-holo"><path d="M0 69 H84 L96 57 L108 69 L120 57 L132 69 H280"/></g>
    <g class="motif m-abyssal"><path d="M0 69 H94 C109 69 120 59 120 45 C120 34 114 26 103 21 C119 18 135 27 140 41 C146 56 135 68 118 69 H280"/><path class="signal" d="M170 69 L180 53 L190 69 L180 85 Z"/></g>
    <g class="motif m-divine"><path d="M0 69 H102 C114 69 122 61 122 50 C122 39 114 31 103 31 C114 22 129 24 137 35 C145 46 140 60 128 66 C125 68 121 69 117 69 H280"/><circle class="signal" cx="170" cy="49" r="8"/><path class="signal" d="M170 30 V68 M151 49 H189"/></g>
    <g class="motif m-glitch"><path d="M0 69 H72 V58 H95 V69 H116 V49 H137 V69 H162 V60 H184 V69 H280"/></g>
  </svg>

  <svg class="doodle side-left" viewBox="0 0 94 230">
    <g class="motif m-alien">
      <path d="M80 0 V60 C80 72 74 80 63 84 C51 88 40 84 35 74 C33 84 26 92 16 96 C26 100 33 108 35 118 C40 108 51 104 63 108 C74 112 80 120 80 132 V230"/>
      <circle class="accent" cx="29" cy="54" r="1.8"/><circle class="signal" cx="18" cy="66" r="1.3"/><circle class="accent" cx="42" cy="45" r="1.1"/>
      <path class="signal" d="M25 144 C28 153 34 159 43 162 C34 165 28 171 25 180 C22 171 16 165 7 162 C16 159 22 153 25 144"/>
    </g>
    <g class="motif m-cute"><path d="M80 0 V65 C80 74 73 80 64 80 C55 80 49 73 49 65 C41 72 34 80 34 90 C34 100 41 108 49 115 C49 106 55 99 64 99 C73 99 80 106 80 115 V230"/></g>
    <g class="motif m-holo"><path d="M80 0 V62 L68 74 L80 86 L68 98 L80 110 V230"/></g>
    <g class="motif m-abyssal"><path d="M80 0 V66 C80 78 72 85 61 85 C49 85 41 77 41 66 C30 72 23 83 23 95 C23 107 30 118 41 124 C41 113 49 105 61 105 C72 105 80 112 80 124 V230"/></g>
    <g class="motif m-divine"><path d="M80 0 V68 C80 78 73 85 63 85 C53 85 46 78 46 68 C46 78 39 85 29 85 C39 85 46 92 46 102 C46 112 53 119 63 119 C73 119 80 126 80 136 V230"/></g>
    <g class="motif m-glitch"><path d="M80 0 V58 H67 V82 H80 V104 H58 V126 H80 V230"/></g>
  </svg>

  <svg class="doodle side-right signal" viewBox="0 0 94 230">
    <g class="motif m-alien">
      <path d="M14 0 V58 C14 70 20 77 31 81 C44 86 56 81 61 70 C66 81 78 86 91 81 C78 88 69 99 66 112 C63 126 69 137 80 144 C66 143 55 149 49 160 C43 171 45 183 54 192 C41 187 29 190 20 199 C16 203 14 210 14 220 V230"/>
      <ellipse class="accent" cx="57" cy="111" rx="28" ry="11" transform="rotate(-24 57 111)"/>
      <circle class="signal" cx="57" cy="111" r="3.2"/>
      <circle class="accent" cx="83" cy="95" r="2"/><circle class="signal" cx="31" cy="130" r="1.5"/>
    </g>
    <g class="motif m-cute"><path d="M14 0 V73 C14 82 21 88 30 88 C39 88 45 81 45 73 C53 80 60 88 60 98 C60 108 53 116 45 123 C45 114 39 107 30 107 C21 107 14 114 14 123 V230"/></g>
    <g class="motif m-holo"><path d="M14 0 V62 L26 74 L14 86 L26 98 L14 110 V230"/></g>
    <g class="motif m-abyssal"><path d="M14 0 V66 C14 78 22 85 33 85 C45 85 53 77 53 66 C64 72 71 83 71 95 C71 107 64 118 53 124 C53 113 45 105 33 105 C22 105 14 112 14 124 V230"/></g>
    <g class="motif m-divine"><path d="M14 0 V68 C14 78 21 85 31 85 C41 85 48 78 48 68 C48 78 55 85 65 85 C55 85 48 92 48 102 C48 112 41 119 31 119 C21 119 14 126 14 136 V230"/></g>
    <g class="motif m-glitch"><path d="M14 0 V58 H27 V82 H14 V104 H36 V126 H14 V230"/></g>
  </svg>

  <svg class="doodle bottom-left signal" viewBox="0 0 275 90">
    <g class="motif m-alien">
      <path d="M0 18 H66 C78 18 86 24 90 34 C94 45 90 55 81 60 C93 63 102 71 106 83 C110 71 119 63 131 60 C122 55 118 45 122 34 C126 24 134 18 146 18 H275"/>
      <path class="accent" d="M165 18 C171 10 180 10 187 18 C180 26 171 26 165 18 Z"/>
      <circle class="signal" cx="201" cy="18" r="6"/><path class="accent" d="M220 12 C226 14 229 20 227 25 C221 24 217 18 220 12 Z"/>
      <circle class="signal" cx="242" cy="18" r="2.2"/><circle class="accent" cx="254" cy="18" r="1.4"/>
    </g>
    <g class="motif m-cute"><path d="M0 18 H74 C85 18 92 24 92 34 C92 44 85 51 75 51 C83 58 91 66 98 76 C105 66 113 58 121 51 C111 51 104 44 104 34 C104 24 111 18 122 18 H275"/></g>
    <g class="motif m-holo"><path d="M0 18 H82 L94 30 L106 18 L118 30 L130 18 H275"/></g>
    <g class="motif m-abyssal"><path d="M0 18 H90 C104 18 113 28 113 41 C113 51 107 59 98 63 C112 66 122 75 126 88 C130 75 140 66 154 63 C145 59 139 51 139 41 C139 28 148 18 162 18 H275"/></g>
    <g class="motif m-divine"><path d="M0 18 H86 C97 18 104 25 104 35 C104 45 97 52 87 52 C97 52 104 59 104 69 C104 59 111 52 121 52 C131 52 138 45 138 35 C138 25 145 18 156 18 H275"/></g>
    <g class="motif m-glitch"><path d="M0 18 H70 V30 H94 V18 H116 V40 H140 V18 H164 V28 H188 V18 H275"/></g>
  </svg>

  <svg class="doodle bottom-right accent" viewBox="0 0 265 86">
    <g class="motif m-alien">
      <path d="M0 18 H82 C94 18 102 24 106 34 C110 45 106 54 97 59 C108 62 117 69 121 80 C125 69 134 62 145 59 C136 54 132 45 136 34 C140 24 148 18 160 18 H265"/>
      <circle class="signal" cx="187" cy="44" r="15"/>
      <ellipse class="accent" cx="187" cy="44" rx="27" ry="8" transform="rotate(-18 187 44)"/>
      <path class="signal" d="M226 28 C229 37 235 43 244 46 C235 49 229 55 226 64 C223 55 217 49 208 46 C217 43 223 37 226 28"/>
    </g>
    <g class="motif m-cute"><path d="M0 18 H92 C103 18 110 25 110 35 C110 45 103 52 93 52 C102 58 111 67 118 78 C125 67 134 58 143 52 C133 52 126 45 126 35 C126 25 133 18 144 18 H265"/></g>
    <g class="motif m-holo"><path d="M0 18 H88 L100 30 L112 18 L124 30 L136 18 H265"/></g>
    <g class="motif m-abyssal"><path d="M0 18 H92 C106 18 115 28 115 41 C115 52 108 60 98 64 C111 67 121 75 125 84 C129 75 139 67 152 64 C142 60 135 52 135 41 C135 28 144 18 158 18 H265"/></g>
    <g class="motif m-divine"><path d="M0 18 H90 C101 18 108 25 108 35 C108 45 101 52 91 52 C101 52 108 59 108 69 C108 59 115 52 125 52 C135 52 142 45 142 35 C142 25 149 18 160 18 H265"/></g>
    <g class="motif m-glitch"><path d="M0 18 H72 V30 H94 V18 H116 V40 H138 V18 H160 V28 H184 V18 H265"/></g>
  </svg>
</div>

<div class="top">
<div><h2 id="title">Untitled Character</h2><p>Live System record synchronized across Hunter, Authority, and Personal layers.</p></div>
<div class="record-actions">
<span id="modePill" class="mode-pill">VIEW MODE</span>
<span id="save">Saved</span>
<button id="recordAction">ENTER EDIT MODE</button>
</div>
</div>
<div id="profileHero" class="profile-hero">
<div class="portrait"><img id="portraitImg" alt="" hidden><span id="portraitGlyph">◇</span></div>
<div class="hero-info"><div class="hero-kicker" id="heroThemeLabel">SYSTEM SIGNATURE</div><div class="hero-name" id="heroName">Untitled Character</div><div class="hero-alias" id="heroAlias">No codename registered</div><div id="heroChips" class="hero-chips"></div><div id="heroStatus" class="status-chips"></div></div>
</div>
<div class="systembar" style="margin:0 0 16px;max-width:none"><span>ACTIVE MODULE // HUNTER STATUS</span><span>ARCHIVE STATE // <span id="archiveStateLabel">LOCKED</span></span><span class="online">● SYSTEM STABLE</span></div>
<div class="tabs">
<button class="active" data-tab="system">01 // SYSTEM / HUNTER</button>
<button data-tab="authority">02 // AUTHORITY / BODY SCAN</button>
<button data-tab="personal">03 // PERSONAL PROFILE</button>
<button data-tab="characterTheme">04 // SYSTEM THEME</button>
<button data-tab="custom">05 // CUSTOM DATA</button>
</div>
<section id="system" class="sheet active"><div class="view-grid grid"></div><div class="edit-grid grid"></div></section>
<section id="authority" class="sheet"><div class="view-grid grid"></div><div class="edit-grid grid"></div></section>
<section id="personal" class="sheet"><div class="view-grid grid"></div><div class="edit-grid grid"></div></section>
<section id="characterTheme" class="sheet">
<div class="theme-shell">
<div id="characterThemePreview" class="theme-preview"><div><div id="charThemeGlyph" class="preview-glyph">◇</div><div id="charThemeTitle" class="preview-title">Inherited System</div><div id="charThemeSource" class="preview-sub">Uses archive personalization</div></div><div><div id="charThemeStyleLabel" class="preview-sub" style="margin-bottom:10px">HOLOGRAPHIC SHELL</div><div id="charThemeSwatches" class="preview-swatches"></div></div></div>
<div class="theme-controls">
<div class="card full"><h3>Character System Signature</h3><div class="fields">
<div class="field"><label>Theme Source</label><select id="charThemeMode"><option value="inherit">Inherit archive default</option><option value="preset">Use preset</option><option value="custom">Custom character theme</option></select></div>
<div class="field"><label>Preset</label><select id="charThemePreset"></select></div>
<div class="field"><label>Theme Name</label><input id="charThemeName" maxlength="40" placeholder="e.g. Valentine Interface"></div>
<div class="field"><label>System Glyph</label><input id="charThemeGlyphInput" maxlength="4" placeholder="✦"></div>
<div class="field"><label>Visual Motif</label><select id="charThemeStyle"><option value="holo">Holographic</option><option value="alien">Alien / Orbital</option><option value="abyssal">Abyssal</option><option value="divine">Divine / Matriarch</option><option value="cute">Soft / Cute</option><option value="glitch">Glitched</option></select></div>
<div class="field"><label>Theme Note</label><input id="charThemeNote" maxlength="100" placeholder="Private design note"></div>
</div><div class="color-row" style="margin-top:12px"><div class="color-control"><label>Primary Glow</label><input id="charThemePrimary" type="color"></div><div class="color-control"><label>Secondary Glow</label><input id="charThemeSecondary" type="color"></div><div class="color-control"><label>Signal Color</label><input id="charThemeSignal" type="color"></div></div><div class="theme-actions" style="margin-top:12px"><button id="copyGlobalTheme">Copy Archive Theme</button><button id="resetCharTheme">Reset to Inherit</button></div><p class="character-theme-note">Selecting this character anywhere in the archive automatically loads this System signature. It is stored with the character and travels with JSON exports.</p></div>
<div class="card full"><h3>Portrait / Record Image</h3><div class="portrait-actions"><button id="portraitUpload">Upload Portrait</button><button id="portraitRemove">Remove Portrait</button><input id="portraitFile" type="file" accept="image/*" hidden></div><p class="character-theme-note">Images are resized before saving so the browser database stays lighter.</p></div>
</div>
</div>
</section>
<section id="custom" class="sheet"><div class="custom-editor"><div class="card full"><h3>Custom Character Data</h3><p class="character-theme-note">Add fields that do not fit the standard System, Authority, or Personal templates. Fields also appear in their chosen module while viewing the record.</p><div id="customList" class="custom-list"></div><button id="addCustomField" style="margin-top:12px">＋ Add Custom Field</button></div></div></section>
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
</div></div>

<script>
const ICON="data:image/webp;base64,"+
"UklGRgQGAABXRUJQVlA4IPgFAABwGQCdASpIAEgAPtFOn0woJCKiMfyK6QAaCWwAssnA176F00zRAXfR3t2edy05CBItEP2X" +
"EjiF95b7/xn1AnddoXAdq3Bqvkxr2oOoWDesRLRT38XzbIPqPeDhqLOjIvGfjhUHvTr9BY6n3m31rR9nybmr3jeK3D6ldF+V" +
"1WARzqpfeIITB13kqq9nYH4sJJqxmt2Jlz6n+tNe6yuxtb7iIjh0weP+OI/ajok9dI7ze4mc/6RBf0a0X8pNbpFYnPAl7foS" +
"R2Gw8t72zFxL6uzfL9/2AAD++9lPFai7lsksKeR566V0B3IOf2iWpn8yhWkVA1rFlIVnMRc/1IN8m67GQvHhSwxmc7dZomAd" +
"cOtjeBpAUDsh7RB8VpZU6seHBh5JnO9cf2bihy2aJASl6e1y/VTM+nNBoFZO87mJEhbYiq3epezILC54aEU8/6mtOMBKq+dy" +
"rXntdSrhwM9SBwCucRrN4QonhSIMORbxE43ywPbQzaet689FZaeCMzLcMSVBV8MwAoKArTuVsGpA/03CddrcA3otuF/ip5Uw" +
"zeu3FVQUysTPklXQ6/C0Scso5TXRsvlC2eWbFR/XuTtO5mgmMCrx4Qjs2FMKcOrD67a02xPCaH51V6hJd+1CnlGUktyi9lTZ" +
"IIhFIQ6j/hcSs0ltlj/O4FABFMmXV0/OJ18k8c/Mp2HLBYx3W5JCwvKtndXmaEC1PHMWB+JM+UEDJF8AklYu9RduxBiiFnYP" +
"SwUEKZviK5ri67cRpeY6soqFdstgoL9p/+Owmrsaeh1PW8PWu+Qxi+r3uZ7O23/yEIaYl8xkcnTeASOk88Xo9gON1cbdin5q" +
"xTiEsh5ygABlMnhdUfEyUIjPd/m9rdAoUM4wiQq4xifFrBSKYKC15+oZg4hvKEGFtov9/yLx4ARefcxsWuce81Gt6CDL2d7n" +
"N0cBhxfwDOlysmJHuWvX2ouQvLY/2KOT5/z5sBvyAulvH49czsRjxiXJjIlA6klWwAbITzFnKh1eAFLa54k1hxgeLIb6VR1L" +
"7+/1SfOCcfkXTTNNH2bZ6H3l/JrC0vrW271SSt34IXKGKaT2L/ELhSCOvWltHzDEwVF9/KVhW/u1MtiNWYG/V9NiOqjfFe6H" +
"t+A3QmUK/rM4loIRivEiCxyBq5efR96kKcOh9D6TB3PaortyXxp/IwYRuBBGv8xNUCDd7UnfCnJKQfOtwsxe2/+7OVC2bIQh" +
"lpx1LMMZEbL+vHyQIcXIEp86EjoqTi8uni3lVR9JITBZADhcShTnD6UXIOuVnBmx3fkzTPj4vlCDTk/4xuDhn6B1nHMp9et6" +
"mdXzYNhlCxQn/516Da4vJfZoBQIO7q9Zy7TF1RYjs1iKpUcVv+aqqdsB3IoYrcjeRetEkHzvE9o03Jzod6B/3Xj6lbc6pGxZ" +
"ciqfb8UrSefsdzvIZYUAEj2EKTxrvMUIybASw0H/9eVdWB8n+Id/B+dXv4rVIrdZZvRxIVScuqO2Ix3V7ypz02Zh109lz8Tr" +
"9WqRMaCkBn/ZD8w7vvZponlJimQXzLp/K/jquAr13e2Sxg6+ahYuqlRRzYf0aSVeUKpZXV1TOQy1m9WDcwCatsazlu0llxJM" +
"F0/94gUJ01EH6enEkofKzQDc+sETZTIRrrNcB/sofV0PyhetJGqQ/Ut1gvpdBeX/SdPbKy77B/Im9eHfMS8Nmt0oEE8dXPas" +
"5nEfn12OI1CoEbVFsnprMood2pyvab3DU2KWd63Oy1PLsL+gtMFuaFAcUBT5+/cVjSjmkkWUe+YQRytSTqhQ5pHdC1YkwjiP" +
"mxtM4ExSYLFzcRM3xfXTxYrOdXmCyZ47ptb3pG+7cc2MGWINuZMRoUtQK2sc0qh6XNGM2TchR6Pnh4iFxzZnEUN1ourKUjU3" +
"fSZzDNOE1mCnlDIcZCfpQw6l9tcp3PqAQ3AhhQeTQVBOq6CvS0GdCN86H5x9GmvoVsYA+6TlbTuXEVQlnclC6kyJ4cMktMY+" +
"U66ldCGa0918qEp7JBhq+gfIN8c6Z879HdIoRcCjKgAAAAAA";;

const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
$("#logo").src=ICON;$("#fav").href=ICON;

const SK="classUnknownDB",SETK="classUnknownSettings",mem=new Map();
const getStore=k=>{try{return localStorage.getItem(k)}catch{return mem.get(k)||null}};
const setStore=(k,v)=>{try{localStorage.setItem(k,v);return true}catch{mem.set(k,v);return false}};

const THEMES={
system:["Archive Blue","#7feaff","#8aa8c7","#9ef1c4","◇",520,"Neutral archive shell","holo"],
authority:["Authority","#8fc8ff","#628fbd","#83e1b3","▣",460,"Authority oversight skin","holo"],
crimson:["Crimson","#ff9eb2","#c8738b","#f4ce7a","✧",560,"Combat alert skin","holo"],
holo:["Holographic","#bfeaff","#d9c7ff","#e7ffd6","◌",500,"Luminous archive skin","holo"],
cyber:["Cyber Cute","#ff9cc8","#7fe9ff","#ffe57b","♥",880,"Pixel hearts + pastel","cute"],
alien:["Val Aliencore","#86f3ef","#ffabc9","#aef7d7","👽",760,"Val archive skin","alien"],
kang:["Kang / Abyssal","#9d8cff","#65718f","#d7be7a","◆",360,"Kang archive skin","abyssal"],
slimes:["Roswell + Kepler","#ff9fc9","#6fa9ff","#9be8d0","●",620,"Roswell + Kepler skin","cute"],
matriarch:["Matriarch","#b5f0dc","#d8c6ff","#efd58d","❋",540,"Matriarch resonance skin","divine"],
sanctuary:["Sanctuary","#86ece9","#83c8ff","#9fe6b9","❈",500,"Sanctuary glass skin","holo"],
glitch:["Glitched","#62efff","#ff5db1","#8ff7c3","▥",420,"Corrupted archive skin","glitch"]
};
const DEF={theme:"system",sound:true,volume:32,fx:"full",density:"normal",font:"16",reduce:false};
let settings={...DEF,...JSON.parse(getStore(SETK)||"{}")};
if(settings.theme==="abyss"||settings.theme==="dragon")settings.theme="kang";
if(settings.theme==="valentine")settings.theme="alien";
if(settings.theme==="light")settings.theme="holo";
if(settings.theme==="cybercute")settings.theme="cyber";
if(settings.theme==="roswellkepler")settings.theme="slimes";
if(settings.theme==="glitched")settings.theme="glitch";
if([".9","1","1.1","1.2"].includes(String(settings.font)))settings.font={".9":"14","1":"16","1.1":"18","1.2":"20"}[String(settings.font)];

const FORMS={
system:[
["Hunter Identification",[["Name","identity.name"],["Alias / Codename","identity.alias"],["Age","identity.age"],["Pronouns","identity.pronouns"],["Rank","hunter.rank"],["Class","hunter.class"],["Level","hunter.level"],["Affiliation","hunter.affiliation"]]],
["Core Stats",[["Strength","stats.strength"],["Agility","stats.agility"],["Endurance","stats.endurance"],["Mana","stats.mana"],["Perception","stats.perception"],["Control","stats.control"]]],
["System Classification",[["Type","hunter.type"],["Lineage","hunter.lineage"],["Status Effects","hunter.statusEffects","ta"],["System Notes","hunter.systemNotes","ta"]]],
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
["Habits & Social",[["Habits / Mannerisms","personal.habits","ta"],["Relationships / Social Notes","personal.relationships","ta"],["Relationship Links","personal.relationshipLinks","ta"]]],
["Voice & Presentation",[["Voice / Accent / Speech","personal.voice","ta"],["Style / Fashion","personal.style","ta"]]],
["Private System Profile",[["Additional Notes","personal.notes","ta"]]]
]};

function blank(){return{
id:crypto.randomUUID?crypto.randomUUID():"c"+Date.now(),createdAt:new Date().toISOString(),updatedAt:new Date().toISOString(),
identity:{name:"",alias:"",age:"",pronouns:""},
hunter:{rank:"",class:"",level:"",affiliation:"",type:"",lineage:"",statusEffects:"",systemNotes:"",abilities:""},
stats:{strength:"",agility:"",endurance:"",mana:"",perception:"",control:""},
gear:{primaryWeapon:"",secondaryWeapon:"",armor:"",artifacts:""},
authority:{registeredName:"",hunterId:"",nationality:"",registrationStatus:"",watchStatus:"",clearance:"",manaSignature:"",scanReliability:"",physiology:"",notes:""},
appearance:{height:"",build:"",hair:"",eyes:"",skin:"",features:""},
personal:{personality:"",likes:"",dislikes:"",habits:"",relationships:"",relationshipLinks:"",voice:"",style:"",notes:""},
systemTheme:{mode:"inherit",preset:"alien",name:"",primary:"#86f3ef",secondary:"#ffabc9",signal:"#aef7d7",glyph:"✦",style:"holo",note:""},
media:{portrait:""},customFields:[]};}
function merge(base,incoming){if(!incoming||typeof incoming!=="object")return base;for(const [k,v] of Object.entries(incoming)){if(Array.isArray(v))base[k]=v;else if(v&&typeof v==="object"&&base[k]&&typeof base[k]==="object"&&!Array.isArray(base[k]))base[k]=merge(base[k],v);else base[k]=v}return base}
function normalizeCharacter(raw){const c=merge(blank(),raw||{});if(!c.id)c.id=crypto.randomUUID?crypto.randomUUID():"c"+Date.now()+Math.random();if(!Array.isArray(c.customFields))c.customFields=[];return c}
let db=(()=>{try{return JSON.parse(getStore(SK)||'{"characters":[],"activeId":null}')}catch{return{characters:[],activeId:null}}})();
db.characters=(db.characters||[]).map(normalizeCharacter);
let active=db.activeId,audio=null,editMode=false,saveTimer=null,homeMode=!active;
const read=(o,p)=>p.split(".").reduce((a,k)=>a?.[k],o)??"";
const write=(o,p,v)=>{const a=p.split("."),last=a.pop();let x=o;for(const k of a)x=x[k]??={};x[last]=v};
const current=()=>db.characters.find(c=>c.id===active)||null;
const safe=(v)=>String(v??"").replace(/[&<>\"']/g,m=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#039;"}[m]));

function presetTheme(key){const t=THEMES[key]||THEMES.system;return{name:t[0],primary:t[1],secondary:t[2],signal:t[3],glyph:t[4],frequency:t[5],style:t[7]||"holo",source:"preset"}}
function resolvedTheme(c=current()){
  const fallback=presetTheme(settings.theme);
  if(!c?.systemTheme)return{...fallback,source:"archive"};
  const st=c.systemTheme;
  if(st.mode==="preset")return{...presetTheme(st.preset),source:"character"};
  if(st.mode==="custom")return{name:st.name||((c.identity?.name||"Character")+" System"),primary:st.primary||fallback.primary,secondary:st.secondary||fallback.secondary,signal:st.signal||fallback.signal,glyph:st.glyph||fallback.glyph,frequency:fallback.frequency,style:st.style||"holo",source:"character"};
  return{...fallback,source:"archive"};
}
function applyTheme(){const t=resolvedTheme(),r=document.documentElement;r.style.setProperty("--a",t.primary);r.style.setProperty("--b",t.secondary);r.style.setProperty("--c",t.signal);r.style.setProperty("--gap",settings.density==="compact"?"10px":settings.density==="spacious"?"20px":"16px");r.style.setProperty("--font-size",(settings.font||"16")+"px");r.dataset.reduce=settings.reduce?"1":"0";r.dataset.characterStyle=t.style||"holo";$("#systemPersonalization").textContent=(t.source==="character"?"CHARACTER THEME: ":"PERSONALIZATION: ")+t.name.toUpperCase();$$('.theme').forEach(b=>b.classList.toggle('active',b.dataset.theme===settings.theme));$("#sound").checked=settings.sound;$("#volume").value=settings.volume;$("#fx").value=settings.fx;$("#density").value=settings.density;$("#font").value=String(settings.font);$("#reduce").checked=settings.reduce}
function saveSettings(){setStore(SETK,JSON.stringify(settings));applyTheme();renderHome();renderThemeEditor()}

function toast(message){const host=$("#toastHost");if(!host)return;const el=document.createElement("div");el.className="toast";el.textContent=message;host.appendChild(el);setTimeout(()=>{el.style.opacity="0";el.style.transform="translateY(6px)"},1600);setTimeout(()=>el.remove(),1900)}
function setSaveState(text,kind=""){const el=$("#save");if(!el)return;el.textContent=text;el.classList.remove("saving","warn");if(kind)el.classList.add(kind)}
function saveDB(message){db.activeId=active;const ok=setStore(SK,JSON.stringify(db));setSaveState(message||(editMode?"Draft autosaved":"Saved & locked"),ok?"":"warn");$("#storageNote").textContent=ok?"Autosaves in this browser.":"Storage blocked. Export JSON before closing.";return ok}
function scheduleSave(){setSaveState("Saving…","saving");if(saveTimer)clearTimeout(saveTimer);saveTimer=setTimeout(()=>{saveTimer=null;saveDB("Draft autosaved")},260)}
function flushSave(message){if(saveTimer){clearTimeout(saveTimer);saveTimer=null}return saveDB(message)}

function buildForms(){for(const [sid,groups] of Object.entries(FORMS)){const grid=$("#"+sid+" .edit-grid");grid.innerHTML="";for(const [title,fields] of groups){const card=document.createElement("div");card.className="card"+(fields.length===1?" full":"");card.innerHTML=`<h3>${title}</h3><div class="fields"></div>`;const box=$(".fields",card);for(const [label,path,type] of fields){const field=document.createElement("div");field.className="field"+(type==="ta"?" full":"");field.innerHTML=`<label>${label}</label>${type==="ta"?`<textarea data-path="${path}"></textarea>`:`<input data-path="${path}">`}`;box.appendChild(field)}grid.appendChild(card)}}}
function valueHTML(path,val){const str=String(val||"").trim();if(!str)return'<span class="readout-value blank-value">—</span>';if(path==="hunter.statusEffects"){const chips=str.split(/[,\n]/).map(x=>x.trim()).filter(Boolean).map(x=>`<span class="status-chip">${safe(x)}</span>`).join("");return`<div class="status-chips">${chips}</div>`}if(path==="personal.relationshipLinks"){const rows=str.split(/\n/).map(x=>x.trim()).filter(Boolean).map(line=>{const [name,...rest]=line.split(/\s*[|:]\s*/);return`<div class="relationship-row"><b>${safe(name)}</b><span>${safe(rest.join(" · ")||"Linked")}</span></div>`}).join("");return`<div class="relationship-list">${rows}</div>`}return`<span class="readout-value">${safe(str)}</span>`}
function renderViewSection(section,c){const grid=$("#"+section+" .view-grid");grid.innerHTML="";for(const [title,fields] of FORMS[section]){const card=document.createElement("div");card.className="card view-card"+(fields.length===1?" full":"");if(title==="Core Stats"){let lines=fields.map(([lab,path])=>{const raw=read(c,path),num=parseFloat(raw),pct=Number.isFinite(num)?Math.max(0,Math.min(100,num)):0;return`<div class="stat-line"><span class="stat-name">${safe(lab)}</span><span class="stat-track"><i class="stat-fill" style="width:${pct}%"></i></span><span class="stat-value">${safe(raw||"—")}</span></div>`}).join("");card.innerHTML=`<h3>${title}</h3>${lines}`}else{const inner=fields.map(([lab,path,type])=>{const alert=path==="authority.watchStatus"&&String(read(c,path)).trim()?" watch-alert":"";return`<div class="readout${type==="ta"?" full":""}${alert}"><span class="readout-label">${safe(lab)}</span>${valueHTML(path,read(c,path))}</div>`}).join("");card.innerHTML=`<h3>${title}</h3><div class="readout-grid">${inner}</div>`}grid.appendChild(card)}
  const custom=(c.customFields||[]).filter(f=>f.section===section&&String(f.label||f.value||"").trim());if(custom.length){const card=document.createElement("div");card.className="card view-card full";card.innerHTML=`<h3>Custom Data</h3><div class="readout-grid">${custom.map(f=>`<div class="readout"><span class="readout-label">${safe(f.label||"Custom Field")}</span>${valueHTML("",f.value)}</div>`).join("")}</div>`;grid.appendChild(card)}
}
function renderViewSections(c){renderViewSection("system",c);renderViewSection("authority",c);renderViewSection("personal",c)}

function renderHero(c){const t=resolvedTheme(c);$("#heroName").textContent=c.identity?.name||"Untitled Character";$("#heroAlias").textContent=c.identity?.alias||"No codename registered";$("#heroThemeLabel").textContent="SYSTEM SIGNATURE // "+t.name.toUpperCase();const img=$("#portraitImg"),glyph=$("#portraitGlyph");if(c.media?.portrait){img.src=c.media.portrait;img.hidden=false;glyph.hidden=true}else{img.hidden=true;glyph.hidden=false;glyph.textContent=t.glyph||"◇"}const chips=[];if(c.hunter?.rank)chips.push(["RANK // "+c.hunter.rank,""]);if(c.hunter?.class)chips.push(["CLASS // "+c.hunter.class,""]);if(c.hunter?.level)chips.push(["LEVEL // "+c.hunter.level,""]);if(c.authority?.watchStatus)chips.push(["WATCH // "+c.authority.watchStatus,"alert"]);$("#heroChips").innerHTML=chips.map(([x,cl])=>`<span class="hero-chip ${cl}">${safe(x)}</span>`).join("");const statuses=String(c.hunter?.statusEffects||"").split(/[,\n]/).map(x=>x.trim()).filter(Boolean);$("#heroStatus").innerHTML=statuses.map(x=>`<span class="status-chip">${safe(x)}</span>`).join("")}

function renderList(){const q=$("#search").value.toLowerCase(),g=$("#charList");g.innerHTML="";const chars=db.characters.filter(c=>((c.identity?.name||"")+" "+(c.identity?.alias||"")).toLowerCase().includes(q));for(const c of chars){const t=resolvedTheme(c),b=document.createElement("button");b.className="char"+(c.id===active&&!homeMode?" active":"");const meta=[c.hunter?.rank&&c.hunter.rank+" Rank",c.hunter?.class].filter(Boolean).join(" · ");b.innerHTML=`<b>${safe(c.identity?.name||"Untitled Character")}</b><small>${safe(meta||t.name)}</small>`;b.onclick=()=>openCharacter(c.id);g.appendChild(b)}if(!g.children.length)g.innerHTML='<small class="muted">No characters yet.</small>'}
function renderHome(){const g=$("#archiveGrid");if(!g)return;g.innerHTML="";if(!db.characters.length){g.innerHTML='<div class="custom-empty" style="grid-column:1/-1">No records yet. Create your first character to begin the archive.</div>';return}for(const c of db.characters){const t=resolvedTheme(c),card=document.createElement("button");card.className="archive-card";card.style.setProperty("--card1",t.primary);card.style.setProperty("--card2",t.secondary);const meta=[c.hunter?.rank&&"Rank "+c.hunter.rank,c.hunter?.class].filter(Boolean);card.innerHTML=`<span class="theme-signature"><i style="background:${t.primary};color:${t.primary}"></i><i style="background:${t.secondary};color:${t.secondary}"></i><i style="background:${t.signal};color:${t.signal}"></i></span><span class="archive-glyph">${safe(t.glyph||"◇")}</span><span class="archive-name">${safe(c.identity?.name||"Untitled Character")}</span><span class="archive-alias">${safe(c.identity?.alias||t.name)}</span><span class="archive-meta">${meta.map(x=>`<span class="mini-badge">${safe(x)}</span>`).join("")}</span>`;card.onclick=()=>openCharacter(c.id);g.appendChild(card)}}
function showHome(){flushSave(editMode?"Draft saved":"Saved & locked");editMode=false;homeMode=true;$("#homeScreen").hidden=false;$("#empty").hidden=true;$("#editor").hidden=true;applyTheme();renderList();renderHome();closeSide()}
function openCharacter(id){flushSave(editMode?"Draft saved":"Saved & locked");active=id;homeMode=false;editMode=false;saveDB("Saved & locked");render();closeSide();toast("SYSTEM SIGNATURE LOADED")}

function sizeReadouts(){$$("#editor.view-mode textarea").forEach(e=>{e.style.height="auto";e.style.height=Math.max(42,e.scrollHeight)+"px"})}
function applyRecordMode(){const editor=$("#editor");if(!editor)return;editor.classList.toggle("edit-mode",editMode);editor.classList.toggle("view-mode",!editMode);$$('[data-path]').forEach(e=>{e.readOnly=!editMode;e.tabIndex=editMode?0:-1;e.placeholder=editMode?"":"—";e.setAttribute("aria-readonly",editMode?"false":"true")});$$('#characterTheme input,#characterTheme select,#characterTheme button,#custom input,#custom textarea,#custom select,#custom button').forEach(e=>{if(e.id==="portraitFile")return;e.disabled=!editMode});$("#recordAction").textContent=editMode?"SAVE & LOCK":"ENTER EDIT MODE";$("#modePill").textContent=editMode?"EDIT MODE":"VIEW MODE";if($("#archiveStateLabel"))$("#archiveStateLabel").textContent=editMode?"EDITING":"LOCKED";if(!editMode)requestAnimationFrame(sizeReadouts)}
function renderEditor(){const c=current();$("#homeScreen").hidden=true;$("#empty").hidden=!!c;$("#editor").hidden=!c;if(!c)return;$("#title").textContent=c.identity?.name||"Untitled Character";$$('[data-path]').forEach(e=>e.value=read(c,e.dataset.path));renderHero(c);renderViewSections(c);applyRecordMode();renderThemeEditor();renderCustomEditor()}
function render(){renderList();renderHome();if(homeMode){$("#homeScreen").hidden=false;$("#empty").hidden=true;$("#editor").hidden=true;applyTheme();return}renderEditor();applyTheme()}

function renderGlobalThemes(){const g=$("#themeGrid");g.innerHTML="";for(const [key,t] of Object.entries(THEMES)){const b=document.createElement("button");b.className="theme";b.dataset.theme=key;b.style.setProperty("--s1",t[1]);b.style.setProperty("--s2",t[2]);b.innerHTML=`<span class="glyph">${t[4]}</span><span class="tname">${t[0]}</span><span class="tdesc">${t[6]}</span>`;b.onclick=()=>{settings.theme=key;saveSettings();tone("page")};g.appendChild(b)}}
function populateCharThemePresets(){const s=$("#charThemePreset");s.innerHTML="";for(const [key,t] of Object.entries(THEMES)){const o=document.createElement("option");o.value=key;o.textContent=t[0];s.appendChild(o)}}
function renderThemeEditor(){const c=current();if(!c)return;const st=c.systemTheme||blank().systemTheme;$("#charThemeMode").value=st.mode||"inherit";$("#charThemePreset").value=st.preset||"alien";$("#charThemeName").value=st.name||"";$("#charThemeGlyphInput").value=st.glyph||"✦";$("#charThemeStyle").value=st.style||"holo";$("#charThemeNote").value=st.note||"";$("#charThemePrimary").value=st.primary||"#86f3ef";$("#charThemeSecondary").value=st.secondary||"#ffabc9";$("#charThemeSignal").value=st.signal||"#aef7d7";const custom=st.mode==="custom";["#charThemeName","#charThemeGlyphInput","#charThemeStyle","#charThemeNote","#charThemePrimary","#charThemeSecondary","#charThemeSignal"].forEach(id=>$(id).disabled=!editMode||!custom);$("#charThemePreset").disabled=!editMode||st.mode!=="preset";const t=resolvedTheme(c);$("#charThemeGlyph").textContent=t.glyph||"◇";$("#charThemeTitle").textContent=t.name;$("#charThemeSource").textContent=st.mode==="inherit"?"INHERITS ARCHIVE PERSONALIZATION":st.mode==="preset"?"CHARACTER PRESET":"CUSTOM CHARACTER SYSTEM";$("#charThemeStyleLabel").textContent=(t.style||"holo").toUpperCase()+" SHELL";$("#charThemeSwatches").innerHTML=`<i style="background:${t.primary};color:${t.primary}"></i><i style="background:${t.secondary};color:${t.secondary}"></i><i style="background:${t.signal};color:${t.signal}"></i>`}
function updateCharTheme(){const c=current();if(!c||!editMode)return;c.systemTheme={...c.systemTheme,mode:$("#charThemeMode").value,preset:$("#charThemePreset").value,name:$("#charThemeName").value,primary:$("#charThemePrimary").value,secondary:$("#charThemeSecondary").value,signal:$("#charThemeSignal").value,glyph:$("#charThemeGlyphInput").value||"✦",style:$("#charThemeStyle").value,note:$("#charThemeNote").value};c.updatedAt=new Date().toISOString();scheduleSave();applyTheme();renderHero(c);renderThemeEditor();renderHome();renderList()}
function copyGlobalIntoCharacter(){const c=current();if(!c||!editMode)return;const t=presetTheme(settings.theme);c.systemTheme={...c.systemTheme,mode:"custom",preset:settings.theme,name:(c.identity?.name||"Character")+" System",primary:t.primary,secondary:t.secondary,signal:t.signal,glyph:t.glyph,style:t.style,note:""};scheduleSave();applyTheme();renderThemeEditor();renderHero(c);renderHome();toast("ARCHIVE THEME COPIED")}
function resetCharacterTheme(){const c=current();if(!c||!editMode)return;c.systemTheme={...blank().systemTheme,mode:"inherit",preset:settings.theme};scheduleSave();applyTheme();renderThemeEditor();renderHero(c);renderHome();toast("CHARACTER THEME RESET")}

function renderCustomEditor(){const c=current(),g=$("#customList");if(!c||!g)return;g.innerHTML="";if(!c.customFields.length){g.innerHTML='<div class="custom-empty">No custom fields yet.</div>';return}c.customFields.forEach((f,i)=>{const row=document.createElement("div");row.className="custom-row";row.innerHTML=`<select data-custom-section="${i}"><option value="system">System / Hunter</option><option value="authority">Authority</option><option value="personal">Personal</option></select><input data-custom-label="${i}" placeholder="Field label" value="${safe(f.label||"")}"><textarea data-custom-value="${i}" placeholder="Value">${safe(f.value||"")}</textarea><button data-custom-remove="${i}" class="danger">Remove</button>`;g.appendChild(row);$(`[data-custom-section="${i}"]`,row).value=f.section||"system"});$$('[data-custom-section], [data-custom-label], [data-custom-value]',g).forEach(el=>{el.disabled=!editMode;el.oninput=()=>{if(!editMode)return;const i=+(el.dataset.customSection??el.dataset.customLabel??el.dataset.customValue);const f=c.customFields[i];if(el.dataset.customSection!==undefined)f.section=el.value;if(el.dataset.customLabel!==undefined)f.label=el.value;if(el.dataset.customValue!==undefined)f.value=el.value;scheduleSave();renderViewSections(c);renderHome()}});$$('[data-custom-remove]',g).forEach(b=>{b.disabled=!editMode;b.onclick=()=>{if(!editMode)return;c.customFields.splice(+b.dataset.customRemove,1);scheduleSave();renderCustomEditor();renderViewSections(c)}})}

async function compressPortrait(file){return new Promise((resolve,reject)=>{const reader=new FileReader();reader.onerror=reject;reader.onload=()=>{const img=new Image();img.onerror=reject;img.onload=()=>{const max=420,scale=Math.min(1,max/Math.max(img.width,img.height)),w=Math.max(1,Math.round(img.width*scale)),h=Math.max(1,Math.round(img.height*scale)),canvas=document.createElement("canvas");canvas.width=w;canvas.height=h;canvas.getContext("2d").drawImage(img,0,0,w,h);resolve(canvas.toDataURL("image/jpeg",.76))};img.src=reader.result};reader.readAsDataURL(file)})}

function tone(kind="click"){if(!settings.sound)return;const A=window.AudioContext||window.webkitAudioContext;if(!A)return;audio??=new A();if(audio.state==="suspended")audio.resume().catch(()=>{});const t=resolvedTheme(),o=audio.createOscillator(),g=audio.createGain(),n=audio.currentTime;o.type=t.style==="glitch"?"square":t.style==="abyssal"?"sawtooth":"triangle";o.frequency.value=kind==="page"?t.frequency*1.45:t.frequency;g.gain.setValueAtTime(.0001,n);g.gain.exponentialRampToValueAtTime(Math.max(.0008,settings.volume/100*.08),n+.01);g.gain.exponentialRampToValueAtTime(.0001,n+.15);o.connect(g);g.connect(audio.destination);o.start(n);o.stop(n+.17)}
function burst(x,y){if(settings.reduce||settings.fx==="off")return;const t=resolvedTheme(),e=document.createElement("div");e.className="burst";e.textContent=t.glyph||"◇";e.style.left=x+"px";e.style.top=y+"px";e.style.color=t.primary;document.body.appendChild(e);setTimeout(()=>e.remove(),650)}
function download(data,name){const u=URL.createObjectURL(new Blob([JSON.stringify(data,null,2)],{type:"application/json"})),a=document.createElement("a");a.href=u;a.download=name;a.click();setTimeout(()=>URL.revokeObjectURL(u),500)}

buildForms();renderGlobalThemes();populateCharThemePresets();
$$('[data-path]').forEach(e=>e.oninput=()=>{if(!editMode)return;const c=current();if(!c)return;write(c,e.dataset.path,e.value);c.updatedAt=new Date().toISOString();if(e.dataset.path==="identity.name")$("#title").textContent=e.value||"Untitled Character";renderHero(c);renderViewSections(c);renderList();renderHome();scheduleSave()});
$$('.tabs button').forEach(b=>b.onclick=()=>{$$('.tabs button').forEach(x=>x.classList.remove('active'));$$('.sheet').forEach(x=>x.classList.remove('active'));b.classList.add('active');$("#"+b.dataset.tab).classList.add('active');$("#editor").dataset.module=b.dataset.tab;renderThemeEditor();renderCustomEditor();b.scrollIntoView({behavior:settings.reduce?"auto":"smooth",block:"nearest",inline:"nearest"});tone('page')});
function makeNew(){flushSave(editMode?"Draft saved":"Saved & locked");const c=blank();db.characters.unshift(c);active=c.id;homeMode=false;editMode=true;saveDB("New draft");render();$('[data-path="identity.name"]').focus()}
$("#new").onclick=makeNew;$("#homeNew").onclick=makeNew;$("#homeBtn").onclick=showHome;
$("#dup").onclick=()=>{flushSave(editMode?"Draft saved":"Saved & locked");const c=current();if(!c)return;const n=normalizeCharacter(JSON.parse(JSON.stringify(c)));n.id=crypto.randomUUID?crypto.randomUUID():"c"+Date.now();n.identity.name=(n.identity.name||"Untitled Character")+" Copy";db.characters.unshift(n);active=n.id;homeMode=false;editMode=true;saveDB("Duplicate draft");render()};
$("#del").onclick=()=>{const c=current();if(c&&confirm(`Delete "${c.identity?.name||"Untitled Character"}"?`)){flushSave(editMode?"Draft saved":"Saved & locked");db.characters=db.characters.filter(x=>x.id!==c.id);active=db.characters[0]?.id||null;editMode=false;homeMode=true;saveDB("Saved & locked");render();toast("ARCHIVE RECORD DELETED")}};
$("#exp").onclick=()=>{const c=current();if(c)download(c,(c.identity?.name||"character").replace(/[^\w-]+/g,"_")+".json")};
$("#expAll").onclick=()=>download({schemaVersion:4,characters:db.characters},"class-unknown-character-database.json");
$("#imp").onclick=()=>$("#file").click();
$("#file").onchange=async e=>{try{const p=JSON.parse(await e.target.files[0].text()),arr=Array.isArray(p)?p:Array.isArray(p.characters)?p.characters:[p],ids=new Set(db.characters.map(x=>x.id));const imported=[];for(const raw of arr){const x=normalizeCharacter(raw);if(ids.has(x.id))x.id=crypto.randomUUID?crypto.randomUUID():"c"+Date.now()+Math.random();ids.add(x.id);db.characters.unshift(x);imported.push(x)}active=imported[0]?.id||active;homeMode=!active;editMode=false;saveDB("Imported & locked");render();toast(`${imported.length} RECORD${imported.length===1?"":"S"} IMPORTED`)}catch(err){alert("Import failed: "+err.message)}e.target.value=""};
$("#search").oninput=renderList;
function openSide(){$("#side").classList.add("open");$("#sideBackdrop").classList.add("open")}function closeSide(){$("#side").classList.remove("open");$("#sideBackdrop").classList.remove("open")}
$("#menu").onclick=()=>$("#side").classList.contains("open")?closeSide():openSide();$("#sideBackdrop").onclick=closeSide;
$("#recordAction").onclick=()=>{if(!current())return;if(editMode){editMode=false;flushSave("Saved & locked");applyRecordMode();renderThemeEditor();renderCustomEditor();toast("ARCHIVE RECORD LOCKED");tone("page")}else{editMode=true;setSaveState("Editing draft");applyRecordMode();renderThemeEditor();renderCustomEditor();tone("page")}};
const open=()=>$("#modal").classList.add("open"),close=()=>$("#modal").classList.remove("open");$("#settings").onclick=open;$("#msettings").onclick=open;$("#close").onclick=close;$("#done").onclick=close;$("#modal").onclick=e=>{if(e.target===$("#modal"))close()};
$("#sound").onchange=e=>{settings.sound=e.target.checked;saveSettings()};$("#volume").oninput=e=>{settings.volume=+e.target.value;saveSettings()};$("#fx").onchange=e=>{settings.fx=e.target.value;saveSettings()};$("#density").onchange=e=>{settings.density=e.target.value;saveSettings()};$("#font").onchange=e=>{settings.font=e.target.value;saveSettings()};$("#reduce").onchange=e=>{settings.reduce=e.target.checked;saveSettings()};$("#reset").onclick=()=>{settings={...DEF};saveSettings()};
["#charThemeMode","#charThemePreset","#charThemeName","#charThemeGlyphInput","#charThemeStyle","#charThemeNote","#charThemePrimary","#charThemeSecondary","#charThemeSignal"].forEach(id=>{$(id).oninput=updateCharTheme;$(id).onchange=updateCharTheme});
$("#copyGlobalTheme").onclick=copyGlobalIntoCharacter;$("#resetCharTheme").onclick=resetCharacterTheme;
$("#portraitUpload").onclick=()=>{if(editMode)$("#portraitFile").click()};$("#portraitRemove").onclick=()=>{const c=current();if(!c||!editMode)return;c.media.portrait="";scheduleSave();renderHero(c);toast("PORTRAIT REMOVED")};$("#portraitFile").onchange=async e=>{const c=current(),file=e.target.files[0];if(c&&file&&editMode){try{c.media.portrait=await compressPortrait(file);scheduleSave();renderHero(c);toast("PORTRAIT SAVED")}catch{alert("Could not process that image.")}}e.target.value=""};
$("#addCustomField").onclick=()=>{const c=current();if(!c||!editMode)return;c.customFields.push({section:"system",label:"",value:""});scheduleSave();renderCustomEditor()};
document.addEventListener("click",e=>{const b=e.target.closest("button");if(!b)return;const r=b.getBoundingClientRect();burst(r.left+r.width/2,r.top+r.height/2);if(!b.closest('.tabs')&&!b.classList.contains('theme'))tone(b.id==="del"?"danger":"click")});
document.addEventListener("keydown",e=>{if(e.key==="Escape"){closeSide();if($("#modal").classList.contains("open"))close()}});window.addEventListener("beforeunload",()=>{if(editMode)flushSave("Draft saved")});
if(active&&!current())active=db.characters[0]?.id||null;if(!active)homeMode=true;editMode=false;render();saveDB("Saved & locked");

</script>
<div id="toastHost"></div>
</body>
</html>

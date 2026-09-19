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
:root{--ease:cubic-bezier(.2,.8,.2,1)}
html{scroll-behavior:smooth}
button,input,textarea,select,.card,.theme,.char{transition:border-color .18s var(--ease),box-shadow .18s var(--ease),background .18s var(--ease),transform .16s var(--ease),opacity .18s var(--ease)}
button:focus-visible,input:focus-visible,textarea:focus-visible,select:focus-visible{outline:2px solid color-mix(in srgb,var(--a) 75%,white 10%);outline-offset:2px}
#editor{background:
linear-gradient(var(--a),var(--a)) left 10px top 10px/34px 2px no-repeat,
linear-gradient(var(--a),var(--a)) left 10px top 10px/2px 34px no-repeat,
linear-gradient(var(--a),var(--a)) right 10px top 10px/34px 2px no-repeat,
linear-gradient(var(--a),var(--a)) right 10px top 10px/2px 34px no-repeat,
linear-gradient(var(--a),var(--a)) left 10px bottom 10px/34px 2px no-repeat,
linear-gradient(var(--a),var(--a)) left 10px bottom 10px/2px 34px no-repeat,
linear-gradient(var(--a),var(--a)) right 10px bottom 10px/34px 2px no-repeat,
linear-gradient(var(--a),var(--a)) right 10px bottom 10px/2px 34px no-repeat,
linear-gradient(180deg,rgba(5,11,18,.88),rgba(4,9,15,.96))}
#editor:before{inset:15px;border-color:color-mix(in srgb,var(--a) 18%,transparent)}
#editor.view-mode .field{min-height:68px;display:flex;flex-direction:column;justify-content:center}
#editor.view-mode input,#editor.view-mode textarea{font-weight:650;letter-spacing:.01em}
#editor.view-mode input::placeholder,#editor.view-mode textarea::placeholder{color:rgba(180,205,230,.45);opacity:1;font-style:italic}
.card{background:
linear-gradient(var(--a),var(--a)) left 7px top 7px/20px 1px no-repeat,
linear-gradient(var(--a),var(--a)) left 7px top 7px/1px 20px no-repeat,
linear-gradient(var(--a),var(--a)) right 7px bottom 7px/20px 1px no-repeat,
linear-gradient(var(--a),var(--a)) right 7px bottom 7px/1px 20px no-repeat,
linear-gradient(180deg,rgba(9,17,27,.93),rgba(5,10,16,.97))}
.card:hover{border-color:color-mix(in srgb,var(--a) 32%,var(--line));box-shadow:0 0 30px color-mix(in srgb,var(--a) 8%,transparent),inset 0 0 0 1px rgba(255,255,255,.025)}
.top h2{color:#f7fbff}.top h2:before{content:"STATUS // ";color:var(--a);font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.14em;display:block;margin-bottom:6px;text-shadow:0 0 14px color-mix(in srgb,var(--a) 25%,transparent)}
.tabs{padding-bottom:2px}.tabs button{position:relative;overflow:hidden}.tabs button.active:after{content:"";position:absolute;left:12%;right:12%;bottom:0;height:1px;background:var(--a);box-shadow:0 0 10px var(--a)}
.systembar{backdrop-filter:blur(10px)}#save{min-width:104px;text-align:right}#save.saving{color:var(--a)}#save.warn{color:#ffd27f}#recordAction{font-weight:800;letter-spacing:.05em}
.sidebar-backdrop{display:none}.toast{position:fixed;right:20px;bottom:20px;z-index:120;max-width:min(360px,calc(100vw - 40px));padding:11px 14px;border:1px solid color-mix(in srgb,var(--a) 38%,var(--line));border-radius:7px;background:rgba(5,12,20,.94);backdrop-filter:blur(12px);color:var(--text);box-shadow:0 18px 50px rgba(0,0,0,.4),0 0 24px color-mix(in srgb,var(--a) 10%,transparent);font:.74rem/1.35 ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.04em;animation:toastIn .22s var(--ease)}
@keyframes toastIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
@media(max-width:900px){.sidebar-backdrop{position:fixed;inset:0;z-index:35;background:rgba(0,0,0,.54);backdrop-filter:blur(3px)}.sidebar-backdrop.open{display:block}aside{box-shadow:16px 0 50px rgba(0,0,0,.48),inset -1px 0 0 rgba(126,223,255,.08)}#editor{padding:22px 16px 18px}}
@media(max-width:560px){#editor:before{inset:10px}.record-actions{gap:6px}#recordAction{width:100%}.mode-pill,#save{font-size:.54rem}}
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
.view-card{grid-column:span 6}.view-card.full{grid-column:1/-1}.readout-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.readout{min-height:66px;padding:10px 12px;border:1px solid rgba(106,178,255,.11);border-radius:4px;background:rgba(4,10,16,.29)}.readout.full{grid-column:1/-1}.readout-label{display:block;color:color-mix(in srgb,var(--a) 70%,var(--muted));font:700 .64rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.11em;text-transform:uppercase;margin-bottom:6px}.readout-value{display:block;color:var(--text);font-weight:650;white-space:pre-wrap;overflow-wrap:anywhere}.readout-value.blank-value{min-height:0;border:0;background:none;display:block;color:rgba(178,203,227,.46);font-style:italic;text-align:left;box-shadow:none}
.stat-line{display:grid;grid-template-columns:minmax(85px,.7fr) minmax(90px,1.7fr) auto;gap:10px;align-items:center;padding:8px 0;border-bottom:1px solid rgba(106,178,255,.08)}.stat-line:last-child{border-bottom:0}.stat-name{font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;color:color-mix(in srgb,var(--a) 70%,var(--muted));letter-spacing:.08em;text-transform:uppercase}.stat-track{height:5px;background:rgba(94,145,190,.12);border-radius:99px;overflow:hidden}.stat-fill{height:100%;background:linear-gradient(90deg,var(--a),var(--b));box-shadow:0 0 10px color-mix(in srgb,var(--a) 45%,transparent)}.stat-value{font:800 .74rem ui-monospace,SFMono-Regular,Menlo,monospace;color:var(--text)}
.relationship-list{display:grid;gap:7px}.relationship-row{display:flex;justify-content:space-between;gap:12px;padding:8px 10px;border:1px solid rgba(106,178,255,.1);border-radius:4px;background:rgba(4,10,16,.26)}.relationship-row b{color:var(--text)}.relationship-row span{color:var(--muted);text-align:right}.watch-alert{border-color:rgba(255,112,150,.28)!important;box-shadow:inset 2px 0 0 rgba(255,112,150,.55)}
.theme-shell{position:relative;z-index:1;display:grid;grid-template-columns:minmax(220px,.8fr) minmax(300px,1.2fr);gap:16px}.theme-preview{min-height:300px;padding:18px;border:1px solid color-mix(in srgb,var(--a) 34%,var(--line));border-radius:8px;background:radial-gradient(circle at 50% 0,color-mix(in srgb,var(--b) 18%,transparent),transparent 42%),linear-gradient(180deg,rgba(5,12,20,.94),rgba(3,8,14,.98));box-shadow:0 0 32px color-mix(in srgb,var(--a) 10%,transparent),inset 0 0 0 1px rgba(255,255,255,.02);display:flex;flex-direction:column;justify-content:space-between;overflow:hidden}.preview-glyph{font-size:3rem;color:var(--a);text-shadow:0 0 24px color-mix(in srgb,var(--a) 48%,transparent)}.preview-title{font-weight:900;font-size:1.3rem;letter-spacing:.06em}.preview-sub{color:var(--muted);font:700 .66rem ui-monospace,SFMono-Regular,Menlo,monospace;letter-spacing:.12em;text-transform:uppercase}.preview-swatches{display:flex;gap:7px}.preview-swatches i{width:30px;height:7px;border-radius:999px;box-shadow:0 0 12px currentColor}.theme-controls{display:grid;gap:12px}.theme-controls .card{grid-column:auto}.color-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}.color-control input[type=color]{height:44px;padding:4px}.theme-actions{display:flex;gap:8px;flex-wrap:wrap}.theme-actions button{flex:1}.portrait-actions{display:flex;gap:8px;flex-wrap:wrap}.portrait-actions button{flex:1}.character-theme-note{color:var(--muted);font-size:.76rem;line-height:1.45}
.custom-editor{position:relative;z-index:1}.custom-list{display:grid;gap:10px}.custom-row{display:grid;grid-template-columns:150px 1fr 1.4fr auto;gap:8px;align-items:start;padding:10px;border:1px solid rgba(106,178,255,.12);border-radius:6px;background:rgba(4,10,16,.35)}.custom-row button{padding:.7rem}.custom-empty{padding:24px;text-align:center;color:var(--muted);border:1px dashed rgba(106,178,255,.17);border-radius:6px}
html[data-character-style="alien"] body:after{background-size:52px 52px;background-image:radial-gradient(circle,rgba(123,239,229,.08) 1px,transparent 1px),linear-gradient(rgba(105,180,255,.035) 1px,transparent 1px)}
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
<div id="empty" class="empty"><div><b>No archive file selected.</b><br>Create a new record or upload a saved profile.</div></div>
<div id="editor" data-module="system" hidden>
<div class="border-doodles" aria-hidden="true">
<svg class="alien-crown" viewBox="0 0 520 128" preserveAspectRatio="xMidYMid meet">
<path d="M0 106 H150 C170 106 183 102 197 92 C211 82 220 69 220 54 C220 38 210 28 197 29 C184 30 174 42 178 55 C184 73 206 88 260 106 C314 88 336 73 342 55 C346 42 336 30 323 29 C310 28 300 38 300 54 C300 69 309 82 323 92 C337 102 350 106 370 106 H520"/>
<path class="accent" d="M198 90 C214 74 232 59 260 40 C288 59 306 74 322 90" opacity=".6"/>
<path class="signal" d="M94 105 C102 93 109 85 117 79 M117 79 C123 89 130 96 142 102" opacity=".75"/>
<circle class="signal" cx="382" cy="104" r="2.4"/><circle class="accent" cx="395" cy="104" r="1.7"/><circle class="signal" cx="408" cy="104" r="1.3"/>
</svg>
<svg class="doodle top-left" viewBox="0 0 320 105">
<g class="motif m-alien"><path d="M0 82 H42 C58 82 70 75 78 63 C86 50 88 36 84 24 C102 31 113 44 113 58 C113 72 103 81 88 82 H320"/><ellipse class="accent" cx="84" cy="55" rx="31" ry="11" transform="rotate(-14 84 55)"/><circle class="signal" cx="84" cy="55" r="18"/><path class="signal" d="M129 35 C132 45 138 51 148 54 C138 57 132 63 129 73 C126 63 120 57 110 54 C120 51 126 45 129 35"/><circle class="accent" cx="160" cy="70" r="2"/><circle class="signal" cx="171" cy="70" r="1.4"/><circle class="accent" cx="181" cy="70" r="1.1"/></g>
<g class="motif m-cute"><path d="M0 82 H58 C71 82 78 74 77 61 C76 49 68 38 57 38 C47 38 41 47 44 57 C48 69 61 78 77 82 C92 72 104 63 113 51 C120 41 137 41 143 53 C150 67 135 77 116 82 H320"/></g>
<g class="motif m-holo"><path d="M0 82 H76 L88 70 L100 82 L112 70 L124 82 H188 L200 74 L212 82 H320"/></g>
<g class="motif m-abyssal"><path d="M0 82 H70 C83 82 91 75 94 64 C98 48 88 35 73 35 C89 24 109 26 119 40 C132 59 119 76 97 82 H180 C195 82 205 74 209 62 C214 47 207 36 195 30 C215 30 229 42 228 58 C227 72 214 81 196 82 H320"/></g>
<g class="motif m-divine"><path d="M0 82 H72 C84 82 92 74 92 63 C92 52 84 44 74 44 C83 35 95 34 103 42 C111 34 123 35 132 44 C122 44 114 52 114 63 C114 74 122 82 134 82 H320"/></g>
<g class="motif m-glitch"><path d="M0 82 H72 V70 H92 V82 H118 V60 H140 V82 H172 V74 H196 V82 H320"/></g>
</svg>
<svg class="doodle top-right accent" viewBox="0 0 280 92">
<g class="motif m-alien"><path d="M0 69 H92 C110 69 122 61 128 48 C134 35 132 24 124 17 C140 19 151 30 152 43 C153 57 143 67 128 69 H280"/><ellipse class="accent" cx="191" cy="52" rx="27" ry="8"/><path class="signal" d="M170 52 C173 38 181 31 191 31 C201 31 209 38 212 52"/><circle class="signal" cx="184" cy="44" r="1.8"/><circle class="signal" cx="198" cy="44" r="1.8"/><path class="signal" d="M191 31 V21 M191 21 C195 17 198 18 200 21"/></g>
<g class="motif m-cute"><path d="M0 69 H86 C96 69 102 63 102 54 C102 45 96 38 87 38 C95 30 106 30 114 38 C122 30 133 30 141 38 C132 38 126 45 126 54 C126 63 132 69 142 69 H280"/></g>
<g class="motif m-holo"><path d="M0 69 H84 L96 57 L108 69 L120 57 L132 69 H280"/></g>
<g class="motif m-abyssal"><path d="M0 69 H94 C109 69 120 59 120 45 C120 34 114 26 103 21 C119 18 135 27 140 41 C146 56 135 68 118 69 H280"/></g>
<g class="motif m-divine"><path d="M0 69 H102 C114 69 122 61 122 50 C122 39 114 31 103 31 C114 22 129 24 137 35 C145 46 140 60 128 66 C125 68 121 69 117 69 H280"/></g>
<g class="motif m-glitch"><path d="M0 69 H72 V58 H95 V69 H116 V49 H137 V69 H162 V60 H184 V69 H280"/></g>
</svg>
</div>
<div class="top"><div><h2 id="title">Untitled Character</h2><p>Live System record synchronized across Hunter, Authority, and Personal layers.</p></div><div class="record-actions"><span id="modePill" class="mode-pill">VIEW MODE</span><span id="save">Saved</span><button id="recordAction">ENTER EDIT MODE</button></div></div>
<div id="profileHero" class="profile-hero"><div class="portrait"><img id="portraitImg" alt="" hidden><span id="portraitGlyph">◇</span></div><div class="hero-info"><div class="hero-kicker" id="heroThemeLabel">SYSTEM SIGNATURE</div><div class="hero-name" id="heroName">Untitled Character</div><div class="hero-alias" id="heroAlias">No codename registered</div><div id="heroChips" class="hero-chips"></div><div id="heroStatus" class="status-chips"></div></div></div>
<div class="systembar" style="margin:0 0 16px;max-width:none"><span>ACTIVE MODULE // HUNTER STATUS</span><span>ARCHIVE STATE // <span id="archiveStateLabel">LOCKED</span></span><span class="online">● SYSTEM STABLE</span></div>
<div class="tabs"><button class="active" data-tab="system">01 // SYSTEM / HUNTER</button><button data-tab="authority">02 // AUTHORITY / BODY SCAN</button><button data-tab="personal">03 // PERSONAL PROFILE</button><button data-tab="characterTheme">04 // SYSTEM THEME</button><button data-tab="custom">05 // CUSTOM DATA</button></div>
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
<div class="field"><label>Theme Name</label><input id="charThemeName" maxlength="40"></div>
<div class="field"><label>System Glyph</label><input id="charThemeGlyphInput" maxlength="4"></div>
<div class="field"><label>Visual Motif</label><select id="charThemeStyle"><option value="holo">Holographic</option><option value="alien">Alien / Orbital</option><option value="abyssal">Abyssal</option><option value="divine">Divine / Matriarch</option><option value="cute">Soft / Cute</option><option value="glitch">Glitched</option></select></div>
<div class="field"><label>Theme Note</label><input id="charThemeNote" maxlength="100"></div>
</div>
<div class="color-row" style="margin-top:12px"><div class="color-control"><label>Primary Glow</label><input id="charThemePrimary" type="color"></div><div class="color-control"><label>Secondary Glow</label><input id="charThemeSecondary" type="color"></div><div class="color-control"><label>Signal Color</label><input id="charThemeSignal" type="color"></div></div>
<div class="theme-actions" style="margin-top:12px"><button id="copyGlobalTheme">Copy Archive Theme</button><button id="resetCharTheme">Reset to Inherit</button></div>
</div>
<div class="card full"><h3>Portrait / Record Image</h3><div class="portrait-actions"><button id="portraitUpload">Upload Portrait</button><button id="portraitRemove">Remove Portrait</button><input id="portraitFile" type="file" accept="image/*" hidden></div></div>
</div></div>
</section>
<section id="custom" class="sheet"><div class="custom-editor"><div class="card full"><h3>Custom Character Data</h3><div id="customList" class="custom-list"></div><button id="addCustomField" style="margin-top:12px">＋ Add Custom Field</button></div></div></section>
</div>
</main>
</div>
<div id="modal" class="modal"><div class="panel">
<div class="panelhead"><div><h2>Archive Personalization</h2><small class="muted">Class Unknown System appearance.</small></div><button id="close">✕</button></div>
<div id="themeGrid" class="themegrid"></div>
<div class="setting"><div><b>Sound effects</b></div><label class="toggle"><input id="sound" type="checkbox"><span>Enabled</span></label></div>
<div class="setting"><div><b>Volume</b></div><input id="volume" type="range" min="0" max="100"></div>
<div class="setting"><div><b>Visual effects</b></div><select id="fx"><option value="off">Off</option><option value="low">Low</option><option value="full">Full</option></select></div>
<div class="setting"><div><b>UI density</b></div><select id="density"><option value="compact">Compact</option><option value="normal">Comfortable</option><option value="spacious">Spacious</option></select></div>
<div class="setting"><div><b>Text size</b></div><select id="font"><option value="14">Small</option><option value="16">Default</option><option value="18">Large</option><option value="20">Extra large</option></select></div>
<div class="setting"><div><b>Reduce motion</b></div><label class="toggle"><input id="reduce" type="checkbox"><span>Reduce</span></label></div>
<div class="row" style="margin-top:16px"><button id="reset">Reset overlay</button><button id="done">Done</button></div>
</div></div>
<script>
const ICON="";
const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
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
const FORMS={
system:[["Hunter Identification",[["Name","identity.name"],["Alias / Codename","identity.alias"],["Age","identity.age"],["Pronouns","identity.pronouns"],["Rank","hunter.rank"],["Class","hunter.class"],["Level","hunter.level"],["Affiliation","hunter.affiliation"]]],["Core Stats",[["Strength","stats.strength"],["Agility","stats.agility"],["Endurance","stats.endurance"],["Mana","stats.mana"],["Perception","stats.perception"],["Control","stats.control"]]],["System Classification",[["Type","hunter.type"],["Lineage","hunter.lineage"],["Status Effects","hunter.statusEffects","ta"],["System Notes","hunter.systemNotes","ta"]]],["Abilities",[["Skills / Authorities","hunter.abilities","ta"]]],["Equipment",[["Primary Weapon","gear.primaryWeapon"],["Secondary Weapon","gear.secondaryWeapon"],["Armor / Raid Gear","gear.armor","ta"],["Artifacts / Inventory","gear.artifacts","ta"]]]],
authority:[["Government Record",[["Registered Name","authority.registeredName"],["Hunter ID","authority.hunterId"],["Nationality","authority.nationality"],["Registration Status","authority.registrationStatus"],["Threat / Watch Status","authority.watchStatus"],["Clearance","authority.clearance"]]],["Body Scan",[["Height","appearance.height"],["Build","appearance.build"],["Hair","appearance.hair"],["Eyes","appearance.eyes"],["Skin","appearance.skin"],["Distinguishing Features","appearance.features"]]],["Medical / Mana Scan",[["Mana Signature","authority.manaSignature"],["Scan Reliability","authority.scanReliability"],["Physiological Notes","authority.physiology","ta"]]],["Authority Notes",[["Restrictions, anomalies, provenance, incident notes, classification warnings","authority.notes","ta"]]]],
personal:[["Personality",[["Core Traits","personal.personality","ta"]]],["Preferences",[["Likes","personal.likes","ta"],["Dislikes","personal.dislikes","ta"]]],["Habits & Social",[["Habits / Mannerisms","personal.habits","ta"],["Relationships / Social Notes","personal.relationships","ta"],["Relationship Links","personal.relationshipLinks","ta"]]],["Voice & Presentation",[["Voice / Accent / Speech","personal.voice","ta"],["Style / Fashion","personal.style","ta"]]],["Private System Profile",[["Additional Notes","personal.notes","ta"]]]]
};
function blank(){return{id:crypto.randomUUID?crypto.randomUUID():"c"+Date.now(),identity:{name:"",alias:"",age:"",pronouns:""},hunter:{rank:"",class:"",level:"",affiliation:"",type:"",lineage:"",statusEffects:"",systemNotes:"",abilities:""},stats:{strength:"",agility:"",endurance:"",mana:"",perception:"",control:""},gear:{primaryWeapon:"",secondaryWeapon:"",armor:"",artifacts:""},authority:{registeredName:"",hunterId:"",nationality:"",registrationStatus:"",watchStatus:"",clearance:"",manaSignature:"",scanReliability:"",physiology:"",notes:""},appearance:{height:"",build:"",hair:"",eyes:"",skin:"",features:""},personal:{personality:"",likes:"",dislikes:"",habits:"",relationships:"",relationshipLinks:"",voice:"",style:"",notes:""},systemTheme:{mode:"inherit",preset:"alien",name:"",primary:"#86f3ef",secondary:"#ffabc9",signal:"#aef7d7",glyph:"✦",style:"holo",note:""},media:{portrait:""},customFields:[]}}
function merge(a,b){if(!b)return a;for(const k in b)a[k]=typeof b[k]==="object"&&!Array.isArray(b[k])&&a[k]?merge(a[k],b[k]):b[k];return a}
let db;try{db=JSON.parse(getStore(SK)||'{"characters":[],"activeId":null}')}catch{db={characters:[],activeId:null}}
db.characters=(db.characters||[]).map(c=>merge(blank(),c));
let active=db.activeId,editMode=false,homeMode=!active;
const current=()=>db.characters.find(c=>c.id===active);
const read=(o,p)=>p.split(".").reduce((a,k)=>a?.[k],o)??"";
const write=(o,p,v)=>{let a=p.split("."),k=a.pop(),x=o;for(const q of a)x=x[q]??={};x[k]=v};
function presetTheme(k){let t=THEMES[k]||THEMES.system;return{name:t[0],primary:t[1],secondary:t[2],signal:t[3],glyph:t[4],style:t[7]}}
function resolvedTheme(c=current()){let f=presetTheme(settings.theme),s=c?.systemTheme;if(!s||s.mode==="inherit")return f;if(s.mode==="preset")return presetTheme(s.preset);return{name:s.name||"Character System",primary:s.primary||f.primary,secondary:s.secondary||f.secondary,signal:s.signal||f.signal,glyph:s.glyph||f.glyph,style:s.style||"holo"}}
function applyTheme(){let t=resolvedTheme(),r=document.documentElement;r.style.setProperty("--a",t.primary);r.style.setProperty("--b",t.secondary);r.style.setProperty("--c",t.signal);r.dataset.characterStyle=t.style;r.style.setProperty("--font-size",settings.font+"px");$("#systemPersonalization").textContent="SYSTEM THEME: "+t.name.toUpperCase()}
function save(){db.activeId=active;setStore(SK,JSON.stringify(db));$("#save").textContent=editMode?"Draft saved":"Saved & locked"}
function buildForms(){for(const s in FORMS){let g=$("#"+s+" .edit-grid");for(const [title,fields] of FORMS[s]){let c=document.createElement("div");c.className="card"+(fields.length===1?" full":"");c.innerHTML=`<h3>${title}</h3><div class="fields"></div>`;for(const [label,path,type] of fields){let f=document.createElement("div");f.className="field"+(type==="ta"?" full":"");f.innerHTML=`<label>${label}</label>${type==="ta"?`<textarea data-path="${path}"></textarea>`:`<input data-path="${path}">`}`;$(".fields",c).append(f)}g.append(c)}}}
function renderList(){let g=$("#charList");g.innerHTML="";for(const c of db.characters){let b=document.createElement("button");b.className="char";b.innerHTML=`<b>${c.identity.name||"Untitled Character"}</b><small>${c.hunter.class||resolvedTheme(c).name}</small>`;b.onclick=()=>{active=c.id;homeMode=false;editMode=false;render();save()};g.append(b)}}
function renderHome(){let g=$("#archiveGrid");g.innerHTML="";for(const c of db.characters){let t=resolvedTheme(c),b=document.createElement("button");b.className="archive-card";b.style.setProperty("--card1",t.primary);b.style.setProperty("--card2",t.secondary);b.innerHTML=`<span class="archive-glyph">${t.glyph}</span><span class="archive-name">${c.identity.name||"Untitled Character"}</span><span class="archive-alias">${c.identity.alias||t.name}</span>`;b.onclick=()=>{active=c.id;homeMode=false;render()};g.append(b)}}
function render(){renderList();renderHome();if(homeMode){$("#homeScreen").hidden=false;$("#editor").hidden=true;$("#empty").hidden=true;applyTheme();return}let c=current();$("#homeScreen").hidden=true;$("#editor").hidden=!c;$("#empty").hidden=!!c;if(!c)return;$("#title").textContent=c.identity.name||"Untitled Character";$$("[data-path]").forEach(e=>{e.value=read(c,e.dataset.path);e.readOnly=!editMode});$("#recordAction").textContent=editMode?"SAVE & LOCK":"ENTER EDIT MODE";$("#modePill").textContent=editMode?"EDIT MODE":"VIEW MODE";applyTheme()}
buildForms();
$$("[data-path]").forEach(e=>e.oninput=()=>{if(!editMode)return;write(current(),e.dataset.path,e.value);save()});
$$(".tabs button").forEach(b=>b.onclick=()=>{$$(".tabs button").forEach(x=>x.classList.remove("active"));$$(".sheet").forEach(x=>x.classList.remove("active"));b.classList.add("active");$("#"+b.dataset.tab).classList.add("active")});
$("#new").onclick=$("#homeNew").onclick=()=>{let c=blank();db.characters.unshift(c);active=c.id;homeMode=false;editMode=true;render();save()};
$("#homeBtn").onclick=()=>{homeMode=true;render()};
$("#recordAction").onclick=()=>{editMode=!editMode;render();save()};
$("#del").onclick=()=>{let c=current();if(c&&confirm("Delete this character?")){db.characters=db.characters.filter(x=>x.id!==c.id);active=null;homeMode=true;render();save()}};
$("#search").oninput=renderList;
$("#charThemeMode").onchange=$("#charThemePreset").onchange=$("#charThemeStyle").onchange=()=>{let c=current();if(!c||!editMode)return;c.systemTheme.mode=$("#charThemeMode").value;c.systemTheme.preset=$("#charThemePreset").value;c.systemTheme.style=$("#charThemeStyle").value;applyTheme();save()};
$("#charThemePrimary").oninput=$("#charThemeSecondary").oninput=$("#charThemeSignal").oninput=()=>{let c=current();if(!c||!editMode)return;c.systemTheme.mode="custom";c.systemTheme.primary=$("#charThemePrimary").value;c.systemTheme.secondary=$("#charThemeSecondary").value;c.systemTheme.signal=$("#charThemeSignal").value;applyTheme();save()};
$("#settings").onclick=$("#msettings").onclick=()=>$("#modal").classList.add("open");
$("#close").onclick=$("#done").onclick=()=>$("#modal").classList.remove("open");
if(active&&!current())active=null;
render();
</script>
<div id="toastHost"></div>
</body>
</html>

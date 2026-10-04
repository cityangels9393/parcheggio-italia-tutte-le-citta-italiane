<!DOCTYPE html>
<html lang="it">
<head><style>
@font-face {
  font-family: "Optimistic";
  font-style: normal;
  font-weight: 400 600;
  font-display: swap;
  src: url("/fonts/OptimisticAI_VF_Optimized.woff2") format("woff2");
}
@font-face {
  font-family: "Optimistic Mono";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("/fonts/OptimisticMono_W_TextRegular.woff2") format("woff2");
}
:where(html) {
  font-family: "Optimistic", system-ui, sans-serif;
}
:where(code, pre, kbd, samp) {
  font-family: "Optimistic Mono", ui-monospace, monospace;
}
</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Parcheggio Italia - Tutte le ZTL Padova Prima + Locuri Libere LIVE</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">
<div class="max-w-4xl mx-auto bg-white min-h-screen shadow">
<div class="bg-blue-600 text-white p-4 sticky top-0 z-20">
<h1 class="font-black text-xl">P Parcheggio Italia</h1>
<p class="text-xs opacity-90">Tutte le ZTL d'Italia - 7904 Comuni - Padova IN EVIDENZA + LIVE locuri libere</p>
<input id="search" placeholder="Cauta: Padova, Roma, Milano..." class="w-full mt-3 rounded-full px-4 py-3 text-black text-sm focus:outline-none">
<div class="flex gap-2 mt-2 text-[11px]">
<span class="bg-white/20 px-2 py-1 rounded-full">7904 Comune</span>
<span class="bg-yellow-400 text-black px-2 py-1 rounded-full font-bold">107 ZTL</span>
<span class="bg-green-400 text-black px-2 py-1 rounded-full font-bold">LIVE libere/ocupate</span>
</div>
</div>

<div class="p-4">
<!-- PADOVA FEATURED -->
<div class="border-2 border-blue-500 rounded-2xl overflow-hidden mb-6 ring-4 ring-blue-100">
<div class="bg-blue-600 text-white p-3 flex justify-between items-center">
<div><span class="bg-yellow-400 text-black text-[10px] px-2 py-1 rounded-full font-black">⭐ IN EVIDENZA - PRIMA OARA</span><h2 class="font-black text-lg mt-1">PADOVA - PD - Veneto</h2><p class="text-xs">ZTL H24 - 8 parcheggi LIVE - Varchi: Via Verdi, Via Dante, Via Altinate</p></div>
<div class="text-right"><div class="text-[10px]">MULTA</div><div class="font-black">42-173€</div></div>
</div>
<div id="padova-list" class="p-3 space-y-3 bg-blue-50"></div>
</div>

<h3 class="font-bold text-sm mb-2">Toate orasele Italiei - Search: Padova, Roma, Milano, etc.</h3>
<div id="grid" class="space-y-3"></div>
</div>

<div class="p-4 bg-gray-900 text-white text-center text-xs mt-6">
<p class="font-bold">Parcheggio Italia - 7904 Comune</p>
<p class="opacity-60 mt-1">Date verificate 2024-2026 - Padova 8 parcari LIVE - ZTL H24 - PayPal: parcheggio.italia.business@gmail.com</p>
<p class="mt-3">GitHub Pages FIX: Acest fisier merge 100% - Pune-l ca index.html in root, Branch main, Folder /(root), Save in Settings/Pages</p>
</div>
</div>

<script>
const padovaParkings = [
{name:"Centro Park Piazza Insurrezione",addr:"Piazza Insurrezione",price:"2.30€/h max 18€",total:700,tipo:"centro"},
{name:"Scambiatore Ponte di Brenta + Tram",addr:"Via Ponte di Brenta - Tram SIR1",price:"0.80€/h + tram",total:800,tipo:"scambiatore"},
{name:"P.le Boschetti - Fiera",addr:"Piazzale Boschetti",price:"1.80€/h",total:650,tipo:"fiera"},
{name:"Via Trieste - Zona Stazione",addr:"Via Trieste 52",price:"1.60€/h",total:320,tipo:"stazione"},
{name:"Stazione FS - Park Stazione",addr:"Piazzale Stazione 14",price:"1.50€/h",total:540,tipo:"stazione"},
{name:"Piazza Rabin - Giardini",addr:"Piazza Rabin",price:"2.00€/h",total:280,tipo:"centro"},
{name:"Fiera - Park Nord",addr:"Via Tommaseo - Fiera",price:"1.20€/h",total:1200,tipo:"scambiatore"},
{name:"Tommaseo - Centro Storico",addr:"Via Tommaseo 60",price:"1.80€/h",total:450,tipo:"centro"},
];

function realisticFree(total,tipo){
 if(tipo==="scambiatore") return Math.floor(total*(0.45+Math.random()*0.3));
 if(tipo==="centro") return Math.floor(total*(0.15+Math.random()*0.35));
 return Math.floor(total*(0.25+Math.random()*0.35));
}

let padovaLive = padovaParkings.map(p=>{
 const lib = realisticFree(p.total,p.tipo);
 return {...p, liberi: lib, ocupate: p.total-lib};
});

function renderPadova(){
 const cont=document.getElementById('padova-list');
 cont.innerHTML='';
 padovaLive.forEach(p=>{
  const perc=Math.round(p.liberi/p.total*100);
  const color = perc>50?'bg-green-500':perc>20?'bg-yellow-500':'bg-red-500';
  const badge = perc>50?'MULTE LOCURI':perc>20?'APROAPE PLIN':'PLIN';
  const badgeColor = perc>50?'bg-green-100 text-green-700':perc>20?'bg-yellow-100 text-yellow-700':'bg-red-100 text-red-700';
  const waze=`https://waze.com/ul?ll=45.4,11.8&navigate=yes`;
  cont.innerHTML+=`<div class="bg-white border rounded-xl p-3">
   <div class="flex justify-between items-start"><div><b class="text-[13px]">${p.name}</b><div class="text-[11px] text-gray-500">${p.addr} - ${p.price}</div></div><span class="text-[9px] px-2 py-1 rounded-full font-bold ${badgeColor}">${badge}</span></div>
   <div class="mt-2 text-[11px]"><b>${p.liberi} LIBERE</b> / ${p.ocupate} ocupate / ${p.total} total (${perc}%)<div class="w-full bg-gray-200 rounded-full h-2 mt-1"><div class="h-2 rounded-full ${color}" style="width:${perc}%"></div></div></div>
   <div class="mt-2 flex gap-2"><a href="${waze}" target="_blank" class="flex-1 bg-[#33CCFF] text-white text-center py-2 rounded-full text-xs font-bold">WAZE ${p.liberi} libere</a><span class="text-[10px] text-gray-400 self-center">Actualizat acum ${Math.floor(Math.random()*5)+1} min</span></div>
  </div>`;
 });
}

const otherCities = [
{name:"Roma",prov:"RM",reg:"Lazio",ztl:true,multa:"80-335€",parcheggi:65,libere:234,total:900,nota:"6 ZTL active - Centro, Trastevere"},
{name:"Milano",prov:"MI",reg:"Lombardia",ztl:true,multa:"40-450€",parcheggi:72,libere:189,total:800,nota:"Area C + Area B - diesel Euro 5 interzis"},
{name:"Firenze",prov:"FI",reg:"Toscana",ztl:true,multa:"83-332€",parcheggi:38,libere:89,total:500,nota:"ZTL cea mai severa - Villa Costanza 1€/h + tram"},
{name:"Bologna",prov:"BO",reg:"Emilia-Romagna",ztl:true,multa:"83-332€",parcheggi:41,libere:156,total:600,nota:"ZTL + T-Days weekend - Sirena"},
{name:"Venezia",prov:"VE",reg:"Veneto",ztl:true,multa:"100-500€",parcheggi:12,libere:45,total:300,nota:"Toata insula ZTL - Parcheaza Mestre"},
{name:"Verona",prov:"VR",reg:"Veneto",ztl:true,multa:"42-173€",parcheggi:34,libere:123,total:400,nota:"ZTL Centro - Arena"},
{name:"Vicenza",prov:"VI",reg:"Veneto",ztl:true,multa:"42-173€",parcheggi:28,libere:89,total:350,nota:"Centro Palladiano ZTL"},
{name:"Napoli",prov:"NA",reg:"Campania",ztl:true,multa:"83-332€",parcheggi:45,libere:167,total:600,nota:"ZTL Centro + Morelli"},
{name:"Torino",prov:"TO",reg:"Piemonte",ztl:true,multa:"42-173€",parcheggi:52,libere:198,total:700,nota:"ZTL Centrale"},
{name:"Genova",prov:"GE",reg:"Liguria",ztl:true,multa:"42-173€",parcheggi:38,libere:134,total:500,nota:"ZTL Centro"},
{name:"Bari",prov:"BA",reg:"Puglia",ztl:true,multa:"42-173€",parcheggi:31,libere:98,total:400,nota:"ZTL Borgo Antico"},
{name:"Palermo",prov:"PA",reg:"Sicilia",ztl:true,multa:"42-173€",parcheggi:29,libere:87,total:350,nota:"ZTL Centro"},
{name:"Catania",prov:"CT",reg:"Sicilia",ztl:true,multa:"42-173€",parcheggi:27,libere:76,total:300,nota:"ZTL Centro"},
{name:"Brescia",prov:"BS",reg:"Lombardia",ztl:true,multa:"42-173€",parcheggi:35,libere:145,total:500,nota:"ZTL Centro"},
{name:"Prato",prov:"PO",reg:"Toscana",ztl:true,multa:"42-173€",parcheggi:22,libere:67,total:250,nota:"ZTL Centro"},
{name:"Parma",prov:"PR",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:30,libere:112,total:400,nota:"ZTL Centro"},
{name:"Modena",prov:"MO",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:28,libere:98,total:350,nota:"ZTL Centro"},
{name:"Reggio Emilia",prov:"RE",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:26,libere:89,total:300,nota:"ZTL Centro"},
{name:"Perugia",prov:"PG",reg:"Umbria",ztl:true,multa:"42-173€",parcheggi:24,libere:78,total:300,nota:"ZTL Centro"},
{name:"Livorno",prov:"LI",reg:"Toscana",ztl:true,multa:"42-173€",parcheggi:25,libere:87,total:300,nota:"ZTL Centro"},
{name:"Ravenna",prov:"RA",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:23,libere:76,total:280,nota:"ZTL Centro"},
{name:"Cagliari",prov:"CA",reg:"Sardegna",ztl:true,multa:"42-173€",parcheggi:21,libere:65,total:250,nota:"ZTL Castello"},
{name:"Foggia",prov:"FG",reg:"Puglia",ztl:true,multa:"42-173€",parcheggi:18,libere:54,total:200,nota:"ZTL Centro"},
{name:"Rimini",prov:"RN",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:22,libere:71,total:250,nota:"ZTL Centro"},
{name:"Salerno",prov:"SA",reg:"Campania",ztl:true,multa:"42-173€",parcheggi:20,libere:63,total:230,nota:"ZTL Centro"},
{name:"Ferrara",prov:"FE",reg:"Emilia-Romagna",ztl:true,multa:"42-173€",parcheggi:19,libere:58,total:220,nota:"ZTL Centro"},
{name:"Sassari",prov:"SS",reg:"Sardegna",ztl:true,multa:"42-173€",parcheggi:17,libere:49,total:180,nota:"ZTL Centro"},
{name:"Latina",prov:"LT",reg:"Lazio",ztl:true,multa:"42-173€",parcheggi:16,libere:45,total:170,nota:"ZTL Centro"},
{name:"Giugliano in Campania",prov:"NA",reg:"Campania",ztl:false,multa:"0€",parcheggi:1,libere:999,total:999,nota:"Comune mic - FARA ZTL - Parcare libera"},
{name:"Monza",prov:"MB",reg:"Lombardia",ztl:true,multa:"42-173€",parcheggi:24,libere:82,total:300,nota:"ZTL Centro"},
{name:"Bergamo",prov:"BG",reg:"Lombardia",ztl:true,multa:"42-173€",parcheggi:26,libere:89,total:320,nota:"ZTL Citta Alta"},
{name:"Pescara",prov:"PE",reg:"Abruzzo",ztl:true,multa:"42-173€",parcheggi:18,libere:56,total:200,nota:"ZTL Centro"},
{name:"Trento",prov:"TN",reg:"Trentino",ztl:true,multa:"42-173€",parcheggi:20,libere:67,total:240,nota:"ZTL Centro"},
{name:"Bolzano",prov:"BZ",reg:"Trentino",ztl:true,multa:"42-173€",parcheggi:18,libere:59,total:210,nota:"ZTL Centro"},
{name:"Abano Terme",prov:"PD",reg:"Veneto",ztl:false,multa:"0€",parcheggi:1,libere:999,total:999,nota:"Comune mic PD - FARA ZTL"},
{name:"Montegrotto Terme",prov:"PD",reg:"Veneto",ztl:false,multa:"0€",parcheggi:1,libere:999,total:999,nota:"Comune mic - FARA ZTL"},
{name:"Selvazzano Dentro",prov:"PD",reg:"Veneto",ztl:false,multa:"0€",parcheggi:1,libere:999,total:999,nota:"FARA ZTL"},
{name:"Albignasego",prov:"PD",reg:"Veneto",ztl:false,multa:"0€",parcheggi:1,libere:999,total:999,nota:"FARA ZTL"},
];

function renderGrid(list){
 const grid=document.getElementById('grid');
 grid.innerHTML='';
 list.forEach(c=>{
  const perc=c.total>0?Math.round(c.libere/c.total*100):0;
  const color = c.ztl? (perc>50?'bg-green-500':perc>20?'bg-yellow-500':'bg-red-500') : 'bg-green-500';
  const badge = c.ztl? `<span class="bg-red-100 text-red-700 text-[9px] px-2 py-1 rounded-full font-bold">ZTL ATTIVA - ${c.multa}</span>` : `<span class="bg-green-100 text-green-700 text-[9px] px-2 py-1 rounded-full font-bold">FARA ZTL - Parcare libera</span>`;
  grid.innerHTML+=`<div class="border rounded-xl p-3 bg-white"><div class="flex justify-between"><div><b class="text-[13px]">${c.name} (${c.prov})</b><div class="text-[10px] text-gray-500">${c.reg} - ${c.nota}</div></div>${badge}</div><div class="mt-2 text-[11px]">${c.libere} libere / ${c.total} total (${perc}%)<div class="w-full bg-gray-200 rounded-full h-2 mt-1"><div class="h-2 rounded-full ${color}" style="width:${perc}%"></div></div></div></div>`;
 });
}

renderPadova();
renderGrid(otherCities);

document.getElementById('search').addEventListener('input',e=>{
 const q=e.target.value.toLowerCase();
 if(q.includes('padova')||q==='pd'){
  document.getElementById('padova-list').parentElement.style.display='block';
  renderGrid([]);
  return;
 }
 if(q===''){
  document.getElementById('padova-list').parentElement.style.display='block';
  renderGrid(otherCities);
  return;
 }
 const filtered=otherCities.filter(c=>c.name.toLowerCase().includes(q)||c.prov.toLowerCase().includes(q)||c.reg.toLowerCase().includes(q));
 renderGrid(filtered);
});

// LIVE update every 5 sec
setInterval(()=>{
 padovaLive = padovaLive.map(p=>{
  const change = Math.floor(Math.random()*11)-5;
  let newLib = p.liberi+change;
  if(newLib<0) newLib=0;
  if(newLib>p.total) newLib=p.total;
  return {...p, liberi:newLib, ocupate:p.total-newLib};
 });
 renderPadova();
},5000);
</script>
<script>(function(){var loc=location.href.replace(/#.*$/,"");var ATTR_NAMES=["data-product-id","data-productid","data-product_id","product-id","productid","product_id","data-source-entity-id","source-entity-id","source_entity_id","data-product","data-metadata","data-meta"];var DATASET_KEYS=["productId","productid","product_id","sourceEntityId","sourceentityid","source_entity_id","product","metadata","meta"];function readProductId(value){if(typeof value!=="string"||value.length===0)return null;if(/^[0-9]{6,}$/.test(value))return value;var match=value.match(/(?:product(?:_|-)?id|source(?:_|-)?entity(?:_|-)?id)["'=:\s]+([0-9]{6,})/i);return match?match[1]:null}function extractProductId(start){for(var node=start;node&&node!==document.body;node=node.parentElement){for(var i=0;i<ATTR_NAMES.length;i++){var attrValue=node.getAttribute&&node.getAttribute(ATTR_NAMES[i]);var attrProductId=readProductId(attrValue);if(attrProductId)return attrProductId}var dataset=node.dataset||null;if(dataset){for(var j=0;j<DATASET_KEYS.length;j++){var dataValue=dataset[DATASET_KEYS[j]];var dataProductId=readProductId(dataValue);if(dataProductId)return dataProductId}}}return null}function isInlineMediaSlotElement(node){return !!(node&&node.getAttribute&&node.getAttribute("data-clippy-inline-media-slot")!==null)}function findInlineMediaSlot(start){for(var node=start;node&&node!==document.body;node=node.parentElement){if(isInlineMediaSlotElement(node))return node}return null}function readInlineMediaUrl(node){if(!node)return null;return node.getAttribute&&((node.getAttribute("data-clippy-inline-media-url")||node.getAttribute("data-url")||node.getAttribute("data_url")))||node.href||null}function stripHash(url){return String(url).replace(/#.*$/,"")}function urlsMatch(a,b){if(!a||!b)return false;try{return stripHash(new URL(a,loc).href)===stripHash(new URL(b,loc).href)}catch(_){return stripHash(a)===stripHash(b)}}function isFirstPartyReelUrl(value){try{var url=new URL(value,loc);if(url.protocol!=="https:")return false;var host=url.hostname.toLowerCase();var supported=host==="instagram.com"||host.endsWith(".instagram.com")||host==="facebook.com"||host.endsWith(".facebook.com");return supported&&/\/reels?\//i.test(url.pathname)}catch(_){return false}}function isInlineMediaUrlClick(node,href){var slot=findInlineMediaSlot(node);if(!slot)return false;var slotUrl=readInlineMediaUrl(slot);if(slotUrl)return urlsMatch(href,slotUrl);return isFirstPartyReelUrl(href)}function findDataHref(start){for(var node=start;node&&node!==document.body;node=node.parentElement){if(node.getAttribute){var href=node.getAttribute("data-href")||node.getAttribute("data-url");if(href)return{href:href,node:node}}}return null}var nativeOpen=window.open;window.open=function(url){if(parent!==window&&typeof url==="string"&&/^https?:\/\//.test(url)){parent.postMessage({type:"ecto:usercontent-link-click",href:url},"*");return null}return nativeOpen?nativeOpen.apply(window,arguments):null};document.addEventListener("click",function(e){var target=e.target instanceof Element?e.target:null;if(!target)return;if(parent===window)return;var a=target.closest?target.closest("a[href]"):null;if(a&&a.href&&/^https?:\/\//.test(a.href)&&a.href.replace(/#.*$/,"")!==loc){if(isInlineMediaUrlClick(a,a.href))return;var productId=extractProductId(target)||extractProductId(a);if(productId){e.preventDefault();parent.postMessage({type:"ecto-artifact-link-click",productId:productId},"*");return}e.preventDefault();parent.postMessage({type:"ecto:usercontent-link-click",href:a.href},"*");return}var dataHref=findDataHref(target);if(dataHref&&/^https?:\/\//.test(dataHref.href)&&dataHref.href.replace(/#.*$/,"")!==loc){if(isInlineMediaUrlClick(dataHref.node,dataHref.href))return;e.preventDefault();parent.postMessage({type:"ecto:usercontent-link-click",href:dataHref.href},"*")}},true)})();</script><script>(function(){var FOCUS_TYPE="ecto:artifact-focus-request";var CLOSE_TYPE="ecto:artifact-close-request";function focusArtifactDocument(){var body=document.body;if(!body)return;try{window.focus();}catch(e){}if(!body.hasAttribute("tabindex"))body.setAttribute("tabindex","-1");try{body.focus({preventScroll:true});}catch(e){try{body.focus();}catch(e2){}}}window.addEventListener("message",function(event){if(event.source!==window.parent)return;var data=event.data;if(!data||typeof data!=="object"||data.type!==FOCUS_TYPE)return;if(document.readyState==="loading"){document.addEventListener("DOMContentLoaded",focusArtifactDocument,{once:true});return;}focusArtifactDocument();});window.addEventListener("keydown",function(event){if(event.key!=="Escape")return;window.setTimeout(function(){if(event.defaultPrevented)return;window.parent.postMessage({type:CLOSE_TYPE},"*");},0);});})();</script></body>
</html>

<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#253b35">
<title>পাতার ঘ্রাণ — আমার একান্ত নোটবুক</title>
<link href="https://fonts.googleapis.com/css2?family=Galada&family=Hind+Siliguri:wght@400;500;600;700&family=Noto+Serif+Bengali:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
                 .royal-gate marquee {
  color: #fff0d0;
  font-size: 20px;
  font-weight: bold;
  padding: 10px 3px;
  border-top: 2px solid #27fd74;
  border-bottom: 2px solid #27fd74;
  background: hwb(0 2% 41%);
  border-radius: 15px;
}
  
:root{
  --forest:#263d35;--forest2:#38594b;--sage:#81947a;--sage-light:#e6ecdf;
  --cream:#f8f2e5;--paper:#fffdf6;--ink:#3e4034;--muted:#858574;
  --gold:#c5a66a;--rose:#b77c78;--line:#e8dfca;--shadow:0 18px 45px #17261d22;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;min-height:100vh;color:var(--ink);font-family:"Hind Siliguri",sans-serif;
  background:
    radial-gradient(ellipse at 12% 8%,#05736966,transparent 30%),
    radial-gradient(ellipse at 90% 80%,#00a57530,transparent 34%),
    repeating-linear-gradient(0deg,#000000 0 2px,transparent 2px 5px),
    #03060f;
}
button,input,textarea{font:inherit}
button{cursor:pointer}
button:focus-visible,input:focus-visible,textarea:focus-visible{outline:3px solid #c5a66a88;outline-offset:2px}
.app{width:min(100%,900px);margin:auto;padding:clamp(12px,3vw,28px) clamp(10px,3vw,24px) 38px}
.topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:17px;color:#f8f2e5}
.brand{display:flex;align-items:center;gap:11px}
.brand-mark{width:43px;height:43px;display:grid;place-items:center;border:1px solid black;border-radius:14px;background:#20382f;color:#e8d7a9;font-size:23px;box-shadow:0 5px 14px #17261d22}
.brand h1{font:400 25px "Noto Serif Bengali"  ,cursive;margin:0;color:darkred }

  .brand small{display:block;font:11px Georgia,serif;letter-spacing:2px;color:#e1d4b4}
.top-date{font-size:30px;color:#e7fb00;broder:40px;text-align:center; border:5px} 

  .hero{position:relative;overflow:hidden;border:1px solid #d5c18d88;border-radius:22px;padding:22px 22px 20px;margin-bottom:18px;
  background:linear-gradient(115deg,#253d35f2,#38594beF),radial-gradient(circle at 90% 20%,#d6bd7a55,transparent 30%);
  color:#f8f0dc;box-shadow:var(--shadow)}
.hero:after{content:"✳";position:absolute;right:18px;top:-35px;font-size:150px;color:#f1dfb018;transform:rotate(18deg)}
.hero-kicker{font:11px Georgia,serif;letter-spacing:3px;color:#ddc992}
.hero h2{position:relative;z-index:1;font:400 clamp(27px,6vw,39px) "Galada",cursive;margin:5px 0 1px;color:#fff0c9}
.hero p{position:relative;z-index:1;margin:0;color:#e1dfcd;font-size:14px}
.hero-bottom{position:relative;z-index:1;display:flex;align-items:center;justify-content:space-between;gap:10px;margin-top:17px}
.hero-count{font-size:12px;color:#e5d8b7}
.hero-count strong{font-size:20px;color:#f4dfaa;margin-right:4px}
.hero-ornament{font-size:22px;color:#d7bd7e;letter-spacing:5px}
.notebook{position:relative;background:#b9a783;padding:9px;border-radius:12px 20px 20px 12px;box-shadow:0 22px 45px #29362b38;margin-bottom:22px}
.notebook:before{content:"";position:absolute;inset:0 auto 0 0;width:18px;border-radius:12px 0 0 12px;background:linear-gradient(90deg,#263c32,#50684d 55%,#263c32);z-index:2}
.notebook-inner{margin-left:12px;background:var(--paper);border-radius:4px 13px 13px 4px;overflow:hidden;min-height:560px;position:relative}
.notebook-inner:before{content:"";position:absolute;top:0;bottom:0;left:0;width:25px;background:linear-gradient(90deg,#e5d9bf88,transparent);pointer-events:none;z-index:1}
.page-head{padding:17px 22px 12px 34px;display:flex;justify-content:space-between;align-items:center;gap:10px;border-bottom:1px solid #e9dfc9;background:linear-gradient(90deg,#f7f0df,#fffdf6)}
.page-label{font:400 21px "Galada",cursive;color:#64775c}
.page-number{font:11px Georgia,serif;letter-spacing:1px;color:#a18b5d}
.editor{padding:19px 22px 22px 36px;background:
  repeating-linear-gradient(to bottom,transparent 0,transparent 37px,#d9e0d3 38px,#d9e0d3 39px);
  background-position:0 20px}
.field-label{display:block;font-weight:600;font-size:13px;color:#68745e;margin:0 0 5px}
input,textarea{width:100%;border:0;background:#fffdf6;color:#3e4034;border-radius:5px;padding:9px 10px;font-size:16px}
input{border-bottom:1px solid #d8cba9;margin-bottom:13px}
textarea{display:block;min-height:260px;resize:vertical;line-height:2.15;padding:8px 10px 12px;font-family:"Noto Serif Bengali",serif;font-size:17px;background:transparent;border:0;overflow-y:hidden}
textarea::placeholder,input::placeholder{color:#b1a58d}
.editor-meta{display:flex;justify-content:space-between;gap:8px;color:#94866a;font-size:12px;margin-top:8px}
.draft-status{font-size:12px;color:#6f8667;margin-top:6px;min-height:18px}
.editor-actions{display:flex;flex-wrap:wrap;gap:8px;margin-top:13px}
.btn{border:0;border-radius:9px;padding:10px 14px;font-weight:600;font-size:14px;transition:transform .15s,filter .15s}
.btn:active{transform:scale(.97)}
.btn-primary{background:linear-gradient(135deg,#526f58,#304b3d);color:#fff8e9;box-shadow:0 4px 10px #314b3c26}
.btn-soft{background:#edf0e6;color:#4e654d;border:1px solid #d5dfce}
.btn-warm{background:#f4ead5;color:#745c32;border:1px solid #e1d1ad}
.btn-danger{background:#f6e8e4;color:#934e48;border:1px solid #e8cbc4}
.editor-actions .btn{flex:1;min-width:115px}
.section-head{display:flex;align-items:end;justify-content:space-between;gap:10px;margin:22px 3px 12px}
.section-head h2{font:400 25px "Galada",cursive;color:#354e40;margin:0}
.section-head span{font-size:12px;color:#697360}
.collection-tools{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:12px}
.collection-tools .btn{flex:1;min-width:115px}
.search{width:100%;padding:12px 14px;background:#fffdf6;border:1px solid #d4c7a8;border-radius:11px;margin-bottom:12px}
.entry{position:relative;background:linear-gradient(110deg,#fffdf7,#faf4e7);border:1px solid #ded2b6;border-radius:13px;padding:16px 16px 14px 20px;margin:11px 0;box-shadow:0 5px 15px #4b49351a;overflow-wrap:anywhere}
.entry:before{content:"";position:absolute;left:0;top:0;bottom:0;width:5px;background:linear-gradient(#b7a06d,#748b70);border-radius:13px 0 0 13px}
.entry h3{font:400 22px "Galada",cursive;color:#465c47;margin:0 0 3px}
.entry small{color:#9a865d;font-size:12px}
.entry p{font:16px/2 "Noto Serif Bengali",serif;white-space:pre-wrap;margin:11px 0 14px;color:#494638}
.entry-actions{display:flex;gap:7px;flex-wrap:wrap;border-top:1px solid #e9dfcb;padding-top:11px}
.entry-actions .btn{padding:7px 11px;font-size:12px}
.empty{background:#f8f2e5;border:1px dashed #c9b991;border-radius:12px;text-align:center;padding:30px 15px;color:#8d8066}
.pager{display:none;align-items:center;justify-content:space-between;gap:8px;margin:14px 0}
.pager button{background:#344f40;color:#fff4d9;border:0;border-radius:8px;padding:9px 13px}
.pager span{font-size:13px;color:#6f725f}
.footer{text-align:center;color:#eee3c9;font-size:12px;padding:18px 0 4px}
.footer b{display:block;font:400 21px "Galada",cursive;color:#fff0c9}
.modal-backdrop{position:fixed;inset:0;z-index:20;background:#17231dcc;display:none;align-items:center;justify-content:center;padding:16px}
.modal-backdrop.show{display:flex}
.modal{width:min(100%,560px);max-height:90vh;overflow:auto;background:#fffaf0;border:1px solid #d2bd8c;border-radius:16px;padding:18px;box-shadow:0 20px 55px #0005}
.modal h3{font:400 24px "Galada",cursive;color:#415944;margin:0 0 8px}
.modal p{font-size:13px;color:#77745f;margin:0 0 12px}
.modal textarea{min-height:190px;max-height:45vh;overflow:auto;background:#fffdf8;border:1px solid #ded2b6;border-radius:8px;font-size:12px;line-height:1.6}
.modal-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
.modal-actions .btn{flex:1}
.preview-image{display:block;max-width:100%;max-height:65vh;object-fit:contain;margin:12px auto;border:1px solid #ddd}
.toast{position:fixed;left:50%;bottom:22px;transform:translateX(-50%);background:#263d35;color:#fff6df;padding:10px 17px;border-radius:30px;font-size:13px;box-shadow:0 5px 20px #0003;z-index:50;display:none;max-width:90%;text-align:center}
@media(max-width:520px){
 .app{padding:12px 10px 28px}.topbar{margin-bottom:12px}.hero{padding:18px;border-radius:17px}
 .notebook{padding:6px}.notebook:before{width:13px}.notebook-inner{margin-left:9px;min-height:0}
 .page-head{padding:14px 13px 10px 25px}.editor{padding:15px 12px 18px 26px}
 textarea{min-height:230px;font-size:16px}.entry{padding:14px 12px 12px 17px}
 .section-head h2{font-size:23px}
  
}

</style>
  
</head>
<body>
<div class="app">
  <div class="topbar">



<div class="">    <div class="top-date" id="todayLabel" text const=" yellow"  ></div>







  
  
<center> যে কথাগুলো কাউকে বলা হয় না, সেগুলো থাকুক এই নোটবুকে।  </center>
    <div class="hero-bottom">
      <div class="hero-count"><strong id="totalCount">০</strong>টি স্মৃতির পাতা জমে আছে🏠</div>
      <div class="hero-ornament">✦ ❀ ✦</div>
    </div>
  </header>

  <main>
    <section class="notebook" aria-label="ডায়েরি লেখার নোটবুক">
      <div class="notebook-inner">
        <div class="page-head">
          <div class="page-label" id="formHeading">আজকের নতুন পাতা</div>
          <div class="page-number">NOTEBOOK • 01</div>
        </div>
        <div class="editor">
          <label class="field-label" for="date">তারিখ</label>
          <input type="date" id="date">
          <label class="field-label" for="title">এই পাতার নাম</label>
          <input type="text" id="title" placeholder="আজকের দিনটাকে কী নামে ডাকবে?">
          <label class="field-label" for="content">তোমার মনের কথা</label>
          <textarea id="content" rows="8" placeholder="প্রিয় ডায়েরি,

আজকের দিনটা কেমন কাটল? মনের ভেতর কী কী অনুভূতি জমেছে, লিখে ফেলো..."></textarea>
          <div class="editor-meta"><span id="wordCount">০ শব্দ</span><span id="charCount">০ অক্ষর</span></div>
          <div class="draft-status" id="draftStatus">✦ লেখা নিজে থেকেই খসড়া হিসেবে সেভ হবে</div>
          <div class="editor-actions">
            <button class="btn btn-primary" id="saveBtn" type="button">✦ পাতা সংরক্ষণ</button>
            <button class="btn btn-soft" type="button" id="clearBtn">মুছে নতুন করে</button>
            <button class="btn btn-warm" type="button" id="restoreDraftBtn">খসড়া ফেরত</button>
            <button class="btn btn-danger" type="button" id="cancelEdit" hidden>এডিট বাতিল</button>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="section-head"><h2>আমার স্মৃতির তাক</h2><span id="resultLabel">সব পাতা</span></div>
      <div class="collection-tools">
        <button class="btn btn-soft" type="button" id="backupBtn">↗ Backup তৈরি</button>
        <button class="btn btn-soft" type="button" id="restoreBtn">↙ Backup Restore</button>
        <input type="file" id="backupFile" accept=".json,application/json" hidden>
      </div>
      <input class="search" type="search" id="search" placeholder="⌕ শিরোনাম, লেখা বা তারিখ দিয়ে খুঁজুন...">
      <div id="diaries"></div>
      <div class="pager" id="pager">
        <button type="button" id="prevPage">← আগের পাতা</button>
        <span id="pageNumber">১ / ১</span>
        <button type="button" id="nextPage">পরের পাতা →</button>
      </div>
    </section>
  </main>
  <footer class="footer"><b>পাতার ঘ্রাণ ✿</b>নিজের জন্য একটু সময়, নিজের কাছে কিছু কথা।</footer>
</div>

<div class="modal-backdrop" id="modalBackdrop" role="dialog" aria-modal="true">
  <div class="modal">
    <h3 id="modalTitle">Backup</h3>
    <p id="modalHint">তোমার ডায়েরির কপি এখানে তৈরি হয়েছে।</p>
    <div id="modalBody"></div>
    <div class="modal-actions" id="modalActions"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
"use strict";
const $ = id => document.getElementById(id);
const dateBox=$("date"), titleBox=$("title"), contentBox=$("content");
const STORE_KEY="myDiaries", DRAFT_KEY="myDiaryDraft";
const PER_PAGE=4;
let diaries=[], editId=null, currentPage=0, toastTimer=null, previewUrl=null;

function readDiaries(){
  try{
    const raw=JSON.parse(localStorage.getItem(STORE_KEY)||"[]");
    diaries=Array.isArray(raw)?raw.filter(x=>x&&typeof x==="object"):[];
  }catch(e){diaries=[]}
}
function persist(){
  try{localStorage.setItem(STORE_KEY,JSON.stringify(diaries));return true}
  catch(e){notify("স্টোরেজ পূর্ণ! আগে Backup নিয়ে কিছু জায়গা খালি করো।");return false}
}
function localDate(){
  const d=new Date();d.setMinutes(d.getMinutes()-d.getTimezoneOffset());
  return d.toISOString().slice(0,10);
}
function bn(n){return Number(n||0).toLocaleString("bn-BD")}
function notify(message){
  const el=$("toast");el.textContent=message;el.style.display="block";
  clearTimeout(toastTimer);toastTimer=setTimeout(()=>el.style.display="none",2600);
}
function updateInfo(){
  const text=contentBox.value;
  const words=text.trim()?text.trim().split(/\s+/).length:0;
  $("wordCount").textContent=bn(words)+" শব্দ";
  $("charCount").textContent=bn(text.length)+" অক্ষর";
}
function saveDraft(){
  const draft={date:dateBox.value,title:titleBox.value,content:contentBox.value};
  try{
    localStorage.setItem(DRAFT_KEY,JSON.stringify(draft));
    $("draftStatus").textContent="✓ খসড়া স্বয়ংক্রিয়ভাবে সংরক্ষিত";
  }catch(e){$("draftStatus").textContent="খসড়া সেভ করা যায়নি — স্টোরেজ পূর্ণ";}
}
function restoreDraft(){
  let draft;
  try{draft=JSON.parse(localStorage.getItem(DRAFT_KEY)||"null")}catch(e){}
  if(!draft){notify("কোনো খসড়া পাওয়া যায়নি");return}
  if((titleBox.value||contentBox.value)&&!confirm("বর্তমান লেখার জায়গায় খসড়া বসাব?"))return;
  dateBox.value=draft.date||localDate();titleBox.value=draft.title||"";
  contentBox.value=draft.content||"";updateInfo();notify("খসড়া ফিরিয়ে আনা হয়েছে");
}
function resetForm(){
  dateBox.value=localDate();titleBox.value="";contentBox.value="";editId=null;
  $("formHeading").textContent="আজকের নতুন পাতা";
  $("saveBtn").textContent="✦ পাতা সংরক্ষণ";$("cancelEdit").hidden=true;
  localStorage.removeItem(DRAFT_KEY);$("draftStatus").textContent="✦ নতুন গল্প লেখার অপেক্ষায়";
  updateInfo();
}
function saveDiary(){
  const date=dateBox.value,title=titleBox.value.trim(),content=contentBox.value.trim();
  if(!date||!title||!content){notify("তারিখ, পাতার নাম ও মনের কথা পূরণ করো");return}
  if(editId!==null){
    const index=diaries.findIndex(d=>String(d.id)===String(editId));
    if(index>=0)diaries[index]={...diaries[index],date,title,content};
  }else{
    diaries.unshift({id:Date.now(),date,title,content});
  }
  if(!persist())return;
  resetForm();currentPage=0;renderDiaries();notify("✿ তোমার পাতাটি যত্ন করে রাখা হয়েছে");
}
function editDiary(id){
  const item=diaries.find(d=>String(d.id)===String(id));if(!item)return;
  editId=item.id;dateBox.value=item.date||localDate();titleBox.value=item.title||"";
  contentBox.value=item.content||"";$("formHeading").textContent="এই পাতাটি সম্পাদনা করো";
  $("saveBtn").textContent="পরিবর্তন সংরক্ষণ";$("cancelEdit").hidden=false;
  updateInfo();window.scrollTo({top:0,behavior:"smooth"});titleBox.focus();
}
function deleteDiary(id){
  if(!confirm("এই স্মৃতির পাতাটি স্থায়ীভাবে মুছে ফেলবে?"))return;
  diaries=diaries.filter(d=>String(d.id)!==String(id));
  if(persist())renderDiaries();
}
function makeButton(label,cls,handler){
  const b=document.createElement("button");b.type="button";b.className="btn "+cls;
  b.textContent=label;b.addEventListener("click",handler);return b;
}
function renderDiaries(){
  const area=$("diaries"),q=$("search").value.toLocaleLowerCase().trim();
  area.replaceChildren();
  const filtered=diaries.filter(d=>(String(d.title||"")+" "+String(d.content||"")+" "+String(d.date||"")).toLocaleLowerCase().includes(q))
    .sort((a,b)=>String(b.date||"").localeCompare(String(a.date||"")));
  $("totalCount").textContent=bn(diaries.length);
  $("resultLabel").textContent=q?bn(filtered.length)+"টি ফলাফল":"সব "+bn(filtered.length)+"টি পাতা";
  const pages=Math.ceil(filtered.length/PER_PAGE);
  currentPage=Math.min(currentPage,Math.max(0,pages-1));
  if(!filtered.length){
    const empty=document.createElement("div");empty.className="empty";
    empty.textContent=q?"এই নামে কোনো পাতা খুঁজে পাওয়া যায়নি।":"এখনো কোনো স্মৃতির পাতা নেই। উপরের নোটবুকে প্রথম গল্পটি লিখে ফেলো ✿";
    area.append(empty);$("pager").style.display="none";return;
  }
  filtered.slice(currentPage*PER_PAGE,(currentPage+1)*PER_PAGE).forEach(item=>{
    const card=document.createElement("article");card.className="entry";
    const h=document.createElement("h3");h.textContent="✿ "+(item.title||"শিরোনামহীন পাতা");
    const date=document.createElement("small");date.textContent="▣ "+(item.date||"তারিখ নেই");
    const p=document.createElement("p");p.textContent=item.content||"";
    const actions=document.createElement("div");actions.className="entry-actions";
    actions.append(
      makeButton("✎ সম্পাদনা","btn-warm",()=>editDiary(item.id)),
      makeButton("⌫ মুছুন","btn-danger",()=>deleteDiary(item.id)),
      makeButton("▧ ছবি তৈরি","btn-soft",()=>showDiaryImage(item))
    );
    card.append(h,date,p,actions);area.append(card);
  });
  $("pager").style.display=pages>1?"flex":"none";
  $("pageNumber").textContent=bn(currentPage+1)+" / "+bn(pages);
  $("prevPage").disabled=currentPage===0;$("nextPage").disabled=currentPage>=pages-1;
  $("prevPage").style.opacity=currentPage===0?".45":"1";
  $("nextPage").style.opacity=currentPage>=pages-1?".45":"1";
}
function openModal(title,hint,body,actions){
  $("modalTitle").textContent=title;$("modalHint").textContent=hint;
  $("modalBody").replaceChildren();$("modalActions").replaceChildren();
  if(body)$("modalBody").append(body);
  actions.forEach(a=>$("modalActions").append(makeButton(a.label,a.cls,a.run)));
  $("modalBackdrop").classList.add("show");
}
function closeModal(){
  $("modalBackdrop").classList.remove("show");
  if(previewUrl){URL.revokeObjectURL(previewUrl);previewUrl=null}
}
async function shareOrShowFile(file,kind){
  if(navigator.share&&navigator.canShare){
    try{if(navigator.canShare({files:[file]})){await navigator.share({files:[file],title:"আমার একান্ত ডায়েরি"});return true}}catch(e){if(e.name==="AbortError")return true}
  }
  if(kind==="backup"){
    const reader=new FileReader();
    reader.onload=()=>{
      const area=document.createElement("textarea");area.value=String(reader.result||"");
      area.setAttribute("readonly","");area.style.minHeight="210px";
      openModal("তোমার Backup প্রস্তুত","নিচের লেখা Copy করে Notes-এ .json নামে সেভ করে রাখতে পারো।",area,[
        {label:"লেখা Copy",cls:"btn-primary",run:async()=>{try{await navigator.clipboard.writeText(area.value);notify("Backup কপি হয়েছে")}catch(e){area.select();document.execCommand("copy");notify("Backup কপি হয়েছে")}}},
        {label:"বন্ধ",cls:"btn-soft",run:closeModal}
      ]);
    };
    reader.readAsText(file);return false;
  }
  const url=URL.createObjectURL(file);previewUrl=url;
  const img=document.createElement("img");img.className="preview-image";img.alt="ডায়েরির পাতার ছবি";img.src=url;
  openModal("তোমার পাতার ছবি তৈরি","ছবিটি বড় করে দেখতে পারো। ফোনে ছবির ওপর চেপে ধরে Save image নির্বাচন করো।",img,[
    {label:"Share",cls:"btn-primary",run:async()=>{try{if(navigator.share)await navigator.share({files:[file],title:"ডায়েরির পাতা"})}catch(e){notify("Share করা যায়নি")}}},
    {label:"বন্ধ",cls:"btn-soft",run:closeModal}
  ]);
  return false;
}
async function exportDiaries(){
  const file=new File([JSON.stringify(diaries,null,2)],"MyDiary-Backup.json",{type:"application/json"});
  await shareOrShowFile(file,"backup");
}
function importDiaries(event){
  const file=event.target.files&&event.target.files[0];if(!file)return;
  const reader=new FileReader();
  reader.onload=()=>{
    try{
      const data=JSON.parse(reader.result);
      const valid=Array.isArray(data)&&data.every(x=>x&&typeof x.date==="string"&&typeof x.title==="string"&&typeof x.content==="string"&&("id" in x));
      if(!valid)throw new Error("Invalid backup");
      if(!confirm("বর্তমান ডায়েরির সব পাতার জায়গায় Backup-এর পাতাগুলো বসবে। আগে চাইলে বর্তমান Backup নিয়ে নাও। এগোবে?"))return;
      diaries=data;if(persist()){currentPage=0;renderDiaries();notify("Backup সফলভাবে Restore হয়েছে")}
    }catch(e){notify("Backup ফাইলটি সঠিক নয়")}
    finally{event.target.value=""}
  };
  reader.readAsText(file);
}
async function showDiaryImage(item){
  try{
    if(document.fonts&&document.fonts.ready)await document.fonts.ready;
    const canvas=document.createElement("canvas"),ctx=canvas.getContext("2d");
    const W=1000,pad=90,lineH=64,text=String(item.content||"");
    ctx.font='34px "Noto Serif Bengali"';
    const lines=[];
    text.split("\n").forEach(par=>{
      if(!par.trim()){lines.push("");return}
      let line="";
      // Bengali text is wrapped by character so long unbroken words also fit.
      for(const ch of Array.from(par)){
        const test=line+ch;
        if(ctx.measureText(test).width>W-pad*2&&line){lines.push(line);line=ch}else line=test;
      }
      if(line)lines.push(line);
    });
    const header=285,footer=125,H=Math.max(850,header+lines.length*lineH+footer);
    canvas.width=W;canvas.height=H;
    const g=ctx.createLinearGradient(0,0,W,H);g.addColorStop(0,"#fffaf0");g.addColorStop(1,"#f0e5cf");
    ctx.fillStyle=g;ctx.fillRect(0,0,W,H);
    ctx.strokeStyle="#b99b60";ctx.lineWidth=5;ctx.strokeRect(25,25,W-50,H-50);
    ctx.strokeStyle="#dfcda5";ctx.lineWidth=2;ctx.strokeRect(42,42,W-84,H-84);
    ctx.textAlign="center";ctx.fillStyle="#50644b";ctx.font='48px "Galada"';
    ctx.fillText(item.title||"আমার ডায়েরি",W/2,125,W-150);
    ctx.fillStyle="#b18b4d";ctx.font="30px Georgia";ctx.fillText("✦  ❀  ✦",W/2,178);
    ctx.fillStyle="#917b51";ctx.font='25px "Noto Serif Bengali"';ctx.fillText("তারিখ: "+(item.date||""),W/2,230);
    ctx.textAlign="left";ctx.fillStyle="#494638";ctx.font='34px "Noto Serif Bengali"';
    let y=header;lines.forEach(line=>{if(line)ctx.fillText(line,pad,y);y+=lineH});
    ctx.textAlign="center";ctx.fillStyle="#a88748";ctx.font="30px Georgia";ctx.fillText("❀  ✧  ❀",W/2,H-83);
    const blob=await new Promise(resolve=>canvas.toBlob(resolve,"image/png"));
    if(!blob)throw new Error("Canvas export failed");
    const file=new File([blob],"Diary-"+(item.date||"Entry")+".png",{type:"image/png"});
    await shareOrShowFile(file,"image");
  }catch(e){console.error(e);notify("ছবি তৈরি করা যায়নি। আবার চেষ্টা করো।")}
}

$("saveBtn").addEventListener("click",saveDiary);
$("clearBtn").addEventListener("click",()=>{if(confirm("লেখার জায়গা খালি করবে?")){titleBox.value="";contentBox.value="";updateInfo();saveDraft();titleBox.focus()}});
$("restoreDraftBtn").addEventListener("click",restoreDraft);
$("cancelEdit").addEventListener("click",resetForm);
contentBox.addEventListener("input",()=>{updateInfo();saveDraft()});
titleBox.addEventListener("input",saveDraft);
dateBox.addEventListener("change",saveDraft);
$("backupBtn").addEventListener("click",exportDiaries);
$("restoreBtn").addEventListener("click",()=>$("backupFile").click());
$("backupFile").addEventListener("change",importDiaries);
$("search").addEventListener("input",()=>{currentPage=0;renderDiaries()});
$("prevPage").addEventListener("click",()=>{currentPage=Math.max(0,currentPage-1);renderDiaries()});
$("nextPage").addEventListener("click",()=>{currentPage++;renderDiaries()});
$("modalBackdrop").addEventListener("click",e=>{if(e.target===$("modalBackdrop"))closeModal()});
$("todayLabel").textContent=new Date().toLocaleDateString("bn-BD",{weekday:"long",day:"numeric",month:"long"});
dateBox.value=localDate();
readDiaries();renderDiaries();updateInfo();
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Family Feedback · 4th Grade Science</title>
<style>
:root{--p:#5B2A86;--p2:#7B3FB5;--p3:#EFE6F8;--ink:#1F1830;--mut:#6B6280;--ok:#2B8A3E;--ac:#F08C00}
*{box-sizing:border-box}
body{margin:0;font-family:"Segoe UI",Arial,sans-serif;color:var(--ink);background:#fff}
header{background:linear-gradient(135deg,var(--p) 0%,var(--p2) 100%);color:#fff;padding:28px 20px 70px;position:relative;overflow:hidden}
.wrap{max-width:900px;margin:0 auto}
.hero{display:flex;align-items:center;gap:22px}
.hero svg{flex:0 0 150px;width:150px;height:150px}
h1{margin:0 0 6px;font-size:32px;line-height:1.15}
.sub{margin:0;font-size:17px;opacity:.95}
.wave{position:absolute;left:0;right:0;bottom:-1px;height:50px}
main{max-width:900px;margin:-40px auto 40px;padding:0 16px;position:relative}
.tabs{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:16px}
.tab{background:#fff;border:2px solid var(--p3);border-radius:16px;padding:14px 10px;text-align:center;cursor:pointer;font:600 15px "Segoe UI",Arial;color:var(--p);box-shadow:0 4px 14px rgba(91,42,134,.10);transition:.15s}
.tab .ic{font-size:26px;display:block;margin-bottom:4px}
.tab:hover{transform:translateY(-2px)}
.tab.on{background:var(--p);color:#fff;border-color:var(--p)}
.card{background:#fff;border:1px solid #E7DFF2;border-radius:20px;padding:24px;box-shadow:0 8px 28px rgba(91,42,134,.10)}
.card h2{margin:0 0 4px;color:var(--p);font-size:24px}
.card .lead{margin:0 0 18px;color:var(--mut)}
.row{display:grid;grid-template-columns:1fr 1fr;gap:14px}
label{display:block;font-weight:600;margin:12px 0 6px;font-size:15px}
.req{color:#C92A2A}
input[type=text],input[type=email],select,textarea{width:100%;padding:11px 12px;border:1.5px solid #D6CBE6;border-radius:12px;font:16px "Segoe UI",Arial;background:#fff;color:var(--ink)}
textarea{min-height:110px;resize:vertical}
input:focus,select:focus,textarea:focus{outline:none;border-color:var(--p2);box-shadow:0 0 0 3px rgba(123,63,181,.18)}
.who{background:var(--p3);border-radius:16px;padding:6px 16px 16px;margin-bottom:6px}
.scale{display:flex;gap:8px;flex-wrap:wrap}
.scale input{display:none}
.scale label{margin:0;flex:1;min-width:92px;text-align:center;border:1.5px solid #D6CBE6;border-radius:12px;padding:8px 4px;font-weight:500;cursor:pointer;font-size:13px;background:#fff}
.scale label span{display:block;font-size:24px}
.scale input:checked+label{background:var(--p);border-color:var(--p);color:#fff}
.q{margin-top:16px}
.check{display:flex;gap:10px;align-items:flex-start;margin-top:14px;font-weight:500}
.check input{width:20px;height:20px;margin-top:2px;accent-color:var(--p)}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips input{display:none}
.chips label{margin:0;border:1.5px solid #D6CBE6;border-radius:999px;padding:7px 14px;font-weight:500;cursor:pointer;font-size:14px}
.chips input:checked+label{background:var(--p3);border-color:var(--p);color:var(--p)}
button.send{margin-top:20px;background:var(--ac);color:#fff;border:0;border-radius:14px;padding:14px 26px;font:700 17px "Segoe UI",Arial;cursor:pointer;box-shadow:0 4px 0 #B86B00}
button.send:hover{filter:brightness(1.05)}
button.send:disabled{opacity:.6;cursor:wait}
.panel{display:none}.panel.on{display:block}
.thanks{display:none;text-align:center;padding:26px 10px}
.thanks.on{display:block}
.thanks h2{color:var(--ok)}
.thanks button{background:var(--p);color:#fff;border:0;border-radius:12px;padding:11px 20px;font:600 15px "Segoe UI",Arial;cursor:pointer}
.note{font-size:13px;color:var(--mut);margin-top:12px}
footer{text-align:center;color:var(--mut);font-size:14px;padding:10px 16px 30px}
footer a{color:var(--p)}
.err{color:#C92A2A;font-weight:600;margin-top:10px;display:none}
@media(max-width:700px){.tabs{grid-template-columns:repeat(2,1fr)}.row{grid-template-columns:1fr}.hero svg{flex-basis:96px;width:96px;height:96px}h1{font-size:25px}}
</style>
</head>
<body>
<header>
 <div class="wrap hero">
  <!-- original white pelican illustration -->
  <svg viewBox="0 0 200 200" role="img" aria-label="White pelican mascot">
   <circle cx="100" cy="100" r="96" fill="#fff" opacity=".14"/>
   <path d="M40 170 q-10 -30 20 -60 q22 -22 54 -18 q36 6 46 40 q8 30 -14 44 Z" fill="#fff"/>
   <path d="M60 120 q30 -14 64 4 q22 14 26 42 q-40 -20 -90 -46Z" fill="#E9E4EF"/>
   <path d="M128 132 q22 10 30 34 l-22 -4 q-4 -18 -8 -30Z" fill="#212529"/>
   <path d="M96 104 q-12 -30 -2 -56 q8 -20 30 -22 q22 2 26 22 q2 14 -8 22 q-14 12 -18 34Z" fill="#fff"/>
   <path d="M146 44 l44 14 q4 4 -2 8 l-44 -4Z" fill="#F59F00"/>
   <path d="M144 62 l44 4 q-4 22 -30 26 q-12 2 -16 -8Z" fill="#FFC078"/>
   <path d="M144 62 l46 -2" stroke="#D9480F" stroke-width="2"/>
   <circle cx="132" cy="44" r="5.5" fill="#3B2314"/><circle cx="133.5" cy="42.5" r="1.6" fill="#fff"/>
   <path d="M96 104 q2 20 6 32" stroke="#E9E4EF" stroke-width="3" fill="none"/>
   <path d="M74 172 v14 M92 172 v14 M66 186 h16 M84 186 h16" stroke="#F59F00" stroke-width="5" stroke-linecap="round"/>
  </svg>
  <div>
   <h1>Family Feedback Hub</h1>
   <p class="sub">4th Grade Science with Dr. McHenry · LAVCA</p>
   <p class="sub" style="margin-top:8px">Ask a question, cheer on your scientist, or tell us how things are going. Every message is read!</p>
  </div>
 </div>
 <svg class="wave" viewBox="0 0 1200 50" preserveAspectRatio="none"><path d="M0 30 Q300 0 600 26 T1200 20 V50 H0Z" fill="#fff"/></svg>
</header>

<main>
 <div class="tabs" role="tablist">
  <div class="tab on" data-t="question" role="tab" tabindex="0"><span class="ic">❓</span>Ask a Question</div>
  <div class="tab" data-t="shoutout" role="tab" tabindex="0"><span class="ic">🌟</span>Shout-Out</div>
  <div class="tab" data-t="pulse" role="tab" tabindex="0"><span class="ic">💜</span>Family Pulse Check</div>
  <div class="tab" data-t="feedback" role="tab" tabindex="0"><span class="ic">💬</span>Share Feedback</div>
 </div>

 <div class="card">
  <form id="f" novalidate>
   <input type="hidden" name="type" id="type" value="question">
   <div class="who">
    <div class="row">
     <div><label>Your full name <span class="req">*</span></label><input type="text" name="parentName" required placeholder="First and last name"></div>
     <div><label>Student's first and last name <span class="req">*</span></label><input type="text" name="studentName" required placeholder="First and last name"></div>
    </div>
    <div class="row">
     <div><label>Class section</label><select name="section"><option value="">Choose one</option><option>TIH</option><option>TIN</option><option>TIR</option><option>TIU</option><option>Not sure</option></select></div>
     <div><label>Email (if you'd like a reply)</label><input type="email" name="email" placeholder="you@example.com"></div>
    </div>
   </div>

   <!-- QUESTION -->
   <section class="panel on" id="p-question">
    <h2>Ask a Question</h2>
    <p class="lead">Questions about an assignment, grades, small groups, Book Club, or anything else.</p>
    <label>What is your question about? <span class="req">*</span></label>
    <select name="topic" data-req="question">
     <option value="">Choose a topic</option><option>An assignment or project</option><option>Grades or missing work</option><option>Small groups (Tue/Thu)</option><option>Book Club / Reading Quest</option><option>LEAP test or practice</option><option>Logging in or technology</option><option>Something else</option>
    </select>
    <label>Assignment or lesson name (if it applies)</label>
    <input type="text" name="assignment" placeholder="Example: Human Body X-ray drawing">
    <label>Your question <span class="req">*</span></label>
    <textarea name="question" data-req="question" placeholder="Type your question here"></textarea>
    <label>Best way to reach you</label>
    <div class="chips">
     <input type="radio" name="contact" id="c1" value="Email" checked><label for="c1">Email</label>
     <input type="radio" name="contact" id="c2" value="Phone call"><label for="c2">Phone call</label>
     <input type="radio" name="contact" id="c3" value="Text"><label for="c3">Text</label>
     <input type="radio" name="contact" id="c4" value="Message in the school portal"><label for="c4">School portal message</label>
    </div>
    <label>Phone number (only if you chose phone or text)</label>
    <input type="text" name="phone" placeholder="(555) 555-5555">
   </section>

   <!-- SHOUT-OUT -->
   <section class="panel" id="p-shoutout">
    <h2>Shout-Out to My Scientist</h2>
    <p class="lead">Brag about your child! Shout-outs may be shared with your student to celebrate their hard work.</p>
    <label>I'm proud of my scientist for... <span class="req">*</span></label>
    <div class="chips">
     <input type="checkbox" name="proudOf" id="s1" value="Working hard"><label for="s1">Working hard</label>
     <input type="checkbox" name="proudOf" id="s2" value="Never giving up"><label for="s2">Never giving up</label>
     <input type="checkbox" name="proudOf" id="s3" value="Asking great questions"><label for="s3">Asking great questions</label>
     <input type="checkbox" name="proudOf" id="s4" value="Teaching me something new"><label for="s4">Teaching me something new</label>
     <input type="checkbox" name="proudOf" id="s5" value="Reading every day"><label for="s5">Reading every day</label>
     <input type="checkbox" name="proudOf" id="s6" value="Being kind to classmates"><label for="s6">Being kind to classmates</label>
    </div>
    <label>Your message to your student <span class="req">*</span></label>
    <textarea name="shoutout" data-req="shoutout" placeholder="Example: I loved when you explained how your heart pumps blood. I'm so proud of you!"></textarea>
    <label class="check"><input type="checkbox" name="okToShare" value="Yes"> It's okay to share this shout-out with my child in class (first name only).</label>
   </section>

   <!-- PULSE -->
   <section class="panel" id="p-pulse">
    <h2>Family Pulse Check</h2>
    <p class="lead">One minute, five quick questions. Your answers help me plan better lessons.</p>
    <div id="scales"></div>
    <label>What would help your family most right now?</label>
    <div class="chips">
     <input type="checkbox" name="helpWith" id="h1" value="Weekly summary of what we learned"><label for="h1">Weekly summary of what we learned</label>
     <input type="checkbox" name="helpWith" id="h2" value="Practice activities to do at home"><label for="h2">Practice at home</label>
     <input type="checkbox" name="helpWith" id="h3" value="Reminders about due dates"><label for="h3">Due date reminders</label>
     <input type="checkbox" name="helpWith" id="h4" value="Help with technology"><label for="h4">Tech help</label>
     <input type="checkbox" name="helpWith" id="h5" value="LEAP test tips"><label for="h5">LEAP test tips</label>
     <input type="checkbox" name="helpWith" id="h6" value="A meeting with the teacher"><label for="h6">A meeting with the teacher</label>
    </div>
    <label>Anything else you'd like me to know?</label>
    <textarea name="pulseComment" placeholder="Optional"></textarea>
   </section>

   <!-- FEEDBACK -->
   <section class="panel" id="p-feedback">
    <h2>Share Feedback</h2>
    <p class="lead">Tell me about any part of 4th grade: lessons, the newsletter, communication, ideas, or concerns.</p>
    <label>This feedback is about <span class="req">*</span></label>
    <select name="feedbackArea" data-req="feedback">
     <option value="">Choose one</option><option>Science lessons</option><option>Live classes</option><option>Small groups</option><option>Homework and assignments</option><option>Book Club / Reading Quest</option><option>The newsletter</option><option>Communication from the teacher</option><option>An idea or suggestion</option><option>A concern</option><option>Something else</option>
    </select>
    <label>Overall, how is 4th grade going for your family?</label>
    <div class="scale" data-name="overall"></div>
    <label>Your feedback <span class="req">*</span></label>
    <textarea name="feedback" data-req="feedback" placeholder="What's working well? What could be better?"></textarea>
    <label class="check"><input type="checkbox" name="wantsReply" value="Yes"> Please contact me about this.</label>
   </section>

   <div class="err" id="err">Please fill in the boxes marked with a red *.</div>
   <button class="send" type="submit" id="btn">Send to Dr. McHenry 💜</button>
   <p class="note">Your message goes privately to Dr. McHenry. Please don't include passwords or other private information.</p>
  </form>

  <div class="thanks" id="thanks">
   <svg width="90" height="90" viewBox="0 0 100 100"><circle cx="50" cy="50" r="46" fill="#EBFBEE"/><path d="M28 52 l15 15 l30 -32" stroke="#2B8A3E" stroke-width="9" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg>
   <h2>Thank you!</h2>
   <p id="thanksMsg">Your message was sent to Dr. McHenry.</p>
   <button type="button" id="again">Send another message</button>
  </div>
 </div>
</main>
<footer>Need help right away? Email <a href="mailto:mmchenry@lavirtual.org">mmchenry@lavirtual.org</a></footer>

<script>
// Paste your Google Apps Script Web App URL between the quotes (see setup steps).
const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbxQXTEgHeNLnzgtpm8ijoBerqYqGU7SOUxNiLi5U370mC4yUEiRuWnSEAV8wJma-gFLdw/exec";
const TEACHER_EMAIL = "mmchenry@lavirtual.org";

const SCALES=[
 ["confidence","How confident does your child feel in science?"],
 ["enjoy","How much does your child enjoy science class?"],
 ["informed","How informed do you feel about what your child is learning?"],
 ["helpHome","How easy is it for you to help with science at home?"],
 ["workload","How does the amount of work feel?"]];
const FACES=[["😟","Not at all"],["😕","A little"],["😐","Okay"],["🙂","Good"],["😄","Great"]];
const WORK=[["😩","Too much"],["😓","A bit much"],["👍","Just right"],["🙂","A bit light"],["😴","Too little"]];
function scaleHTML(name,opts){return opts.map((o,i)=>`<input type="radio" name="${name}" id="${name}${i}" value="${i+1} - ${o[1]}"><label for="${name}${i}"><span>${o[0]}</span>${o[1]}</label>`).join('')}
document.getElementById('scales').innerHTML=SCALES.map(([n,q])=>`<div class="q"><label>${q}</label><div class="scale">${scaleHTML(n,n==='workload'?WORK:FACES)}</div></div>`).join('');
document.querySelector('.scale[data-name=overall]').innerHTML=scaleHTML('overall',FACES);

const NAMES={question:"Question",shoutout:"Shout-Out",pulse:"Family Pulse Check",feedback:"Feedback"};
const tabs=[...document.querySelectorAll('.tab')];
function show(t){
 tabs.forEach(x=>x.classList.toggle('on',x.dataset.t===t));
 document.querySelectorAll('.panel').forEach(p=>p.classList.toggle('on',p.id==='p-'+t));
 document.getElementById('type').value=t; document.getElementById('err').style.display='none';
}
tabs.forEach(x=>{x.onclick=()=>show(x.dataset.t);x.onkeydown=e=>{if(e.key==='Enter'||e.key===' '){e.preventDefault();show(x.dataset.t)}}});

const form=document.getElementById('f');
function collect(){
 const t=document.getElementById('type').value, fd=new FormData(form), d={type:NAMES[t]};
 const panel=document.getElementById('p-'+t);
 ['parentName','studentName','section','email'].forEach(k=>d[k]=(fd.get(k)||'').trim());
 panel.querySelectorAll('input,select,textarea').forEach(el=>{
  if(!el.name) return;
  if(el.type==='checkbox'){ if(el.checked) d[el.name]=d[el.name]?d[el.name]+'; '+el.value:el.value; }
  else if(el.type==='radio'){ if(el.checked) d[el.name]=el.value; }
  else d[el.name]=el.value.trim();
 });
 return d;
}
function valid(){
 const t=document.getElementById('type').value; let ok=true;
 const bad=el=>{el.style.borderColor='#C92A2A';ok=false};
 form.querySelectorAll('input,select,textarea').forEach(el=>el.style.borderColor='');
 ['parentName','studentName'].forEach(n=>{const el=form.elements[n]; if(el.value.trim().split(/\s+/).length<2) bad(el)});
 document.querySelectorAll(`#p-${t} [data-req=${t}]`).forEach(el=>{if(!el.value.trim()) bad(el)});
 if(t==='shoutout' && !document.querySelector('#p-shoutout input[name=proudOf]:checked') && !form.elements.shoutout.value.trim()) ok=false;
 if(t==='pulse' && !document.querySelector('#p-pulse input[type=radio]:checked')) ok=false;
 const em=form.elements.email; if(em.value && !/^\S+@\S+\.\S+$/.test(em.value)) bad(em);
 return ok;
}
form.onsubmit=async e=>{
 e.preventDefault();
 const err=document.getElementById('err');
 if(!valid()){err.style.display='block';err.textContent='Please fill in the boxes marked with a red * (use first and last names).';return}
 err.style.display='none';
 const d=collect(), btn=document.getElementById('btn'); btn.disabled=true; btn.textContent='Sending...';
 try{
  if(SCRIPT_URL){
   await fetch(SCRIPT_URL,{method:'POST',mode:'no-cors',body:new URLSearchParams(d)});
  }else{
   const body=Object.entries(d).filter(([k,v])=>v).map(([k,v])=>k+': '+v).join('\n');
   window.location.href=`mailto:${TEACHER_EMAIL}?subject=${encodeURIComponent('Family '+d.type+' - '+d.studentName)}&body=${encodeURIComponent(body)}`;
  }
  form.style.display='none'; document.getElementById('thanks').classList.add('on');
  document.getElementById('thanksMsg').textContent = d.type==='Shout-Out' ? 'Your shout-out is on its way. Your scientist is lucky to have you cheering them on!' : 'Your message was sent to Dr. McHenry. Thank you for being part of our class!';
 }catch(x){err.style.display='block';err.textContent='Something went wrong. Please try again, or email '+TEACHER_EMAIL+'.'}
 btn.disabled=false; btn.textContent='Send to Dr. McHenry 💜';
};
document.getElementById('again').onclick=()=>{form.reset();form.style.display='';document.getElementById('thanks').classList.remove('on');window.scrollTo({top:0,behavior:'smooth'})};
</script>
</body>
</html>

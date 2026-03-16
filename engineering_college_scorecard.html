<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Engineering College Scorecard</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --color-background-primary: #ffffff;
    --color-background-secondary: #f5f4f0;
    --color-background-tertiary: #eeede8;
    --color-background-info: #e6f1fb;
    --color-text-primary: #1a1a18;
    --color-text-secondary: #5f5e5a;
    --color-text-tertiary: #888780;
    --color-text-info: #185fa5;
    --color-border-tertiary: rgba(0,0,0,0.12);
    --color-border-secondary: rgba(0,0,0,0.22);
    --color-border-primary: rgba(0,0,0,0.35);
    --color-border-info: #b5d4f4;
    --font-sans: system-ui, -apple-system, sans-serif;
    --border-radius-md: 8px;
    --border-radius-lg: 12px;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --color-background-primary: #1e1e1c;
      --color-background-secondary: #2a2a28;
      --color-background-tertiary: #333331;
      --color-background-info: #0c2840;
      --color-text-primary: #f0efe8;
      --color-text-secondary: #a8a79f;
      --color-text-tertiary: #6e6d68;
      --color-text-info: #85b7eb;
      --color-border-tertiary: rgba(255,255,255,0.1);
      --color-border-secondary: rgba(255,255,255,0.18);
      --color-border-primary: rgba(255,255,255,0.28);
      --color-border-info: #185fa5;
    }
  }

  body {
    font-family: var(--font-sans);
    color: var(--color-text-primary);
    background: var(--color-background-tertiary);
    min-height: 100vh;
    padding: 2rem 1rem;
  }

  .container {
    max-width: 720px;
    margin: 0 auto;
    background: var(--color-background-primary);
    border-radius: var(--border-radius-lg);
    border: 0.5px solid var(--color-border-tertiary);
    padding: 2rem;
  }

  h2 { font-size: 20px; font-weight: 500; margin-bottom: 4px; }
  .sub { font-size: 13px; color: var(--color-text-secondary); margin-bottom: 1.5rem; }

  .tabs { display: flex; gap: 8px; margin-bottom: 1.5rem; flex-wrap: wrap; }
  .tab { padding: 6px 14px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); font-size: 13px; cursor: pointer; background: transparent; color: var(--color-text-secondary); font-family: var(--font-sans); }
  .tab.active { background: var(--color-background-secondary); color: var(--color-text-primary); border-color: var(--color-border-primary); font-weight: 500; }
  .tab:hover { background: var(--color-background-secondary); }

  .school-bar { display: flex; gap: 8px; align-items: center; margin-bottom: 1.25rem; }
  .school-bar input { flex: 1; padding: 7px 10px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); font-size: 14px; background: transparent; color: var(--color-text-primary); font-family: var(--font-sans); }
  .add-btn { padding: 7px 14px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); font-size: 13px; cursor: pointer; background: transparent; color: var(--color-text-primary); white-space: nowrap; font-family: var(--font-sans); }
  .add-btn:hover { background: var(--color-background-secondary); }

  .school-tabs { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 1.5rem; }
  .stab { padding: 5px 12px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); font-size: 13px; cursor: pointer; background: transparent; color: var(--color-text-secondary); display: flex; align-items: center; gap: 6px; font-family: var(--font-sans); }
  .stab.active { background: var(--color-background-info); color: var(--color-text-info); border-color: var(--color-border-info); }
  .stab .del { font-size: 11px; opacity: 0.6; cursor: pointer; }
  .stab .del:hover { opacity: 1; }

  .section { margin-bottom: 1.5rem; }
  .sec-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.04em; margin-bottom: 10px; padding-bottom: 6px; border-bottom: 0.5px solid var(--color-border-tertiary); }

  .row { display: flex; align-items: flex-start; gap: 10px; margin-bottom: 10px; }
  .row label { font-size: 13px; flex: 1; color: var(--color-text-primary); }
  .row .q { font-size: 11px; color: var(--color-text-tertiary); display: block; margin-top: 2px; }
  .stars { display: flex; gap: 3px; padding-top: 2px; }
  .star { width: 26px; height: 26px; cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 18px; line-height: 1; }

  .total-card { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; margin-bottom: 1.5rem; display: flex; align-items: center; justify-content: space-between; }
  .total-num { font-size: 32px; font-weight: 500; }
  .total-label { font-size: 13px; color: var(--color-text-secondary); }
  .tier { font-size: 13px; font-weight: 500; }

  .notes-area { width: 100%; margin-top: 8px; padding: 8px 10px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); font-size: 13px; resize: vertical; min-height: 60px; background: transparent; color: var(--color-text-primary); font-family: var(--font-sans); }

  .compare-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 12px; }
  .comp-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem; }
  .comp-name { font-size: 14px; font-weight: 500; margin-bottom: 8px; }
  .comp-total { font-size: 28px; font-weight: 500; margin-bottom: 2px; }
  .comp-tier { font-size: 12px; color: var(--color-text-secondary); margin-bottom: 10px; }
  .comp-row { display: flex; justify-content: space-between; font-size: 12px; padding: 3px 0; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .comp-row:last-child { border-bottom: none; }
  .comp-cat { color: var(--color-text-secondary); }
  .comp-val { font-weight: 500; }

  .empty { font-size: 13px; color: var(--color-text-tertiary); text-align: center; padding: 2rem; }

  .questions-sec { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; margin-bottom: 1rem; }
  .q-title { font-size: 13px; font-weight: 500; margin-bottom: 10px; }
  .q-item { font-size: 13px; color: var(--color-text-secondary); padding: 6px 0; border-bottom: 0.5px solid var(--color-border-tertiary); display: flex; gap: 8px; }
  .q-item:last-child { border-bottom: none; }
  .q-num { font-weight: 500; color: var(--color-text-primary); min-width: 18px; }
  .q-cat { font-size: 11px; color: var(--color-text-tertiary); margin-bottom: 2px; }
</style>
</head>
<body>
<div class="container">
  <div id="app"></div>
</div>

<script>
const CRITERIA = [
  { cat: "Academics & rigor", items: [
    { id: "rigor", label: "Academic rigor & challenge", q: "Ask: How hard are the intro engineering courses? What's the fail/drop rate?" },
    { id: "faculty", label: "Faculty accessibility", q: "Ask: How easy is it to get research or office hours time with professors?" },
    { id: "curriculum", label: "Curriculum flexibility", q: "Ask: Can you design your own track or take courses outside your major?" },
  ]},
  { cat: "Hands-on & experiential", items: [
    { id: "labs", label: "Lab & makerspace access", q: "Ask: Is the makerspace open 24/7? Do undergrads get real access or just seniors?" },
    { id: "projects", label: "Project-based learning", q: "Ask: What's the biggest hands-on project you did in your first two years?" },
    { id: "research", label: "Undergraduate research", q: "Ask: How many undergrads are in research labs? Is it competitive to get in?" },
    { id: "coop", label: "Co-op / internship pipeline", q: "Ask: What companies recruit here? How early can I start a co-op?" },
  ]},
  { cat: "Campus life & culture", items: [
    { id: "fit", label: "Vibe / culture fit", q: "Ask: What do engineers do on weekends? Is it collaborative or cutthroat?" },
    { id: "diversity", label: "Community & belonging", q: "Ask: What engineering clubs or teams are really active here?" },
    { id: "mental", label: "Student support & wellness", q: "Ask: What resources exist when you're overwhelmed during midterms?" },
  ]},
  { cat: "Outcomes & value", items: [
    { id: "jobs", label: "Career outcomes & recruiting", q: "Ask: Where did last year's grads go? What's the avg starting salary?" },
    { id: "network", label: "Alumni network strength", q: "Ask: Have you gotten internships or jobs through alumni connections?" },
    { id: "cost", label: "Cost & financial aid", q: "Ask admissions: What % of need is met? Are merit scholarships renewable?" },
  ]},
];

const QUESTIONS = [
  { cat: "Power question #1 — reality check", q: "\"Walk me through what freshman year engineering actually looked like for you. What surprised you most?\"" },
  { cat: "Power question #2 — hands-on access", q: "\"What's the most impressive hands-on project you've done, and how did you get the resources to make it happen?\"" },
  { cat: "Power question #3 — outcomes", q: "\"Where did your engineering friends end up — internships, jobs, grad school? How did the school help make that happen?\"" },
  { cat: "Bonus — culture", q: "\"Is this place collaborative or competitive? What happens when you're stuck on a problem set at midnight?\"" },
  { cat: "Bonus — access", q: "\"Can first-year students get into labs, join research, or lead clubs, or do you have to wait?\"" },
];

let schools = ["School 1"];
let activeSchool = 0;
let activeView = "rate";
let data = { "School 1": {} };

// Load data from localStorage
function loadData() {
  const savedSchools = localStorage.getItem('schools');
  const savedActiveSchool = localStorage.getItem('activeSchool');
  const savedActiveView = localStorage.getItem('activeView');
  const savedData = localStorage.getItem('data');
  
  if (savedSchools) schools = JSON.parse(savedSchools);
  if (savedActiveSchool !== null) activeSchool = parseInt(savedActiveSchool);
  if (savedActiveView) activeView = savedActiveView;
  if (savedData) data = JSON.parse(savedData);
}

// Save data to localStorage
function saveData() {
  localStorage.setItem('schools', JSON.stringify(schools));
  localStorage.setItem('activeSchool', activeSchool.toString());
  localStorage.setItem('activeView', activeView);
  localStorage.setItem('data', JSON.stringify(data));
}

// Load data on page load
loadData();

function getScore(sname) {
  const d = data[sname] || {};
  let total = 0, count = 0;
  CRITERIA.forEach(c => c.items.forEach(i => { if (d[i.id]) { total += d[i.id]; count++; } }));
  return count ? Math.round((total / (count * 5)) * 100) : 0;
}

function getCatScore(sname, cat) {
  const d = data[sname] || {};
  const items = CRITERIA.find(c => c.cat === cat)?.items || [];
  let total = 0, count = 0;
  items.forEach(i => { if (d[i.id]) { total += d[i.id]; count++; } });
  return count ? Math.round((total / (count * 5)) * 100) : 0;
}

function getTier(score) {
  if (score >= 85) return { label: "Strong fit", color: "#1D9E75" };
  if (score >= 65) return { label: "Good fit", color: "#378ADD" };
  if (score >= 45) return { label: "Worth considering", color: "#BA7517" };
  if (score > 0) return { label: "Probably not the one", color: "#E24B4A" };
  return { label: "Not yet rated", color: "#888780" };
}

function starColor(val, idx) {
  if (idx >= val) return "var(--color-border-secondary)";
  if (val >= 4) return "#1D9E75";
  if (val >= 3) return "#378ADD";
  if (val >= 2) return "#BA7517";
  return "#E24B4A";
}

function render() {
  const app = document.getElementById("app");
  const sname = schools[activeSchool];
  const d = data[sname] || {};
  const score = getScore(sname);
  const tier = getTier(score);

  let html = `<h2>Engineering school scorecard</h2><p class="sub">Rate each school on tour to find your best fit</p>`;

  html += `<div class="tabs">
    <button class="tab ${activeView==='rate'?'active':''}" onclick="setView('rate')">Rate a school</button>
    <button class="tab ${activeView==='questions'?'active':''}" onclick="setView('questions')">Tour guide questions</button>
    <button class="tab ${activeView==='compare'?'active':''}" onclick="setView('compare')">Compare schools</button>
  </div>`;

  if (activeView === "rate") {
    html += `<div class="school-bar">
      <input id="newname" placeholder="Add school name..." onkeydown="if(event.key==='Enter')addSchool()" />
      <button class="add-btn" onclick="addSchool()">+ Add school</button>
    </div>`;
    html += `<div class="school-tabs">`;
    schools.forEach((s, i) => {
      html += `<div class="stab ${i===activeSchool?'active':''}" onclick="selectSchool(${i})">
        ${s}<span class="del" onclick="event.stopPropagation();removeSchool(${i})">✕</span>
      </div>`;
    });
    html += `</div>`;

    if (score > 0) {
      html += `<div class="total-card">
        <div>
          <div class="total-label">Overall score</div>
          <div class="total-num">${score}<span style="font-size:18px;color:var(--color-text-secondary)">/100</span></div>
        </div>
        <div style="text-align:right">
          <div class="tier" style="color:${tier.color}">${tier.label}</div>
          <div class="total-label" style="margin-top:4px">${sname}</div>
        </div>
      </div>`;
    }

    CRITERIA.forEach(cat => {
      html += `<div class="section"><div class="sec-title">${cat.cat}</div>`;
      cat.items.forEach(item => {
        const val = d[item.id] || 0;
        html += `<div class="row">
          <div style="flex:1">
            <label>${item.label}</label>
            <span class="q">${item.q}</span>
          </div>
          <div class="stars">`;
        for (let i = 1; i <= 5; i++) {
          html += `<span class="star" onclick="rate('${item.id}',${i})" style="color:${starColor(val, i <= val ? val : 0)}">${i <= val ? "★" : "☆"}</span>`;
        }
        html += `</div></div>`;
      });
      html += `</div>`;
    });

    html += `<div class="section"><div class="sec-title">Notes & gut feeling</div>
      <textarea class="notes-area" placeholder="First impressions, things that stood out, questions you still have..."
        oninput="saveNote(this.value)">${d._notes||""}</textarea>
    </div>`;
  }

  if (activeView === "questions") {
    html += `<div class="questions-sec"><div class="q-title">Questions to ask your tour guide</div>`;
    QUESTIONS.forEach((q, i) => {
      html += `<div class="q-item"><span class="q-num">${i+1}</span><div><div class="q-cat">${q.cat}</div>${q.q}</div></div>`;
    });
    html += `</div>`;

    html += `<div class="questions-sec"><div class="q-title">Questions to ask admissions / financial aid</div>
      <div class="q-item"><span class="q-num">1</span><div><div class="q-cat">Financial</div>"What percentage of demonstrated financial need does the school meet on average, and are merit scholarships renewable?"</div></div>
      <div class="q-item"><span class="q-num">2</span><div><div class="q-cat">Outcomes</div>"What's the 4-year graduation rate for engineering, and what's the average starting salary for recent grads in my major?"</div></div>
      <div class="q-item"><span class="q-num">3</span><div><div class="q-cat">Access</div>"How many undergrads are in paid research positions, and what's the co-op or internship participation rate?"</div></div>
    </div>`;
  }

  if (activeView === "compare") {
    const rated = schools.filter(s => getScore(s) > 0);
    if (rated.length === 0) {
      html += `<div class="empty">Rate at least one school to see comparisons here.</div>`;
    } else {
      const sorted = [...rated].sort((a,b) => getScore(b)-getScore(a));
      html += `<div class="compare-grid">`;
      sorted.forEach(s => {
        const sc = getScore(s);
        const t = getTier(sc);
        html += `<div class="comp-card">
          <div class="comp-name">${s}</div>
          <div class="comp-total" style="color:${t.color}">${sc}</div>
          <div class="comp-tier">${t.label}</div>`;
        CRITERIA.forEach(cat => {
          const cs = getCatScore(s, cat.cat);
          html += `<div class="comp-row">
            <span class="comp-cat">${cat.cat.split(" ")[0]}</span>
            <span class="comp-val" style="color:${cs>=70?'#1D9E75':cs>=50?'#378ADD':cs>0?'#BA7517':'#888780'}">${cs>0?cs+'%':'—'}</span>
          </div>`;
        });
        html += `</div>`;
      });
      html += `</div>`;
    }
  }

  app.innerHTML = html;
}

function setView(v) { activeView = v; saveData(); render(); }
function selectSchool(i) { activeSchool = i; saveData(); render(); }
function addSchool() {
  const inp = document.getElementById("newname");
  const name = inp?.value?.trim();
  if (!name) return;
  if (!schools.includes(name)) { schools.push(name); data[name] = {}; }
  activeSchool = schools.indexOf(name);
  saveData();
  render();
}
function removeSchool(i) {
  if (schools.length === 1) return;
  delete data[schools[i]];
  schools.splice(i, 1);
  activeSchool = Math.min(activeSchool, schools.length - 1);
  saveData();
  render();
}
function rate(id, val) {
  const sname = schools[activeSchool];
  if (!data[sname]) data[sname] = {};
  data[sname][id] = (data[sname][id] === val) ? 0 : val;
  saveData();
  render();
}
function saveNote(val) {
  const sname = schools[activeSchool];
  if (!data[sname]) data[sname] = {};
  data[sname]._notes = val;
  saveData();
}

// Load data on page load
loadData();

render();
</script>
</body>
</html>

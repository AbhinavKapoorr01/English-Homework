<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GSSS Jahu - Academic Portal</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --primary: #4f46e5;
    --secondary: #0ea5e9;
    --bg-grad: linear-gradient(135deg, #0f172a, #1e293b);
    --glass: rgba(255, 255, 255, 0.1);
    --border: rgba(255, 255, 255, 0.15);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
  
  body { 
    min-height: 100vh; background: var(--bg-grad); color: white; 
    display: flex; justify-content: center; align-items: flex-start; 
    padding: 20px; 
  }

  .app-container {
    width: 100%; max-width: 1000px;
    background: var(--glass); backdrop-filter: blur(12px);
    border: 1px solid var(--border);
    border-radius: 24px; padding: 30px;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
    margin-top: 20px;
  }

  /* --- Navigation Views --- */
  .view-section { display: none; animation: fadeIn 0.3s ease-in-out; }
  .view-section.active { display: block; }
  @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

  /* --- UI Elements --- */
  h1 { text-align: center; font-size: 1.8rem; font-weight: 700; margin-bottom: 5px; }
  .subtitle { text-align: center; color: #94a3b8; margin-bottom: 25px; font-size: 0.9rem; }
  
  .grid-menu { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 20px; margin-top: 20px; }
  
  .nav-card {
    background: rgba(255,255,255,0.05); padding: 25px; border-radius: 16px;
    border: 1px solid var(--border); text-align: center; cursor: pointer;
    transition: all 0.2s ease;
  }
  .nav-card:hover { background: rgba(255,255,255,0.1); transform: translateY(-3px); border-color: var(--secondary); }
  .nav-icon { font-size: 2rem; margin-bottom: 10px; display: block; }

  /* --- Inputs & Buttons --- */
  input, select, textarea {
    width: 100%; background: rgba(15, 23, 42, 0.8); border: 1px solid var(--border);
    color: white; padding: 12px 15px; border-radius: 8px; margin-top: 8px;
    font-size: 1rem; outline: none; transition: 0.2s;
  }
  input:focus, textarea:focus { border-color: var(--secondary); box-shadow: 0 0 0 2px rgba(14, 165, 233, 0.2); }
  
  button {
    width: 100%; background: var(--primary); color: white;
    padding: 14px; border: none; border-radius: 8px; font-weight: 600;
    margin-top: 20px; cursor: pointer; transition: 0.2s; font-size: 1rem;
  }
  button:hover { background: #4338ca; }
  button.secondary { background: rgba(255,255,255,0.1); margin-top: 0; width: auto; padding: 8px 20px; margin-bottom: 15px; }
  button.delete { background: #ef4444; }

  /* --- Tables --- */
  .table-container { overflow-x: auto; max-height: 60vh; margin-top: 15px; border-radius: 12px; border: 1px solid var(--border); }
  table { width: 100%; border-collapse: collapse; min-width: 600px; }
  th { background: #1e293b; color: #94a3b8; font-weight: 600; text-transform: uppercase; font-size: 0.8rem; position: sticky; top: 0; z-index: 10; }
  th, td { padding: 12px 15px; text-align: left; border-bottom: 1px solid var(--border); }
  td input { margin: 0; background: transparent; border: 1px solid transparent; padding: 5px; }
  td input:focus { background: rgba(0,0,0,0.3); border-color: var(--secondary); }

  /* --- Lists --- */
  .list-item {
    background: rgba(255,255,255,0.03); padding: 15px; margin-bottom: 10px;
    border-radius: 10px; display: flex; justify-content: space-between; align-items: center;
    border-left: 4px solid var(--secondary); cursor: pointer;
  }
  .list-item:hover { background: rgba(255,255,255,0.08); }

  /* --- Toast Notification --- */
  #toast {
    visibility: hidden; min-width: 250px; background-color: #10b981; color: white;
    text-align: center; border-radius: 8px; padding: 16px; position: fixed; z-index: 100;
    bottom: 30px; left: 50%; transform: translateX(-50%);
  }
  #toast.show { visibility: visible; animation: fadein 0.5s, fadeout 0.5s 2.5s; }
  @keyframes fadein { from{bottom: 0; opacity: 0;} to{bottom: 30px; opacity: 1;} }
  @keyframes fadeout { from{bottom: 30px; opacity: 1;} to{bottom: 0; opacity: 0;} }
</style>
</head>
<body>

<div class="app-container">
  <h1>English Homework & Marks</h1>
  <p class="subtitle">GSSS Jahu • Class 11th Portal</p>

  <div id="view-dashboard" class="view-section active">
    <div class="grid-menu">
      <div class="nav-card" onclick="navTo('view-homework')">
        <span class="nav-icon">📘</span>
        <h3>Check Homework</h3>
        <p style="font-size:0.8rem; opacity:0.7; margin-top:5px">View today's assignments</p>
      </div>
      <div class="nav-card" onclick="navTo('view-history'); loadTestHistory();">
        <span class="nav-icon">📊</span>
        <h3>Check Marks</h3>
        <p style="font-size:0.8rem; opacity:0.7; margin-top:5px">View test results</p>
      </div>
      <div class="nav-card" onclick="navTo('view-login')">
        <span class="nav-icon">🔐</span>
        <h3>Admin Login</h3>
        <p style="font-size:0.8rem; opacity:0.7; margin-top:5px">Teachers only</p>
      </div>
    </div>
  </div>

  <div id="view-homework" class="view-section">
    <button class="secondary" onclick="navTo('view-dashboard')">← Back</button>
    <h3 style="text-align:center; margin-bottom:20px;">Today's Homework</h3>
    <div id="display-hw" style="white-space: pre-wrap; background: rgba(255,255,255,0.05); padding: 20px; border-radius: 10px; min-height: 150px; line-height: 1.6;">
      Loading...
    </div>
  </div>

  <div id="view-history" class="view-section">
    <button class="secondary" onclick="navTo('view-dashboard')">← Back</button>
    <h3 style="text-align:center; margin-bottom:20px;">Recent Tests</h3>
    <div id="list-history"></div>
  </div>

  <div id="view-result" class="view-section">
    <button class="secondary" onclick="navTo('view-history')">← Back</button>
    <div style="background: rgba(79, 70, 229, 0.2); padding: 15px; border-radius: 10px; margin-bottom: 20px; text-align: center;">
      <h2 id="res-title" style="font-size:1.4rem"></h2>
      <p>Max Marks: <strong id="res-max"></strong> | Date: <span id="res-date"></span></p>
    </div>

    <select id="res-stream-select" onchange="renderResultTable(this.value)">
      <option value="">-- Select Stream to View --</option>
      <option value="arts">Arts (201 - 230)</option>
      <option value="science">Science (251 - 277)</option>
      <option value="commerce">Commerce (286 - 305)</option>
    </select>

    <div class="table-container" id="res-table-container"></div>
  </div>

  <div id="view-login" class="view-section">
    <button class="secondary" onclick="navTo('view-dashboard')">← Back</button>
    <div style="max-width: 400px; margin: 0 auto; text-align: center;">
      <h3>Teacher Access</h3>
      <input type="text" id="admin-id" placeholder="Username">
      <input type="password" id="admin-pass" placeholder="Password">
      <button onclick="login()">Login</button>
    </div>
  </div>

  <div id="view-admin" class="view-section">
    <div style="display:flex; justify-content:space-between; align-items:center;">
      <h3>Admin Panel</h3>
      <button class="secondary" style="background:#ef4444; margin:0;" onclick="navTo('view-dashboard')">Logout</button>
    </div>
    <div class="grid-menu">
      <div class="nav-card" onclick="navTo('view-edit-hw'); loadAdminHomework();">
        <span class="nav-icon">✏️</span>
        <h3>Update Homework</h3>
      </div>
      <div class="nav-card" onclick="navTo('view-add-marks'); resetMarksForm();">
        <span class="nav-icon">📝</span>
        <h3>Upload New Marks</h3>
      </div>
    </div>
  </div>

  <div id="view-edit-hw" class="view-section">
    <button class="secondary" onclick="navTo('view-admin')">← Back</button>
    <h3>Edit Homework</h3>
    <textarea id="input-hw" style="height: 200px;" placeholder="Type today's homework here..."></textarea>
    <button onclick="saveHomework()">Update Homework</button>
  </div>

  <div id="view-add-marks" class="view-section">
    <button class="secondary" onclick="navTo('view-admin')">← Back</button>
    <h3>Create New Test Result</h3>
    
    <div style="display:grid; grid-template-columns: 2fr 1fr; gap: 10px; margin-bottom: 20px;">
      <input id="new-test-title" placeholder="Test Title (e.g. Unit Test 1)">
      <input id="new-test-max" type="number" placeholder="Max Marks">
    </div>

    <div style="background: rgba(255,255,255,0.05); padding: 15px; border-radius: 10px; border: 1px solid var(--secondary);">
      <label style="font-size:0.9rem; color:#94a3b8;">Current Stream:</label>
      <select id="input-stream" onchange="renderEntryTable()">
        <option value="">Select Stream to Enter Data...</option>
        <option value="arts">Arts (201-230)</option>
        <option value="science">Science (251-277)</option>
        <option value="commerce">Commerce (286-305)</option>
      </select>
    </div>

    <div class="table-container" id="entry-table-container" style="display:none;">
      <table id="entry-table">
        </table>
    </div>

    <button onclick="publishTest()">💾 PUBLISH TEST</button>
  </div>

</div>

<div id="toast">Saved Successfully!</div>

<script>
// --- CONFIGURATION ---
const CREDENTIALS = { user: "Abhinav Kapoor", pass: "hypocrite@123" };
const RANGES = {
  arts: { min: 201, max: 230 },
  science: { min: 251, max: 277 },
  commerce: { min: 286, max: 305 }
};

// --- GLOBAL STATE ---
// This holds the marks you are currently typing before you hit Publish
let currentSessionData = { arts: {}, science: {}, commerce: {} };

// --- INITIALIZATION ---
window.onload = function() {
  const hw = localStorage.getItem('HOMEWORK_DB') || "No homework yet.";
  document.getElementById('display-hw').innerText = hw;
};

// --- NAVIGATION ---
function navTo(id) {
  document.querySelectorAll('.view-section').forEach(el => el.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}

function showToast(msg) {
  const t = document.getElementById("toast");
  t.innerText = msg;
  t.className = "show";
  setTimeout(() => { t.className = t.className.replace("show", ""); }, 3000);
}

// --- AUTH ---
function login() {
  const u = document.getElementById('admin-id').value;
  const p = document.getElementById('admin-pass').value;
  if(u === CREDENTIALS.user && p === CREDENTIALS.pass) {
    document.getElementById('admin-pass').value = ''; 
    navTo('view-admin');
  } else {
    alert("Incorrect Username or Password");
  }
}

// --- HOMEWORK LOGIC ---
function loadAdminHomework() {
  document.getElementById('input-hw').value = localStorage.getItem('HOMEWORK_DB') || "";
}

function saveHomework() {
  const text = document.getElementById('input-hw').value;
  localStorage.setItem('HOMEWORK_DB', text);
  document.getElementById('display-hw').innerText = text;
  showToast("Homework Updated!");
  navTo('view-admin');
}

// --- MARKS ENTRY LOGIC (CRITICAL FIX) ---
function resetMarksForm() {
  currentSessionData = { arts: {}, science: {}, commerce: {} };
  document.getElementById('new-test-title').value = "";
  document.getElementById('new-test-max').value = "";
  document.getElementById('input-stream').value = "";
  document.getElementById('entry-table-container').style.display = "none";
}

function renderEntryTable() {
  const stream = document.getElementById('input-stream').value;
  const container = document.getElementById('entry-table-container');
  const table = document.getElementById('entry-table');
  
  if(!stream) { container.style.display = "none"; return; }
  
  // Get Saved Student Names (Persistent DB)
  const studentDB = JSON.parse(localStorage.getItem('STUDENT_NAMES_DB') || '{}');
  const streamNames = studentDB[stream] || {};
  
  const range = RANGES[stream];
  
  let html = `<thead><tr><th width="15%">Roll</th><th>Name</th><th width="25%">Marks</th></tr></thead><tbody>`;
  
  for(let r = range.min; r <= range.max; r++) {
    // 1. Check if we typed something in this session
    // 2. If not, check if we have a saved name in DB
    // 3. Else empty
    const sessionVal = currentSessionData[stream][r] || {};
    const displayName = sessionVal.name !== undefined ? sessionVal.name : (streamNames[r] || '');
    const displayMark = sessionVal.marks || '';

    html += `<tr>
      <td><strong>${r}</strong></td>
      <td><input type="text" placeholder="Student Name" value="${displayName}" oninput="updateSession('${stream}', ${r}, 'name', this.value)" tabindex="1"></td>
      <td><input type="number" placeholder="Marks" value="${displayMark}" oninput="updateSession('${stream}', ${r}, 'marks', this.value)" tabindex="2"></td>
    </tr>`;
  }
  
  html += `</tbody>`;
  table.innerHTML = html;
  container.style.display = "block";
}

// Saves data to temporary memory immediately when typing
function updateSession(stream, roll, field, value) {
  if(!currentSessionData[stream][roll]) currentSessionData[stream][roll] = {};
  currentSessionData[stream][roll][field] = value;
}

function publishTest() {
  const title = document.getElementById('new-test-title').value;
  const max = document.getElementById('new-test-max').value;
  
  if(!title || !max) { alert("Please enter Test Title and Max Marks."); return; }
  
  // 1. Update Persistent Student Name Database
  const studentDB = JSON.parse(localStorage.getItem('STUDENT_NAMES_DB') || '{}');
  
  // 2. Build Final Result Object
  const finalResults = { arts: {}, science: {}, commerce: {} };
  
  ['arts', 'science', 'commerce'].forEach(stream => {
    if(!studentDB[stream]) studentDB[stream] = {};
    const range = RANGES[stream];
    
    for(let r = range.min; r <= range.max; r++) {
      const sessionEntry = currentSessionData[stream][r] || {};
      
      // Determine Name: Typed > DB > Empty
      const name = sessionEntry.name || studentDB[stream][r] || '';
      // If name exists, save to DB for future
      if(name) studentDB[stream][r] = name;
      
      finalResults[stream][r] = {
        name: name,
        marks: sessionEntry.marks || 'Abs'
      };
    }
  });
  
  // Save Names
  localStorage.setItem('STUDENT_NAMES_DB', JSON.stringify(studentDB));
  
  // 3. Save to History
  const history = JSON.parse(localStorage.getItem('TEST_HISTORY') || '[]');
  history.push({
    id: Date.now(),
    title: title,
    max: max,
    date: new Date().toLocaleDateString(),
    data: finalResults
  });
  localStorage.setItem('TEST_HISTORY', JSON.stringify(history));
  
  showToast("Test Published Successfully!");
  navTo('view-admin');
}

// --- HISTORY VIEWER ---
let loadedTestData = null;

function loadTestHistory() {
  const list = document.getElementById('list-history');
  const history = JSON.parse(localStorage.getItem('TEST_HISTORY') || '[]');
  
  if(history.length === 0) {
    list.innerHTML = "<p style='text-align:center; opacity:0.6'>No tests found.</p>";
    return;
  }
  
  let html = '';
  history.slice().reverse().forEach((test, idx) => {
    const realIdx = history.length - 1 - idx;
    html += `
      <div class="list-item" onclick="openTestResult(${realIdx})">
        <div>
          <div style="font-weight:700; font-size:1.1rem">${test.title}</div>
          <div style="font-size:0.85rem; opacity:0.7">${test.date}</div>
        </div>
        <div style="font-weight:600; font-size:1.5rem">→</div>
      </div>
    `;
  });
  list.innerHTML = html;
}

function openTestResult(index) {
  const history = JSON.parse(localStorage.getItem('TEST_HISTORY'));
  loadedTestData = history[index];
  
  document.getElementById('res-title').innerText = loadedTestData.title;
  document.getElementById('res-max').innerText = loadedTestData.max;
  document.getElementById('res-date').innerText = loadedTestData.date;
  document.getElementById('res-stream-select').value = "";
  document.getElementById('res-table-container').innerHTML = "<p style='text-align:center; padding:20px; color:#94a3b8'>Select a stream to see the marks list.</p>";
  
  navTo('view-result');
}

function renderResultTable(stream) {
  if(!stream || !loadedTestData) return;
  
  const data = loadedTestData.data[stream];
  const container = document.getElementById('res-table-container');
  
  let html = `<table><thead><tr><th>Roll</th><th>Name</th><th>Marks</th></tr></thead><tbody>`;
  
  Object.keys(data).sort((a,b)=>a-b).forEach(roll => {
    const row = data[roll];
    // Optional: Red text for marks < 33
    const isFail = !isNaN(row.marks) && Number(row.marks) < 33;
    const markStyle = isFail ? "color: #ef4444; font-weight:700;" : "font-weight:600;";
    
    html += `<tr>
      <td>${roll}</td>
      <td>${row.name || '-'}</td>
      <td style="${markStyle}">${row.marks}</td>
    </tr>`;
  });
  html += `</tbody></table>`;
  container.innerHTML = html;
}
</script>
</body>
</html>

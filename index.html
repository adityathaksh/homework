<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Homework Management Portal</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-100 min-h-screen text-slate-800 font-sans">

  <!-- Header -->
  <header class="bg-indigo-900 text-white shadow-md">
    <div class="max-w-5xl mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center gap-3">
      <div>
        <h1 class="text-2xl font-bold tracking-tight">Homework Portal</h1>
        <p class="text-xs text-indigo-200">Aditya Thaksh International School</p>
      </div>
      <!-- Tab Navigation -->
      <nav class="flex bg-indigo-800 p-1 rounded-lg text-sm font-medium">
        <button onclick="switchTab('teacher')" id="tab-teacher" class="px-4 py-2 rounded-md transition-all bg-white text-indigo-900 shadow">Teacher Entry</button>
        <button onclick="switchTab('principal')" id="tab-principal" class="px-4 py-2 rounded-md transition-all text-indigo-200 hover:text-white">Principal Review</button>
        <button onclick="switchTab('parent')" id="tab-parent" class="px-4 py-2 rounded-md transition-all text-indigo-200 hover:text-white">Parent Portal</button>
      </nav>
    </div>
  </header>

  <main class="max-w-5xl mx-auto px-4 py-8">

    <!-- TAB 1: TEACHER SUBMISSION -->
    <section id="view-teacher" class="block">
      <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-6 max-w-2xl mx-auto">
        <h2 class="text-xl font-bold text-slate-800 mb-1">Submit Homework</h2>
        <p class="text-sm text-slate-500 mb-6">Fill in assignment details below for principal review.</p>

        <form id="hwForm" onsubmit="handleFormSubmit(event)" class="space-y-5">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Date</label>
              <input type="date" id="hwDate" required onchange="updateDayName()" class="w-full px-3 py-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none">
            </div>
            <div>
              <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Day</label>
              <input type="text" id="hwDay" readonly class="w-full px-3 py-2 bg-slate-100 border rounded-lg text-slate-500 cursor-not-allowed">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Grade</label>
              <select id="hwGrade" required class="w-full px-3 py-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none">
                <option value="">Select Grade</option>
                <option value="K1">K1</option>
                <option value="K2">K2</option>
                <option value="Grade 1">Grade 1</option>
                <option value="Grade 2">Grade 2</option>
                <option value="Grade 3">Grade 3</option>
                <option value="Grade 4">Grade 4</option>
                <option value="Grade 5">Grade 5</option>
                <option value="Grade 6">Grade 6</option>
                <option value="Grade 7">Grade 7</option>
                <option value="Grade 8">Grade 8</option>
                <option value="Grade 9">Grade 9</option>
                <option value="Grade X">Grade X</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Subject</label>
              <select id="hwSubject" required class="w-full px-3 py-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none">
                <option value="">Select Subject</option>
                <option value="Math">Math</option>
                <option value="English">English</option>
                <option value="Science">Science</option>
                <option value="Social">Social</option>
                <option value="Computer Science / AI">Computer Science / AI</option>
                <option value="Hindi">Hindi</option>
                <option value="Telugu">Telugu</option>
              </select>
            </div>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-2">Sections</label>
            <div class="flex gap-4">
              <label class="flex items-center gap-2 text-sm text-slate-700 cursor-pointer">
                <input type="checkbox" value="Tulip" class="section-check rounded text-indigo-600" checked> Tulip
              </label>
              <label class="flex items-center gap-2 text-sm text-slate-700 cursor-pointer">
                <input type="checkbox" value="Orchid" class="section-check rounded text-indigo-600" checked> Orchid
              </label>
              <label class="flex items-center gap-2 text-sm text-slate-700 cursor-pointer">
                <input type="checkbox" value="Daisy" class="section-check rounded text-indigo-600" checked> Daisy
              </label>
            </div>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Teacher Name</label>
            <input type="text" id="hwTeacher" placeholder="Enter your name" required class="w-full px-3 py-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none">
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Homework Details</label>
            <textarea id="hwContent" rows="3" placeholder="e.g., ✏️ L/W 3 table 2 times in HW" required class="w-full px-3 py-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none"></textarea>
          </div>

          <button type="submit" id="submitBtn" class="w-full bg-indigo-600 hover:bg-indigo-700 text-white font-medium py-2.5 rounded-lg transition-colors">Submit Homework</button>
        </form>
      </div>
    </section>

    <!-- TAB 2: PRINCIPAL REVIEW -->
    <section id="view-principal" class="hidden">
      <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-6 mb-6 flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
        <div>
          <h2 class="text-xl font-bold text-slate-800">Principal Review Panel</h2>
          <p class="text-sm text-slate-500">Edit, approve, and generate WhatsApp text for parents.</p>
        </div>
        <div class="flex items-center gap-3">
          <input type="date" id="filterDate" onchange="listenToPrincipalData()" class="px-3 py-2 border rounded-lg text-sm outline-none">
          <button onclick="copyWhatsAppFormat()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-medium px-4 py-2 rounded-lg text-sm flex items-center gap-2 transition-colors">
            <span>📲 Copy WhatsApp Format</span>
          </button>
        </div>
      </div>

      <div id="principalList" class="space-y-4">
        <!-- Rendered dynamically from Firestore -->
      </div>
    </section>

    <!-- TAB 3: PARENT PORTAL -->
    <section id="view-parent" class="hidden">
      <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-6 mb-6 flex flex-col sm:flex-row justify-between items-center gap-4">
        <h2 class="text-xl font-bold text-slate-800">Approved Daily Agenda</h2>
        <div class="flex gap-3 w-full sm:w-auto">
          <input type="date" id="parentFilterDate" onchange="listenToParentData()" class="px-3 py-2 border rounded-lg text-sm outline-none">
          <select id="parentFilterGrade" onchange="listenToParentData()" class="px-3 py-2 border rounded-lg text-sm outline-none">
            <option value="ALL">All Grades</option>
            <option value="K1">K1</option>
            <option value="K2">K2</option>
            <option value="Grade 1">Grade 1</option>
            <option value="Grade 2">Grade 2</option>
            <option value="Grade 3">Grade 3</option>
            <option value="Grade 4">Grade 4</option>
            <option value="Grade 5">Grade 5</option>
            <option value="Grade 6">Grade 6</option>
            <option value="Grade 7">Grade 7</option>
            <option value="Grade 8">Grade 8</option>
            <option value="Grade 9">Grade 9</option>
            <option value="Grade X">Grade X</option>
          </select>
        </div>
      </div>

      <div id="parentList" class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <!-- Rendered dynamically from Firestore -->
      </div>
    </section>

  </main>

  <!-- Firebase Modular SDK Script -->
  <script type="module">
    import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
    import { 
      getFirestore, 
      collection, 
      addDoc, 
      updateDoc, 
      deleteDoc, 
      doc, 
      query, 
      where, 
      onSnapshot,
      serverTimestamp 
    } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore.js";

    // 1. YOUR FIREBASE CONFIGURATION (Replace with your console keys)
    const firebaseConfig = {
       	apiKey: "AIzaSyBesKlVSBr7a4ClbJ8yLQmFSlkJqDJeuVE",
		authDomain: "homework-9b801.firebaseapp.com",
		projectId: "homework-9b801",
		storageBucket: "homework-9b801.firebasestorage.app",
		messagingSenderId: "718017176358",
		appId: "1:718017176358:web:1842b4a3372c1c170257e7",
		measurementId: "G-XM82NFGJDF"
    };

    // Initialize Firebase & Firestore
    const app = initializeApp(firebaseConfig);
    const db = getFirestore(app);
    const homeworkCol = collection(db, "homeworks");

    // Track active query unsubscribers to prevent memory leaks
    let principalUnsub = null;
    let parentUnsub = null;
    let currentPrincipalData = [];

    // Initialize UI on Load
    window.addEventListener("DOMContentLoaded", () => {
      const today = new Date().toISOString().split('T')[0];
      document.getElementById('hwDate').value = today;
      document.getElementById('filterDate').value = today;
      document.getElementById('parentFilterDate').value = today;
      window.updateDayName();
      listenToPrincipalData();
      listenToParentData();
    });

    window.updateDayName = function() {
      const dateVal = document.getElementById('hwDate').value;
      if (!dateVal) return;
      const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
      const dateObj = new Date(dateVal);
      document.getElementById('hwDay').value = days[dateObj.getDay()];
    };

    // Tab Switching Logic
    window.switchTab = function(tab) {
      ['teacher', 'principal', 'parent'].forEach(t => {
        document.getElementById(`view-${t}`).classList.add('hidden');
        document.getElementById(`tab-${t}`).className = "px-4 py-2 rounded-md transition-all text-indigo-200 hover:text-white";
      });

      document.getElementById(`view-${tab}`).classList.remove('hidden');
      document.getElementById(`tab-${tab}`).className = "px-4 py-2 rounded-md transition-all bg-white text-indigo-900 shadow";

      if (tab === 'principal') listenToPrincipalData();
      if (tab === 'parent') listenToParentData();
    };

    // 2. CREATE: Add Homework Submission
    window.handleFormSubmit = async function(e) {
      e.preventDefault();
      const submitBtn = document.getElementById('submitBtn');
      submitBtn.disabled = true;
      submitBtn.innerText = "Submitting...";

      const sections = Array.from(document.querySelectorAll('.section-check:checked')).map(cb => cb.value);
      if (sections.length === 0) {
        alert("Please select at least one section.");
        submitBtn.disabled = false;
        submitBtn.innerText = "Submit Homework";
        return;
      }

      const dateInput = document.getElementById('hwDate').value;
      const [year, month, day] = dateInput.split('-');

      try {
        await addDoc(homeworkCol, {
          date: dateInput,
          formattedDate: `${day}-${month}-${year}`,
          day: document.getElementById('hwDay').value,
          grade: document.getElementById('hwGrade').value,
          subject: document.getElementById('hwSubject').value,
          sections: sections,
          teacher: document.getElementById('hwTeacher').value,
          content: document.getElementById('hwContent').value,
          status: 'pending',
          createdAt: serverTimestamp()
        });

        alert("Homework submitted successfully for principal review!");
        document.getElementById('hwContent').value = '';
      } catch (error) {
        console.error("Error submitting document: ", error);
        alert("Failed to submit. Check console or Firestore settings.");
      } finally {
        submitBtn.disabled = false;
        submitBtn.innerText = "Submit Homework";
      }
    };

    // 3. READ (Real-time): Principal Panel Query
    window.listenToPrincipalData = function() {
      if (principalUnsub) principalUnsub();

      const selectedDate = document.getElementById('filterDate').value;
      const q = query(homeworkCol, where("date", "==", selectedDate));

      principalUnsub = onSnapshot(q, (snapshot) => {
        currentPrincipalData = [];
        const container = document.getElementById('principalList');
        container.innerHTML = '';

        if (snapshot.empty) {
          container.innerHTML = `<div class="bg-white p-8 rounded-xl text-center text-slate-500">No homework submissions found for this date.</div>`;
          return;
        }

        snapshot.forEach((docSnap) => {
          const item = { id: docSnap.id, ...docSnap.data() };
          currentPrincipalData.push(item);

          const card = document.createElement('div');
          card.className = "bg-white p-5 rounded-xl border border-slate-200 shadow-sm space-y-3";
          card.innerHTML = `
            <div class="flex justify-between items-start">
              <div>
                <span class="inline-block bg-indigo-100 text-indigo-800 text-xs font-semibold px-2.5 py-0.5 rounded mr-2">${item.subject}</span>
                <span class="font-bold text-slate-800">${item.grade} (${item.sections ? item.sections.join(', ') : ''})</span>
                <p class="text-xs text-slate-400 mt-0.5">Teacher: ${item.teacher}</p>
              </div>
              <button onclick="toggleApprove('${item.id}', '${item.status}')" class="px-3 py-1 text-xs font-semibold rounded-full ${item.status === 'approved' ? 'bg-emerald-100 text-emerald-700' : 'bg-amber-100 text-amber-700'}">
                ${item.status === 'approved' ? '✓ Approved' : '⏳ Pending'}
              </button>
            </div>
            <div>
              <textarea id="edit-${item.id}" rows="2" class="w-full text-sm p-2 border rounded-lg focus:ring-2 focus:ring-indigo-500 outline-none">${item.content}</textarea>
            </div>
            <div class="flex justify-end gap-2">
              <button onclick="saveEdit('${item.id}')" class="px-3 py-1 bg-slate-800 text-white rounded-md text-xs hover:bg-slate-900">Save Edit</button>
              <button onclick="deleteEntry('${item.id}')" class="px-3 py-1 bg-rose-50 text-rose-600 rounded-md text-xs hover:bg-rose-100">Delete</button>
            </div>
          `;
          container.appendChild(card);
        });
      });
    };

    // 4. UPDATE: Save Principal Edits
    window.saveEdit = async function(id) {
      const newText = document.getElementById(`edit-${id}`).value;
      try {
        const docRef = doc(db, "homeworks", id);
        await updateDoc(docRef, { content: newText });
        alert("Changes saved to cloud!");
      } catch (err) {
        console.error("Save error: ", err);
      }
    };

    // 5. UPDATE: Toggle Approval Status
    window.toggleApprove = async function(id, currentStatus) {
      const newStatus = currentStatus === 'approved' ? 'pending' : 'approved';
      try {
        const docRef = doc(db, "homeworks", id);
        await updateDoc(docRef, { status: newStatus });
      } catch (err) {
        console.error("Approval error: ", err);
      }
    };

    // 6. DELETE: Remove Entry
    window.deleteEntry = async function(id) {
      if (!confirm("Delete this submission permanently?")) return;
      try {
        await deleteDoc(doc(db, "homeworks", id));
      } catch (err) {
        console.error("Delete error: ", err);
      }
    };

    // 7. READ (Real-time): Parent Portal Query
    window.listenToParentData = function() {
      if (parentUnsub) parentUnsub();

      const selectedDate = document.getElementById('parentFilterDate').value;
      const selectedGrade = document.getElementById('parentFilterGrade').value;

      const q = query(
        homeworkCol, 
        where("date", "==", selectedDate), 
        where("status", "==", "approved")
      );

      parentUnsub = onSnapshot(q, (snapshot) => {
        const container = document.getElementById('parentList');
        container.innerHTML = '';

        let items = [];
        snapshot.forEach(docSnap => items.push({ id: docSnap.id, ...docSnap.data() }));

        if (selectedGrade !== 'ALL') {
          items = items.filter(item => item.grade === selectedGrade);
        }

        if (items.length === 0) {
          container.innerHTML = `<div class="col-span-full bg-white p-8 rounded-xl text-center text-slate-500">No homework posted for this filter.</div>`;
          return;
        }

        items.forEach(item => {
          const card = document.createElement('div');
          card.className = "bg-white p-5 rounded-xl border border-slate-200 shadow-sm space-y-2";
          card.innerHTML = `
            <div class="flex justify-between items-center border-b pb-2">
              <span class="font-bold text-slate-800">${item.grade} (${item.sections ? item.sections.join(', ') : ''})</span>
              <span class="bg-indigo-50 text-indigo-700 text-xs font-semibold px-2.5 py-0.5 rounded">${item.subject}</span>
            </div>
            <p class="text-slate-700 text-sm whitespace-pre-line mt-2">${item.content}</p>
          `;
          container.appendChild(card);
        });
      });
    };

    // 8. EXPORT: Generate Copyable WhatsApp String
    window.copyWhatsAppFormat = function() {
      const approvedItems = currentPrincipalData.filter(item => item.status === 'approved');

      if (approvedItems.length === 0) {
        alert("No approved entries available to export for this date.");
        return;
      }

      const selectedDate = document.getElementById('filterDate').value;
      const [year, month, day] = selectedDate.split('-');
      const formattedDate = `${day}-${month}-${year}`;
      const dayName = approvedItems[0]?.day || '';

      const groupedBySubject = {};
      approvedItems.forEach(item => {
        if (!groupedBySubject[item.subject]) groupedBySubject[item.subject] = [];
        groupedBySubject[item.subject].push(item);
      });

      let text = `📅 Date: ${formattedDate}\n📆 Day: ${dayName}\n\n`;

      for (const [subject, items] of Object.entries(groupedBySubject)) {
        text += `📚 Subject: ${subject}\n\n`;
        items.forEach(item => {
          text += `${item.grade} (${item.sections.join(', ')})\n${item.content}\n\n`;
        });
      }

      navigator.clipboard.writeText(text.trim()).then(() => {
        alert("WhatsApp message copied to clipboard!\n\nPreview:\n" + text);
      });
    };
  </script>
</body>
</html>
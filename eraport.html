<!doctype html>
<html lang="id">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jadwal Ujian Santri</title>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="/_sdk/data_sdk.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      box-sizing: border-box;
    }
    
    * {
      box-sizing: border-box;
    }

    .gradient-bg {
      background: linear-gradient(135deg, #86efac 0%, #fef08a 50%, #86efac 100%);
      position: relative;
      overflow: hidden;
    }

    .abstract-shape {
      position: absolute;
      border-radius: 50%;
      filter: blur(80px);
      opacity: 0.3;
      pointer-events: none;
    }

    .shape-1 {
      width: 400px;
      height: 400px;
      background: #22c55e;
      top: -100px;
      right: -100px;
    }

    .shape-2 {
      width: 300px;
      height: 300px;
      background: #facc15;
      bottom: -80px;
      left: -80px;
    }

    .shape-3 {
      width: 250px;
      height: 250px;
      background: #84cc16;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    .watermark {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      opacity: 0.15;
      pointer-events: none;
      z-index: 1;
      width: 300px;
      height: auto;
    }

    .content-wrapper {
      position: relative;
      z-index: 2;
    }

    .search-container {
      position: relative;
    }

    .suggestions-list {
      position: absolute;
      top: 100%;
      left: 0;
      right: 0;
      background: white;
      border: 2px solid #86efac;
      border-top: none;
      border-radius: 0 0 12px 12px;
      max-height: 250px;
      overflow-y: auto;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      z-index: 10;
    }

    .suggestion-item {
      padding: 12px 16px;
      cursor: pointer;
      transition: background-color 0.2s;
      border-bottom: 1px solid #f0f0f0;
    }

    .suggestion-item:hover {
      background-color: #f0fdf4;
    }

    .suggestion-item:last-child {
      border-bottom: none;
    }

    .profile-card {
      background: white;
      border-radius: 16px;
      padding: 24px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      animation: slideUp 0.3s ease-out;
    }

    @keyframes slideUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes slideIn {
      from {
        opacity: 0;
        transform: translateX(100px);
      }
      to {
        opacity: 1;
        transform: translateX(0);
      }
    }

    @keyframes slideOut {
      from {
        opacity: 1;
        transform: translateX(0);
      }
      to {
        opacity: 0;
        transform: translateX(100px);
      }
    }

    .info-row {
      display: flex;
      justify-content: space-between;
      padding: 12px 0;
      border-bottom: 1px solid #f0f0f0;
    }

    .info-row:last-child {
      border-bottom: none;
    }

    .info-label {
      font-weight: 600;
      color: #16a34a;
    }

    .info-value {
      color: #374151;
      text-align: right;
    }

    .btn-wa {
      background: #25d366;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      text-decoration: none;
      transition: background-color 0.2s;
      font-size: 13px;
    }

    .btn-wa:hover {
      background: #1da851;
    }

    .btn-call {
      background: #3b82f6;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      text-decoration: none;
      transition: background-color 0.2s;
      font-size: 13px;
    }

    .btn-call:hover {
      background: #2563eb;
    }

    .info-box {
      background: linear-gradient(135deg, #dcfce7 0%, #fef9c3 100%);
      border-left: 4px solid #16a34a;
      padding: 16px;
      border-radius: 8px;
      margin-top: 20px;
      margin-bottom: 20px;
      line-height: 1.8;
      overflow: visible;
    }

    .logo-img {
      max-width: 120px;
      height: auto;
    }

    .search-page, .detail-page {
      transition: opacity 0.3s ease, transform 0.3s ease;
    }

    .search-page.hidden {
      display: none;
      opacity: 0;
      transform: translateX(-50px);
    }

    .detail-page {
      display: none;
      opacity: 0;
      transform: translateX(50px);
      min-height: auto;
    }

    .detail-page.active {
      display: block;
      opacity: 1;
      transform: translateX(0);
      animation: slideInRight 0.4s ease-out;
      min-height: auto;
    }

    @keyframes slideInRight {
      from {
        opacity: 0;
        transform: translateX(50px);
      }
      to {
        opacity: 1;
        transform: translateX(0);
      }
    }

    .btn-back {
      background: white;
      color: #16a34a;
      padding: 12px 24px;
      border-radius: 12px;
      border: 2px solid #16a34a;
      cursor: pointer;
      font-weight: 600;
      transition: all 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    .btn-back:hover {
      background: #16a34a;
      color: white;
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    }

    .detail-header {
      display: none;
    }

    .detail-header-content {
      display: flex;
      align-items: center;
      gap: 20px;
      justify-content: center;
    }

    .student-photo {
      width: 12px;
      height: 15px;
      object-fit: cover;
      border-radius: 4px;
      border: 1px solid white;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
      flex-shrink: 0;
    }

    .photo-section {
      text-align: center;
      margin-bottom: 24px;
    }

    .student-photo-container {
      width: 160px;
      height: 160px;
      background: linear-gradient(135deg, #dcfce7 0%, #fef9c3 100%);
      border: 3px solid #16a34a;
      border-radius: 50%;
      overflow: hidden;
      margin: 0 auto 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 64px;
      font-weight: bold;
      color: #16a34a;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    .student-photo-container:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.15);
    }

    .student-photo-container img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .photo-label {
      font-size: 12px;
      color: #16a34a;
      font-weight: 600;
      margin-top: 8px;
      text-align: center;
      font-weight: 600;
      color: #16a34a;
      font-size: 18px;
    }

    .photo-label-class {
      font-size: 14px;
      color: #16a34a;
      font-weight: 600;
      margin-top: 4px;
      text-align: center;
    }

    .photo-modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.95);
      display: none;
      justify-content: center;
      align-items: center;
      z-index: 2000;
      padding: 20px;
    }

    .photo-modal-overlay.active {
      display: flex;
    }

    .photo-modal-content {
      position: relative;
      max-width: 90vw;
      max-height: 90vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .photo-modal-image {
      max-width: 100%;
      max-height: 80vh;
      object-fit: contain;
      border-radius: 12px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
    }

    .photo-modal-info {
      color: white;
      text-align: center;
      margin-top: 16px;
      font-size: 14px;
    }

    .photo-modal-close {
      position: absolute;
      top: -40px;
      right: 0;
      background: white;
      color: #000;
      border: none;
      width: 44px;
      height: 44px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 24px;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.2s;
      font-weight: bold;
    }

    .photo-modal-close:hover {
      background: #f0f0f0;
      transform: scale(1.1);
    }

    .student-info {
      text-align: left;
    }

    .student-name {
      font-size: 1.5rem;
      font-weight: bold;
      margin-bottom: 4px;
    }

    .student-class {
      font-size: 0.95rem;
      opacity: 0.95;
    }

    .modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.7);
      display: none;
      justify-content: center;
      align-items: center;
      z-index: 1000;
      overflow-y: auto;
      padding: 20px;
    }

    .modal-overlay.active {
      display: flex;
    }

    .modal-content {
      background: white;
      border-radius: 20px;
      padding: 20px;
      max-width: 900px;
      width: 100%;
      max-height: 90vh;
      overflow-y: auto;
      position: relative;
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
      font-size: 14px;
    }

    .modal-close {
      position: absolute;
      top: 16px;
      right: 16px;
      background: #ef4444;
      color: white;
      border: none;
      width: 36px;
      height: 36px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.2s;
    }

    .modal-close:hover {
      background: #dc2626;
      transform: scale(1.1);
    }

    .student-checkbox {
      display: flex;
      align-items: center;
      padding: 12px;
      border: 2px solid #d1d5db;
      border-radius: 8px;
      cursor: pointer;
      transition: all 0.2s;
      margin-bottom: 8px;
    }

    .student-checkbox:hover {
      border-color: #16a34a;
      background: #f0fdf4;
    }

    .student-checkbox input[type="checkbox"] {
      width: 20px;
      height: 20px;
      margin-right: 12px;
      cursor: pointer;
    }

    .student-checkbox.selected {
      border-color: #16a34a;
      background: #dcfce7;
    }

    .print-preview {
      display: none;
    }

    @media print {
      body * {
        visibility: hidden;
      }
      
      .print-preview, .print-preview * {
        visibility: visible;
      }
      
      .print-preview {
        position: absolute;
        left: 0;
        top: 0;
        width: 100%;
      }

      .page-break {
        page-break-after: always;
      }

      @page {
        size: A4 portrait;
        margin: 0;
      }
    }

    @media (max-width: 640px) {
      .profile-card {
        padding: 16px;
      }
      
      .logo-img {
        max-width: 80px;
      }

      .watermark {
        width: 200px;
      }

      .detail-header {
        margin: -16px -16px 16px -16px;
        padding: 20px;
      }

      .detail-header-content {
        flex-direction: column;
        text-align: center;
      }

      .student-info {
        text-align: center;
      }

      .student-name {
        font-size: 1.5rem;
      }

      .student-class {
        font-size: 1rem;
      }

      .modal-content {
        padding: 20px;
      }

      #printButton {
        padding: 10px 16px;
        font-size: 14px;
      }

      .student-photo {
        width: 100px;
        height: 120px;
      }
    }

    .exam-map-container {
      background: linear-gradient(135deg, #f0fdf4 0%, #fef9c3 100%);
      border: 3px solid #16a34a;
      border-radius: 12px;
      padding: 24px;
    }

    .exam-map-title {
      text-align: center;
      font-size: 18px;
      font-weight: 700;
      color: #16a34a;
      margin-bottom: 20px;
    }

    .map-layout {
      display: flex;
      justify-content: center;
      align-items: flex-end;
      gap: 40px;
      margin-bottom: 20px;
    }

    .building {
      text-align: center;
    }

    .building-name {
      font-size: 16px;
      font-weight: 700;
      color: #16a34a;
      margin-bottom: 12px;
    }

    .building-rooms {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      gap: 8px;
    }

    .room-box {
      background: white;
      border: 2px solid #16a34a;
      border-radius: 8px;
      padding: 12px;
      min-width: 90px;
      text-align: center;
    }

    .room-code {
      font-size: 13px;
      font-weight: 700;
      color: #16a34a;
      margin-bottom: 4px;
    }

    .room-teacher {
      font-size: 11px;
      color: #4b5563;
      line-height: 1.3;
    }

    .gate {
      text-align: center;
      margin-bottom: 20px;
    }

    .gate-icon {
      font-size: 32px;
      margin-bottom: 8px;
    }

    .gate-label {
      font-size: 14px;
      font-weight: 700;
      color: #16a34a;
    }

    .map-note {
      text-align: center;
      font-size: 12px;
      color: #666;
      font-style: italic;
      margin-top: 16px;
      padding-top: 16px;
      border-top: 2px solid #d1d5db;
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
 </head>
 <body class="gradient-bg" style="min-height: 100%; overflow-y: auto;">
  <div class="abstract-shape shape-1"></div>
  <div class="abstract-shape shape-2"></div>
  <div class="abstract-shape shape-3"></div><img src="https://iili.io/fFA80TF.md.png" alt="Watermark" class="watermark" onerror="this.style.display='none';">
  <div class="content-wrapper p-4 md:p-8" style="min-height: 100%; padding-bottom: 80px;">
   <div class="max-w-4xl mx-auto"><!-- Search Page -->
    <div id="searchPage" class="search-page"><!-- Header -->
     <div class="header-section mb-8">
      <div class="flex-1 text-center mb-4"><img src="https://iili.io/fFA80TF.md.png" alt="Logo SD International Tahfizh Quran" class="logo-img mx-auto mb-4" onerror="this.style.display='none';">
      </div>
      <div class="flex justify-center gap-2 mb-4 flex-wrap"><button id="printButton" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 md:px-8 md:py-3 rounded-lg font-semibold shadow-lg transition-all flex items-center gap-2 text-sm md:text-base"> 📄 <span class="hidden sm:inline">Cetak</span> </button> <button id="adminButton" class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 md:px-8 md:py-3 rounded-lg font-semibold shadow-lg transition-all flex items-center gap-2 text-sm md:text-base"> ⚙️ <span class="hidden sm:inline">Admin</span> </button> <button id="teacherButton" class="bg-purple-600 hover:bg-purple-700 text-white px-4 py-2 md:px-8 md:py-3 rounded-lg font-semibold shadow-lg transition-all flex items-center gap-2 text-sm md:text-base"> 👨‍🏫 <span class="hidden sm:inline">Guru</span> </button>
      </div>
      <div class="text-center">
       <h1 id="app-title" class="text-2xl md:text-4xl font-bold text-green-800 mb-2 leading-tight">JADWAL UJIAN SANTRI</h1>
       <p class="text-green-700 text-sm md:text-base">SD International Tahfizh Quran</p>
      </div>
     </div><!-- Search Box -->
     <div class="search-container mb-6"><input type="text" id="searchInput" placeholder="🔍 Ketik minimal 3 huruf nama santri..." class="w-full px-6 py-4 text-lg border-2 border-green-300 rounded-xl focus:outline-none focus:border-green-500 shadow-lg">
      <div id="suggestionsList" class="suggestions-list" style="display: none;"></div>
     </div><!-- Result Container -->
     <div id="resultContainer"></div>
    </div><!-- Detail Page -->
    <div id="detailPage" class="detail-page"><button id="backButton" class="btn-back mb-6"> ⬅️ Kembali ke Pencarian </button>
     <div id="detailContent"></div>
    </div><!-- Teacher Page -->
    <div id="teacherPage" class="detail-page"><button id="backButtonTeacher" class="btn-back mb-6"> ⬅️ Kembali ke Pencarian </button>
     <div class="profile-card"><img src="https://iili.io/fFA80TF.md.png" alt="Logo SD International Tahfizh Quran" class="logo-img mx-auto mb-6" onerror="this.style.display='none';">
      <div class="text-center mb-8">
       <h1 style="font-size: 24px; font-weight: 700; color: #16a34a; margin-bottom: 8px;">GENERASI QURAN SIAP BERPRESTASI</h1>
       <p style="font-size: 18px; font-weight: 600; color: #16a34a;">SD INTERNATIONAL TAHFIZH QURAN</p>
      </div><!-- Teacher Table -->
      <div id="teacherTableSection">
       <h2 style="font-size: 16px; md:font-size: 20px; font-weight: 700; color: #16a34a; text-align: center; margin-bottom: 16px; padding-bottom: 12px; border-bottom: 3px solid #16a34a;">👨‍🏫🏫 DEWAN GURU PENGUJI UJIAN</h2>
       <div style="overflow-x: auto; -webkit-overflow-scrolling: touch;">
        <table style="width: 100%; border-collapse: collapse; margin-bottom: 24px; font-size: 13px;">
         <thead>
          <tr style="background: linear-gradient(135deg, #86efac 0%, #dcfce7 100%); border: 2px solid #16a34a;">
           <th style="padding: 8px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 35px; font-size: 12px;">No</th>
           <th style="padding: 8px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: left; min-width: 120px; font-size: 12px;">Nama Guru</th>
           <th style="padding: 8px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: left; min-width: 80px; font-size: 12px;">Ruang</th>
           <th style="padding: 8px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 85px; font-size: 12px;">Aksi</th>
          </tr>
         </thead>
         <tbody id="teachersTableBody"><!-- Teacher rows akan ditampilkan di sini -->
         </tbody>
        </table>
       </div>
      </div><!-- Student List Section (Hidden by default) -->
      <div id="studentListSection" style="display: none;"><button id="backToTeachersButton" class="btn-back mb-6" style="background: white; color: #16a34a; border: 2px solid #16a34a;"> ⬅️ Kembali ke Daftar Guru </button>
       <h3 id="selectedTeacherName" style="font-size: 18px; font-weight: 700; color: #16a34a; margin-bottom: 16px; padding: 16px; background: linear-gradient(135deg, #dcfce7 0%, #fef9c3 100%); border-radius: 8px; border-left: 4px solid #16a34a;">👨‍🏫 Siswa Mengikuti Ujian</h3><!-- Search bar for students -->
       <div style="margin-bottom: 20px;"><input type="text" id="studentSearchInput" placeholder="🔍 Cari nama siswa..." style="width: 100%; padding: 12px 16px; border: 2px solid #16a34a; border-radius: 8px; font-size: 14px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
       </div><!-- Student Table -->
       <div style="overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse;">
         <thead>
          <tr style="background: linear-gradient(135deg, #86efac 0%, #dcfce7 100%); border: 2px solid #16a34a;">
           <th style="padding: 12px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 50px;">No</th>
           <th style="padding: 12px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: left; min-width: 150px;">Nama Siswa</th>
           <th style="padding: 12px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 120px;">📅 Tanggal Ujian</th>
           <th style="padding: 12px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 100px;">🕐 Waktu Ujian</th>
           <th style="padding: 12px; border: 2px solid #16a34a; color: #16a34a; font-weight: 700; text-align: center; min-width: 120px;">📱 No HP</th>
          </tr>
         </thead>
         <tbody id="studentTableBody"><!-- Student rows akan ditampilkan di sini -->
         </tbody>
        </table>
       </div><!-- Print Button -->
       <div style="text-align: center; margin-top: 24px;"><button id="printTeacherButton" onclick="openPrintTeacherPage()" style="background: #16a34a; color: white; border: none; padding: 14px 32px; border-radius: 8px; cursor: pointer; font-weight: 700; font-size: 16px; transition: all 0.2s; box-shadow: 0 4px 12px rgba(0,0,0,0.2);" onmouseover="this.style.background='#15803d'; this.style.transform='translateY(-2px)'" onmouseout="this.style.background='#16a34a'; this.style.transform='translateY(0)'"> 📋 Cetak Daftar Ujian </button>
       </div>
      </div>
     </div>
    </div>
   </div>
  </div><!-- Modal Cetak -->
  <div id="printModal" class="modal-overlay">
   <div class="modal-content"><button class="modal-close" onclick="closePrintModal()">✕</button>
    <h2 class="text-2xl font-bold text-green-800 mb-2 text-center">📄 Cetak Jadwal Ujian</h2>
    <p class="text-center text-gray-600 mb-6">Pilih santri yang akan dicetak (2 kartu per halaman A4 Portrait)</p>
    <div class="mb-4">
     <div class="flex gap-2 mb-4"><input type="text" id="printSearchInput" placeholder="🔍 Cari nama santri..." class="flex-1 px-4 py-2 border-2 border-green-300 rounded-lg focus:outline-none focus:border-green-500"> <button onclick="selectAllStudents()" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg font-semibold"> ✓ Pilih Semua </button> <button onclick="deselectAllStudents()" class="bg-gray-400 hover:bg-gray-500 text-white px-4 py-2 rounded-lg font-semibold"> ✕ Batalkan </button>
     </div>
     <div id="studentsList" class="max-h-96 overflow-y-auto mb-6 border-2 border-gray-200 rounded-lg p-4"><!-- Student checkboxes akan diisi di sini -->
     </div>
     <div class="text-center text-sm text-gray-600 mb-4"><span id="selectedCount">0</span> santri dipilih
     </div>
     <div class="flex gap-3 justify-center"><button onclick="generatePrint()" class="bg-green-600 hover:bg-green-700 text-white px-8 py-3 rounded-lg font-bold text-lg shadow-lg transition-all flex items-center gap-2"> 📄 Cetak Sekarang </button> <button onclick="closePrintModal()" class="bg-gray-400 hover:bg-gray-500 text-white px-8 py-3 rounded-lg font-bold text-lg"> ✕ Tutup </button>
     </div>
    </div>
   </div>
  </div><!-- Modal Admin -->
  <div id="adminModal" class="modal-overlay">
   <div class="modal-content"><button class="modal-close" onclick="closeAdminModal()">✕</button>
    <h2 class="text-2xl font-bold text-blue-800 mb-2 text-center">⚙️ Panel Admin</h2>
    <p class="text-center text-gray-600 mb-6">Kelola pesan informasi ujian yang akan ditampilkan di detail santri</p>
    <div class="mb-6"><label class="block font-semibold text-gray-700 mb-2">📝 Pesan Informasi Ujian:</label> <textarea id="adminMessageInput" rows="10" placeholder="Contoh:
🔔 Perhatian Penting untuk Wali Santri:
• Mohon pastikan ananda hadir TEPAT WAKTU sesuai jadwal yang tertera
• Jika tidak ada jadwal ujian pada hari tertentu, santri belajar di rumah masing-masing
✅ Apabila ananda berhalangan hadir, mohon segera menghubungi Wali Kelas untuk koordinasi lebih lanjut
📍 Lokasi Ujian: {ruang}
👨‍🏫 Guru Penguji: {guru}

📞 Informasi &amp; Koordinasi:
• Untuk informasi lebih lanjut atau pertanyaan seputar ujian, silakan hubungi Wali Kelas masing-masing
• Jika ada perubahan jadwal atau keperluan khusus, segera koordinasikan dengan Wali Kelas
• Nomor kontak Wali Kelas dapat dilihat di atas atau melalui grup kelas" class="w-full px-4 py-3 border-2 border-blue-300 rounded-lg focus:outline-none focus:border-blue-500 font-mono text-sm"></textarea>
     <p class="text-xs text-gray-500 mt-2">💡 Gunakan {ruang} dan {guru} sebagai placeholder yang akan otomatis diganti dengan data santri</p>
    </div>
    <div id="currentMessageDisplay" class="mb-6 p-4 bg-gray-50 rounded-lg border-2 border-gray-200">
     <h3 class="font-semibold text-gray-700 mb-2">📋 Pesan Saat Ini:</h3>
     <div id="currentMessageText" class="text-sm text-gray-600 whitespace-pre-wrap">
      Belum ada pesan custom. Menggunakan pesan default.
     </div>
    </div>
    <div class="flex gap-3 justify-center"><button id="saveMessageBtn" onclick="saveAdminMessage()" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-3 rounded-lg font-bold text-lg shadow-lg transition-all flex items-center gap-2"> 💾 Simpan Pesan </button> <button onclick="closeAdminModal()" class="bg-gray-400 hover:bg-gray-500 text-white px-8 py-3 rounded-lg font-bold text-lg"> ✕ Tutup </button>
    </div>
   </div>
  </div><!-- Print Preview (Hidden) -->
  <div id="printPreview" class="print-preview"></div><!-- Photo Modal Fullscreen -->
  <div id="photoModal" class="photo-modal-overlay">
   <div class="photo-modal-content"><button class="photo-modal-close" onclick="closePhotoModal()">✕</button> <img id="photoModalImage" class="photo-modal-image" alt="Foto Santri" loading="lazy" onerror="this.parentElement.parentElement.querySelector('.photo-modal-info').innerHTML = '❌ Foto tidak dapat dimuat';">
    <div class="photo-modal-info" id="photoModalInfo"></div>
   </div>
  </div>
  <script>
    const defaultConfig = {
      app_title: "JADWAL UJIAN SANTRI",
      exam_info: "SELURUH SANTRI MELAKSANAKAN UJIAN \n\nSELURUH SANTRI HADIR TEPAT WAKTU SESUAI JADWAL, JIKA TIDAK ADA JADWAL MAKA SANTRI BELAJAR DIRUMAH MASING MASING\n\nSELURUH SANTRI MASUK KEMBALI SEPERTI BIASA UNTUK",
      background_color: "#86efac",
      surface_color: "#ffffff",
      text_color: "#374151",
      primary_action_color: "#16a34a",
      secondary_action_color: "#facc15",
      font_family: "system-ui",
      font_size: 16
    };

    let studentsData = [];
    let currentConfig = defaultConfig;
    let isRefreshing = false;
    let refreshInterval;
    let customMessageData = [];

    const dataHandler = {
      onDataChanged(data) {
        customMessageData = data;
        updateCurrentMessageDisplay();
      }
    };

    async function initDataSdk() {
      if (window.dataSdk) {
        const result = await window.dataSdk.init(dataHandler);
        if (!result.isOk) {
          console.error('Failed to initialize Data SDK');
        }
      }
    }

    async function getCustomMessage() {
      if (customMessageData.length > 0) {
        return customMessageData[customMessageData.length - 1].custom_message || null;
      }
      return null;
    }

    function updateCurrentMessageDisplay() {
      const displayDiv = document.getElementById('currentMessageText');
      if (displayDiv) {
        if (customMessageData.length > 0) {
          const latestMsg = customMessageData[customMessageData.length - 1].custom_message;
          displayDiv.textContent = latestMsg || 'Belum ada pesan custom. Menggunakan pesan default.';
        } else {
          displayDiv.textContent = 'Belum ada pesan custom. Menggunakan pesan default.';
        }
      }
    }

    function openAdminModal() {
      const modal = document.getElementById('adminModal');
      const textarea = document.getElementById('adminMessageInput');
      
      if (customMessageData.length > 0) {
        textarea.value = customMessageData[customMessageData.length - 1].custom_message || '';
      }
      
      updateCurrentMessageDisplay();
      modal.classList.add('active');
    }

    function closeAdminModal() {
      document.getElementById('adminModal').classList.remove('active');
    }

    function openPhotoModal(photoUrl, nama, kelas) {
      const modal = document.getElementById('photoModal');
      const img = document.getElementById('photoModalImage');
      const info = document.getElementById('photoModalInfo');
      
      img.src = photoUrl;
      info.textContent = `${nama} - Kelas ${kelas}`;
      
      modal.classList.add('active');
      
      modal.addEventListener('click', function(e) {
        if (e.target === modal) {
          closePhotoModal();
        }
      });
      
      document.addEventListener('keydown', function(e) {
        if (e.key === 'Escape') {
          closePhotoModal();
        }
      });
    }

    function closePhotoModal() {
      document.getElementById('photoModal').classList.remove('active');
    }

    async function saveAdminMessage() {
      const textarea = document.getElementById('adminMessageInput');
      const message = textarea.value.trim();
      
      if (!message) {
        showNotification('📝 Pesan tidak boleh kosong!', 'warning');
        return;
      }

      if (!window.dataSdk) {
        showNotification('⚠️ Data SDK tidak tersedia!', 'error');
        return;
      }

      const saveBtn = document.getElementById('saveMessageBtn');
      saveBtn.disabled = true;
      saveBtn.innerHTML = '<span>⏳ Menyimpan...</span>';

      try {
        if (customMessageData.length >= 999) {
          showNotification('⚠️ Batas maksimal 999 pesan tercapai! Tidak dapat menambah pesan baru.', 'warning');
          saveBtn.disabled = false;
          saveBtn.innerHTML = `💾 Simpan Pesan`;
          return;
        }

        const newMessage = {
          message_id: `msg_${Date.now()}`,
          custom_message: message,
          created_at: new Date().toISOString()
        };

        const result = await window.dataSdk.create(newMessage);
        
        if (result.isOk) {
          showNotification('✅ Pesan berhasil disimpan!', 'success');
          textarea.value = '';
          setTimeout(() => {
            closeAdminModal();
          }, 1000);
        } else {
          showNotification('❌ Gagal menyimpan pesan!', 'error');
        }
      } catch (error) {
        console.error('Error saving message:', error);
        showNotification('❌ Terjadi kesalahan saat menyimpan!', 'error');
      } finally {
        saveBtn.disabled = false;
        saveBtn.innerHTML = `💾 Simpan Pesan`;
      }
    }

    function showNotification(message, type = 'info') {
      const notification = document.createElement('div');
      const bgColor = type === 'success' ? 'bg-green-600' : type === 'error' ? 'bg-red-600' : type === 'warning' ? 'bg-yellow-600' : 'bg-blue-600';
      
      notification.style.cssText = `position: fixed; top: 20px; right: 20px; ${bgColor}; color: white; padding: 16px 24px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); z-index: 3000; font-weight: 600; animation: slideIn 0.3s ease-out;`;
      notification.className = bgColor + ' text-white';
      notification.textContent = message;
      
      document.body.appendChild(notification);
      
      setTimeout(() => {
        notification.style.animation = 'slideOut 0.3s ease-out';
        setTimeout(() => notification.remove(), 300);
      }, 3000);
    }

    document.getElementById('adminButton').addEventListener('click', openAdminModal);

    document.getElementById('teacherButton').addEventListener('click', openTeacherPage);

    async function onConfigChange(config) {
      currentConfig = config;
      
      const baseSize = config.font_size || defaultConfig.font_size;
      const customFont = config.font_family || defaultConfig.font_family;
      const baseFontStack = 'system-ui, -apple-system, sans-serif';
      
      const title = (config.app_title || defaultConfig.app_title).replace(/\n/g, '<br>');
      document.getElementById('app-title').innerHTML = title;
      document.getElementById('app-title').style.fontFamily = `${customFont}, ${baseFontStack}`;
      document.getElementById('app-title').style.fontSize = `${baseSize * 2}px`;
      
      document.body.style.fontFamily = `${customFont}, ${baseFontStack}`;
      document.body.style.fontSize = `${baseSize}px`;
    }

    const capabilities = {
      recolorables: [
        {
          get: () => currentConfig.background_color || defaultConfig.background_color,
          set: (value) => {
            currentConfig.background_color = value;
            if (window.elementSdk) window.elementSdk.setConfig({ background_color: value });
          }
        },
        {
          get: () => currentConfig.surface_color || defaultConfig.surface_color,
          set: (value) => {
            currentConfig.surface_color = value;
            if (window.elementSdk) window.elementSdk.setConfig({ surface_color: value });
          }
        },
        {
          get: () => currentConfig.text_color || defaultConfig.text_color,
          set: (value) => {
            currentConfig.text_color = value;
            if (window.elementSdk) window.elementSdk.setConfig({ text_color: value });
          }
        },
        {
          get: () => currentConfig.primary_action_color || defaultConfig.primary_action_color,
          set: (value) => {
            currentConfig.primary_action_color = value;
            if (window.elementSdk) window.elementSdk.setConfig({ primary_action_color: value });
          }
        },
        {
          get: () => currentConfig.secondary_action_color || defaultConfig.secondary_action_color,
          set: (value) => {
            currentConfig.secondary_action_color = value;
            if (window.elementSdk) window.elementSdk.setConfig({ secondary_action_color: value });
          }
        }
      ],
      borderables: [],
      fontEditable: {
        get: () => currentConfig.font_family || defaultConfig.font_family,
        set: (value) => {
          currentConfig.font_family = value;
          if (window.elementSdk) window.elementSdk.setConfig({ font_family: value });
        }
      },
      fontSizeable: {
        get: () => currentConfig.font_size || defaultConfig.font_size,
        set: (value) => {
          currentConfig.font_size = value;
          if (window.elementSdk) window.elementSdk.setConfig({ font_size: value });
        }
      }
    };

    async function loadStudentData(showNotification = true) {
      const loadingMsg = document.getElementById('resultContainer');
      
      if (showNotification && !isRefreshing) {
        loadingMsg.innerHTML = '<div class="profile-card text-center"><p class="text-green-700">⏳ Memuat data santri...</p></div>';
      }
      
      isRefreshing = true;
      
      try {
        const timestamp = new Date().getTime();
        const response = await fetch(`https://docs.google.com/spreadsheets/d/e/2PACX-1vQ3jmw8son5_Yig0PwbsH69YeY8nGMK58dylFHIBN9fcmpn5uHzkB0JyObcrRZ1GDTaL2D0UzbohkEf/pub?gid=0&single=true&output=csv&cachebust=${timestamp}`, {
          method: 'GET',
          mode: 'cors'
        });
        
        if (!response.ok) {
          throw new Error('Gagal mengambil data');
        }
        
        const csvText = await response.text();
        const lines = csvText.trim().split('\n');
        
        if (lines.length < 2) {
          throw new Error('Data spreadsheet kosong');
        }
        
        const headers = lines[0].split(',').map(h => h.trim().replace(/"/g, ''));
        
        studentsData = [];
        for (let i = 1; i < lines.length; i++) {
          const line = lines[i].trim();
          if (!line) continue;
          
          const values = [];
          let currentValue = '';
          let insideQuotes = false;
          
          for (let char of line) {
            if (char === '"') {
              insideQuotes = !insideQuotes;
            } else if (char === ',' && !insideQuotes) {
              values.push(currentValue.trim());
              currentValue = '';
            } else {
              currentValue += char;
            }
          }
          values.push(currentValue.trim());
          
          const student = {};
          headers.forEach((header, index) => {
            student[header] = (values[index] || '').replace(/"/g, '');
          });
          
          if (student[headers[0]]) {
            studentsData.push(student);
          }
        }
        
        if (showNotification) {
          loadingMsg.innerHTML = `<div class="profile-card text-center"><p class="text-green-700">✅ Data ${studentsData.length} santri berhasil dimuat!</p><p class="text-sm text-gray-600 mt-2">Silakan ketik minimal 3 huruf nama santri di kolom pencarian</p><p class="text-xs text-gray-500 mt-1">🔄 Data otomatis ter-refresh setiap 30 detik</p></div>`;
        }
        
        if (studentsData.length > 0) {
          console.log('🔄 Data ter-refresh:', new Date().toLocaleTimeString());
          console.log('Jumlah santri:', studentsData.length);
          console.log('Kolom tersedia:', Object.keys(studentsData[0]));
        }
        
        isRefreshing = false;
        
      } catch (error) {
        if (showNotification) {
          loadingMsg.innerHTML = `<div class="profile-card text-center"><p class="text-red-600">❌ Gagal memuat data: ${error.message}</p><p class="text-sm text-gray-600 mt-2">Pastikan spreadsheet sudah dipublikasikan dan link benar</p></div>`;
        }
        console.error('Error loading data:', error);
        isRefreshing = false;
      }
    }

    function startAutoRefresh() {
      refreshInterval = setInterval(() => {
        loadStudentData(false);
        console.log('🔄 Auto-refresh data...');
      }, 30000);
    }

    function stopAutoRefresh() {
      if (refreshInterval) {
        clearInterval(refreshInterval);
      }
    }

    function searchStudents(query) {
      if (query.length < 3) return [];
      const lowerQuery = query.toLowerCase();
      
      return studentsData.filter(student => {
        const namaFields = ['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA'];
        
        for (let field of namaFields) {
          if (student[field] && student[field].toLowerCase().includes(lowerQuery)) {
            return true;
          }
        }
        
        const firstKey = Object.keys(student)[0];
        if (student[firstKey] && student[firstKey].toLowerCase().includes(lowerQuery)) {
          return true;
        }
        
        return false;
      });
    }

    function displaySuggestions(students) {
      const suggestionsList = document.getElementById('suggestionsList');
      
      if (students.length === 0) {
        suggestionsList.innerHTML = '<div style="padding: 12px 16px; text-align: center; color: #666;">❌ Tidak ada santri ditemukan</div>';
        suggestionsList.style.display = 'block';
        return;
      }

      suggestionsList.innerHTML = students.map(student => {
        const namaFields = ['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA'];
        let nama = '';
        
        for (let field of namaFields) {
          if (student[field]) {
            nama = student[field];
            break;
          }
        }
        
        if (!nama) {
          nama = student[Object.keys(student)[0]];
        }
        
        return `<div class="suggestion-item" data-name="${nama}">${nama}</div>`;
      }).join('');
      
      suggestionsList.style.display = 'block';

      document.querySelectorAll('.suggestion-item').forEach(item => {
        item.addEventListener('click', function() {
          const name = this.getAttribute('data-name');
          document.getElementById('searchInput').value = name;
          displayStudentProfile(name);
          suggestionsList.style.display = 'none';
        });
      });
    }

    async function displayStudentProfile(name) {
      const student = studentsData.find(s => {
        const namaFields = ['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA'];
        for (let field of namaFields) {
          if (s[field] === name) return true;
        }
        return s[Object.keys(s)[0]] === name;
      });
      
      if (!student) return;

      const getData = (possibleNames) => {
        for (let name of possibleNames) {
          if (student[name]) return student[name];
        }
        return '-';
      };
      
      const namaSiswa = getData(['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA', Object.keys(student)[0]]);
      const kelas = getData(['Kelas', 'kelas', 'KELAS']);
      const jadwalUjian = getData(['Jadwal Ujian (Hari/Tanggal)', 'Jadwal Ujian', 'jadwal ujian', 'JADWAL UJIAN']);
      const waktuUjian = getData(['Waktu Ujian', 'waktu ujian', 'WAKTU UJIAN', 'Waktu']);
      const ruangKelas = getData(['Ruang Kelas', 'ruang kelas', 'RUANG KELAS', 'Ruang']);
      const guruPenguji = getData(['Nama Guru Penguji', 'Guru Penguji', 'guru penguji', 'GURU PENGUJI', 'Guru']);
      const nomorHP = getData(['Nomor HP', 'nomor hp', 'NOMOR HP', 'No HP', 'HP', 'Telepon']);
      let fotoSiswa = getData(['Foto Siswa', 'foto siswa', 'FOTO SISWA', 'Foto', 'URL Foto', 'url foto']);
      
      const waNumber = nomorHP.replace(/\D/g, '');
      
      const customMsg = await getCustomMessage();
      let waMessageBody = '';
      
      if (customMsg) {
        const processedMsg = customMsg
          .replace(/{ruang}/g, ruangKelas)
          .replace(/{guru}/g, guruPenguji);
        waMessageBody = encodeURIComponent(processedMsg);
      } else {
        waMessageBody = `🔔 Perhatian Penting untuk Wali Santri:%0A• Mohon pastikan ananda hadir TEPAT WAKTU sesuai jadwal yang tertera%0A• Ujian dilaksanakan sesuai jadwal yang tertera%0A• Jika tidak ada jadwal ujian pada hari tertentu, santri belajar di rumah masing-masing%0A• Apabila ananda berhalangan hadir, mohon segera menghubungi Wali Kelas untuk koordinasi lebih lanjut%0A• %0A%0A📍 Lokasi Ujian: ${ruangKelas}%0A👨‍🏫 Guru Penguji: ${guruPenguji}%0A%0A📞 Informasi & Koordinasi:%0A• Untuk informasi lebih lanjut atau pertanyaan seputar ujian, silakan hubungi Wali Kelas masing-masing%0A• Jika ada perubahan jadwal atau keperluan khusus, segera koordinasikan dengan Wali Kelas%0A• Nomor kontak Wali Kelas dapat dilihat di atas atau melalui grup kelas`;
      }
      
      const waMessage = `Assalamualaikum Warahmatullahi Wabarakatuh,%0A%0AKepada Yth.%0AAbi Umi / Bapak Ibu Wali Santri%0A%0ADengan hormat,%0A%0APerkenalkan saya Wali Kelas dari *${namaSiswa}* Kelas *${kelas}*.%0A%0ABerikut kami sampaikan informasi jadwal ujian untuk putra/putri Bapak/Ibu:%0A%0A📋 *DETAIL JADWAL UJIAN*%0A━━━━━━━━━━━━━━━━━━━━━━%0A📅 Jadwal: *${jadwalUjian}*%0A🕐 Waktu: *${waktuUjian}*%0A🏫 Ruang: *${ruangKelas}*%0A👨‍🏫 Guru Penguji: *${guruPenguji}*%0A━━━━━━━━━━━━━━━━━━━━━━%0A%0A${waMessageBody}%0A%0ADemikian informasi yang dapat kami sampaikan. Atas perhatian dan kerjasamanya, kami ucapkan terima kasih.%0A%0AWassalamualaikum Warahmatullahi Wabarakatuh%0A%0A_Wali Kelas ${kelas}_`;
      const waLink = waNumber ? `https://wa.me/${waNumber.startsWith('62') ? waNumber : '62' + waNumber.replace(/^0/, '')}?text=${waMessage}` : '#';
      const telLink = `tel:${nomorHP}`;

      const detailContent = document.getElementById('detailContent');
      
      let personalMessage = '';
      
      if (customMsg) {
        const processedMsg = customMsg
          .replace(/{ruang}/g, ruangKelas)
          .replace(/{guru}/g, guruPenguji);
        personalMessage = `
          <strong>📢 INFORMASI UJIAN UNTUK ${namaSiswa.toUpperCase()}:</strong><br><br>
          
          Ananda <strong>${namaSiswa}</strong> melaksanakan ujian pada <strong>${jadwalUjian}</strong> pukul <strong>${waktuUjian}</strong>.<br><br>
          
          ${processedMsg.replace(/\n/g, '<br>')}
        `;
      } else {
        personalMessage = `
          <strong>📢 INFORMASI UJIAN UNTUK ${namaSiswa.toUpperCase()}:</strong><br><br>
          
          Ananda <strong>${namaSiswa}</strong> melaksanakan ujian pada <strong>${jadwalUjian}</strong> pukul <strong>${waktuUjian}</strong>.<br><br>
          
          <strong>🔔 Perhatian Penting untuk Wali Santri:</strong><br>
          • Mohon pastikan ananda hadir <strong>TEPAT WAKTU</strong> sesuai jadwal yang tertera<br>
          • Ujian dilaksanakan sesuai jadwal yang tertera<br>
          • Jika tidak ada jadwal ujian pada hari tertentu, santri <strong>belajar di rumah masing-masing</strong><br>
          • <strong>Apabila ananda berhalangan hadir</strong>, mohon segera menghubungi <strong>Wali Kelas</strong> untuk koordinasi lebih lanjut<br>
          • Seluruh santri masuk seperti Setelah Ujian ini <strong></strong>
        `;
      }
      
      let photoUrl = fotoSiswa.trim();
      const initials = namaSiswa.charAt(0).toUpperCase();
      
      if (photoUrl.includes('src=')) {
        let srcMatch = photoUrl.match(/src\s*=\s*["']?([^\s"'<>]+)["']?/i);
        if (srcMatch && srcMatch[1]) {
          photoUrl = srcMatch[1].trim();
        } else {
          photoUrl = '';
        }
      } else if (photoUrl.startsWith('http')) {
        photoUrl = photoUrl;
      } else {
        photoUrl = '';
      }
      
      console.log('📸 Student:', namaSiswa);
      console.log('📸 Raw foto data:', fotoSiswa);
      console.log('📸 Extracted URL:', photoUrl);
      
      const mapHTML = buildExamMap(ruangKelas);
      
      detailContent.innerHTML = `
        <div class="profile-card">
          ${photoUrl && photoUrl.length > 0 ? `
            <div class="photo-section">
              <div class="student-photo-container" onclick="openPhotoModal('${photoUrl}', '${namaSiswa}', '${kelas}')">
                <img src="${photoUrl}" alt="${namaSiswa}" loading="lazy" onerror="this.parentElement.innerHTML='${initials}';">
              </div>
              <div style="text-align: center; margin-top: 16px; font-weight: 700; color: #16a34a; font-size: 20px;">${namaSiswa}</div>
              <div style="text-align: center; font-size: 16px; color: #16a34a; font-weight: 600; margin-top: 4px;">${kelas}</div>
            </div>
          ` : `
            <div class="photo-section">
              <div class="student-photo-container" onclick="openPhotoModal('', '${namaSiswa}', '${kelas}')">
                ${initials}
              </div>
              <div style="text-align: center; margin-top: 16px; font-weight: 700; color: #16a34a; font-size: 20px;">${namaSiswa}</div>
              <div style="text-align: center; font-size: 16px; color: #16a34a; font-weight: 600; margin-top: 4px;">${kelas}</div>
            </div>
          `}
          
          <div class="space-y-1" style="margin-top: 24px;">
            <div class="info-row">
              <span class="info-label">📅 Jadwal Ujian:</span>
              <span class="info-value font-semibold">${jadwalUjian}</span>
            </div>
            
            <div class="info-row">
              <span class="info-label">🕐 Waktu Ujian:</span>
              <span class="info-value font-semibold">${waktuUjian}</span>
            </div>
            
            <div class="info-row">
              <span class="info-label">🏫 Ruang Kelas:</span>
              <span class="info-value">${ruangKelas}</span>
            </div>
            
            <div class="info-row">
              <span class="info-label">👨‍🏫 Guru Penguji:</span>
              <span class="info-value">${guruPenguji}</span>
            </div>
            
            <div class="info-row">
              <span class="info-label">📱 Nomor HP:</span>
              <div class="flex gap-2 items-center justify-end flex-wrap">
                <span class="info-value">${nomorHP}</span>
                ${waNumber ? `
                  <a href="${telLink}" class="btn-call">
                    ☎️ Telepon
                  </a>
                  <a href="${waLink}" target="_blank" rel="noopener noreferrer" class="btn-wa">
                    💬 WhatsApp
                  </a>
                ` : ''}
              </div>
            </div>
          </div>

          <div id="exam-info" class="info-box text-sm mt-6">
            ${personalMessage}
          </div>

          <div class="exam-map-container mt-8" id="examMap">
            ${mapHTML}
          </div>
        </div>
      `;

      document.getElementById('searchPage').classList.add('hidden');
      document.getElementById('detailPage').classList.add('active');
      document.getElementById('suggestionsList').style.display = 'none';
    }

    function openTeacherPage() {
      const teachersMap = new Map();

      studentsData.forEach(student => {
        const getData = (possibleNames) => {
          for (let name of possibleNames) {
            if (student[name]) return student[name];
          }
          return '-';
        };

        const guru = getData(['Nama Guru Penguji', 'Guru Penguji', 'guru penguji', 'GURU PENGUJI', 'Guru']);
        const ruang = getData(['Ruang Kelas', 'ruang kelas', 'RUANG KELAS', 'Ruang']);
        const hp = getData(['Nomor HP', 'nomor hp', 'NOMOR HP', 'No HP', 'HP', 'Telepon']);

        if (guru !== '-' && !teachersMap.has(guru)) {
          teachersMap.set(guru, {
            nama: guru,
            ruang: ruang,
            hp: hp
          });
        }
      });

      const teachersTableBody = document.getElementById('teachersTableBody');
      teachersTableBody.innerHTML = '';

      if (teachersMap.size === 0) {
        teachersTableBody.innerHTML = '<tr><td colspan="4" style="padding: 16px; text-align: center; color: #666; font-size: 13px;">📋 Belum ada data guru penguji</td></tr>';
      } else {
        let no = 1;
        Array.from(teachersMap.values()).forEach(teacher => {
          const row = document.createElement('tr');
          row.style.cssText = 'border: 2px solid #d1d5db; background: white; transition: background-color 0.2s; font-size: 13px;';
          row.onmouseover = () => row.style.background = '#f0fdf4';
          row.onmouseout = () => row.style.background = 'white';

          row.innerHTML = `
            <td style="padding: 8px; border: 2px solid #d1d5db; color: #16a34a; font-weight: 600; text-align: center; font-size: 12px;">${no}</td>
            <td style="padding: 8px; border: 2px solid #d1d5db; color: #000; font-weight: 600; cursor: pointer; font-size: 12px;" onclick="showStudentsForTeacher('${teacher.nama}')">${teacher.nama}</td>
            <td style="padding: 8px; border: 2px solid #d1d5db; color: #4b5563; font-size: 12px;">${teacher.ruang}</td>
            <td style="padding: 8px; border: 2px solid #d1d5db; text-align: center;">
              <button onclick="showStudentsForTeacher('${teacher.nama}')" style="background: #16a34a; color: white; border: none; padding: 6px 12px; border-radius: 6px; cursor: pointer; font-weight: 600; transition: all 0.2s; font-size: 11px;" onmouseover="this.style.background='#15803d'" onmouseout="this.style.background='#16a34a'">
                👀 Lihat
              </button>
            </td>
          `;

          teachersTableBody.appendChild(row);
          no++;
        });
      }

      document.getElementById('searchPage').classList.add('hidden');
      document.getElementById('teacherPage').classList.add('active');
    }

    function showStudentsForTeacher(teacherName) {
      let studentsForTeacher = studentsData.filter(student => {
        const getData = (possibleNames) => {
          for (let name of possibleNames) {
            if (student[name]) return student[name];
          }
          return '-';
        };
        
        const guru = getData(['Nama Guru Penguji', 'Guru Penguji', 'guru penguji', 'GURU PENGUJI', 'Guru']);
        return guru === teacherName;
      });

      studentsForTeacher.sort((a, b) => {
        const getDateField = (student) => {
          const fieldNames = ['Jadwal Ujian (Hari/Tanggal)', 'Jadwal Ujian', 'jadwal ujian', 'JADWAL UJIAN'];
          for (let field of fieldNames) {
            if (student[field] && student[field] !== '-' && student[field].trim() !== '') {
              return student[field].trim();
            }
          }
          return '-';
        };
        
        const dateA = getDateField(a);
        const dateB = getDateField(b);
        
        console.log('📅 Sorting - A:', dateA, 'B:', dateB);
        
        const extractDate = (dateStr) => {
          if (!dateStr || dateStr === '-') {
            return new Date(9999, 11, 31);
          }
          
          let day, month, year;
          
          const monthMap = {
            'januari': 1, 'februari': 2, 'maret': 3, 'april': 4, 'mei': 5, 'juni': 6,
            'juli': 7, 'agustus': 8, 'september': 9, 'oktober': 10, 'november': 11, 'desember': 12
          };
          
          let textMatch = dateStr.match(/(\d{1,2})\s+([a-z]+)\s+(\d{4})/i);
          if (textMatch) {
            day = parseInt(textMatch[1], 10);
            const monthName = textMatch[2].toLowerCase();
            month = monthMap[monthName] || 0;
            year = parseInt(textMatch[3], 10);
            
            if (month > 0) {
              console.log(`  ✅ Parsed Indonesian format: Day=${day}, Month=${month}, Year=${year}`);
              return year * 10000 + month * 100 + day;
            }
          }
          
          let slashMatch = dateStr.match(/(\d{1,2})[\/-](\d{1,2})[\/-](\d{4})/);
          if (slashMatch) {
            day = parseInt(slashMatch[1], 10);
            month = parseInt(slashMatch[2], 10);
            year = parseInt(slashMatch[3], 10);
            
            console.log(`  ✅ Parsed slash format: Day=${day}, Month=${month}, Year=${year}`);
            return year * 10000 + month * 100 + day;
          }
          
          console.log(`  ⚠️ Could not parse: "${dateStr}"`);
          return 99999999;
        };
        
        const timeA = extractDate(dateA);
        const timeB = extractDate(dateB);
        
        console.log(`  Timestamps: A=${timeA}, B=${timeB}, Result=${timeA - timeB}`);
        
        return timeA - timeB;
      });

      document.getElementById('selectedTeacherName').innerHTML = `👨‍🏫 Siswa Mengikuti Ujian - <span style="color: #16a34a;">${teacherName}</span>`;

      window.currentTeacher = teacherName;
      window.currentStudentsForTeacher = studentsForTeacher;

      const studentTableBody = document.getElementById('studentTableBody');
      studentTableBody.innerHTML = '';

      if (studentsForTeacher.length === 0) {
        studentTableBody.innerHTML = '<tr><td colspan="6" style="padding: 20px; text-align: center; color: #666;">📋 Belum ada siswa untuk guru ini</td></tr>';
      } else {
        let no = 1;
        studentsForTeacher.forEach(student => {
          const getData = (possibleNames) => {
            for (let name of possibleNames) {
              if (student[name]) return student[name];
            }
            return '-';
          };

          const namaSiswa = getData(['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA', Object.keys(student)[0]]);
          const jadwalUjian = getData(['Jadwal Ujian (Hari/Tanggal)', 'Jadwal Ujian', 'jadwal ujian', 'JADWAL UJIAN']);
          const waktuUjian = getData(['Waktu Ujian', 'waktu ujian', 'WAKTU UJIAN', 'Waktu']);
          const nomorHP = getData(['Nomor HP', 'nomor hp', 'NOMOR HP', 'No HP', 'HP', 'Telepon']);

          const waNumber = nomorHP.replace(/\D/g, '');
          const waLink = waNumber ? `https://wa.me/${waNumber.startsWith('62') ? waNumber : '62' + waNumber.replace(/^0/, '')}` : '#';

          const row = document.createElement('tr');
          row.style.cssText = 'border: 2px solid #d1d5db; background: white; transition: background-color 0.2s; font-size: 13px;';
          row.onmouseover = () => row.style.background = '#f0fdf4';
          row.onmouseout = () => row.style.background = 'white';

          row.innerHTML = `
            <td style="padding: 10px 8px; border: 2px solid #d1d5db; color: #16a34a; font-weight: 600; text-align: center; font-size: 12px;">${no}</td>
            <td style="padding: 10px 8px; border: 2px solid #d1d5db; color: #000; font-weight: 600; font-size: 12px; min-width: 130px;">${namaSiswa}</td>
            <td style="padding: 10px 8px; border: 2px solid #d1d5db; color: #000; font-weight: 600; text-align: center; font-size: 12px; min-width: 110px;">${jadwalUjian}</td>
            <td style="padding: 10px 8px; border: 2px solid #d1d5db; color: #000; font-weight: 600; text-align: center; font-size: 12px; min-width: 90px;">${waktuUjian}</td>
            <td style="padding: 10px 8px; border: 2px solid #d1d5db; text-align: center; font-size: 11px; min-width: 110px;">
              <a href="${waLink}" target="_blank" rel="noopener noreferrer" style="color: #25d366; text-decoration: none; font-weight: 700; padding: 4px 8px; background: #f0f0f0; border-radius: 4px; display: inline-block; transition: all 0.2s; cursor: pointer; font-size: 11px;" onmouseover="this.style.background='#e0e0e0'; this.style.color='#1da851';" onmouseout="this.style.background='#f0f0f0'; this.style.color='#25d366';">
                💬 ${nomorHP}
              </a>
            </td>
          `;

          studentTableBody.appendChild(row);
          no++;
        });
      }

      document.getElementById('studentSearchInput').value = '';

      document.getElementById('teacherTableSection').style.display = 'none';
      document.getElementById('studentListSection').style.display = 'block';
    }

    function openPrintTeacherPage() {
      if (!window.currentStudentsForTeacher || window.currentStudentsForTeacher.length === 0) {
        showNotification('❌ Belum ada siswa dipilih!', 'error');
        return;
      }

      const teacherName = window.currentTeacher;
      const students = window.currentStudentsForTeacher;

      let htmlContent = `
        <!DOCTYPE html>
        <html lang="id">
        <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Daftar Ujian - ${teacherName}</title>
          <style>
            * {
              margin: 0;
              padding: 0;
              box-sizing: border-box;
            }
            
            body {
              font-family: 'Arial', sans-serif;
              background: white;
              padding: 20px;
            }

            .print-container {
              max-width: 900px;
              margin: 0 auto;
            }

            .header {
              text-align: center;
              margin-bottom: 30px;
              border-bottom: 3px solid #16a34a;
              padding-bottom: 20px;
            }

            .header h1 {
              font-size: 28px;
              font-weight: bold;
              color: #16a34a;
              margin-bottom: 8px;
            }

            .header p {
              font-size: 16px;
              color: #16a34a;
              font-weight: 600;
              margin-bottom: 4px;
            }

            .header .teacher-info {
              font-size: 14px;
              color: #000;
              margin-top: 12px;
              font-weight: bold;
            }

            .print-table {
              width: 100%;
              border-collapse: collapse;
              margin-bottom: 40px;
            }

            .print-table th {
              background: linear-gradient(135deg, #86efac 0%, #dcfce7 100%);
              border: 2px solid #16a34a;
              padding: 14px;
              text-align: left;
              font-weight: 700;
              color: #16a34a;
              font-size: 14px;
            }

            .print-table td {
              border: 2px solid #16a34a;
              padding: 14px;
              font-size: 13px;
              color: #000;
            }

            .print-table tr:nth-child(odd) {
              background: #f0fdf4;
            }

            .print-table tr:nth-child(even) {
              background: white;
            }

            .signature-cell {
              height: 80px;
              vertical-align: bottom;
              padding-bottom: 8px;
              border-top: 2px solid #000;
              text-align: center;
              font-size: 10px;
              color: #666;
            }

            .page-break {
              page-break-after: always;
              margin-bottom: 40px;
            }

            .footer {
              text-align: center;
              margin-top: 40px;
              padding-top: 20px;
              border-top: 2px solid #ccc;
              font-size: 12px;
              color: #666;
            }

            .print-button-container {
              position: fixed;
              top: 20px;
              right: 20px;
              z-index: 1000;
              display: flex;
              gap: 10px;
            }

            .print-button {
              background: #16a34a;
              color: white;
              border: none;
              padding: 12px 24px;
              border-radius: 8px;
              font-size: 16px;
              font-weight: bold;
              cursor: pointer;
              box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
              transition: all 0.2s;
            }

            .print-button:hover {
              background: #15803d;
              transform: translateY(-2px);
            }

            .close-button {
              background: #dc2626;
            }

            .close-button:hover {
              background: #b91c1c;
            }

            @media print {
              .print-button-container {
                display: none !important;
              }

              body {
                padding: 0;
              }

              .page-break {
                page-break-after: always;
              }

              @page {
                size: A4 portrait;
                margin: 0.5cm;
              }
            }

            @media screen {
              body {
                background: #f5f5f5;
              }

              .print-container {
                background: white;
                padding: 30px;
                border-radius: 8px;
                box-shadow: 0 2px 8px rgba(0,0,0,0.1);
              }
            }

            .no-column {
              width: 50px;
              text-align: center;
            }

            .name-column {
              width: 200px;
            }

            .wa-column {
              width: 120px;
              text-align: center;
            }

            .signature-column {
              flex: 1;
            }
          </style>
        </head>
        <body>
          <div class="print-button-container">
            <button class="print-button" onclick="window.print()">
              📄 Cetak Sekarang
            </button>
            <button class="print-button close-button" onclick="window.close()">
              ✕ Tutup
            </button>
          </div>

          <div class="print-container">
            <div class="header">
              <h1>📋 DAFTAR UJIAN SANTRI</h1>
              <p>SD International Tahfizh Quran</p>
              <div class="teacher-info">
                Guru Penguji: <strong>${teacherName}</strong>
              </div>
            </div>

            <table class="print-table">
              <thead>
                <tr>
                  <th class="no-column">No</th>
                  <th class="name-column">Nama Siswa</th>
                  <th style="width: 120px; text-align: center;">📅 Tanggal Ujian</th>
                  <th style="width: 100px; text-align: center;">🕐 Waktu Ujian</th>
                  <th class="wa-column">📱 HP Orang Tua</th>
                  <th class="signature-column">Tanda Tangan Orang Tua</th>
                </tr>
              </thead>
              <tbody>
      `;

      students.forEach((student, index) => {
        const getData = (possibleNames) => {
          for (let name of possibleNames) {
            if (student[name]) return student[name];
          }
          return '-';
        };

        const namaSiswa = getData(['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA', Object.keys(student)[0]]);
        const jadwalUjian = getData(['Jadwal Ujian (Hari/Tanggal)', 'Jadwal Ujian', 'jadwal ujian', 'JADWAL UJIAN']);
        const waktuUjian = getData(['Waktu Ujian', 'waktu ujian', 'WAKTU UJIAN', 'Waktu']);
        const nomorHP = getData(['Nomor HP', 'nomor hp', 'NOMOR HP', 'No HP', 'HP', 'Telepon']);

        htmlContent += `
          <tr>
            <td class="no-column"><strong>${index + 1}</strong></td>
            <td class="name-column">${namaSiswa}</td>
            <td style="text-align: center; padding: 12px; border: 2px solid #16a34a;">${jadwalUjian}</td>
            <td style="text-align: center; padding: 12px; border: 2px solid #16a34a;">${waktuUjian}</td>
            <td class="wa-column">${nomorHP}</td>
            <td class="signature-column"></td>
          </tr>
        `;
      });

      htmlContent += `
              </tbody>
            </table>

            <div class="footer">
              <p>Dicetak pada: ${new Date().toLocaleDateString('id-ID', { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' })}</p>
              <p style="margin-top: 8px; font-size: 11px;">Setiap orang tua wajib menandatangani daftar ini sebagai bukah persetujuan ujian anaknya</p>
            </div>
          </div>
        </body>
        </html>
      `;

      const printWindow = window.open('', '_blank');
      printWindow.document.write(htmlContent);
      printWindow.document.close();
    }

    document.getElementById('studentSearchInput').addEventListener('input', function(e) {
      const query = e.target.value.toLowerCase();
      const rows = document.querySelectorAll('#studentTableBody tr');

      rows.forEach(row => {
        const cells = row.querySelectorAll('td');
        if (cells.length > 0) {
          const text = cells[1].textContent.toLowerCase();
          row.style.display = text.includes(query) ? '' : 'none';
        }
      });
    });

    document.getElementById('backToTeachersButton').addEventListener('click', function() {
      document.getElementById('teacherTableSection').style.display = 'block';
      document.getElementById('studentListSection').style.display = 'none';
      document.getElementById('studentSearchInput').value = '';
    });

    function buildExamMap(ruangKelas) {
      const buildingK = {};
      const buildingM = {};

      studentsData.forEach(student => {
        const getData = (possibleNames) => {
          for (let name of possibleNames) {
            if (student[name]) return student[name];
          }
          return '-';
        };

        const ruang = getData(['Ruang Kelas', 'ruang kelas', 'RUANG KELAS', 'Ruang']);
        const guru = getData(['Nama Guru Penguji', 'Guru Penguji', 'guru penguji', 'GURU PENGUJI', 'Guru']);

        if (ruang.startsWith('K')) {
          if (!buildingK[ruang]) buildingK[ruang] = new Set();
          buildingK[ruang].add(guru);
        } else if (ruang.startsWith('M')) {
          if (!buildingM[ruang]) buildingM[ruang] = new Set();
          buildingM[ruang].add(guru);
        }
      });

      const kRoomsData = Object.entries(buildingK).sort((a, b) => a[0].localeCompare(b[0]));
      const mRoomsData = Object.entries(buildingM).sort((a, b) => a[0].localeCompare(b[0]));

      let html = `
        <div class="exam-map-title">📍 PETA LOKASI UJIAN DAN GURU PENGUJI</div>
        <div style="display: flex; justify-content: center; align-items: flex-start; margin-top: 20px; gap: 40px; flex-wrap: wrap;">
          <div class="gate">
            <div class="gate-icon">🚪</div>
            <div class="gate-label">GERBANG MASUK</div>
          </div>
          
          <div style="text-align: center; background: linear-gradient(135deg, #86efac 0%, #dcfce7 100%); border: 3px solid #16a34a; border-radius: 12px; padding: 16px; min-width: 200px; margin-left: 60px;">
            <div style="font-size: 28px; margin-bottom: 8px;">🕌</div>
            <div style="font-size: 14px; font-weight: 700; color: #16a34a; margin-bottom: 12px;">GEDUNG MUSHALLA</div>
            <div style="font-size: 11px; color: #16a34a; line-height: 1.5; margin-bottom: 10px;">
              <div style="font-weight: 700; margin-bottom: 4px;">LOKASI UJIAN TAHSIN:</div>
              Level I, II, III<br>& Kelas VI
            </div>
            <div style="font-size: 9px; color: #92400e; line-height: 1.5; background: rgba(253, 230, 138, 0.5); padding: 8px; border-radius: 6px; border: 1px solid #f59e0b;">
              <strong style="color: #92400e;">⚠️ Perhatian:</strong><br>
              Santri wajib ujian Tahsin sebelum ujian Level
            </div>
          </div>
        </div>
      `;

      if (kRoomsData.length > 0) {
        html += `
          <div style="margin-top: 20px;">
            <div style="font-size: 16px; font-weight: 700; color: #16a34a; margin-bottom: 12px;">GEDUNG K</div>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 12px;">
        `;

        kRoomsData.forEach(([room, teachers]) => {
          const teacherArray = Array.from(teachers).filter(t => t !== '-');
          const teacherText = teacherArray.length > 0 ? teacherArray.join('<br>') : 'TBD';

          html += `
            <div class="room-box">
              <div class="room-code">${room}</div>
              <div class="room-teacher">${teacherText}</div>
            </div>
          `;
        });

        html += `
            </div>
          </div>
        `;
      }

      if (mRoomsData.length > 0) {
        html += `
          <div style="margin-top: 20px;">
            <div style="font-size: 16px; font-weight: 700; color: #16a34a; margin-bottom: 12px;">GEDUNG M</div>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 12px;">
        `;

        mRoomsData.forEach(([room, teachers]) => {
          const teacherArray = Array.from(teachers).filter(t => t !== '-');
          const teacherText = teacherArray.length > 0 ? teacherArray.join('<br>') : 'TBD';

          html += `
            <div class="room-box">
              <div class="room-code">${room}</div>
              <div class="room-teacher">${teacherText}</div>
            </div>
          `;
        });

        html += `
            </div>
          </div>
        `;
      }

      html += `
        <div class="map-note">✨ Silakan datang lebih awal dan tanyakan lokasi ruang kepada panitia jika kurang jelas</div>
      `;

      return html;
    }

    document.getElementById('searchInput').addEventListener('input', function(e) {
      const query = e.target.value;
      if (query.length >= 3) {
        const results = searchStudents(query);
        displaySuggestions(results);
      } else {
        document.getElementById('suggestionsList').style.display = 'none';
        document.getElementById('resultContainer').innerHTML = '';
      }
    });

    document.addEventListener('click', function(e) {
      if (!e.target.closest('.search-container')) {
        document.getElementById('suggestionsList').style.display = 'none';
      }
    });

    document.getElementById('backButton').addEventListener('click', function() {
      document.getElementById('detailPage').classList.remove('active');
      document.getElementById('searchPage').classList.remove('hidden');
      document.getElementById('searchInput').value = '';
    });

    document.getElementById('backButtonTeacher').addEventListener('click', function() {
      document.getElementById('teacherPage').classList.remove('active');
      document.getElementById('searchPage').classList.remove('hidden');
      document.getElementById('searchInput').value = '';
    });

    let selectedStudents = [];

    document.getElementById('printButton').addEventListener('click', function() {
      openPrintModal();
    });

    function openPrintModal() {
      if (studentsData.length === 0) {
        const modal = document.createElement('div');
        modal.style.cssText = 'position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%); background: white; padding: 24px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); z-index: 2000; text-align: center;';
        modal.innerHTML = `
          <p class="text-red-600 font-semibold mb-4">❌ Data santri belum dimuat!</p>
          <p class="text-gray-600 text-sm mb-4">Mohon tunggu hingga data selesai dimuat</p>
          <button onclick="this.parentElement.remove()" class="bg-green-600 text-white px-6 py-2 rounded-lg">✓ OK</button>
        `;
        document.body.appendChild(modal);
        setTimeout(() => modal.remove(), 3000);
        return;
      }

      populateStudentsList();
      document.getElementById('printModal').classList.add('active');
    }

    function closePrintModal() {
      document.getElementById('printModal').classList.remove('active');
      selectedStudents = [];
    }

    function populateStudentsList() {
      const studentsList = document.getElementById('studentsList');
      
      studentsList.innerHTML = studentsData.map((student, index) => {
        const getData = (possibleNames) => {
          for (let name of possibleNames) {
            if (student[name]) return student[name];
          }
          return '-';
        };
        
        const namaSiswa = getData(['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA', Object.keys(student)[0]]);
        const kelas = getData(['Kelas', 'kelas', 'KELAS']);
        
        return `
          <label class="student-checkbox" data-index="${index}">
            <input type="checkbox" value="${index}" onchange="toggleStudent(${index})">
            <div>
              <div class="font-semibold text-gray-800">${namaSiswa}</div>
              <div class="text-sm text-gray-600">${kelas}</div>
            </div>
          </label>
        `;
      }).join('');

      updateSelectedCount();
    }

    function toggleStudent(index) {
      const checkbox = document.querySelector(`input[value="${index}"]`);
      const label = checkbox.closest('.student-checkbox');
      
      if (checkbox.checked) {
        selectedStudents.push(index);
        label.classList.add('selected');
      } else {
        selectedStudents = selectedStudents.filter(i => i !== index);
        label.classList.remove('selected');
      }
      
      updateSelectedCount();
    }

    function selectAllStudents() {
      selectedStudents = studentsData.map((_, index) => index);
      document.querySelectorAll('.student-checkbox input').forEach(checkbox => {
        checkbox.checked = true;
        checkbox.closest('.student-checkbox').classList.add('selected');
      });
      updateSelectedCount();
    }

    function deselectAllStudents() {
      selectedStudents = [];
      document.querySelectorAll('.student-checkbox input').forEach(checkbox => {
        checkbox.checked = false;
        checkbox.closest('.student-checkbox').classList.remove('selected');
      });
      updateSelectedCount();
    }

    function updateSelectedCount() {
      document.getElementById('selectedCount').textContent = selectedStudents.length;
    }

    document.getElementById('printSearchInput').addEventListener('input', function(e) {
      const query = e.target.value.toLowerCase();
      document.querySelectorAll('.student-checkbox').forEach(label => {
        const text = label.textContent.toLowerCase();
        label.style.display = text.includes(query) ? 'flex' : 'none';
      });
    });

    function generatePrint() {
      if (selectedStudents.length === 0) {
        const warning = document.createElement('div');
        warning.style.cssText = 'position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%); background: white; padding: 24px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); z-index: 2000; text-align: center;';
        warning.innerHTML = `
          <p class="text-yellow-600 font-semibold mb-4">⚠️ Belum ada santri dipilih!</p>
          <p class="text-gray-600 text-sm mb-4">Silakan pilih minimal 1 santri untuk dicetak</p>
          <button onclick="this.parentElement.remove()" class="bg-green-600 text-white px-6 py-2 rounded-lg">✓ OK</button>
        `;
        document.body.appendChild(warning);
        setTimeout(() => warning.remove(), 3000);
        return;
      }

      let htmlContent = `
        <!DOCTYPE html>
        <html lang="id">
        <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Cetak Jadwal Ujian Santri</title>
          <style>
            * {
              margin: 0;
              padding: 0;
              box-sizing: border-box;
            }
            
            body {
              font-family: 'Arial', sans-serif;
              background: white;
            }

            .print-page {
              width: 210mm;
              height: 297mm;
              page-break-after: always;
              position: relative;
              padding: 0;
              margin: 0 auto;
            }

            .card-half {
              width: 210mm;
              height: 148.5mm;
              position: relative;
              padding: 15mm;
              box-sizing: border-box;
            }

            .card-top {
              border-bottom: 3px dashed #999;
            }

            .card-content {
              background: white;
              border: 3px solid #16a34a;
              border-radius: 12px;
              padding: 20px;
              height: 100%;
              position: relative;
              display: flex;
              flex-direction: column;
            }

            .print-watermark {
              position: absolute;
              top: 50%;
              left: 50%;
              transform: translate(-50%, -50%);
              opacity: 0.15;
              width: 220px;
              height: auto;
              pointer-events: none;
              z-index: 1;
            }

            .print-header {
              text-align: center;
              border-bottom: 3px solid #000;
              padding-bottom: 12px;
              margin-bottom: 15px;
              position: relative;
              z-index: 10;
            }

            .print-header h1 {
              font-size: 20px;
              font-weight: bold;
              color: #000;
              margin-bottom: 4px;
              letter-spacing: 0.5px;
            }

            .print-header p {
              font-size: 14px;
              color: #000;
              font-weight: 600;
            }

            .student-identity {
              margin-bottom: 12px;
              padding: 12px;
              background: white;
              border: 2px solid #000;
              border-radius: 8px;
              position: relative;
              z-index: 10;
            }

            .student-name {
              font-size: 20px;
              font-weight: bold;
              color: #000;
              margin-bottom: 4px;
            }

            .student-class {
              font-size: 14px;
              color: #000;
            }

            .info-section {
              position: relative;
              z-index: 10;
              flex-grow: 1;
            }

            .info-row {
              display: flex;
              margin-bottom: 8px;
              font-size: 13px;
            }

            .info-label {
              font-weight: bold;
              color: #000;
              width: 140px;
              flex-shrink: 0;
            }

            .info-value {
              color: #000;
              font-weight: 600;
              flex: 1;
            }

            .info-text {
              font-size: 12px;
              line-height: 1.6;
              color: #000;
              margin-top: 10px;
              padding: 10px;
              background: white;
              border: 2px solid #000;
              border-radius: 6px;
              position: relative;
              z-index: 10;
            }

            .info-text strong {
              color: #000;
              font-size: 13px;
            }

            .print-button-container {
              position: fixed;
              top: 20px;
              right: 20px;
              z-index: 1000;
              display: flex;
              gap: 10px;
            }

            .print-button {
              background: #16a34a;
              color: white;
              border: none;
              padding: 12px 24px;
              border-radius: 8px;
              font-size: 16px;
              font-weight: bold;
              cursor: pointer;
              box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
              transition: all 0.2s;
            }

            .print-button:hover {
              background: #15803d;
              transform: translateY(-2px);
            }

            .close-button {
              background: #dc2626;
            }

            .close-button:hover {
              background: #b91c1c;
            }

            @media print {
              .print-button-container {
                display: none !important;
              }

              body {
                margin: 0;
                padding: 0;
              }

              .print-page {
                page-break-after: always;
                margin: 0;
              }

              @page {
                size: A4 portrait;
                margin: 0;
              }
            }

            @media screen {
              body {
                background: #f5f5f5;
                padding: 20px;
              }
            }
          </style>
        </head>
        <body>
          <div class="print-button-container">
            <button class="print-button" onclick="window.print()">
              📄 Cetak Semua
            </button>
            <button class="print-button close-button" onclick="window.close()">
              ✕ Tutup
            </button>
          </div>
      `;

      for (let i = 0; i < selectedStudents.length; i += 2) {
        htmlContent += '<div class="print-page">';
        
        const student1 = studentsData[selectedStudents[i]];
        htmlContent += '<div class="card-half card-top">';
        htmlContent += generateStudentCard(student1);
        htmlContent += '</div>';
        
        if (i + 1 < selectedStudents.length) {
          const student2 = studentsData[selectedStudents[i + 1]];
          htmlContent += '<div class="card-half">';
          htmlContent += generateStudentCard(student2);
          htmlContent += '</div>';
        }
        
        htmlContent += '</div>';
      }

      htmlContent += `
        </body>
        </html>
      `;

      const printWindow = window.open('', '_blank');
      printWindow.document.write(htmlContent);
      printWindow.document.close();
      
      closePrintModal();
    }

    function generateStudentCard(student) {
      const getData = (possibleNames) => {
        for (let name of possibleNames) {
          if (student[name]) return student[name];
        }
        return '-';
      };
      
      const namaSiswa = getData(['Nama Siswa', 'Nama', 'nama siswa', 'nama', 'NAMA SISWA', 'NAMA', Object.keys(student)[0]]);
      const kelas = getData(['Kelas', 'kelas', 'KELAS']);
      const jadwalUjian = getData(['Jadwal Ujian (Hari/Tanggal)', 'Jadwal Ujian', 'jadwal ujian', 'JADWAL UJIAN']);
      const waktuUjian = getData(['Waktu Ujian', 'waktu ujian', 'WAKTU UJIAN', 'Waktu']);
      const ruangKelas = getData(['Ruang Kelas', 'ruang kelas', 'RUANG KELAS', 'Ruang']);
      const guruPenguji = getData(['Nama Guru Penguji', 'Guru Penguji', 'guru penguji', 'GURU PENGUJI', 'Guru']);
      const nomorHP = getData(['Nomor HP', 'nomor hp', 'NOMOR HP', 'No HP', 'HP', 'Telepon']);

      return `
        <div class="card-content">
          <img src="https://iili.io/fFA80TF.md.png" class="print-watermark" onerror="this.style.display='none';">
          
          <div class="print-header">
            <h1>📚 JADWAL UJIAN SANTRI</h1>
            <p>SD INTERNATIONAL TAHFIZH QURAN</p>
          </div>

          <div class="student-identity">
            <div class="student-name">${namaSiswa}</div>
            <div class="student-class">Kelas: ${kelas}</div>
          </div>

          <div class="info-section">
            <div class="info-row">
              <span class="info-label">📅 Jadwal:</span>
              <span class="info-value">${jadwalUjian}</span>
            </div>

            <div class="info-row">
              <span class="info-label">⏰ Waktu:</span>
              <span class="info-value">${waktuUjian}</span>
            </div>

            <div class="info-row">
              <span class="info-label">🏫 Ruang:</span>
              <span class="info-value">${ruangKelas}</span>
            </div>

            <div class="info-row">
              <span class="info-label">👨‍🏫 Guru:</span>
              <span class="info-value">${guruPenguji}</span>
            </div>

            <div class="info-row">
              <span class="info-label">📞 HP:</span>
              <span class="info-value">${nomorHP}</span>
            </div>

            <div class="info-text">
              Ananda <strong>${namaSiswa}</strong> melaksanakan ujian pada <strong>${jadwalUjian}</strong> pukul <strong>${waktuUjian}</strong>.<br><br>
              
              <strong>🔔 Perhatian Penting untuk Wali Santri:</strong><br>
              • Mohon pastikan ananda hadir <strong>TEPAT WAKTU</strong> sesuai jadwal yang tertera<br>
              • Ujian dilaksanakan sesuai jadwal yang tertera<br>
              • Jika tidak ada jadwal ujian pada hari tertentu, santri <strong>belajar di rumah masing-masing</strong><br>
              • Apabila ananda berhalangan hadir, mohon segera menghubungi <strong>Wali Kelas</strong> untuk koordinasi lebih lanjut<br>
            </div>
          </div>
        </div>
      `;
    }

    function printSingleStudent(namaSiswa, jadwalUjian, waktuUjian, ruangKelas, guruPenguji, nomorHP) {
      let htmlContent = `
        <!DOCTYPE html>
        <html lang="id">
        <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Cetak Kartu Ujian - ${namaSiswa}</title>
          <style>
            * {
              margin: 0;
              padding: 0;
              box-sizing: border-box;
            }
            
            body {
              font-family: 'Arial', sans-serif;
              background: white;
            }

            .print-page {
              width: 210mm;
              height: 297mm;
              page-break-after: always;
              position: relative;
              padding: 0;
              margin: 0 auto;
            }

            .card-half {
              width: 210mm;
              height: 148.5mm;
              position: relative;
              padding: 15mm;
              box-sizing: border-box;
            }

            .card-top {
              border-bottom: 3px dashed #999;
            }

            .card-content {
              background: white;
              border: 3px solid #16a34a;
              border-radius: 12px;
              padding: 20px;
              height: 100%;
              position: relative;
              display: flex;
              flex-direction: column;
            }

            .print-watermark {
              position: absolute;
              top: 50%;
              left: 50%;
              transform: translate(-50%, -50%);
              opacity: 0.15;
              width: 220px;
              height: auto;
              pointer-events: none;
              z-index: 1;
            }

            .print-header {
              text-align: center;
              border-bottom: 3px solid #000;
              padding-bottom: 12px;
              margin-bottom: 15px;
              position: relative;
              z-index: 10;
            }

            .print-header h1 {
              font-size: 20px;
              font-weight: bold;
              color: #000;
              margin-bottom: 4px;
              letter-spacing: 0.5px;
            }

            .print-header p {
              font-size: 14px;
              color: #000;
              font-weight: 600;
            }

            .student-identity {
              margin-bottom: 12px;
              padding: 12px;
              background: white;
              border: 2px solid #000;
              border-radius: 8px;
              position: relative;
              z-index: 10;
            }

            .student-name {
              font-size: 20px;
              font-weight: bold;
              color: #000;
              margin-bottom: 4px;
            }

            .student-class {
              font-size: 14px;
              color: #000;
            }

            .info-section {
              position: relative;
              z-index: 10;
              flex-grow: 1;
            }

            .info-row {
              display: flex;
              margin-bottom: 8px;
              font-size: 13px;
            }

            .info-label {
              font-weight: bold;
              color: #000;
              width: 140px;
              flex-shrink: 0;
            }

            .info-value {
              color: #000;
              font-weight: 600;
              flex: 1;
            }

            .info-text {
              font-size: 12px;
              line-height: 1.6;
              color: #000;
              margin-top: 10px;
              padding: 10px;
              background: white;
              border: 2px solid #000;
              border-radius: 6px;
              position: relative;
              z-index: 10;
            }

            .info-text strong {
              color: #000;
              font-size: 13px;
            }

            .print-button-container {
              position: fixed;
              top: 20px;
              right: 20px;
              z-index: 1000;
              display: flex;
              gap: 10px;
            }

            .print-button {
              background: #16a34a;
              color: white;
              border: none;
              padding: 12px 24px;
              border-radius: 8px;
              font-size: 16px;
              font-weight: bold;
              cursor: pointer;
              box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
              transition: all 0.2s;
            }

            .print-button:hover {
              background: #15803d;
              transform: translateY(-2px);
            }

            .close-button {
              background: #dc2626;
            }

            .close-button:hover {
              background: #b91c1c;
            }

            @media print {
              .print-button-container {
                display: none !important;
              }

              body {
                margin: 0;
                padding: 0;
              }

              .print-page {
                page-break-after: always;
                margin: 0;
              }

              @page {
                size: A4 portrait;
                margin: 0;
              }
            }

            @media screen {
              body {
                background: #f5f5f5;
                padding: 20px;
              }
            }
          </style>
        </head>
        <body>
          <div class="print-button-container">
            <button class="print-button" onclick="window.print()">
              📄 Cetak Sekarang
            </button>
            <button class="print-button close-button" onclick="window.close()">
              ✕ Tutup
            </button>
          </div>

          <div class="print-page">
            <div class="card-half card-top">
              <div class="card-content">
                <img src="https://iili.io/fFA80TF.md.png" class="print-watermark" onerror="this.style.display='none';">
                
                <div class="print-header">
                  <h1>📚 JADWAL UJIAN SANTRI</h1>
                  <p>SD INTERNATIONAL TAHFIZH QURAN</p>
                </div>

                <div class="student-identity">
                  <div class="student-name">${namaSiswa}</div>
                  <div class="student-class">Kelas: -</div>
                </div>

                <div class="info-section">
                  <div class="info-row">
                    <span class="info-label">📅 Jadwal:</span>
                    <span class="info-value">${jadwalUjian}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">⏰ Waktu:</span>
                    <span class="info-value">${waktuUjian}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">🏫 Ruang:</span>
                    <span class="info-value">${ruangKelas}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">👨‍🏫 Guru:</span>
                    <span class="info-value">${guruPenguji}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">📞 HP:</span>
                    <span class="info-value">${nomorHP}</span>
                  </div>

                  <div class="info-text">
                    Ananda <strong>${namaSiswa}</strong> melaksanakan ujian pada <strong>${jadwalUjian}</strong> pukul <strong>${waktuUjian}</strong>.<br><br>
                    
                    <strong>🔔 Perhatian Penting untuk Wali Santri:</strong><br>
                    • Mohon pastikan ananda hadir <strong>TEPAT WAKTU</strong> sesuai jadwal yang tertera<br>
                    • Ujian dilaksanakan sesuai jadwal yang tertera<br>
                    • Jika tidak ada jadwal ujian pada hari tertentu, santri <strong>belajar di rumah masing-masing</strong><br>
                    • Apabila ananda berhalangan hadir, mohon segera menghubungi <strong>Wali Kelas</strong> untuk koordinasi lebih lanjut<br>
                  </div>
                </div>
              </div>
            </div>

            <div class="card-half">
              <div class="card-content">
                <img src="https://iili.io/fFA80TF.md.png" class="print-watermark" onerror="this.style.display='none';">
                
                <div class="print-header">
                  <h1>📚 JADWAL UJIAN SANTRI</h1>
                  <p>SD INTERNATIONAL TAHFIZH QURAN</p>
                </div>

                <div class="student-identity">
                  <div class="student-name">${namaSiswa}</div>
                  <div class="student-class">Kelas: -</div>
                </div>

                <div class="info-section">
                  <div class="info-row">
                    <span class="info-label">📅 Jadwal:</span>
                    <span class="info-value">${jadwalUjian}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">⏰ Waktu:</span>
                    <span class="info-value">${waktuUjian}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">🏫 Ruang:</span>
                    <span class="info-value">${ruangKelas}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">👨‍🏫 Guru:</span>
                    <span class="info-value">${guruPenguji}</span>
                  </div>

                  <div class="info-row">
                    <span class="info-label">📞 HP:</span>
                    <span class="info-value">${nomorHP}</span>
                  </div>

                  <div class="info-text">
                    Ananda <strong>${namaSiswa}</strong> melaksanakan ujian pada <strong>${jadwalUjian}</strong> pukul <strong>${waktuUjian}</strong>.<br><br>
                    
                    <strong>🔔 Perhatian Penting untuk Wali Santri:</strong><br>
                    • Mohon pastikan ananda hadir <strong>TEPAT WAKTU</strong> sesuai jadwal yang tertera<br>
                    • Ujian dilaksanakan sesuai jadwal yang tertera<br>
                    • Jika tidak ada jadwal ujian pada hari tertentu, santri <strong>belajar di rumah masing-masing</strong><br>
                    • Apabila ananda berhalangan hadir, mohon segera menghubungi <strong>Wali Kelas</strong> untuk koordinasi lebih lanjut<br>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </body>
        </html>
      `;

      const printWindow = window.open('', '_blank');
      printWindow.document.write(htmlContent);
      printWindow.document.close();
    }

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities: () => capabilities,
        mapToEditPanelValues: (config) => new Map([
          ['app_title', config.app_title || defaultConfig.app_title]
        ])
      });
    }

    initDataSdk();
    loadStudentData();
    startAutoRefresh();
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9c96cc6102873dc8',t:'MTc3MDM0MDU0Ny4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

<!doctype html>
<html lang="id">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RSVP Pernikahan - Nurul Afni &amp; Ardiansyah</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&amp;family=Poppins:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(180deg, #fdfbf7 0%, #f8f4ed 50%, #fdfbf7 100%);
      min-height: 100%;
      padding: 20px;
      color: #2c2c2c;
    }
    
    html, body {
      height: 100%;
    }
    
    .font-display {
      font-family: 'Playfair Display', serif;
    }
    
    .container {
      max-width: 600px;
      margin: 0 auto;
    }
    
    .header {
      text-align: center;
      margin-bottom: 40px;
      padding-top: 20px;
    }
    
    .header-icon {
      font-size: 48px;
      margin-bottom: 16px;
    }
    
    .header-title {
      font-size: 36px;
      font-weight: 700;
      color: #2c2c2c;
      margin-bottom: 8px;
    }
    
    .header-subtitle {
      font-size: 14px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: #c9a961;
      font-weight: 500;
    }
    
    .couples-name {
      font-size: 20px;
      color: #555;
      margin-top: 12px;
    }
    
    .ornament-line {
      height: 1px;
      background: linear-gradient(90deg, transparent, #c9a961, transparent);
      max-width: 128px;
      margin: 20px auto;
    }
    
    .form-card {
      background: #ffffff;
      border-radius: 24px;
      padding: 40px;
      box-shadow: 0 10px 40px rgba(201, 169, 97, 0.15);
      border: 2px solid rgba(201, 169, 97, 0.1);
      margin-bottom: 24px;
    }
    
    .form-group {
      margin-bottom: 24px;
    }
    
    .form-label {
      display: block;
      font-size: 14px;
      font-weight: 600;
      color: #c9a961;
      margin-bottom: 12px;
    }
    
    .form-input,
    .form-select,
    .form-textarea {
      width: 100%;
      padding: 16px 20px;
      border: 2px solid rgba(201, 169, 97, 0.3);
      border-radius: 12px;
      background: #fdfbf7;
      font-family: 'Poppins', sans-serif;
      font-weight: 500;
      font-size: 16px;
      color: #2c2c2c;
      transition: all 0.3s ease;
    }
    
    .form-input:focus,
    .form-select:focus,
    .form-textarea:focus {
      outline: none;
      border-color: #c9a961;
      transform: scale(1.01);
    }
    
    .form-textarea {
      resize: vertical;
      min-height: 120px;
    }
    
    .btn-submit {
      width: 100%;
      padding: 18px;
      background: linear-gradient(135deg, #c9a961, #d4b76a);
      color: #ffffff;
      border: none;
      border-radius: 12px;
      font-family: 'Poppins', sans-serif;
      font-weight: 700;
      font-size: 16px;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 6px 25px rgba(201, 169, 97, 0.4);
    }
    
    .btn-submit:hover:not(:disabled) {
      transform: scale(1.03);
    }
    
    .btn-submit:active:not(:disabled) {
      transform: scale(0.98);
    }
    
    .btn-submit:disabled {
      opacity: 0.6;
      cursor: not-allowed;
    }
    
    .success-message {
      background: #ffffff;
      border-radius: 24px;
      padding: 48px;
      text-align: center;
      box-shadow: 0 10px 40px rgba(201, 169, 97, 0.15);
      border: 2px solid rgba(201, 169, 97, 0.1);
      display: none;
    }
    
    .success-message.active {
      display: block;
    }
    
    .success-icon {
      width: 80px;
      height: 80px;
      background: linear-gradient(135deg, #c9a961, #d4b76a);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 24px;
      font-size: 40px;
    }
    
    .success-title {
      font-size: 28px;
      font-weight: 700;
      margin-bottom: 12px;
      color: #2c2c2c;
    }
    
    .success-text {
      font-size: 16px;
      color: #666;
      font-weight: 500;
    }
    
    .loading-spinner {
      display: none;
      text-align: center;
      padding: 20px;
    }
    
    .loading-spinner.active {
      display: block;
    }
    
    .spinner {
      border: 4px solid rgba(201, 169, 97, 0.2);
      border-top: 4px solid #c9a961;
      border-radius: 50%;
      width: 40px;
      height: 40px;
      animation: spin 1s linear infinite;
      margin: 0 auto 16px;
    }
    
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    
    .error-message {
      background: #fff5f5;
      border: 2px solid #fc8181;
      border-radius: 12px;
      padding: 16px;
      color: #c53030;
      font-weight: 500;
      margin-bottom: 24px;
      display: none;
    }
    
    .error-message.active {
      display: block;
    }
    
    .rsvp-list {
      margin-top: 40px;
    }
    
    .rsvp-list-title {
      font-size: 24px;
      font-weight: 700;
      text-align: center;
      margin-bottom: 24px;
      color: #2c2c2c;
    }
    
    .rsvp-item {
      background: #ffffff;
      border-radius: 16px;
      padding: 20px;
      margin-bottom: 12px;
      box-shadow: 0 4px 15px rgba(201, 169, 97, 0.1);
      border: 1px solid rgba(201, 169, 97, 0.1);
    }
    
    .rsvp-header {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 8px;
    }
    
    .rsvp-avatar {
      width: 40px;
      height: 40px;
      background: linear-gradient(135deg, #c9a961, #d4b76a);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      color: #ffffff;
      flex-shrink: 0;
    }
    
    .rsvp-name {
      font-weight: 700;
      color: #2c2c2c;
    }
    
    .attendance-badge {
      display: inline-block;
      font-size: 12px;
      padding: 4px 10px;
      border-radius: 50px;
      background: rgba(201, 169, 97, 0.15);
      color: #c9a961;
      margin-left: 8px;
    }
    
    .rsvp-message {
      color: #555;
      line-height: 1.6;
      margin-top: 8px;
    }
    
    .rsvp-meta {
      font-size: 12px;
      color: #888;
      margin-top: 8px;
    }
    
    @media (max-width: 640px) {
      .header-title {
        font-size: 28px;
      }
      
      .form-card {
        padding: 24px;
      }
      
      .success-message {
        padding: 32px 24px;
      }
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/element_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <div class="container"><!-- Header -->
   <div class="header">
    <div class="header-icon">
     💌
    </div>
    <p class="header-subtitle">KONFIRMASI KEHADIRAN</p>
    <h1 class="font-display header-title">RSVP</h1>
    <div class="ornament-line"></div>
    <p class="font-display couples-name">Nurul Afni &amp; Ardiansyah</p>
   </div><!-- Error Message -->
   <div id="error-message" class="error-message"></div><!-- Form -->
   <div id="rsvp-form-container" class="form-card">
    <form id="rsvp-form">
     <div class="form-group"><label for="name" class="form-label">Nama Lengkap *</label> <input type="text" id="name" name="name" class="form-input" placeholder="Masukkan nama Anda" required>
     </div>
     <div class="form-group"><label for="attendance" class="form-label">Kehadiran *</label> <select id="attendance" name="attendance" class="form-select" required> <option value="">Pilih kehadiran</option> <option value="hadir">✅ Ya, saya akan hadir</option> <option value="tidak">❌ Maaf, tidak bisa hadir</option> </select>
     </div>
     <div class="form-group"><label for="guests" class="form-label">Jumlah Tamu</label> <select id="guests" name="guests" class="form-select"> <option value="1">1 Orang</option> <option value="2">2 Orang</option> <option value="3">3 Orang</option> <option value="4">4 Orang</option> <option value="5">5 Orang</option> </select>
     </div>
     <div class="form-group"><label for="message" class="form-label">Ucapan &amp; Doa</label> <textarea id="message" name="message" class="form-textarea" placeholder="Tulis ucapan dan doa untuk kedua mempelai..."></textarea>
     </div><button type="submit" class="btn-submit" id="submit-btn"> 📨 Kirim Konfirmasi </button>
    </form>
    <div id="loading-spinner" class="loading-spinner">
     <div class="spinner"></div>
     <p style="color: #666; font-weight: 500;">Mengirim data...</p>
    </div>
   </div><!-- Success Message -->
   <div id="success-message" class="success-message">
    <div class="success-icon">
     ✅
    </div>
    <h3 class="font-display success-title">Terima Kasih!</h3>
    <p class="success-text">Konfirmasi kehadiran Anda telah berhasil tersimpan 🙏</p>
   </div><!-- RSVP List -->
   <div id="rsvp-list" class="rsvp-list">
    <h2 class="font-display rsvp-list-title">💬 Ucapan &amp; Doa</h2>
    <div id="rsvp-items"></div>
   </div>
  </div>
  <script>
    // Load existing RSVPs on page load
    window.addEventListener('load', function() {
      loadRSVPList();
    });
    
    // Form submission
    document.getElementById('rsvp-form').addEventListener('submit', function(e) {
      e.preventDefault();
      
      const formData = new FormData();
      formData.append('name', document.getElementById('name').value);
      formData.append('attendance', document.getElementById('attendance').value);
      formData.append('guests', document.getElementById('guests').value);
      formData.append('message', document.getElementById('message').value || 'Semoga menjadi keluarga yang sakinah, mawaddah, warahmah 🤲');
      
      // Show loading
      document.getElementById('submit-btn').disabled = true;
      document.getElementById('rsvp-form').style.display = 'none';
      document.getElementById('loading-spinner').classList.add('active');
      document.getElementById('error-message').classList.remove('active');
      
      // Submit to Google Apps Script
      fetch(window.location.href, {
        method: 'POST',
        body: formData
      })
      .then(response => response.json())
      .then(result => {
        document.getElementById('loading-spinner').classList.remove('active');
        
        if (result.success) {
          document.getElementById('rsvp-form-container').style.display = 'none';
          document.getElementById('success-message').classList.add('active');
          
          // Reload RSVP list
          setTimeout(function() {
            loadRSVPList();
          }, 1000);
        } else {
          showError(result.message);
          document.getElementById('rsvp-form').style.display = 'block';
          document.getElementById('submit-btn').disabled = false;
        }
      })
      .catch(error => {
        document.getElementById('loading-spinner').classList.remove('active');
        showError('Terjadi kesalahan: ' + error.message);
        document.getElementById('rsvp-form').style.display = 'block';
        document.getElementById('submit-btn').disabled = false;
      });
    });
    
    // Load RSVP list
    function loadRSVPList() {
      fetch(window.location.href + '?action=get')
        .then(response => response.json())
        .then(rsvpList => {
          const container = document.getElementById('rsvp-items');
          
          if (!rsvpList || rsvpList.length === 0) {
            container.innerHTML = '<p style="text-align: center; color: #888; font-weight: 500;">Belum ada ucapan 💭</p>';
            return;
          }
          
          container.innerHTML = rsvpList.map(rsvp => `
            <div class="rsvp-item">
              <div class="rsvp-header">
                <div class="rsvp-avatar">${rsvp.name.charAt(0).toUpperCase()}</div>
                <div style="flex: 1;">
                  <div class="rsvp-name">
                    ${rsvp.name}
                    <span class="attendance-badge">${rsvp.attendance}</span>
                  </div>
                  <div class="rsvp-meta">👥 ${rsvp.guests} orang</div>
                </div>
              </div>
              <p class="rsvp-message">${rsvp.message}</p>
            </div>
          `).join('');
        })
        .catch(error => {
          console.error('Error loading RSVP list:', error);
          document.getElementById('rsvp-items').innerHTML = '<p style="text-align: center; color: #888; font-weight: 500;">Belum ada ucapan 💭</p>';
        });
    }
    
    // Show error message
    function showError(message) {
      const errorDiv = document.getElementById('error-message');
      errorDiv.textContent = message;
      errorDiv.classList.add('active');
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9be94a6f24187e17',t:'MTc2ODUyMTE4OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

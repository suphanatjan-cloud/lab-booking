<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ระบบจองห้อง LAB</title>
<link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600;700&family=IBM+Plex+Sans+Thai:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --purple-50: #faf5ff;
    --purple-100: #f3e8ff;
    --purple-200: #e9d5ff;
    --purple-300: #d8b4fe;
    --purple-400: #c084fc;
    --purple-500: #a855f7;
    --purple-600: #9333ea;
    --purple-700: #7c3aed;
    --purple-800: #6d28d9;
    --white: #ffffff;
    --gray-50: #f9fafb;
    --gray-100: #f3f4f6;
    --gray-200: #e5e7eb;
    --gray-300: #d1d5db;
    --gray-400: #9ca3af;
    --gray-500: #6b7280;
    --gray-600: #4b5563;
    --gray-700: #374151;
    --green-100: #dcfce7;
    --green-600: #16a34a;
    --red-100: #fee2e2;
    --red-500: #ef4444;
    --red-600: #dc2626;
    --yellow-100: #fef9c3;
    --yellow-600: #ca8a04;
    --shadow-sm: 0 1px 3px rgba(168,85,247,0.08), 0 1px 2px rgba(168,85,247,0.04);
    --shadow-md: 0 4px 16px rgba(168,85,247,0.10), 0 2px 6px rgba(168,85,247,0.06);
    --shadow-lg: 0 10px 40px rgba(168,85,247,0.14), 0 4px 16px rgba(168,85,247,0.08);
    --radius: 14px;
    --radius-sm: 8px;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Sarabun', 'IBM Plex Sans Thai', sans-serif;
    background: var(--purple-50);
    min-height: 100vh;
    color: var(--gray-700);
  }

  /* ============ VIEWS ============ */
  .view { display: none; }
  .view.active { display: block; }

  /* ============ NAV ============ */
  .nav {
    background: var(--white);
    border-bottom: 1px solid var(--purple-100);
    padding: 0 32px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 64px;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: var(--shadow-sm);
  }
  .nav-brand {
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: 700;
    font-size: 18px;
    color: var(--purple-700);
  }
  .nav-brand .dot {
    width: 10px; height: 10px;
    background: var(--purple-400);
    border-radius: 50%;
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0%,100%{opacity:1;transform:scale(1)}
    50%{opacity:.6;transform:scale(1.3)}
  }
  .nav-actions { display: flex; gap: 10px; align-items: center; }
  .btn {
    padding: 8px 18px;
    border-radius: var(--radius-sm);
    font-size: 14px;
    font-family: inherit;
    font-weight: 500;
    cursor: pointer;
    border: none;
    transition: all .18s ease;
  }
  .btn-ghost {
    background: transparent;
    color: var(--gray-500);
    border: 1px solid var(--gray-200);
  }
  .btn-ghost:hover { background: var(--gray-50); color: var(--purple-600); border-color: var(--purple-200); }
  .btn-primary {
    background: var(--purple-600);
    color: white;
  }
  .btn-primary:hover { background: var(--purple-700); transform: translateY(-1px); box-shadow: 0 4px 12px rgba(147,51,234,0.3); }
  .btn-outline {
    background: white;
    color: var(--purple-600);
    border: 1.5px solid var(--purple-300);
  }
  .btn-outline:hover { background: var(--purple-50); border-color: var(--purple-400); }
  .btn-danger { background: var(--red-500); color: white; }
  .btn-danger:hover { background: var(--red-600); }
  .btn-success { background: var(--green-600); color: white; }
  .btn-success:hover { background: #15803d; }
  .btn-sm { padding: 5px 12px; font-size: 13px; }

  /* ============ BOOKING FORM VIEW ============ */
  .form-hero {
    background: linear-gradient(135deg, var(--purple-700) 0%, var(--purple-500) 100%);
    color: white;
    padding: 48px 32px 60px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .form-hero::before {
    content:'';
    position:absolute;
    width:300px;height:300px;
    background:rgba(255,255,255,0.05);
    border-radius:50%;
    top:-80px;right:-60px;
  }
  .form-hero::after {
    content:'';
    position:absolute;
    width:200px;height:200px;
    background:rgba(255,255,255,0.05);
    border-radius:50%;
    bottom:-40px;left:-40px;
  }
  .form-hero h1 { font-size: 28px; font-weight: 700; margin-bottom: 8px; }
  .form-hero p { font-size: 15px; opacity: .85; }

  .form-container {
    max-width: 680px;
    margin: -28px auto 48px;
    padding: 0 16px;
  }
  .form-card {
    background: white;
    border-radius: var(--radius);
    box-shadow: var(--shadow-lg);
    padding: 36px;
  }
  .form-section-title {
    font-size: 13px;
    font-weight: 600;
    color: var(--purple-500);
    text-transform: uppercase;
    letter-spacing: .08em;
    margin-bottom: 16px;
    margin-top: 28px;
    padding-bottom: 8px;
    border-bottom: 1.5px solid var(--purple-100);
  }
  .form-section-title:first-child { margin-top: 0; }
  .form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .form-group { display: flex; flex-direction: column; gap: 6px; }
  .form-group.full { grid-column: 1/-1; }
  label { font-size: 14px; font-weight: 500; color: var(--gray-600); }
  .required { color: var(--purple-500); margin-left: 2px; }
  input, select, textarea {
    padding: 10px 14px;
    border: 1.5px solid var(--gray-200);
    border-radius: var(--radius-sm);
    font-size: 15px;
    font-family: inherit;
    color: var(--gray-700);
    background: white;
    transition: border .15s, box-shadow .15s;
    outline: none;
    width: 100%;
  }
  input:focus, select:focus, textarea:focus {
    border-color: var(--purple-400);
    box-shadow: 0 0 0 3px rgba(168,85,247,0.12);
  }
  select { cursor: pointer; }
  .time-row { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .form-submit { margin-top: 28px; }
  .form-submit .btn { width: 100%; padding: 13px; font-size: 16px; border-radius: var(--radius-sm); }

  .toast {
    position: fixed;
    bottom: 28px;
    left: 50%;
    transform: translateX(-50%) translateY(80px);
    background: var(--purple-700);
    color: white;
    padding: 14px 24px;
    border-radius: 50px;
    font-size: 14px;
    font-weight: 500;
    box-shadow: var(--shadow-lg);
    z-index: 999;
    transition: transform .35s cubic-bezier(.34,1.56,.64,1);
    white-space: nowrap;
  }
  .toast.show { transform: translateX(-50%) translateY(0); }
  .toast.error { background: var(--red-500); }
  .toast.success { background: var(--green-600); }

  /* ============ ADMIN VIEW ============ */
  .admin-layout { display: flex; min-height: calc(100vh - 64px); }

  .sidebar {
    width: 220px;
    background: white;
    border-right: 1px solid var(--purple-100);
    padding: 24px 0;
    flex-shrink: 0;
    position: sticky;
    top: 64px;
    height: calc(100vh - 64px);
    overflow-y: auto;
  }
  .sidebar-label {
    font-size: 11px;
    font-weight: 600;
    color: var(--gray-400);
    text-transform: uppercase;
    letter-spacing: .1em;
    padding: 0 20px;
    margin-bottom: 8px;
  }
  .sidebar-item {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 10px 20px;
    font-size: 14px;
    font-weight: 500;
    color: var(--gray-500);
    cursor: pointer;
    transition: all .15s;
    border-left: 3px solid transparent;
  }
  .sidebar-item:hover { background: var(--purple-50); color: var(--purple-600); }
  .sidebar-item.active { background: var(--purple-50); color: var(--purple-700); border-left-color: var(--purple-600); font-weight: 600; }
  .sidebar-icon { font-size: 18px; }

  .admin-content { flex: 1; padding: 32px; overflow-x: auto; }
  .admin-tab { display: none; }
  .admin-tab.active { display: block; }

  .page-header { margin-bottom: 28px; }
  .page-header h2 { font-size: 22px; font-weight: 700; color: var(--gray-700); }
  .page-header p { font-size: 14px; color: var(--gray-400); margin-top: 4px; }

  /* Stats */
  .stats-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 16px; margin-bottom: 32px; }
  .stat-card {
    background: white;
    border-radius: var(--radius);
    padding: 22px 24px;
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--purple-100);
    position: relative;
    overflow: hidden;
  }
  .stat-card::before {
    content:'';
    position:absolute;
    top:-20px;right:-20px;
    width:80px;height:80px;
    border-radius:50%;
    opacity:.08;
    background: var(--purple-400);
  }
  .stat-label { font-size: 13px; color: var(--gray-400); font-weight: 500; margin-bottom: 8px; }
  .stat-value { font-size: 32px; font-weight: 700; color: var(--purple-700); line-height: 1; }
  .stat-sub { font-size: 12px; color: var(--gray-400); margin-top: 6px; }

  /* Filter bar */
  .filter-bar {
    display: flex;
    gap: 10px;
    align-items: center;
    margin-bottom: 18px;
    flex-wrap: wrap;
  }
  .filter-bar input, .filter-bar select {
    width: auto;
    padding: 8px 12px;
    font-size: 13px;
  }
  .filter-bar input { min-width: 200px; }

  /* Table */
  .table-wrap {
    background: white;
    border-radius: var(--radius);
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--purple-100);
    overflow: hidden;
  }
  table { width: 100%; border-collapse: collapse; font-size: 14px; }
  thead tr { background: var(--purple-50); border-bottom: 1.5px solid var(--purple-100); }
  th { padding: 12px 16px; text-align: left; font-size: 12px; font-weight: 600; color: var(--purple-500); text-transform: uppercase; letter-spacing: .06em; white-space: nowrap; }
  td { padding: 13px 16px; border-bottom: 1px solid var(--gray-100); vertical-align: middle; }
  tr:last-child td { border-bottom: none; }
  tr:hover td { background: var(--purple-50); }

  .badge {
    display: inline-block;
    padding: 3px 10px;
    border-radius: 50px;
    font-size: 12px;
    font-weight: 600;
  }
  .badge-pending { background: var(--yellow-100); color: var(--yellow-600); }
  .badge-approved { background: var(--green-100); color: var(--green-600); }
  .badge-rejected { background: var(--red-100); color: var(--red-600); }

  .action-btns { display: flex; gap: 6px; }

  .empty-state {
    text-align: center;
    padding: 64px 32px;
    color: var(--gray-400);
  }
  .empty-state .icon { font-size: 48px; margin-bottom: 12px; }
  .empty-state p { font-size: 15px; }

  /* ============ MODAL ============ */
  .modal-overlay {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,.35);
    z-index: 500;
    align-items: center;
    justify-content: center;
    backdrop-filter: blur(2px);
  }
  .modal-overlay.open { display: flex; }
  .modal {
    background: white;
    border-radius: var(--radius);
    box-shadow: var(--shadow-lg);
    width: 90%;
    max-width: 480px;
    padding: 32px;
    animation: modalIn .25s ease;
  }
  @keyframes modalIn {
    from{opacity:0;transform:translateY(20px) scale(.97)}
    to{opacity:1;transform:translateY(0) scale(1)}
  }
  .modal h3 { font-size: 18px; font-weight: 700; color: var(--gray-700); margin-bottom: 6px; }
  .modal p { font-size: 14px; color: var(--gray-500); margin-bottom: 20px; }
  .modal .form-group { margin-bottom: 16px; }
  .modal-actions { display: flex; gap: 10px; justify-content: flex-end; margin-top: 24px; }

  .detail-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin: 16px 0; }
  .detail-item label { font-size: 12px; color: var(--gray-400); font-weight: 600; text-transform: uppercase; letter-spacing: .06em; display: block; margin-bottom: 3px; }
  .detail-item span { font-size: 14px; color: var(--gray-700); font-weight: 500; }

  /* ============ CHART ============ */
  .charts-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 24px; }
  .chart-card {
    background: white;
    border-radius: var(--radius);
    padding: 24px;
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--purple-100);
  }
  .chart-card h4 { font-size: 14px; font-weight: 600; color: var(--gray-600); margin-bottom: 20px; }
  .bar-chart { display: flex; flex-direction: column; gap: 12px; }
  .bar-row { display: flex; align-items: center; gap: 12px; font-size: 13px; }
  .bar-label { width: 130px; color: var(--gray-500); flex-shrink: 0; }
  .bar-track { flex: 1; background: var(--purple-100); border-radius: 50px; height: 10px; overflow: hidden; }
  .bar-fill { height: 100%; background: linear-gradient(90deg, var(--purple-400), var(--purple-600)); border-radius: 50px; transition: width .6s ease; }
  .bar-count { width: 28px; text-align: right; font-weight: 600; color: var(--purple-600); }

  /* ============ LOGIN MODAL ============ */
  .login-icon { font-size: 40px; text-align: center; margin-bottom: 12px; }
  #adminPwInput { letter-spacing: .2em; }

  @keyframes spin { to { transform: rotate(360deg); } }
    .stats-grid { grid-template-columns: 1fr 1fr; }
    .charts-grid { grid-template-columns: 1fr; }
    .form-grid { grid-template-columns: 1fr; }
    .form-group.full { grid-column: auto; }
  }
  @media(max-width: 640px) {
    .sidebar { display: none; }
    .admin-content { padding: 16px; }
    .stats-grid { grid-template-columns: 1fr 1fr; gap: 10px; }
    .stat-value { font-size: 24px; }
    .nav { padding: 0 16px; }
    .form-card { padding: 20px; }
    .time-row { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav class="nav">
  <div class="nav-brand">
    <div class="dot"></div>
    <span>LAB Booking System</span>
  </div>
  <div class="nav-actions">
    <button class="btn btn-ghost" onclick="showView('booking')" id="navBooking">📋 จองห้อง</button>
    <button class="btn btn-ghost" onclick="showView('status')" id="navStatus">🔍 ตรวจสอบสถานะ</button>
    <button class="btn btn-outline" onclick="requireAdminLogin()" id="navAdmin">🔐 ผู้ดูแลระบบ</button>
  </div>
</nav>

<!-- ========== STATUS VIEW ========== -->
<div class="view" id="viewStatus">
  <div class="form-hero">
    <h1>🔍 ตรวจสอบสถานะการจองห้อง</h1>
    <p>กรอกรหัสนักศึกษาเพื่อดูสถานะคำขอของคุณ</p>
  </div>
  <div class="form-container">
    <div class="form-card">
      <div class="form-section-title">ค้นหาคำขอของคุณ</div>
      <div class="form-grid">
        <div class="form-group full">
          <label>รหัสนักศึกษา <span class="required">*</span></label>
          <input type="text" id="statusSearchId" placeholder="กรอกรหัสนักศึกษา 13 หลัก" maxlength="13" oninput="this.value=this.value.replace(/\D/g,'')">
        </div>
      </div>
      <div class="form-submit">
        <button class="btn btn-primary" onclick="searchStatus()">🔍 ตรวจสอบสถานะ</button>
      </div>
      <div id="statusResult" style="margin-top:24px;"></div>
    </div>
  </div>
</div>
<div class="view active" id="viewBooking">
  <div class="form-hero">
    <h1>🔬 ระบบจองห้องปฏิบัติการ</h1>
    <p>กรุณากรอกข้อมูลให้ครบถ้วนเพื่อส่งคำขอใช้ห้อง LAB</p>
  </div>
  <div class="form-container">
    <div class="form-card">
      <div class="form-section-title">ข้อมูลผู้ขอใช้งาน</div>
      <div class="form-grid">
        <div class="form-group">
          <label>รหัสนักศึกษา <span class="required">*</span></label>
          <input type="text" id="studentId" placeholder="เช่น 6601234567890" maxlength="13">
        </div>
        <div class="form-group">
          <label>สาขา <span class="required">*</span></label>
          <select id="branch">
            <option value="">-- เลือกสาขา --</option>
            <option value="วิทยาการแปรรูปและการประกอบอาหาร">วิทยาการแปรรูปและการประกอบอาหาร</option>
            <option value="เทคโนโลยีและการจัดการสิ่งแวดล้อม">เทคโนโลยีและการจัดการสิ่งแวดล้อม</option>
            <option value="เทคโนโลยีสุขภาพและความงาม">เทคโนโลยีสุขภาพและความงาม</option>
            <option value="เทคโนโลยีการกีฬาและการออกกำลังกาย">เทคโนโลยีการกีฬาและการออกกำลังกาย</option>
            <option value="วิทยาการคอมพิวเตอร์และปัญญาประดิษฐ์ประยุกต์">วิทยาการคอมพิวเตอร์และปัญญาประดิษฐ์ประยุกต์</option>
            <option value="นวัตกรรมโภชนาการเพื่อการชะลอวัย">นวัตกรรมโภชนาการเพื่อการชะลอวัย</option>
          </select>
        </div>
        <div class="form-group">
          <label>เบอร์โทรติดต่อ <span class="required">*</span></label>
          <input type="tel" id="phone" placeholder="0XX-XXX-XXXX" maxlength="10">
        </div>
        <div class="form-group">
          <label>อาจารย์ที่ปรึกษา <span class="required">*</span></label>
          <input type="text" id="advisor" placeholder="ชื่อ-นามสกุล อาจารย์">
        </div>
      </div>

      <div class="form-section-title">ข้อมูลการจอง</div>
      <div class="form-grid">
        <div class="form-group">
          <label>ห้องที่ขอใช้งาน <span class="required">*</span></label>
          <select id="room">
            <option value="">-- เลือกห้อง --</option>
            <optgroup label="ชั้น 2">
              <option value="ห้องอุตสาหกรรมแปรรูปเนื้อสัตว์">ห้องอุตสาหกรรมแปรรูปเนื้อสัตว์</option>
              <option value="ห้องจำลองการให้บริการด้านความงาม (เสริมสวย)">ห้องจำลองการให้บริการด้านความงาม (เสริมสวย)</option>
            </optgroup>
            <optgroup label="ชั้น 3">
              <option value="โรงงานผลิตเครื่องสำอาง">โรงงานผลิตเครื่องสำอาง</option>
            </optgroup>
            <optgroup label="ชั้น 5">
              <option>26506</option><option>26507</option><option>26508</option>
            </optgroup>
            <optgroup label="ชั้น 6">
              <option>26606</option><option>26607</option><option>26608</option>
            </optgroup>
            <optgroup label="ชั้น 7">
              <option>26706</option><option>26707</option><option>26708</option>
            </optgroup>
            <optgroup label="ชั้น 8">
              <option>26806</option><option>26807</option><option>26808</option>
            </optgroup>
          </select>
        </div>
        <div class="form-group">
          <label>วันที่ขอใช้ <span class="required">*</span></label>
          <input type="date" id="bookDate">
        </div>
        <div class="form-group">
          <label>เวลาเริ่มต้น <span class="required">*</span></label>
          <select id="timeStart">
            <option value="">-- เลือกเวลา --</option>
            <option value="08:30">08:30</option>
            <option value="09:00">09:00</option>
            <option value="09:30">09:30</option>
            <option value="10:00">10:00</option>
            <option value="10:30">10:30</option>
            <option value="11:00">11:00</option>
            <option value="11:30">11:30</option>
            <option value="12:00">12:00</option>
            <option value="12:30">12:30</option>
            <option value="13:00">13:00</option>
            <option value="13:30">13:30</option>
            <option value="14:00">14:00</option>
            <option value="14:30">14:30</option>
            <option value="15:00">15:00</option>
            <option value="15:30">15:30</option>
            <option value="16:00">16:00</option>
          </select>
        </div>
        <div class="form-group">
          <label>เวลาสิ้นสุด <span class="required">*</span></label>
          <select id="timeEnd">
            <option value="">-- เลือกเวลา --</option>
            <option value="09:00">09:00</option>
            <option value="09:30">09:30</option>
            <option value="10:00">10:00</option>
            <option value="10:30">10:30</option>
            <option value="11:00">11:00</option>
            <option value="11:30">11:30</option>
            <option value="12:00">12:00</option>
            <option value="12:30">12:30</option>
            <option value="13:00">13:00</option>
            <option value="13:30">13:30</option>
            <option value="14:00">14:00</option>
            <option value="14:30">14:30</option>
            <option value="15:00">15:00</option>
            <option value="15:30">15:30</option>
            <option value="16:00">16:00</option>
            <option value="16:30">16:30</option>
          </select>
        </div>
        <div class="form-group full">
          <label>วัตถุประสงค์การใช้งาน</label>
          <input type="text" id="purpose" placeholder="เช่น ทดลองวิทยาศาสตร์อาหาร / โปรเจกต์สิ้นปี">
        </div>
      </div>

      <div class="form-submit">
        <button class="btn btn-primary" onclick="submitBooking()">📨 ส่งคำขอจองห้อง</button>
      </div>
    </div>
  </div>
</div>

<!-- ========== ADMIN VIEW ========== -->
<div class="view" id="viewAdmin">
  <div class="admin-layout">
    <div class="sidebar">
      <div class="sidebar-label" style="margin-bottom:16px">เมนู</div>
      <div class="sidebar-item active" onclick="switchAdminTab('dashboard',this)">
        <span class="sidebar-icon">📊</span> ภาพรวม
      </div>
      <div class="sidebar-item" onclick="switchAdminTab('requests',this)">
        <span class="sidebar-icon">📋</span> คำขอจองทั้งหมด
      </div>
      <div class="sidebar-item" onclick="switchAdminTab('approved',this)">
        <span class="sidebar-icon">✅</span> อนุมัติแล้ว
      </div>
      <div class="sidebar-item" onclick="switchAdminTab('pending',this)">
        <span class="sidebar-icon">⏳</span> รอการอนุมัติ
      </div>
      <div class="sidebar-item" onclick="switchAdminTab('rejected',this)">
        <span class="sidebar-icon">❌</span> ไม่อนุมัติ
      </div>
      <div style="padding:12px 20px;border-top:1px solid var(--purple-100);margin-top:32px;display:flex;flex-direction:column;gap:8px;">
        <button class="btn btn-outline btn-sm" style="width:100%" onclick="manualRefresh(this)">🔄 รีเฟรชข้อมูล</button>
        <button class="btn btn-ghost btn-sm" style="width:100%" onclick="adminLogout()">🚪 ออกจากระบบ</button>
      </div>
    </div>

    <div class="admin-content">
      <!-- Loading overlay -->
      <div id="loadingOverlay" style="display:none;position:fixed;inset:0;background:rgba(255,255,255,0.75);z-index:200;align-items:center;justify-content:center;flex-direction:column;gap:14px;">
        <div style="width:44px;height:44px;border:4px solid var(--purple-200);border-top-color:var(--purple-600);border-radius:50%;animation:spin .8s linear infinite;"></div>
        <p style="color:var(--purple-600);font-weight:600;font-size:15px;">กำลังโหลดข้อมูล...</p>
      </div>
      <!-- Error banner -->
      <div id="errorBanner" style="display:none;background:var(--red-100);border:1.5px solid var(--red-500);color:var(--red-600);border-radius:var(--radius-sm);padding:12px 18px;margin-bottom:20px;font-size:14px;font-weight:500;">
        ⚠️ ไม่สามารถโหลดข้อมูลจาก Google Sheets ได้ — กรุณาตรวจสอบว่าคุณ Login บัญชี <strong>@rmutr.ac.th</strong> ใน Browser แล้ว จากนั้นกด 🔄 รีเฟรชข้อมูล
      </div>
      <!-- DASHBOARD TAB -->
      <div class="admin-tab active" id="tabDashboard">
        <div class="page-header">
          <h2>ภาพรวมระบบจองห้อง LAB</h2>
          <p id="dashboardDate"></p>
        </div>
        <div class="stats-grid">
          <div class="stat-card">
            <div class="stat-label">คำขอทั้งหมด</div>
            <div class="stat-value" id="statTotal">0</div>
            <div class="stat-sub">รายการ</div>
          </div>
          <div class="stat-card">
            <div class="stat-label">รอการอนุมัติ</div>
            <div class="stat-value" id="statPending" style="color:var(--yellow-600)">0</div>
            <div class="stat-sub">รายการ</div>
          </div>
          <div class="stat-card">
            <div class="stat-label">อนุมัติแล้ว</div>
            <div class="stat-value" id="statApproved" style="color:var(--green-600)">0</div>
            <div class="stat-sub">รายการ</div>
          </div>
          <div class="stat-card">
            <div class="stat-label">ไม่อนุมัติ</div>
            <div class="stat-value" id="statRejected" style="color:var(--red-500)">0</div>
            <div class="stat-sub">รายการ</div>
          </div>
        </div>
        <div class="charts-grid">
          <div class="chart-card">
            <h4>📊 การจองตามสาขา</h4>
            <div class="bar-chart" id="chartBranch"></div>
          </div>
          <div class="chart-card">
            <h4>🚪 ห้องที่ถูกจองมากที่สุด</h4>
            <div class="bar-chart" id="chartRoom"></div>
          </div>
        </div>
      </div>

      <!-- REQUESTS TAB (all / approved / pending / rejected share same template) -->
      <div class="admin-tab" id="tabRequests">
        <div class="page-header"><h2>คำขอจองทั้งหมด</h2><p>รายการคำขอทั้งหมดในระบบ</p></div>
        <div class="filter-bar">
          <input type="text" id="searchAll" placeholder="🔍 ค้นหา รหัส / ชื่อ / ห้อง" oninput="renderTable('all')">
          <select id="filterRoomAll" onchange="renderTable('all')"><option value="">ทุกห้อง</option></select>
          <select id="filterBranchAll" onchange="renderTable('all')"><option value="">ทุกสาขา</option></select>
        </div>
        <div class="table-wrap" id="tableAll"></div>
      </div>

      <div class="admin-tab" id="tabApproved">
        <div class="page-header"><h2>รายการที่อนุมัติแล้ว</h2><p>คำขอที่ได้รับการอนุมัติ</p></div>
        <div class="filter-bar">
          <input type="text" id="searchApproved" placeholder="🔍 ค้นหา" oninput="renderTable('approved')">
        </div>
        <div class="table-wrap" id="tableApproved"></div>
      </div>

      <div class="admin-tab" id="tabPending">
        <div class="page-header"><h2>รายการรอการอนุมัติ</h2><p>คำขอที่ยังไม่ได้รับการพิจารณา</p></div>
        <div class="filter-bar">
          <input type="text" id="searchPending" placeholder="🔍 ค้นหา" oninput="renderTable('pending')">
        </div>
        <div class="table-wrap" id="tablePending"></div>
      </div>

      <div class="admin-tab" id="tabRejected">
        <div class="page-header"><h2>รายการที่ไม่อนุมัติ</h2><p>คำขอที่ถูกปฏิเสธ</p></div>
        <div class="filter-bar">
          <input type="text" id="searchRejected" placeholder="🔍 ค้นหา" oninput="renderTable('rejected')">
        </div>
        <div class="table-wrap" id="tableRejected"></div>
      </div>
    </div>
  </div>
</div>

<!-- ========== TOAST ========== -->
<div class="toast" id="toast"></div>

<!-- ========== MODALS ========== -->

<!-- Admin Login Modal -->
<div class="modal-overlay" id="loginModal">
  <div class="modal">
    <div class="login-icon">🔐</div>
    <h3 style="text-align:center">เข้าสู่ระบบผู้ดูแล</h3>
    <p style="text-align:center">กรุณาใส่รหัสผ่านเพื่อเข้าถึงระบบหลังบ้าน</p>
    <div class="form-group">
      <label>รหัสผ่าน</label>
      <input type="password" id="adminPwInput" placeholder="••••••" onkeydown="if(event.key==='Enter')doAdminLogin()">
    </div>
    <p id="loginError" style="color:var(--red-500);font-size:13px;display:none;margin-top:-8px">รหัสผ่านไม่ถูกต้อง</p>
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal('loginModal')">ยกเลิก</button>
      <button class="btn btn-primary" onclick="doAdminLogin()">เข้าสู่ระบบ</button>
    </div>
  </div>
</div>

<!-- Approve Modal -->
<div class="modal-overlay" id="approveModal">
  <div class="modal">
    <div style="font-size:36px;text-align:center;margin-bottom:12px">🔑</div>
    <h3 style="text-align:center">ยืนยันการอนุมัติ</h3>
    <p style="text-align:center">กรุณาใส่รหัสผ่านเพื่อยืนยันการอนุมัติคำขอนี้</p>
    <div class="form-group">
      <label>รหัสผ่านผู้ดูแลระบบ</label>
      <input type="password" id="approvePwInput" placeholder="••••••" onkeydown="if(event.key==='Enter')confirmApprove()">
    </div>
    <p id="approveError" style="color:var(--red-500);font-size:13px;display:none;margin-top:-8px">รหัสผ่านไม่ถูกต้อง</p>
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal('approveModal')">ยกเลิก</button>
      <button class="btn btn-success" onclick="confirmApprove()">✅ อนุมัติ</button>
    </div>
  </div>
</div>

<!-- Reject Modal -->
<div class="modal-overlay" id="rejectModal">
  <div class="modal">
    <div style="font-size:36px;text-align:center;margin-bottom:12px">🔑</div>
    <h3 style="text-align:center">ยืนยันการไม่อนุมัติ</h3>
    <p style="text-align:center">กรุณาใส่รหัสผ่านเพื่อยืนยันการปฏิเสธคำขอนี้</p>
    <div class="form-group">
      <label>รหัสผ่านผู้ดูแลระบบ</label>
      <input type="password" id="rejectPwInput" placeholder="••••••" onkeydown="if(event.key==='Enter')confirmReject()">
    </div>
    <p id="rejectError" style="color:var(--red-500);font-size:13px;display:none;margin-top:-8px">รหัสผ่านไม่ถูกต้อง</p>
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal('rejectModal')">ยกเลิก</button>
      <button class="btn btn-danger" onclick="confirmReject()">❌ ไม่อนุมัติ</button>
    </div>
  </div>
</div>

<!-- Detail Modal -->
<div class="modal-overlay" id="detailModal">
  <div class="modal" style="max-width:560px">
    <h3>📋 รายละเอียดคำขอ</h3>
    <div id="detailContent"></div>
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal('detailModal')">ปิด</button>
    </div>
  </div>
</div>

<script>
// ============ CONFIG ============
const API_URL = 'https://script.google.com/macros/s/AKfycbx8z_8Ty5ct97mcujx-MtyJOP_88b4ozb6w6vslx7jFWwKKPo3onZyp3I6gv0BcBRkw/exec';
const ADMIN_PASS = 'admin';
let isAdminLoggedIn = false;
let pendingActionId = null;
let pendingAction = null;
let cachedBookings = [];

// ============ DATA (Google Sheets) ============
function getBookings() {
  return new Promise((resolve) => {
    const cbName = 'cb_' + Date.now();
    const script = document.createElement('script');
    let done = false;

    const timeout = setTimeout(() => {
      if (done) return;
      done = true;
      delete window[cbName];
      try { document.body.removeChild(script); } catch(e){}
      resolve(false); // timeout = fail
    }, 8000);

    window[cbName] = (data) => {
      if (done) return;
      done = true;
      clearTimeout(timeout);
      delete window[cbName];
      try { document.body.removeChild(script); } catch(e){}
      cachedBookings = Array.isArray(data) ? data : [];
      resolve(true);
    };
    script.onerror = () => {
      if (done) return;
      done = true;
      clearTimeout(timeout);
      delete window[cbName];
      try { document.body.removeChild(script); } catch(e){}
      resolve(false);
    };
    script.src = API_URL + '?callback=' + cbName + '&t=' + Date.now();
    document.body.appendChild(script);
  });
}

function postToSheet(payload) {
  return new Promise((resolve) => {
    // สร้าง hidden iframe รับ response
    const iframeName = 'frm_' + Date.now();
    const iframe = document.createElement('iframe');
    iframe.name = iframeName;
    iframe.style.display = 'none';
    document.body.appendChild(iframe);

    // สร้าง form แล้ว submit ไป Apps Script
    const form = document.createElement('form');
    form.method = 'POST';
    form.action = API_URL;
    form.target = iframeName;
    form.style.display = 'none';

    const input = document.createElement('input');
    input.type = 'hidden';
    input.name = 'data';
    input.value = JSON.stringify(payload);
    form.appendChild(input);

    document.body.appendChild(form);

    iframe.onload = () => {
      setTimeout(() => {
        try { document.body.removeChild(iframe); } catch(e){}
        try { document.body.removeChild(form); } catch(e){}
      }, 500);
      resolve(true);
    };

    setTimeout(() => {
      try { document.body.removeChild(iframe); } catch(e){}
      try { document.body.removeChild(form); } catch(e){}
      resolve(true);
    }, 6000);

    form.submit();
  });
}

async function addBooking(booking) {
  return postToSheet({ action: 'add', ...booking });
}

async function updateStatusRemote(id, status, password) {
  await postToSheet({ action: 'updateStatus', id, status, password });
  return { success: true };
}

// ============ VIEWS ============
function showView(name) {
  document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
  document.getElementById('view' + name.charAt(0).toUpperCase() + name.slice(1)).classList.add('active');
}

function requireAdminLogin() {
  if (isAdminLoggedIn) { enterAdmin(); return; }
  document.getElementById('adminPwInput').value = '';
  document.getElementById('loginError').style.display = 'none';
  openModal('loginModal');
  setTimeout(() => document.getElementById('adminPwInput').focus(), 200);
}
function doAdminLogin() {
  const pw = document.getElementById('adminPwInput').value;
  if (pw === ADMIN_PASS) {
    isAdminLoggedIn = true;
    closeModal('loginModal');
    enterAdmin();
  } else {
    document.getElementById('loginError').style.display = 'block';
    document.getElementById('adminPwInput').value = '';
  }
}
function setLoading(on) {
  const el = document.getElementById('loadingOverlay');
  el.style.display = on ? 'flex' : 'none';
}
function setError(on) {
  document.getElementById('errorBanner').style.display = on ? 'block' : 'none';
}

async function enterAdmin() {
  showView('admin');
  setLoading(true);
  setError(false);
  const ok = await getBookings();
  setLoading(false);
  if (!ok) { setError(true); }
  loadDashboard();
  populateFilters();
  renderTable('all');
  renderTable('approved');
  renderTable('pending');
  renderTable('rejected');
}

async function manualRefresh(btn) {
  btn.disabled = true;
  btn.textContent = '⏳ กำลังโหลด...';
  setError(false);
  setLoading(true);
  const ok = await getBookings();
  setLoading(false);
  btn.disabled = false;
  btn.textContent = '🔄 รีเฟรชข้อมูล';
  if (!ok) { setError(true); showToast('❌ โหลดข้อมูลไม่สำเร็จ', 'error'); }
  else { showToast('✅ โหลดข้อมูลสำเร็จ', 'success'); refreshAdminTabs(); }
}
function adminLogout() {
  isAdminLoggedIn = false;
  showView('booking');
}

// ============ ADMIN TABS ============
function switchAdminTab(tab, el) {
  document.querySelectorAll('.admin-tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.sidebar-item').forEach(s => s.classList.remove('active'));
  document.getElementById('tab' + tab.charAt(0).toUpperCase() + tab.slice(1)).classList.add('active');
  el.classList.add('active');
  if (tab === 'dashboard') loadDashboard();
  else renderTable(tab === 'requests' ? 'all' : tab);
}

// ============ DASHBOARD ============
function loadDashboard() {
  const data = cachedBookings;
  document.getElementById('statTotal').textContent = data.length;
  document.getElementById('statPending').textContent = data.filter(b => b.status === 'pending').length;
  document.getElementById('statApproved').textContent = data.filter(b => b.status === 'approved').length;
  document.getElementById('statRejected').textContent = data.filter(b => b.status === 'rejected').length;
  const now = new Date();
  document.getElementById('dashboardDate').textContent = 'ข้อมูล ณ วันที่ ' + now.toLocaleDateString('th-TH', {year:'numeric',month:'long',day:'numeric'});
  renderCharts(data);
}

function renderCharts(data) {
  const branches = ['วิทยาการแปรรูปและการประกอบอาหาร','เทคโนโลยีและการจัดการสิ่งแวดล้อม','เทคโนโลยีสุขภาพและความงาม','เทคโนโลยีการกีฬาและการออกกำลังกาย','วิทยาการคอมพิวเตอร์และปัญญาประดิษฐ์ประยุกต์','นวัตกรรมโภชนาการเพื่อการชะลอวัย'];
  const rooms = [
    'ห้องอุตสาหกรรมแปรรูปเนื้อสัตว์',
    'ห้องจำลองการให้บริการด้านความงาม (เสริมสวย)',
    'โรงงานผลิตเครื่องสำอาง',
    '26506','26507','26508','26606','26607','26608','26706','26707','26708','26806','26807','26808'
  ];
  const branchCount = {};
  const roomCount = {};
  branches.forEach(b => branchCount[b] = 0);
  rooms.forEach(r => roomCount[r] = 0);
  data.forEach(b => {
    if (branchCount[b.branch] !== undefined) branchCount[b.branch]++;
    if (roomCount[b.room] !== undefined) roomCount[b.room]++;
  });
  const maxB = Math.max(...Object.values(branchCount), 1);
  const maxR = Math.max(...Object.values(roomCount), 1);

  document.getElementById('chartBranch').innerHTML = branches.map(b =>
    `<div class="bar-row">
      <div class="bar-label" style="font-size:11px">${b}</div>
      <div class="bar-track"><div class="bar-fill" style="width:${(branchCount[b]/maxB*100)}%"></div></div>
      <div class="bar-count">${branchCount[b]}</div>
    </div>`
  ).join('');

  const topRooms = rooms.sort((a,b) => roomCount[b]-roomCount[a]).slice(0,6);
  document.getElementById('chartRoom').innerHTML = topRooms.map(r =>
    `<div class="bar-row">
      <div class="bar-label">ห้อง ${r}</div>
      <div class="bar-track"><div class="bar-fill" style="width:${(roomCount[r]/maxR*100)}%"></div></div>
      <div class="bar-count">${roomCount[r]}</div>
    </div>`
  ).join('');
}

// ============ POPULATE FILTERS ============
function populateFilters() {
  const rooms = [
    'ห้องอุตสาหกรรมแปรรูปเนื้อสัตว์',
    'ห้องจำลองการให้บริการด้านความงาม (เสริมสวย)',
    'โรงงานผลิตเครื่องสำอาง',
    '26506','26507','26508','26606','26607','26608','26706','26707','26708','26806','26807','26808'
  ];
  const branches = ['วิทยาการแปรรูปและการประกอบอาหาร','เทคโนโลยีและการจัดการสิ่งแวดล้อม','เทคโนโลยีสุขภาพและความงาม','เทคโนโลยีการกีฬาและการออกกำลังกาย','วิทยาการคอมพิวเตอร์และปัญญาประดิษฐ์ประยุกต์','นวัตกรรมโภชนาการเพื่อการชะลอวัย'];
  ['filterRoomAll'].forEach(id => {
    const el = document.getElementById(id);
    el.innerHTML = '<option value="">ทุกห้อง</option>' + rooms.map(r=>`<option>${r}</option>`).join('');
  });
  ['filterBranchAll'].forEach(id => {
    const el = document.getElementById(id);
    el.innerHTML = '<option value="">ทุกสาขา</option>' + branches.map(b=>`<option>${b}</option>`).join('');
  });
}

// ============ TABLE ============
function renderTable(filter) {
  let data = [...cachedBookings];
  const tableId = filter === 'all' ? 'tableAll' : filter === 'approved' ? 'tableApproved' : filter === 'pending' ? 'tablePending' : 'tableRejected';

  if (filter !== 'all') {
    data = data.filter(b => b.status === filter);
  }

  // search
  const searchId = 'search' + (filter === 'all' ? 'All' : filter.charAt(0).toUpperCase() + filter.slice(1));
  const searchEl = document.getElementById(searchId);
  if (searchEl && searchEl.value) {
    const q = searchEl.value.toLowerCase();
    data = data.filter(b => b.studentId.toLowerCase().includes(q) || b.advisor.toLowerCase().includes(q) || b.room.includes(q) || b.branch.toLowerCase().includes(q));
  }

  if (filter === 'all') {
    const roomF = document.getElementById('filterRoomAll')?.value;
    const branchF = document.getElementById('filterBranchAll')?.value;
    if (roomF) data = data.filter(b => b.room === roomF);
    if (branchF) data = data.filter(b => b.branch === branchF);
  }

  data = data.sort((a,b) => new Date(b.submittedAt) - new Date(a.submittedAt));

  const container = document.getElementById(tableId);
  if (!data.length) {
    container.innerHTML = `<div class="empty-state"><div class="icon">🗂️</div><p>ไม่พบรายการ</p></div>`;
    return;
  }

  const statusBadge = s => ({
    pending: '<span class="badge badge-pending">⏳ รอการอนุมัติ</span>',
    approved: '<span class="badge badge-approved">✅ อนุมัติแล้ว</span>',
    rejected: '<span class="badge badge-rejected">❌ ไม่อนุมัติ</span>'
  })[s] || '';

  const isMobile = window.innerWidth < 768;

  if (isMobile) {
    // Card layout for mobile
    const cards = data.map(b => `
      <div style="background:white;border-radius:12px;padding:16px;margin-bottom:12px;border:1px solid var(--purple-100);box-shadow:var(--shadow-sm);">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:10px;">
          <div>
            <div style="font-weight:700;font-size:15px;color:var(--gray-700)">${b.studentId}</div>
            <div style="font-size:13px;color:var(--gray-400);margin-top:2px">${b.branch}</div>
          </div>
          ${statusBadge(b.status)}
        </div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;font-size:13px;margin-bottom:12px;">
          <div><span style="color:var(--gray-400)">ห้อง</span><br><strong style="color:var(--purple-700)">ห้อง ${b.room}</strong></div>
          <div><span style="color:var(--gray-400)">วันที่</span><br><strong>${formatDate(b.date)}</strong></div>
          <div><span style="color:var(--gray-400)">เวลา</span><br><strong>${b.timeStart} – ${b.timeEnd}</strong></div>
          <div><span style="color:var(--gray-400)">อาจารย์</span><br><strong>${b.advisor}</strong></div>
        </div>
        <div style="display:flex;gap:8px;">
          <button class="btn btn-ghost btn-sm" style="flex:1" onclick="showDetail('${b.id}')">👁 รายละเอียด</button>
          ${b.status === 'pending' ? `
            <button class="btn btn-success btn-sm" style="flex:1" onclick="openApprove('${b.id}')">✅ อนุมัติ</button>
            <button class="btn btn-danger btn-sm" style="flex:1" onclick="openReject('${b.id}')">❌ ไม่อนุมัติ</button>
          ` : ''}
        </div>
      </div>
    `).join('');
    container.innerHTML = `<div style="padding:12px;">${cards}</div>`;
  } else {
    // Table layout for desktop
    const rows = data.map(b => `
      <tr>
        <td><strong>${b.studentId}</strong></td>
        <td>${b.branch}</td>
        <td><strong>ห้อง ${b.room}</strong></td>
        <td>${formatDate(b.date)}</td>
        <td>${b.timeStart} – ${b.timeEnd}</td>
        <td>${b.advisor}</td>
        <td>${statusBadge(b.status)}</td>
        <td>
          <div class="action-btns">
            <button class="btn btn-ghost btn-sm" onclick="showDetail('${b.id}')">👁</button>
            ${b.status === 'pending' ? `
              <button class="btn btn-success btn-sm" onclick="openApprove('${b.id}')">✅</button>
              <button class="btn btn-danger btn-sm" onclick="openReject('${b.id}')">❌</button>
            ` : ''}
          </div>
        </td>
      </tr>
    `).join('');
    container.innerHTML = `
      <table>
        <thead><tr>
          <th>รหัสนักศึกษา</th><th>สาขา</th><th>ห้อง</th><th>วันที่</th><th>เวลา</th><th>อาจารย์ที่ปรึกษา</th><th>สถานะ</th><th>จัดการ</th>
        </tr></thead>
        <tbody>${rows}</tbody>
      </table>`;
  }
}

// ============ APPROVE / REJECT ============
function openApprove(id) {
  pendingActionId = id;
  pendingAction = 'approve';
  document.getElementById('approvePwInput').value = '';
  document.getElementById('approveError').style.display = 'none';
  openModal('approveModal');
  setTimeout(() => document.getElementById('approvePwInput').focus(), 200);
}
function openReject(id) {
  pendingActionId = id;
  pendingAction = 'reject';
  document.getElementById('rejectPwInput').value = '';
  document.getElementById('rejectError').style.display = 'none';
  openModal('rejectModal');
  setTimeout(() => document.getElementById('rejectPwInput').focus(), 200);
}
async function confirmApprove() {
  const pw = document.getElementById('approvePwInput').value;
  if (pw !== ADMIN_PASS) { document.getElementById('approveError').style.display = 'block'; return; }
  closeModal('approveModal');
  showToast('⏳ กำลังบันทึก...', '');
  await updateStatusRemote(pendingActionId, 'approved', pw);
  showToast('✅ อนุมัติการจองเรียบร้อยแล้ว', 'success');
  setTimeout(async () => { await getBookings(); refreshAdminTabs(); }, 2000);
}
async function confirmReject() {
  const pw = document.getElementById('rejectPwInput').value;
  if (pw !== ADMIN_PASS) { document.getElementById('rejectError').style.display = 'block'; return; }
  closeModal('rejectModal');
  showToast('⏳ กำลังบันทึก...', '');
  await updateStatusRemote(pendingActionId, 'rejected', pw);
  showToast('❌ ปฏิเสธคำขอเรียบร้อยแล้ว', 'error');
  setTimeout(async () => { await getBookings(); refreshAdminTabs(); }, 2000);
}
async function refreshAdminTabs() {
  loadDashboard();
  ['all','approved','pending','rejected'].forEach(t => renderTable(t));
}

// ============ DETAIL ============
function showDetail(id) {
  const b = cachedBookings.find(x => x.id === id);
  if (!b) return;
  const statusMap = { pending: '⏳ รอการอนุมัติ', approved: '✅ อนุมัติแล้ว', rejected: '❌ ไม่อนุมัติ' };
  document.getElementById('detailContent').innerHTML = `
    <div class="detail-grid">
      <div class="detail-item"><label>รหัสนักศึกษา</label><span>${b.studentId}</span></div>
      <div class="detail-item"><label>สาขา</label><span>${b.branch}</span></div>
      <div class="detail-item"><label>เบอร์โทร</label><span>${b.phone}</span></div>
      <div class="detail-item"><label>อาจารย์ที่ปรึกษา</label><span>${b.advisor}</span></div>
      <div class="detail-item"><label>ห้อง</label><span>ห้อง ${b.room}</span></div>
      <div class="detail-item"><label>วันที่</label><span>${formatDate(b.date)}</span></div>
      <div class="detail-item"><label>เวลา</label><span>${b.timeStart} – ${b.timeEnd}</span></div>
      <div class="detail-item"><label>สถานะ</label><span>${statusMap[b.status]}</span></div>
      <div class="detail-item" style="grid-column:1/-1"><label>วัตถุประสงค์</label><span>${b.purpose || '-'}</span></div>
      <div class="detail-item" style="grid-column:1/-1"><label>ส่งคำขอเมื่อ</label><span>${new Date(b.submittedAt).toLocaleString('th-TH')}</span></div>
    </div>`;
  openModal('detailModal');
}

// ============ SUBMIT BOOKING ============
async function submitBooking() {
  const fields = {
    studentId: document.getElementById('studentId'),
    branch: document.getElementById('branch'),
    phone: document.getElementById('phone'),
    advisor: document.getElementById('advisor'),
    room: document.getElementById('room'),
    bookDate: document.getElementById('bookDate'),
    timeStart: document.getElementById('timeStart'),
    timeEnd: document.getElementById('timeEnd'),
  };
  for (const [k, el] of Object.entries(fields)) {
    if (!el.value.trim()) {
      el.focus(); el.style.borderColor = 'var(--red-500)';
      setTimeout(() => el.style.borderColor = '', 2000);
      showToast('กรุณากรอกข้อมูลให้ครบถ้วน', 'error');
      return;
    }
  }
  // Validate student ID 13 digits
  if (fields.studentId.value.trim().length !== 13 || !/^\d{13}$/.test(fields.studentId.value.trim())) {
    fields.studentId.focus(); fields.studentId.style.borderColor = 'var(--red-500)';
    setTimeout(() => fields.studentId.style.borderColor = '', 2000);
    showToast('รหัสนักศึกษาต้องเป็นตัวเลข 13 หลัก', 'error'); return;
  }
  // Validate time
  const end = fields.timeEnd.value;
  if (fields.timeStart.value >= end) { showToast('เวลาเริ่มต้นต้องน้อยกว่าเวลาสิ้นสุด', 'error'); return; }

  const booking = {
    id: 'BK' + Date.now(),
    studentId: fields.studentId.value.trim(),
    branch: fields.branch.value,
    phone: fields.phone.value.trim(),
    advisor: fields.advisor.value.trim(),
    room: fields.room.value,
    date: fields.bookDate.value,
    timeStart: fields.timeStart.value,
    timeEnd: fields.timeEnd.value,
    purpose: document.getElementById('purpose').value.trim(),
    status: 'pending',
    submittedAt: new Date().toISOString(),
    updatedAt: null
  };

  const btnSubmit = document.querySelector('.form-submit .btn');
  btnSubmit.disabled = true;
  btnSubmit.textContent = '⏳ กำลังส่งข้อมูล...';
  try {
    await addBooking(booking);
    // Reset
    ['studentId','phone','advisor','purpose'].forEach(id => document.getElementById(id).value = '');
    ['branch','room'].forEach(id => document.getElementById(id).value = '');
    ['bookDate','timeStart','timeEnd'].forEach(id => document.getElementById(id).value = '');
    showToast('✅ ส่งคำขอจองห้องเรียบร้อยแล้ว! กำลังรอการอนุมัติ', 'success');
  } catch(e) {
    showToast('❌ เกิดข้อผิดพลาด กรุณาลองใหม่', 'error');
  } finally {
    btnSubmit.disabled = false;
    btnSubmit.textContent = '📨 ส่งคำขอจองห้อง';
  }
}
// ============ STATUS CHECK ============
async function searchStatus() {
  const sid = document.getElementById('statusSearchId').value.trim();
  const resultEl = document.getElementById('statusResult');
  if (!sid || sid.length !== 13) {
    showToast('กรุณากรอกรหัสนักศึกษา 13 หลัก', 'error');
    return;
  }
  resultEl.innerHTML = `<div style="text-align:center;padding:24px;color:var(--purple-500)">⏳ กำลังค้นหา...</div>`;

  const ok = await getBookings();
  if (!ok && cachedBookings.length === 0) {
    resultEl.innerHTML = `<div style="text-align:center;padding:24px;color:var(--red-500)">❌ ไม่สามารถโหลดข้อมูลได้ กรุณาลองใหม่</div>`;
    return;
  }

  const results = cachedBookings.filter(b => b.studentId === sid);
  if (!results.length) {
    resultEl.innerHTML = `
      <div style="text-align:center;padding:32px;background:var(--gray-50);border-radius:12px;border:1px solid var(--gray-200)">
        <div style="font-size:40px;margin-bottom:12px">📭</div>
        <p style="color:var(--gray-500);font-size:15px">ไม่พบคำขอของรหัส <strong>${sid}</strong></p>
        <p style="color:var(--gray-400);font-size:13px;margin-top:8px">กรุณาตรวจสอบรหัสนักศึกษาอีกครั้ง</p>
      </div>`;
    return;
  }

  const sorted = results.sort((a,b) => new Date(b.submittedAt) - new Date(a.submittedAt));
  const statusMap = {
    pending: { label: 'รอการอนุมัติ', color: 'var(--yellow-600)', bg: 'var(--yellow-100)', icon: '⏳' },
    approved: { label: 'อนุมัติแล้ว', color: 'var(--green-600)', bg: 'var(--green-100)', icon: '✅' },
    rejected: { label: 'ไม่อนุมัติ', color: 'var(--red-600)', bg: 'var(--red-100)', icon: '❌' },
  };

  const cards = sorted.map(b => {
    const s = statusMap[b.status] || statusMap.pending;
    return `
      <div style="background:white;border-radius:12px;padding:20px;margin-bottom:14px;border:1.5px solid ${b.status==='approved'?'var(--green-600)':b.status==='rejected'?'var(--red-500)':'var(--purple-200)'};box-shadow:var(--shadow-sm)">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;flex-wrap:wrap;gap:8px">
          <div>
            <div style="font-weight:700;font-size:16px;color:var(--gray-700)">ห้อง ${b.room}</div>
            <div style="font-size:13px;color:var(--gray-400);margin-top:2px">${b.branch}</div>
          </div>
          <span style="background:${s.bg};color:${s.color};padding:6px 14px;border-radius:50px;font-size:13px;font-weight:700">${s.icon} ${s.label}</span>
        </div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;font-size:14px;background:var(--gray-50);border-radius:8px;padding:12px">
          <div><span style="color:var(--gray-400);font-size:12px">วันที่ขอใช้</span><br><strong>${formatDate(b.date)}</strong></div>
          <div><span style="color:var(--gray-400);font-size:12px">เวลา</span><br><strong>${b.timeStart} – ${b.timeEnd} น.</strong></div>
          <div><span style="color:var(--gray-400);font-size:12px">อาจารย์ที่ปรึกษา</span><br><strong>${b.advisor}</strong></div>
          <div><span style="color:var(--gray-400);font-size:12px">ส่งคำขอเมื่อ</span><br><strong>${new Date(b.submittedAt).toLocaleDateString('th-TH')}</strong></div>
        </div>
        ${b.status==='approved' ? `<div style="margin-top:12px;background:var(--green-100);color:var(--green-600);border-radius:8px;padding:10px 14px;font-size:13px;font-weight:600">✅ คำขอของคุณได้รับการอนุมัติแล้ว สามารถเข้าใช้ห้องได้ตามวันเวลาที่กำหนด</div>` : ''}
        ${b.status==='rejected' ? `<div style="margin-top:12px;background:var(--red-100);color:var(--red-600);border-radius:8px;padding:10px 14px;font-size:13px;font-weight:600">❌ คำขอของคุณไม่ได้รับการอนุมัติ กรุณาติดต่ออาจารย์ที่ปรึกษา</div>` : ''}
        ${b.status==='pending' ? `<div style="margin-top:12px;background:var(--yellow-100);color:var(--yellow-600);border-radius:8px;padding:10px 14px;font-size:13px;font-weight:600">⏳ คำขอของคุณอยู่ระหว่างการพิจารณา กรุณารอการแจ้งผล</div>` : ''}
      </div>`;
  }).join('');

  resultEl.innerHTML = `
    <div style="margin-bottom:14px;font-size:14px;color:var(--gray-500)">พบ <strong style="color:var(--purple-600)">${results.length}</strong> คำขอของรหัส <strong>${sid}</strong></div>
    ${cards}`;
}
function formatDate(d) {
  if (!d) return '-';
  const dt = new Date(d + 'T00:00:00');
  return dt.toLocaleDateString('th-TH', {year:'numeric',month:'long',day:'numeric'});
}
function openModal(id) { document.getElementById(id).classList.add('open'); }
function closeModal(id) { document.getElementById(id).classList.remove('open'); }
let toastTimer;
function showToast(msg, type = '') {
  const el = document.getElementById('toast');
  el.textContent = msg;
  el.className = 'toast ' + (type === 'error' ? 'error' : type === 'success' ? 'success' : '');
  el.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => el.classList.remove('show'), 3500);
}

// Close modal on overlay click
document.querySelectorAll('.modal-overlay').forEach(o => {
  o.addEventListener('click', e => { if (e.target === o) o.classList.remove('open'); });
});

// Set min date to today
document.getElementById('bookDate').min = new Date().toISOString().split('T')[0];
</script>
</body>
</html>

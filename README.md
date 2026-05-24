<!doctype html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ma Trận Kỹ Năng CNTT</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" />
  </head>
  <body class="bg-light">
 
    <!-- Thanh điều hướng -->
 <nav class="navbar navbar-expand-lg bg-info border-bottom shadow-sm">
      <div class="container">
        <a class="navbar-brand" href="#">Kỹ năng CNTT</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navMenu">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link" href="#" onclick="showPage('home')">Trang Chủ</a></li>
            <li class="nav-item"><a class="nav-link" href="#" onclick="showPage('manage')">Quản Lý</a></li>
            <li class="nav-item"><a class="nav-link" href="#" onclick="showPage('debug')">Debug</a></li>
          </ul>
        </div>
      </div>
    </nav>
 
    <!-- ===== TRANG CHỦ ===== -->
 <div id="page-home">
 
      <!-- Card công nghệ -->
 <div class="container mt-4">
        <h4>Các Công Nghệ Đang Học</h4>
        <div class="row g-3 mt-1">
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title">HTML & CSS</h5>
                <span class="badge bg-success">Nền tảng Web</span>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title">JavaScript</h5>
                <span class="badge text-bg-warning">Lập trình Web</span>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title">Python</h5>
                <span class="badge text-bg-danger">Đa năng</span>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title">SQL</h5>
                <span class="badge bg-primary">Cơ sở dữ liệu</span>
              </div>
            </div>
          </div>
        </div>
      </div>
 
      <!-- Carousel chứng chỉ -->
 <div class="container mt-4">
        <h4>Chứng Chỉ Đã Đạt Được</h4>
        <div id="carouselExampleAutoplaying" class="carousel slide mt-2" data-bs-ride="carousel">
          <div class="carousel-inner rounded">
            <div class="carousel-item active">
              <div class="bg-primary text-white text-center p-5">
                <h5>Chứng Chỉ HTML5 & CSS3</h5>
                <p>Cấp bởi: W3Schools · 2023</p>
              </div>
            </div>
            <div class="carousel-item">
              <div class="bg-success text-white text-center p-5">
                <h5>Chứng Chỉ JavaScript</h5>
                <p>Cấp bởi: freeCodeCamp · 2024</p>
              </div>
            </div>
            <div class="carousel-item">
              <div class="bg-warning text-dark text-center p-5">
                <h5>Chứng Chỉ Python Basics</h5>
                <p>Cấp bởi: Coursera · 2024</p>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
          </button>
        </div>
      </div>
 
      <!-- Về tôi -->
 <div class="container mt-4 mb-5">
        <h4>Về Tôi</h4>
        <div class="card mt-2">
          <div class="card-body d-flex align-items-center gap-3">
            <img src="https://via.placeholder.com/100" class="rounded-circle" alt="Ảnh cá nhân" />
            <div>
              <h5 class="mb-1">Nguyễn Văn A</h5>
              <p class="text-muted mb-0">Sinh viên Công nghệ Thông tin</p>
              <p class="mb-0">Ảnh chụp tại phòng trường hoặc ở nhà.</p>
            </div>
          </div>
        </div>
      </div>
 
</div>
 
    <!-- ===== TRANG QUẢN LÝ ===== -->
 <div id="page-manage" style="display:none">
      <div class="container mt-4 mb-5">
        <h4>Quản Lý Kỹ Năng</h4>
 
<div class="alert alert-info mt-2">
          MSSV lẻ → thêm vào <strong>đầu</strong> bảng &nbsp;|&nbsp; MSSV chẵn → thêm vào <strong>cuối</strong> bảng
        </div>
 
<div class="row g-4 mt-1">
 
          <!-- Form -->
<div class="col-md-5">
            <div class="card">
              <div class="card-header bg-primary text-white">Thêm Kỹ Năng</div>
              <div class="card-body">
                <div class="mb-3">
                  <label for="inputMSSV" class="form-label">MSSV</label>
                  <input type="text" class="form-control" id="inputMSSV" placeholder="VD: 254D4800300" />
                </div>
                <div class="mb-3">
                  <label for="inputTech" class="form-label">Tên Công Nghệ</label>
                  <input type="text" class="form-control" id="inputTech" placeholder="VD: HTML" />
                </div>
                <div class="mb-3">
                  <label for="inputYear" class="form-label">Năm Ban Hành</label>
                  <input type="text" class="form-control" id="inputYear" placeholder="VD: 2025" />
                </div>
                <div class="mb-3">
                  <label for="inputLevel" class="form-label">Mức Độ (1-10)</label>
                  <input type="number" class="form-control" id="inputLevel" placeholder="1-10" min="1" max="10" />
                </div>
                <div class="mb-3">
                  <label for="inputNote" class="form-label">Ghi Chú</label>
                  <input type="text" class="form-control" id="inputNote" placeholder="" />
                </div>
                <button class="btn btn-primary" onclick="addSkill()">Thêm</button>
              </div>
            </div>
          </div>
 
          <!-- Bảng -->
<div class="col-md-7">
            <table class="table table-striped table-hover table-bordered">
              <thead class="table-primary">
                <tr>
                  <th>#</th>
                  <th>MSSV</th>
                  <th>Tên Công Nghệ</th>
                  <th>Năm Ban Hành</th>
                  <th>Mức Độ</th>
                  <th>Ghi Chú</th>
                </tr>
              </thead>
              <tbody id="skillTableBody">
                <tr><td colspan="6" class="text-center text-muted">Chưa có dữ liệu</td></tr>
              </tbody>
            </table>
          </div>
 
</div>
      </div>
    </div>
 
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script>
      // Navigation
      function showPage(name) {
        ['home', 'manage', 'debug'].forEach(function(p) {
          var el = document.getElementById('page-' + p);
          if (el) el.style.display = (p === name) ? 'block' : 'none';
        });
      }
 
      // Quản lý kỹ năng
      var skills = [];
 
      function addSkill() {
        var mssv  = document.getElementById('inputMSSV').value.trim();
        var tech  = document.getElementById('inputTech').value.trim();
        var year  = document.getElementById('inputYear').value.trim();
        var level = parseInt(document.getElementById('inputLevel').value);
        var note  = document.getElementById('inputNote').value.trim();
 
        if (!mssv || !tech || !year || isNaN(level)) {
          alert('Vui lòng điền đầy đủ thông tin!');
          return;
        }
        if (level < 1 || level > 10) {
          alert('Mức độ phải từ 1 đến 10!');
          return;
        }
 
        var skill = { mssv: mssv, tech: tech, year: year, level: level, note: note };
        var lastDigit = parseInt(mssv[mssv.length - 1]);
 
        // Ràng buộc định danh: lẻ → đầu, chẵn → cuối
        if (lastDigit % 2 !== 0) {
          skills.unshift(skill);
        } else {
          skills.push(skill);
        }
 
        // Tính năng bổ sung
        var highCount = skills.filter(function(s) { return s.level > 7; }).length;
        if (highCount > 7) {
          alert('Hồ sơ năng lực rất ấn tượng!');
        }
 
        renderTable();
 
        // Xoá form
        document.getElementById('inputMSSV').value = '';
        document.getElementById('inputTech').value = '';
        document.getElementById('inputYear').value = '';
        document.getElementById('inputLevel').value = '';
        document.getElementById('inputNote').value = '';
      }
 
      function renderTable() {
        var tbody = document.getElementById('skillTableBody');
        if (skills.length === 0) {
          tbody.innerHTML = '<tr><td colspan="6" class="text-center text-muted">Chưa có dữ liệu</td></tr>';
          return;
        }
        tbody.innerHTML = skills.map(function(s, i) {
          return '<tr><td>' + (i+1) + '</td><td>' + s.mssv + '</td><td>' + s.tech +
                 '</td><td>' + s.year + '</td><td>' + s.level + '/10</td><td>' +
                 (s.note || '—') + '</td></tr>';
        }).join('');
      }
    </script>
  </body>
</html>

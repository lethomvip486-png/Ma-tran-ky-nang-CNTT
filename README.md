<!doctype html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ma Trận Kỹ Năng CNTT</title>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    />
  </head>
  <body class="bg-light">
 
    <!-- Thanh điều hướng -->
 <nav class="navbar navbar-expand-lg bg-info border-bottom shadow-sm">
      <div class="container">
        <a class="navbar-brand" href="#">Kỹ năng CNTT</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navMenu"
        >
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
 
    <!-- Phần trang chủ -->
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



  <div class="container mt-4 mb-5">
        <h4>Quản Lý Kỹ Năng</h4>
        <div class="row g-3 mt-1">
 
<div class="col-md-3">
            <div class="card text-center bg-info">
              <div class="card-body">
                <p class="card-title">MSSV lẻ → thêm
                   vào đầu bảng  |  
                  MSSV chẵn → thêm vào cuối bảng</p>
                
 </div>
            </div>
          </div>
          <div class="container mt-4 mb-5">
             <div class="row">
              <div class="col">
        <h5 class="bg-primary text-white bs-light ">Thêm Kỹ Năng
        </h5>
         <div class="mb-3">
  <label for="MSSV" class="form-label">MSSV</label>
  <input type="text" class="form-control" id="MSSV" placeholder="VD: 254D4800300">
</div>


<div class="mb-3">
  <label for="Technology" class="form-label">Tên Công Nghệ</label>
  <input type="text" class="form-control" id="Technology" placeholder="VD: HTML">
</div>


<div class="mb-3">
  <label for="Year" class="form-label">Năm Ban Hành</label>
  <input type="text" class="form-control" id="Year" placeholder="VD: 2025">
</div>



<div class="mb-3">
  <label for="Lever" class="form-label">Mức Độ (1-10)</label>
  <input type="text" class="form-control" id="Lever" placeholder="1-10">
</div>


<div class="mb-3">
  <label for="Keep" class="form-label">Ghi chú</label>
  <input type="text" class="form-control" id="Keep" placeholder="">
</div>

 <input
            type="button"
            class="btn btn-primary my-3"
            value="Thêm"
            onclick="displayValue()"
          />



 </div>
        </div> 
      </div>
    </div>
    <div class="col">

 <table class="table table-striped table-primary table-hover">
            <thead>
              <tr>
                <th id="MSSV">MSSV</th>
                <th id="Teachnology">Tên Công Nghệ</th>
                <th id="Year">Năm Ban Hành</th>
                 <th id="Lever">Mức Độ</th>
                 <th id="Keep">Ghi Chú</th>
              </tr>
            </thead>
            <tbody id="danh-sach-mon-hoc"></tbody>
          </table>
        </div>

 
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
 <script>
      var i = 1;
      function displayValue() {
        let name = document.getElementById("MSSV").value;
        document.getElementById("full-name").innerHTML = name;
        let subject_name = document.getElementById("subject").value;
        let credit = document.getElementById("credit").value;
        document.getElementById("danh-sach-mon-hoc").insertRow(0).innerHTML =
          "<td>" +
          i +
          "</td><td>" +
          subject_name +
          "</td><td>" +
          credit +
          "</td>";
        i++;
        document.getElementById("subject").value = "";
        document.getElementById("credit").value = "";
      }
    </script>
  </body>
</html>

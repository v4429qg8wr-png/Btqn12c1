# Btqn12c1 
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Định Hướng Nghề Nghiệp Du Lịch</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(to bottom,#f4fbff,#dff6ff,#ffffff);
    color:#333;
    overflow-x:hidden;
}


header{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.55)),
    url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=1600&auto=format&fit=crop');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
    position:relative;
    overflow:hidden;
}
header::after{
    content:'';
    position:absolute;
    bottom:0;
    left:0;
    width:100%;
    height:120px;
    background:linear-gradient(to top,#f4fbff,transparent);
}
.hero{
    max-width:900px;
    animation:fadeIn 2s ease;
}

.hero h1{
    font-size:70px;
    margin-bottom:20px;
    text-shadow:3px 3px 15px rgba(0,0,0,0.5);
}

.hero p{
    font-size:24px;
    line-height:1.8;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#89cff0;
    color:white;
    text-decoration:none;
    border-radius:40px;
    font-weight:bold;
    transition:0.4s;
}

.btn:hover{
    transform:scale(1.08);
    background:#4da8da;
    color:white;
}


nav{
    background:rgba(110,198,255,0.85);
    backdrop-filter:blur(10px);
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
    flex-wrap:wrap;
}

nav ul li{
    margin:15px 25px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-weight:600;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ffd166;
}


section{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:90px 20px;
}

.title{
    text-align:center;
    margin-bottom:50px;
}

.title h2{
    font-size:42px;
    color:#4da8da;
    margin-bottom:15px;
}

.title p{
    color:#666;
    font-size:18px;
}


.profile{
    background:white;
    padding:50px;
    border-radius:30px;
    box-shadow:0 10px 30px rgba(0,0,0,0.08);
}

.profile h3{
    font-size:32px;
    color:#4da8da;
    margin-bottom:20px;
}

.profile p{
    margin:12px 0;
    font-size:18px;
}


.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:30px;
}
.card{
background:rgba(255,255,255,0.75);
    padding:35px;
    border-radius:25px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    transition:0.4s;
    backdrop-filter:blur(10px);
    border:1px solid rgba(255,255,255,0.5);
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
    color:#4da8da;
}

.quote{
    background:linear-gradient(135deg,#89cff0,#bdefff);
    color:white;
    padding:60px;
    border-radius:30px;
    text-align:center;
    margin-top:50px;
    box-shadow:0 10px 30px rgba(0,0,0,0.15);
}

.quote h2{
    font-size:40px;
margin-bottom:25px;
}

.quote p{
    font-size:20px;
    line-height:2;
}


footer{
    background:#0077b6;
    color:white;
    text-align:center;
    padding:35px;
    margin-top:70px;
}

footer p{
    margin:8px 0;
}


@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(40px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}


@media(max-width:768px){

.hero h1{
    font-size:42px;
}

.hero p{
    font-size:18px;
}

.title h2{
    font-size:32px;
}

.quote h2{
    font-size:30px;
}

}

</style>

</head>

<body>


<header>

<div class="hero">

<h1>NGÀNH DU LỊCH</h1>

<p>
“Hành trình khám phá thế giới, kết nối văn hóa và mở ra tương lai đầy trải nghiệm.”
</p>

<a href="#profile" class="btn">Khám Phá Ngay</a>

</div>

</header>


<nav>

<ul>
<li><a href="#profile">Thông Tin</a></li>
<li><a href="#dream">Định Hướng</a></li>
<li><a href="#difficulty">Băn Khoăn</a></li>
<li><a href="#english">Tiếng Anh</a></li>
<li><a href="#goal">Cần Có</a></li>
</ul>

</nav>


<section id="profile">

<div class="title">
<h2>Thông Tin Cá Nhân</h2>
<p>Định hướng nghề nghiệp tương lai</p>
</div>

<div class="profile">

<h3>Bùi Thị Quỳnh Như</h3>

<p><b>Ngày sinh:</b> 26/03/2008</p>

<p><b>Trường:</b> THPT Trường Chinh</p>

<p><b>Lớp:</b> 12C1</p>

<p><b>Định hướng nghề nghiệp:</b> Quản trị dịch vụ du lịch và lữ hành</p>

</div>

</section>


<section id="dream">

<div class="title">
<h2>Lý Do Chọn Ngành</h2>
<p>Đam mê và định hướng của bản thân</p>
</div>

<div class="cards">

<div class="card">

<h3>🌍 Yêu Thích Khám Phá</h3>

<p>
Em yêu thích khám phá văn hóa, những vùng đất mới và được giao tiếp với nhiều người.
Ngành du lịch giúp em mở rộng hiểu biết và trải nghiệm thực tế.
</p>

</div>

<div class="card">

<h3>✨ Môi Trường Năng Động</h3>

<p>
Ngành du lịch có môi trường làm việc năng động,
hiện đại và mang lại nhiều cơ hội phát triển kỹ năng.
</p>

</div>

<div class="card">

<h3>💙 Phù Hợp Sở Thích</h3>

<p>
Đây là ngành học phù hợp với tính cách hòa đồng,
thích giao tiếp và yêu thích các hoạt động trải nghiệm của em.
</p>

</div>

</div>

</section>


<section id="difficulty">

<div class="title">
<h2>Những Băn Khoăn Và Trắc Trở</h2>
<p>Con đường theo đuổi ngành du lịch cần nhiều cố gắng</p>
</div>

<div class="cards">

<div class="card">

<h3>📚 Áp Lực Học Tập</h3>

<p>
Cần học tập chăm chỉ để có kiến thức về quản lý,
dịch vụ và kỹ năng giao tiếp chuyên nghiệp.
</p>

</div>

<div class="card">

<h3>💰 Điều Kiện Kinh Tế</h3>

<p>
Ngành du lịch cần nhiều trải nghiệm thực tế,
đôi khi phải di chuyển và tham gia các hoạt động ngoại khóa.
</p>

</div>

<div class="card">

<h3>⏰ Sự Kiên Trì</h3>

<p>
Cần có sự tự tin, năng động và kiên trì để vượt qua khó khăn,
áp lực công việc và môi trường cạnh tranh.
</p>

</div>

</div>

</section>


<section id="english">

<div class="title">
<h2>Tiền Đề Và Năng Khiếu</h2>
<p>Kỹ năng cần thiết để học ngành du lịch</p>
</div>

<div class="cards">

<div class="card">

<h3>🗣️ Kỹ Năng Giao Tiếp</h3>

<p>
Ngành du lịch cần khả năng giao tiếp tốt,
biết lắng nghe và tạo thiện cảm với mọi người.
</p>

</div>

<div class="card">

<h3>🇬🇧 Ngoại Ngữ Tiếng Anh</h3>

<p>
Tiếng Anh là kỹ năng rất quan trọng giúp giao tiếp với khách quốc tế,
mở rộng cơ hội nghề nghiệp và học hỏi thêm kiến thức.
</p>

</div>

<div class="card">

<h3>🌟 Sự Tự Tin</h3>

<p>
Tự tin và năng động là yếu tố giúp em thích nghi tốt
với môi trường du lịch và dịch vụ.
</p>

</div>

</div>

</section>


<section id="goal">

<div class="quote">

<h2>Thành Tích Cần Có </h2>

<p>

✔ Cố gắng học tập tốt để đạt kết quả cao.<br><br>

✔ Rèn luyện kỹ năng giao tiếp và ngoại ngữ.<br><br>

✔ Tích lũy kinh nghiệm để làm việc trong lĩnh vực quản lý và điều hành du lịch.

</p>

</div>

</section>


<footer>

<p><b>WEBSITE ĐỊNH HƯỚNG NGHỀ NGHIỆP NGÀNH DU LỊCH</b></p>

<p>Thiết kế với niềm yêu thích khám phá và trải nghiệm 🌍</p>

<p>© 2026 - Bùi Thị Quỳnh Như</p>

</footer>

</body>
</html>

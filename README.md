<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>ELITE FIGHTER PROFILE</title>

<style>
body{
margin:0;
font-family: Arial;
background: radial-gradient(circle at top,#1a1a1a,#000);
color:white;
display:flex;
justify-content:center;
align-items:center;
min-height:100vh;

/* 🔥 cinematic entry */
animation: bgFade 1.2s ease;
}

@keyframes bgFade{
from{opacity:0;}
to{opacity:1;}
}

.card{
width: 560px;
background: linear-gradient(145deg,#141414,#070707);
border-radius: 22px;
padding: 25px;
box-shadow: 0 0 50px black;
border: 1px solid #333;
position: relative;
overflow:hidden;

/* 🔥 cinematic zoom */
animation: cardIn 1s ease;
}

@keyframes cardIn{
from{transform:scale(0.85); opacity:0;}
to{transform:scale(1); opacity:1;}
}

.card::before{
content:"";
position:absolute;
width:200%;
height:200%;
top:-50%;
left:-50%;
background: radial-gradient(circle, rgba(255,215,0,0.08), transparent 60%);
transform: rotate(30deg);
animation: glowMove 6s linear infinite;
}

@keyframes glowMove{
0%{transform:rotate(0deg);}
100%{transform:rotate(360deg);}
}

/* 🔥 FIRE HEADER */
.fire-header{
margin-bottom:15px;
padding:12px;
border-radius:12px;
text-align:center;
font-weight:bold;
color:white;
background: linear-gradient(90deg,#ff2b2b,#ff7b00,#ff2b2b);
background-size:200% 100%;
animation: fireMove 1.5s linear infinite;
box-shadow: 0 0 18px #ff3b00;
}

@keyframes fireMove{
0%{background-position:0%;}
100%{background-position:200%;}
}

.badge{
display:inline-block;
background:gold;
color:black;
padding:6px 14px;
border-radius:8px;
font-weight:bold;
}

h1{
margin:10px 0;
font-size:32px;
}

.nickname{
color:#ff2b2b;
font-size:22px;
font-weight:bold;
}

.flame-name{
font-size: 28px;
font-weight: bold;
background: linear-gradient(90deg,#ff0000,#ff6a00,#ffb300,#fff000,#ff0000);
background-size: 400% 100%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
animation: flameMove 0.9s linear infinite, flameFlicker 0.15s infinite;
text-shadow: 0 0 5px #ff2b00,0 0 10px #ff6a00,0 0 20px #ffb300,0 0 30px #ff0000;
}

@keyframes flameMove{
0%{background-position:0%;}
100%{background-position:400%;}
}

@keyframes flameFlicker{
0%,100%{transform: scale(1);}
50%{transform: scale(1.02);}
}

.stars{
color:gold;
margin:10px 0;
font-size:18px;
}

.info{
color:#ddd;
margin:5px 0;
}

.profile img{
width:120px;
height:120px;
border-radius:50%;
border:3px solid gold;
object-fit:cover;
margin-top:15px;
}

.section{
margin-top:15px;
padding-top:10px;
border-top:1px solid #333;
}

.bio{
font-size:14px;
line-height:1.6;
color:#ccc;
}

.stat{
text-align:left;
margin:10px 0;
}

.bar{
height:10px;
background:#333;
border-radius:10px;
overflow:hidden;
}

.fill{
height:10px;
background:gold;
}

.small{
font-size:12px;
color:#888;
}

.footer{
margin-top:10px;
font-size:12px;
color:#777;
}

/* 🔥 FIRE LINE */
.fire-line{
margin-top:18px;
padding:14px;
border-radius:12px;
text-align:center;
font-weight:bold;
color:white;
background: linear-gradient(90deg,#ff2b2b,#ff7b00,#ff2b2b);
background-size:200% 100%;
animation: fireMove 1.5s linear infinite;
box-shadow: 0 0 18px #ff3b00;
}

/* 🔥 QR UFC STYLE */
.qr-box{
display:flex;
justify-content:center;
margin-top:10px;
}

.qr-frame{
padding:14px;
border-radius:14px;
border:2px solid gold;
background:#111;
box-shadow:0 0 20px rgba(255,215,0,0.4);
animation: qrGlow 2s infinite alternate;
}

@keyframes qrGlow{
from{box-shadow:0 0 10px rgba(255,215,0,0.3);}
to{box-shadow:0 0 25px rgba(255,215,0,0.8);}
}

</style>
</head>

<body>

<div class="card">

<div class="fire-header">
أحد تلاميذ الكابتن سجاد البديري
</div>

<div class="badge">UFC ELITE FIGHTER</div>

<h1>مرتضى فراس عضيم</h1>

<div class="nickname">
اللقب: <span class="flame-name">غضب 🔥</span>
</div>

<div class="stars">★★★★★ محترف</div>

<div class="profile">
<img src="https://i.imgur.com/8Km9tLL.png">
</div>

<div class="info">العمر: 18 سنة</div>
<div class="info">الطول: 184 سم</div>
<div class="info">الوزن: 66 كغم</div>
<div class="info">الرياضة: مواي تاي 🥊</div>
<div class="info">الأكاديمية: بانكوك</div>

<div class="section">
<h3>الإحصائيات القتالية</h3>

<div class="stat">القوة<div class="bar"><div class="fill" style="width:92%"></div></div></div>
<div class="stat">السرعة<div class="bar"><div class="fill" style="width:88%"></div></div></div>
<div class="stat">التحمل<div class="bar"><div class="fill" style="width:90%"></div></div></div>
<div class="stat">الخبرة<div class="bar"><div class="fill" style="width:84%"></div></div></div>

</div>

<div class="section">
<h3>نبذة احترافية</h3>
<div class="bio">
مقاتل مواي تاي يمتلك أسلوب هجومي سريع يعتمد على الضغط والسيطرة داخل الحلبة.  
يُعرف بلقب "غضب" لأسلوبه القتالي القوي والانفجاري.  
يمتلك مستوى متقدم في المواي تاي مع قدرة عالية على التكيف تحت الضغط.
</div>
</div>

<div class="section">
<h3>الإنجازات 🏆</h3>
<p>4 بطولات بابل</p>
<p>2 الناصرية</p>
<p>1 واسط</p>
</div>

<div class="section qr">
<h3>QR CODE</h3>

<div class="qr-box">
<div class="qr-frame">
<img src="https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=https://r66vfcbwh9-alt.github.io/Murtada/">
</div>
</div>

<div class="small" style="text-align:center;margin-top:8px;">
امسح الكود لفتح البطاقة
</div>

</div>

<div class="section">
<h3>التواصل</h3>
<p>Instagram: _9w7o</p>
<p>TikTok: _9w7o</p>
</div>

<div class="fire-line">

✔ يمتلك خبرة في مواقف صعبة ويتعامل مع الضغط بهدوء  
✔ يمكنه بكل سهولة الدفاع عن نفسه عند الحاجة  
✔ يمتلك حضور قوي وثقة عالية بالنفس  

</div>

<div class="footer">
ELITE FIGHTER PROFILE • MUAY THAI
</div>

</div>

</body>
</html>

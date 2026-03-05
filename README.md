<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Abdelrahman Ahmed</title>

<style>

body{
margin:0;
font-family:system-ui;
background:#0f172a;
color:#e2e8f0;
}

/* layout */

.container{
display:flex;
max-width:1200px;
margin:auto;
padding:30px;
gap:30px;
}

/* sidebar */

.sidebar{
width:300px;
background:#111827;
padding:25px;
border-radius:12px;
}

.profile-img{
width:120px;
height:120px;
border-radius:50%;
object-fit:cover;
margin-bottom:15px;
}

.name{
font-size:22px;
font-weight:600;
}

.username{
color:#9ca3af;
margin-bottom:10px;
}

.bio{
font-size:14px;
margin-bottom:15px;
}

.edit-btn{
width:100%;
padding:10px;
background:#1f2937;
border:none;
border-radius:8px;
color:white;
cursor:pointer;
margin-bottom:20px;
}

.info{
font-size:14px;
margin:6px 0;
color:#cbd5e1;
}

.achievements{
margin-top:20px;
}

.achievements img{
width:45px;
height:45px;
border-radius:10px;
margin:5px;
}

/* right side */

.content{
flex:1;
}

.section{
background:#111827;
padding:25px;
border-radius:12px;
margin-bottom:20px;
}

.section h2{
margin-top:0;
margin-bottom:15px;
}

.tech-stack span{
display:inline-block;
background:#1f2937;
padding:6px 12px;
border-radius:6px;
margin:5px;
font-size:13px;
}

.socials a{
display:inline-block;
margin-right:10px;
padding:8px 14px;
background:#1f2937;
border-radius:6px;
text-decoration:none;
color:#e2e8f0;
font-size:13px;
}

</style>

</head>

<body>

<div class="container">

<!-- Sidebar -->

<div class="sidebar">

<img src="profile.jpg" class="profile-img">

<div class="name">Abdelrahman Ahmed</div>
<div class="username">@abdelrahman</div>

<div class="bio">
Data Science Student | Data Analyst | Machine Learning Enthusiast
</div>

<button class="edit-btn">Edit profile</button>

<div class="info">👥 2.2k followers · 12 following</div>
<div class="info">📍 Egypt</div>
<div class="info">🕒 UTC +02:00</div>
<div class="info">🔗 abdelrahmanahmed.com</div>

<div class="info">💼 Data Science Student</div>

<div class="achievements">

<h4>Achievements</h4>

<img src="https://github.githubassets.com/images/modules/profile/achievements/pull-shark-default.png">
<img src="https://github.githubassets.com/images/modules/profile/achievements/yolo-default.png">
<img src="https://github.githubassets.com/images/modules/profile/achievements/starstruck-default.png">
<img src="https://github.githubassets.com/images/modules/profile/achievements/quickdraw-default.png">

</div>

</div>

<!-- Right Content -->

<div class="content">

<div class="section">

<h2>👋 Hi there</h2>

<p>
I'm Abdelrahman Ahmed, a passionate Data Science student with strong
interest in data analysis, machine learning, and building real-world
data projects.
</p>

<p>
My goal is to become a professional Data Scientist by applying
statistical analysis and machine learning techniques to solve
real-world problems.
</p>

</div>

<div class="section">

<h2>🚀 Expertise</h2>

<p>
Experienced in data analysis using Python and modern data science
tools. Skilled in exploratory data analysis, machine learning
modeling, and data visualization.
</p>

<p>
I enjoy transforming raw data into actionable insights and building
predictive models.
</p>

</div>

<div class="section">

<h2>💻 Tech Stack</h2>

<div class="tech-stack">

<span>Python</span>
<span>SQL</span>
<span>Pandas</span>
<span>NumPy</span>
<span>Scikit-Learn</span>
<span>Matplotlib</span>
<span>Seaborn</span>
<span>Machine Learning</span>

</div>

</div>

<div class="section">

<h2>🌐 Socials</h2>

<div class="socials">

<a href="https://www.linkedin.com/in/abdelrahmanahmed">LinkedIn</a>
<a href="#">GitHub</a>
<a href="#">Twitter</a>

</div>

</div>

</div>

</div>

</body>
</html>

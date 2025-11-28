body {
font-family: 'Roboto', sans-serif;
margin: 0;
padding: 0;
background-color: #f5f5f5;
}
header {
background-color: #0a4d8c;
color: white;
padding: 20px;
text-align: center;
}
header img {
max-width: 80px;
vertical-align: middle;
}
nav {
background-color: #007acc;
overflow: hidden;
}
nav a {
float: left;
display: block;
color: white;
text-align: center;
padding: 14px 20px;
text-decoration: none;
transition: 0.3s;
}
nav a:hover {
background-color: #005f99;
}
.hero {
position: relative;
text-align: center;
color: white;
}
.slider {
position: relative;
overflow: hidden;
max-height: 400px;
}
.slide {
width: 100%;
display: none;
}
.slide.active {
display: block;
}
.hero-text {
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
}
.courses {
display: flex;
flex-wrap: wrap;
justify-content: center;
padding: 20px;
}
.course {
background-color: white;
border: 1px solid #ddd;
border-radius: 10px;
margin: 10px;
padding: 20px;
width: 250px;
text-align: center;
box-shadow: 2px 2px 15px rgba(0,0,0,0.15);
transition: transform 0.3s;
}
.course:hover {
transform: scale(1.05);
}
.course h3 {
color: #007acc;
}
footer {
background-color: #0a4d8c;
color: white;
text-align: center;
padding: 20px;
margin-top: 20px;
}
footer a {
color: #ffeb3b;
text-decoration: none;
}
@media (max-width: 768px) {
.courses { flex-direction: column; align-items: center; }
}

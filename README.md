<!DOCTYPE html>
<html>
<head>
  <title>iLex Public School</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
    }
    
    header {
      background-color: red;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    h1 {
      font-size: 32px;
      font-weight: bold;
    }
    
    .container {
      display: flex;
    }
    
    .options {
      flex-basis: 20%;
      background-color: #333;
      color: #fff;
      padding: 10px;
    }
    
    .options ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }
    
    .options li {
      margin-bottom: 10px;
    }
    
    section {
      flex-basis: 80%;
      padding: 20px;
    }
    
    section h2 {
      font-weight: bold;
      color: blue;
      font-size: 24px;
      cursor: pointer;
    }
    
    section p {
      margin-bottom: 10px;
      color: blue;
      font-size: 16px;
    }
    
    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    .background-animation {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      animation: animateBackground 20s linear infinite;
      background-image: url("C:/Users/admin/Pictures/2023_02_17_09_11_IMG_0005.JPG");
      background-size: cover;
    }
    
    @keyframes animateBackground {
      0% {
        background-position: 0 0;
      }
      25% {
        background-position: 100% 0;
      }
      50% {
        background-position: 100% 100%;
      }
      75% {
        background-position: 0 100%;
      }
      100% {
        background-position: 0 0;
      }
    }
    
    .link-container {
      display: flex;
      align-items: center;
    }
    
    .link-container a {
      color: #fff;
      font-size: 20px;
      text-decoration: none;
      margin-right: 10px;
    }
    
    .contact-principal {
      margin-top: 40px;
      padding: 20px;
      background-color: #000;
      color: #fff;
    }
    
    .contact-principal h2 {
      font-weight: bold;
      font-size: 24px;
      margin-bottom: 10px;
      color: #fff;
    }
    
    .contact-principal p {
      margin-bottom: 10px;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>iLex Public School</h1>
  </header>
  
  <div class="container">
    <div class="options">
      <ul>
        <li><a href="#admissions">Admissions</a></li>
        <li><a href="#examinations">Examinations</a></li>
        <li><a href="#results">Results</a></li>
        <li><a href="file:///C:/Users/admin/Desktop/teachers%20corner.html">Teacher's Corner</a></li>
      </ul>
    </div>
    
    <section id="admissions">
      <h2>Admissions</h2>
      <p>Apply for admission to iLex Public School by clicking the link below:</p>
      <div class="link-container">
        <a href="file:///C:/Users/admin/Desktop/admission.html">Admission Form</a>
      </div>
    </section>
    
    <section id="examinations">
      <h2>Examinations</h2>
      <p>Stay updated with our examination schedule. Prepare yourself for upcoming tests and excel in your studies.</p>
    </section>
    
    <section id="results">
      <h2>Results</h2>
      <p>Check your examination results online. We believe in providing transparent and accurate assessments.</p>
    </section>
    
    <section id="teacher-corner">
      <h2>Teacher's Corner</h2>
      <div class="link-container">
        <a href="file:///C:/Users/admin/Desktop/teachers%20corner.html">Teacher's Corner Page</a>
      </div>
    </section>
    
    <section class="contact-principal">
      <h2>Contact Principal</h2>
      <p>Contact our principal for any inquiries or concerns:</p>
      <p>Telephone: 9631909721</p>
    </section>
  </div>
  
  <footer>
    <p>&copy; 2023 iLex Public School. All rights reserved.</p>
  </footer>
  
  <div class="background-animation"></div>
</body>
</html>
# ilex

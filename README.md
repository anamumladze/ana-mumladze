/* სერტიფიკატების სექცია */
.certificates {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 50px 20px;
}

.certificates h1 {
  font-size: 2.5rem;
  margin-bottom: 40px;
}

/* სერტიფიკატების სია */
.certificate-list {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 30px;
  max-width: 1000px;
  margin: 0 auto;
}

/* თითოეული სერტიფიკატი */
.certificate-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* სერტიფიკატის სურათი */
.certificate-img {
  width: 100%;
  height: auto;
  max-width: 200px;
  border-radius: 8px;
  margin-bottom: 15px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* სერტიფიკატზე მაუსის გაჩენისას */
.certificate-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* სურათის დარუტვა */
.certificate-img:hover {
  transform: scale(1.1);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* სერტიფიკატის ინფო */
.certificate-info h2 {
  font-size: 1.5rem;
  margin: 10px 0;
}

.certificate-info p {
  font-size: 1rem;
  color: #777;
}

.certificate-info a {
  font-size: 1rem;
  color: #0077b6;
  text-decoration: none;
}

.certificate-info a:hover {
  text-decoration: underline;
}

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ჩემს შესახებ | ანა მუმლაძე</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>

  <main>
    <section class="about">
      <h2>ჩემს შესახებ:</h2>
      <p>მე ვარ ანა მუმლაძე, გადავდივარ 11-ე კლასში. ტექნოლოგიები და ვებდიზაინი ყოველთვის მაინტერესებდა.აქამდე შეხება პროგრამირებასთნ მხოლოდ c++-ის სწავლის დროს მქონდა. ასევე გეოლაბში გავიარე UI/UX დიზაინის კურსი. ამ ორი საკითხის გამაერთიანებლად ეს კურსი მიმაჩნია ამითმაც დავინტერესდი და დავრეგისტრირდი. ამ კურსმა მასწავლა HTML-ის და CSS-ის საფუძვლები, რაც საშუალებას მაძლევს დამოუკიდებლად შევქმნა მარტივი საიტები.</p>
    </section>
  </main>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისის ლოგო" width="100" />
    </a>
    <p>© 2025 ანა მუმლაძე</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ნამუშევრები | ანა მუმლაძე</title>
  <link rel="stylesheet" href="style.css"> 
</head>
<body>

  <header>
    <nav>
      <ul>
        <li><a href="index.html">მთავარი</a></li>
        <li><a href="about.html">ჩემს შესახებ</a></li>
        <li><a href="projects.html">ნამუშევრები</a></li>
        <li><a href="contact.html">კონტაქტი</a></li>
        <li><a href="certificates.html">სერთიფიკატები</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="projects">
      <h1>ჩემი ნამუშევრები</h1>

      <div class="project-list">
       
        <div class="project-item">
          <img src="project1.jpg" alt="ნამუშევარი 1" class="project-img">
          <div class="project-info">
            <h2>ვებ-დიზაინის პროექტი</h2>
            <p>ტექნოლოგიები: HTML, CSS, JavaScript</p>
            <a href="project1.html" target="_blank">იხილე ნამუშევარი</a>
          </div>
        </div>

       
        <div class="project-item">
          <img src="project2.jpg" alt="ნამუშევარი 2" class="project-img">
          <div class="project-info">
            <h2>ონლაინ მაღაზიის დიზაინი</h2>
            <p>ტექნოლოგიები: HTML, CSS, React</p>
            <a href="project2.html" target="_blank">იხილე ნამუშევარი</a>
          </div>
        </div>

      </div>
    </section>
  </main>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="tbc-logo.png" alt="თიბისი ლოგო" width="120">
    </a>
    <p>2025 © ანა მუმლაძე</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ანა მუმლაძე | მთავარი</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>


  
  <header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>


  <main>
    <section class="certificates">
      <h1>                           ჩემს მიერ მიღებული სერტიფიკატები</h1>

      <!-- სერტიფიკატების სია -->
      <div class="certificate-list">
        <!-- სერტიფიკატი 1 -->
        <div class="certificate-item">
          <img src="certificate1.jpg" alt="სერთიფიკატი 1" class="certificate-img">
          <div class="certificate-info">
            <h2>ფოტო-ვიდეოგრაფია</h2>
            <p>თიბისიXგეოლაბი  - 2024</p>
            <a href="C:\Users\GioPC\Downloads\7bc9c959-0970-4693-99ca-8f27d3737827.jfif" target="_blank">იხილე სერთიფიკატი</a>
          </div>
        </div>

        <!-- სერტიფიკატი 2 -->
        <div class="certificate-item">
          <img src="certificate2.jpg" alt="სერთიფიკატი 2" class="certificate-img">
          <div class="certificate-info">
            <h2>HTML/CSS კურსი</h2>
            <p>თიბისიXგეოლაბი  - 2025</p>
            
          </div>
        </div>

        <div class="certificate-item">
          <img src="certificate2.jpg" alt="სერთიფიკატი 3" class="certificate-img">
          <div class="certificate-info">
            <h2>UI/UX დიზაინი</h2>
            <p>თიბისიXგეოლაბი- 2025</p>
            
          </div>
        </div>

        <div class="certificate-item">
          <img src="certificate2.jpg" alt="სერთიფიკატი 4" class="certificate-img">
          <div class="certificate-info">
            <h2>c++</h2>
            <p>მზიური - 2025</p>
           
          </div>
        </div>

      
      </div>
    </section>
  </main>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისი ლოგო" width="120">
    </a>
    <p>2025 © ანა მუმლაძე</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>კონტაქტი | ანა მუმლაძე</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>
  <main>
    <section class="contact">
      <h2>კონტაქტი</h2>
      <p>თუ გსურთ დამიკავშირდეთ, შეგიძლიათ გამოიყენოთ ფორმა ან დამეკონტაქტოთ ჩემს სოციალური მედიის გვერდებზე.</p>

      <form action="#" method="post">
        <label for="name">სახელი:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">ელ. ფოსტა:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">მესიჯი:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" class="btn">გაგზავნა</button>
      </form>

      <div class="contact-info">
        <h3>საკონტაქტო ინფორმაცია:</h3>
        <p><strong>ელ. ფოსტა:</strong> <a href="mailto:example@email.com">mumladzeana4@email.com</a></p>
        <p><strong>Facebook:</strong> <a href="https://www.facebook.com/username" target="_blank">https://www.facebook.com/ana.mumladze.31//ana.mumladze.31</a></p>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/username" target="_blank">instagram.com/ana.mmla</a></p>
      </div>
    </section>
  </main>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისი ლოგო" width="120">
    </a>
    <p>2025 © ანა მუმლაძე</p>
  </footer>

</body>
</html>

s


 <!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ანა მუმლაძე | მთავარი</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>


  
  <header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>
      
      
      
      

  <main>
    <section class="hero">
      <h1>გამარჯობა! მე ვარ ანა მუმლაძე</h1>
      <p>მოხარული ვარ, რომ შემოხვედით ჩემს პირველ ვებსაიტზე</p>
      <a href="about.html" class="btn">გაიგე მეტი ჩემზე</a>
    </section>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისის ლოგო">
    </a>
    <p>2025 © ანა მუმლაძე</p>
  </footer>

</body>
</html>

/* საკონტაქტო ფორმის სტილი */
.contact form {
  display: grid;
  gap: 15px;
  margin-top: 30px;
}

.contact label {
  font-weight: bold;
}

.contact input, .contact textarea {
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ddd;
  font-size: 1rem;
}

.contact textarea {
  resize: vertical;
}

.contact .btn {
  padding: 12px 20px;
  background-color: #0077b6;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  cursor: pointer;
}

.contact .btn:hover {
  background-color: #005f87;
}

/* საკონტაქტო ინფომაციის განლაგება */
.contact-info {
  margin-top: 40px;
}

.contact-info h3 {
  font-size: 1.5rem;
  margin-bottom: 15px;
}

.contact-info a {
  color: #0077b6;
  text-decoration: none;
}

.contact-info a:hover {
  text-decoration: underline;
}

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ჩემი ნამუშევრები | ანა მუმლაძე</title>
  <link rel="stylesheet" href="style.css"> <!-- დაუკავშირდი სტილის ფაილს -->
</head>
<body>

  
  <header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>
      
      
      

  <main>
    <section class="projects">
      <h1>ჩემი ნამუშევრები</h1>

      <!-- ნამუშევრების სია -->
      <div class="project-list">
        
        <!-- ნამუშევარი 1 -->
        <div class="project-item">
          <img src="project1.jpg" alt="ნამუშევარი 1" class="project-img">
          <div class="project-info">
            <h2>ვებ-დიზაინის პროექტი</h2>
            <p>ტექნოლოგიები: HTML, CSS, JavaScript</p>
            <a href="file:///C:/Users/GioPC/OneDrive/Desktop/davaleba%20ana%20mumladze%20tbc/index.html" target="_blank">იხილე ნამუშევარი</a>
          </div>
        </div>

        <!-- ნამუშევარი 2 -->
        <div class="project-item">
          <img src="project2.jpg" alt="ნამუშევარი 2" class="project-img">
          <div class="project-info">
            <h2>ონლაინ მაღაზიის დიზაინი</h2>
            <p>UI/UX დიზაინი</p>
            <a href="https://www.figma.com/design/20AFfD1uv5bwMP1E2Aeh2K/ana-mumladze?node-id=64-10&t=g2Jo3ByxWy5SdERp-1" target="_blank">იხილე ნამუშევარი</a>
          </div>
        </div>

        <!-- ნამუშევარი 2 -->
        <div class="project-item">
          <img src="project2.jpg" alt="ნამუშევარი 3" class="project-img">
          <div class="project-info">
            <h2>ფოტო პორთფოლიო</h2>
            <p>ფოტო-ვიდეოგრაფია</p>
            
          </div>
        </div>

      
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="footer-container">
      <a href="https://education.tbcbank.ge/" target="_blank">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისი ლოგო" width="120">
      </a>
      <p>2025 © ანა მუმლაძე</p>
    </div>
  </footer>

</body>
</html>

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.5;
  color: #500;
}

header {
  background-color: #0077b6;
  padding: 25px;
}

nav {
  display: flex;
  justify-content: center;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  padding: 60px 20px;
  text-align: center;
  background: #caf0f8;
}

.hero h1 {
  font-size: 2.5rem;
}

.btn {
  background: #0077b6;
  color: white;
  padding: 40px 20px;
  display: inline-block;
  margin-top: 20px;
  text-decoration: none;
  border-radius: 50px;
}

.about {
  padding: 130px 200px;
  max-width: 800px;
  margin: auto;
}

footer {
  text-align: center;
  padding: 20px;
  background: #0077b6;
  color: white;
  margin-top: 40px;
}

.contact form {
  display: grid;
  gap: 15px;
  margin-top: 30px;
}

.contact label {
  font-weight: bold;
}

.contact input, .contact textarea {
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ddd;
  font-size: 1rem;
}

.contact textarea {
  resize: vertical;
}

.contact .btn {
  padding: 12px 20px;
  background-color: #0077b6;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  cursor: pointer;
}

.contact .btn:hover {
  background-color: #005f87;
}


.contact-info {
  margin-top: 40px;
}

.contact-info h3 {
  font-size: 1.5rem;
  margin-bottom: 15px;
}

.contact-info a {
  color: #0077b6;
  text-decoration: none;
}

.contact-info a:hover {
  text-decoration: underline;
}
 .contact-photo {
  display: flex;
  justify-content: center; 
  align-items: center; 
  margin-bottom: 30px;
}

.contact-photo img {
  width: 300px;
  height: 300px;
  
  border: 2px solid #0077b6; 
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0);
}
 

.certificates {
  display: flex;
  flex-direction: column;
  align-items: center;  
  justify-content: center; 
  text-align: center; 
  padding: 50px 20px;
}

.certificates h1 {
  font-size: 2.5rem;
  margin-bottom: 90px;
}


.certificate-list {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); 
  gap: 30px;
  max-width: 1000px;
  margin: 0 auto; 
}


.certificate-item {
  display: flex;
  flex-direction: column;
  align-items: center; 
  text-align: center;
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}


.certificate-img {
  width: 100%;
  height: auto;
  max-width: 200px;
  border-radius: 8px;
  margin-bottom: 15px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}


.certificate-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}


.certificate-img:hover {
  transform: scale(1.1);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}


.certificate-info h2 {
  font-size: 1.5rem;
  margin: 10px 0;
}

.certificate-info p {
  font-size: 1rem;
  color: #777;
}

.certificate-info a {
  font-size: 1rem;
  color: #0077b6;
  text-decoration: none;
}

.certificate-info a:hover {
  text-decoration: underline;
}

/* ნამუშევრების სექცია */
.projects {
  display: flex;
  flex-direction: column;
  align-items: center;  /* ცენტრში განლაგება ვერტიკალურად */
  justify-content: center; /* ცენტრში განლაგება ჰორიზონალურად */
  text-align: center; /* ტექსტის ცენტრირება */
  padding: 50px 20px;
}

.projects h1 {
  font-size: 2.5rem;
  margin-bottom: 40px;
}

/* ნამუშევრების სია */
.project-list {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* ტაბლეტისა და მობილური მოწყობილობებისთვის ადაპტირება */
  gap: 30px;
  max-width: 1000px;
  margin: 0 auto; /* ცენტირება */
}

/* თითოეული ნამუშევარი */
.project-item {
  display: flex;
  flex-direction: column;
  align-items: center; /* ცენტრში განლაგება ნამუშევრის სურათისა და ტექსტის */
  text-align: center;
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* ნამუშევრის სურათი */
.project-img {
  width: 100%;
  height: auto;
  max-width: 200px;
  border-radius: 8px;
  margin-bottom: 15px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* ნამუშევარზე მაუსის გაჩენისას */
.project-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* სურათის დარუტვა */
.project-img:hover {
  transform: scale(1.1);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* ნამუშევრის ინფო */
.project-info h2 {
  font-size: 1.5rem;
  margin: 10px 0;
}

.project-info p {
  font-size: 1rem;
  color: #777;
}

.project-info a {
  font-size: 1rem;
  color: #0077b6;
  text-decoration: none;
}

.project-info a:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  background-color: #0077b6; /* ლურჯი ფონდი */
  padding: 30px 0;
  text-align: center;
  color: #fff;
}

.footer-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

footer a {
  margin-bottom: 10px;
}

footer img {
  max-width: 120px;
  margin-bottom: 15px;
}

footer p {
  font-size: 1rem;
  color: #fff;
}


<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>კონტაქტი | ანა მუმლაძე</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav>
      <a href="index.html">მთავარი</a>
      <a href="about.html">ჩემს შესახებ</a>
      <a href="projects.html">ნამუშევრები</a>
      <a href="contact.html">კონტაქტი</a>
      <a href="certificates.html">სერთიფიკატები </a>
    </nav>
  </header>
  <main>
    <section class="cprojects">
      <h2>ჩემი ნამუშევრები</h2>
      <p>თუ გსურთ დამიკავშირდეთ, შეგიძლიათ გამოიყენოთ ფორმა ან დამეკონტაქტოთ ჩემს სოციალური მედიის გვერდებზე.</p>

      <form action="#" method="post">
        <label for="name">სახელი:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">ელ. ფოსტა:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">მესიჯი:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" class="btn">გაგზავნა</button>
      </form>

      <div class="contact-info">
        <h3>საკონტაქტო ინფორმაცია:</h3>
        <p><strong>ელ. ფოსტა:</strong> <a href="mailto:example@email.com">mumladzeana4@email.com</a></p>
        <p><strong>Facebook:</strong> <a href="https://www.facebook.com/username" target="_blank">https://www.facebook.com/ana.mumladze.31//ana.mumladze.31</a></p>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/username" target="_blank">instagram.com/ana.mmla</a></p>
      </div>
    </section>
  </main>

  <footer>
    <a href="https://education.tbcbank.ge/" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSijqghtTLCaZUPIQNdpgvfJw64wHX8YEkGQQ&s" alt="თიბისი ლოგო" width="120">
    </a>
    <p>2025 © ანა მუმლაძე</p>
  </footer>

</body>
</html>


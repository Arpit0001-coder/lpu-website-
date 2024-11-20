# lpu-website-
create a website using html and css .
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>L.P.U</title>
  </head>
  <link rel="shortcut icon" type="x-icon" href="download.png" />
  <link rel="stylesheet" href="style.css" />
  <body>
    <nav class="navbar h-nav-resp background">
      <ul class="nav-list v-class-resp">
        <div class="logo"><img src="download.png" alt="LOGO" /></div>
        <li><a href="#"> Home</a></li>
        <li><a href="#about"> About</a></li>
        <li><a href="#infrastructure">Infrastructure </a></li>
        <li><a href="#Affiliation">Affiliation </a></li>
        <li><a href="#contact"> Contact Us</a></li>
      </ul>
      <div class="rightnav v-class-resp">
        <input
          type="text"name="search"id="search"placeholder="search"/><button class="btn btn-sn">Search</button>
      </div>
      <div class="burger">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
      </div>
    </nav>

    <section class="background firstsection">
      <div class="box-main">
        <div class="firsthalf">
          <p class="text-big">THE FUTURE OF EDUCATION IS HERE</p><hr>
          <p class="text-small">
            UNIVERSITY WITH BEST PLACEMENTS
From Google to Microsoft, LPU Students are working with top brands at packages of over Rs. 1 Crore
          </p>
          <hr>
          <div class="buttons">
            <a href="https://admission.lpu.in/" target="_blank"> <button class="btn"> ADMISSION</button></a>
           <a href="https://www.youtube.com/c/LPUOnYoutube" target="_blank" > <button class="btn">WATCH VIDEO</button></a>
          </div>
        </div>
        <div class="secondhalf">
          <img src="download.png" alt="LOGO" />
        </div>
      </div>
    </section>
    
    </section>
    <section class="section boy section-left" id="about">
      <div class="paras">
        <p class="sectiontag text-big">ABOUT US</p><hr>
        <p class="sectiontag text-small">
          Lovely Professional University (LPU) is a private state university located in Chaheru, Phagwara,  Punjab, India. The university was established in 2005 by Lovely International Trust, under The Lovely Professional University Act, 2005 (Punjab Act 25 of 2005) and started operation in 2006.

          The university has 45+ teaching and research departments at the campus located at Chaheru, Phagwara, Punjab and more than 360+ Programme in various undergraduate, post-graduate and doctorate degrees in various disciplines including engineering,agricultural science, legal studies,management, computer sciences, education, media studies, animation and multimedia, tourism, biotechnology, architecture, pharma sciences,commerce, liberal arts and basic sciences
        </p>
        <hr>
      </div>
      <div class="thumbnail">
        <img src="https://smapse.com/storage/2021/07/1-13.jpg" alt="LOGO" class="imgFluid" />
      </div>
    </section>
    <section class="section  boy" id="infrastructure">
      <div class="paras">
        <p class="sectiontag text-big">INFRASTRUCTURE</p><hr>
        <p class="sectiontag text-small">
          The university campus on the Jalandhar-Delhi GT Road Phagwara is spread over 600 acres[4] in Chaheru Village. The university campus hosts academic blocks, a cricket stadium, LPU student centre with student-run shops, restaurants and a hotel, landscaped gardens, central library, laboratories, Mac Lab, Aviation Lab, open air theatre, student residences, university hospital, in-house laundry, a football field, snooker lounge, roller skating rink, in-house bowling complex, gym, university shopping mall, over 5 banks and 55 ATMs within the campus, Western Union Money Transfer, over 300 food kiosks, exhibition centre, fire department, and ambulance service. It is manned by over 400 full time security officials and over 3600 CCTV cameras.
        </p>
        <hr>
      </div>
      <div class="thumbnail">
        <img src="https://qph.fs.quoracdn.net/main-qimg-0769d40d28d49f1d9d1584f50037a34d-lq" alt="LOGO" class="imgFluid" />
      </div>
    </section>
    <section class="section boy section-left" id="Affiliation">
      <div class="paras">
        <p class="sectiontag text-big">AFFILIATION</p><hr>
        <p class="sectiontag text-small">
          LPU is affiliated with the University Grants Commission, the National Council for Teacher Education and the Council of Architecture and approved by the Pharmacy Council of India. It is also a member of the Association of Indian Universities (AIU).

          LPU Law programs such as LL.B, B.A.LL.B (Hons.), and BBA LL.B (Hons.) are recognized by the Bar Council of India
          
          LPU's School of Agriculture is accredited by the Indian Council of Agricultural Research (ICAR). Internationally, LPU is accredited by the Accreditation Council for Business Schools and Programs (ACBSP) and a member of the Association of Commonwealth Universities (ACU). The distance education programmes are approved by the Distance Education Bureau (DEB).
        </p><hr>
      </div>
      <div class="thumbnail">
        <img src="AFFILIATION.jpg" alt="LOGO" class="imgFluid" />
      </div>
    </section>
    <section class="contact " id="contact">
      <h2 class="text-center">Contact Us</h2>
      <div class="form">
        <input class="form-input"type="text"name="name"id="name"placeholder="Enter your name"/>
        <input class="form-input"  type="text"phone="phone"id="phone"placeholder="Enter your number"/>
        <input class="form-input"type="text"email="email"id="email"placeholder="Enter your email"/>
        <textarea class="form-input"name="text"id="text"cols="30"rows="10"placeholder="Elaborate your concern">Elaborate your concern</textarea>
        <button class="btn  btn-sn btn-dark">Submit</button>
      </div>
    </section>
    <footer class="background">
      <p class="text-footer">
        Copyright &copy; 2027 LPU.com-all rights are reserved</p></footer>
<script src="JS/resp.js"></script>
</body>
</html>

CSS.
* {
  margin: 0;
  padding: 0;
}
html{
  scroll-behavior: smooth;
}
.logo img {
  display: flex;
  width: 30%;
  border: 2px solid black;
  border-radius: 50%;
}
.logo {
  display: flex;
  width: 20%;
  justify-content: center;
  align-items: center;
}
.navbar {
  display: flex;
  background-color: rgb(138, 135, 135);
  align-items: center;
  justify-content: center;
  position: sticky;
  top: 0;
  cursor: pointer;
}
.nav-list {
  display: flex;
  width: 70%;
}

.nav-list li {
  list-style: none;
  padding: 26px 30px;
}

.nav-list li a {
  text-decoration: none;
  color: white;
  font-size: 20px;
}
.nav-list li a:hover {
  color: grey;
}
.rightnav {
  width: 30%;
  text-align: right;
  padding: 0 23px;
}
#search {
  padding: 5px;
  font-size: 17px;
  border: 2px solid grey;
  border-radius: 9px;
}
.background {
  background: rgba(0, 0, 0, 0.7) url(https://pbs.twimg.com/media/FO8JErYUYAItSvc.jpg);
  background-size: cover;
  background-blend-mode: darken;
}
.box-main {
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  max-width: 50%;
  margin: auto;
  height: 75%;
}
.firstsection {
  height: 90vh;
}
.firsthalf {
  width: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.secondhalf {
  width: 30%;
}
.secondhalf img {
  width: 70%;
  border: 4px solid white;
  border-radius: 150px;
  display: block;
  margin: auto;
}
.text-big {
  font-size: 30px;
  color: #f50000;
  padding: 20px 0px;
  
}
.text-small {
  font-size: 26px;
  padding: 20px 0px;
}
.btn {
  padding: 8px 20px;
  margin: 7px 3px;
  border: 2px solid white;
  border-radius: 8px;
  background: none;
  color: white;
  cursor: pointer;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
.btn-sn {
  padding: 6px 10px;
  vertical-align: middle;
  font-size: 16px;
  
}
.section {
  /* background: url(../IMG/naruto.jpg); */
  /* height: 400px; */
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin: auto;
  max-width: 80%;
  padding: 10px ;
}
.section-left {
  flex-direction: row-reverse;
}
.paras {
  padding: 0px 69px;
}
.thumbnail img{
  width: 400px;
  height: 320px;
  border: 2px solid black;
  border-radius: 10%;
  margin-top: 19px;
}
.contact {
  background-color: rgb(3 137 155 / 72%);
  /* height: 90vh; */
  height: 586px;
}
.text-center {
  text-align: center;
  padding-top: 30px;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 35px;
  padding-top: 30px;
}
.btn-dark {
  color: black;
    border: 2px solid #020202;
    padding: 8px 30px;
    border-radius: 12px;
    cursor: pointer;
    background: #e9ba0e;
}
.form {
  max-width: 62%;
  margin: 25px auto;
}
.form-input {
  width: 100%;
  font-size: 14px;
  border: 2px solid grey;
  border-radius: 6px;
  margin: 14px 0;
  padding: 6px 0px;
}
.text-footer
{
  text-align: center;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
 padding: 30px 0;
 color: white;


}

.burger
{
  display: none;
position: absolute;
cursor: pointer;
right: 5%;
top: 15px;
}
.line
{
  width: 33px;
  background-color: white;
  height: 4px;
  margin: 5px 3px;
}


  

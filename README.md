
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;1,100;1,300&display=swap');
/* Rest values css default*/
* {
  margin: 0;
  padding: 0;
}


 .wrapper {
  margin-right: auto; /* 1 */
  margin-left:  auto; /* 1 */
  max-width: 960px; /* 2 */
  padding-right: 10px; /* 3 */
  padding-left:  10px; /* 3 */
}

/* HERO SECTION */
.hero {
  margin-top: 30px;
  margin-bottom: 30px;
  font-family: 'Roboto', sans-serif;
}

.social li {
  display: inline-block;
}

.social li a {
  font-size: 30px;
  color: #FFFFFF;
  display: block;
}

.social li a i {
  display: block;
  margin: 10px;
  padding: 10px;
}

.hero h1 {
  color: #FFFFFF;
  font-size: 35px;
  font-weight: 900;
}

.hero p {
  color: #FFFFFF;
  font-size: 26px;
  line-height: 40px;
  font-weight: 300;
}

.hero img {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  border: 10px solid #24273B;
}

.card {
  width: 100%;
  height: 460px;
  box-shadow: 5px 5px 5px 5px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
  background-color: #24273B;
}

.card-header {
  background-color: #1F2235;
  width: 100%;
  height: 160px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.card-content{
  position: relative;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  top: -140px;
}
/* HERO SECTION */
</style>

<section class="hero wrapper">
  <div class="card">
    <div class="card-header"></div>
      <div class="card-content">
        <figure>
          <img src="https://avatars2.githubusercontent.com/u/21282810?s=460&u=b2242f78c5f3eb9361915668405b1f83ddc4218d&v=4" alt="Jose Luis Campos Bautista">
        </figure>
        <h1>I am Jose Luis Campos Bautista</h1>
        <p>A passionate software developer from México</p>
        <ul class="social">
          <li><a href="https://www.linkedin.com/in/bautistaj20" target="_blank"><i class="fab fa-linkedin-in"></i></a></li>
          <li><a href="https://medium.com/@bautistaj20"  target="_blank"><i class="fab fa-medium-m"></i></a></li>
          <li><a href="https://github.com/bautistaj" target="_blank"><i class="fab fa-github"></i></a></li>
        </ul>
        </div>
      </div>
</section>
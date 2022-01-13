<template>
  <section class="top">
    <label>Eventor</label>
    <div class="widget">
      <nav>
        <ul class="navbar">
          <li><a href="#home">Home</a></li>
          <li><a href="#about-us">About Us</a></li>
          <li><a href="#service">Service</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
      <div class="register">
        <button class="login">Login</button>
        <div class="line"></div>
        <button class="signup">Sign Up</button>
      </div>
    </div>
  </section>

  <section id="home">
    <img src="https://wallpaperaccess.com/full/2489665.jpg" alt="" />
  </section>

  <section id="about-us">
    <h2>About Us</h2>
    <p class="info">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt nisi,
      error vero pariatur optio doloremque porro quo tempore? Doloremque
      accusantium ea sint reprehenderit alias eaque porro ex delectus vel, ipsa
      quasi corrupti fugit error ducimus! Dolores quasi sapiente at ipsum. Error
      incidunt architecto eveniet laudantium at sit, inventore nihil nobis iusto
      quisquam libero veniam reiciendis perferendis obcaecati quo fugit maiores
      iure tenetur, vitae beatae recusandae provident? Laudantium quia facere
      nulla inventore iste accusamus porro consequuntur aspernatur amet,
      reiciendis sed quidem libero perferendis voluptatum itaque ullam placeat
      recusandae. Voluptatum quidem magnam vero commodi porro repudiandae error
      autem voluptas assumenda tenetur. Sit?
    </p>
  </section>

  <section id="service">
    <h2>Services</h2>
    <div class="card-deck">
      <div class="card">
        <header>
          <h3>Host an Event</h3>
        </header>
        <div>
          <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quisquam
            molestiae, vel accusantium rerum sapiente odit quas asperiores eaque
            illo hic mollitia quae nostrum similique doloribus! Porro aliquid a
            quo fuga!
          </p>
          <button>Create Event</button>
        </div>
      </div>
      <div class="card">
        <header>
          <h3>Browse Event</h3>
        </header>
          <div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quisquam
              molestiae, vel accusantium rerum sapiente odit quas asperiores
              eaque illo hic mollitia quae nostrum similique doloribus! Porro
              aliquid a quo fuga!
            </p>
            <button>Look for events</button>
          </div>
      </div>
      <div class="card">
        <header>
          <h3>Utility</h3>
          
        </header>
        <div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quisquam
              molestiae, vel accusantium rerum sapiente odit quas asperiores
              eaque illo hic mollitia quae nostrum similique doloribus! Porro
              aliquid a quo fuga!
            </p>
            <button>Check it out</button>
          </div>
      </div>
    </div>
  </section>

  <footer id="contact"></footer>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  scroll-behavior: smooth;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
}

/*---------------------------------------------------------------------------------------------------------*/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Qwitcher+Grypen&family=Ubuntu:wght@400;500;700&display=swap");
.top {
  height: 50px;
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  margin-bottom: 20px;
  align-items: center;
  background-color: white;
}

.top label {
  font-family: "Qwitcher Grypen", cursive;
  font-size: 70px;
}

.top .widget {
  display: flex;
  flex-direction: row;
}

.top .navbar {
  list-style: none;
  width: fit-content;
  height: fit-content;
}

.top .navbar li {
  float: left;
  margin-right: 50px;
}

.top .navbar li a {
  text-decoration: none;
  color: #213b4e;
  transition: 0.5s ease-in;
  font-size: 17px;
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  transition: 0.5s;
}

.top .navbar li a:hover {
  font-size: 18px;
}

.top .register {
  float: right;
  height: 100%;
  display: flex;
}

.register .line {
  height: 40px;
  margin: 5px 0;
  border-left: 0.09px solid #d1cccc;
}

.top .register .login,
.signup {
  width: 100px;
  height: 40px;
  margin: 5px;
  border: none;
  border-radius: 11px;
  cursor: pointer;
  font-weight: 700;
  border: 1px solid #213b4e;
}

.login {
  color: #fff;
  background-color: #213b4e;
  transition: 0.5s;
}

.signup {
  color: #213b4e;
  background-color: #f8f0f0;
  transition: 0.5s;
}

.signup:hover,
.login:hover {
  transform: scale(1.04);
  transition: 0.35s ease-in-out;
}

/*---------------------------------------------------------------------------------------------------------*/
#home {
  width: 100%;
  margin-top: 5%;
  height: 500px;
  text-align: center;
}

#home img {
  width: 90%;
  height: 100%;
}

#about-us {
  width: 100%;
  height: 300px;
  text-align: center;
  font-style: italic;
}

#service {
  width: 100%;
  height: 500px;
  text-align: center;
  display: flex;
  flex-direction: column;
}

#service .card-deck {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

#service .card-deck .card {
  width: 25%;
  height: 90%;
  display: flex;
  flex-direction: column;
  justify-content: space-ev;
  border-radius: 2%;
  border: 1px solid #213b4e;
}

#service .card-deck .card header {
  color: #fff;
  height: 14%;
  background-color: #213b4e;
}

#service .card-deck .card div {
  width: 90%;
  height: 86%;
  text-align: justify;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}

#contact {
  width: 100%;
  height: 86%;
  height: 250px;
  background-color: #213b4e;
}
</style>
 
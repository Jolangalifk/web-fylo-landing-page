<script setup>
</script>

<template>
  <body>
    <header>
      <button class="head-logo">
        <div id="logo-image">
          <img src="@/assets/icon/logo.svg" alt="">
        </div>
      </button>
      <nav>
        <ul>
          <li>Features</li>
          <li>Team</li>
          <li>Sign In</li>
        </ul>
      </nav>
    </header>
    <main>
      <article class="preview">
        <div class="preview-bg">
          <img src="@/assets/image/bg-curvy-desktop-3.svg" alt="">
        </div>
        <div class="preview-image">
          <img src="@/assets/image/illustration-intro.png" alt="">
        </div>
        <div class="preview-description">
          <h1>All your files in one secure location, accessible anywhere.</h1>
          <p>Fylo stores all your most important files in one secure location. Access them wherever you need, share and
            collaborate with friends family, and co-workers.</p>
          <button>Get Started</button>
        </div>
      </article>
      <article class="feature">
        <div class="feature-grid">
          <div class="feature-description">
            <div class="feature-image">
              <img src="@/assets/icon/icon-access-anywhere.svg" alt="">
            </div>
            <h1>Access your files, anywhere</h1>
            <p>The ability to use a smartphone, tablet, or computer to access your account means your files follow you
              everywhere.</p>
          </div>
          <div class="feature-description">
            <div class="feature-image">
              <img src="@/assets/icon/icon-security.svg" alt="">
            </div>
            <h1>Security you can trust</h1>
            <p>2-factor authentication and user-controlled encryption are just a couple of the security features we allow
              to help secure your files.</p>
          </div>
          <div class="feature-description">
            <div class="feature-image">
              <img src="@/assets/icon/icon-collaboration.svg" alt="">
            </div>
            <h1>Real-time collaboration</h1>
            <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email
              attachments required.</p>
          </div>
          <div class="feature-description">
            <div class="feature-image">
              <img src="@/assets/icon/icon-any-file.svg" alt="">
            </div>
            <h1>Store any type of file</h1>
            <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types
              to be securely stored and shared.</p>
          </div>
        </div>
      </article>
      <article class="promotion">
        <div class="promotion-image">
          <img src="@/assets/image/illustration-stay-productive.png" alt="">
        </div>
        <div class="promotion-description">
          <h1>Stay productive, wherever you are</h1>
          <p>Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage
            needs.</p>
          <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email
            attachments required.</p>
          <div class="promotion-link">
            <a>See how Fylo works</a>
            <img src="@/assets/icon/icon-arrow.svg" alt="">
          </div>
        </div>
      </article>
      <article class="quotes">
        <div class="quotes-bg">
          <img src="@/assets/image/bg-quotes.png" alt="">
        </div>
        <div class="quotes-description">
          <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
            become a well-oiled collaboration machine.</p>
          <div class="quotes-author">
            <div class="quotes-author-image">
              <img src="@/assets/image/profile-1.jpg" alt="">
            </div>
            <div class="quotes-author-description">
              <h1>Satish Patel</h1>
              <p>Founder & CEO, Huddle</p>
            </div>
          </div>
        </div>
        <div class="quotes-description">
          <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
            become a well-oiled collaboration machine.</p>
          <div class="quotes-author">
            <div class="quotes-author-image">
              <img src="@/assets/image/profile-2.jpg" alt="">
            </div>
            <div class="quotes-author-description">
              <h1>Satish Patel</h1>
              <p>Founder & CEO, Huddle</p>
            </div>
          </div>
        </div>
        <div class="quotes-description">
          <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
            become a well-oiled collaboration machine.</p>
          <div class="quotes-author">
            <div class="quotes-author-image">
              <img src="@/assets/image/profile-3.jpg" alt="">
            </div>
            <div class="quotes-author-description">
              <h1>Satish Patel</h1>
              <p>Founder & CEO, Huddle</p>
            </div>
          </div>
        </div>
      </article>
    </main>
    <footer class="footer">
      <div class="get-access">
        <h1>Get early access today</h1>
        <p>it only takes a minute to sign up and our free starter tier is extremely generous. if you have any questions,
          our support team would be happy to help you.</p>
        <form action="#">
          <input type="email" name="email" placeholder="email@example.com">
          <button>
            <p>Get Started For Free</p>
          </button>
        </form>
      </div>
      <div class="footer-image">
        <img src="@/assets/icon/logo.svg" alt="">
      </div>
      <div class="footer-link">
        <div class="footer-description">
          <div class="footer-contact-image">
            <img src="@/assets/icon/icon-location.svg" alt="">
          </div>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua</p>
        </div>
        <div class="footer-contact-description">
          <div class="footer-contact">
            <div class="footer-contact-image">
              <img src="@/assets/icon/icon-phone.svg" alt="">
            </div>
            <p>+1-543-123-4567</p>
          </div>
          <div class="footer-contact">
            <div class="footer-contact-image">
              <img src="@/assets/icon/icon-email.svg" alt="">
            </div>
            <p>example@fylo.com</p>
          </div>
        </div>
        <div class="footer-description-anu">
          <ul>
            <li>About Us</li>
            <li>Jobs</li>
            <li>Press</li>
            <li>Blog</li>
          </ul>
        </div>
        <div class="footer-description-anu">
          <ul>
            <li>Contact Us</li>
            <li>Terms</li>
            <li>Privacy</li>
          </ul>
        </div>
        <div class="footer-description-anu">
          <div class="footer-description-social-media">
            <div class="social-media-image">
              <img src="@/assets/icon/facebook-logo.svg" alt="">
            </div>
            <div class="social-media-image">
              <img src="@/assets/icon/twitter-logo.svg" alt="">
            </div>
            <div class="social-media-image">
              <img src="@/assets/icon/instagram-logo.svg" alt="">
            </div>
          </div>
        </div>
      </div>
    </footer>
  </body>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
}


body {
  background-color: #181E2A;
  font-family: 'Poppins', sans-serif;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 5rem;
  background-image: url('../assets/image/bg-curvy-desktop-3.svg');
}

.head-logo {
  border: none;
  background-color: transparent;
  cursor: pointer;
}

.head-logo #logo-image {
  width: 10rem;
  object-fit: cover;
}

nav {
  width: 20%;
}

nav ul {
  display: flex;
  list-style: none;
  justify-content: space-between;
}

nav ul li {
  font-size: 1.2rem;
  cursor: pointer;
  font-family: 'raleway', sans-serif;
  text-decoration: none;
  background-image: linear-gradient(to right,
      #43B1D2,
      #43B1D2 50%,
      #ffffff 50%);
  background-size: 200% 100%;
  background-position: -100%;
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
  transition: all 0.3s ease-in-out;
}

nav ul li:hover {
  font-weight: bold;
  background-position: 0;
}

nav ul li:before {
  content: '';
  background: #ffffff;
  display: block;
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 0;
  height: 3px;
}

nav ul li:hover::before {
  width: 100%;
}

main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: fit-content;
}

.preview {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 100%;
  padding-bottom: 5rem;
  overflow: hidden;
}

.preview-image {
  width: 50%;
  margin-top: 4rem;
  margin-bottom: 2rem;
}

.preview-image img {
  width: 100%;
}

.preview-description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 50%;
}

.preview-description h1 {
  font-size: 2.5rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 2rem;
  font-family: 'Raleway', sans-serif;
}

.preview-description p {
  width: 75%;
  font-size: 1.2rem;
  font-weight: 300;
  text-align: center;
  margin-bottom: 2rem;
  font-family: 'Raleway', sans-serif;
}

.preview-description button {
  width: 40%;
  padding: 1rem 2rem;
  border: none;
  border-radius: 2rem;
  background-color: #43B1D2;
  font-size: 1rem;
  font-weight: 500;
  cursor: pointer;
}

.preview-description button:hover {
  background-color: #A7EAFF;
  font-weight: 600;
  transition: 1s;
}

.preview-bg {
  width: 140%;
  height: 100%;
  position: absolute;

}

.preview-bg img {
  height: 100%;
  object-fit: cover;
}


.feature {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.feature-grid {
  display: grid;
  grid-template-columns: auto auto;
  width: 80%;
  padding: 5rem 0;
  padding-top: 0;
  margin-top: 5rem;
}

.feature-description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
}

.feature-description .feature-image {
  width: 15%;
  height: 20%;
  margin-bottom: 3rem;
  display: flex;
  align-items: center;
}

.feature-description .feature-image img {
  object-fit: cover;
  width: 100%;
}

.feature-description h1 {
  font-size: 1.5rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 0.5rem;
  font-family: 'Raleway', sans-serif;
}

.feature-description p {
  width: 80%;
  font-size: 1rem;
  font-weight: 300;
  text-align: center;
  margin-bottom: 2rem;
  font-family: 'Raleway', sans-serif;
}

.promotion {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 70%;
  margin-bottom: 10rem;
  padding-left: 5rem;
  padding-right: 5rem;
}

.promotion-image {
  width: 50%;
}

.promotion-image img {
  width: 100%;
}

.promotion-description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 50%;
  padding: 5rem;
  padding-right: 0;
}

.promotion-description h1 {
  width: 70%;
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
  font-family: 'Raleway', sans-serif;
}

.promotion-description p {
  width: 100%;
  font-size: 1.2rem;
  font-weight: 300;
  margin-bottom: 1rem;
  font-family: 'Raleway', sans-serif;
}

.promotion-link {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 35%;
  margin: 0 -.25rem;
  padding: 0 .25rem;
  transition: color .3s ease-in-out, box-shadow .3s ease-in-out;
  box-shadow: inset 0 0 0 0 #43B1D2;
}

.promotion-link {
  background:
    linear-gradient(to right,
      rgba(100, 200, 200, 1),
      rgba(100, 200, 200, 1)),
    linear-gradient(to right,
      rgba(255, 0, 0, 1),
      rgba(255, 0, 180, 1),
      rgba(0, 100, 200, 1));
  background-size: 100% 3px, 0 3px;
  background-position: 100% 100%, 0 100%;
  background-repeat: no-repeat;
  transition: background-size 400ms;
}

.promotion-link:hover {
  background-size: 0 3px, 100% 3px;
  cursor: pointer;
}

.promotion-link a {
  font-size: 1.2rem;
  font-weight: 500;
  text-decoration: none;
  color: #ffffff;
  font-family: 'Raleway', sans-serif;
}

.promotion-link a:hover {
  font-weight: bold;
  transition: 0.5s;
}

.promotion-link img {
  width: 10%;
}

.quotes {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 80%;
  margin-bottom: 25rem;
}

.quotes-bg {
  width: 5%;
  position: absolute;
  bottom: 93%;
  right: 96%;
}

.quotes-bg img {
  width: 100%;
}

.quotes-description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 31%;
  padding: 2rem;
  background-color: #21293C;
  border-radius: 5px;
}

.quotes-description p {
  width: 100%;
  font-size: 0.9rem;
  font-weight: 300;
  margin-bottom: 1rem;
  font-family: 'Raleway', sans-serif;
}

.quotes-author {
  display: flex;
  align-items: center;
  width: 100%;
}

.quotes-author-image {
  width: 10%;
  margin-right: 1rem;
}

.quotes-author-image img {
  width: 100%;
  border-radius: 50%;
}

.quotes-author-description {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.quotes-author-description h1 {
  font-size: 0.8rem;
  font-weight: 600;
  margin-top: 0.5rem;
  font-family: 'Raleway', sans-serif;
}

.quotes-author-description p {
  font-size: 0.6rem;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
}

.footer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  background-color: #0C1524;
  padding-top: 10rem;
}

.get-access {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 60%;
  padding: 3rem;
  background-color: #21293C;
  border-radius: 10px;
  position: absolute;
  bottom: 75%;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 5px 20px;
}

.get-access h1 {
  font-size: 2.5rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 2rem;
  font-family: 'Raleway', sans-serif;
}

.get-access p {
  width: 100%;
  font-size: 1.2rem;
  font-weight: 300;
  text-align: center;
  margin-bottom: 2rem;
  font-family: 'Raleway', sans-serif;
}

.get-access form {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.get-access form input {
  width: 70%;
  padding: 1rem;
  border: none;
  border-radius: 2rem;
  margin-right: 1rem;
  font-size: 1rem;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
  color: black;
}

.get-access form button {
  width: 30%;
  border: none;
  border-radius: 2rem;
  background-color: #43B1D2;
  font-size: 1rem;
  font-weight: 500;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
}

.get-access form button:hover {
  background-color: #A7EAFF;
  font-weight: bold;
  transition: 1s;
}

.get-access form button p {
  padding: 1rem;
  margin: 0;
  font-family: 'Raleway', sans-serif;
  font-size: 1rem;
  font-weight: bold;
}

.get-access form button p:hover {
  transition: 0.5s;
}

.footer-image {
  width: 90%;
  margin-top: 5rem;
  display: flex;
}

.footer-image img {
  width: 15%;
}

.footer-link {
  display: flex;
  justify-content: space-between;
  width: 90%;
  padding: 2rem;
  margin-bottom: 3rem;
}

.footer-description {
  display: flex;
  flex-direction: row;
  width: 28%;
}

.footer-description .footer-location-image {
  width: 10%;
  margin-bottom: 1rem;
}

.footer-description p {
  width: 100%;
  font-size: 1rem;
  font-weight: 300;
  margin-bottom: 1rem;
  font-family: 'Raleway', sans-serif;
}

.footer-description-anu ul {
  list-style: none;
}

.footer-description-anu ul li {
  font-size: 1rem;
  font-weight: 300;
  margin-bottom: 1rem;
  font-family: 'Raleway', sans-serif;
}

.footer-description-anu ul li:hover {
  font-weight: bold;
  transition: 0.5s;
  cursor: pointer;
}

.footer-contact-description .footer-contact {
  display: flex;
  flex-direction: row;
}

.footer-contact-image {
  width: 20px;
  height: fit-content;
  display: flex;
  margin-right: 2rem;
  margin-bottom: 2rem;
  margin-top: 0.2rem;
}

.footer-contact-image img {
  width: 100%;
  object-fit: cover;
}

.footer-description-social-media {
  width: 100%;
  display: flex;
  justify-content: space-between;
  gap: 15px;
}

.footer-description-social-media .social-media-image {
  width: 30px;
  border: 2px solid #ffffff;
  height: fit-content;
  display: flex;
  border-radius: 50%;
  padding: 5px;
}

.footer-description-social-media .social-media-image:hover {
  background-color: #43B1D2;
  transition: 0.5s;
  cursor: pointer;
}

.footer-description-social-media .social-media-image img {
  width: 100%;
  object-fit: cover;
}

@media screen and (max-width: 768px) {
  header {
    padding: 1rem;
  }

  .head-logo #logo-image {
    width: 6rem;
    object-fit: cover;
  }

  .head-logo #logo-image img {
    width: 100%;
  }

  nav {
    text-align: center;
    width: 55%;
  }

  nav ul li {
    font-size: 1rem; 
  }

  main {
    width: 100%;
  }

  .preview {
    width: 100%;
    height: 100%;
    padding: 0;
    margin-bottom: 5rem;
  }

  .preview-image {
    width: 70%;
  }

  .preview-description {
    width: 80%;
  }

  .preview-description h1 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }

  .preview-description p {
    width: 100%;
    font-size: 1rem;
  }

  .preview-description button {
    width: 75%;
    padding: 1rem 2rem;
    border: none;
    border-radius: 2rem;
    background-color: #43B1D2;
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
  }

  .preview-description button:hover {
    background-color: #A7EAFF;
    font-weight: 500;
    transition: 1s;
  }

  .preview-bg {
    width: 170%;
    height: 75%;
    position: absolute;
  }

  .preview-bg img {
    width: 80%;
    height: 100%;
    object-fit: cover;
  }

  .feature {
    width: 100%;
  }

  .feature-grid {
    display: grid;
    grid-template-columns: auto;
    width: 100%;
    padding: 5rem 0;
    padding-top: 0;
    margin-top: 5rem;
  }

  .feature-description {
    width: 100%;
    margin-top: 0;
    margin-bottom: 3rem;
  }

  .feature-description .feature-image {
    width: 15%;
    height: 20%;
    margin-bottom: 2rem;
    display: flex;
    align-items: center;
  }

  .feature-description .feature-image img {
    object-fit: cover;
    width: 100%;
  }

  .feature-description h1 {
    font-size: 1.3rem;
    font-weight: bold;
    text-align: center;
    margin-bottom: 0.5rem;
    font-family: 'Raleway', sans-serif;
  }

  .feature-description p {
    width: 80%;
    font-size: 1rem;
    font-weight: 300;
    text-align: center;
    margin-bottom: 2rem;
    font-family: 'Raleway', sans-serif;
  }
  .promotion {
    width: 100%;
    height: 100%;
    margin-bottom: 5rem;
    padding: 0;
    display: flex;
    flex-direction: column;
  }

  .promotion-image {
    width: 80%;
    margin-bottom: 1rem;
  }

  .promotion-image img {
    width: 100%;
  }

  .promotion-description {
    width: 100%;
    padding: 2rem;
  }

  .promotion-description h1 {
    width: 100%;
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 1rem;
  }

  .promotion-description p {
    width: 100%;
    font-size: 0.9rem;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .promotion-link {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 60%;
    margin: 0 -.25rem;
    padding: 0 .25rem;
    transition: color .3s ease-in-out, box-shadow .3s ease-in-out;
    box-shadow: inset 0 0 0 0 #43B1D2;
  }

  .promotion-link {
    background:
      linear-gradient(to right,
        rgba(100, 200, 200, 1),
        rgba(100, 200, 200, 1)),
      linear-gradient(to right,
        rgba(255, 0, 0, 1),
        rgba(255, 0, 180, 1),
        rgba(0, 100, 200, 1));
    background-size: 100% 1.5px, 0 1.5px;
    background-position: 100% 100%, 0 100%;
    background-repeat: no-repeat;
    transition: background-size 400ms;
  }

  .promotion-link:hover {
    background-size: 0 3px, 100% 3px;
    cursor: pointer;
  }

  .promotion-link a {
    font-size: 1rem;
    font-weight: 400;
    text-decoration: none;
    color: #43B1D2;
    font-family: 'Raleway', sans-serif;
    margin-bottom: 0.5rem;
  }

  .promotion-link a:hover {
    font-weight: bold;
    transition: 0.5s;
  }

  .promotion-link img {
    width: 15%;
    margin-bottom: 0.5rem;
  }

  .quotes {
    width: 100%;
    margin-bottom: 20rem;
    display: flex;
    flex-direction: column;
  }

  .quotes-bg {
    width: 10%;
    position: absolute;
    bottom: 98%;
    right: 76%;
  }

  .quotes-bg img {
    width: 100%;
  }

  .quotes-description {
    width: 80%;
    padding: 2rem;
    background-color: #21293C;
    border-radius: 5px;
    margin-bottom: 2rem;
  }

  .quotes-description p {
    width: 100%;
    font-size: 0.7rem;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .quotes-author {
    display: flex;
    align-items: center;
    width: 100%;
  }

  .quotes-author-image {
    width: 10%;
    margin-right: 1rem;
  }

  .quotes-author-image img {
    width: 100%;
    border-radius: 50%;
  }

  .quotes-author-description {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .quotes-author-description h1 {
    font-size: 0.8rem;
    font-weight: 600;
    margin-top: 0.5rem;
  }

  .quotes-author-description p {
    font-size: 0.6rem;
    font-weight: 300;
  }

  .footer {
    width: 100%;
    padding-top: 15rem;
  }

  .get-access {
    width: 90%;
    padding: 2rem;
    background-color: #21293C;
    border-radius: 10px;
    position: absolute;
    bottom: 80%;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 5px 20px;
  }

  .get-access h1 {
    font-size: 1.5rem;
    font-weight: bold;
    text-align: center;
    margin-bottom: 1.5rem;
  }

  .get-access p {
    width: 100%;
    font-size: 0.9rem;
    font-weight: 300;
    text-align: center;
    margin-bottom: 1.5rem;
  }

  .get-access form {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .get-access form input {
    width: 100%;
    border: none;
    border-radius: 2rem;
    font-size: 1rem;
    font-weight: 300;
    font-family: 'Raleway', sans-serif;
    color: black;
    margin-left: 1rem;
    margin-bottom: 1.5rem;
  }

  .get-access form button {
    width: 100%;
    border: none;
    border-radius: 2rem;
    background-color: #43B1D2;
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .get-access form button:hover {
    background-color: #A7EAFF;
    font-weight: bold;
    transition: 1s;
  }

  .get-access form button p {
    padding: 1rem;
    margin: 0;
    font-family: 'Raleway', sans-serif;
    font-size: 1rem;
    font-weight: bold;
  }

  .get-access form button p:hover {
    transition: 0.5s;
  }

  .footer-image img {
    width: 50%;
    margin: 0;
    margin-bottom: 1rem;
    margin-left: 2rem;
  }

  .footer-link {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    padding: 2rem;
    margin-bottom: 3rem;
  }

  .footer-description {
    display: flex;
    flex-direction: row;
    width: 100%;
    margin-bottom: 1rem;
  }

  .footer-description .footer-location-image {
    width: 10%;
    margin-bottom: 1rem;
  }

  .footer-description p {
    width: 100%;
    font-size: 1rem;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .footer-description-anu {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin-bottom: 2rem;
  }

  .footer-description-anu ul {
    list-style: none;
  }

  .footer-description-anu ul li {
    font-size: 1rem;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .footer-description-anu ul li:hover {
    font-weight: bold;
    transition: 0.5s;
    cursor: pointer;
  }

  .footer-contact-image {
    width: 25px;
    height: fit-content;
    display: flex;
    margin-right: 2rem;
    margin-bottom: 2rem;
    margin-top: 0.2rem;
  }

  .footer-contact-image img {
    width: 100%;
    object-fit: cover;
  }

  .footer-description-social-media .social-media-image {
    width: 30px;
    border: 2px solid #ffffff;
    height: fit-content;
    display: flex;
    border-radius: 50%;
    padding: 5px;
  }

  .footer-description-social-media .social-media-image:hover {
    background-color: #43B1D2;
    transition: 0.5s;
    cursor: pointer;
  }

  .footer-description-social-media .social-media-image img {
    width: 100%;
    object-fit: cover;
  }

  .footer-link {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding: 2rem;
    padding-bottom: 0;
  }

  .footer-description .footer-location-image {
    width: 10%;
    margin-bottom: 1rem;
  }

  .footer-description p {
    width: 100%;
    font-size: 1rem;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .footer-contact-description {
    width: 100%;
    margin-bottom: 3rem;
  }

  .footer-contact-description .footer-contact {
    display: flex;
    flex-direction: row;
    height: fit-content;
  }
  .footer-contact-description .footer-contact p {
    width: 100%;
    font-size: 1rem;
    font-weight: 300;
  }

  .footer-description-social-media {
    width: 40%;
    display: flex;
    justify-content: space-between;
    gap: 15px;
    margin-left: 6rem;
  }

  .footer-description-social-media .social-media-image {
    width: 30px;
    border: 2px solid #ffffff;
    height: fit-content;
    display: flex;
    border-radius: 50%;
    padding: 5px;
  }

  .footer-description-social-media .social-media-image:hover {
    background-color: #43B1D2;
    transition: 0.5s;
    cursor: pointer;
  }

  .footer-description-social-media .social-media-image img {
    width: 100%;
    object-fit: cover;
  }

}
</style>

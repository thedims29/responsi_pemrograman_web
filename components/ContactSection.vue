<template>
  <section class="contact">
    <div id="contact">
      <h2>Contact Me</h2>
      <div id="contact-details-form">
        <div id="contact-details">
          <p><strong>Location:</strong> Sleman, Yogyakarta, Indonesia</p>
          <p><strong>Phone:</strong> +62 82-133-926-339</p>
          <p><strong>Email:</strong> dimasramadhan750@email.com</p>
        </div>
        <div id="contact-form">
          <form method="POST" action="https://formspree.io/email@email.com">
            <input type="hidden" name="_subject" value="Contact request from personal website" />
            <input type="email" name="_replyto" placeholder="Your email" required>
            <textarea name="message" placeholder="Your message" required></textarea>
            <button type="submit">Send</button>
          </form>
        </div>
      </div>
      <!-- End #contact-details-form -->
    </div>
    <!-- End #contact -->
    <footer id="footer-down">
      <h2>FOLLOW US ON</h2>
      <ul class="social-icon">
        <li class="twitter hvr-pulse"><a href="https://x.com/Dimralf29/"><i class="fa fa-twitter"><img src="assets/x.png" class="logo" alt=""></i></a></li>
        <li class="instagram hvr-pulse"><a href="https://www.instagram.com/dimasralf/"><i class="fa fa-instagram"><img src="assets/ig.png" class="logo" alt=""></i></a></li>
        <li class="email hvr-pulse"><a href="#"><i class="fa fa-email"><img src="assets/gmail.png" class="logo" alt=""></i></a></li>
        <li class="tiktok hvr-pulse"><a href="https://www.tiktok.com/@dimsom6/"><i class="fa fa-email"><img src="assets/tiktok.png" class="logo" alt=""></i></a></li>
      </ul>
    </footer>
  </section>
</template>


<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 0px 0;
}

#contact {
  padding: 50px 15px;
  background: #818181;
  text-align: center;

  h2 {
    margin: 0 0 15px 0;
    color: #000000;
    font-weight: 500;
  }
}

#contact-details-form {
  padding-top: 20px;
  display: flex;
  justify-content: space-around;
  align-items: flex-start;
}

#contact-details {
  max-width: 250px;
  margin-top: 20px;
  padding-top: 20px;
  margin-right: 10px;
  text-align: left;

  p {
    margin: 0 0 10px;
    color: #000;
    font-weight: 500;
  }
}

#contact-form {
  max-width: 500px;

  input, textarea {
    display: block;
    width: 500px;
    padding: 10px;
    border-radius: 4px;
    border: none;
    margin-bottom: 10px;
    background: darken(#fff, 15%);
    color: #000000;
    transition: background 0.3s;

    &::placeholder {
      color: #fff;
    }

    &:focus {
      outline: none;
      background: darken(#fff, 25%);
    }
  }

  textarea {
    height: 150px;
    resize: none;
  }

  button {
    display: block;
    width: 100%;
    background: #fff;
    border-radius: 4px;
    padding: 5px 10px;
    border: none;
    color: #000;
    font-weight: 700;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
    transition: box-shadow 0.3s;

    &:hover {
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
    }
  }
}

#footer {
  text-align: center;
}

#footer .bg-sec h2 {
  color: #FFFFFF;
  font-size: 25px;
  font-weight: normal;
}

#footer-down {
  background: #818181;
  color: #fff;
  position: relative;
  top: 0px;
  text-align: center;
}

#footer-down h2 {
  color: #000;
  margin: 0px 0px 40px 0px;
  text-transform: none;
  padding-left: 30px;
}

#footer-down ul li {
  display: inline-block;
  margin-right: 30px;
}

#footer-down ul li a i.fa {
  color: #000;
  font-size: 22px;
  border: 2px solid #000;
  height: 50px;
  width: 50px;
  border-radius: 50px;
  padding: 25%;
}

#footer-down ul li.facebook i.fa:hover {
  color: #3b5998;
  border: 2px solid #bb0000;
}

#footer-down ul li.twitter i.fa:hover {
  color: #00aced;
  border: 2px solid #bb0000;
}

#footer-down ul li.linkedin i.fa:hover {
  color: #007bb6;
  border: 2px solid #bb0000;
}

#footer-down ul li.youtube i.fa:hover {
  color: #bb0000;
  border: 2px solid #bb0000;
}

#footer-down ul li.instagram i.fa:hover {
  color: #517fa4;
  border: 2px solid #bb0000;
}

#footer-down ul li.email i.fa:hover {
  color: #1769ff;
  border: 2px solid #bb0000;
}

.logo {
  width: 30px;
  height: 40px;
  padding-bottom: 10px;
}
</style>
<template>
<div id="footer_bg" class="footer_bg"></div>

  <div class="wrapper">
    <section class="first_screen">
      <div class="top_row">
      <v-lazy-image src="img/logo.svg" @click="logo()" class="logo_img" alt=""/>
      <v-lazy-image src="img/get_in_touch.svg" class="get_in_touch_img" @click="contact()" alt=""/>
        <v-lazy-image src="img/hamburger.svg" class="hamburger" @click="open_popup" alt=""/>
      </div>
      <div id="main_content" class="main_content">
        <v-lazy-image src="img/hedline.svg" class="headline" alt=""/>
        <v-lazy-image src="img/succes.svg" class="succes" alt=""/>
        <v-lazy-image src="img/main_swiches.svg" class="main_swiches" alt=""/>
        <v-lazy-image src="img/navigate_img.svg" class="navigate_img" alt=""/>
        <v-lazy-image src="img/about_us.svg" class="about_us" id="about_us" alt=""/>
        <v-lazy-image src="img/about_headline_desktop.svg" class="about_headline_desktop" alt=""/>
        <v-lazy-image src="img/about_headline_mobile.svg" class="about_headline_mobile" alt=""/>
        <v-lazy-image src="img/about_text_desktop.svg" class="about_text_desktop" alt=""/>
        <v-lazy-image src="img/about_text_mobile.svg" class="about_text_mobile" alt=""/>
        <v-lazy-image src="img/picture_about_us.png" class="picture_about_us" alt=""/>
        <v-lazy-image src="img/our_values.svg" class="our_values" id="our_values" alt=""/>
        <v-lazy-image src="img/our_values_headline_desktop.svg" class="our_values_headline_desktop" alt=""/>
        <v-lazy-image src="img/our_values_headline_mobile.svg" class="our_values_headline_mobile" alt=""/>
        <div class="c_cards_section">
          <div class="c_cards">
            <v-lazy-image src="img/card1.svg" class="card_d" alt=""/>
            <v-lazy-image src="img/card2.svg" class="card_d" alt=""/>
            <v-lazy-image src="img/card3.svg" class="card_d" alt=""/>
          </div>
        </div>
        <v-lazy-image src="img/our_advantages.svg" class="our_advantages" id="our_advantages" alt=""/>
        <v-lazy-image src="img/our_advantages_headline.svg" class="our_advantages_headline" alt=""/>
        <v-lazy-image src="img/advantages_headline_mobile.svg" class="advantages_headline_mobile" alt=""/>
        <div class="icons">
          <v-lazy-image src="img/icon1.svg" class="icon_adv" alt=""/>
          <v-lazy-image src="img/icon2.svg" class="icon_adv" alt=""/>
          <v-lazy-image src="img/icon3.svg" class="icon_adv" alt=""/>
        </div>
        <v-lazy-image src="img/our_servises.svg" class="our_services" id="our_services" alt=""/>
        <v-lazy-image src="img/our_servises_headline.svg" class="our_services_headline" alt=""/>
        <v-lazy-image src="img/servisec_headline_m.svg" class="servisec_headline_m" alt=""/>
        <v-lazy-image src="img/our_servises_text.svg" class="our_services_text" alt=""/>
        <v-lazy-image src="img/servises_text_m.svg" class="servises_text_m" alt=""/>
        <div class="services_row">
          <v-lazy-image src="img/serv1.svg" @click="serv('s1')" class="serv" alt=""/>
          <v-lazy-image src="img/serv2.svg" @click="serv('s2')" class="serv" alt=""/>
          <v-lazy-image src="img/serv3.svg" @click="serv('s3')" class="serv" alt=""/>
          <v-lazy-image src="img/serv4.svg" @click="serv('s4')" class="serv" alt=""/>
          <v-lazy-image src="img/serv5.svg" @click="serv('s5')" class="serv" alt=""/>
          <v-lazy-image src="img/serv6.svg" @click="serv('s6')" class="serv" alt=""/>
          <v-lazy-image src="img/serv7.svg" @click="serv('s7')" class="serv" alt=""/>
          <v-lazy-image src="img/serv8.svg" @click="serv('s8')" class="serv" alt=""/>
          <v-lazy-image src="img/serv9.svg" @click="serv('services_section')" class="serv" alt=""/>
        </div>
        <v-lazy-image src="img/our_vacancies.svg" class="our_vacancies" id="our_vacancies" alt=""/>
        <v-lazy-image src="img/our_values_list.svg" class="our_vacancies_list" alt=""/>
        <v-lazy-image src="img/our_values_arrow.svg" class="our_vacancies_arrow" alt=""/>
        <v-lazy-image src="img/our_vacancies_button.svg" class="vacancies_button" @click="contact()" alt=""/>
        <v-lazy-image src="img/vacations_img.png" class="vacations_img" alt=""/>
        <v-lazy-image src="img/values_line_m.svg" class="values_line_m" alt=""/>
      </div>
      <div id="services_section" class="services_section">
        <v-lazy-image src="img/arrow_back.svg" @click="back()" class="arrow_back" alt=""/>
        <v-lazy-image src="img/our_servises.svg" class="our_servises_page" alt=""/>
        <div id="s1" class="services_block">
        <v-lazy-image src="img/servs/serv1.svg" class="serv1" alt=""/>
        <div class="services_headline">Business Analysis</div>
          <div class="services_description">Before making any changes, we research your customers' needs and the market. Our decisions are always based on the customer's goals and values. That is why we have achieved a high percentage of efficiency in our offerings. </div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Depth of analysis</b> <br>
            We not only identify business goals but also link them to current rank-and-file tasks. This allows each employee to evaluate his or her contribution to the overall goal.
          </div>
          <div class="benefits_itself">
            <b>Technology</b> <br>
            We use advanced methods to gather market and customer information. We trust data and everything we can measure.
          </div>
          <div class="benefits_itself">
            <b>Speed</b> <br>
            We have built up solid expertise in several niches over the years, and each new project is easier and faster for us.
          </div>
          <v-lazy-image src="img/servs/pic1.png" class="serv_pic" alt=""/>
        </div>
        <div id="s2" class="services_block">
          <v-lazy-image src="img/servs/serv2.svg" class="serv1" alt=""/>
          <div class="services_headline">Technical communication</div>
          <div class="services_description">At the heart of any work must be good communication. We make sure that all parties involved in the project understand each other. Sometimes even without direct communication.</div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Depth of analysis</b> <br>
            First, we create the structure of technical documentation based on the goals and the information needs of all parties.
          </div>
          <div class="benefits_itself">
            <b>Details</b> <br>
            We create detailed technical documentation which describes all possible variants of events and all potential problems in the course of project development.
          </div>
          <div class="benefits_itself">
            <b>Clarity</b> <br>
            We write for people, so we use simple everyday language without compromising accuracy.
          </div>
          <v-lazy-image src="img/servs/pic2.png" class="serv_pic" alt=""/>
        </div>
        <div id="s3" class="services_block">
          <v-lazy-image src="img/servs/serv3.svg" class="serv1" alt=""/>
          <div class="services_headline">Solution Architecture</div>
          <div class="services_description">We develop technological solutions for business problems from the ground up.</div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Early start
            </b> <br>
            We get started on a project before it's even realized. Do you just have an idea? We can already be approached.
          </div>
          <div class="benefits_itself">
            <b>Attention to detail</b> <br>
            We deeply dive into a niche to understand as accurately as possible how it works. The accuracy of the software solution implementation depends on it. So don't be surprised by a lot of questions.
          </div>
          <div class="benefits_itself">
            <b>Experience</b> <br>
            Our engineers have vast experience and domain expertise in several niches. Thanks to this, the speed of the solution implementation increases many times over.
          </div>
          <v-lazy-image src="img/servs/pic3.png" class="serv_pic" alt=""/>
        </div>
        <div id="s4" class="services_block">
          <v-lazy-image src="img/servs/serv4.svg" class="serv1" alt=""/>
          <div class="services_headline">Software Development</div>
          <div class="services_description">Service is now rapidly coming to the forefront of any business. The more convenient and pleasant the interaction of your customers with your product, the higher the probability of repeat sales. We provide convenience and comfort to your customers.</div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Reliability
            </b> <br>
            We get started on a project before it's even realized. Do you just have an idea? We can already be approached.
          </div>
          <div class="benefits_itself">
            <b>Convenience
            </b> <br>
            We deeply dive into a niche to understand as accurately as possible how it works. The accuracy of the software solution implementation depends on it. So don't be surprised by a lot of questions.
          </div>
          <div class="benefits_itself">
            <b>Versatility</b> <br>
            Our team includes developers who can code in all major programming languages — from Phyton to Java.
          </div>
          <v-lazy-image src="img/servs/pic4.png" class="serv_pic" alt=""/>
        </div>
        <div id="s5" class="services_block">
          <v-lazy-image src="img/servs/serv5.svg" class="serv1" alt=""/>
          <div class="services_headline">Software Testing</div>
          <div class="services_description">If you already have software but aren't ready to show it to your customers, talk to us. Our QA department will provide rigorous testing and accurate bug detection.</div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Tough conditions
            </b> <br>
            We subject your software to more stress than it will receive in reality. Such a crash test helps to reduce the number of failures in the future.
          </div>
          <div class="benefits_itself">
            <b>Insight
            </b> <br>
            Our QA department has domain expertise in several areas, so we already know the potential pitfalls of software flaws.
          </div>
          <div class="benefits_itself">
            <b>Speed</b> <br>
            We have a separate QA department, which ensures fast testing of any kind of software.
          </div>
          <v-lazy-image src="img/servs/pic5.png" class="serv_pic" alt=""/>
        </div>
        <div id="s6" class="services_block">
          <v-lazy-image src="img/servs/serv6.svg" class="serv1" alt=""/>
          <div class="services_headline">Product Management</div>
          <div class="services_description">Sometimes it happens that there is a good product, but there
            is also a lot of chaos in its management. Get rid of the chaos — assign the project to us.
          </div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Transparency
            </b> <br>
            All projects are kept in a task manager open for you; you can find all data about the project, its progress, and its status at any time.
          </div>
          <div class="benefits_itself">
            <b>Reporting
            </b> <br>
            At the end of each sprint, we report on the successes and problems of each project.
          </div>
          <div class="benefits_itself">
            <b>Empathy
            </b> <br>
            Any project doesn't rely only on key stakeholders. All employees involved matter. We know how to engage them.
          </div>
          <v-lazy-image src="img/servs/pic6.png" class="serv_pic" alt=""/>
        </div>
        <div id="s7" class="services_block">
          <v-lazy-image src="img/servs/serv7.svg" class="serv1" alt=""/>
          <div class="services_headline">Marketing</div>
          <div class="services_description">Strategy is king. That's where we start. But we can also implement yours.
          </div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>Accuracy
            </b> <br>
            We have done more than one study in key niches, but we do it repeatedly with every new project. This allows us to identify the needs of the target audience accurately.
          </div>
          <div class="benefits_itself">
            <b>Fundamental
            </b> <br>
            The most important thing before the start of the project is to understand where the project is at this stage and where it should be in a certain period of time.
          </div>
          <div class="benefits_itself">
            <b>Creativity
            </b> <br>
            Our CMO, SMM and other employees of the department have versatile experience. This helps us to approach the marketing tasks of our clients unconventionally.
          </div>
          <v-lazy-image src="img/servs/pic7.png" class="serv_pic" alt=""/>
        </div>
        <div id="s8" class="services_block" style="margin-bottom: 350px">
          <v-lazy-image src="img/servs/serv8.svg" class="serv1" alt=""/>
          <div class="services_headline">Operational support
          </div>
          <div class="services_description">After the development and testing of any software come the moment of its implementation. And here, it is essential to integrate the product into customers' lives smoothly.

          </div>
          <div class="benefits">Benefits</div>
          <div class="benefits_itself">
            <b>24/7 access
            </b> <br>
            Our team is ready to fix any problem at any time.
          </div>
          <div class="benefits_itself">
            <b>Ease of integration
            </b> <br>
            We help you to integrate software into your workflows smoothly and painlessly.
          </div>
          <div class="benefits_itself">
            <b>Timelines
            </b> <br>
            We’ve been providing software support for several years, so we always understand at what stage problems can arise. And take care of them.
          </div>
          <v-lazy-image src="img/servs/pic8.png" class="serv_pic" alt=""/>
        </div>
      </div>
    </section>

    <terms_all id="terms_all"/>
    <privacy_all id="privacy_all"/>

    <div id="content_clip" class="content_clip">
      <v-lazy-image src="img/values_line.svg" class="values_line" alt=""/>

    </div>
    <section class="footer" id="footer">
      <div class="footer_content">
      <v-lazy-image src="img/footer_headline.svg" class="footer_headline" alt=""/>
        <v-lazy-image src="img/footer_headline_m.svg" class="footer_headline_m" alt=""/>
      <v-lazy-image src="img/footer_button.svg" class="footer_button" @click="contact()" alt=""/>
      <v-lazy-image src="img/footer_subtitle.svg" class="footer_subtitle" alt=""/>
      <v-lazy-image src="img/footer_figure.svg" class="footer_figure" alt=""/>
        <div class="footer_pages">
          <div @click="privacy()" class="pages" id="privacy">Privacy Policy</div>
          <div @click="terms()" class="pages" id="terms">Terms And Conditions</div>
        </div>
        <div class="footer_text">
          PULSUP LTD <br>
          Boumpoulinas, 1-3, BOUMBOULINA BUILDING, Flat/Office 42, 1060, Nicosia, Cyprus<br>
          <a class="mail_footer" href="mailto:info@pulsup.tech">info@pulsup.tech</a>
        </div>
      </div>
    </section>
  </div>
  <div class="popup" id="popup">
    <div class="popup_content">
      <v-lazy-image src="img/logo_popup.svg" class="logo_popup" alt=""/>
      <v-lazy-image src="img/cross_popup.svg" class="cross_popup" @click="close_popup" alt=""/>
    </div>
    <div class="popup_content_text">
      <div class="text_popup_itself" @click="go_popup('about_us')">about us</div>
      <div class="text_popup_itself">●</div>
    </div>
    <div class="popup_content_text">
      <div class="text_popup_itself" @click="go_popup('our_values')">our values</div>
      <div class="text_popup_itself">●</div>
    </div>
    <div class="popup_content_text">
      <div class="text_popup_itself" @click="go_popup('our_advantages')">our advantages</div>
      <div class="text_popup_itself">●</div>
    </div>
    <div class="popup_content_text">
      <div class="text_popup_itself" @click="go_popup('our_services')">our services</div>
      <div class="text_popup_itself">●</div>
    </div>
    <div class="popup_content_text">
      <div class="text_popup_itself" @click="go_popup('our_vacancies')">our vacancies</div>
      <div class="text_popup_itself">●</div>
    </div>
    <v-lazy-image src="img/footer_figure.svg" class="popup_figure" alt=""/>
    <v-lazy-image src="img/footer_button.svg" class="popup_button" @click="contact()" alt=""/>
  </div>
</template>

<script>
import VLazyImage from "v-lazy-image";

import terms_all from '../components/terms_all'
import privacy_all from '../components/privacy_all'




export default {
  components: {
    VLazyImage,
    terms_all,
    privacy_all,
  },
  methods: {
    serv(hash) {
      document.getElementById("main_content").style.display = "none";
      document.getElementById("content_clip").style.display = "none";
      document.getElementById("privacy").style.opacity = "1";
      document.getElementById("terms").style.opacity = "1";
      document.getElementById("footer").classList.remove("footer_i_cor");
      document.getElementById("services_section").style.display = "block";
      document.getElementById("services_section").classList.remove("services_animation_back");
      document.getElementById("services_section").classList.add("services_animation");
      location.hash = "#" + hash;
      document.getElementById("footer_bg").classList.remove("privacy_correction");
      document.getElementById("footer_bg").classList.remove("terms_correction");
      document.getElementById("footer_bg").classList.add("footer_correction");
      document.getElementById("footer").classList.add("footer_i_cor");
    },
    logo() {
      document.getElementById("terms_all").style.display = "none";
      document.getElementById("privacy_all").style.display = "none";
      document.getElementById("main_content").style.display = "block";
      document.getElementById("content_clip").style.display = "block";
      document.getElementById("privacy").style.opacity = "1";
      document.getElementById("terms").style.opacity = "1";
      document.getElementById("footer").classList.remove("footer_i_cor");
      document.getElementById("services_section").style.display = "none";
      document.getElementById("services_section").classList.remove("services_animation_back");
      document.getElementById("services_section").classList.remove("services_animation");
      document.getElementById("footer_bg").classList.remove("privacy_correction");
      document.getElementById("footer_bg").classList.remove("terms_correction");
      document.getElementById("footer_bg").classList.remove("footer_correction");
      document.body.scrollTop = document.documentElement.scrollTop = 0;
    },
    terms() {
      document.getElementById("main_content").style.display = "none";
      document.getElementById("content_clip").style.display = "none";
      document.getElementById("terms_all").style.display = "block";
      document.getElementById("privacy_all").style.display = "none";
      document.getElementById("footer_bg").classList.remove("privacy_correction");
      document.getElementById("footer_bg").classList.add("terms_correction");
      document.getElementById("footer").classList.add("footer_i_cor");
      document.getElementById("terms").style.opacity = "0";
      document.getElementById("privacy").style.opacity = "1";
      document.body.scrollTop = document.documentElement.scrollTop = 0;
      document.getElementById("services_section").classList.remove("services_animation");
      document.getElementById("services_section").style.display = "none";
    },
    privacy() {
      document.getElementById("main_content").style.display = "none";
      document.getElementById("content_clip").style.display = "none";
      document.getElementById("privacy_all").style.display = "block";
      document.getElementById("terms_all").style.display = "none";
      document.getElementById("footer_bg").classList.remove("terms_correction");
      document.getElementById("footer_bg").classList.add("privacy_correction");
      document.getElementById("footer").classList.add("footer_i_cor");
      document.getElementById("privacy").style.opacity = "0";
      document.getElementById("terms").style.opacity = "1";
      document.body.scrollTop = document.documentElement.scrollTop = 0;
      document.getElementById("services_section").classList.remove("services_animation");
      document.getElementById("services_section").style.display = "none";
    },
    back() {
      document.getElementById("services_section").classList.remove("services_animation");
      document.getElementById("services_section").classList.add("services_animation_back");

      setTimeout(() => {
        document.getElementById("main_content").style.display = "block";
        document.getElementById("services_section").style.display = "none";
        document.getElementById("content_clip").style.display = "block";
        document.getElementById("footer_bg").classList.remove("footer_correction");
        document.getElementById("footer").classList.remove("footer_i_cor");
      }, 200);
    },
    contact() {
      window.location.href='mailto:info@pulsup.tech';
    },
    open_popup() {
      document.getElementById("popup").classList.add("open_popup");
    },
    close_popup() {
      document.getElementById("popup").classList.remove("open_popup");
    },
    go_popup(hash) {
      document.getElementById("main_content").style.display = "block";
      document.getElementById("content_clip").style.display = "block";
      document.getElementById("privacy_all").style.display = "none";
      document.getElementById("terms_all").style.display = "none";
      document.getElementById("footer_bg").classList.remove("privacy_correction");
      document.getElementById("footer_bg").classList.remove("terms_correction");
      document.getElementById("footer").classList.remove("footer_i_cor");
      document.getElementById("privacy").style.opacity = "1";
      document.getElementById("terms").style.opacity = "1";
      document.getElementById("popup").classList.remove("open_popup");
      location.hash = "#" + hash;
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.wrapper {
  position: relative;
  width: 100%;
  z-index: 1;
}
.first_screen {
  width: 100%;
  position: relative;
  top: 0;
  left: 0;
  z-index: 1;
}
.logo_img{
  margin-left: -9px;
  position: relative;
  cursor: pointer;
}
.get_in_touch_img {
  position: relative;
  margin-top: 6px;
  cursor: pointer;
  transition: all .5s linear;
}
.get_in_touch_img:hover {
  background-color: #faeb45;

}
.top_row {
  position: relative;
  display: flex;
  top: 14px;
  width: 1139px;
  left: 50%;
  transform: translate(-50%);
  justify-content: space-between;
  align-content: space-around;
  align-items: center;
}
.main_content {
  position: relative;
  top: 5px;
  width: 1139px;
  left: 50%;
  transform: translate(-50%);
  height: 3164px;
}
.headline{
  position: absolute;
  top: 38px;
  left: 92px;
}
.succes {
  position: absolute;
  top: 382px;
  left: 91px;
}
.main_swiches {
  position: absolute;
  top: 99px;
  left: 515px;
}
.navigate_img {
  position: absolute;
  top: 250px;
  left: -11px;
}
.about_us{
  position: absolute;
  top: 634px;
  left: -10px;
}
.about_headline_desktop{
  position: absolute;
  top: 711px;
  left: -10px;
  z-index: 1;
}
.about_text_desktop{
  position: absolute;
  top: 885px;
  left: -10px;
  z-index: 1;
}
.picture_about_us{
  position: absolute;
  top: 683px;
  z-index: 0;
  left: 514px;
}
.our_values {
  position: absolute;
  top: 1187px;
  left: -11px;
}

.values_line {
  position: absolute;
  top: 1282px;
  left: 50%;
  transform: translate(-7%);
  z-index: 5;
  overflow: hidden;
}

.our_values_headline_desktop {
  position: absolute;
  top: 1265px;
  left: -11px;
}

.c_cards {
  position: absolute;
  width: 1160px;
  display: flex;
  justify-content: space-between;
  z-index: 4;
}

.c_cards_section {
  overflow: hidden;
  top: 1402px;
  width: 100%;
  height: 400px;
  position: absolute;
  left: -11px;
}

.content_clip {
  width: 100%;
  height: 1800px;
  position: absolute;
  top: 0;
  overflow: hidden;
}
.our_advantages {
  position: absolute;
  top: 1825px;
  z-index: 0;
  left: -10px;
}
.our_advantages_headline {
  position: absolute;
  top: 1905px;
  z-index: 0;
  left: -10px;
}
.icons {
  position: absolute;
  top: 2041px;
  left: -8px;
  display: flex;
  width: 1107px;
  justify-content: space-between;
}
.our_services {
  position: absolute;
  top: 2249px;
  z-index: 0;
  left: -10px;
}
.our_services_headline {
  position: absolute;
  top: 2329px;
  z-index: 0;
  left: -10px;
}
.our_services_text {
  position: absolute;
  top: 2466px;
  z-index: 0;
  left: -10px;
}
.services_row {
  position: absolute;
  display: flex;
  top: 2572px;
  left: -10px;
  width: 1200px;
  flex-wrap: wrap;
}
.serv {
  margin-right: 58px;
  margin-bottom: 35px;
  cursor: pointer;
  transition: background-color .5s ease-in-out;
}
.serv:hover {
  background-color: #faeb45;
}
.our_vacancies {
  position: absolute;
  top: 2831px;
  z-index: 0;
  left: -10px;
}
.our_vacancies_list {
  position: absolute;
  top: 2909px;
  z-index: 0;
  left: -10px;
}

.our_vacancies_arrow {
  position: absolute;
  top: 3003px;
  z-index: 0;
  left: 235px;
}
.vacancies_button {
  position: absolute;
  top: 3057px;
  z-index: 0;
  left: 324px;
  cursor: pointer;
  transition: filter .5s ease-in-out;
}
.vacancies_button:hover {
  filter: invert(1);
}

.vacations_img{
  position: absolute;
  top: 2818px;
  z-index: 0;
  left: 695px;
}
.footer {
  position: relative;
  top: 39px;
  width: 100%;
  height: 525px;

}
.footer_headline {
  position: absolute;
  top: 86px;
  left: 0px;
}
.footer_button {
  position: absolute;
  top: 275px;
  left: 0;
  cursor: pointer;
  transition: filter .5s ease-in-out;
}
.footer_button:hover {
  filter: invert(1);
}
.footer_subtitle {
  position: absolute;
  top: 490px;
  left: 0;
  margin-bottom: 50px;
}
.card_d {
  width: 358px;
  height: 331px
}

.footer_figure {
  position: absolute;
  top: 104px;
  left: 599px;
}

.footer_content {
  width: 1162px;
  position: absolute;
  left: 50%;
  transform: translate(-50%);
}

.services_section {
  position: relative;
  width: 1139px;
  top: 10px;
  left: 50%;
  transform: translate(100%);
  height: auto;
  display: none;
  z-index: 6;
}
.services_animation {
  animation: translate_serv .2s ease-in-out forwards;
}

.services_animation_back {
  animation: translate_serv_back .2s ease-in-out forwards;
}

@keyframes translate_serv {
  0% {
    transform: translate(100%);
  }
  100% {
    transform: translate(-50%);
  }
}

@keyframes translate_serv_back {
  0% {
    transform: translate(-50%);
  }
  100% {
    transform: translate(100%);
  }
}

.our_servises_page {
  position: relative;
  top: 127px;
  left: -511px;
}
.arrow_back {
  position: relative;
  top: 75px;
  left: -486px;
  cursor: pointer;
}


.services_block {
  position: relative;
  top: 173px;
  margin-bottom: 153px;
}


.services_headline {
  font-family: 'Poppins', sans-serif;
  font-size: 45.7px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  text-align: left;
  color: #000;
  position: relative;
  left: -11px;
  letter-spacing: -.5px;
}
.serv1 {
  position: absolute;
  top: 25px;
  left: -8px;
}

.services_description {
  font-family: 'Poppins', sans-serif;
  font-size: 25px;
  line-height: 36px;
  font-weight: 400;
  font-stretch: normal;
  font-style: normal;
  text-align: left;
  color: #000;
  position: relative;
  left: -11px;
  letter-spacing: normal;
  width: 840px;
  top: 18px;
}

.benefits {
  font-family: 'Poppins', sans-serif;
  font-size: 25px;
  line-height: 36px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  text-align: left;
  color: #000;
  position: relative;
  left: -11px;
  letter-spacing: normal;
  width: 840px;
  top: 52px;
}

.benefits_itself {
  font-family: 'Poppins', sans-serif;
  font-size: 18px;
  line-height: 25px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  text-align: left;
  color: #000;
  position: relative;
  left: -11px;
  width: 860px;
  top: 84px;
  letter-spacing: -.2px;
  margin-bottom: 27px;
}
.serv_pic{
  position: absolute;
  top: -16px;
  left: 514px;
}

.footer_bg {
  position: absolute;
  width: 100%;
  height: 526px;
  top: 3298px;
  z-index: 0;
  left: 0;
  background-color: #000000;
}

.footer_correction {
  top: 5448px!important;
}

.hamburger {
  display: none;
}

.about_headline_mobile {
  display: none;
}

.about_text_mobile {
  display: none;
}

.our_values_headline_mobile {
  display: none;
}
.advantages_headline_mobile {
  display: none;
}

.servisec_headline_m{
  display: none;
}

.servises_text_m {
  display: none;
}


.footer_headline_m {
  display: none;
}

.values_line_m {
  display: none;
}

.footer_text {
  position: absolute;
  left: 435px;
  width: 720px;
  top: 365px;
  font-family: 'Poppins', sans-serif;
  font-size: 18px;
  line-height: 25px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  text-align: left;
  color: #ffffff;
  letter-spacing: -.2px;
}

.mail_footer{
  text-decoration: none;
  color: #ffffff;
  transition: all .5s linear;
  text-decoration: underline;
}

.mail_footer:hover {
  background-color: #faeb45;
  color: #000000;
}

.footer_pages {
  position: absolute;
  top: 367px;
  left: 0;
  display: flex;
  flex-direction: column;
}

.pages {
  font-family: 'Poppins', sans-serif;
  font-size: 20px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  text-align: left;
  color: #ffffff;
  cursor: pointer;
  transition: all .5s linear;
  line-height: 200%;
  text-decoration: underline;
}

.pages:hover {
  background-color: #faeb45;
  color: #000000;
}
.privacy_correction {
  top: 3775px;
}
.terms_correction {
  top: 2907px;
}

@media (max-width: 1260px) {
  .wrapper {
    transform: scale(.9);
    transform-origin: top;
    height: 2300px;
  }
  .footer_bg {
    height: 500px;
    top: 2967px;
  }
  .footer_correction {
    top: 4900px!important;
  }
  .terms_correction {
    top: 2605px;
  }
  .privacy_correction {
    top: 3389px;
  }
}

@media (max-width: 1140px) {
  .wrapper {
    transform: scale(.8);
    transform-origin: top;
    height: 2000px;
  }
  .footer_bg {
    height: 444px;
    top: 2667px;
  }
  .footer_correction {
    top: 4380px!important;
  }
  .terms_correction {
    top: 2323px;
  }
  .privacy_correction {
    top: 3010px;
  }
}

@media (max-width: 1010px) {
  .wrapper {
    transform: scale(.7);
    transform-origin: top;
    height: 1700px;
  }
  .footer_bg {
    height: 400px;
    top: 2317px;
  }
  .footer_correction {
    top: 3820px!important;
  }
  .terms_correction {
    top: 2044px;
  }
  .privacy_correction {
    top: 2645px;
  }
}

@media (max-width: 890px) {
  .wrapper {
    transform: scale(.6);
    transform-origin: top;
    height: 1500px;
  }
  .footer_bg {
    height: 338px;
    top: 2000px;
  }
  .footer_correction {
    top: 3300px!important;
  }
  .privacy_correction {
    top: 2272px;
  }
}

@media (max-width: 760px) {
  .footer_text {
    position: absolute;
    left: 0px;
    width: 320px;
    top: 470px;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    line-height: 25px;
    font-weight: 600;
    text-align: center;
    color: #ffffff;
    letter-spacing: -.2px;
  }
  .wrapper {
    transform: scale(.7);
    transform-origin: top;
    height: 1700px;
  }
  .footer_bg {
    height: 400px;
    top: 2317px;
  }
  .footer_correction {
    top: 3820px!important;
  }
  .get_in_touch_img {
    display: none;
  }
  .logo_img {
    margin-left: -75px;
    height: 52px;
  }
  .top_row {
    top: -66px;
  }
  .hamburger {
    display: block;
    position: relative;
    left: 75px;
    top: 7px;
    height: 24px;
    cursor: pointer;
  }

  .headline {
    position: absolute;
    top: -53px;
    left: -76px;
    height: 370px;
  }
  .main_swiches {
    position: absolute;
    top: 418px;
    left: 48px;
    height: 236px;
  }
  .succes {
    top: 353px;
    left: -73px;
    height: 31px;
  }
  .about_headline_desktop {
    display: none;
  }
  .about_headline_mobile {
    position: absolute;
    top: 799px;
    left: -75px;
    z-index: 1;
    display: block;
    height: 198px;
  }
  .main_content {
    width: 320px;
  }
  .navigate_img {
    display: none;
  }
  .about_us {
    top: 728px;
    left: -73px;
    height: 17px;
  }
  .about_text_desktop {
    display: none;
  }
  .about_text_mobile {
    display: block;
    position: absolute;
    top: 1027px;
    left: -74px;
    height: 291px;
  }
  .picture_about_us {
    top: 1245px;
    z-index: 0;
    left: 37px;
    height: 185px;
  }
  .our_values {
    top: 1630px;
    left: -73px;
    height: 18px;
  }

  .top_row{
    width: 320px;
  }
  .values_line {
    top: 1881px;
    transform: translate(-25%);
    height: 98px;
    z-index: 5;
    overflow: hidden;
  }
  .content_clip {
    width: 100%;
    height: 2500px;
  }
  .our_values_headline_desktop {
    display: none;
  }
  .our_values_headline_mobile {
    display: block;
    position: absolute;
    top: 1685px;
    left: -73px;
    height: 151px;
  }
  .c_cards_section{
    top: 1894px;
    left: -76px;
    height: 1400px;
    width: 430px;
  }
  .c_cards {
    width: 430px;
    flex-direction: column;
  }
  .card_d {
    margin-bottom: 20px;
    width: 430px;
    height: 397px
  }
  .footer_bg {
    top: 4700px;
  }
  .our_advantages {
    top: 3216px;
    left: -74px;
    height: 18.5px;
  }
  .our_advantages_headline {
    display: none;
  }
  .our_services_headline {
    display: none;
  }
  .our_services_text {
    display: none;
  }

  .advantages_headline_mobile {
    display: block;
    top: 3288px;
    left: -74px;
    position: absolute;
    height: 244px;
  }

  .icons {
    position: absolute;
    top: 3571px;
    left: -77px;
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    width: 134%;
    align-items: flex-start;
  }
  .icon_adv {
    height: 124px;
    margin-bottom: 11px;
  }
  .our_services {
    top: 4039px;
    left: -74px;
    height: 18.5px;
  }
  .servisec_headline_m{
    display: block;
    position: absolute;
    top: 4111px;
    left: -74px;
    height: 192px;
  }
  .our_services_text {
    display: none;
  }
  .servises_text_m {
    display: block;
    position: absolute;
    top: 4338px;
    left: -76px;
    height: 236px;
  }
  .services_row {
    top: 4634px;
    width: 500px;
    left: -72px;
  }
  .serv {
    height: 40px;
    margin-bottom: 37px;
  }
  .our_vacancies {
    position: absolute;
    z-index: 0;
    left: -72px;
    top: 5434px;
    height: 18.4px;
  }
  .vacations_img {
    position: absolute;
    top: 5500px;
    z-index: 0;
    left: -44px;
  }
  .our_vacancies_list {
    display: none;
  }

  .values_line_m {
    display: block;
    position: absolute;
    top: 5592px;
    left: -76px;
    height: 150px;
    z-index: 5;
  }
  .vacancies_button {
    top: 5847px;
    left: 71px;
    height: 80px;
  }
  .our_vacancies_arrow {
    top: 5772px;
    left: -58px;
    height: 103px;
  }
  .footer_headline {
    display: none;
  }
  .footer_headline_m {
    display: block;
    position: absolute;
    top: 48px;
    left: -74px;
    height: 148px;
  }
  .footer {
    top: 2846px;
    height: 635px;
  }
  .footer_figure {
    position: absolute;
    top: 66px;
    left: -73px;
    height: 175px;
  }
  .footer_content {
    width: 320px;
  }
  .footer_button {
    top: 265px;
    left: -27px;
    height: 80px;
  }
  .footer_subtitle {
    position: absolute;
    top: 627px;
    left: 9px;
    height: 18px;
    margin-bottom: 50px;
  }
  .footer_pages {
    top: 378px;
    width: inherit;
  }
  .pages {
    text-align: center;
  }
  .footer_bg {
    top: 4303px;
    height: 480px;
  }
  .arrow_back {
    position: relative;
    top: 14px;
    left: -101px;
    cursor: pointer;
    height: 27px;
  }
  .our_servises_page {
    top: 72px;
    left: -155px;
    height: 18px;
  }
  .services_section {
    width: 320px;
  }
  .services_block {
    left: -70px;
  }
  .serv_pic {
    position: absolute;
    top: -40px;
    left: 114px;
    height: 153px;
  }

  .services_description, .benefits, .benefits_itself {
    width: 420px;
  }
  .serv1 {
    display: none;
  }
  .footer_i_cor {
    top: 0;
  }
  .footer_correction {
    top: 5280px!important;
  }
  .terms_correction {
    top: 3613px;

  }
  .privacy_correction {
    top: 5648px;
  }

}

.popup {
  width: 100%;
  height: 100%;
  background: #000000;
  position: fixed;
  top: 0;
  z-index: 50;
  left: 100%;
  display: none;
}

.open_popup {
  display: block!important;
  animation: popup_in .2s ease-in-out forwards;
}

@keyframes popup_in {
  0% {
    left: 100%;
  }
  100% {
    left: 0;
  }
}

.popup_content {
  width: 320px;
  position: absolute;
  display: flex;
  top: 20px;
  justify-content: space-between;
  left: 50%;
  transform: translate(-50%);
}
.popup_content_text {
  width: 320px;
  position: relative;
  display: flex;
  top: 85px;
  left: 50%;
  transform: translate(-50%);
  justify-content: flex-start;
  margin-top: 30px;
}
.text_popup_itself {
  font-family: 'Poppins', sans-serif;
  font-size: 18px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  text-align: left;
  color: #ffffff;
  position: relative;
  left: 0;
  letter-spacing: 0;
  text-transform: uppercase;
  cursor: pointer;
  margin-right: 20px;
}
.popup_figure {
  position: absolute;
  top: 399px;
  left: 50%;
  transform: translate(-50%);
  height: 120px;
}
.popup_button {
  position: absolute;
  top: 555px;
  left: 50%;
  transform: translate(-50%);
  cursor: pointer;
  transition: filter .5s ease-in-out;
}
.popup_button:hover {
  filter: invert(1);
}



.v-lazy-image {
  opacity: 0;
  margin-top: 20px;
  transition: all 0.6s ease-out;
}

.v-lazy-image-loaded {
  margin-top: 0;
  opacity: 1;
}



</style>

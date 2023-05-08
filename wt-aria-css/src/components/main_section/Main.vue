<template>
  <main>
    <div class="intro">
      <p>A Web Developer</p>
      <p>I am a web developer and I love to create websites.</p>
      <button>Learn More</button>
    </div>
    <div class="achievements">
      <div class="work">
        <i class="fas fa-atom"></i>
        <p class="work-heading">Projects</p>
        <p class="work-text">I have worked on many projects and I am very proud of them. I am a very good developer and I am always looking for new projects.</p>
      </div>
      <div class="work">
        <i class="fas fa-skiing"></i>
        <p class="work-heading">Skills</p>
        <p class="work-text">I have a lot of skills and I am very good at them. I am very good at programming and I am always looking for new skills.</p>
      </div>
      <div class="work">
        <i class="fas fa-ethernet"></i>
        <p class="work-heading">Network</p>
        <p class="work-text">I have a lot of network skills and I am very good at them. I am very good at networking and I am always looking for new network skills.</p>
      </div>
    </div>
    <div class="about-me">
      <div class="about-me-text">
        <p>About Me</p>
        <p>I am a web developer and I love to create websites. I am a very good developer and I am always looking for new projects. I am a very good developer and I am always looking for new projects.</p>
      </div>
      <img src="https://images.unsplash.com/photo-1596495578065-6e0763fa1178?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80">
    </div>

    <div class="contact-form">
      <div class="row">
        <p>Kontakt anfragen</p>
      </div>
      <div class="row">
        <p style="text-align:center">Ich freu mich von dir zu höhren!</p>
      </div>
      <div class="row input-container">
        <div class="col-xs-12">
          <div class="styled-input wide">
            <input  required />
            <label>Name</label>
          </div>
        </div>
        <div class="col-md-6 col-sm-12">
          <div class="styled-input">
            <input  required />
            <label>Email</label>
          </div>
        </div>
        <div class="col-md-6 col-sm-12">
          <div class="styled-input" style="float:right;">
            <input required />
            <label>Nummer</label>
          </div>
        </div>
        <div class="col-xs-12">
          <div class="styled-input wide">
            <textarea required></textarea>
            <label>Nachricht</label>
          </div>
        </div>
        <div class="col-xs-12">
          <div class="btn-lrg submit-btn">Kontakt</div>
        </div>
      </div>
    </div>

  </main>
</template>

<script>


export default {
  name: "Main",
}
</script>

<style scoped>
@import "./main.css";
</style>
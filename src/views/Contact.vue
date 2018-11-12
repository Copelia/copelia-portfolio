<template>
  <div class="container">
    <div class="row justify-center">
      <div class="col-12">
        <div class="contact-list">
        <a href="https://github.com/Copelia" target="_blank" title="Github page">
          <i class="fab fa-github pair"></i>
        </a>
        <a href="https://www.linkedin.com/in/copelia-altamirano" target="_blank" title="LinkedIn">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="mailto:coral_altamirano@hotmail.com" title="email me">
          <i class="fas fa-envelope pair"></i>
        </a>
      <!-- </div>
      <div class="col-12">   -->
        <a href="https://dev.to/cocorali" target="_blanck">
          <i class="fab fa-dev"></i>
        </a>
        <a href="../assets/CopeliaResume.pdf" download="CopeliaCV">
        <i class="far fa-file pair">
        </i>
        </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.contact-list{
  margin: 5vw 2vw 5vw 2vw;
}
i{
  margin: 1em 1em 1em 0.5em;
  font-size: 3em;
  color: #64AF76;
}

.pair{
  color: #419B7F;
}

@media screen and (max-width: 375px) {
  i{
    font-size: 2.5em;
    margin: 15px 15px 15px 15px;
  }
}
</style>

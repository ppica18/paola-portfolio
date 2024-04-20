<template>
  <div style="margin-bottom: 80px;">
    <h1>Hi!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Paola Pica</strong>, a Game Designer that is currently studying a degree in Design and Production of Videogames in Pompeu Fabra University.<br/>
        I love puzzles and playing Videogames. I also like reading mystery novels, drawing and listening music.
      </div>

      <div style="margin-top: 20px;">I've worked on <router-link to="/game-projects">stuff</router-link> for university projects or participating in GameJams, I also wrote and took part in various <router-link to="/other-projects">other stuff</router-link>, and took part in <router-link to="/resume">a few things</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for a job</strong> as a Game Designer or Level Designer. If you're interested you can reach me at <a href="mailto:paolapicac@gmail.com">paolapicac@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of John" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="SkillBar">
  
  <div class="Skill">
    <h3 class="SkillName">HTML</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">CSS</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">Javascript</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">PHP</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">React / Next.js</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">Vue.js</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">jQuery</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">Layout und Design</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">Adobe Illustrator</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">Adobe Photoshop</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
  </div>

  <div class="Skill">
    <h3 class="SkillName">VS Code</h3>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin"></div>
    <div class="Pumpkin Grey"></div>
    <div class="Pumpkin Grey"></div>
  </div>
</div>
</template>

<style scoped>

.Pumpkin {
  display: flex;
  background-image: url(/src/assets/images/own_logo/Logo_colored.png);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  height: 3rem;
  width: 3rem;
}

.SkillBar {
  display: grid;
  grid-template-columns: 1fr;
  margin: 0 auto;
  border-radius: 2rem 0rem 2rem 0.5rem;
  border-bottom: solid 0.4rem var(--accentOrange);
  border-left: solid 0.4rem var(--accentOrange);
}

.Skill {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1fr 1fr 1fr;
  padding: 1rem;
}

.SkillName {
  display: flex;
  text-align: left;
  align-items: center;
  margin-right: 0.5rem;
}

.Grey {
  background-image: url(/src/assets/images/own_logo/Logo_grey.png);
}
</style>
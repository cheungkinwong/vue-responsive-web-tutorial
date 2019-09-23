<template>
  <div class="about-card">
    <div class="card-title">
      <img
        height="50px"
        src="../assets/69629720_708605172900729_1289481209553879040_n.jpg"
        alt="avatar"
        class="avatar"
      />
      <div class="title-text-content">
        <p>About me</p>
        <h2>Cheung Kin Wong</h2>
      </div>
    </div>
    <div class="card-content">
      <p>
        I’m a Junior Web Developer finishing a work study at BeCode Antwerp. My career path started as a Chemist at Umicore and evolved to a Prepress Coordinator at printing company Gazelle for almost 9 years.
        Now I am pursuing my love of coding.
        I’m a very driven and curious person, always eager to learn and face new challenges. In my professional experience, I’ve learned to think analytically, manage a small team and to use problem solving skills, all while dealing with stress and deadlines.
      </p>

      <table style="width:100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Photoshop, Illustrator, Figma</td>
        </tr>
        <tr>
          <td>Front-end</td>
          <td>React.js, Vue.js, HTML, CSS, JavaScript</td>
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Php, MySQL</td>
        </tr>
      </table>

      <p>
        I’m a Junior Web Developer finishing a work study at BeCode Antwerp. My career path started as a Chemist at Umicore and evolved to a Prepress Coordinator at printing company Gazelle for almost 9 years.
        Now I am pursuing my love of coding.
        I’m a very driven and curious person, always eager to learn and face new challenges. In my professional experience, I’ve learned to think analytically, manage a small team and to use problem solving skills, all while dealing with stress and deadlines.
      </p>

      <p>
        I’m a Junior Web Developer finishing a work study at BeCode Antwerp. My career path started as a Chemist at Umicore and evolved to a Prepress Coordinator at printing company Gazelle for almost 9 years.
        Now I am pursuing my love of coding.
        I’m a very driven and curious person, always eager to learn and face new challenges. In my professional experience, I’ve learned to think analytically, manage a small team and to use problem solving skills, all while dealing with stress and deadlines.
      </p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
 .about-card
  min-height: calc(100vh - 150px)
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      height: 50px
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content 
      p
        margin-bottom: 0
        color: rgb(210,210,210)
      h2
        margin-top: 0
  .card-content p
    line-height: 1.5
    margin: 30px auto
  table
    border-spacing: 0px
    margin: 50px auto
    tr th, tr td
      border: 1px solid white
      border-top: none
      padding: 10px
      text-align: center
      &:first-of-type
        border-left: none
      &:nth-of-type(2)
        border-right: none
  
</style>
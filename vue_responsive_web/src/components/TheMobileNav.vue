<template>
  <section class="nav">
    <div class="nav-brand">
      <img height="160px" src alt="logo" />
    </div>

    <div class="nav-menu">
      <ul class="nav-menu-list">
        <li class="nav-list-item">About me</li>
        <li class="nav-list-item">Github</li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>


<style lang="sass" scoped>
    .nav
        background: #333
        display: flex
        flex-direction: column
        justify-content: space-around
        align-items: center
        .nav-logo
            margin: 20px auto
        .nav-menu
            width: 100%
            color: white
        .nav-menu-list
            list-style: none
            padding: 0
            display: flex
            margin: 0
            color: white
            li
                width: 50%
                text-align: center
                background: #555
                padding: 10px 0
                curser: pointer
                transition: background 300ms ease-in-out
                &:hover
                    background: #333
                &:first-of-type
                    border-bottom: 5px solid #222
</style>
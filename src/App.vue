<template lang="pug">
#app
  nav.navbar.navbar-expand-lg.navbar-dark.bg-dark.rounded
    a.navbar-brand(href='#') 
      i.fas.fa-sun.fa-2x
      | &nbsp; Engenho Novo LLC
    button.navbar-toggler(type='button' data-toggle='collapse' data-target='#navbar_example_1' aria-controls='navbar_example_1' aria-expanded='false' aria-label='Toggle navigation')
      span.navbar-toggler-icon
    .collapse.navbar-collapse#navbar_example_1
      ul.navbar-nav.mr-auto
        li.nav-item.active
          a.nav-link(href='#')
            | In Principio 
            span.sr-only (current)
        li.nav-item
          a.nav-link(href='#') In Media Res
        li.nav-item.dropdown
          a.nav-link.dropdown-toggle#navbar_1_dropdown_1(href='#' role='button' data-toggle='dropdown' aria-haspopup='true' aria-expanded='false') Arbitria
          .dropdown-menu(aria-labelledby='navbar_1_dropdown_1')
            a.dropdown-item(href='#') Nero Was No Hero
            a.dropdown-item(href='#') Commodus Caesar
            .dropdown-divider
            a.dropdown-item(href='#') Julius Caesar
        li.nav-item
          a.nav-link.disabled(href='#') Augustus Caesar
      ul.navbar-nav.ml-auto
        li.nav-item
          a.nav-link.nav-link-icon(href='#')
            i.fas.fa-cogs
        li.nav-item.dropdown
          a.nav-link.nav-link-icon#navbar_1_dropdown_2(href='#' role='button' data-toggle='dropdown' aria-haspopup='true' aria-expanded='false')
            i.fas.fa-bell
          .dropdown-menu.dropdown-menu-right.dropdown-menu-xl.py-0
            .py-3.px-3
              h5.heading.h6.mb-0 Notifications
            .list-group
              a.list-group-item.list-group-item-action.d-flex.align-items-center(href='#')
                .list-group-img
                  span.avatar.bg-purple JD
                .list-group-content
                  .list-group-heading
                    | Johnyy Depp 
                    small 10:05 PM
                  p.text-sm Lorem ipsum dolor sit amet consectetur adipiscing eiusmod tempor
              a.list-group-item.list-group-item-action.d-flex.align-items-center(href='#')
                .list-group-img
                  span.avatar.bg-pink TC
                .list-group-content
                  .list-group-heading
                    | Tom Cruise 
                    small 10:05 PM
                  p.text-sm Lorem ipsum dolor sit amet consectetur adipiscing eiusmod tempor
              a.list-group-item.list-group-item-action.d-flex.align-items-center(href='#')
                .list-group-img
                  span.avatar.bg-blue WS
                .list-group-content
                  .list-group-heading
                    | Will Smith 
                    small 10:05 PM
                  p.text-sm Lorem ipsum dolor sit amet consectetur adipiscing eiusmod tempor
            .py-3.text-center
              a.link.link-sm.link--style-3(href='#') View all notifications
        li.nav-item.dropdown
          a.nav-link.nav-link-icon#navbar_1_dropdown_3(href='#' role='button' data-toggle='dropdown' aria-haspopup='true' aria-expanded='false')
            i.fas.fa-user
          .dropdown-menu.dropdown-menu-right
            h6.dropdown-header O Cardápio
            a.dropdown-item(href='#')
              span.float-right.badge.badge-primary 4
              i.fas.fa-envelope.text-primary
              | Messages

            a.dropdown-item(href='#')
              i.fas.fa-cog.text-primary
              | Settings

            .dropdown-divider(role='presentation')
            a.dropdown-item(href='#')
              i.fas.fa-sign-out-alt.text-primary
              | Sign out




  router-view.
</template>

<style lang="scss">
#app {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

  i, .material-icons, .fa, .fas {
    vertical-align: middle;
  }

</style>

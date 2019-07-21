<template>
  <div class="navbar">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">
        <i class="fab fa-dropbox"></i>
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- left aligned nav items -->
        <b-navbar-nav class="mr-auto">
          <b-nav-form class="search">
            <b-form-input size="sm" class="input-search mr-sm-2" placeholder="type to search..."></b-form-input>
            <b-button size="sm" class="btn-search my-2 my-sm-0" type="submit">
              <i class="fas fa-search"></i>
            </b-button>
          </b-nav-form>
        </b-navbar-nav>
        <!-- right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <div class="upgrade">
            <div class="img">
              <img src="~/assets/image/navbar/upgrade-icon.png" alt="upgrade-image" />
            </div>
            <div class="data">
              <p>Upgrade Account</p>
              <span>Pay 10$, Yearly</span>
            </div>
          </div>
          <div class="information">
            <div class="img">
              <img src="~/assets/image/navbar/personal-img.png" alt="personal-image" />
            </div>

            <div class="data">
              <p>Tim Van Damme</p>
              <span>Narmal User</span>
            </div>
          </div>
          <!--End information-->

          <div>
            <b-dropdown class="dropdown-btn m-md-2 fas fa-cog">
              <b-dropdown-item>notification 1</b-dropdown-item>
              <b-dropdown-item>notification 2</b-dropdown-item>
              <b-dropdown-item>notification 3</b-dropdown-item>
              <b-dropdown-item>notification 4</b-dropdown-item>
              <b-dropdown-item>notification 5</b-dropdown-item>
            </b-dropdown>
          </div>

          <div>
            <b-dropdown class="dropdown-btn m-md-2 fas fa-bell">
              <b-dropdown-item>notification 1</b-dropdown-item>
              <b-dropdown-item>notification 2</b-dropdown-item>
              <b-dropdown-item>notification 3</b-dropdown-item>
              <b-dropdown-item>notification 4</b-dropdown-item>
              <b-dropdown-item>notification 5</b-dropdown-item>
            </b-dropdown>
          </div>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<style>
@media screen and (max-width: 992px) {
  .dropdown-btn{
    display: inline;
    margin-left: 15px;
  }
  }

</style>
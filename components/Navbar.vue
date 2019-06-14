<template>
  <b-navbar toggleable="sm" type="light" variant="light">
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
    <b-navbar-brand>
      <img
        src="~/assets/scratch-cat.png"
        class="d-inline-block align-baseline"
        alt="Scratch cat"
        height="35"
      />
      <div class="d-inline-block pl-2">
        #ScratchFest
        <br />
        <small class="text-muted">2019</small>
      </div>
    </b-navbar-brand>
    <b-collapse id="nav-text-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>Home</b-nav-item>
        <b-nav-item>Explore</b-nav-item>
      </b-navbar-nav>
      <form class="mx-2 my-auto d-inline w-100">
        <div class="input-group">
          <input
            type="text"
            class="form-control border border-right-0"
            placeholder="Search..."
          />
          <button class="btn btn-secondary search-btn" type="button">
            <i class="fa fa-search"></i>
          </button>
        </div>
      </form>
      <b-navbar-nav class="d-inline my-auto">
        <b-nav-item>
          <!-- TODO: Fix button sizing -->
          <b-button variant="outline-primary">Sign in</b-button>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<style>
.navbar-brand {
  line-height: 0.95;
}

.search-btn {
  border-radius: 0 0.25rem 0.25rem 0;
}
</style>

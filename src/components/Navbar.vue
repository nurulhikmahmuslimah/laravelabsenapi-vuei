<template>
<div class="container">
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Contact App</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" to="/">home</router-link> 
          </li>
          <li class="nav-item">
             <router-link class="nav-link" to="/jadwals">jadwal</router-link> 
          </li>
          <li class="nav-item">
             <router-link class="nav-link" to="/mahasiswas">mahasiswa</router-link> 
          </li>
          <li class="nav-item">
             <router-link class="nav-link" to="/kontrakmatakuliahs">kontrak matakuliah</router-link> 
          </li>
          <li class="nav-item">
             <router-link class="nav-link" to="/matakuliahs">matakuliah</router-link> 
          </li>
          <li class="nav-item">
             <router-link class="nav-link" to="/semesters">semester</router-link> 
          </li>

        </ul>
      </div>
    </div>
  </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
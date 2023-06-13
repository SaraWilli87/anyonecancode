<template>
  <div id="app">
    <b-navbar fixed-top :mobile-burger="false">
      <template #brand>
        <div id="left"></div>
        <div id="right"></div>
        <div id="top"></div>
        <div id="bottom"></div>
        <b-navbar-item id="fontnavbar" class="title is-2" style ="color: green">
          Sara-GitHub
        </b-navbar-item>
      </template>
    </b-navbar>
    <div class="container">
      <Profile />
      <ImageList />
      <Navbar />
    </div>
  </div>
</template>
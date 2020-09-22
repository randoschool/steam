<template>
  <div class="nav">
    <div class="secondary-nav">
      <div class="download-btn">
        <a href="#">paigalda aur</a>
      </div>
      <a href="#">sisene</a>
      <span>keel</span>
    </div>
    <div class="primary-nav">
      <img
        src="https://steamstore-a.akamaihd.net/public/shared/images/header/globalheader_logo.png?t=962016"
        alt="Steam logo"
      />
      <div class="nav-items">
        <a href="#">pood</a>
        <a href="#">kommun</a>
        <a href="#">meist</a>
        <a href="#">tugi</a>
      </div>
    </div>
  </div>
</template>
<style scoped>
.nav {
  flex: 1;
  background-color: #171a21;
  padding: 0.5rem 10rem 1rem;
}
.primary-nav {
  flex: 1;
  display: flex;
  align-items: center;
}

.secondary-nav {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.nav a,
span {
  color: #b8b6b4;
  text-transform: uppercase;
  margin: 0 1rem;
  text-decoration: none;
}

.nav-items a:hover {
  color: white;
}

.download-btn {
  background-color: #5c7e10;
  padding-top: 10px;
  padding-bottom: 10px;
}

.download-btn a {
  background-image: url(https://steamstore-a.akamaihd.net/public/shared/images/header/btn_header_installsteam_download.png?v=1);
  background-position: 10px 2px;
  background-repeat: no-repeat;
  padding-left: 35px;
  padding-right: 9px;
  color: white;
}
</style>

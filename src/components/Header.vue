<template>
  <div class="header">
    <div class="logo">
      <a href="#"
        ><img
          src="https://secure.gravatar.com/avatar/fabdb283fe15708440314fae08b0e7a1?s=60&d=retro&r=g"
      /></a>
    </div>
     <div class="search">
        <div class="constrain">
          <input class="input" type="text" placeholder="Search" />
        </div>
      </div>
    <header>
     
      <div class="nav">
        <ul>
          <span><li>Documentation</li></span>
          <li>Support</li>
        </ul>
      </div>

      <div class="profile">
        <img src="../images/Dp.png" alt="" />
      </div>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  background: #9370db;
  height: 55px;
  padding-top: 10px;
  display: flex;
 
}
.logo {
  font-size: 18px;
  margin: -10px 5px;
}

header {
  display: flex;
    margin: 10px px;

}
.nav {
}
ul {
  list-style: none;
  margin-left: 30px;
  color: aliceblue;
}
li {
  display: inline-block;
  margin: 5px 20px;
  font-size: 14px;
}
span {
  color: khaki;
}
.logo img {
  margin: 10px 20px;
}
img {
  width: 35px;
  margin-right: 20px;
}
.search {
  display: none;
}
@media only screen and (min-width: 1440px) {
  .header {
  background: #9370db;
   height: 95px;
  padding-top: 10px;
  display: flex;
  justify-content: space-between;
}
.logo img {
width: 45px;
}

header {
  display: flex;
  margin: 30px 40px;
}
.nav {
 
}
ul {
  list-style: none;
  /* margin-left: 90px; */
  color: aliceblue;
}
li {
  display: inline-block;
  margin: 5px 45px;
  font-size: 14px;
}
span {
  color: khaki;
}
.profile img {
  width: 45px;
  margin-right: 40px;
}
.search {
  display: none;
}
  .search {
    max-width: 230px;
    padding: 20px 20px;
    display: inline-block;
  }
  .constrain {
    max-width: 300px;
    /* padding: 60px; */
    margin: 0 -80px;
  }

  input {
    margin-bottom: 40px;
    /* max-width: 300px; */
  }
  .input {
    font-size: 16px;
    line-height: 1.5;
    background: #e9eef0;
    border: 1px solid #d5d9db;
    background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 16 16'><path fill='%238C92A0' d='M11.44 10.73l4.41 4.42a.5.5 0 1 1-.7.7l-4.42-4.41a6.5 6.5 0 1 1 .7-.7v-.01zM6.5 12a5.5 5.5 0 1 0 0-11 5.5 5.5 0 0 0 0 11z'></path></svg>");
    background-repeat: no-repeat;
    background-position: 15px 10px;
    background-size: 20px 20px;
    border-radius: 100px;
    width: 750px;
    padding: 0.5em 1em 0.5em 2.5em;
  }

  .input-grey-rounded::placeholder {
    color: #838d99;
  }

  .input-grey-rounded:focus {
    outline: none;
    border: none;
    background-color: #fff;
    border: 1px solid #84a2fa;
  }
  
}
@media only screen and (max-width: 1280) {
  .search {
    display: ;
  }
}
</style>

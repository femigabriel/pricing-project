<template>
  <div class="main">
    <section>
      <div class="profile-info">
        <div class="profile-name">
          <img src="../images/Dp.png" alt="" />
          <div class="name">
            <h3>Debbie Torera</h3>
            <div class="icon">
              <i class="lab la-github"></i>
              <p>@Debbietorera</p>
            </div>
          </div>
        </div>
        <!-- <div class="icon">
          <i class="lab la-github"></i>
          <p>@Debbietorera</p>
        </div> -->
      </div>
      <div class="button">
        <button class="new">New Project</button>
        <button class="invite">Invite Team</button>
      </div>
      <div class="down-content">
        <div class="flex">
          <div class="icon">
            <i class="las la-registered"></i>
          </div>
          <p>Pro Member</p>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-registered"></i>
          </div>

          <p>8 Projects</p>
        </div>
      </div>
    </section>
  </div>
  <div class="line"></div>
</template>

<script>
export default {};
</script>

<style scoped>
.main {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 10px;
}
@media only screen and (min-width: 1440px) {
  .main {
    height: 350px;
    width: 350px;
  }
}
.profile-name {
  display: flex;
  margin-top: 60px;
}
img {
  width: 95px;
  margin-right: 10px;
}
/* h3 {
margin-right: 10px;
} */
.icon {
  display: flex;
}
.lab {
  font-size: 22px;
}
.button {
  display: flex;
  flex-direction: column;
  margin-top: 20px;
  padding-bottom: 30px;
}
button {
  padding: 10px 15px;
  border: none;
  outline: none;
  border-radius: 3px;
}
.new {
  background: #9370db;
  margin-bottom: 15px;
}
/* .line {
  margin-top: 30px;
  border: 0.5px solid #9370db;
  opacity: 0.5;
} */
/* section {
  border-bottom: 1px solid red;
} */
.flex {
  display: flex;
  color: darkgray;
}
.icon {
  margin-right: 5px;
  margin-top: 5px;
}
.down-content {
  padding-bottom: 20px;
}
</style>

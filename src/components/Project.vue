<template>
  <div class="project">
    <div class="main">
      <div class="privacy-content-1">
        <div class="grid">
          <h3>Projects</h3>
          <div class="sort-btn">
            <button class="btn">
              <i class="las la-sort-amount-up"></i>
              Sort
              <i class="las la-caret-down"></i>
            </button>
          </div>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="lar la-dot-circle"></i>
          </div>
          <h3>Workcation</h3>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <div class="passage">
            <p>Debbietorera/workcation</p>
          </div>
        </div>
        <div class="sort-list">
          <div class="site">
            <h3>Visit Site</h3>

            <div class="sort-info">
              <div class="flex">
                <div class="flex">
                  <i class="lab la-laravel"></i>
                  <div class="icon-name">
                    <p>Laravel</p>
                  </div>
                </div>
                <div class="date">
                  <p>last deploy <span>3 hours ago</span></p>
                </div>
                <div class="state">
                  <p>United state</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="lar la-dot-circle"></i>
          </div>
          <h3>Tailwin CSS</h3>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <div class="passage">
            <p>Debbietorera/workcation</p>
          </div>
        </div>
        <div class="sort-list">
          <div class="site">
            <h3>Visit Site</h3>
            <div class="sort-info">
              <div class="flex">
                <div class="flex">
                  <i class="lab la-react"></i>
                  <div class="icon-name">
                    <p>Reat.JS</p>
                  </div>
                </div>
                <div class="date">
                  <p>last deploy <span>3 hours ago</span></p>
                </div>
                <div class="state">
                  <p>United state</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="lar la-dot-circle"></i>
          </div>
          <h3>Kitetail</h3>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <div class="passage">
            <p>Debbietorera/workcation</p>
          </div>
        </div>
        <div class="sort-list">
          <div class="site">
            <h3>Visit Site</h3>
            <div class="sort-info">
              <div class="flex">
                <div class="flex">
                  <i class="lab la-node-js"></i>
                  <div class="icon-name">
                    <p>Vue.JS</p>
                  </div>
                </div>
                <div class="date">
                  <p>last deploy <span>3 hours ago</span></p>
                </div>
                <div class="state">
                  <p>United state</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="lar la-dot-circle"></i>
          </div>
          <h3>Refactoring UI</h3>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <div class="passage">
            <p>Debbietorera/workcation</p>
          </div>
        </div>
        <div class="sort-list">
          <div class="site">
            <h3>Visit Site</h3>
            <div class="sort-info">
              <div class="flex">
                <div class="flex">
                  <i class="lab la-vuejs"></i>
                  <div class="icon-name">
                    <p>Vue.JS</p>
                  </div>
                </div>
                <div class="date">
                  <p>last deploy <span>3 hours ago</span></p>
                </div>
                <div class="state">
                  <p>United state</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
               <i class="lar la-dot-circle"></i>
          </div>
          <h3>Hero Pattern</h3>
        </div>
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <div class="passage">
            <p>Debbietorera/workcation</p>
          </div>
        </div>
        <div class="sort-list">
          <div class="site">
            <h3>Visit Site</h3>
            <div class="sort-info">
              <div class="flex">
                <div class="flex">
                  <i class="lab la-node"></i>
                  <div class="icon-name">
                    <p>Node.JS</p>
                  </div>
                </div>
                <div class="date">
                  <p>last deploy <span>3 hours ago</span></p>
                </div>
                <div class="state">
                  <p>United state</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <SettingPage class="setting"/>
</template>

<script>
import SettingPage from './SettingPage.vue';
export default {
    components: {
    SettingPage,
  },
};
</script>

<style scoped>
@media only screen and (max-width: 780px){
   .setting {
    display: none;
  }
}

@media only screen and (min-width: 1440px) {
  .project {
    width: 850px;
    display: none;
  }
  .setting{
      width: 850px;
  }
  
  .lar {
    color: greenyellow;
    background: greenyellow;
    border-radius: 50%;

  }
    .privacy-content h3 {
    padding-left: 40px;
  
  }
  .passage p {
    padding-left: 30px;

    
  }
}
  .privacy {
    display: block;
  }
  .privacy-content h3 {
    padding-left: 40px;
    padding-right: 40px;
    color: #222;
  }
  .passage p {
    padding-left: 20px;
    padding-right: 40px;
    color: #999;
  }
  .lab {
    font-size: ;
    padding-right: 40px;
  }

.lar {
    color: greenyellow;
    background: greenyellow;
    border-radius: 50%;
    font-size: 10px;

  }
.privacy-title {
  padding-bottom: 20px;
  padding-top: 20px;
}
.privacy-content {
  border: 1px solid #e5e4e2;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 40px;
  /* border-radius: 5px; */
}


.flex {
  display: flex;
  /* margin-right: 10px; */
}
.grid {
  display: flex;
  justify-content: space-between;
}

.lab {
  font-size: 19px;
  /* margin: 0 40px; */
  padding-right: 20px;
}
.privacy-content-1 {
  background: #f0f8ff;
  border: 1px solid #e5e4e2;
  /* border-radius: 5px; */
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 20px;
}
.las {
  /* padding-left: 20px; */
  font-size: 19px;
}
.sort-info {
  padding-left: 0px;
}
.sort-info p {
  /* padding-right: 15px;  */
  margin: 0px 5px;
}
span {
  /* margin: 40px; */
}
</style>

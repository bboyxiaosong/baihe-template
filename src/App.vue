<template>
  <div id="app">
    <div class="footer">

      <ul class="">
        <router-link to="/home">
          <li>
            <p>首页</p>
          </li>
        </router-link>
        <router-link to="/guarantee">
          <li>
            <p>保障</p>
          </li>
        </router-link>
        <router-link to="/pub">
          <li>
            <p>发布</p>
          </li>
        </router-link>
        <router-link to="/mine">
        <li>
          <p>我的</p>
        </li>
      </router-link>
      <router-view></router-view>
      </ul>
    </div>

  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  li {list-style: none;}
  * {
    margin: 0;
    padding: 0;
  }
.footer{
  width: 100%;
  height: 80px;
  position: fixed;
  bottom: 0;
  left: 0;
  background-color: #ccc;
}
  .footer ul{
    display: flex;
  }

</style>

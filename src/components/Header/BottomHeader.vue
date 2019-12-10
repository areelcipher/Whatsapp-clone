<template>
  <div>
    <div id="cam">
      <i class="fas fa-camera"></i>
    </div>
    <ul>
      <li v-for="menu in menus" :key="menu">
        <a :href="menu.href">{{ menu.name }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menus: [{name: "CHATS", href: "#/chats"}, {name: "STATUS", href: "#/status"}, {name: "CALLS", href: "#/calls"}],
      href: "#/chats",
    
    };
  }
};
</script>

<style scoped>
div {
  display: flex;
  height: 40px;
  color: #fff;
  align-items: center;
}
#cam {
  width: 5%;
  margin-left: 3px;
}
/* .fa-camera {
    width: 5%;
    border: 1px solid red
} */
ul {
  display: flex;
  width: 85%;
  margin: 0 0 0 -20px;
  justify-content: space-between;
}
li {
  list-style: none;
  padding: 9px 0;
}
li:hover {
  border-bottom: 3px solid #fff;
}
li:focus {
  border-bottom: 3px solid #fff;
}
a {
  text-decoration: none;
  color: #fff;
  text-align: center;
  font-size: 12px;
  padding: 0 15px;
}
</style>

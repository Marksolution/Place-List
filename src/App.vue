<script setup>
import Data_Detail from './views/Data_detail.vue';
import DetailVue from './views/Detail.vue';
</script>
<template>
  <section>
    <div>
   
    <nav class="navbar  fixed-top" style="background-color: #134B8A;">
  <div class="container-fluid">
    <a class="navbar-brand"></a>
    <form class="row g-3">
      <div class="col-auto">
    <img style="margin-top: 5px;"  src="https://cdn-icons-png.flaticon.com/128/1827/1827370.png"   :width="sizeicon" :height="sizeicon">
  </div>
  <div class="col-auto">
    <img  src="https://cdn-icons-png.flaticon.com/128/3135/3135715.png"   :width="sizeimg" :height="sizeimg">
  </div>
  <div class="col-auto">
    <label style="color: white;margin-top:5px ;">Akkarapol</label>
  </div>
  <div class="col-auto" >
      <ul class="navbar-nav" style="margin-right: 40px;">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" style="color: white;" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false"></a>
          <ul class="dropdown-menu dropdown-menu-dark">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
      </ul>
  </div>
    </form>
  </div>
</nav>

</div>
    <DetailVue></DetailVue>
    </section>
</template>
<script>
export default {
 name: 'App',
 data(){
   return{
       minisize: 15,
       sizex:151,
       size:60,
       sizeimg:30,
       sizeicon:20,
   }
}
}
</script>


<template>
  <div>
    <div class="row md-5">
      <div class="col-md-4 col-sm-12">
        <!-- navigator -->
        <div class="list-group md-5">
          <router-link tag="li" :to="{name: 'historyLink'}" class="nav-link">
            <a class="list-group-item list-group-item-action">History Orders</a>
          </router-link>
          <router-link tag="li" :to="{name: 'deliveryLink'}" class="nav-link">
            <a class="list-group-item list-group-item-action">Delivery Infor</a>
          </router-link>
          <router-link tag="li" :to="{name: 'orderingGuideLink'}" class="nav-link">
            <a class="list-group-item list-group-item-action">Ordering Guide</a>
          </router-link>
          <router-link tag="li" :to="{name: 'contactLink'}" class="nav-link">
            <a class="list-group-item list-group-item-action">Contact Us</a>
          </router-link>
        </div>
      </div>
      <div class="col-md-8 col-sm-12">
        <!-- nav-content -->
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

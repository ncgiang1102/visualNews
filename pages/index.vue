<template>
  <div class="layout">
    <Header />
    <div class="primary-content">
          <div class="left-page">

          </div>

          <div class="content-wrapper">
            
            <div class="content">
              <Content />
            </div>

            <div class="follow">
              <Follow />
            </div>

          </div>


          <div class="service">
            <Service />
          </div>

          <div class="right-page">

          </div>
    </div>
    


  </div>
</template>

<script>
import Header from '../components/Header.vue';
import Content from '../components/Content.vue';
import Follow from '../components/Follow.vue';
import Service from '../components/Service.vue';
export default {
  components:{
    Header,
    Content,
    Follow,
    Service,
  }
}
</script>

<style scoped>
.primary-content {
  display: flex;
}

.left-page {
  flex: 1;
  /* Nội dung cho phần left-page */
}

.content-wrapper {
  display: flex;
  flex: 8;
}

.content {
  flex: 7.5;
  /* Nội dung cho phần content */
}

.follow {
  flex: 2.5;
  /* Nội dung cho phần follow */
}

.service {
 display: flex;
}

.right-page {
  flex: 1;
  /* Nội dung cho phần right-page */
}

</style>

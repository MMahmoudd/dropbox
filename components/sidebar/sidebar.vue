<template>
  <div class="side-bar">
    <div class="main list">
      <label>Main</label>
      <div class="items">
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/file-icon.png" alt="file icon" />
          <p>File</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/photo-Icon.png" alt="photo icon" />
          <p>Photos</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/Share-Icon.png" alt="Sharing icon" />
          <p>Sharing</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/Link-Icon.png" alt="Links icon" />
          <p>Linkes</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/Calender-icon.png" alt="file icon" />
          <p>Events</p>
        </div>
      </div>
      <!--End Items-->
    </div>
    <!--End main-->
    <div class="dropbox list">
      <label>Also from Dropbox</label>
      <div class="items">
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/Carousel-Icon.png" alt="Carousel icon" />
          <p>Carousel</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/Mailbox-Icon.png" alt="Mailbox icon" />
          <p>Mailbox</p>
        </div>
      </div>
      <!--End Items-->
    </div>
    <!--End dropbox-->
    <div class="labels list">
      <label>Labels</label>
      <div class="items">
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/red-Circle.png" alt="red icon" />
          <p>Design</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/green-Circle.png" alt="photo icon" />
          <p>Web Elemnts</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/blue-Circle.png" alt="Sharing icon" />
          <p>Mobile</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/purple-Circle.png" alt="Links icon" />
          <p>Application</p>
        </div>
        <div class="item d-flex">
          <img src="~/assets/image/sidebar/yellow-Circle.png" alt="file icon" />
          <p>UI / UX</p>
        </div>
      </div>
      <!--End Items-->
    </div>
    <!--End labels-->
    <div class="progress-container">
      <label>1.2 GB OF 2GB IN USED</label>
      <b-progress :value="value" :max="max" class="mb-3"></b-progress>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      value: 33.333333333,
      max: 50
    };
  }
};
</script>
<style>
@media screen and (max-width: 992px) {
  .side-bar .list .item p,
  .progress-container,
  .labels,
  .side-bar .list label{
    display: none;
  }
  .list .item{
    justify-content: center;
  }
  .list{
    padding-top: 40px;
  }
  .list .item img {
    margin-bottom: 20px;
}
}
</style>

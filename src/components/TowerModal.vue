<template>
  <div class="modal fade" id="tower-modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-xl" role="document">
      <div class="modal-content">
        <div class="modal-body">
          <iframe src="/src/assets/video/fullstackVue.client - Google Chrome 2023-02-02 10-28-17.mp4" class="video"></iframe>
        </div>
      </div>
    </div>
  </div>
  </template>
  
  
  <script>
  import { AppState } from '../AppState';
  import { computed, reactive, onMounted } from 'vue';
  export default {
    setup(){
    return {  }
    }
  };
  </script>
  
  
  <style lang="scss" scoped>
  
  .modal-body{
    height: 70vh;
    padding: 0;
  }
  .video{
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }
  </style>
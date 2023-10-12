<template>
  <div class="container my-4 px-5">
  <div class="icons">
    <div class="settings off cursor-pointer">
      <i class="fas fa-cog" @click="showSettings()"></i>
    </div>
  </div>
</div>
</template>

<script>
export default{
  data() {
    const settings = document.querySelector('.fa-cog');
    return{
      methods: {
        showSettings()  {
          settings.addEventListener('click', () => {
            settings.classList.remove('.off')
            settings.classList.add('.on')
            console.log(settings);                                            
          })
        }
        
      },

    }
  }
}
</script>
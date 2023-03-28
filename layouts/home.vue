<template>
    <div> 
        <div v-if="isLoading">
            <Loading/>
        </div>
        <div v-if="isPage">
            <NavbarHome />
            <div class="mt-3">
                <Nuxt />
            </div>
        </div>
    </div>
</template>

<script>
 export default {
      data() {
          return {
            isLoading:true,
            isPage:false
          }
      }, 
      mounted(){
            setTimeout(() => {
            this.isLoading = false
            this.isPage = true
            }, 4000)
        }
    }
</script>

<style scoped>
        
</style>
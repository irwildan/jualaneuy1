<template> 
    <main>
        <div class="container">
           <navigasi />
               <div class="jumbotron">
                 <h1>Selamat Datang Di Toko Saya</h1>
                </div>
               </div>
         </main>
    </template>

<script>
export default {
  mounted(){
    console.log(this.$supabase)
  }
}
</script>

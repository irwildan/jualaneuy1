<template>
  <div class="container">
    <navigasi />
      <div class="jumbotron">
        <h1>Products</h1>
      </div>
      <div class="row">
      <div class="col-md-12">
            <div v-if="loading" class="text-center">
              <img src="~/static/assets/loading.gif" alt="">
            </div>
          </div>
        <div class="row">
          <div class="col-md-4" v-for="item in items" :key="item.id">
            <div class="card mb-3">
              <div class="card-header">
                <img :src="item.foto" width="100%">
              </div>
              <div class="card-body">
                <h4>{{ item.nama }}</h4>
                <h4>Rp{{ item.harga }}</h4>
                <a :href="item.link_eksternal" class="btn btn-success btn-block"
                  >Pesan Lewat Wildan</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      items: '',
      loading: true,
    }
  },
  mounted() {
    this.ambilData()
  },
  methods: {
    async ambilData() {
      const { data, error } = await this.$supabase
        .from('tb_produk')
        .select()
      if(data) 
      this.items = data
      this.loading = false
      if(error) console.log(error)
    }
  }
}
</script>
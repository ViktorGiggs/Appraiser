<template>
  <div class="homepage">

    <h2 class="text-center central-text text-over text-down">List Of All Establishments</h2>
    
    <div class="container mt-3 text-over text-center">
      <div class="row">
        <div class="col">
          <ListCarpet/>
        </div>
        <div class="col">
          <ListRealty/>
        </div>
        <div class="col mb-3">
          <ListTechnic/>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  layout: 'firstpage',
  name: 'IndexPage'
}
</script>
<template>
  <div>
      <h3 class="card-title"> {{ title }} </h3>
  </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: 'ini title',
        }
    }
}
</script>

<style>

</style>
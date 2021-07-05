<template>
  <div class="h-full">
      <img :src="'./' + imageLink" alt="" class="rounded-md cursor-pointer shadow-lg object-cover h-full w-full">
  </div>
</template>

<script>
export default {
props: {
    imageLink: {
        type: String
    },
},
}
</script>

<style>

</style>
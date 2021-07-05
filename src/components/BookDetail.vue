<template>
<svg class="w-7 h-7 ml-auto mb-6 cursor-pointer" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" @click="closeDetail"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
  <div>
      <div class="relative">
      <img :src="'./' + activeBook.imageLink" alt="" class="rounded-md shadow-lg object-cover h-auto w-full">
<span class="bg-pink-600 text-white py-1 rounded-full px-2.5 absolute bottom-2 right-3">{{activeBook.year}}</span>
      </div>

      <div class="py-5">
        <h3 class="text-gray-800 text-xl font-semibold">{{activeBook.title}}</h3>
       <h4 class="text-gray-400 text-base mt-1 mb-4">{{activeBook.author}}</h4>
       <p>Country: {{activeBook.country}}</p>

           <p class="my-2">Language: {{activeBook.language}}</p>
          <p> Count of pages: {{activeBook.pages}}</p>

  <a :href="activeBook.link" class="text-white inline-block mt-8 bg-gray-600 capitalize hover:bg-pink-600 transition-colors duration-200 py-2 px-4 rounded-sm shadow-sm" target="_blank">view more</a>
      </div>
  </div>
</template>

<script>
export default {
props: {
    activeBook: {
        type: Object
    },

},
    methods: {
        closeDetail() {
            this.$emit('closeDetail')
        }
    },
}
</script>

<style>

</style>
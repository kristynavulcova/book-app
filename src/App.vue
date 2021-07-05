<template>
<div class="container-app"> 
    <div class="sidebar w-72 bg-gray-100 p-8 transition duration-200 hidden invisible lg:visible lg:flex lg:flex-col lg:flex-shrink-0 ">
    <div class="logo font-bold text-3xl">
      bookie
    </div>

    <div class="pt-16 pb-14 text-center">
       <img src="/user.jpeg" alt="User" class="rounded-full w-24 h-24 border-pink-500 border-2 p-1.5 mx-auto">
     <div class="mt-3 mb-7">
         <h3 class="font-semibold text-xl">Jennifer Doe</h3>
       <span class="text-sm text-gray-400">New York, NY</span>
     </div>

       <ul class="flex text-sm">
         <li class="p-1 font-semibold">
           Post
           <span class="font-normal">200</span>
           </li>
             <li class="p-1 font-semibold mr-3 ml-3">
           Followers
           <span class="font-normal">20m</span>
           </li>
             <li class="p-1 font-semibold">
           Following
           <span class="font-normal">42m</span>
           </li>
       </ul>
    </div>
    
    <nav class="h-full overflow-x-hidden overflow-y-auto">
      <ul>
        <li class="text-pink-500 font-semibold flex items-center mb-5 py-1">
          <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
          Home
        </li>
       <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
     <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
          Explore
        </li>
              <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
    <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 20l4-16m2 16l4-16M6 9h14M4 15h14"></path></svg>
          Trending Tags
        </li>
              <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
 <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg>
          Top Book
        </li>
           <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
<svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"></path></svg>
         People
        </li>
           <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
<svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
         Notification
        </li>
           <li class="text-gray-400 font-semibold flex items-center mb-5 py-1">
<svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"></path></svg>
         Stats
        </li>
           <li class="text-gray-400 font-semibold flex items-center py-1">
<svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
         Settings
        </li>
      </ul>
    </nav>
  </div>
  <div class="wrapper flex flex-col flex-grow">
 <header class="w-full">
  <div class="navbar flex flex-col md:flex-row justify-between p-8 flex-shrink-0">
<div>
  <input type="text" class="search focus:outline-none border py-2 px-4 rounded-sm w-full md:w-80" placeholder="Search">
</div>
<div class="flex items-center justify-center md:justify-start my-6 md:my-0">
    <button class="relative capitalize text-white bg-pink-600 w-10 h-10 rounded-full flex items-center justify-center shadow-lg focus:outline-none hover:bg-pink-500 transition-colors duration-200 xl:hidden xl:invisible"><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path></svg></button>
  <button class="invisible hidden xl:visible xl:inline-block btn relative capitalize text-white bg-pink-600 py-2 pr-5 xl:pl-10 rounded shadow-lg focus:outline-none hover:bg-pink-500 transition-colors duration-200">create new book</button>
  <svg class="w-7 h-7 mx-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
  <img src="/user.jpeg" alt="User" class="rounded-full w-10 h-10">
  <svg class="w-4 h-4 ml-2 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
</div>
  </div>
    </header>
    <div class="flex overflow-auto md:overflow-hidden h-full">
    <main class="flex flex-col flex-grow h-full flex-shrink overflow-auto">
     <div>
          <h2 class="font-semibold text-2xl capitalize pl-8">featured books</h2>
  <div class="grid grid-cols-2 sm:grid-cols-4 gap-7 py-5 px-8 place-items-center">

       <BookCard v-for="book in latestBooks" :key="book.title" :imageLink="book.imageLink" @click="showBook(book)" />
    </div>
      </div>
         <div>
      <h2 class="font-semibold text-2xl capitalize pl-8 mt-5">latest books</h2>
       <div class="grid grid-cols-2 sm:grid-cols-5 gap-7 py-5 px-8 place-items-center">
     
     <BookCard v-for="book in books" :key="book.title" :imageLink="book.imageLink" @click="showBook(book)" />
    </div>


      </div>
 

</main>

<aside class="p-8 w-56 h-full bg-white absolute top-0 right-0 md:static md:w-72 flex-shrink-0 border-l transition duration-200 overflow-auto" v-if="showDetail">
   <BookDetail :activeBook="activeBook" @closeDetail="showDetail = false" />
</aside>
    </div>

  </div>

 



 </div>
</template>

<script>
import mojeData from "./shared/data"
import BookCard from "./components/BookCard.vue"
import BookDetail from "./components/BookDetail.vue"

export default{
  components: {
    BookCard,
    BookDetail,
  },
  data() {
    return {
      showDetail:false,
      activeBook:mojeData[0],
      books: mojeData.slice(4,34),
      latestBooks: mojeData.slice(0,4)
    }
  },
  methods: {
    showBook(book) {
      this.activeBook = book
      this.showDetail = true
    }
  },
}
</script>

<style>
::-webkit-scrollbar {
 width: 6px;
 border-radius: 10px;
}

::-webkit-scrollbar-thumb {
 background-color: rgb(21 20 26 / 63%);
 border-radius: 10px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 1em 2em;
    width: 100%;
    height: 100vh;
    overflow: hidden;

}
.container-app{
    max-width: 1400px;
    max-height: 900px;
    height: 95vh;
    display: flex;
    overflow: hidden;
    width: 100%;
    border-radius: 20px;
    font-size: 15px;
    font-weight: 500;
    box-shadow: 0 20px 50px rgb(0 0 0 / 30%);
    position: relative;
}
.search{
  background:white url("../search.svg") no-repeat right .8em center;
}
.btn{
  background:white url("../plus.svg") no-repeat left .8em center;
}

</style>
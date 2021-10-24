<template>
<div class="app-header">
    <div class="grid grid-cols-12">  <!-- tailwind grid for app header -->
        <div class="col-span-4"></div>

        <div class="col-span-8">
            <div class="bg-red-600 max-w-xl rounded-md justify-self-center"><!-- marging just for display-->
                <div class="max-w-lg mx-auto">
                    
                    <form action="#" class="mt-2">

                        <div class="flex items-center md:flex">
                           <div class="dropdown inline-block relative">
                                <button class="bg-red-600 text-white font-semibold py-3 px-4 rounded
                                 inline-flex items-center" style="margin-left: -7.8rem;">
                                <span class="mr-1">Categories</span>
                                <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/> </svg>
                                </button>
                                <ul class="divide-y-2 divide-white dropdown-menu absolute hidden text-white pt-1 w-40" style="margin-left: -7.8rem;">
                                <nuxt-link to="" class=" text-white rounded-t bg-red-600 hover:bg-gray-400 py-2 px-4 block whitespace-no-wrap" >One</nuxt-link>
                                <nuxt-link to="" class=" text-white rounded-t bg-red-600 hover:bg-gray-400 py-2 px-4 block whitespace-no-wrap" >Two</nuxt-link>
                                <nuxt-link to="" class=" text-white rounded-t bg-red-600 hover:bg-gray-400 py-2 px-4 block whitespace-no-wrap" >Three is the magic number</nuxt-link>
                                
                                </ul>
                            </div>

                            <input type="text" class="w-full py-2 
                            bg-white shadow-inner rounded-md border 
                            border-red-500 focus:outline-none">
                            
                        
                        <!--search icon-->
                        <button type="submit" class=" mr-1 outline-none focus:outline-none active:outline-none">
                        <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            viewBox="0 0 24 24" class="w-6 h-6 text-white">
                            <path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                        </svg>
                        </button>
                        </div>
                    </form>
                 </div>
            </div>
        </div>
    </div>
    </div>
</template>   

 <script>
 export default {
     
 }
 </script>

 <style>
    .dropdown:hover .dropdown-menu {
    display: block;

    }
 </style>
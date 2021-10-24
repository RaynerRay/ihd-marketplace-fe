<template>
    <div id="registration">

            <!-- Form -->
            <div class="divide-y divide-y-reverse divide-rose-400">
                    <div class=" mt-6 py-2 px-2 
                        text-gray-700 text-sm leading-tight "
                        > Verify email address</div>
                        <div> </div>
                </div>
            <div class='flex max-w-lg w-full bg-white  rounded-lg overflow-hidden mx-auto mt-6'>
                
                
              <div class='flex items-center px-2 py-3'>
               <form class="w-full max-w-lg">
                    <div class="md:flex md:items-center mb-6">
                        <div class="md:w-2/4">
                        <label class="block text-gray-500 text-sm font-light md:text-right mb-1 md:mb-0 pr-4" for="inline-full-name">
                        <span class="text-red-600">*</span>
                            Email:
                        </label>
                        </div>
                        <div class="md:w-2/4 w-full">
                        <p class=" px-2 
                        text-gray-700 text-sm leading-tight "
                        > chans.aliecom@gmail.com</p>
                        </div>
                    </div>
            

            <!--confirm password-->
            <div class="md:flex md:items-center mb-6">
                <div class="md:w-2/4">
                <label class="block text-gray-500 text-sm font-light md:text-right mb-1 md:mb-0 pr-4"
                 for="inline-password">
                    <span class="text-red-600">*</span>
                    Verification Code:
                </label>
                </div>
                <div class="md:w-2/4">
                <input class="bg-white appearance-none border border-gray-200 rounded w-full py-2 px-4 
                text-gray-700 text-sm leading-tight focus:outline-none focus:bg-white focus:border-red-500" 
                id="inline-password" type="text" placeholder="Input checkcode">
                </div>
            </div>

            
            <div class="md:flex md:items-center">
                <div class="md:w-2/4"></div>
                <div class="md:w-2/4">
                <button class="shadow bg-red-500 hover:bg-red-400 focus:shadow-outline focus:outline-none text-white font-light py-2 px-4 rounded" type="button">
                    Submit
                </button>
                </div>
            </div>
            </form>
        </div>
    </div>
</div>
</template>

<style scoped>

html {
  background-color: #ffffff;
}


</style>
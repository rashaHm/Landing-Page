<script setup lang="ts">
</script>

<template>
  <div class="bg-[#a64d2e]">
    <div class="max-w-4xl pt-2 mx-auto">
      <div class="text-xs text-white ">
        <div class="flex justify-center md:space-x-2  text-[12px] md:flex-row md:justify-end">
          <div><a href="#">lorem1</a> |</div>
          <div><a href="#"> lorem2</a> |</div>
          <div><a href="#"> lorem3</a> |</div>
          <div><a href="#"> lorem5</a> |</div>
          <div><a href="#"> lorem6</a></div>
        </div>
      </div>

      <div class="flex flex-col md:flex-row md:justify-between">
        <div class="relative">
          <h1 class="mt-3 text-2xl tracking-tighter text-center text-white md:text-lg md:mt-0 md:text-left md:text-2xl">
            Lorem ipsum dolor.
          </h1>
          <p class="tracking-tighter text-center text-gray-500 md:absolute md:text-left md:top-5 top-6">
            Consectetur adipi
          </p>
        </div>

        <div class="relative justify-center text-center">
          <input  class="p-1 md:mt-3 md:mt-5 mt-3  text-xs placeholder-gray-500 rounded-lg placeholder:text-[14px]" type="text" placeholder="Search Here">
        </div>
      </div>
      
      <div class="w-full h-8 p-1 mt-4 bg-white rounded-lg">
        <div class="items-center justify-around hidden text-sm md:flex md:flex-row ">
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">lorem</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">Ipsum dolor</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">sit amet consectetur</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">adipisicing elit</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">Nam expedita beatae illum</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">temporibus deserunt</a>
          <a class="mt-1 hover:text-[#55ABDA] focus:text-[#55ABDA] text-xs uppercase" href="#">Cumque, adipisci</a>
        </div>
        
      </div>

      <div class="p-2 mt-4 bg-white rounded-lg md:h-64">
        <div class="relative pt-20 bg-orange-400 rounded-t-lg md:pt-0 md:h-3/4">
          <div class="hidden p-3 bg-orange-200 rounded-lg md:w-64 md:block md:absolute hover:bg-white backdrop-opacity-10 top-5 right-5">
            <h3 class="text-xs">Lorem, ipsum dolor</h3>
            <p class="text-[14px] mt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum saepe unde.</p>
            <a class="float-right mt-3 text-[14px] text-blue-500" href="#">Ipsum dolor »</a>
          </div>
        </div>

        <div class="flex flex-col bg-[#DEDACB]  md:space-x-0  md:flex-row md:h-1/4">
          <a href="#" class="p-3 w-full flex justify-center items-center active hover:text-white hover:bg-[#a64d2e] border-[1px] border-[#666666] text-xs tracking-tighter text-center">Lorem, ipsum dolor.</a>
          <a href="#" class="p-3 w-full flex justify-center items-center hover:text-white hover:bg-[#a64d2e] border-[1px] border-[#666666] text-xs tracking-tighter text-center">Lorem ipsum dolor sit.</a>
          <a href="#" class="p-3 w-full flex justify-center items-center hover:text-white hover:bg-[#a64d2e] border-[1px] border-[#666666] text-xs tracking-tighter text-center">Lorem, ipsum.</a>
          <a href="#" class="p-3 w-full flex justify-center items-center hover:text-white hover:bg-[#a64d2e] border-[1px] border-[#666666] text-xs tracking-tighter text-center">Lorem ipsum dolor sit amet.</a>
          <a href="#" class="p-3 w-full flex justify-center items-center hover:text-white hover:bg-[#a64d2e] border-[1px] border-[#666666] text-xs tracking-tighter text-center">Lorem, ipsum dolor.</a>
        </div>

      </div>

      <div class="flex flex-col mt-6 bg-white rounded-lg">
      <div class="flex flex-col justify-between p-2 pb-3 md:flex-row ">
        <div class="flex flex-col justify-start w-full md:space-x-4 md:flex-row">
          <!--------- First section------------->
          <div class="flex flex-col pt-3 pl-2 md:basis-1/4">
            <div>
              <div class="w-full pl-0 border-b-2">
                <h5 class="text-xs text-left text-blue-500">Lorem, ipsum.</h5>
              </div>
              <div class="mt-3 md:w-full ">
                <div class="h-16 max-w-sm mr-5 bg-gray-500 md:mr-0 md:w-full"></div>
              </div>
            </div>

            <div>
              <div class="w-full p-1 pl-0 border-b-2">
                <h5 class="text-xs text-left text-blue-500">Lorem, ipsum.</h5>
              </div>
              <div class="mt-3 md:w-full ">
                <div class="h-16 max-w-sm mr-5 bg-gray-500 md:mr-0 md:w-full"></div>
              </div>
            </div>

            <div>
              <div class="w-full p-1 pl-0 border-b-2">
                <h5 class="text-xs text-left text-blue-500">Lorem, ipsum dolor.</h5>
              </div>
              <div class="mt-3 md:w-full ">
                <div class="h-16 max-w-sm mr-5 bg-gray-500 md:mr-0 md:w-full"></div>
              </div>
            </div>

            <div>
              <div class="w-full p-1 pl-0 border-b-2">
                <h5 class="text-xs text-left text-blue-500">lorem</h5>
              </div>
              <div class="mt-3 md:w-full ">
                <div class="h-16 max-w-sm mr-5 bg-gray-500 md:mr-0 md:w-full"></div>
              </div>
            </div>
                        
        
          </div>
          <!--------- Second section------------->
            <div class="flex flex-col pt-3 pl-2 md:basis-2/4">
              <div>
                <div class="w-full pl-0 border-b-2">
                  <h5 class="text-xs text-left text-gray-500">Lorem ipsum dolor sit.</h5>
                </div>
              </div>

              <div class="flex flex-col pb-3 pl-0 mt-3 space-x-0 space-y-3 border-b-2 md:space-x-3 md:space-y-0 md:flex-row">
                <div class="w-1/2 h-24 bg-gray-500"></div>
                <div>
                  <h5 class="text-[14px] text-blue-500 mb-2">Lorem ipsum dolor sit</h5>
                  <p class=" text-[14px] text-gray-500 ">Lorem ipsum dolor sit amet adipisicing elit sit amet consectetur adipisicing elit.</p>
                </div>
              </div>

              <div class="flex flex-col pb-3 pl-0 mt-3 space-x-0 space-y-3 border-b-2 md:space-x-3 md:space-y-0 md:flex-row">
                <div class="w-1/2 h-24 bg-gray-500"></div>
                <div>
                  <h5 class="text-[14px] text-blue-500 mb-2">Lorem ipsum dolor sit</h5>
                  <p class=" text-[14px] text-gray-500 ">Lorem ipsum dolor sit amet adipisicing elit sit amet consectetur adipisicing elit.</p>
                </div>
              </div>

              <div class="flex flex-col pb-3 pl-0 mt-3 space-x-0 space-y-3 border-b-2 md:space-x-3 md:space-y-0 md:flex-row">
                <div class="w-1/2 h-24 bg-gray-500"></div>
                <div>
                  <h5 class="text-[14px] text-blue-500 mb-2">Lorem ipsum dolor sit</h5>
                  <p class=" text-[14px] text-gray-500 ">Lorem ipsum dolor sit amet adipisicing elit sit amet consectetur adipisicing elit.</p>
                </div>
              </div>
              <div class="p-2 text-[14px] text-blue-500">
                Click here to view all »
              </div>

            </div>
          <!--------- Third section------------->
          <div class="flex flex-col pl-2 md:basis-1/4">
            <div>
              <div class="w-full pt-3 pl-0 border-b-2">
                <h5 class="text-xs text-left text-gray-500">Lorem, ipsum.</h5>
              </div>
              <div class="w-full h-32 mt-3 bg-black"></div>
              <div class="mt-2 text-[14px] text-blue-500">Consectetur adipisicing</div>
            </div>

              <div class="w-full p-1 pl-0 mt-5 border-b-2">
                <h5 class="text-xs text-left text-gray-500">Sit amet consectetur adipisicing</h5>
              </div>

              <div class="flex flex-row mt-3 space-x-0 ">
                <div class="w-1/3 h-16 bg-gray-500"></div>
                <div class="w-2/3 text-center text-wrap flex items-center font-bold  justify-center hover:bg-[#a64d2e] hover:text-white text-[14px] bg-gray-300"><p>Lorem, ipsum dolor.</p></div>
              </div>

              <div class="flex flex-row mt-3 space-x-0 ">
                <div class="w-1/3 h-16 bg-gray-500"></div>
                <div class="w-2/3 text-center text-wrap flex items-center font-bold  justify-center hover:bg-[#a64d2e] hover:text-white text-[14px] bg-gray-300"><p>Lorem, ipsum dolor.</p></div>
              </div>
          </div>
        </div>
      </div>

      <div class="bg-[#a64d2e] flex flex-col md:flex-row md:p-5 m-3 p-5 md:space-y-0 space-y-2  rounded-lg">
        <div class="flex items-center justify-center md:w-1/4 md:border-white p-1 md:p-3 w-full md:border-r-2 text-[#55ABDA]">Lorem</div>
        <div class="flex items-center justify-center w-3/4 w-full p-1 text-xs text-white text-wrap md:p-3">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Lorem ipsum dolor sit amet.
        </div>
      </div>

      <div class="p-3 pl-0 ml-5 mr-5 border-b-2 ">
        <h5 class="text-lg text-left text-gray-500">Lorem ipsum dolor sit amet consectetur.</h5>
      </div>

      <div class="flex flex-col p-5 space-y-3 md:space-y-0 md:flex-row md: justify-items-start md:justify-between ">
        <div class="flex flex-col space-y-0 justify-left">
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet consectetur.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem, ipsum dolor.</a>
        </div>

        <div class="flex flex-col space-y-0 justify-left">
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet consectetur.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem, ipsum dolor.</a>
        </div>

        <div class="flex flex-col space-y-0 justify-left">
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem ipsum dolor sit amet consectetur.</a>
          <a class="cursor-pointer text-[14px] text-blue-500" herf="#">Lorem, ipsum dolor.</a>
        </div>
      </div>
    <!----------  box white ----------------->
    </div>

    <div class="flex flex-col mt-6 bg-white rounded-lg">

      <div class="flex flex-col p-6 space-y-3 md:space-y-0 md:flex-row md: justify-items-start md:justify-between ">
        <div class="flex flex-col justify-center space-y-2">
          <div class="w-full h-24 bg-gray-500 rounded-lg"></div>
          <a class="cursor-pointer text-[14px] text-blue-500">Lorem ipsum dolor sit amet. »</a>
        </div>

        <div class="flex flex-col space-y-3 justify-left">
          <div>
            <p class="cursor-pointer text-[14px] text-gray-500">Country Name</p>
            <p class="cursor-pointer text-[14px] text-gray-500">Address Line 2</p>
            <p class="cursor-pointer text-[14px] text-gray-500">Town/City</p>
            <p class="cursor-pointer text-[14px] text-gray-500">Postcode/Zip</p>
          </div>
          <div>
            <p class="cursor-pointer text-[14px] text-gray-500">xxxxx-xxxxx</p>
            <p class="cursor-pointer text-[14px] text-gray-500">test@test.test</p>
          </div>
        </div>

        <div class="flex flex-col space-y-4 justif-center">
          <div class="flex flex-col space-y-1">
            <a class="cursor-pointer  text-[14px] text-gray-500" herf="#">Lorem, ipsum.</a>
            <div class="flex flex-row justify-between space-x-2">
              <div class="w-12 h-12 bg-gray-500 rounded-md"></div>
              <div class="w-12 h-12 bg-gray-500 rounded-md"></div>
              <div class="w-12 h-12 bg-gray-500 rounded-md"></div>
              <div class="w-12 h-12 bg-gray-500 rounded-md"></div>
              <div class="w-12 h-12 bg-gray-500 rounded-md"></div>
            </div>
          </div>
          
          <div class="flex flex-col space-y-1">
            <a class="cursor-pointer  text-[14px] text-gray-500" herf="#">Lorem ipsum dolor sit.</a>
            <input  class="p-1 md:mt-3 md:mt-5 mt-3 bg-gray-300 p-2 text-xs placeholder-gray-500 rounded-lg placeholder:text-[14px]" type="text" placeholder="Enter your email!">
          </div>
        </div>
      </div>
    </div>

      <div class="text-[#55ABDA] text-[12px] mt-2 pb-2 items-center sp flex flex-col md:flex-row md:justify-between">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        </p>
        <p>
          Lorem, ipsum dolor.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>

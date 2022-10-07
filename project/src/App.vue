<template>
  <nav class="w-100 m-0 text-center p-10 pb-8 flex justify-between bg-white shadow-md ">   
    <div class="flex space-x-16 justify-start">
      <img class = "w-12 h-12" src="public\logo.png">
      <div>
        <ul class="flex space-x-7  text-green-900 text-lg pt-2">
          <li><a class="" href="#">Página Inicial</a></li>
          <li><a href="#">Produtos</a></li>
          <li><a href="#">Nos Conheça</a></li>
          <li><a href="#">Fale Conosco</a></li>
        </ul>
      </div>
    </div>

    <!-- Barra de Pesquisa-->
    
    
    <div class="flex items-center justify-end space-x-5">
      <div class="flex relative pr-2">
        <input class="border-2 border-gray-300 h-10 pr-20 rounded-lg text-sm focus:outline-none pl-6" type="text" placeholder="Search">
        <span class="absolute pt-2 pl-1 ">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 text-gray-400 ">
            <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 100 11 5.5 5.5 0 000-11zM2 9a7 7 0 1112.452 4.391l3.328 3.329a.75.75 0 11-1.06 1.06l-3.329-3.328A7 7 0 012 9z" clip-rule="evenodd" />
            </svg>
            
          </span>
      </div>
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      <!--
        <div class=" relative py-1 px-2 rounded-lg border-gray-500 mx-auto">
          <input class="pl-7 font-medium focus:outline-none" type="text" placeholder="Search"> 
          <span class="absolute inset-1.5 w-auto">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 text-gray-400 ">
            <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 100 11 5.5 5.5 0 000-11zM2 9a7 7 0 1112.452 4.391l3.328 3.329a.75.75 0 11-1.06 1.06l-3.329-3.328A7 7 0 012 9z" clip-rule="evenodd" />
            </svg>
          </span>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 text-gray-500 cursor-pointer">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0" />
       </svg>
       -->

      <!-- Foto de Usuário-->
      <img class="flex-none w-12 h-12 rounded-full object-cover cursor-pointer" src="public\foto.png">
    </div>
  </nav>



</template>
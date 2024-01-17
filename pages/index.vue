<template>
  
  
  <div>
    <Hero/>
    <div class="grid grid-cols-1 md:grid-cols-4 p-4 md:p-10">
      <div class="hidden md:block bg-white  col-span-1 flex justify-center">
        <div>Serach by any</div>
      </div>
      <div class="col-span-3">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-10 md:px-20">
          <Card/>
          <Card/>
          <Card/>
          <Card/>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
div{
  
}
</style>
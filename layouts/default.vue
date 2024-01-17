<template>
  <div class="min-h-screen flex flex-col bg-slate-50">
    <HeaderNavbar/>
    <div class="flex-grow">
      <slot/>
    </div>
    <div>Footer</div>
  </div>
</template>
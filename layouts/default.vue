<template>
  <div class="min-h-screen flex flex-col gap-20">
    <HeaderNavbar/>
    <div class="flex-grow">
      <slot/>
    </div>
    <div>Footer</div>
  </div>
</template>
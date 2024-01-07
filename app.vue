<template>
  <div>
  <NuxtLayout>
    <ul class="flex justify-between p-10">
      <li>
        <NuxtLink to="/">Home</NuxtLink>
       
      </li>
      <li>
        <NuxtLink to="/events">events</NuxtLink>
      
      </li>
      <li>
        <NuxtLink to="/events/12">event id</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/signup">Signup</NuxtLink>
      </li>
    </ul>
    <NuxtPage/>
  </NuxtLayout>
  </div>
</template>

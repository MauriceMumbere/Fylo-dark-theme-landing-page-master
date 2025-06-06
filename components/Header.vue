<template>
  <!-- Header -->
  <header
    class="flex justify-between items-center px-5 md:px-[4rem] py-7 md:pt-[5rem] bg-navy-850"
  >
    <!-- Logo -->
    <div>
      <img class="h-7" src="../public/images/logo.svg" alt="Logo" />
    </div>
    <!-- Navigation -->
    <nav>
      <!-- Link -->
      <ul class="space-x-5 flex md:space-x-10">
        <li>
          <NuxtLink to="#">Features</NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">Team</NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">Sign In</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

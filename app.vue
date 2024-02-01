<template>
  <nav>
    <ul>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
        <NuxtLink to="/admin/auth/login">Admin</NuxtLink>
      </li>
    </ul>
  </nav>
  <div>
    <NuxtPage />
  </div>
</template>

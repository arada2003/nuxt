<template>
    <div class="flex flex-row text-3xl">
      Hello world!
      <NuxtLink to="/name">name</NuxtLink>
      <NuxtLink to="/product">product</NuxtLink>
      <NuxtLink to="/product/item">item</NuxtLink>
    </div>
    <div>
        <slot />
    </div>
  </template>
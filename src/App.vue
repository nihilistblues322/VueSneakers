<script setup></script>
<template>
  <div class="bg-white w-4/5 m-auto h-screen rounded-xl shadow-xl mt-14">
    <header class="flex justify-between border-b border-slate-300 px-8">
      <div class="flex items-center gap-4">
        <img src="/logo.png" alt="logo" class="w-10 mr-5" />
        <div>
          <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
          <p class="text-slate-500">Магазин лучших кроссовок</p>
        </div>
      </div>
      <ul>
        <li>
          <img src="/cart.svg" alt="cart" />
          <b>1205 руб. </b>
        </li>
      </ul>
      <ul>
        <li>
          <img src="/heart.svg" alt="heart" />
          <b>Закладки</b>
        </li>
      </ul>
      <ul>
        <li>
          <img src="/profile.svg" alt="profile" />
          <b>Профиль</b>
        </li>
      </ul>
    </header>
  </div>
</template>

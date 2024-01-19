<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('+')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские кроссовки Nike Blazer Mid Suede"
      imageUrl="/sneakers/sneakers-1.jpg"
      :price="5000"
      :isFavorite="false"
      :onClickAdd="onClickAdd"
      :isAdded="true"
    />
 
  </div>
</template>

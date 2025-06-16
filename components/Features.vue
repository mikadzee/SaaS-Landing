<template>
  <BaseSection class="features">
    <div class="cards">
      <CommonCard v-for="card of cardsData" :image="card.image" :title="card.title" :description="card.description" />
    </div>
  </BaseSection>
</template>

<script setup>
import cardImage1 from '@/assets/images/icons/Cards icon.png';
import cardImage2 from '@/assets/images/icons/Coin icon.png';
import cardImage3 from '@/assets/images/icons/Purse icon.png';
  const cardsData = [
    {
      image: cardImage1,
      title: 'Customizable card',
      description: 'Custom your own card for your exact incomes and expenses needs.'
    },
    {
      image: cardImage2,
      title: 'No payment fee',
      description: 'Transfer your payment all over the world with no payment fee.'
    },
    {
      image: cardImage3,
      title: 'All in one place',
      description: 'The right place to keep your credit and debit cards, boarding passes & more.'
    },

  ]
</script>

<style scoped>
@import "./features.less";
</style>
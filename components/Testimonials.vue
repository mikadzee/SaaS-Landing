<template>
  <BaseSection class="testimonials bg-2">
    <div class="wrapper">
      <div class="info">
        <p class="text-average is-black">“Wallet is a great product! All of my most important information is there - credit cards, transit cards, boarding passes, tickets, and more. And I don't need to worry because it's all in one place! thanks!”</p>
        
        <div class="reviews">
          <div class="review">
            <img class="avatar" src="@/assets/images/Mask Group.png"/>
  
            <div class="statistic">
              <p class="text-average is-black">Johnny Owens</p>
              <div class="stars">
                <IconsStar v-for="stars in 5" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </BaseSection>
</template>

<style scoped>
@import "./testimonials.less";
</style>
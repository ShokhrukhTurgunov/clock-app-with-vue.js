<template>
  <div class="home">
    <div class="container">
      <article class="quote-article">
        <div class="quote-box">
        <p class="quote">“The science of operations, as derived from mathematics more especially, is a science of itself, and has its own abstract truth and value.”</p>
        <a class="author-link" href="#">Ada Lovelace</a>
        </div>
        <button class="reolad-quote-btn"></button>
      </article>

      <article class="time-article">
        <div>
          <p class="greeting-time">GOOD MORNING, IT’S CURRENTLY</p>
          <time class="time">11:37<span>BST</span></time>
          <p class="place-time">IN LONDON, UK</p>
        </div>

        <div class="btn-box">
          <p class="btn-text">MORE</p>
          <button class="more-btn"></button>
        </div>
      </article>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  
}
</script>

<style scoped>
.quote-article{
  display: flex;
  margin-bottom: 200px;
}

.home{
  padding-top: 56px;
  padding-bottom: 98px;
  background: url("../assets/background-day.png") no-repeat center center;
  background-size: cover;
}

.quote{
  margin: 0;
  padding: 0;
  max-width: 490px;
  font-size: 18px;
  line-height: 28px;
}

.author-link{
  display: inline-block;
  margin-top: 15px;
  font-weight: bold;
  font-size: 18px;
  line-height: 28px;
  display: flex;
  align-items: flex-end;
  text-decoration: none;
  color: #fff;
}

.reolad-quote-btn{
  width: 17px;
  height: 17px;
  margin-left: 10px;
  margin-top: 5px;
  border: none;
  outline: none;
  background-color: inherit;
  background: url("../assets/reload.svg") no-repeat;
  cursor: pointer;
}

.time-article{
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.greeting-time{
  margin: 0;
  padding: 0;
  font-size: 20px;
  line-height: 28px;
  display: flex;
  align-items: flex-end;
  letter-spacing: 4px;
  text-transform: uppercase;
}

.time{
  font-weight: bold;
  font-size: 180px;
  line-height: 180px;
  letter-spacing: -5px;
}

.time span{
  font-weight: 300;
  font-size: 40px;
  line-height: 28px;
  text-transform: uppercase;
}

.place-time{
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  letter-spacing: 4.8px;
  text-transform: uppercase;
}

.btn-box{
  display: flex;
  align-items: center;
  padding: 15px 0;
  background: #FFFFFF;
  border-radius: 28px;
}

.btn-text{
  margin: 0;
  margin-left: 20px;
  padding: 0;
  font-weight: bold;
  font-size: 16px;
  line-height: 28px;
  letter-spacing: 5px;
  text-transform: uppercase;
  color: #000000;
}

.more-btn{
  width: 40px;
  height: 40px;
  margin-right: 8px;
  border-radius: 50%;
  border: none;
  background: url("../assets/arrow.svg") no-repeat center center;
  background-color: #000000;
}

</style>

<template>
  <article class="container">
    <div class="icon">
        <img src="/icon-star.svg" alt="Icon">
    </div>
    <h1>How did we do?</h1>
    <p>
      Please let us know how we did with your support request.
      All feedback is appreciated to help us improve our offering!
     </p>
    <div class="raiting-container">
      <div class="circle">
        1
      </div>
      <div class="circle">
        2
      </div>
      <div class="circle">
        3
      </div>
      <div class="circle">
        4
      </div>
      <div class="circle">
        5
      </div>
    </div>
    <button class="button">
      Submit
    </button>
  </article>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};

</script>

<style scoped>
h1 {
  color: white;
  text-align: left;
}
p {
  color: #969FAD;
}
.button {
  color: #fff;
  background-color: #FC7614;
  width: 100%;
  padding: 11px;
  border-radius: 22.5px;
  border: none;
  font-size: 15px;
  letter-spacing: 2px;
  font-weight: 700;
} 
.circle {
  color: #7C8798;
  background-color: #262E38;
  border-radius: 50%;
  width: 51px;
  height: 51px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.raiting-container{
  display: flex;
  justify-content: center;
  width: 100%;
  gap: 21px;
  margin-bottom: 32px;
  margin-top: 24px;
}
.container {
  display: flex;
  flex-direction: column;
  max-width: 412px;
  max-height: 416px;
  align-items: flex-start;
  background: radial-gradient(98.96% 98.96% at 50% 0%, #232A34 0%, #181E27 100%);
  padding: 32px;
  border-radius: 30px;
}
.icon {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background-color: #262E38;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>

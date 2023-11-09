<template>
  <article class="container">
    <div>star icon here</div>
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
}
p {
  color: #969FAD;
}
.button {
  color: #fff;
  background-color: #FC7614;
}
.circle {
  color: #7C8798;
  background-color: #262E38;
  border-radius: 50%;
  width: 51px;
  height: 51px;
}
.raiting-container{
  display: flex;
  justify-content: center;
}
.container {
  display: flex;
  flex-direction: column;
  max-width: 412px;
  align-items: center;
  background-color: black;
}
</style>

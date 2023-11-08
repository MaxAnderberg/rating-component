<template>
  <article>
    <div>star icon here</div>
    <h1>How did we do?</h1>
    <p>
      Please let us know how we did with your support request.
      All feedback is appreciated to help us improve our offering!
     </p>
    <div>
      <div>
        1
      </div>
      <div>
        2
      </div>
      <div>
        3
      </div>
      <div>
        4
      </div>
      <div>
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

console.log('hello world');
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
</style>

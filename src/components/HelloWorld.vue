<template>
  <div>
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
  </div>
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
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.button {
  color: #fff;
  background-color: #FC7614;
}
</style>

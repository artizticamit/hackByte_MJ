<template>
  <div class="home">
    <h1 class="headng">Natural Language Understanding</h1>
    <form>
      <textarea
        class="input"
        name=""
        id=""
        cols="30"
        rows="10"
        v-model="inputText"
      ></textarea>
    </form>
    <button class="btnStyle1">Check</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  data() {
    return {
      inputText: "",
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Special+Elite&display=swap");

.home {
  font-family: "Special Elite", cursive;
  color: black;
}

.input {
  font-family: "Special Elite";
  border: none;
  background-color: whitesmoke;
  width: 70%;
  height: 300px;
  font-size: 20px;
  outline: none;
  padding: 15px 10px;
}

.btnStyle1 {
  font-size: 30px;
  margin: 20px 0px;
  border: none;
  background: wheat;
  border-radius: 10px;
  padding: 10px 15px;
}
</style>

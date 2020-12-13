<template>
  <div>
      <ShortCut />
    <Header/>
    <Nav />
    <Main />
  </div>
</template>

<script>
import Header from "../../components/Header";
import ShortCut from "../../components/ShortCut";
import Spacer from "../../components/Spacer";
import Nav from "../../components/Nav";
import Main from "../../components/Main";

export default {
  name: "Index",
  components:{Header,ShortCut,Spacer,Nav,Main}
}
</script>

<style>

</style>

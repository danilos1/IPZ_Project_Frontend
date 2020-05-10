<template>
    <div>
        <hero></hero>
        <TopicList></TopicList>
    </div>
</template>
<script>
import Hero from "./components/Hero";
import TopicList from "./components/TopicList";


export default {
  name: "components",
  components: {
      Hero,
      TopicList
  }
};
</script>

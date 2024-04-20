<template>
  <div>
    <h1>Game Design Documents</h1>

    <div style="margin-bottom: 30px;">
      The following are some game proposals or game design documents I've made or heavily contributed to, check it out if you're interested!
    </div>
    <ProjectsList v-bind:projects="projects" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import otherProjectsData from "@/data/OtherProjectsData.ts";

export default Vue.extend({
  name: "OtherProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: otherProjectsData,
    };
  },
});
</script>

<template>
  <div>
    <TopNav />
    <div class="container mx-8 md:px-8 mt-10">
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12">
        Project Pheonix - AEG (as Kunai)
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        This was an enormous project! I came in a senior engineer to help re-architect and rebuild (from scratch) an internal tool to AEG. It had various integrations with banks, internal apps, and had to allow for concurrent usage with the legacy system. At the end, I was able to help deliver the application on schedule and with a joyful experience that our stakeholders loved.
        <br><br>
        The stack and tooling was: Ember on the front-end, Rails JSON:API on the backend, webhooks for various integrations, custom MSSQL sync with their data warehouse, and Redis for background jobs.
      </p>
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12 mt-10">
        MyMedLab
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        This was a project of love. For 8 years I maintained, ran, and developed the MyMedlab platform. This included but was not limited to: rebuilding lab integrations, on-call fire snuffing, enhancing payment security, and updating infrastructure to improve patient data security.
        <br><br>
        The stack and tooling was: Rails (fullstack), webhooks for various integrations, and CRON for syncing lab data.
      </p>
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12 mt-10">
        Hub - BigSouthern
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        This is a truly interesting project. It was more of a team-addition rather than a staff augmentation. My general duties were the usual building of features and bug fixing. But what made it interesting was the mentorship of new Rails devs to help level-up the internal team.
        <br><br>
        The stack and tooling was: Rails (fullstack), docker, StimulusJS, and Redis for background jobs.
      </p>
    </div>
  </div>
</template>

<script>
import TopNav from '~/components/TopNav'

export default {
  components: {
    TopNav
  }
}
</script>

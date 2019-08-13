<template>
  <div>
    <TopNav />
    <div class="container mx-8 md:px-8 mt-10">
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12">
        Lead Rails Engineer - OneCallCareMedical
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        As a lead engineer at OCCM I was responsible for leading the team from a technology point of view. This included leading the larger projects, helping architect infrastructure, and gracefully introducing new tech. On the other side of the coin I was additionally responsible for mentorship, helping product to shape incoming work, and run 1 on 1s. This was some of my most impactful work.
      </p>
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12 mt-10">
        Senior Software Engineer - MyPowerSupply
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        This scrappy team was delightful to work with. We explored front-end testing together, fixed bugs, and introduced new features that brought joy to our customers. I led some of the more technical projects at that time such as rewriting the subscriptions logic, upgrading Rails, and raising the quality of our Javascript.
      </p>
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-3xl md:font-light text-gray-700 border-b w-11/12 mt-10">
        Senior Developer - Elevator Up
      </h2>
      <p class="text-xl text-gray-700 w-11/12 mt-4">
        This employment was a truly unique experience. As the sole software engineer on the team not only did I implement, but I also established architecture and shaped technical requirements with new clients. Some of those projects included:
      </p>
      <ul class="list-disc list-inside text-xl text-gray-700  mt-2 ml-2">
        <li>helping Baker Books develop a modern site that synced with their data</li>
        <li>maintaining a goverment-driven app serving over 30 countries</li>
        <li>converting an legacy CMS system to a headless one</li>
      </ul>

      <p class="my-16 text-lg text-gray-700">
        Want to see the rest? Jump over to <a href="https://www.linkedin.com/in/caseyprovost" target="_new" class="border-b border-gray-900 pb-px md:pb-1 text-gray-900">LinkedIn</a> and browse my full employment history.
      </p>
    </div>
  </div>
</template>

<script>
import TopNav from '../components/TopNav'

export default {
  components: {
    TopNav
  }
}
</script>

<style>
body {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
}
</style>

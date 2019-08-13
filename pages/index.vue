<template>
  <div>
    <TopNav />
    <div class="container mx-8 md:px-8 mt-10">
      <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-5xl md:font-light text-gray-700">
        Howdy!
      </h2>
      <p class="text-xl sm:text-2xl md:text-3xl lg:text-4xl md:font-light text-gray-700 w-11/12 mt-6">
        My name is Casey Provost, and I craft delightful web applications and APIs with <a href="#" class="border-b border-gray-900 pb-px md:pb-1 text-gray-900">Ruby on Rails</a>.
      </p>
      <p class="text-xl sm:text-2xl md:text-3xl lg:text-4xl md:font-light text-gray-700 w-11/12 mt-8">
        When I am not building stuff I am writing about it on my engineering <a href="https://caseyprovost.com" class="border-b border-gray-900 pb-px md:pb-1 text-gray-900">blog</a>. I write about APIs, design patterns, and how to build great stuff together.
      </p>
      <p class="text-xl sm:text-2xl md:text-3xl lg:text-4xl md:font-light text-gray-700 w-11/12 mt-8">
        I am currently accepting new clients. Please <a class="border-b border-gray-900 pb-px md:pb-1 text-gray-900" href="mailto:caseyr.provost@gmail.com">reach out</a> if you would like to explore working together.
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

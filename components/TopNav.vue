<template>
  <div class="top-nav">
    <div class="logo-container">
      <span class="text-gray-900 text-2xl w-full text-center">Casey Provost</span>
    </div>
    <div class="flex w-3/5">
      <MenuItem text="About Me" route="/" />
      <MenuItem text="Experience" route="/experience" />
      <MenuItem text="Projects" route="/projects" />
      <a activeClass="active" href="https://caseyprovost.com" target="_new" class="py-5 px-10 hover:text-blue-600 text-gray-700">
        Blog
      </a>
    </div>
    <div class="w-1/5 text-right">
      <div class="text-gray-500 text-2xl float-right pr-8 py-4">
        <a href="https://www.linkedin.com/in/caseyprovost/" target="_new" class="mx-1 hover:text-blue-700">
          <font-awesome-icon :icon="['fab', 'linkedin']"/>
        </a>
        <a href="https://github.com/caseyprovost" target="_new" class="mx-1 hover:text-blue-700">
          <font-awesome-icon :icon="['fab', 'github']"/>
        </a>
        <a href="https://twitter.com/caseyprovost" target="_new" class="mx-1 hover:text-blue-700">
          <font-awesome-icon :icon="['fab', 'twitter']"/>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import MenuItem from '~/components/MenuItem'

export default {
  components: {
    MenuItem
  }
}
</script>

<style>
.top-nav {
  @apply flex w-full border-b border text-gray-700;
}

.logo-container {
  @apply flex p-4 border-r w-1/5;
}
</style>

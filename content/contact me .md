<template>
  <div>
    <img :src="cover" alt="Cover Image" />
    <div>
      <a :href="socials.twitter" target="_blank">Twitter</a>
      <a :href="socials.github" target="_blank">GitHub</a>
      <a :href="socials.linktr.ee" target="_blank">Linktr.ee</a>
    </div>
  </div>
</template>

<script setup>
import { useAppConfig } from '#app'

const { cover, socials } = useAppConfig()
</script> 
x<template>
  <main>
    <ul>
    <ContentList path="/" v-slot="{ list }">
      <li v-for="article in list" :key="article._path">
        <NuxtLink :to="article._path">{{ article.title }}</NuxtLink>
      </li>
    </ContentList>
  </ul>
  </main>
</template>
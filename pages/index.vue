<template>
  <div>Hello Vue</div>
</template>

<script setup>
useSeoMeta({
  title: "Portfolio",
  description: "This is my portfolio",
  ogTitle: "Portfolio",
  ogDescription: "This is my portfolio",
  ogImage: "https://avatars.githubusercontent.com/u/88965473?v=4",
  ogUrl: "https://mohamed-omar.com",
  twitterTitle: "Portfolio",
  twitterDescription: "This is my portfolio",
  twitterImage: "https://avatars.githubusercontent.com/u/88965473?v=4",
  twitterCard: "summary",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
  link: [
    {
      rel: "icon",
      type: "image/png",
      href: "/favicon.png",
    },
  ],
});
</script>

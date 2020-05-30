<template>
  <div>
    <article class="m-block">
      <h2 class="caption__h2">Галерея</h2>
      <gallery :images="images" />
    </article>
  </div>
</template>


<script>
import Gallery from "vue-cover-gallery"

export default {
  components: {
    Gallery
  },
  data() {
    return {
      images: [
        {
          title: "title 1",
          description: "des 1",
          href: "/images/sdhfgs78.jpg"
        },
        {
          title: "title 2",
          description: "des 2",
          href: "/images/sdhfgs78.jpg"
        },
        {
          title: "title 1",
          description: "des 1",
          href: "/images/sdhfgs78.jpg"
        },
        {
          title: "title 2",
          description: "des 2",
          href: "/images/sdhfgs78.jpg"
        },
        {
          title: "title 1",
          description: "des 1",
          href: "/images/sdhfgs78.jpg"
        },
        {
          title: "title 2",
          description: "des 2",
          href: "/images/sdhfgs78.jpg"
        }
      ]
    };
  },
};
</script>



<template>
  <div class="article-body">
    <slot />
  </div>
</template>

<style scoped lang="scss">
  .article-body {
    margin: 20px 0;
    h3 {
      font-size: 1.4rem;
      margin: 10px;
      font-family: 'Varela Round';
    }

    p {
      line-height: 1.5;

      + p {
        margin-top: 20px;
      }

      a {
        color: $color-blue;
      }
    }

    ul {
      margin-left: 20px;

      li {
        &:nth-of-type(n+2) {
          margin-top: 0.5em;
        }
      }
    }

    img {
      max-width: 100%;
    }
  }
</style>

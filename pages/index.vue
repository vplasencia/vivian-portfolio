<template>
  <div class="px-2">
    <div class="flex place-content-center mt-20">
      <img src="/logo.jpg" class="rounded-full" alt="Logo" width="160" />
    </div>
    <div class="flex place-content-center mt-10">
      <p class="w-96 text-center">
        Hi! I am <span class="font-semibold">Vivian Plasencia</span>. I am a
        Computer Scientist curious about Web3. I like building stuff.
      </p>
    </div>
    <div>
      <div class="flex place-content-center mt-10">
        <span class="font-semibold text-lg">My Social Media</span>
      </div>
      <div class="flex flex-wrap place-content-center mt-5 gap-5">
        <a
          href="https://twitter.com/ViviPlasenciaC"
          target="_blank"
          class="socialMediaLink"
          rel="noreferrer noopener nofollow"
          title="Vivian Plasencia Twitter"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-twitter"
          >
            <path
              d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
            ></path></svg
        ></a>
        <a
          href="https://www.linkedin.com/in/vivian-plasencia-221603170"
          target="_blank"
          class="socialMediaLink"
          rel="noreferrer noopener nofollow"
          title="Vivian Plasencia LinkedIn"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-linkedin"
          >
            <path
              d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"
            ></path>
            <rect x="2" y="9" width="4" height="12"></rect>
            <circle cx="4" cy="4" r="2"></circle></svg
        ></a>
        <a
          href="https://github.com/vplasencia"
          target="_blank"
          class="socialMediaLink"
          rel="noreferrer noopener nofollow"
          title="Vivian Plasencia Github"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-github"
          >
            <path
              d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
            ></path></svg
        ></a>
        <a
          href="https://www.instagram.com/vivian_plasencia"
          target="_blank"
          class="socialMediaLink"
          rel="noreferrer noopener nofollow"
          title="Vivian Plasencia Instagram"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-instagram"
          >
            <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg
        ></a>
        <a
          href="https://vivianblog.hashnode.dev/"
          target="_blank"
          class="socialMediaLink"
          rel="noreferrer noopener nofollow"
          title="Vivian Plasencia Blog"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-edit"
          >
            <path
              d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"
            ></path>
            <path
              d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"
            ></path></svg
        ></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.socialMediaLink {
  @apply p-3 rounded-lg bg-purple-100 text-purple-600 hover:bg-purple-200 transition-colors ease-in-out;
}
</style>
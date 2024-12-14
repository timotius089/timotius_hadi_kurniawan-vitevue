<template>
  <main
    style="width: 100%; animation: fade-upslide 1500ms"
    class="transition duration-300 delay-150"
  >
    <div class="flex-1" style="margin: auto; width: 70%; padding: 10px">
      <div class="flex justify-between items-center">
        <div>
          <h2 class="text-6xl font-bold mt-4">About Me</h2>
          <p class="text-gray-600 mt-4 max-w-lg">
            A junior fullstack developer who currently focused on Web
            Development. Other than that, I also interested in UX/UI Design,
            Mobile and AI Development. I love to learn new things and always
            open to new opportunities.
          </p>
          <div class="mt-8 space-x-4">
            <button
              class="border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
            >
              Learn More
            </button>
          </div>
        </div>
        <div class="hidden md:block">
          <img
            alt="Profile picture of Alvalen Shafel"
            class="rounded-full"
            height="200"
            src="@/assets/Tim.jpeg"
            width="200"
          />
        </div>
      </div>
    </div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

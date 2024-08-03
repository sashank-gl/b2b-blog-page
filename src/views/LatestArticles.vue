<template>
  <div class="px-4 xl:px-12 py-12 min-h-screen">
    <div>
      <h4 class="text-4xl xl:text-7xl mb-1">Latest Articles</h4>
      <p class="text-base xl:text-xl">
        Discover our newest insights into the world of nature and greenery.
      </p>
    </div>

    <div class="grid grid-cols-1 xl:grid-cols-2 gap-6 mt-6">
      <!-- Latest Article -->
      <div>
        <img
          src="https://images.unsplash.com/photo-1542665219-70061e49d6c2?q=80&w=1740"
          class="object-cover rounded-xl"
        />
        <div class="mt-2">
          <h5 class="text-2xl xl:text-4xl">
            The Healing Power of Forest Bathing
          </h5>
          <p class="mt-2 mb-4">
            Discover how forest bathing reduces stress and boosts well-being by
            immersing yourself in nature.
          </p>
          <div class="flex items-center justify-between">
            <p class="italic">Published on 25 Jul, 2024</p>
            <p class="border rounded-full px-2">Nature Therapy</p>
          </div>
        </div>
      </div>

      <!-- Older Articles -->
      <div class="flex flex-col gap-6">
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1560274765-374eb66b6563?q=80&w=1738"
            class="object-cover rounded-xl xl:h-36 xl:w-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">Urban Gardening: Transforming City Spaces</h5>
            <p class="mt-2 mb-4">
              Learn how to create green oases in urban environments, turning
              concrete jungles into vibrant spaces that improve well-being.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 20 Jul, 2024</p>
              <p class="border rounded-full px-2">Sustainable Living</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1592150621744-aca64f48394a?q=80&w=1782"
            class="object-cover rounded-xl xl:h-36 xl:w-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">Top 10 Indoor Plants for Cleaner Air</h5>
            <p class="mt-2 mb-4">
              Enhance your home's air quality with these easy-to-care-for
              plants, which add natural beauty to your living spaces.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 18 Jul, 2024</p>
              <p class="border rounded-full px-2">Home Improvement</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1527690499469-ef2eff9c6735?q=80&w=1738"
            class="object-cover rounded-xl xl:h-36 xl:w-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">The Benefits of Green Roofs</h5>
            <p class="mt-2 mb-4">
              Discover how green roofs can reduce urban heat islands, improve
              energy efficiency, and provide habitat for wildlife.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 10 Jul, 2024</p>
              <p class="border rounded-full px-2">Eco-Architecture</p>
            </div>
          </div>
        </div>
        <button class="rounded-full border font-semibold py-2 px-6 self-center">
          View All Articles
        </button>
      </div>
    </div>
  </div>
</template>

<template>
  <div class="text-center ">
  <h1 class="text-3xl font-bold mt-6 mb-4 sm:mt-12 sm:mb-6">5 principles of Supervisely</h1>
  <p class="text-lg leading-7  sm:mx-auto">There are hundreds of features within the platform, but everything we do is defined by these five concepts.</p>
</div>
  <div class="flex flex-wrap justify-center items-center py-8 px-11">
    <div v-for="card in cards" :key="card.id" class="w-full sm:w-1/2 md:w-1/3 lg:w-1/5 px-4">
      <div class="bg-white shadow-lg rounded-lg overflow-hidden hover:border-blue-500 transition-colors duration-300 hover:cursor-pointer">
        <div class="p-4 text-center">
          <span class="bg-gray-700 text-white px-2.5 rounded-full font-bold">{{ card.id }}</span>
          <h2 class="font-bold text-xl mb-2">{{ card.title }}</h2>
          <div class="flex justify-center items-center">
            <a href="" class="btn btn-link font-bold text-blue-400 hover:no-underline">Learn More -&gt;</a>
          </div>
          <p class="text-gray-700 text-base">{{ card.description }}</p>
        </div>
        <div>
          <ul class="ml-5 space-y-1">
            <li v-for="feature in card.features" :key="feature" class="flex items-center">
              <div class="w-4 h-4 rounded-full bg-gray-200"></div>
              <span class="px-2 py-1">{{ feature }}</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          id: 1,
          title: 'Powerful labeling suites',
          description: 'Best-in-class tools, augmented with AI-assistance and custom UIs',
          features: ['Images', 'Text', 'Audio', 'Video', 'Annotations']
        },
        {
          id: 2,
          title: 'Data and users collaboration',
          description: 'Reduce manual effort with automation and pre-built pipelines',
          features: ['Collaboration', 'Version control', 'Quality control', 'Customizability', 'Security']
        },
        {
          id: 3,
          title: 'Intelligent data management',
          description: 'Advanced data organization and storage, with easy access and retrieval',
          features: ['Metadata', 'Searchability', 'Curation', 'Exportability', 'Integration']
        },
        {
          id: 4,
          title: 'Intelligent data management',
          description: 'Advanced data organization and storage, with easy access and retrieval',
          features: ['Metadata', 'Searchability', 'Curation', 'Exportability', 'Integration']
        },
        {
          id: 5,
          title: 'Intelligent data management',
          description: 'Advanced data organization and storage, with easy access and retrieval',
          features: ['Metadata', 'Searchability', 'Curation', 'Exportability', 'Integration']
        },
      ]
    }
  }
}
</script>

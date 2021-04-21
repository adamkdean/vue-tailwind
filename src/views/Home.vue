<template>
  <div class="lg:flex lg:items-center lg:justify-between">
    <div class="flex-1 min-w-0">
      <h2 class="text-2xl font-bold leading-7 text-gray-900 sm:text-3xl sm:truncate">
        vue-tailwind
      </h2>
      <div class="mt-1 flex flex-col sm:flex-row sm:flex-wrap sm:mt-0 sm:space-x-6">
        <div class="mt-2 flex items-center text-sm text-gray-500">
          <BriefcaseIcon class="flex-shrink-0 mr-1.5 h-5 w-5 text-gray-400" aria-hidden="true" />
          TailwindCSS working
        </div>
        <div class="mt-2 flex items-center text-sm text-gray-500">
          <LocationMarkerIcon class="flex-shrink-0 mr-1.5 h-5 w-5 text-gray-400" aria-hidden="true" />
          Heroicons working
        </div>
        <div class="mt-2 flex items-center text-sm text-gray-500">
          <CurrencyDollarIcon class="flex-shrink-0 mr-1.5 h-5 w-5 text-gray-400" aria-hidden="true" />
          Vue 3.X working
        </div>
        <div class="mt-2 flex items-center text-sm text-gray-500">
          <CalendarIcon class="flex-shrink-0 mr-1.5 h-5 w-5 text-gray-400" aria-hidden="true" />
          Tested: Wed 21 Apr 2021
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  BriefcaseIcon,
  CalendarIcon,
  CurrencyDollarIcon,
  LocationMarkerIcon,
} from '@heroicons/vue/solid'

export default {
  name: 'Home',
  components: {
    BriefcaseIcon,
    CalendarIcon,
    CurrencyDollarIcon,
    LocationMarkerIcon,
  },
}
</script>

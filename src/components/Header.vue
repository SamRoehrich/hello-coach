<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <nav class="bg-gray-50">
      <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
        <div class="relative flex items-center justify-between h-16">
          <div
            class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start"
          >
            <div class="flex-shrink-0 flex items-center">
              <div>
                <p href="#" class="px-3 py-2 rounded-md text-md font-medium">
                  Search...
                </p>
              </div>
              <img src="../assets/notification-svgrepo-com.svg" class="py-2" />
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

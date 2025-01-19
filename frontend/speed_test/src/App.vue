<script setup>
</script>


<template>
  <div id="app">
    <div class="flex-col text-start py-5">
      <h1 class="pb-5">Frankfurt Download Speed Test</h1>
      <p>
        Created for testing 1Gbps download from server located in Frankfurt by Amazon service. The bandwidth of the Frankfurt server is 1Gbps with no shared traffic.
      </p>
      <p class="py-3"><span class="font-bold">Please Note:</span> amazon server have to be at least t3.large instance and higher!</p>
    </div>
      <!-- <button @click="downloadFile">Download 10GB Test File</button> -->
  </div>
  <a href="#" aria-describedby="tier-hobby" class="mt-8 rounded-md px-3.5 py-2.5 text-center text-sm font-semibold bg-indigo-600 text-white ring-1 ring-inset ring-indigo-200 hover:ring-indigo-300 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600 ">Get started today</a>
</template>

<script>
export default {
  methods: {
    downloadFile() {
      window.location.href = '/10GB-test-file.zip'; // Replace with actual file path.
    }
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}
</style>
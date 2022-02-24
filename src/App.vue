<script>
 
</script>

<template>
  <div class="w-1280px h-screen mx-auto p-30  text-center overflow-hidden text-[	#5A5AAD]">
    <h1 class="mb-10 text-2xl font-medium text-[#FFAF60] ">File Upload & Image Preview</h1>
    <div class="relative w-1/2 inline-block h-auto  p-4 rounded-md border-4 border-[#FFAF60] ">
      <label class=" block  rounded-md bg-true-gray-50 border-gray-200 border-2 border-dashed text-gray-400 " for="upload -z-1">
        <input class="hidden" type="file" name="" id="upload">
        <span class="inline-block leading-200px ">請將圖片拖曳於此</span>
      </label>
      <i-mdi-cloud-upload-outline class="absolute  bottom-4 left-0 right-0 mx-auto text-4xl align-middle animate-bounce text-[#FFAF60] z-3"/>
      <div class="absolute left-0 opacity-10 top-0 z-2 w-full h-full bg-[#FFAF60]"></div>
    </div>
    
  </div>
</template>

<style>

</style>

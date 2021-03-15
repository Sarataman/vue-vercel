<template>
  <div class="antialiased bg-gray-100 text-black">
    <div class="bg-white">
      <header class="space-y-2">
        <nav class="max-w-5xl mx-auto px-6 flex items-center justify-between">
          <div>
            <!-- Vercel logo -->
            <span>
              <img src="../assets/vercel.png" alt="vercel logo"  class="mt-2 h-6 w-6">
              <!-- <img src="../assets/vercel2.png" alt=""  class="h-6 w-6"> -->
            </span>
            <span>
              <svg viewBox="0 0 32 32" stroke="currentColor" class="h-8 w-8 text-gray-300">
                <line x1="10" y1="28" x2="22" y2="4"></line>
              </svg>
            </span>
            <span class="inline-flex items-center space-x-2 text-sm leading-5 font-medium">
              <a href="" class="inline-flex items-center space-x-2">
                <span>
                  <img src="../assets/profile.jpg" alt="profile picture" class="h-7 w-7 rounded-full border border-gray-200" />
                </span>
                <span>Sarah Ataman</span>
              </a>
              <button type="button" class="inline-flex items-center border rounded p-0.5 hover:border-gray-200 hover:bg-gray-50 transition ease-in-out duration 150">
                <!-- icon h-5 w-5 text-gray-400 -->
              </button>
            </span>
          </div>
          <div class="flex items-center space-x-5">
            <div class="flex items-center space-x-5">
              <button type="button" class="border border-gray-200 rounded px-3 py-1.5 text-sm leading-5 text-gray-500 text-sm leading-5 hover:border-black transition ease-in-out duration-150">
                Feedback
              </button>
              <a href="">
                <a href="" class="inline-block text-sm leading-5 text-gray-500 hover:text-black transition ease-in-out duration-150">Blog</a>
              </a>
              <a href="" class="inline-block text-sm leading-5 text-gray-500 hover:text-black transition ease-in-out duration-150">Support</a>
              <a href="" class="inline-block text-sm leading-5 text-gray-500 hover:text-black transition ease-in-out duration-150">Docs</a>
            </div>
            <button type="button" class="h-5 w-5 text-gray-400">...</button>
            <span>
              <button></button>
            </span>
          </div>
        </nav>
        <nav class="flex text-sm leading-5">
          <div class="max-w-5xl mx-auto">
            <a href="" class="border-b-2 border-black px-0.5 py-3 text-black">Overview</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Projects</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Integrations</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Activity</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Domains</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Usage</a>
            <a href="" class="border-b-2 border-transparent px-1.5 py-3 text-gray-500 hover:text-black transition ease-in-out duration 150">Settings</a>
          </div>
        </nav>
      </header>
      <div class="max-w-5xl mx-auto px-6 pt-14 pb-28">
        <div class="flex space-x-8">
          <div>
            <img class="h-24 w-24 rounded-full" src="../assets/profile.jpg" alt="profile picture">
          </div>
          <div class="flex flex-col justify-between space-y-4">
            <div class="flex items-center space-x-3">
              <h1 class="text-4xl leading-10 font-bold">Sarah Ataman</h1>
              <span class="mt-1 inline-flex text-xs leading-5 font-medium rounded-full bg-gray-50 border border-gray-200 px-2 text-black uppercase tracking-wide">
                Hobby
              </span>
            </div>
            <div>
              <dl>
                <dt class="text-xs leading-5 font-medium text-gray-500 uppercase tracking-wide">Git Integration</dt>
                <dd class="text-sm leading-5 font-medium">
                  <span>
                    <img src="" alt="" class="h-7 w-7">
                  </span>
                  <!-- github logo -->
                  sarataman
                </dd>
              </dl>
            </div>
          </div>
        </div>
        <div class="grid grid-cols-2 col-gap-6">
          <a href="" class="inline-flex justify-center rounded border border-gray-200 bg-white px-6 py-2 text-sm leading-5 font-medium text-gray-500 hover:border-black hover:text-black transition ease-in-out duration-150">Invite Team</a>
          <a href="" class="inline-flex justify-center rounded border border-gray-200 bg-black px-6 py-2 text-sm leading-5 font-medium text-white hover:border-black hover:text-black hover:bg-white transition ease-in-out duration-150">Import Projects</a>
        </div> 
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
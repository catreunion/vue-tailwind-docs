<template>
  <main class="w-96">
    <div class="grid grid-cols-1 gap-6 py-6">
      <!-- Justify Items -->
      <div>
        <h1>Justify Items</h1>
        <h2>control how grid items are aligned along their inline x axis</h2>
        <h3 class="font-mono">justify-items-{x}</h3>
        <h4 class="font-mono">start|center|end|stretch</h4>

        <div class="grid grid-cols-1 gap-3 py-3">
          <div>
            <h5 class="font-mono">justify-items-start</h5>
            <p>align grid items at the start of their inline x axis</p>
            <div class="grid grid-cols-3 justify-items-start border-2 border-pink-500 p-2">
              <div class="border-2 border-indigo-500 p-2">File</div>
              <div class="border-2 border-indigo-500 p-2">Edit</div>
              <div class="border-2 border-indigo-500 p-2">View</div>
              <div class="border-2 border-indigo-500 p-2">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">justify-items-center</h5>
            <p>align grid items at the center of their inline x axis</p>
            <div class="grid grid-cols-3 justify-items-center border-2 border-pink-500 p-2">
              <div class="border-2 border-indigo-500 p-2">File</div>
              <div class="border-2 border-indigo-500 p-2">Edit</div>
              <div class="border-2 border-indigo-500 p-2">View</div>
              <div class="border-2 border-indigo-500 p-2">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">justify-items-end</h5>
            <p>align grid items at the end of their inline x axis</p>
            <div class="grid grid-cols-3 justify-items-end border-2 border-pink-500 p-2">
              <div class="border-2 border-indigo-500 p-2">File</div>
              <div class="border-2 border-indigo-500 p-2">Edit</div>
              <div class="border-2 border-indigo-500 p-2">View</div>
              <div class="border-2 border-indigo-500 p-2">Help</div>
            </div>
          </div>

          <div class="border-2 border-green-500 p-2">
            <h5 class="font-mono">justify-items-stretch</h5>
            <p>stretch grid items along their inline x axis</p>
            <div class="grid grid-cols-3 justify-items-stretch border-2 border-pink-500 p-2">
              <div class="border-2 border-indigo-500 p-2">File</div>
              <div class="border-2 border-indigo-500 p-2">Edit</div>
              <div class="border-2 border-indigo-500 p-2">View</div>
              <div class="border-2 border-indigo-500 p-2">Help</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Align Items -->
      <div>
        <h1>Align Items</h1>
        <h2>control how items are aligned along the container's y axis</h2>
        <h3 class="font-mono">items-{y}</h3>
        <h4 class="font-mono">start|center|end|baseline|stretch</h4>

        <div class="grid grid-cols-1 gap-3 py-3">
          <div class="border-2 border-green-500 p-2">
            <h5 class="font-mono">items-start</h5>
            <p>align items at the start of the container’s y axis</p>
            <div class="flex items-start border-2 border-pink-500">
              <div class="border-2 border-indigo-500 px-2 py-4">File</div>
              <div class="border-2 border-indigo-500 px-2 py-12">Edit</div>
              <div class="border-2 border-indigo-500 px-2 py-8">View</div>
              <div class="border-2 border-indigo-500 px-2 py-10">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">items-center</h5>
            <p>align items at the center of the container’s y axis</p>
            <div class="flex items-center border-2 border-pink-500">
              <div class="border-2 border-indigo-500 px-2 py-4">File</div>
              <div class="border-2 border-indigo-500 px-2 py-12">Edit</div>
              <div class="border-2 border-indigo-500 px-2 py-8">View</div>
              <div class="border-2 border-indigo-500 px-2 py-10">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">items-end</h5>
            <p>align items at the end of the container’s y axis</p>
            <div class="flex items-end border-2 border-pink-500">
              <div class="border-2 border-indigo-500 px-2 py-4">File</div>
              <div class="border-2 border-indigo-500 px-2 py-12">Edit</div>
              <div class="border-2 border-indigo-500 px-2 py-8">View</div>
              <div class="border-2 border-indigo-500 px-2 py-10">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">items-baseline</h5>
            <p>align items along their baselines</p>
            <div class="flex items-baseline border-2 border-pink-500">
              <div class="border-2 border-indigo-500 px-2 py-4">File</div>
              <div class="border-2 border-indigo-500 px-2 py-12">Edit</div>
              <div class="border-2 border-indigo-500 px-2 py-8">View</div>
              <div class="border-2 border-indigo-500 px-2 py-10">Help</div>
            </div>
          </div>

          <div>
            <h5 class="font-mono">items-stretch</h5>
            <p>stretch items to fill the container’s y axis</p>
            <div class="flex items-stretch border-2 border-pink-500">
              <div class="border-2 border-indigo-500 px-2 py-4">File</div>
              <div class="border-2 border-indigo-500 px-2 py-12">Edit</div>
              <div class="border-2 border-indigo-500 px-2 py-8">View</div>
              <div class="border-2 border-indigo-500 px-2 py-10">Help</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

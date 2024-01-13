<template>
          <div class="flex p-4 bg-black text-white">
        <div class="w-1/2 p-4">
          <h2 class="text-2xl font-bold mb-4">კონტაქტი</h2>
          <div class="mb-4">
            <label for="name" class="block text-white">თბილისი, ლეონარდო და ვინჩის ქუჩა N15</label>
          </div>
          <div class="mb-4">
            <label for="email" class="block">
              მობილური: <span class="text-blue-500">(+995) 551 10 11 12</span>
            </label>
          </div>
          <div class="mb-4">
            <label for="email" class="block">
              მეილი: <span class="text-blue-500">ლეონარდოს_ფუნჯი@gmail.com</span>
            </label>
          </div>
        </div>
        <div class="w-1/2 p-4"> <!-- Updated background and text color for the second half -->
          <h2 class="text-2xl font-bold mb-4"></h2>
          <div class="mb-4">
            <input placeholder="მეილი" type="text" id="subject" name="subject" class="w-full border rounded p-2">
          </div>
          <div class="mb-4">
            <input placeholder="სათაური" type="text" id="subject" name="subject" class="w-full border rounded p-2">
          </div>
          <div class="mb-4">
            <textarea placeholder="შეტყობინება" id="message" name="message" rows="4"
              class="w-full border rounded p-2"></textarea>
          </div>
          <button class="bg-blue-500 text-white py-2 px-4 rounded">გაგზავნა</button>
        </div>
      </div>

</template>
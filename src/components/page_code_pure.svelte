<script>
    import Prism from "./../views/PrismJS.svelte";
  
    let code_sample = `
    <footer class="bg-[#444343] sm:bg-[#6b3804] lg:bg-[#75190f]">
    <div
      class="sm:grid overflow-hidden grid-cols-3 grid-rows-1 gap-0 w-full h-1/3 px-3"
    >
      <div class="box">
        <!-- <img src="" alt="logo" /> OR -->
        <h1 class="text-center font-bold text-4xl p-4">COMPANY NAME</h1>
        <p class="sm:text-left sm:pt-2 sm:pb-6 text-center">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took.
        </p>
      </div>
      <div class="box col-start-2 col-end-4 my-5">
        <div
          class="sm:grid grid-cols-3 grid-rows-1 gap-0 w-full h-1/3 sm:ml-8 lg:ml-32"
        >
          <div class="box">
            <h3 class="text-center font-bold text-2xl my-5 sm:text-left">
              Services
            </h3>
            <ul class="grid my-2">
              <a class="text-center sm:text-left" href="#link">Lorem Ipsum</a>
              <a class="text-center sm:text-left" href="#link">Is simply</a>
              <a class="text-center sm:text-left" href="#link">Dummy text</a>
              <a class="text-center sm:text-left" href="#link">Not only five</a>
            </ul>
          </div>
          <div class="box">
            <h3 class="text-center font-bold text-2xl my-5 sm:text-left">
              Location
            </h3>
            <ul class="grid my-2">
              <a class="text-center sm:text-left" href="#link">Lorem Ipsum</a>
              <a class="text-center sm:text-left" href="#link">Is simply</a>
              <a class="text-center sm:text-left" href="#link">Dummy text</a>
              <a class="text-center sm:text-left" href="#link">Not only five</a>
            </ul>
          </div>
          <div class="box">
            <h3 class="text-center font-bold text-2xl my-5 sm:text-left">
              Contact
            </h3>
            <ul class="grid my-2">
              <a class="text-center sm:text-left" href="#link">Lorem Ipsum</a>
              <a class="text-center sm:text-left" href="#link">Is simply</a>
              <a class="text-center sm:text-left" href="#link">Dummy text</a>
              <a class="text-center sm:text-left" href="#link">Not only five</a>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-[#151515] w-full">
      <p class="text-center sm:text-right mx-5">
        Copyright © 2022 - All right reserved.<a
          href="https://leop.me/"
          class="ml-1 sm:hover:underline">Legal Notice</a
        >
      </p>
    </div>
  </footer>
  `;
  </script>
  
  <svelte:head>
    <title>🌸 Léo_p Ctrl C + V 🌸</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="/style.css">
  </svelte:head>
  
  <html lang="fr">
    <br />
    <h1 class="text-center text-2xl">Svelte Léop Devkit</h1>
  
    <Prism language="markup" code={code_sample} header="" />
  </html>
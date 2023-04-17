<template>
  <div>
    <div class="showcase pb-4">
      <div class="p-4 bg1 flex gap-4 items-center justify-between">
        <div class="max-[1080px] mx-auto">
          <p class="text-[18px] font-semibold">01:21:57:21</p>
          <p>Day:Hour:Minutes:Second</p>
        </div>
        <h1>Grab Discounted Produts $ Save </h1>
      </div>
      <div class="header_container bg-[#2d394b] flex items-center justify-between gap-4 py-2 px-4">
          <nuxt-link to="/"><img class="max-h-[30px]" src="/logo.svg" alt=""></nuxt-link>
          <div class="flex items-center gap-4 justify-between">
            <div class="min-w-[300px] flex items-center gap-4 justify-between bg-[#00a3ff;] py-2 px-6 rounded text-white">
              <div class="flex items-center gap-4 cursor-pointer">
                <svg class="header-button-icon header-button-icon_nav-toggle" width="20" height="20" viewBox="0 0 22 22"><rect width="10.214" height="10.214" rx="1"></rect><rect y="11.786" width="10.214" height="10.214" rx="1"></rect><rect x="11.786" width="10.214" height="10.214" rx="1"></rect><rect x="11.786" y="11.786" width="10.214" height="10.214" rx="1"></rect></svg>
                <p class="hidden">All Products</p>
              </div>
              <span class="header-button-arrow"></span>
            </div>
            <div class="flex items-center lg:min-w-[750px] justify-between gap-4 bg-white rounded py-2 px-8">
              <input type="text" name="text" placeholder="e.g. Wordpress">
              <svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="search-button search-form_submit-icon "><path d="M19.65 17.977l-3.843-3.844a8.734 8.734 0 001.804-5.326 8.748 8.748 0 00-2.58-6.227A8.748 8.748 0 008.804 0a8.749 8.749 0 00-6.226 2.58c-3.434 3.434-3.434 9.02 0 12.454a8.748 8.748 0 006.226 2.579c1.952 0 3.802-.64 5.327-1.804l3.843 3.844a1.18 1.18 0 001.676 0 1.185 1.185 0 000-1.676zm-15.397-4.62a6.444 6.444 0 010-9.101A6.395 6.395 0 018.804 2.37c1.72 0 3.336.67 4.551 1.885a6.394 6.394 0 011.885 4.55c0 1.72-.67 3.336-1.885 4.552a6.394 6.394 0 01-4.55 1.885 6.394 6.394 0 01-4.552-1.886z"></path></svg>
            </div>
            <div class="flex items-center justify-between gap-4 rounded bg-[#f3683e] text-white py-2 px-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" class="header-button-icon inline-svg inlined-svg" data-src="/assets/icons/monsterEye.svg" role="img" aria-labelledby="title"><title>monsterEye</title><path fill-rule="evenodd" clip-rule="evenodd" d="M18 9A9 9 0 1 1 .352 6.5 11.87 11.87 0 0 1 0 3.652c0-.759.095-1.518.238-2.277v-.047C.333.854.428.427.57 0l2.824 1.958A8.962 8.962 0 0 1 9 0c2.12 0 4.067.732 5.605 1.958L17.43 0c.142.427.237.854.332 1.328v.047c.143.76.238 1.518.238 2.277 0 .98-.127 1.938-.352 2.848.23.794.352 1.633.352 2.5zm-9 4.304a4.304 4.304 0 1 0 0-8.608 4.304 4.304 0 0 0 0 8.608z"></path><path d="m9.747 9.747.934 5.23 2.801-1.196v-2.39L9.747 9.746zm6.297-4.66c0 1.729-3.154 3.13-7.044 3.13-3.89 0-7.043-1.401-7.043-3.13 0-1.729 3.153-3.13 7.043-3.13s7.044 1.401 7.044 3.13z"></path></svg>
              <p>Unlimited Download</p>
            </div>
            <div class="bg-white rounded flex items-center gap-4 py-2 px-8">
              <svg xmlns="http://www.w3.org/2000/svg" class="header-button-icon-2 inline-svg inlined-svg" width="20" height="20" data-src="/assets/icons/wallet.svg" role="img" aria-labelledby="title"><title>wallet</title><path d="M16.087 14.571c-2.047 0-3.712-1.73-3.712-3.857 0-2.126 1.665-3.857 3.712-3.857h2.063V5.143c0-.946-.74-1.714-1.65-1.714h-.825V1.714c0-.945-.74-1.714-1.65-1.714H2.475C1.25 0 .24.93.042 2.142c-.018.07-.042.139-.042.215V15.43C0 16.846 1.11 18 2.475 18H16.5c.91 0 1.65-.769 1.65-1.714V14.57h-2.063zm-14.437-12c0-.472.37-.857.825-.857h11.55V3.43H2.475c-.455 0-.825-.385-.825-.858z"></path><path d="M19.181 8.143h-3.093c-1.365 0-2.475 1.154-2.475 2.571 0 1.418 1.11 2.572 2.475 2.572h3.093a.631.631 0 0 0 .62-.643V8.786a.631.631 0 0 0-.62-.643zm-3.093 3.429c-.456 0-.825-.384-.825-.857 0-.474.37-.858.825-.858.455 0 .825.384.825.857 0 .474-.37.858-.825.858z"></path></svg>
              <p>Start Selling</p>
            </div>
            <div class="flex items-center justify-between py-2 px-6 gap-4">
              <svg viewBox="0 0 22 20" width="20" height="20" class="header-button-icon"><path fill-rule="evenodd" clip-rule="evenodd" d="M1.795 10.556a6.195 6.195 0 018.781-8.742l.424.424.424-.424a6.193 6.193 0 018.76 0 6.197 6.197 0 01.02 8.742l-8.405 8.9a1.1 1.1 0 01-1.598 0l-8.406-8.9zM11 17.098l7.607-8.055.023-.022a3.999 3.999 0 000-5.651 3.997 3.997 0 00-5.652 0l-1.2 1.201c-.43.43-1.127.43-1.556 0L9.021 3.37A3.993 3.993 0 002.2 6.195a3.994 3.994 0 001.19 2.848L11 17.098z"></path></svg>
              <svg viewBox="0 0 20 22" width="20" height="20" class="header-button-icon"><path d="M13.694 10.722a5.998 5.998 0 10-7.389 0A10.004 10.004 0 000 20v1A1 1 0 001 22h17.992a1 1 0 001-1v-1a10.004 10.004 0 00-6.298-9.278zM5.997 6.007a3.998 3.998 0 117.997 0 3.998 3.998 0 01-7.997 0zM2 20a7.997 7.997 0 1115.993 0H2z"></path></svg>
              <svg viewBox="0 0 22 22" width="20" height="20" class="header-button-icon header-button-icon_cart"><path d="M19.45 15.24a.86.86 0 00.848-.719l1.69-10.14a.86.86 0 00-.848-1H4.91L4.229.65A.86.86 0 003.395 0H.858a.86.86 0 100 1.719h1.865l.673 2.696L5.07 14.45v2.6a2.553 2.553 0 00-1.69 2.4A2.552 2.552 0 005.93 22c1.744 0 2.981-1.726 2.41-3.38h7.01c-.572 1.655.667 3.38 2.41 3.38a2.552 2.552 0 002.55-2.55 2.552 2.552 0 00-2.55-2.55H6.79v-1.66H19.45zm.676-10.141l-1.404 8.422H6.658L5.254 5.099h14.872zM6.76 19.45a.832.832 0 01-1.661 0 .832.832 0 011.661 0zm11 .831a.832.832 0 010-1.661.832.832 0 010 1.661z"></path></svg>            
            </div>
          </div>
        </div>
        <div class="navbar flex items-center justify-center gap-8 font-semibold p-4">
          <nuxt-link to="#">Website</nuxt-link>
          <nuxt-link to="#">Wordpress</nuxt-link>
          <nuxt-link to="#">Shopify</nuxt-link>
          <nuxt-link to="#">HTML</nuxt-link>
          <nuxt-link to="#">Wocommerce</nuxt-link>
          <nuxt-link to="#">Presta Shop</nuxt-link>
          <nuxt-link to="#">Joomla</nuxt-link>
          <nuxt-link to="#">Services</nuxt-link>
        </div>
        <body>
          <div class="mb-[80px]">
            <div class="flex items-center justify-center p-4">
              <img src="/monster.svg" alt="">
            </div>
            <p class="text-[45px] font-bold max-w-[70%] text-center mx-auto">MonsterONE - Unlimited Digital Products and Services for your Creative Projects</p>
            <div class="flex items-center justify-center gap-6 py-6">
              <p class="flex items-center gap-2 font-semibold justify-center w-[400px] h-[60px] bg-white py-2 px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Unlimited Projects</p>
              <p class="flex items-center gap-2 font-semibold justify-center w-[400px] h-[60px] bg-white py-2 px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Cost-effective Commercial Licensing</p>
              <p class="flex items-center gap-2 font-semibold justify-center w-[400px] h-[60px] bg-white py-2 px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Reliable Product Support & Chat</p>
            </div>
            <p class="text-[24px] text-center font-bold">Get FREE <span class="text-[18px]">access to:</span></p>
            <div>
              <div class="flex items-center gap-6 justify-center py-12">
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="max-h-[18px]" src="/weblium.svg" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Weblium - The most effortless website builder</p>
                    <p class="text-[18px]">Design websites for personal or client needs</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="max-h-[18px]" src="/draftium.svg" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Draftium - Website prototyping tool</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
              </div>
              <button type="submit" class="mx-auto text-center flex justify-center bg-[#f9430a] rounded py-4 text-white font-bold text-[18px] px-20">
                <nuxt-link class="" to="#">Starting at $13.5/mo</nuxt-link>            
              </button>
            </div>
          </div>
        </body>
          
    </div>
    <div class="max-w-[1380px] mx-auto p-4">
      <div class="flex items-center gap-4 justify-center">
        <div class="flex items-center gap-4 bg-blue-500 w-fit py-3 px-5 rounded text-white">
          <img class="w-[20px] h-[20px]" src="/wordpress.svg" alt="">
          <p>Wordpress</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded">
          <img class="w-[20px] h-[20px]" src="/wordpress.svg" alt="">
          <p>Web Templates</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded">
          <img class="w-[20px] h-[20px]" src="/wordpress.svg" alt="">
          <p>Graphic Design</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded">
          <img class="w-[20px] h-[20px]" src="/wordpress.svg" alt="">
          <p>Logo</p>
        </div>
      </div>
      <div class="p-4">
        <div class="flex justify-between items-center gap-4">
          <p class="font-bold text-[20px]">Best WordPress Themes and Plugins to Download</p>
          <button class="font-bold text-[#2196f3]">Browse and Download</button>
        </div>
        <div class="grid grid-cols-3 gap-4 py-4">
          <div class="shadow">
            <nuxt-link to="#">
              <div>
                <img class="w-full" src="theme_1.webp" alt="">
              </div>
              <div class="p-4">
                <div class="flex items-center justify-between gap-4">
                  <img class="max-w-[20px]" src="wordpress.svg" alt="">
                  <p>Monstroid2 - Multipurpose Modular WordPress</p>
                </div>              
                <p>By: ASDF</p>
                <div class="mt-6 flex items-center justify-between gap-4" >
                  <div class="flex items-center gap-1">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                  </div>
                  <div class="">
                    <div class="flex items-center gap-1">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                    </div>
                  </div>
                </div>
                <div class="flex items-center justify-between gap-4 py-2">
                  <p>1234 <span>Sales</span></p>
                  <p>$82</p>
                </div>
              </div>
            </nuxt-link>
            <div class="flex justify-between items-center p-4 gap-4 text-white">
              <button class="bg-[#7a929e] w-[200px] py-2">Details</button>
              <button class="bg-[#00a3ff] w-[200px] py-2">Live Demo</button>
            </div>
          </div>
          <div class="shadow">
            <nuxt-link to="#">
              <div>
                <img class="w-full" src="theme_1.webp" alt="">
              </div>
              <div class="p-4">
                <div class="flex items-center justify-between gap-4">
                  <img class="max-w-[20px]" src="wordpress.svg" alt="">
                  <p>Monstroid2 - Multipurpose Modular WordPress</p>
                </div>              
                <p>By: ASDF</p>
                <div class="mt-6 flex items-center justify-between gap-4" >
                  <div class="flex items-center gap-1">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                  </div>
                  <div class="">
                    <div class="flex items-center gap-1">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                    </div>
                  </div>
                </div>
                <div class="flex items-center justify-between gap-4 py-2">
                  <p>1234 <span>Sales</span></p>
                  <p>$82</p>
                </div>
              </div>
            </nuxt-link>
            <div class="flex justify-between items-center p-4 gap-4 text-white">
              <button class="bg-[#7a929e] w-[200px] py-2">Details</button>
              <button class="bg-[#00a3ff] w-[200px] py-2">Live Demo</button>
            </div>
          </div>
          <div class="shadow">
            <nuxt-link to="#">
              <div>
                <img class="w-full" src="theme_1.webp" alt="">
              </div>
              <div class="p-4">
                <div class="flex items-center justify-between gap-4">
                  <img class="max-w-[20px]" src="wordpress.svg" alt="">
                  <p>Monstroid2 - Multipurpose Modular WordPress</p>
                </div>              
                <p>By: ASDF</p>
                <div class="mt-6 flex items-center justify-between gap-4" >
                  <div class="flex items-center gap-1">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                    <img src="star.svg" alt="">
                  </div>
                  <div class="">
                    <div class="flex items-center gap-1">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                      <img src="rocket.svg" alt="">
                    </div>
                  </div>
                </div>
                <div class="flex items-center justify-between gap-4 py-2">
                  <p>1234 <span>Sales</span></p>
                  <p>$82</p>
                </div>
              </div>
            </nuxt-link>
            <div class="flex justify-between items-center p-4 gap-4 text-white">
              <button class="bg-[#7a929e] w-[200px] py-2">Details</button>
              <button class="bg-[#00a3ff] w-[200px] py-2">Live Demo</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

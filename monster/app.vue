<template>
  <div>
    <div class="showcase pb-4">
      <div class="p-4 bg1 flex gap-4 items-center justify-between">
        <div class="hidden md:block max-[1080px] mx-auto">
          <p class="text-[18px] font-semibold">01:21:57:21</p>
          <p>Day:Hour:Minutes:Second</p>
        </div>
        <h1>Grab Discounted Produts $ Save </h1>
      </div>
      <div class="header_container bg-[#2d394b] flex items-center justify-between gap-4 py-2 px-4">
        <div class="flex items-center justyfy-between gap-4">
          <nuxt-link to="/"><img class="h-[39px] w-[39px] object-contain" src="logo.svg" alt=""></nuxt-link>
            <div class="lg:min-w-[230px] flex items-center gap-4 justify-between bg-[#00a3ff;] py-2 px-4 md:px-6 rounded text-white">
              <div class="flex items-center gap-4 cursor-pointer">
                <svg class="header-button-icon header-button-icon_nav-toggle" width="20" height="20" viewBox="0 0 22 22"><rect width="10.214" height="10.214" rx="1"></rect><rect y="11.786" width="10.214" height="10.214" rx="1"></rect><rect x="11.786" width="10.214" height="10.214" rx="1"></rect><rect x="11.786" y="11.786" width="10.214" height="10.214" rx="1"></rect></svg>
                <p class="hidden lg:flex">All Products</p>
              </div>
              <span class="header-button-arrow"></span>
            </div>

        </div>
          <div class="flex items-center gap-4 justify-between">
            <div class="hidden md:flex items-center lg:min-w-[350px] 2xl:min-w-[600px] justify-between gap-4 bg-white rounded py-2 px-8">
              <input type="text" name="text w-full outline-none" placeholder="e.g. Wordpress">
              <svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="search-button search-form_submit-icon "><path d="M19.65 17.977l-3.843-3.844a8.734 8.734 0 001.804-5.326 8.748 8.748 0 00-2.58-6.227A8.748 8.748 0 008.804 0a8.749 8.749 0 00-6.226 2.58c-3.434 3.434-3.434 9.02 0 12.454a8.748 8.748 0 006.226 2.579c1.952 0 3.802-.64 5.327-1.804l3.843 3.844a1.18 1.18 0 001.676 0 1.185 1.185 0 000-1.676zm-15.397-4.62a6.444 6.444 0 010-9.101A6.395 6.395 0 018.804 2.37c1.72 0 3.336.67 4.551 1.885a6.394 6.394 0 011.885 4.55c0 1.72-.67 3.336-1.885 4.552a6.394 6.394 0 01-4.55 1.885 6.394 6.394 0 01-4.552-1.886z"></path></svg>
            </div>
            <div class="hidden xl:flex items-center justify-between gap-4 rounded bg-[#f3683e] text-white py-2 px-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" class="header-button-icon inline-svg inlined-svg" data-src="/assets/icons/monsterEye.svg" role="img" aria-labelledby="title"><title>monsterEye</title><path fill-rule="evenodd" clip-rule="evenodd" d="M18 9A9 9 0 1 1 .352 6.5 11.87 11.87 0 0 1 0 3.652c0-.759.095-1.518.238-2.277v-.047C.333.854.428.427.57 0l2.824 1.958A8.962 8.962 0 0 1 9 0c2.12 0 4.067.732 5.605 1.958L17.43 0c.142.427.237.854.332 1.328v.047c.143.76.238 1.518.238 2.277 0 .98-.127 1.938-.352 2.848.23.794.352 1.633.352 2.5zm-9 4.304a4.304 4.304 0 1 0 0-8.608 4.304 4.304 0 0 0 0 8.608z"></path><path d="m9.747 9.747.934 5.23 2.801-1.196v-2.39L9.747 9.746zm6.297-4.66c0 1.729-3.154 3.13-7.044 3.13-3.89 0-7.043-1.401-7.043-3.13 0-1.729 3.153-3.13 7.043-3.13s7.044 1.401 7.044 3.13z"></path></svg>
              <p>Unlimited Download</p>
            </div>
            <div class="hidden bg-white rounded xl:flex items-center gap-4 py-2 px-6">
              <svg xmlns="http://www.w3.org/2000/svg" class="header-button-icon-2 inline-svg inlined-svg" width="20" height="20" data-src="/assets/icons/wallet.svg" role="img" aria-labelledby="title"><title>wallet</title><path d="M16.087 14.571c-2.047 0-3.712-1.73-3.712-3.857 0-2.126 1.665-3.857 3.712-3.857h2.063V5.143c0-.946-.74-1.714-1.65-1.714h-.825V1.714c0-.945-.74-1.714-1.65-1.714H2.475C1.25 0 .24.93.042 2.142c-.018.07-.042.139-.042.215V15.43C0 16.846 1.11 18 2.475 18H16.5c.91 0 1.65-.769 1.65-1.714V14.57h-2.063zm-14.437-12c0-.472.37-.857.825-.857h11.55V3.43H2.475c-.455 0-.825-.385-.825-.858z"></path><path d="M19.181 8.143h-3.093c-1.365 0-2.475 1.154-2.475 2.571 0 1.418 1.11 2.572 2.475 2.572h3.093a.631.631 0 0 0 .62-.643V8.786a.631.631 0 0 0-.62-.643zm-3.093 3.429c-.456 0-.825-.384-.825-.857 0-.474.37-.858.825-.858.455 0 .825.384.825.857 0 .474-.37.858-.825.858z"></path></svg>
              <p>Start Selling</p>
            </div>
            <div class="flex items-center justify-between py-2 px-2 xl:px-6 gap-4">
              <svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="md:hidden search-button search-form_submit-icon "><path d="M19.65 17.977l-3.843-3.844a8.734 8.734 0 001.804-5.326 8.748 8.748 0 00-2.58-6.227A8.748 8.748 0 008.804 0a8.749 8.749 0 00-6.226 2.58c-3.434 3.434-3.434 9.02 0 12.454a8.748 8.748 0 006.226 2.579c1.952 0 3.802-.64 5.327-1.804l3.843 3.844a1.18 1.18 0 001.676 0 1.185 1.185 0 000-1.676zm-15.397-4.62a6.444 6.444 0 010-9.101A6.395 6.395 0 018.804 2.37c1.72 0 3.336.67 4.551 1.885a6.394 6.394 0 011.885 4.55c0 1.72-.67 3.336-1.885 4.552a6.394 6.394 0 01-4.55 1.885 6.394 6.394 0 01-4.552-1.886z"></path></svg>
              <svg viewBox="0 0 22 20" width="20" height="20" class=" love"><path fill-rule="evenodd" clip-rule="evenodd" d="M1.795 10.556a6.195 6.195 0 018.781-8.742l.424.424.424-.424a6.193 6.193 0 018.76 0 6.197 6.197 0 01.02 8.742l-8.405 8.9a1.1 1.1 0 01-1.598 0l-8.406-8.9zM11 17.098l7.607-8.055.023-.022a3.999 3.999 0 000-5.651 3.997 3.997 0 00-5.652 0l-1.2 1.201c-.43.43-1.127.43-1.556 0L9.021 3.37A3.993 3.993 0 002.2 6.195a3.994 3.994 0 001.19 2.848L11 17.098z"></path></svg>
              <svg viewBox="0 0 20 22" width="20" height="20" class=" login"><path d="M13.694 10.722a5.998 5.998 0 10-7.389 0A10.004 10.004 0 000 20v1A1 1 0 001 22h17.992a1 1 0 001-1v-1a10.004 10.004 0 00-6.298-9.278zM5.997 6.007a3.998 3.998 0 117.997 0 3.998 3.998 0 01-7.997 0zM2 20a7.997 7.997 0 1115.993 0H2z"></path></svg>
              <svg viewBox="0 0 22 22" width="20" height="20" class=" header-button-icon_cart cart"><path d="M19.45 15.24a.86.86 0 00.848-.719l1.69-10.14a.86.86 0 00-.848-1H4.91L4.229.65A.86.86 0 003.395 0H.858a.86.86 0 100 1.719h1.865l.673 2.696L5.07 14.45v2.6a2.553 2.553 0 00-1.69 2.4A2.552 2.552 0 005.93 22c1.744 0 2.981-1.726 2.41-3.38h7.01c-.572 1.655.667 3.38 2.41 3.38a2.552 2.552 0 002.55-2.55 2.552 2.552 0 00-2.55-2.55H6.79v-1.66H19.45zm.676-10.141l-1.404 8.422H6.658L5.254 5.099h14.872zM6.76 19.45a.832.832 0 01-1.661 0 .832.832 0 011.661 0zm11 .831a.832.832 0 010-1.661.832.832 0 010 1.661z"></path></svg>            
            </div>
          </div>
        </div>
        <div class="hidden navbar lg:flex items-center justify-center gap-8 font-semibold p-4">
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
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 py-6 px-4">
              <p class="flex items-center gap-2 font-semibold lg:justify-center lg:w-[400px] h-[60px] bg-white py-2 lg:px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Unlimited Projects</p>
              <p class="flex items-center gap-2 font-semibold lg:justify-center lg:w-[400px] h-[60px] bg-white py-2 lg:px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Cost-effective Commercial Licensing</p>
              <p class="flex items-center gap-2 font-semibold lg:justify-center lg:w-[400px] h-[60px] bg-white py-2 lg:px-12 rounded"><span><svg xmlns="http://www.w3.org/2000/svg" width="30" height="20" viewBox="0 0 24 24"><path fill="#31af36" d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z"/></svg></span> Reliable Product Support & Chat</p>
            </div>
            <p class="text-[24px] text-center font-bold">Get FREE <span class="text-[18px]">access to:</span></p>
            <div>
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6 py-12 px-4 max-w-7xl mx-auto">
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="ecommerce-dropshipping.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">e-commerce & Dropshipping</p>
                    <p class="text-[18px]">Design websites for personal or client needs</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="domain.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Domain</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="web-mail.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Webmail</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="facebook-boosting.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Facebook Boosting</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="email-marketing.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Email Marketing</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="sms-marketing.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">SMS Marketing</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="billing.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Blling</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
                <div class="bg-white p-4 rounded">
                  <div class="flex items-center gap-4">
                    <img class="w-28" src="account-setting.png" alt="">
                    <p class="font-bold p-1 bg-[#31af36] w-[80px] text-center rounded text-[14px] text-white">SAVE $99</p>
                  </div>
                    <p class="text-[22px] font-bold">Account Setting</p>
                    <p class="text-[18px]">Collaborate with your team and clients on website prototypes</p>
                </div>
              </div>
              <button type="submit" class="mx-auto text-center flex justify-center px-4 bg-[#f9430a] rounded py-4 text-white font-bold text-[18px] lg:px-20">
                <nuxt-link class="" to="#">Starting at $13.5/mo</nuxt-link>            
              </button>
            </div>
          </div>
        </body>
          
    </div>
    <div class="max-w-[1380px] mx-auto p-4">
      <div class="flex items-center gap-4 lg:justify-center overflow-scroll lg:overflow-hidden">
        <div class="flex items-center gap-4 bg-blue-500 w-fit py-3 px-5 rounded text-white whitespace-nowrap">
          <img class="w-[20px] h-[20px]" src="wordpress.svg" alt="">
          <p>Wordpress</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded whitespace-nowrap">
          <img class="w-[20px] h-[20px]" src="wordpress.svg" alt="">
          <p>Web Templates</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded whitespace-nowrap">
          <img class="w-[20px] h-[20px]" src="wordpress.svg" alt="">
          <p>Graphic Design</p>
        </div>
        <div class="flex items-center gap-4 border w-fit py-3 px-5 rounded whitespace-nowrap">
          <img class="w-[20px] h-[20px]" src="wordpress.svg" alt="">
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
      
      <div class="join_content">
        <p class="text-[24px] font-semibold mb-[30px] text-center">Join us and get access to 290000+ premium digital products</p>
        <div class="grid grid-cols-4 gap-6">
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="48" height="48" rx="5" fill="#3DA7ED" stroke="#91D3FF" stroke-width="2"></rect> <path d="M25 10a15 15 0 1 0 0 30 15 15 0 0 0 0-30ZM11.5 25c0-2 .4-3.8 1.2-5.5L19 37.1A13.5 13.5 0 0 1 11.5 25ZM25 38.5c-1.3 0-2.6-.2-3.8-.6l4-11.7 4.2 11.3v.2c-1.3.5-2.8.8-4.4.8Zm1.9-19.8 1.5-.1c.7-.1.6-1.2 0-1.2l-3.7.2-3.5-.2c-.8 0-.8 1.1-.1 1.2h1.4l2.1 5.8-3 8.9-4.9-14.6 1.6-.1c.7-.1.6-1.2-.1-1.2l-3.6.2h-.9A13.5 13.5 0 0 1 34.1 15H34c-1.3 0-2.2 1.2-2.2 2.4 0 1.1.6 2 1.3 3.2a7 7 0 0 1 1.1 3.7c0 1.2-.4 2.5-1 4.4l-1.4 4.5L27 18.7Zm10-.2a13.4 13.4 0 0 1-5.1 18.2l4.1-12a12.8 12.8 0 0 0 1-6.2Z" fill="#fff"></path> </svg>
                <p class="font-semibold">WordPress Themes & Plugins</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon join__item-icon_large" width="54" height="54" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="52" height="52" rx="7" fill="#F45B39" stroke="#FFA48F" stroke-width="2"></rect> <g clip-path="url(#a)"> <path d="M15.6 38.3 27 42l11.4-3.7L40.3 12H13.8l1.8 26.3Zm20-22-.3 3.6h-13l.3 4.5H35L34.2 35 27 37.4 19.8 35l-.2-3.5H23v1l4 1.2 3.8-1.3.3-4.5h-12l-.7-11.5h17Z" fill="#fff"></path> </g> <defs> <clipPath id="a"><path fill="#fff" transform="translate(12 12)" d="M0 0h30v30H0z"></path></clipPath> </defs> </svg>
                <p class="font-semibold">HTML Templates</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M1 6a5 5 0 0 1 5-5h38a5 5 0 0 1 5 5v38a5 5 0 0 1-5 5H6a5 5 0 0 1-5-5V6Z" fill="#38B723" stroke="#A4EA99" stroke-width="2"></path> <g clip-path="url(#a)" fill="#fff"> <path d="M28.7 25.1a4 4 0 0 1-1.1 2.4c-.8.8-2 1.1-3.3 1-1 0-1.5.3-1.5.3a1.6 1.6 0 0 1-2.3 0c-.5-.6-.6-1.4-.2-2l.2-.4.2-1.4c0-1.4.3-2.5 1.1-3.3a4 4 0 0 1 2.4-1.1c.1-.6.4-1.2.8-1.7h-9.4c-1 0-1.9.9-1.9 1.9V30h19.6v-9.2l-2.4 2.9c-.6.7-1.3 1.1-2.2 1.3ZM13.7 32.1c0 1 .8 1.9 1.9 1.9h5.3v1.6h-1.2a.7.7 0 1 0 0 1.4h7.6a.7.7 0 0 0 0-1.4H26V34h5.3c1 0 1.9-.9 1.9-1.9v-.6H13.7v.6Z"></path> <path d="M21.5 27.4a.2.2 0 0 0 .4.4s.7-.7 2.4-.6c1 0 1.8-.2 2.3-.7a2.7 2.7 0 0 0-3.8-3.8c-.5.5-.7 1.3-.7 2.3.1 1.7-.6 2.4-.6 2.4ZM28.7 23.7l1.1-.8 1-1.1-3.3-3.2-1 .9c-.4.3-.7.7-.9 1.1a4 4 0 0 1 3 3ZM35.9 13.4c-.5-.5-1.4-.5-2 0l-5.3 4.3 3 3 4.4-5.4c.4-.5.4-1.4-.1-1.9Z"></path> </g> <defs> <clipPath id="a"><path fill="#fff" transform="translate(13 13)" d="M0 0h24v24H0z"></path></clipPath> </defs> </svg>
                <p class="font-semibold">Graphic Templates</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="48" height="48" rx="5" fill="#D24726" stroke="#FFAD98" stroke-width="2"></rect> <g clip-path="url(#a)"> <path d="m26.8 12 .4.3v13.1l-13 .3v-1.2c0-3.7 1.2-6.8 3.3-9 2.1-2.1 5.2-3.4 9.3-3.5Z" fill="#ED6C47" stroke="#fff" stroke-width="2"></path> <path d="M27.8 12C34.5 12.5 40 18 40 24.5v.5H27.7V12Z" fill="#FF8F6B" stroke="#fff" stroke-width="2"></path> <path d="M14.1 26H40c-.5 6.6-6 11.9-12.8 12h-.3C20 37.8 14.6 32.5 14 26Z" fill="#D35230" stroke="#FEFEFE" stroke-width="2"></path> <path d="M13 17h12.8c.7 0 1.3.6 1.3 1.3V31c0 .7-.6 1.2-1.3 1.2H13c-.7 0-1.3-.5-1.3-1.2V18.3c0-.7.6-1.3 1.3-1.3Z" fill="#FEFEFE"></path> <path d="M19.6 20.7c.9 0 1.7.2 2.4.7a2.4 2.4 0 0 1 .8 2c0 .5-.2 1-.4 1.4-.3.5-.7.8-1.2 1-.5.3-1 .4-1.7.4H18v3h-1.6v-8.5h3.3ZM18 24.9h1.4c.5 0 1-.1 1.3-.4a1.4 1.4 0 0 0 .4-1c0-1-.5-1.5-1.6-1.5h-1.5V25Z" fill="#D35230"></path> </g> <defs> <clipPath id="a"><path fill="#fff" transform="translate(11 11)" d="M0 0h30v28.1H0z"></path></clipPath> </defs> </svg>
                <p class="font-semibold">Presentation Templates</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="48" height="48" rx="5" fill="#669CED" stroke="#BDD6FD" stroke-width="2"></rect> <path fill-rule="evenodd" clip-rule="evenodd" d="M13 10a3 3 0 0 0-3 3v5h30v-5a3 3 0 0 0-3-3H13Zm2 3a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm4 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm4 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm-13 7v17a3 3 0 0 0 3 3h24a3 3 0 0 0 3-3V20H10Zm3 5c0-.6.4-1 1-1h15c.6 0 1 .4 1 1v10c0 .6-.4 1-1 1H14a1 1 0 0 1-1-1V25Zm20-1a1 1 0 0 0-1 1v10c0 .6.4 1 1 1h3c.6 0 1-.4 1-1V25c0-.6-.4-1-1-1h-3Z" fill="#fff"></path> </svg>
                <p class="font-semibold">CMS & E-Commerce Templates</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="48" height="48" rx="5" fill="#95BF46" stroke="#C4DF92" stroke-width="2"></rect> <g clip-path="url(#a)"> <path d="M35.1 14.9c0-.2-.1-.2-.3-.3l-2.4-.1-1.7-1.8a350.1 350.1 0 0 0-1.5.2c-.6-1.5-1.6-3-3.2-3h-.2c-.4-.5-1-.8-1.5-.8-3.9 0-5.8 4.8-6.3 7.2l-2.7.9c-.9.2-1 .3-1 1L12 35.7 29.1 39l9.3-2L35 15Zm-7-1.7-1.4.4v-.3a7 7 0 0 0-.3-2.3c.8.1 1.4 1 1.8 2.2Zm-2.8-2c.2.6.4 1.4.4 2.6v.2l-3 .9c.6-2.2 1.7-3.3 2.6-3.7Zm-1.1-1h.5c-1.3.7-2.6 2.1-3.2 5l-2.3.8c.6-2.3 2.2-5.9 5-5.9Z" fill="#fff"></path> <path d="m34.8 14.6-2.4-.1-1.7-1.8-.3-.1-1.3 26.3 9.3-2L35 15c0-.2-.1-.2-.3-.3Z" fill="#C4DF92"></path> <path d="m26 19.7-1.2 3.4s-1-.5-2.2-.5c-1.8 0-1.9 1.1-1.9 1.4 0 1.5 4 2.1 4 5.8 0 2.8-1.8 4.6-4.2 4.6-3 0-4.4-1.8-4.4-1.8l.7-2.6s1.6 1.4 2.9 1.4c.8 0 1.2-.7 1.2-1.2 0-2-3.3-2.1-3.3-5.4 0-2.8 2-5.5 6-5.5a5 5 0 0 1 2.4.4Z" fill="#95BF46"></path> </g> <defs> <clipPath id="a"><path fill="#fff" transform="translate(12 9)" d="M0 0h26.4v30H0z"></path></clipPath> </defs> </svg>
                <p class="font-semibold">Shopify Themes</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon" width="50" height="50" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="48" height="48" rx="5" fill="#DC5EB9" stroke="#EABDDD" stroke-width="2"></rect> <g clip-path="url(#a)" fill="#fff"> <path d="m36.3 26.1-9.6 2.4a1 1 0 0 0-.7.9v7.2c-1.8-.7-3.8.7-3.8 2.6 0 .7.3 1.4.8 2 1.1 1 2.9 1 4 0 .5-.6.8-1.3.8-2v-5.3l7.6-2v2.8a2.8 2.8 0 1 0-1.2 5.4c1.7 0 3-1.2 3-3V26.8c-.1-.4-.5-.7-.9-.8ZM24 24.7a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path> <path d="M24.2 34.4V28c0-.4.3-.8.7-.9l10.3-2.6C35.9 17.8 30.7 12 24 12a11.2 11.2 0 1 0 .1 22.4Zm-3.4-11.2a3.2 3.2 0 1 1 6.5 0 3.2 3.2 0 0 1-6.5 0Z"></path> </g> <defs> <clipPath id="a"><path fill="#fff" transform="translate(10 12)" d="M0 0h30v30H0z"></path></clipPath> </defs> </svg>
                <p class="font-semibold">Audio Products</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
          <div class="join_item">
            <nuxt-link to="#">
              <div class="flex items-center justify-between gap-4 p-4">
                <svg class="join__item-icon join__item-icon_large" width="54" height="54" fill="none" xmlns="http://www.w3.org/2000/svg"> <rect x="1" y="1" width="52" height="52" rx="7" fill="#7539F4" stroke="#D1BBFF" stroke-width="2"></rect> <path d="M27 12a15 15 0 1 0 0 30 15 15 0 0 0 0-30Zm6.3 15.5a1 1 0 0 1-.5.5l-8.5 4.3a1 1 0 0 1-1.6-1v-8.6a1 1 0 0 1 1.6-1l8.5 4.3c.6.3.8 1 .5 1.5Z" fill="#fff"></path> </svg>
                <p class="font-semibold">Video Products</p>
              </div>
                <hr class="w-[90%] mx-auto">
              <div class="p-4 flex items-center justify-between">
                <p class="font-semibold">2826 <span class="font-normal">Items</span></p>
                <p class="text-[#31af36] font-semibold">+37 <span class="text-[#243238] font-normal text-[14px]">the last week</span></p>
              </div>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

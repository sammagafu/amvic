
<template>
  <section class="py-36 lg:py-64 w-full table relative bg-center bg-cover custom-section" id="home">
    <div class="absolute inset-0 bg-black opacity-80"></div>
    <div class="mx-auto px-4 sm:px-6 lg:max-w-7xl lg:px-8 container h-full relative">
      <div class="grid grid-cols-1 mt-12">
        <p class="text-yellow-200 font-medium">Welcome to AMVIC Insuarance Brokers your Partner for</p>
        <h4 class="text-white lg:text-5xl text-4xl lg:leading-normal leading-normal font-medium mb-7 position-relative">
          <span class="text-yellow-200 font-bold"><vue-writer :array="insuarance" :typeSpeed="100"></vue-writer></span>
        </h4>
        <p class="text-white mb-0 max-w-2xl text-lg">Welcome to AMVIC Insurance Brokers, where your aspirations are our
          utmost priority. As Tanzania's most recent independent insurance brokerage company, we take pride in offering a
          diverse array of insurance products to cater to your unique needs with unparalleled professionalism
        </p>
        <div class="relative mt-10"><a
            class="p-3 bg-yellow-300 hover:bg-yellow-500 border-yellow-600 hover:border-yellow-700 text-slate rounded-md">Get
            Started</a></div>
      </div>
    </div>
  </section>

  <section class="my-48">
    <div class="mx-auto px-4 sm:px-6 lg:max-w-7xl lg:px-8">
      <div class="grid grid-cols-1 gap-5 xl:gap-10 lg:grid-cols-3 items-center">
        <div class="col-span-1">
          <div class=" mb-10">
            <h4 class="text-porange-700 text-xl font-medium capitalize mb-2">
              About Us
            </h4>
            <h2 class="text-4xl leading-snug font-bold text-interface-100 capitalize">
              Your Shield Of Assuarance,
              <span class="relative z-30"><span class="relative z-10"> </span>
                <svg class="absolute right-0 bottom-1" width="214" height="9" viewBox="0 0 180 9" fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <path d="M3 6C26.9011 3.73613 95.1626 0.566711 177 6" stroke="#ffd757" stroke-width="6"
                    stroke-linecap="round"></path>
                </svg>
              </span>
              Our Pledge Of Care
            </h2>
            <p class="text-interface-500 text-lg mt-4 mb-8">
              AMVIC Insurance Brokers is a distinguished and dynamic independent insurance brokerage company based in
              Tanzania.
            </p>
            <p>On behalf of the entire AMVIC Insurance Brokers team, we extend a warm and heartfelt welcome to you.</p>
          </div>
        </div>
        <div class="col-span-1">
          <div>
            <img src="@/assets/img/bg/team.jpg" class="mx-auto" alt="">
          </div>
        </div>
        <div class="col-span-1">
          <ul class="divide-y divide-[#177370] divide-opacity-10">
            <li class="flex space-x-4 py-8">
              <div
                class="w-[60px] h-[60px] rounded-full shrink-0 inline-flex items-center justify-center bg-porange-700 bg-opacity-10">
                <svg width="30" height="32" viewBox="0 0 30 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M10.536 4.53675C10.536 2.03711 12.5404 0 14.9994 0C17.4598 0 19.4645 2.03693 19.4645 4.53675C19.4645 5.44892 19.1979 6.29935 18.7399 7.01177C20.0499 7.86686 20.9234 9.36246 20.9234 11.0581V13.5082C20.9234 14.463 20.1582 15.2405 19.2193 15.2405H17.7603C17.4208 15.2405 17.1456 14.9607 17.1456 14.6155C17.1456 14.2703 17.4208 13.9905 17.7603 13.9905H19.2193C19.4795 13.9905 19.6939 13.7724 19.6939 13.5082V11.0581C19.6939 9.74152 18.9785 8.5813 17.919 7.96706C17.1354 8.6571 16.1142 9.07526 14.9994 9.07526C13.885 9.07526 12.864 8.65687 12.0806 7.96653C11.0206 8.58063 10.3048 9.74115 10.3048 11.0581V13.5082C10.3048 13.7723 10.5192 13.9905 10.7794 13.9905H12.2383C12.5779 13.9905 12.8531 14.2703 12.8531 14.6155C12.8531 14.9607 12.5779 15.2405 12.2383 15.2405H10.7794C9.84049 15.2405 9.07524 14.463 9.07524 13.5082V11.0581C9.07524 9.36193 9.94936 7.86593 11.26 7.01098C10.8023 6.29871 10.536 5.44855 10.536 4.53675ZM14.9994 1.25C13.2192 1.25 11.7655 2.72777 11.7655 4.53675C11.7655 6.34767 13.2194 7.82526 14.9994 7.82526C16.7813 7.82526 18.2349 6.34749 18.2349 4.53675C18.2349 2.72795 16.7814 1.25 14.9994 1.25ZM2.26879 9.31731C2.26878 9.31737 2.26878 9.31744 2.26877 9.3175L1.26828 18.1435C1.26785 18.1472 1.26739 18.151 1.26689 18.1548C1.1528 19.0218 1.30779 19.6045 1.61331 20.1105C1.94221 20.6551 2.45823 21.1383 3.16362 21.7828C4.89373 23.3619 5.80074 24.4315 5.80074 26.0052V26.895H10.8462V22.3309C10.8462 20.7717 9.88315 19.5258 8.57595 18.2095C8.57592 18.2095 8.57589 18.2095 8.57586 18.2095L6.9584 16.5814L6.95808 16.5811C6.56211 16.182 5.91597 16.1855 5.52658 16.5846L5.52598 16.5852C5.13512 16.9846 5.13607 17.6399 5.53112 18.0403L5.53126 18.0404L8.01162 20.5562C8.25198 20.8 8.25244 21.1957 8.01264 21.4401C7.77285 21.6844 7.38361 21.6849 7.14325 21.4411L4.66303 18.9255C4.66298 18.9255 4.66293 18.9254 4.66289 18.9254C3.85788 18.1093 3.78955 16.8176 4.46518 15.9233L4.18312 9.43106C4.18312 9.43103 4.18312 9.431 4.18312 9.43097C4.15549 8.79783 3.75086 8.37689 3.27551 8.35347L3.27424 8.35341C2.78579 8.32832 2.3371 8.71752 2.26879 9.31731ZM5.6606 15.111C6.40664 14.9086 7.23745 15.1027 7.82343 15.6931L7.82375 15.6934M7.82375 15.6934L9.44098 17.3213L9.44107 17.3213C10.7519 18.6413 12.0757 20.2122 12.0757 22.3309V26.9218C12.8245 27.0614 13.397 27.7303 13.397 28.5333V30.3599C13.397 31.2626 12.6726 32 11.7852 32H4.86179C3.97441 32 3.25002 31.2626 3.25002 30.3599V28.5333C3.25002 27.7303 3.82252 27.0614 4.57123 26.9218V26.0052C4.57123 25.0457 4.09782 24.3153 2.34203 22.7127L2.34182 22.7125L2.33421 22.7056C1.66343 22.0928 1.00362 21.49 0.565503 20.7645C0.103137 19.9988 -0.100159 19.1251 0.0474728 17.9948L1.04739 9.17391C1.17783 8.02713 2.09885 7.0418 3.33565 7.10497C4.58553 7.16689 5.36244 8.25161 5.41143 9.37573L5.6606 15.111M26.6631 7.10497C27.8999 7.04183 28.8209 8.02715 28.9513 9.17391L28.9513 9.17403L29.953 17.9951C30.0997 19.1252 29.8965 19.9987 29.4344 20.7643C28.996 21.4908 28.3356 22.0941 27.6639 22.7078L27.6587 22.7125L27.6585 22.7127C25.9026 24.3153 25.4292 25.0457 25.4292 26.0052V26.922C26.1787 27.0622 26.7487 27.7313 26.7487 28.5333V30.3599C26.7487 31.2618 26.0268 32 25.1369 32H18.2153C17.3269 32 16.6018 31.2633 16.6018 30.3599V28.5333C16.6018 27.7302 17.1741 27.0621 17.923 26.922V22.3309C17.923 20.2122 19.2468 18.6413 20.5576 17.3213L20.558 17.321L22.1767 15.6934C22.1767 15.6934 22.1768 15.6933 22.1769 15.6933C22.7633 15.1023 23.5936 14.9086 24.3396 15.1112L24.5872 9.37599L24.5872 9.37568C24.6363 8.25159 25.4132 7.16685 26.6631 7.10497ZM24.4745 16.5852C24.0828 16.185 23.438 16.1823 23.0423 16.5811L21.4228 18.2095C21.4227 18.2096 21.4226 18.2097 21.4225 18.2098M21.4225 18.2098C20.1154 19.526 19.1525 20.7718 19.1525 22.3309V26.895H24.1997V26.0052C24.1997 24.4314 25.1068 23.3618 26.8371 21.7826C27.5422 21.1384 28.0578 20.6552 28.3864 20.1106C28.6918 19.6045 28.8469 19.0216 28.7335 18.1542C28.733 18.1507 28.7326 18.1471 28.7322 18.1436L27.73 9.3175C27.73 9.31746 27.7299 9.31742 27.7299 9.31738C27.6617 8.71755 27.213 8.32832 26.7245 8.35341L26.7232 8.35347C26.2479 8.37689 25.8433 8.79773 25.8156 9.4308C25.8155 9.4309 25.8155 9.431 25.8155 9.43111L25.5353 15.9232C26.2112 16.8182 26.1402 18.1096 25.338 18.9249L25.3375 18.9254L22.8572 21.4411C22.6168 21.6849 22.2276 21.6844 21.9878 21.4401C21.748 21.1957 21.7484 20.8 21.9888 20.5562L24.4687 18.0409C24.4689 18.0407 24.469 18.0406 24.4692 18.0404M24.4745 16.5852C24.8644 16.9837 24.8636 17.6391 24.4692 18.0404L24.4745 16.5852ZM14.3846 14.6155C14.3846 14.2703 14.6598 13.9905 14.9993 13.9905H15.0028C15.3424 13.9905 15.6176 14.2703 15.6176 14.6155C15.6176 14.9607 15.3424 15.2405 15.0028 15.2405H14.9993C14.6598 15.2405 14.3846 14.9607 14.3846 14.6155ZM4.86179 28.145C4.65311 28.145 4.47954 28.3213 4.47954 28.5333V30.3599C4.47954 30.5733 4.65454 30.75 4.86179 30.75H11.7852C11.9924 30.75 12.1674 30.5733 12.1674 30.3599V28.5333C12.1674 28.3213 11.9939 28.145 11.7852 28.145H4.86179ZM18.2153 28.145C18.0041 28.145 17.8313 28.3221 17.8313 28.5333V30.3599C17.8313 30.5726 18.0056 30.75 18.2153 30.75H25.1369C25.3453 30.75 25.5192 30.574 25.5192 30.3599V28.5333C25.5192 28.3206 25.3467 28.145 25.1369 28.145H18.2153Z"
                    fill="#FFB711"></path>
                </svg>
              </div>
              <div>
                <h4 class="text-2xl text-interface-100 font-semibold mb-2">
                  Our Mission
                </h4>
                <p class="text-interface-500 text-lg">To be the leading insurance brokerage firm in Tanzania, known for
                  our unwavering commitment to exceptional service, innovative solutions, and the protection of our
                  clients’ dreams.</p>
              </div>
            </li>

            <li class="flex space-x-4 py-8">
              <div
                class="w-[60px] h-[60px] rounded-full shrink-0 inline-flex items-center justify-center bg-seagreen-500 bg-opacity-10">
                <svg width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M25.5391 6.5625H22.2009C22.717 5.8765 23.0234 5.0242 23.0234 4.10156C23.0234 1.83996 21.1835 0 18.9219 0C17.5596 0 16.555 0.488086 15.7604 1.53601C15.0957 2.41276 14.6097 3.63688 14 5.18355C13.3903 3.63683 12.9043 2.41276 12.2396 1.53601C11.445 0.488086 10.4404 0 9.07812 0C6.81652 0 4.97656 1.83996 4.97656 4.10156C4.97656 5.0242 5.28298 5.8765 5.79912 6.5625H2.46094C1.10398 6.5625 0 7.66648 0 9.02344V10.6641C0 11.7335 0.685836 12.6453 1.64062 12.9839V25.5391C1.64062 26.896 2.7446 28 4.10156 28H23.8984C25.2554 28 26.3594 26.896 26.3594 25.5391V12.9839C27.3142 12.6453 28 11.7335 28 10.6641V9.02344C28 7.66648 26.896 6.5625 25.5391 6.5625ZM15.5058 5.83734C16.7624 2.64917 17.2402 1.64062 18.9219 1.64062C20.2788 1.64062 21.3828 2.7446 21.3828 4.10156C21.3828 5.45852 20.2788 6.5625 18.9219 6.5625H15.2188C15.3193 6.31012 15.4152 6.06714 15.5058 5.83734ZM9.07812 1.64062C10.7598 1.64062 11.2376 2.64917 12.4942 5.83734C12.5848 6.06714 12.6807 6.31012 12.7812 6.5625H9.07812C7.72116 6.5625 6.61719 5.45852 6.61719 4.10156C6.61719 2.7446 7.72116 1.64062 9.07812 1.64062ZM10.7188 26.3594H4.10156C3.64924 26.3594 3.28125 25.9914 3.28125 25.5391V13.125H10.7188V26.3594ZM10.7188 11.4844H2.46094C2.00862 11.4844 1.64062 11.1164 1.64062 10.6641V9.02344C1.64062 8.57112 2.00862 8.20312 2.46094 8.20312H10.7188V11.4844ZM15.6406 26.3594H12.3594V8.20312C12.5313 8.20312 14.6978 8.20312 15.6406 8.20312V26.3594ZM24.7188 25.5391C24.7188 25.9914 24.3508 26.3594 23.8984 26.3594H17.2812V13.125H24.7188V25.5391ZM26.3594 10.6641C26.3594 11.1164 25.9914 11.4844 25.5391 11.4844H17.2812V8.20312H25.5391C25.9914 8.20312 26.3594 8.57112 26.3594 9.02344V10.6641Z"
                    fill="#47D990"></path>
                </svg>
              </div>
              <div>
                <h4 class="text-2xl text-interface-100 font-semibold mb-2">
                  Our Vision
                </h4>
                <p class="text-interface-500 text-lg">
                  We strive to empower our clients by delivering tailor-made insurance solutions, backed by expert
                  insights and personalized service, to safeguard their assets, mitigate risks, and facilitate their
                  aspirations.
                </p>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section class="my-48">
    <div class="max-w-screen-xl mx-auto my-24">
      <div class="hidden md:block text-2xl font-medium mb-[100px]">
        <div class="font-semibold py-4">Our Services</div>
        <div class="">We offer personalized and comprehensive insurance solutions to safeguard what matters most in your
          life.</div>
      </div>

      <div class="mx-auto max-w-7xl px-6 lg:px-8 mt-16">
        <div class="mx-auto max-w-2xl lg:max-w-none">
          <div class="lg:flex lg:items-center lg:justify-end">
            <div class="flex justify-center lg:w-1/2 lg:justify-end lg:pr-12">
              <div class="w-[33.75rem] flex-none lg:w-[45rem]" style="opacity: 1; transform: none;">
                <div class="justify-center lg:justify-end relative flex aspect-[719/680] w-full grayscale"><svg
                    viewBox="0 0 655 680" fill="none" class="h-full">
                    <g clip-path="url(#:S1:-clip)" class="group">
                      <g class="origin-center scale-100 transition duration-500 motion-safe:group-hover:scale-105">
                        <foreignObject width="655" height="680"><img alt="" loading="lazy" width="2400" height="3000"
                            decoding="async" data-nimg="1" class="w-full bg-neutral-100 object-cover"
                            style="color:transparent;aspect-ratio:655 / 680" sizes="(min-width: 1024px) 41rem, 31rem"
                            srcset="@/assets/img/service/health.jpg" src="@/assets/img/service/health.jpg">
                        </foreignObject>
                      </g>
                      <use href="#:S1:-shape" stroke-width="2" class="stroke-neutral-950/10"></use>
                    </g>
                    <defs>
                      <clipPath id=":S1:-clip">
                        <path id=":S1:-shape"
                          d="M537.827 9.245A11.5 11.5 0 0 1 549.104 0h63.366c7.257 0 12.7 6.64 11.277 13.755l-25.6 128A11.5 11.5 0 0 1 586.87 151h-28.275a15.999 15.999 0 0 0-15.689 12.862l-59.4 297c-1.98 9.901 5.592 19.138 15.689 19.138h17.275l.127.001c.85.009 1.701.074 2.549.009 11.329-.874 21.411-7.529 24.88-25.981.002-.012.016-.016.023-.007.008.009.022.005.024-.006l24.754-123.771A11.5 11.5 0 0 1 580.104 321h63.366c7.257 0 12.7 6.639 11.277 13.755l-25.6 128A11.5 11.5 0 0 1 617.87 472H559c-22.866 0-28.984 7.98-31.989 25.931-.004.026-.037.035-.052.014-.015-.02-.048-.013-.053.012l-24.759 123.798A11.5 11.5 0 0 1 490.87 631h-29.132a14.953 14.953 0 0 0-14.664 12.021c-4.3 21.502-23.18 36.979-45.107 36.979H83.502c-29.028 0-50.8-26.557-45.107-55.021l102.4-512C145.096 91.477 163.975 76 185.902 76h318.465c10.136 0 21.179-5.35 23.167-15.288l10.293-51.467Zm-512 160A11.5 11.5 0 0 1 37.104 160h63.366c7.257 0 12.7 6.639 11.277 13.755l-25.6 128A11.5 11.5 0 0 1 74.87 311H11.504c-7.257 0-12.7-6.639-11.277-13.755l25.6-128Z"
                          fill-rule="evenodd" clip-rule="evenodd"></path>
                      </clipPath>
                    </defs>
                  </svg></div>
              </div>
            </div>
            <div>
              <ul role="list" class="text-base text-neutral-600 mt-16 lg:mt-0 lg:w-1/2 lg:min-w-[33rem] lg:pl-4 ">
                <li class="my-4 font-medium text-2xl">Motor insurance </li>
                <li class="my-4 font-medium text-2xl">Health Insurance </li>
                <li class="my-4 font-medium text-2xl">Fire insurance </li>
                <li class="my-4 font-medium text-2xl">Travel Insurance </li>
                <li class="my-4 font-medium text-2xl">Life insurance </li>
                <li class="my-4 font-medium text-2xl">Engineering insurance </li>
                <li class="my-4 font-medium text-2xl">Goods in transit insurance </li>
                <li class="my-4 font-medium text-2xl">Money insurance </li>
                <li class="my-4 font-medium text-2xl">Bonds </li>
                <li class="my-4 font-medium text-2xl">Property insurance </li>
                <li class="my-4 font-medium text-2xl">Business insurance </li>
                <li class="my-4 font-medium text-2xl">Burglary insurance </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="my-48 lg:pb-20 py-16">
    <div class="container mx-auto">
      <div class="text-center"><span class="text-sm bg-primary/10 text-primary rounded-full px-3 py-1">Partners</span>
        <h1 class="text-3xl/tight font-medium mt-3 mb-4">We are backed by</h1>
      </div>
      <div class="mt-14">
        <div class="grid md:grid-cols-4 grid-cols-2 gap-2 items-center aos-init" data-aos="fade-up">
          <div><img src="@/assets/img/partners/uap.png" alt="brand-logo" class="w-32 mx-auto"></div>
          <div><img src="@/assets/img/partners/jubilee.png" alt="brand-logo" class="w-32 mx-auto"></div>
          <div><img src="@/assets/img/partners/sanlam.png" alt="brand-logo" class="w-32 mx-auto"></div>
          <div><img src="@/assets/img/partners/jubilee.png" alt="brand-logo" class="w-32 mx-auto"></div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact">
    <div class="mx-auto max-w-7xl px-6 lg:px-8 mt-24 sm:mt-32 lg:mt-40">
      <div class="mx-auto max-w-2xl lg:max-w-none">
        <div class="grid grid-cols-1 gap-x-8 gap-y-24 lg:grid-cols-2">
          <div class="lg:order-last" style="opacity: 1; transform: none;">
            <form>
              <h2 class="font-display text-base font-semibold text-neutral-950">Work inquiries</h2>
              <div class="isolate mt-6 -space-y-px rounded-2xl bg-white/50">
                <div class="group relative z-0 transition-all focus-within:z-10"><input id=":S1:" autocomplete="name"
                    placeholder=" "
                    class="peer block w-full border border-neutral-300 bg-transparent px-6 pb-4 pt-12 text-base/6 text-neutral-950 ring-4 ring-transparent transition focus:border-neutral-950 focus:outline-none focus:ring-neutral-950/5 group-first:rounded-t-2xl group-last:rounded-b-2xl"
                    type="text" name="name"><label for=":S1:"
                    class="pointer-events-none absolute left-6 top-1/2 -mt-3 origin-left text-base/6 text-neutral-500 transition-all duration-200 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:font-semibold peer-focus:text-neutral-950 peer-[:not(:placeholder-shown)]:-translate-y-4 peer-[:not(:placeholder-shown)]:scale-75 peer-[:not(:placeholder-shown)]:font-semibold peer-[:not(:placeholder-shown)]:text-neutral-950">Name</label>
                </div>
                <div class="group relative z-0 transition-all focus-within:z-10"><input id=":S2:" autocomplete="email"
                    placeholder=" "
                    class="peer block w-full border border-neutral-300 bg-transparent px-6 pb-4 pt-12 text-base/6 text-neutral-950 ring-4 ring-transparent transition focus:border-neutral-950 focus:outline-none focus:ring-neutral-950/5 group-first:rounded-t-2xl group-last:rounded-b-2xl"
                    type="email" name="email"><label for=":S2:"
                    class="pointer-events-none absolute left-6 top-1/2 -mt-3 origin-left text-base/6 text-neutral-500 transition-all duration-200 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:font-semibold peer-focus:text-neutral-950 peer-[:not(:placeholder-shown)]:-translate-y-4 peer-[:not(:placeholder-shown)]:scale-75 peer-[:not(:placeholder-shown)]:font-semibold peer-[:not(:placeholder-shown)]:text-neutral-950">Email</label>
                </div>
                <div class="group relative z-0 transition-all focus-within:z-10"><input id=":S3:"
                    autocomplete="organization" placeholder=" "
                    class="peer block w-full border border-neutral-300 bg-transparent px-6 pb-4 pt-12 text-base/6 text-neutral-950 ring-4 ring-transparent transition focus:border-neutral-950 focus:outline-none focus:ring-neutral-950/5 group-first:rounded-t-2xl group-last:rounded-b-2xl"
                    type="text" name="company"><label for=":S3:"
                    class="pointer-events-none absolute left-6 top-1/2 -mt-3 origin-left text-base/6 text-neutral-500 transition-all duration-200 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:font-semibold peer-focus:text-neutral-950 peer-[:not(:placeholder-shown)]:-translate-y-4 peer-[:not(:placeholder-shown)]:scale-75 peer-[:not(:placeholder-shown)]:font-semibold peer-[:not(:placeholder-shown)]:text-neutral-950">Company</label>
                </div>
                <div class="group relative z-0 transition-all focus-within:z-10"><input id=":S4:" autocomplete="tel"
                    placeholder=" "
                    class="peer block w-full border border-neutral-300 bg-transparent px-6 pb-4 pt-12 text-base/6 text-neutral-950 ring-4 ring-transparent transition focus:border-neutral-950 focus:outline-none focus:ring-neutral-950/5 group-first:rounded-t-2xl group-last:rounded-b-2xl"
                    type="tel" name="phone"><label for=":S4:"
                    class="pointer-events-none absolute left-6 top-1/2 -mt-3 origin-left text-base/6 text-neutral-500 transition-all duration-200 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:font-semibold peer-focus:text-neutral-950 peer-[:not(:placeholder-shown)]:-translate-y-4 peer-[:not(:placeholder-shown)]:scale-75 peer-[:not(:placeholder-shown)]:font-semibold peer-[:not(:placeholder-shown)]:text-neutral-950">Phone</label>
                </div>
                <div class="group relative z-0 transition-all focus-within:z-10"><input id=":S5:" placeholder=" "
                    class="peer block w-full border border-neutral-300 bg-transparent px-6 pb-4 pt-12 text-base/6 text-neutral-950 ring-4 ring-transparent transition focus:border-neutral-950 focus:outline-none focus:ring-neutral-950/5 group-first:rounded-t-2xl group-last:rounded-b-2xl"
                    type="text" name="message"><label for=":S5:"
                    class="pointer-events-none absolute left-6 top-1/2 -mt-3 origin-left text-base/6 text-neutral-500 transition-all duration-200 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:font-semibold peer-focus:text-neutral-950 peer-[:not(:placeholder-shown)]:-translate-y-4 peer-[:not(:placeholder-shown)]:scale-75 peer-[:not(:placeholder-shown)]:font-semibold peer-[:not(:placeholder-shown)]:text-neutral-950">Message</label>
                </div>
              </div>
              <button
                class="mt-10 inline-flex rounded-full px-4 py-1.5 text-sm font-semibold transition bg-neutral-950 text-white hover:bg-neutral-800"
                type="submit"><span class="relative top-px">Let’s work together</span>
                </button>
            </form>
          </div>
          <div style="opacity: 1; transform: none;">
            <h2 class="font-display text-base font-semibold text-neutral-950">Our offices</h2>
            <p class="mt-6 text-base text-neutral-600">Prefer doing things in person? We don’t but we have to list our
              addresses here for legal reasons.</p>
            <ul role="list" class="mt-10 grid grid-cols-1 gap-8 sm:grid-cols-2">
              <li>
                <address class="text-sm not-italic text-neutral-600"><strong
                    class="text-neutral-950">Copenhagen</strong><br>1 Carlsberg Gate<br>1260, København, Denmark</address>
              </li>
              <li>
                <address class="text-sm not-italic text-neutral-600"><strong
                    class="text-neutral-950">Billund</strong><br>24 Lego Allé<br>7190, Billund, Denmark</address>
              </li>
            </ul>
            <div
              class="mt-16 pt-16 relative before:absolute after:absolute before:bg-neutral-950 after:bg-neutral-950/10 before:left-0 before:top-0 before:h-px before:w-6 after:left-8 after:right-0 after:top-0 after:h-px">
              <h2 class="font-display text-base font-semibold text-neutral-950">Email us</h2>
              <dl class="mt-6 grid grid-cols-1 gap-8 text-sm sm:grid-cols-2">
                <div>
                  <dt class="font-semibold text-neutral-950">Careers</dt>
                  <dd><a class="text-neutral-600 hover:text-neutral-950"
                      href="mailto:careers@studioagency.com">careers@studioagency.com</a></dd>
                </div>
                <div>
                  <dt class="font-semibold text-neutral-950">Press</dt>
                  <dd><a class="text-neutral-600 hover:text-neutral-950"
                      href="mailto:press@studioagency.com">press@studioagency.com</a></dd>
                </div>
              </dl>
            </div>
          <div
            class="mt-16 pt-16 relative before:absolute after:absolute before:bg-neutral-950 after:bg-neutral-950/10 before:left-0 before:top-0 before:h-px before:w-6 after:left-8 after:right-0 after:top-0 after:h-px">
            <h2 class="font-display text-base font-semibold text-neutral-950">Follow us</h2>
            <ul role="list" class="flex gap-x-10 text-neutral-950 mt-6">
              <li><a aria-label="Facebook" class="transition hover:text-neutral-700" href="https://facebook.com"><svg
                    viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 fill-current">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12Z">
                    </path>
                  </svg></a></li>
              <li><a aria-label="Instagram" class="transition hover:text-neutral-700" href="https://instagram.com"><svg
                    viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 fill-current">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465.668.25 1.272.644 1.772 1.153.509.5.902 1.104 1.153 1.772.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.903 4.903 0 0 1-1.153 1.772c-.5.509-1.104.902-1.772 1.153-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.903 4.903 0 0 1-1.772-1.153 4.902 4.902 0 0 1-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 0 1 1.153-1.772A4.902 4.902 0 0 1 5.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63Zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.096 3.096 0 0 0-.748-1.15 3.098 3.098 0 0 0-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058ZM12 6.865a5.135 5.135 0 1 1 0 10.27 5.135 5.135 0 0 1 0-10.27Zm0 1.802a3.333 3.333 0 1 0 0 6.666 3.333 3.333 0 0 0 0-6.666Zm5.338-3.205a1.2 1.2 0 1 1 0 2.4 1.2 1.2 0 0 1 0-2.4Z">
                    </path>
                  </svg></a></li>
              <li><a aria-label="Twitter" class="transition hover:text-neutral-700" href="https://twitter.com"><svg
                    viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 fill-current">
                    <path
                      d="M8.29 20.253c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0 0 22 5.922a8.19 8.19 0 0 1-2.357.646 4.118 4.118 0 0 0 1.804-2.27 8.224 8.224 0 0 1-2.605.996 4.107 4.107 0 0 0-6.993 3.743A11.65 11.65 0 0 1 3.392 4.75a4.106 4.106 0 0 0 1.27 5.477A4.072 4.072 0 0 1 2.8 9.715v.052a4.105 4.105 0 0 0 3.292 4.022 4.095 4.095 0 0 1-1.853.07 4.108 4.108 0 0 0 3.834 2.85A8.232 8.232 0 0 1 2 18.41a11.616 11.616 0 0 0 6.29 1.84">
                    </path>
                  </svg></a></li>
              <li><a aria-label="GitHub" class="transition hover:text-neutral-700" href="https://github.com"><svg
                    viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 fill-current">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0 1 12 6.844a9.59 9.59 0 0 1 2.504.337c1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.02 10.02 0 0 0 22 12.017C22 6.484 17.522 2 12 2Z">
                    </path>
                  </svg></a></li>
              <li><a aria-label="Dribbble" class="transition hover:text-neutral-700" href="https://dribbble.com"><svg
                    viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 fill-current">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2Zm6.605 4.61a8.502 8.502 0 0 1 1.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.42 25.42 0 0 0-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362ZM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.688 8.688 0 0 1 12 3.475Zm-3.633.803a53.889 53.889 0 0 1 3.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 0 1 4.729-5.975ZM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.523 8.523 0 0 1-2.191-5.705ZM12 20.547a8.482 8.482 0 0 1-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.32 35.32 0 0 1 1.823 6.475 8.402 8.402 0 0 1-3.341.684Zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 0 1-3.655 5.715Z">
                    </path>
                  </svg></a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</section></template>

<script>
import { onMounted, ref } from 'vue';

export default {
  setup() {
    const pageTitle = ref('Initial Page Title');
    const insuarance = ref([
      "Motor insurance ",
      "Health Insurance",
      "Fire insurance",
      "Travel Insurance ",
      "Life insurance ",
      "Engineering insurance",
      "Goods in transit insurance",
      "Money insurance",
      "Bonds",
      "Property insurance",
      "Business insurance",
      "Burglary insurance"
    ])

    // Function to change the page title
    const setPageTitle = (newTitle) => {
      pageTitle.value = newTitle;
      document.title = newTitle;
    };

    // Call setPageTitle when the component is mounted
    onMounted(() => {
      setPageTitle('AMVIC :: Your comfort is assured');
    });

    return {
      pageTitle,
      setPageTitle,
      insuarance
    };
  },
};
</script>

<style>.custom-section {
  background-image: url(../assets/img/bg/1.jpg);
}

.is-typed span.typed {
  colour: black;
}

.is-typed span.cursor {
  display: inline-block;
  width: 3px;
  background-color: #fff;
  animation: blink 1s infinite;
}

.is-typed span.underscore {
  display: inline-flex;
  width: 10px;
  height: 1px;
  align-items: flex-end;
  background-color: #fff;
  animation: blink 1s infinite;
}

.is-typed span.cursor.typing {
  animation: none;
}

@keyframes blink {
  49% {
    background-color: #fff;
  }

  50% {
    background-color: transparent;
  }

  99% {
    background-color: transparent;
  }
}</style>

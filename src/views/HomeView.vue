
<template>
  <section class="py-36 lg:py-64 w-full table relative bg-center bg-cover custom-section" id="home">
    <div class="absolute inset-0 bg-black opacity-80"></div>
    <div class="container relative mx-auto">
      <div class="grid grid-cols-1 mt-12">
        <h4 class="text-white lg:text-5xl text-4xl lg:leading-normal leading-normal font-medium mb-7 position-relative">
          Welcome to AMVIC Insuarance Brokers<br>Your Partner for
            <span class="text-yellow-200 font-bold"><vue-writer :array="insuarance" :typeSpeed="100"></vue-writer></span>
        </h4>
        <p class="text-white mb-0 max-w-2xl text-lg">Welcome to AMVIC Insurance Brokers, where your aspirations are our
          utmost priority. As Tanzania's most recent independent insurance brokerage company, we take pride in offering a
          diverse array of insurance products to cater to your unique needs with unparalleled professionalism
        </p>
        <div class="relative mt-10"><a
            class="p-3 bg-orange-600 hover:bg-orange-700 border-orange-600 hover:border-orange-700 text-white rounded-md">Get
            Started</a></div>
      </div>
    </div>
  </section>

  <section class="py-48">
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
                  <path d="M3 6C26.9011 3.73613 95.1626 0.566711 177 6" stroke="#DAED1A" stroke-width="6"
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
            <img src="assets/images/about/person.png" class="mx-auto" alt="">
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

<section class="bg-yellow-100">
  <div class="max-w-screen-xl mx-auto p-4">
				<div class="hidden md:block text-[55px] leading-[65px] font-medium mb-[100px]">
					<div class="">We offer personalized and comprehensive insurance solutions to safeguard what matters most in your life.</div>
					<div class="">Digital Agency Services</div>
				</div>
				<a href="#" class="group flex items-center justify-between">
					<div class="w-[300px] hidden xl:flex">
						<div class="group/img relative hway">
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-[#FF6B00] transition-all duration-[.5s]"></div>
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-white transition-all duration-[.5s] group-[.hway-active]/img:delay-[.25s]"></div>
							<img class="origin-left scale-x-0 group-[.hway-active]/img:scale-x-100 transition-all duration-[.5s] group-[.hway-active]/img:delay-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/expert-digital/01Placeholder.png" alt="">
						</div>
					</div>
					<div class="flex-1 relative">
						<div class="group-hover:text-[#FF6B00] text-[22px] leading-[22px] font-bold mb-[20px]">Personal Insurance</div>
						<div class="text-[#454545]">Welcome to our digital agency We specialize in helping business most</div>
						<div class="text-[#454545]">like yours succeed online. From website design and development to</div>
						<div class="text-[#454545]">digital marketing agency.</div>
					</div>
					<div class="">
						<img class="rotate-[-45deg] group-hover:rotate-0 group-hover:brightness-100 brightness-0 transition-all duration-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/creative-portfolio/Arrow-30x30.svg" alt="">
					</div>
				</a>
				<div class="xl:ps-[300px] my-[50px]">
					<div class="border-t border-t-[1px] border-t-[#C1C1C1]"></div>
				</div>
				<a href="#" class="group flex items-center justify-between">
					<div class="w-[300px] hidden xl:flex">
						<div class="group/img relative hway">
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-[#FF6B00] transition-all duration-[.5s]"></div>
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-white transition-all duration-[.5s] group-[.hway-active]/img:delay-[.25s]"></div>
							<img class="origin-left scale-x-0 group-[.hway-active]/img:scale-x-100 transition-all duration-[.5s] group-[.hway-active]/img:delay-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/expert-digital/02Placeholder.png" alt="">
						</div>
					</div>
					<div class="flex-1 relative">
						<div class="group-hover:text-[#FF6B00] text-[22px] leading-[22px] font-bold mb-[20px]">Web Development</div>
						<div class="text-[#454545]">Welcome to our digital agency We specialize in helping business most</div>
						<div class="text-[#454545]">like yours succeed online. From website design and development to</div>
						<div class="text-[#454545]">digital marketing agency.</div>
					</div>
					<div class="">
						<img class="rotate-[-45deg] group-hover:rotate-0 group-hover:brightness-100 brightness-0 transition-all duration-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/creative-portfolio/Arrow-30x30.svg" alt="">
					</div>
				</a>
				<div class="xl:ps-[300px] my-[50px]">
					<div class="border-t border-t-[1px] border-t-[#C1C1C1]"></div>
				</div>
				<a href="#" class="group flex items-center justify-between">
					<div class="w-[300px] hidden xl:flex">
						<div class="group/img relative hway">
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-[#FF6B00] transition-all duration-[.5s]"></div>
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-white transition-all duration-[.5s] group-[.hway-active]/img:delay-[.25s]"></div>
							<img class="origin-left scale-x-0 group-[.hway-active]/img:scale-x-100 transition-all duration-[.5s] group-[.hway-active]/img:delay-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/expert-digital/03Placeholder.png" alt="">
						</div>
					</div>
					<div class="flex-1 relative">
						<div class="group-hover:text-[#FF6B00] text-[22px] leading-[22px] font-bold mb-[20px]">Digital Services</div>
						<div class="text-[#454545]">Welcome to our digital agency We specialize in helping business most</div>
						<div class="text-[#454545]">like yours succeed online. From website design and development to</div>
						<div class="text-[#454545]">digital marketing agency.</div>
					</div>
					<div class="">
						<img class="rotate-[-45deg] group-hover:rotate-0 group-hover:brightness-100 brightness-0 transition-all duration-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/creative-portfolio/Arrow-30x30.svg" alt="">
					</div>
				</a>
				<div class="xl:ps-[300px] my-[50px]">
					<div class="border-t border-t-[1px] border-t-[#C1C1C1]"></div>
				</div>
				<a href="#" class="group flex items-center justify-between">
					<div class="w-[300px] hidden xl:flex">
						<div class="group/img relative hway">
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-[#FF6B00] transition-all duration-[.5s]"></div>
							<div class="absolute h-full w-0 group-[.hway-active]/img:w-full bg-white transition-all duration-[.5s] group-[.hway-active]/img:delay-[.25s]"></div>
							<img class="origin-left scale-x-0 group-[.hway-active]/img:scale-x-100 transition-all duration-[.5s] group-[.hway-active]/img:delay-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/expert-digital/04Placeholder.png" alt="">
						</div>
					</div>
					<div class="flex-1 relative">
						<div class="group-hover:text-[#FF6B00] text-[22px] leading-[22px] font-bold mb-[20px]">Digital Product Design</div>
						<div class="text-[#454545]">Welcome to our digital agency We specialize in helping business most</div>
						<div class="text-[#454545]">like yours succeed online. From website design and development to</div>
						<div class="text-[#454545]">digital marketing agency.</div>
					</div>
					<div class="">
						<img class="rotate-[-45deg] group-hover:rotate-0 group-hover:brightness-100 brightness-0 transition-all duration-[.5s]" src="https://raw.githubusercontent.com/uiaextend/jvixan/main/creative-portfolio/Arrow-30x30.svg" alt="">
					</div>
				</a>
			</div>
</section>

</template>

<script>
import { onMounted, ref } from 'vue';

export default {
  setup() {
    const pageTitle = ref('Initial Page Title');
    const insuarance = ref(["Motor vehicles", "Plant All Risk", "Contractors All Risk","Burglary/Theft cove","All Risk Insurance","Fire insurance","Marine Hull & Machinery","Fidelity guarantee"])

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
}</style>
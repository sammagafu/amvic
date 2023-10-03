
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

  <section class="py-48" id="about">
    <div class="mx-auto px-4 sm:px-6 lg:max-w-7xl lg:px-8">
      <div class="grid grid-cols-1 gap-5 xl:gap-10 lg:grid-cols-3 items-center">
        <div class="col-span-1">
          <div class=" mb-10">
            <h4 class="text-porange-700 text-xl font-medium capitalize mb-2"
              v-wow="{ 'animation-name': 'fadeInUp', 'animation-duration': '1s' }">
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
        <div class="col-span-1 animate-bounce">
          <div>
            <img src="@/assets/img/bg/team.jpg" class="mx-auto" alt="">
          </div>
        </div>
        <div class="col-span-1">
          <ul class="divide-y divide-[#177370] divide-opacity-10">
            <li class="flex space-x-4 py-8">
              <div
                class="w-[60px] h-[60px] rounded-full shrink-0 inline-flex items-center justify-center bg-porange-700 bg-opacity-10">
                <img src="@/assets/img/icons/target.svg" alt="">
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
                <img src="@/assets/img/icons/mission.svg" alt="">
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

  <section class="py-36 bg-yellow-50" id="whychooseuse">
    <div class="container mx-auto">
      <div class="text-center max-w-xl mx-auto">
        <!-- <h6 class="font-normal uppercase mb-2">Why <span class="font-semibold">Choosing Us</span></h6> -->
        <h2 class="text-3xl font-semibold mb-3 uppercase">why choosing us</h2>
        <p class="text-base font-normal text-gray-500">Our personal insurance offerings are designed to provide you and
          your loved ones with the protection and peace of mind you deserve.</p>
      </div>

      <div class="mt-20">
        <div class="grid lg:grid-cols-3 grid-cols-1 gap-10">
          <div>
            <div class="relative">
              <div class="text-center">
                <span
                  class="inline-flex relative z-0 bg-blue-500/10 dark:bg-blue-100/5 h-32 w-32 items-center justify-center"
                  style="border-radius: 28% 72% 50% 50%/26% 20% 80% 74%;">
                  <img src="@/assets/img/icons/rating-stars.svg" alt="" class="p-6">
                </span>
                <h5 class="text-xl font-semibold mb-3 mt-5">Expertise and Experience</h5>
                <p class="text-base font-normal text-gray-500">Benefit from our industry expertise, gained through years
                  of experience in insurance, construction, and banking sectors.</p>
              </div>
            </div>
          </div><!-- end grid col -->

          <div>
            <div class="relative">
              <div class="text-center">
                <span
                  class="inline-flex relative z-0 bg-emerald-500/10 dark:bg-emerald-100/5 h-32 w-32 items-center justify-center"
                  style="border-radius: 28% 72% 50% 50%/26% 20% 80% 74%;">
                  <img src="@/assets/img/icons/unique.svg" alt="" class="p-6">
                </span>
                <h5 class="text-xl font-semibold mb-3 mt-5">Unique products</h5>
                <p class="text-gray-600 dark:text-gray-400">We tailor insurance solutions to your unique needs, whether
                  it's personal, commercial, or industry-specific coverage.</p>
              </div>
            </div>
          </div><!-- end grid col -->

          <div>
            <div class="text-center">
              <span
                class="inline-flex relative z-0 bg-amber-500/10 dark:bg-amber-100/5 h-32 w-32 items-center justify-center"
                style="border-radius: 28% 72% 50% 50%/26% 20% 80% 74%;">
                <img src="@/assets/img/icons/group.svg" alt="" class="p-6">
              </span>
              <h5 class="text-xl font-semibold mb-3 mt-5">Customer-Centric</h5>
              <p class="text-gray-600 dark:text-gray-400">Our commitment to excellent customer care ensures you're not
                just a policyholder but a valued partner in securing your future.</p>
            </div>
          </div><!-- end grid col -->
        </div><!-- Grid End -->
      </div>
    </div><!-- Container End -->
  </section>

  <section class="my-48" id="services">
    <div class="max-w-screen-xl mx-auto my-24">
      <div class="hidden md:block text-2xl font-medium mb-[100px]">
        <div class="text-3xl font-semibold mb-3 uppercase">Our Services</div>
        <div class="">Whether it’s protecting your dream home, your cherished possessions, or planning for retirement, our
          personalized approach ensures that your unique priorities are covered with care.</div>
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
        <div class="grid md:grid-cols-9 grid-cols-2 gap-2 items-center aos-init" data-aos="fade-up">
          <div><img src="@/assets/img/partners/jubilee.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/icea.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/uap.png" alt="brand-logo" class="w-32 mx-auto grayscale hover:filter-none">
          </div>
          <div><img src="@/assets/img/partners/sanlam.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/mayfair.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/phoenix.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/heritage.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/assembly.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
          <div><img src="@/assets/img/partners/strategis.png" alt="brand-logo"
              class="w-32 mx-auto grayscale hover:filter-none"></div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact pt-8" id="contact">
    <div class="conatiner">
      <div class="bg-gray-300 lg:h-2/3">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3961.949353221044!2d39.24173377499508!3d-6.776019193220909!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x185c4d03434200b5%3A0x5f37c9979c9022e9!2sMwanga%20Tower!5e0!3m2!1sen!2stz!4v1696234580482!5m2!1sen!2stz"
          width="100%" height="600" style="border:0;" allowfullscreen="" loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </div>
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
            <p class="mt-6 text-base text-neutral-600">For your convenience, you can also reach us by filling out our
              online contact form on our website.

            </p>
            <ul role="list" class="mt-10 grid grid-cols-1 gap-8 sm:grid-cols-2">
              <li>
                <address class="text-sm not-italic text-neutral-600"><strong
                    class="text-neutral-950">Tanzania</strong><br>21 Floor Mwanga Tower <br> New Bagaomo Road,
                  Makubusho<br>Dar es salaam </address>
              </li>
            </ul>
            <div
              class="mt-16 pt-16 relative before:absolute after:absolute before:bg-neutral-950 after:bg-neutral-950/10 before:left-0 before:top-0 before:h-px before:w-6 after:left-8 after:right-0 after:top-0 after:h-px">
              <h2 class="font-display text-base font-semibold text-neutral-950">Email us</h2>
              <dl class="mt-6 grid grid-cols-1 gap-8 text-sm sm:grid-cols-2">
                <div>
                  <dt class="font-semibold text-neutral-950">information</dt>
                  <dd><a class="text-neutral-600 hover:text-neutral-950"
                      href="mailto:careers@studioagency.com">info@amvic.co.tz</a></dd>
                </div>
              </dl>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

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

<style>
.custom-section {
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

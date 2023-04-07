<script setup>
import {ref} from "vue";
import 'vue3-carousel/dist/carousel.css'
import {Carousel, Slide, Pagination, Navigation} from 'vue3-carousel'


const settings = ref({
  itemsToShow: 4,
  snapAlign: 'center',
  // breakpoints: {
  //   // 700px and up
  //   700: {
  //     itemsToShow: 4,
  //     snapAlign: 'center',
  //   },
  //   // 1024 and up
  //   1024: {
  //     itemsToShow: 3,
  //     snapAlign: 'start',
  //   },
  // },
})
</script>

<template>
  <div class="mt-[3rem] container mx-auto">
    <div class="grid grid-cols-2  ">
      <div class="col-span-1">
        <img src="https://wp.dreamitsolution.net/itsolve/wp-content/uploads/2020/06/about-1.png" alt="">
      </div>
      <div class="col-span-1">
        <div>
          <h2 class="text-[#1e1666] text-[2.375rem] font-[800]  leading-[2.813rem]">Exclusive Technology For
            Provide IT <span class="text-[#2513d1]">Solution</span></h2>
          <div class="bg-[#2513d1] mt-[0.5rem] w-[10%] h-[4px]">
          </div>
          <p class="text-[#6a7c92] mt-[2rem] text-[0.938rem] leading-[1.75rem]">
            IT-Solve is the partner of choice for many of the world’s leading and solving enterprises, SMEs and
            technology
            challengers. We help businesses elevate their value through custom software development.
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. At beatae, consectetur culpa earum error fugiat
            iure magnam non praesentium quae?
          </p>
        </div>
        <div class="mt-[2rem]">
          <div>
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
          <div class="my-[1rem]">
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
          <div>
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
        </div>

        <button class="button mt-[1rem]">
          Read More
        </button>
      </div>
    </div>
  </div>

  <div class="bg-[#f4f7fc] my-[3rem]">
    <div class="container  mx-auto ">
      <div class=" py-[3rem]">
        <div class="text-center text-[#2513d1] font-[600] leading-[20px]">
          OUR SERVICES
        </div>
        <div class="text-center line my-[1rem] text-[#1e1666] text-[38px] leading-[2.8rem]">
          We Provide Best IT Solution
          <!--         <div class="w-[52px] h-[4px] border-4 border-[transparent]">-->
          <!--         </div>-->
        </div>

        <div class="flex justify-center">
          <div class="bg-[#2513d1] mb-[1rem] w-[10%] h-[4px]">
          </div>
        </div>
        <div class="text-center text-[#6a7c92]    text-[0.938rem] leading-[1.75rem]">
          <div class="px-[20rem]">
            Business solution company sit our any how site used the our company any site us it-solve theme is very
            professional theme business & corporate, finance, advisor, solution, company and all project used, there are
            all
            kinds of websites here.
          </div>
        </div>
      </div>


      <div class="grid pb-[3rem] grid-cols-3  gap-5">
        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img src="https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service4.png"
                     alt="">
                <div class="absolute top-[20%] right-[40%]">
                  <i class="fa-solid fa-globe text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>


        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img src="	https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service2.png"
                     alt="">
                <div class="absolute top-[20%] right-[35%]">
                  <i class="fas fa-sitemap text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>


        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img
                    src="		https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service3.png"
                    alt="">
                <div class="absolute top-[20%] right-[40%]">
                  <i class="fas fa-shield-alt text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>


        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img
                    src="			https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service1.png"
                    alt="">
                <div class="absolute top-[20%] right-[40%]">
                  <i class="fas fa-chart-pie text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>


        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img src="	https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service5.png"
                     alt="">
                <div class="absolute top-[20%] right-[40%]">
                  <i class="fas fa-comment text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>


        <div class="bg-[#FFFFFF] col-span-1 ">
          <div class="mx-[20px] my-[2rem]">
            <div class="flex justify-center ">
              <div class="w-[120px] h-[120px] relative">
                <img src="	https://wp.dreamitsolution.net/itsolve/wp-content/themes/itsolve/assets/images/service6.png"
                     alt="">
                <div class="absolute top-[20%] right-[40%]">
                  <i class="fas fa-calendar text-[#FFFFFF] text-5xl"></i>
                </div>
              </div>

            </div>
            <div class="text-[#1e1666]  text-[24px] font-[700] text-center leading-[31px] ">
              Interface Design
            </div>
            <div class="text-[#6a7c92] my-[1rem] text-center font-[15px] leading-[28px] ">
              IT Solve professional business theme for your company, support quality all time, any help please late me
              know.
            </div>
            <div class="text-center cursor-pointer">
              <a class=" text-indigo-500 inline-flex items-center">Discover Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>

  </div>

  <div class="container">


    <section class="text-gray-600 body-font">
      <div class="container px-5  mx-auto">
        <div class="text-center mb-[3rem]">
          <div class="text-center line my-[1rem] text-[#1e1666] text-[38px] leading-[2.8rem]">
            How IT Work
          </div>
          <div class="text-center text-[#6a7c92]    text-[0.938rem] leading-[1.75rem]">
            <div class="px-[20rem]">
              Business solution company sit our any how site used the our company any site us it-solve theme is very
              professional theme business & corporate, finance, advisor, solution, company and all project used, there
              are
              all
              kinds of websites here.
            </div>
          </div>

          <div class="flex justify-center items-center">
            <div class="bg-[#2513d1] mt-[1rem]  w-[5%] h-[4px]">
            </div>
          </div>

        </div>
        <div class="flex flex-wrap     md:space-y-0 space-y-6 ">
          <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <div
                class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                   class="w-10 h-10" viewBox="0 0 24 24">
                <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Shooting Stars</h2>
              <p class="leading-relaxed text-base">Blue bottle crucifix vinyl post-ironic four dollar toast vegan
                taxidermy. Gastropub indxgo juice poutine, ramps microdosing banh mi pug VHS try-hard.</p>
              <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
          <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <div
                class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                   class="w-10 h-10" viewBox="0 0 24 24">
                <circle cx="6" cy="6" r="3"></circle>
                <circle cx="6" cy="18" r="3"></circle>
                <path d="M20 4L8.12 15.88M14.47 14.48L20 20M8.12 8.12L12 12"></path>
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">The Catalyzer</h2>
              <p class="leading-relaxed text-base">Blue bottle crucifix vinyl post-ironic four dollar toast vegan
                taxidermy. Gastropub indxgo juice poutine, ramps microdosing banh mi pug VHS try-hard.</p>
              <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
          <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <div
                class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                   class="w-10 h-10" viewBox="0 0 24 24">
                <path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"></path>
                <circle cx="12" cy="7" r="4"></circle>
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Neptune</h2>
              <p class="leading-relaxed text-base">Blue bottle crucifix vinyl post-ironic four dollar toast vegan
                taxidermy. Gastropub indxgo juice poutine, ramps microdosing banh mi pug VHS try-hard.</p>
              <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                     class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                  <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

  </div>


  <section class="p-6 dark:bg-gray-800 dark:text-gray-100">
    <div class="container mx-auto grid justify-center grid-cols-2 text-center lg:grid-cols-3">
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">50+</p>
        <p class="text-sm sm:text-base text-[#4b5563]">Clients</p>
      </div>
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">89K</p>
        <p class="text-sm sm:text-base text-[#4b5563]">Followers on social media</p>
      </div>
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">3</p>
        <p class="text-sm sm:text-base text-[#4b5563]">Published books</p>
      </div>
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">8</p>
        <p class="text-sm sm:text-base text-[#4b5563]">TED talks</p>
      </div>
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">22</p>
        <p class="text-sm sm:text-base text-[#4b5563]">Years of experience</p>
      </div>
      <div class="flex flex-col justify-start m-2 lg:m-6">
        <p class="text-4xl font-bold leading-none lg:text-6xl text-[#4b5563]">10+</p>
        <p class="text-sm sm:text-base text-[#4b5563]">Workshops</p>
      </div>
    </div>
  </section>


  <br>
  <br>

  <div class="container mx-auto my-[3rem]">
    <div class="grid grid-cols-2 gap-5">
      <div>
        <img src="https://wp.dreamitsolution.net/itsolve/wp-content/uploads/2020/06/hero-img1.png" alt="">
      </div>

      <div>
        <div class="text-[#dddddd] text-[80px] font-[700] leading-[104px]">
          01
        </div>
        <div class="text-[#1e1666] text-[38px] font-[800] leading-[2.8rem] ">
          We Consultant To Get
          Our Business Plan
        </div>

        <div class="bg-[#2513d1] mt-[1rem]  w-[10%] h-[4px]">
        </div>

        <div class="text-[#6a7c92] my-[1rem] font-[700] leading-[28px]">
          Business solution company sit our any how site used the our company any site us it-solve theme is very
          professional theme business & corporate, finance, advisor, solution, company and all project used.
        </div>

        <div class="text-[#6a7c92] text-[15px] leading-[28px]">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores atque aut, blanditiis ea est libero nihil
          perspiciatis praesentium provident vel!
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti distinctio enim harum iure molestias
          officia repellendus totam vitae voluptates voluptatibus.
        </div>

        <button class="button mt-[1rem]">
          Read More
        </button>
      </div>
    </div>

    <br>
    <br>


    <div class="grid grid-cols-2 my-[6rem] gap-5">
      <div>
        <div class="text-[#dddddd] text-[80px] font-[700] leading-[6.5rem]">
          02
        </div>
        <div class="text-[#1e1666] text-[38px] font-[800] leading-[2.813rem] ">
          Partner Company Business
          And Me Success Fully
        </div>
        <div class="bg-[#2513d1] mt-[1rem]  w-[10%] h-[4px]">
        </div>
        <div class="text-[#6a7c92] my-[1rem] font-[700] leading-[1.75rem]">
          Business solution company sit our any how site used the our company any site us it-solve theme is very
          professional theme business & corporate, finance, advisor, solution, company and all project used.
        </div>

        <div class="mt-[2rem]">
          <div>
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
          <div class="my-[1rem]">
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
          <div>
            <i class="fa-solid fa-check text-[green] text-lg mr-2"></i> <span
              class="text-[#6a7c92]  text-[0.938rem] leading-[1.75rem]">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, blanditiis?</span>
          </div>
        </div>
      </div>
      <div>
        <img src="https://wp.dreamitsolution.net/itsolve/wp-content/uploads/2020/06/hero-img1.png" alt="">
      </div>
    </div>


    <div class="grid grid-cols-2 gap-5">
      <div>
        <img src="https://wp.dreamitsolution.net/itsolve/wp-content/uploads/2020/06/hero-img1.png" alt="">
      </div>

      <div>
        <div class="text-[#dddddd] text-[80px] font-[700] leading-[6.5rem]">
          03
        </div>
        <div class="text-[#1e1666] text-[38px] font-[800] leading-[2.813rem] ">
          IT Solution For Your
          Business Is Best Theme
        </div>
        <div class="bg-[#2513d1] mt-[1rem]  w-[10%] h-[4px]">
        </div>
        <div class="text-[#6a7c92] my-[1rem] font-[700] leading-[1.75rem]">
          Business solution company sit our any how site used the our company any site us it-solve theme is very
          professional theme business & corporate, finance, advisor, solution, company and all project used.
        </div>

        <div>
          <div>
            <div>
              <i class="fa-solid text-xl fa-circle-check text-green-500 mr-2"></i> <span
                class="text-[#1e1666] text-[1.125rem] leading-[1.75rem] font-[700]">Business & Analysis</span>
            </div>
            <div class="text-[#6a7c92] text-[0.938rem] leading-[1.75rem]">
              My project is best under-full is very professional site and used very easy customization this site.
            </div>
          </div>

          <div class="mt-[1rem]">
            <div>
              <i class="fa-solid text-xl fa-circle-check text-green-500 mr-2"></i> <span
                class="text-[#1e1666] text-[1.125rem] leading-[1.75rem] font-[700]">IT Solutions & Analysis</span>
            </div>
            <div class="text-[#6a7c92] text-[0.938rem] leading-[1.75rem]">
              This project is best under-full is very professional site and used very easy customization
            </div>
          </div>


        </div>

      </div>
    </div>


  </div>


  <div class="bg-[#f4f7fc] my-[3rem]">
    <div class="container  mx-auto ">
      <div class=" py-[2.5rem]">
        <div class="text-center text-[#2513d1] font-[600] leading-[20px]">
          TESTIMONIAL
        </div>
        <div class="text-center line my-[1rem] text-[#1e1666] text-[38px] leading-[2.813rem]">
          What Says
          Our Happy Clients
          <!--         <div class="w-[52px] h-[4px] border-4 border-[transparent]">-->
          <!--         </div>-->
        </div>

        <div class="flex justify-center">
          <div class="bg-[#2513d1] mb-[1rem] w-[5%] h-[4px]">
          </div>
        </div>
        <div class="text-center text-[#6a7c92]    text-[0.938rem] leading-[1.75rem]">
          <div class="px-[20rem]">
            Business solution company sit our any how site used the our company any site us it-solve theme is very
            professional theme business & corporate, finance, advisor, solution, company and all project easy for used,
          </div>
        </div>
      </div>
      <Carousel :settings="settings" :breakpoints="breakpoints">
        <Slide v-for="slide in 8" :key="slide">
          <div class="carousel__item">
            <div class="bg-white shadow-xl shadow-md rounded-lg  p-6 max-w-sm">
              <img class="w-20 z-[9999] h-20 object-cover rounded-full mx-auto -mt-10"
                   src="https://i.pinimg.com/236x/9c/e5/9f/9ce59fe16be122466feacf547099eb25.jpg" alt="Avatar"/>
              <h3 class="mt-2 text-gray-900 text-lg font-medium text-center">John Doe</h3>
              <p class="mt-2 text-gray-600 text-center">"Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Aliquam euismod lacus sed enim porta dignissim. Nullam congue et lacus id bibendum."</p>
            </div>
          </div>
        </Slide>
      </Carousel>
      <br>
    </div>
  </div>

  <div class="container mx-auto">
    <div class="grid grid-cols-2 gap-5">
      <div>
        <div class=" line my-[1rem] text-[#1e1666] text-[2.375rem] leading-[2.813rem]">
          How May We Help You!
        </div>
        <div class="bg-[#2513d1] mb-[1rem] w-[5%] h-[4px]">
        </div>
        <div class=" text-[#6a7c92]    text-[0.938rem] leading-[1.75rem]">
          <div>
            Business solution company sit our any how site used the our company any site us it-solve theme is very
            professional theme business & corporate, finance, advisor, solution, company and all project easy for used,
          </div>
        </div>


        <section class="text-gray-600 body-font mt-5">
          <div class="flex gap-5 items-center">
            <div class="relative flex-grow w-full">
              <input placeholder="name" type="text" id="full-name" name="full-name"
                     class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <div class="relative flex-grow w-full">
              <input placeholder="Email" type="text" id="full-name" name="full-name"
                     class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
          </div>
          <div class="flex gap-5 items-center mt-5">
            <div class="relative flex-grow w-full">
              <input placeholder="Phone" type="text" id="full-name" name="full-name"
                     class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <div class="relative flex-grow w-full">
              <input placeholder="Subject" type="text" id="full-name" name="full-name"
                     class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>

          </div>

          <div class="relative flex-grow w-full mt-5">
              <textarea
                  class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700  leading-8 transition-colors duration-200 ease-in-out"
                  name="" id="" cols="5" rows="5">
              </textarea>
          </div>

          <button
              class="text-white bg-indigo-500 border-0 py-2 mt-5 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg">
            Send Message
          </button>
        </section>
      </div>
      <div>
        <img src="https://wp.dreamitsolution.net/itsolve/wp-content/uploads/2020/06/consultform.png" alt="">
      </div>
    </div>
  </div>


  <div class="my-[5rem] bg-[#2513d1]">
    <div class="container mx-auto ">
      <div class="grid grid-cols-2 py-[3rem]">
        <p class="text-[#ffffff] text-[38px] font-[800] leading-[2.8rem] ">
          Great Things In Business Are Never
          Done By One Person.
        </p>

        <div class="flex justify-end items-center">
          <button class="button ">
            Read More
          </button>
        </div>
      </div>
    </div>
  </div>


  <div class="container">
    <div class="">
      <div class="text-center text-[#2513d1] font-[600] leading-[20px]">
        TESTIMONIAL
      </div>
      <div class="text-center line my-[1rem] text-[#1e1666] text-[2.375rem] leading-[2.8rem]">
        See Your Latest
        Blog Post
      </div>

      <div class="flex justify-center">
        <div class="bg-[#2513d1] mb-[1rem] w-[5%] h-[4px]">
        </div>
      </div>
      <div class="text-center text-[#6a7c92]    text-[0.938rem] leading-[1.75rem]">
        <div class="px-[20rem]">
          Business solution company sit our any how site used the our company any site us it-solve theme is very
          professional theme business & corporate, finance, advisor, solution, company and all project easy for used,
        </div>
      </div>
    </div>

    <div>
      <section class="py-6 sm:py-12  text-gray-100">
        <div class="container p-6 mx-auto space-y-8">
          <div class="grid grid-cols-1 gap-x-4 gap-y-8 md:grid-cols-2 lg:grid-cols-4">
            <article class="flex rounded-lg flex-col overflow-hidden bg-white shadow-xl">
              <a rel="noopener noreferrer" href="#" class="relative"
                 aria-label="Te nulla oportere reprimique his dolorum">
                <img alt="" class="object-cover w-full h-52 bg-gray-500"
                     src="https://i.pinimg.com/236x/42/dc/be/42dcbe16e949e7fe3b66c298e05a9535.jpg">
                <button
                    class="bg-[#2513d1] top-[8px] left-[8px] absolute py-1 px-2 rounded-[5px] text-[#FFFFFF] text-[12px] font-[500] leading-[19px]">
                  Marketing
                </button>
              </a>
              <div class="flex flex-col flex-1 p-6">
                <a rel="noopener noreferrer" href="#" aria-label="Te nulla oportere reprimique his dolorum"></a>
                <h3 class="flex-1 py-1 text-lg font-semibold leading-snug text-[#1e166b]">Te nulla oportere reprimique
                  his dolorum</h3>
                <p class="text-[#6a7c92] text-[15px] leading-[28px]">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, ipsa.
                </p>

                <div class="flex flex-wrap justify-between pt-3 space-x-2 text-xs text-[#6a7c92]">
                  <span>June 1, 2020</span>
                  <span>2.1K views</span>
                </div>
              </div>
            </article>

            <article class="flex rounded-lg flex-col overflow-hidden bg-white shadow-xl">
              <a rel="noopener noreferrer" href="#" class="relative"
                 aria-label="Te nulla oportere reprimique his dolorum">
                <img alt="" class="object-cover w-full h-52 bg-gray-500"
                     src="https://i.pinimg.com/236x/42/dc/be/42dcbe16e949e7fe3b66c298e05a9535.jpg">
                <button
                    class="bg-[#2513d1] top-[8px] left-[8px] absolute py-1 px-2 rounded-[5px] text-[#FFFFFF] text-[12px] font-[500] leading-[19px]">
                  Marketing
                </button>
              </a>
              <div class="flex flex-col flex-1 p-6">
                <a rel="noopener noreferrer" href="#" aria-label="Te nulla oportere reprimique his dolorum"></a>
                <h3 class="flex-1 py-1 text-lg font-semibold leading-snug text-[#1e166b]">Te nulla oportere reprimique
                  his dolorum</h3>
                <p class="text-[#6a7c92] text-[15px] leading-[28px]">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, ipsa.
                </p>

                <div class="flex flex-wrap justify-between pt-3 space-x-2 text-xs text-[#6a7c92]">
                  <span>June 1, 2020</span>
                  <span>2.1K views</span>
                </div>
              </div>
            </article>

            <article class="flex rounded-lg flex-col overflow-hidden bg-white shadow-xl">
              <a rel="noopener noreferrer" href="#" class="relative"
                 aria-label="Te nulla oportere reprimique his dolorum">
                <img alt="" class="object-cover w-full h-52 bg-gray-500"
                     src="https://i.pinimg.com/236x/42/dc/be/42dcbe16e949e7fe3b66c298e05a9535.jpg">
                <button
                    class="bg-[#2513d1] top-[8px] left-[8px] absolute py-1 px-2 rounded-[5px] text-[#FFFFFF] text-[12px] font-[500] leading-[19px]">
                  Marketing
                </button>
              </a>
              <div class="flex flex-col flex-1 p-6">
                <a rel="noopener noreferrer" href="#" aria-label="Te nulla oportere reprimique his dolorum"></a>
                <h3 class="flex-1 py-1 text-lg font-semibold leading-snug text-[#1e166b]">Te nulla oportere reprimique
                  his dolorum</h3>
                <p class="text-[#6a7c92] text-[15px] leading-[28px]">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, ipsa.
                </p>

                <div class="flex flex-wrap justify-between pt-3 space-x-2 text-xs text-[#6a7c92]">
                  <span>June 1, 2020</span>
                  <span>2.1K views</span>
                </div>
              </div>
            </article>

            <article class="flex rounded-lg flex-col overflow-hidden bg-white shadow-xl">
              <a rel="noopener noreferrer" href="#" class="relative"
                 aria-label="Te nulla oportere reprimique his dolorum">
                <img alt="" class="object-cover w-full h-52 bg-gray-500"
                     src="https://i.pinimg.com/236x/42/dc/be/42dcbe16e949e7fe3b66c298e05a9535.jpg">
                <button
                    class="bg-[#2513d1] top-[8px] left-[8px] absolute py-1 px-2 rounded-[5px] text-[#FFFFFF] text-[12px] font-[500] leading-[19px]">
                  Marketing
                </button>
              </a>
              <div class="flex flex-col flex-1 p-6">
                <a rel="noopener noreferrer" href="#" aria-label="Te nulla oportere reprimique his dolorum"></a>
                <h3 class="flex-1 py-1 text-lg font-semibold leading-snug text-[#1e166b]">Te nulla oportere reprimique
                  his dolorum</h3>
                <p class="text-[#6a7c92] text-[15px] leading-[28px]">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, ipsa.
                </p>

                <div class="flex flex-wrap justify-between pt-3 space-x-2 text-xs text-[#6a7c92]">
                  <span>June 1, 2020</span>
                  <span>2.1K views</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </section>
    </div>
  </div>


  <footer class="px-4 divide-y bg-[#1e1666] text-gray-100">
    <div class="container flex flex-col justify-between py-10 mx-auto space-y-8 lg:flex-row lg:space-y-0">
      <div class="lg:w-1/3">
        <a rel="noopener noreferrer" href="#" class="flex justify-center space-x-3 lg:justify-start">
          <span class="self-center text-2xl font-semibold">
            <img src="https://www.cyglobal.net/wp-content/uploads/2020/05/logo2.png" alt="">
          </span>
        </a>
      </div>
      <div class="grid grid-cols-2 text-sm gap-x-3 gap-y-8 lg:w-2/3 sm:grid-cols-4">
        <div class="space-y-3">
          <h3 class="tracking-wide uppercase text-gray-50">Product</h3>
          <ul class="space-y-1">
            <li>
              <a rel="noopener noreferrer" href="#">Features</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">Integrations</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">Pricing</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">FAQ</a>
            </li>
          </ul>
        </div>
        <div class="space-y-3">
          <h3 class="tracking-wide uppercase text-gray-50">Company</h3>
          <ul class="space-y-1">
            <li>
              <a rel="noopener noreferrer" href="#">Privacy</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">Terms of Service</a>
            </li>
          </ul>
        </div>
        <div class="space-y-3">
          <h3 class="uppercase text-gray-50">Developers</h3>
          <ul class="space-y-1">
            <li>
              <a rel="noopener noreferrer" href="#">Public API</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">Documentation</a>
            </li>
            <li>
              <a rel="noopener noreferrer" href="#">Guides</a>
            </li>
          </ul>
        </div>
        <div class="space-y-3">
          <div class="uppercase text-gray-50">Social media</div>
          <div class="flex justify-start space-x-3">
            <a rel="noopener noreferrer" href="#" title="Facebook" class="flex items-center p-1">
              <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 32 32"
                   class="w-5 h-5 fill-current">
                <path
                    d="M32 16c0-8.839-7.167-16-16-16-8.839 0-16 7.161-16 16 0 7.984 5.849 14.604 13.5 15.803v-11.177h-4.063v-4.625h4.063v-3.527c0-4.009 2.385-6.223 6.041-6.223 1.751 0 3.584 0.312 3.584 0.312v3.937h-2.021c-1.984 0-2.604 1.235-2.604 2.5v3h4.437l-0.713 4.625h-3.724v11.177c7.645-1.199 13.5-7.819 13.5-15.803z"></path>
              </svg>
            </a>
            <a rel="noopener noreferrer" href="#" title="Twitter" class="flex items-center p-1">
              <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 fill-current">
                <path
                    d="M23.954 4.569a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.061a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.937 4.937 0 004.604 3.417 9.868 9.868 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 002.46-2.548l-.047-.02z"></path>
              </svg>
            </a>
            <a rel="noopener noreferrer" href="#" title="Instagram" class="flex items-center p-1">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" fill="currentColor"
                   class="w-5 h-5 fill-current">
                <path
                    d="M16 0c-4.349 0-4.891 0.021-6.593 0.093-1.709 0.084-2.865 0.349-3.885 0.745-1.052 0.412-1.948 0.959-2.833 1.849-0.891 0.885-1.443 1.781-1.849 2.833-0.396 1.020-0.661 2.176-0.745 3.885-0.077 1.703-0.093 2.244-0.093 6.593s0.021 4.891 0.093 6.593c0.084 1.704 0.349 2.865 0.745 3.885 0.412 1.052 0.959 1.948 1.849 2.833 0.885 0.891 1.781 1.443 2.833 1.849 1.020 0.391 2.181 0.661 3.885 0.745 1.703 0.077 2.244 0.093 6.593 0.093s4.891-0.021 6.593-0.093c1.704-0.084 2.865-0.355 3.885-0.745 1.052-0.412 1.948-0.959 2.833-1.849 0.891-0.885 1.443-1.776 1.849-2.833 0.391-1.020 0.661-2.181 0.745-3.885 0.077-1.703 0.093-2.244 0.093-6.593s-0.021-4.891-0.093-6.593c-0.084-1.704-0.355-2.871-0.745-3.885-0.412-1.052-0.959-1.948-1.849-2.833-0.885-0.891-1.776-1.443-2.833-1.849-1.020-0.396-2.181-0.661-3.885-0.745-1.703-0.077-2.244-0.093-6.593-0.093zM16 2.88c4.271 0 4.781 0.021 6.469 0.093 1.557 0.073 2.405 0.333 2.968 0.553 0.751 0.291 1.276 0.635 1.844 1.197 0.557 0.557 0.901 1.088 1.192 1.839 0.22 0.563 0.48 1.411 0.553 2.968 0.072 1.688 0.093 2.199 0.093 6.469s-0.021 4.781-0.099 6.469c-0.084 1.557-0.344 2.405-0.563 2.968-0.303 0.751-0.641 1.276-1.199 1.844-0.563 0.557-1.099 0.901-1.844 1.192-0.556 0.22-1.416 0.48-2.979 0.553-1.697 0.072-2.197 0.093-6.479 0.093s-4.781-0.021-6.48-0.099c-1.557-0.084-2.416-0.344-2.979-0.563-0.76-0.303-1.281-0.641-1.839-1.199-0.563-0.563-0.921-1.099-1.197-1.844-0.224-0.556-0.48-1.416-0.563-2.979-0.057-1.677-0.084-2.197-0.084-6.459 0-4.26 0.027-4.781 0.084-6.479 0.083-1.563 0.339-2.421 0.563-2.979 0.276-0.761 0.635-1.281 1.197-1.844 0.557-0.557 1.079-0.917 1.839-1.199 0.563-0.219 1.401-0.479 2.964-0.557 1.697-0.061 2.197-0.083 6.473-0.083zM16 7.787c-4.541 0-8.213 3.677-8.213 8.213 0 4.541 3.677 8.213 8.213 8.213 4.541 0 8.213-3.677 8.213-8.213 0-4.541-3.677-8.213-8.213-8.213zM16 21.333c-2.948 0-5.333-2.385-5.333-5.333s2.385-5.333 5.333-5.333c2.948 0 5.333 2.385 5.333 5.333s-2.385 5.333-5.333 5.333zM26.464 7.459c0 1.063-0.865 1.921-1.923 1.921-1.063 0-1.921-0.859-1.921-1.921 0-1.057 0.864-1.917 1.921-1.917s1.923 0.86 1.923 1.917z"></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="py-6 text-sm text-center text-gray-400">© 1968 Company Co. All rights reserved.</div>
  </footer>

</template>


<style scoped>
.carousel__slide {
  padding: 19px;
}

.carousel__viewport {
  perspective: 2000px;
}

.carousel__track {
  transform-style: preserve-3d;
}

.carousel__slide--sliding {
  transition: 0.5s;
}


.button {
  display: inline-block;
  text-decoration: none;
  text-transform: uppercase;
  letter-spacing: 2px;
  outline: 2px solid;
  padding: 10px 30px;
  position: relative;
  overflow: hidden;
  transition: color 1s;
}

.button:hover {
  color: #fff;
}

.button::before {
  content: '';
  position: absolute;
  top: 0;
  left: -50px;
  width: 150%;
  height: 100%;
  background-color: #6a5af9;
  transform: scaleX(0) skewX(35deg);
  transform-origin: left;
  z-index: -1;
  transition: transform 1s;
}

.button:hover::before {
  transform: scaleX(1) skewX(35deg);
}


</style>
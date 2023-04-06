<template>
  <div>
    <div class="leading-normal tracking-normal text-white gradient" style="font-family: 'Source Sans Pro', sans-serif;">
      <!--Nav-->
      <nav id="header" class="fixed w-full bg-[#e7a20e] z-30 top-0 text-white">
        <div class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 py-2">
          <div class=" flex items-center">
            <a class="toggleColour text-white no-underline hover:no-underline font-bold text-2xl lg:text-4xl" href="#">
              <!--Icon from: http://www.potlabicons.com/ -->
              <img src="https://www.cyglobal.net/wp-content/uploads/2020/05/logo2.png" alt="">
            </a>
          </div>
          <div class="block lg:hidden pr-4">
            <button id="nav-toggle"
                    class="flex items-center p-1 text-pink-800 hover:text-gray-900 focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out">
              <svg class="fill-current h-6 w-6" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <title>Menu</title>
                <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/>
              </svg>
            </button>
          </div>
          <div
              class="w-full flex-grow lg:flex lg:items-center lg:w-auto hidden mt-2 lg:mt-0 bg-white lg:bg-transparent text-black p-4 lg:p-0 z-20"
              id="nav-content">
            <ul class="list-reset lg:flex justify-end flex-1 items-center">
              <li class="mr-3">
                <a class="inline-block text-[#FFFFFF] py-2 px-4  font-[500] hover:text-gray-800 no-underline"
                   href="#">
                  Home
                </a>
              </li>
              <li class="mr-3">
                <a class="inline-block text-[#FFFFFF] no-underline font-[500] hover:text-gray-800 hover:text-underline py-2 px-4"
                   href="#">Company</a>
              </li>
              <li class="mr-3">
                <a class="inline-block text-[#FFFFFF] no-underline font-[500] hover:text-gray-800 hover:text-underline py-2 px-4"
                   href="#">Services</a>
              </li>
              <li class="mr-3">
                <a class="inline-block text-[#FFFFFF] no-underline font-[500] hover:text-gray-800 hover:text-underline py-2 px-4"
                   href="#">Project</a>
              </li>
              <li class="mr-3">
                <a class="inline-block text-[#FFFFFF] no-underline font-[500] hover:text-gray-800 hover:text-underline py-2 px-4"
                   href="#">Blog</a>
              </li>
            </ul>
          </div>
        </div>
        <hr class="border-b border-gray-100 opacity-25 my-0 py-0"/>
      </nav>
      <!--Hero-->
      <div class="pt-24">
        <div class="container  mx-auto flex flex-wrap flex-col md:flex-row items-center">
          <!--Left Col-->
          <div class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left">
            <p class="uppercase tracking-loose w-full">SECURE & IT SERVICES</p>
            <h1 class="my-4 text-5xl font-bold leading-tight">
              Excellent IT Services for your success
              <br>
            </h1>
            <p class="leading-normal text-2xl mb-8 ">
              Sub-hero message, not too long and not too short. Make it just right!
            </p>
            <button href="#" class="button hover:text-[#fff]  z-[9]"> Subscribe</button>
          </div>
          <!--Right Col-->
          <div class="w-full md:w-3/5 py-6 text-center">
            <img class="w-full md:w-4/5 z-50" src="https://tailwindtoolbox.github.io/Landing-Page/hero.png"/>
          </div>
        </div>
      </div>
      <div class="relative -mt-12 lg:-mt-24">
        <svg viewBox="0 0 1428 174" version="1.1" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
            <g transform="translate(-2.000000, 44.000000)" fill="#FFFFFF" fill-rule="nonzero">
              <path
                  d="M0,0 C90.7283404,0.927527913 147.912752,27.187927 291.910178,59.9119003 C387.908462,81.7278826 543.605069,89.334785 759,82.7326078 C469.336065,156.254352 216.336065,153.6679 0,74.9732496"
                  opacity="0.100000001"></path>
              <path
                  d="M100,104.708498 C277.413333,72.2345949 426.147877,52.5246657 546.203633,45.5787101 C666.259389,38.6327546 810.524845,41.7979068 979,55.0741668 C931.069965,56.122511 810.303266,74.8455141 616.699903,111.243176 C423.096539,147.640838 250.863238,145.462612 100,104.708498 Z"
                  opacity="0.100000001"
              ></path>
              <path
                  d="M1046,51.6521276 C1130.83045,29.328812 1279.08318,17.607883 1439,40.1656806 L1439,120 C1271.17211,77.9435312 1140.17211,55.1609071 1046,51.6521276 Z"
                  id="Path-4" opacity="0.200000003"></path>
            </g>
            <g transform="translate(-4.000000, 76.000000)" fill="#FFFFFF" fill-rule="nonzero">
              <path
                  d="M0.457,34.035 C57.086,53.198 98.208,65.809 123.822,71.865 C181.454,85.495 234.295,90.29 272.033,93.459 C311.355,96.759 396.635,95.801 461.025,91.663 C486.76,90.01 518.727,86.372 556.926,80.752 C595.747,74.596 622.372,70.008 636.799,66.991 C663.913,61.324 712.501,49.503 727.605,46.128 C780.47,34.317 818.839,22.532 856.324,15.904 C922.689,4.169 955.676,2.522 1011.185,0.432 C1060.705,1.477 1097.39,3.129 1121.236,5.387 C1161.703,9.219 1208.621,17.821 1235.4,22.304 C1285.855,30.748 1354.351,47.432 1440.886,72.354 L1441.191,104.352 L1.121,104.031 L0.457,34.035 Z"
              ></path>
            </g>
          </g>
        </svg>
      </div>
    </div>
  </div>
</template>

<style scoped>
.gradient {
  background: rgb(56, 58, 66);
  background: linear-gradient(0deg, rgba(56, 58, 66, 1) 0%, rgba(246, 171, 9, 1) 100%);
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


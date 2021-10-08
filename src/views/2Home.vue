<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div class="h-full min-h-screen bg-gray-600">
    <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <!-- We've used 3xl here, but feel free to try other max-widths based on your needs -->
      <div class="max-w-3xl py-16 mx-auto">
        <div class="bg-white rounded-lg shadow">
          <div class="px-4 py-5 text-center sm:p-6">
            <div class="flex justify-center pb-5">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-8 h-8"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M9 3a1 1 0 012 0v5.5a.5.5 0 001 0V4a1 1 0 112 0v4.5a.5.5 0 001 0V6a1 1 0 112 0v5a7 7 0 11-14 0V9a1 1 0 012 0v2.5a.5.5 0 001 0V4a1 1 0 012 0v4.5a.5.5 0 001 0V3z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h2 class="text-2xl font-medium text-gray-900">
              Jeff's Portfolio is Under Construction
            </h2>
            <h3 class="pt-3 text-lg font-medium text-gray-900">
              In the meantime, here are some relevant links:
            </h3>
            <div class="mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">LinkedIn</h4>
                <div class="sm:flex sm:items-start">
                  <img src="/assets/linkedin.svg" class="inline-flex sm:block"/>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      /uxjeff
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('https://www.linkedin.com/in/uxjeff/','_blank')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">View Jeff's LinkedIn</span>
                  </button>
                </div>
              </div>
            </div>
            <div class="pb-5 mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">Email</h4>
                <div class="sm:flex sm:items-start">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="inline-flex w-10 h-10 sm:block"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"
                    />
                    <path
                      d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"
                    />
                  </svg>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      jeff@uxjeff.com
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('mailto:jeff@uxjeff.com?subject=Hi Jeff!')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">Send Jeff a Message</span>
                  </button>
                </div>
              </div>
            </div>
            <div class="relative">
              <div
                class="absolute inset-0 flex items-center"
                aria-hidden="true"
              >
                <div class="w-full border-t border-gray-300" />
              </div>
              <div class="relative flex justify-center">
                <span
                  class="px-3 text-lg font-medium text-gray-900 bg-white"
                >
                  Projects
                </span>
              </div>
            </div>
            <div class="mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">CG Sign Lab</h4>
                <div class="sm:flex sm:items-start">
                  <img src="/assets/cg-logo.png" width="42" class="inline-flex sm:block"/>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      UX/UI Dev @ CG Sign Lab
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('https://www.cgsignlab.com','_blank')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">View CG Sign Lab</span>
                  </button>
                </div>
              </div>
            </div>
            <div class="mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">CG on Demand</h4>
                <div class="sm:flex sm:items-start">
                  <img src="/assets/cg-logo.png" width="42" class="inline-flex sm:block"/>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      UX/UI Dev @ CG on Demand
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('https://www.cgondemand.com','_blank')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">View CG on Demand</span>
                  </button>
                </div>
              </div>
            </div>  
            <div class="mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">CG Pro Prints</h4>
                <div class="sm:flex sm:items-start">
                  <img src="/assets/cg-logo.png" width="42" class="inline-flex sm:block"/>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      UX/UI Dev @ CG Pro Prints
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('https://www.cgproprints.com','_blank')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">View CG Pro Prints</span>
                  </button>
                </div>
              </div>
            </div> 
            <div class="mt-5">
              <div
                class="px-6 py-5 bg-gray-100 rounded-md sm:flex sm:items-start sm:justify-between"
              >
                <h4 class="sr-only">Infinite Domain</h4>
                <div class="sm:flex sm:items-start">
                  <img src="/assets/ucsd-seal.svg" width="42" class="inline-flex sm:block"/>
                  <div class="mt-3 sm:mt-0 sm:ml-4">
                    <div
                      class="pt-1 text-2xl font-medium text-center text-gray-900 sm:text-left"
                    >
                      UCSD Exhibition Project
                    </div>
                    <div
                      class="mt-1 text-sm text-gray-600 sm:flex sm:items-center"
                    ></div>
                  </div>
                </div>
                <div class="mt-4 sm:mt-0 sm:ml-6 sm:flex-shrink-0">
                  <button
                    onclick=" window.open('https://infinitedomain.herokuapp.com/','_blank')"
                    type="button"
                    class="inline-flex items-center px-4 py-2 font-medium text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 sm:text-sm"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      /></svg
                    ><span class="pl-2">View Infinite Domain</span>
                  </button>
                </div>
              </div>
            </div>                                    
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

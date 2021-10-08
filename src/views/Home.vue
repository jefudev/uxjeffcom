<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <header class="bg-blue-600">
    <nav class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8" aria-label="Top">
      <div
        class="flex items-center justify-between w-full py-4 border-b border-blue-500 lg:border-none"
      >
        <div class="flex items-center">
          <a href="#">
            <span class="sr-only">Jeff Lau</span>
            <img
              class="w-auto text-white h-14"
              src="/assets/profile-icon-scribble.svg"
              alt="Menu Icon"
            />
          </a>
          <!-- <div class="hidden ml-10 space-x-8 lg:block">
            <a
              v-for="link in navigation"
              :key="link.name"
              :href="link.href"
              class="text-base font-medium text-white hover:text-blue-50"
            >
              {{ link.name }}
            </a>
          </div> -->
        </div>
        <div class="ml-10 space-x-4">
          <!-- <a
            href="#"
            class="inline-block px-4 py-2 text-base font-medium text-white bg-blue-500 border border-transparent rounded-md hover:bg-opacity-75"
            >Sign in</a
          > -->
          <a
            href="mailto:jeff@uxjeff.com"
            class="inline-block px-4 py-2 text-base font-medium text-blue-600 bg-white border border-transparent rounded-md hover:bg-blue-50"
            >Message Jeff</a
          >
        </div>
      </div>
      <!-- <div class="flex flex-wrap justify-center py-4 space-x-6 lg:hidden">
        <a
          v-for="link in navigation"
          :key="link.name"
          :href="link.href"
          class="text-base font-medium text-white hover:text-blue-50"
        >
          {{ link.name }}
        </a>
      </div> -->
    </nav>
  </header>

  <!-- Header -->
  <div class="bg-white">
    <!-- Header -->
    <div class="relative pb-32 bg-gray-800">
      <div class="absolute inset-0">
        <img
          class="object-cover w-full h-full"
          src="/assets/co-hero-photo.jpg"
          alt="Header Hero Image"
        />
        <div
          class="absolute inset-0 bg-gray-800 mix-blend-multiply"
          aria-hidden="true"
        />
      </div>
      <div
        class="relative px-4 py-24 mx-auto max-w-7xl sm:py-32 sm:px-6 lg:px-8"
      >
        <h1
          class="text-5xl font-bold tracking-tight text-white lg:text-6xl"
        >
          Jeff Lau
        </h1>
        <p class="max-w-3xl mt-6 text-xl text-gray-300">
          is a web developer and UX designer based in Denver, Colorado. He
          integrates his studies in interdisciplinary art with UX principles to
          create products that are effective, accessible, and enjoyable to use.
        </p>
      </div>
    </div>

    <!-- Overlapping cards -->
    <section
      class="relative z-10 px-4 pb-1 mx-auto -mt-32 max-w-7xl sm:px-6 lg:px-8"
      aria-labelledby="contact-heading"
    >
      <h2 class="sr-only" id="contact-heading">Contact us</h2>
      <div
        class="grid grid-cols-1 gap-y-20 lg:grid-cols-3 lg:gap-y-0 lg:gap-x-8"
      >
        <div
          v-for="link in supportLinks"
          :key="link.name"
          class="flex flex-col bg-white shadow-xl rounded-2xl"
        >
          <div class="relative flex-1 px-6 pt-16 pb-8 md:px-8">
            <div
              class="absolute top-0 inline-block p-2 transform -translate-y-1/2 bg-blue-600 shadow-lg rounded-xl"
            >
              <img :src="link.icon" class="w-auto h-14" />
              <!-- <component
                :is="link.icon"
                class="w-6 h-6 text-white"
                aria-hidden="true"
              /> -->
            </div>
            <h3 class="text-xl font-medium text-gray-900">{{ link.name }}</h3>
            <p class="mt-4 text-base text-gray-500">{{ link.description }}</p>
          </div>

          <div class="p-6 bg-gray-50 rounded-bl-2xl rounded-br-2xl md:px-8">
            <a
              :href="link.href"
              class="text-base font-medium text-blue-700 hover:text-blue-600"
              >{{ link.linkTxt }}<span aria-hidden="true"> &rarr;</span></a
            >
          </div>
        </div>
      </div>
    </section>
  </div>

  <!-- selected projects -->
  <div class="relative pt-16 pb-32 overflow-hidden bg-white">
    <div class="relative">
      <div
        class="px-4 py-12 mx-auto max-w-7xl sm:px-6 lg:px-8"
        id="selectedWork"
      >
        <h2
          class="text-4xl font-extrabold tracking-tight text-gray-900 lg:text-5xl"
        >
          Selected Work
        </h2>
        <p class="max-w-3xl mt-6 text-xl text-gray-900">
          Here are some of Jeff's previous projects, which showcase his
          experience in UX design, web development, and graphic design.
        </p>
      </div>
      <div
        class=" lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="max-w-xl px-4 mx-auto sm:px-6 lg:py-16 lg:max-w-none lg:mx-0 lg:px-0"
        >
          <div>
            <div>
              <span
                class="flex items-center justify-center w-12 h-12 bg-blue-600 rounded-md "
              >
                <img src="/assets/icon-diamond.svg" class="w-auto h-6" />
              </span>
            </div>
            <div class="mt-6 copy__height">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                CG Pro Prints
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                Working closely with engineers and key stakeholders, Jeff led
                the redesign of CG Pro Prints, Circle Graphics' top-performing
                wall decor store. His UX responsibilities included user
                research, competitive analysis, wireframes, high-fidelity
                prototyping, usability testing, information architecture, and
                design systems. <br /><br />
                By following a user-centered approach, Jeff created an online
                design tool and improved the checkout experience tailored to the
                user's needs. By using quantitative and qualitative data from
                past customers and interactions, Jeff was able to optimize the
                shopping experience for both new customers and frequent users.
              </p>
              <div class="mt-6">
                <a
                  href="#"
                  class="inline-flex px-4 py-2 text-base font-medium text-white bg-blue-600 border border-transparent rounded-md shadow-sm pointer-events-none opacity-40 hover:bg-blue-700"
                >
                  View Case Study
                </a>
                <p class="pt-2 pl-3 text-base italic text-gray-500">
                  Check back soon!
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0">
          <div
            class="pl-4 -mr-48 sm:pl-6 md:-mr-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full shadow-xl rounded-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:left-0 lg:h-full lg:w-auto lg:max-w-none"
              src="/assets/cgproprints.png"
              alt="CG Pro Prints Builder"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- SENSARIA -->
    <div class="mt-24">
      <div
        class=" lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="max-w-xl px-4 mx-auto sm:px-6 lg:py-16 lg:max-w-none lg:mx-0 lg:px-0 lg:col-start-2"
        >
          <div>
            <div>
              <span
                class="flex items-center justify-center w-12 h-12 bg-blue-600 rounded-md "
              >
                <img src="/assets/icon-lightbulb.svg" class="w-auto h-6" />
              </span>
            </div>
            <div class="mt-6 copy__height">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                Sensaria
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                Jeff was the lead front-end developer for the re-branding of an
                existing corporate site. He worked directly with stakeholders
                and designers to create a modular, marketing website that can be
                quickly updated with no-code.
                <br /><br />

                By providing valuable feedback and creative direction, Jeff
                built the WordPress-driven website to reflect an identity shift
                as a B2B company. Jeff was responsible for building HTML, CSS,
                and JS components to bring the corporate site to life. It
                featured responsive design, fluid grid layout, consistent design
                system, modular components, motion design, iconography, and
                product videos.
              </p>
              <div class="mt-6">
                <a
                  href="https://www.sensaria.com"
                  target="_blank"
                  class="inline-flex px-4 py-2 text-base font-medium text-white bg-blue-600 border border-transparent rounded-md shadow-sm hover:bg-blue-700"
                >
                  Visit Sensaria
                  <ExternalLinkIcon
                    class="w-5 h-6 ml-2 text-white"
                    aria-hidden="true"
                  />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0 lg:col-start-1">
          <div
            class="pr-4 -ml-48 sm:pr-6 md:-ml-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full shadow-xl rounded-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:right-0 lg:h-full lg:w-auto lg:max-w-none"
              src="/assets/sensaria.png"
              alt="Sensaria Landing Page"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- CG SIGN LAB -->
    <div class="mt-24">
      <div
        class=" lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="max-w-xl px-4 mx-auto sm:px-6 lg:py-16 lg:max-w-none lg:mx-0 lg:px-0"
        >
          <div>
            <div>
              <span
                class="flex items-center justify-center w-12 h-12 bg-blue-600 rounded-md "
              >
                <img src="/assets/icon-lightning.svg" class="w-auto h-6" />
              </span>
            </div>
            <div class="mt-6 copy__height">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                CG Sign Lab
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                Jeff was a key member in building CG Sign Lab, an online store
                that offers high-quality, customizable signs, and branding
                solutions. He was involved in every stage of the business's
                development, from idea generation, competitive analysis, graphic
                design, full-stack web development, and marketing.<br /><br />
                Jeff developed and re-imagined the theming component to create a
                suite of in-house eCommerce brands. By using the same codebase,
                Jeff quickly created niche stores serving different industries.
              </p>
              <div class="mt-6">
                <a
                  href="https://www.cgsignlab.com"
                  target="_blank"
                  class="inline-flex px-4 py-2 text-base font-medium text-white bg-blue-600 border border-transparent rounded-md shadow-sm hover:bg-blue-700"
                >
                  Visit CG Sign Lab
                  <ExternalLinkIcon
                    class="w-5 h-6 ml-2 text-white"
                    aria-hidden="true"
                  />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0">
          <div
            class="pl-4 -mr-48 sm:pl-6 md:-mr-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full shadow-xl rounded-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:left-0 lg:h-full lg:w-auto lg:max-w-none"
              src="/assets/cgsignlab-builder-min.png"
              alt="CG Sign Lab Builder"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- UCSD -->
    <div class="mt-24">
      <div
        class=" lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="max-w-xl px-4 mx-auto sm:px-6 lg:py-16 lg:max-w-none lg:mx-0 lg:px-0 lg:col-start-2"
        >
          <div>
            <div>
              <span
                class="flex items-center justify-center w-12 h-12 bg-blue-600 rounded-md "
              >
                <img src="/assets/icon-eye.svg" class="w-auto h-6" />
              </span>
            </div>
            <div class="mt-6 copy__height">
              <h2 class="text-3xl font-extrabold tracking-tight text-gray-900">
                Infinite Domain
              </h2>
              <p class="mt-4 text-lg text-gray-500">
                Jeff's senior thesis at UC San Diego, Infinite Domain, was a
                commentary on online privacy and phone addiction. At the time,
                he was worried about how much information he shared online every
                day — his name, social media handles, interests, and other
                personal details that could be accessed by anyone with an
                Internet connection or mobile device. He also feared falling
                into an unhealthy technology habit — those short sessions on his
                smartphone every hour or so.<br /><br />
                The website offered a provocative, interactive experience
                through its examination of how technology is changing our
                private lives. This piece was featured in the ICAM Senior
                Exhibition in 2016.
              </p>
              <div class="mt-6">
                <a
                  href="https://infinitedomain.herokuapp.com"
                  target="_blank"
                  class="inline-flex px-4 py-2 mr-6 text-base font-medium text-white bg-gray-700 border border-transparent rounded-md shadow-sm hover:bg-gray-800"
                >
                  Visit Infinite Domain
                  <ExternalLinkIcon
                    class="w-5 h-6 ml-2 text-white"
                    aria-hidden="true"
                  />
                </a>
                <a
                  href="https://projectwalt.wordpress.com"
                  target="_blank"
                  class="inline-flex px-4 py-2 text-base font-medium text-white bg-blue-600 border border-transparent rounded-md shadow-sm hover:bg-blue-700"
                >
                  View Case Study
                  <ExternalLinkIcon
                    class="w-5 h-6 ml-2 text-white"
                    aria-hidden="true"
                  />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0 lg:col-start-1">
          <div
            class="pr-4 -ml-48 sm:pr-6 md:-ml-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full shadow-xl rounded-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:right-0 lg:h-full lg:w-auto lg:max-w-none"
              src="/assets/infinite-domain.png"
              alt="Infinite Domain Mobile Renders"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- FOOTER -->
  <footer class="bg-gray-50">
    <div
      class="px-4 py-12 mx-auto max-w-7xl sm:px-6 md:flex md:items-center md:justify-between lg:px-8"
    >
      <div class="flex justify-center space-x-6 md:order-2">
        <a
          v-for="item in footerNavigation"
          :key="item.name"
          :href="item.href"
          class="text-gray-400 hover:text-gray-500"
          target="_blank"
        >
          <span class="sr-only">{{ item.name }}</span>
          <component :is="item.icon" class="w-6 h-6" aria-hidden="true" />
        </a>
      </div>
      <div class="mt-8 md:mt-0 md:order-1">
        <p class="text-base text-center text-gray-400">
          &copy; {{ new Date().getFullYear() }} Jeff Lau. All rights reserved.
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
const navigation = [{ name: "Work", href: "#" }];

import {
  NewspaperIcon,
  PhoneIcon,
  SupportIcon,
  InboxIcon,
  SparklesIcon,
  ExternalLinkIcon,
} from "@heroicons/vue/outline";
import { defineComponent, h } from "vue";

const supportLinks = [
  {
    name: "UX Designer",
    href: "#selectedWork",
    linkTxt: "See Work",
    description:
      "Jeff handles the entire product life-cycle, from user research to design to prototyping to testing and beyond. Jeff can craft thoughtful flows that reflect your business goals, build wireframes and prototypes using the latest tools, and run A/B tests with data-driven results.",
    icon: "/assets/pattern_1.svg",
  },
  {
    name: "Web Developer",
    href: "#selectedWork",
    linkTxt: "See Work",
    description:
      "With over 5 years of front-end experience, Jeff has a strong understanding of responsive design and is comfortable working with HTML, CSS, and Javascript to build beautiful, dynamic websites that capture the heart of your brand.",
    icon: "/assets/pattern_2.svg",
  },
  {
    name: "Let's chat!",
    href: "mailto:jeff@uxjeff.com",
    linkTxt: "Send Message",
    description:
      "The Internet is a place of endless possibilities, and there's always something exciting to discover. Please reach out! You never know what you’ll find...",
    icon: "/assets/pattern_3.svg",
  },
];
const footerNavigation = [
  {
    name: "LinkedIn",
    href: "http://linkedin.com/in/uxjeff/",
    icon: defineComponent({
      render: () =>
        h("svg", { fill: "currentColor", viewBox: "0 50 512 512" }, [
          h("path", {
            d: "M150.65,100.682c0,27.992-22.508,50.683-50.273,50.683c-27.765,0-50.273-22.691-50.273-50.683C50.104,72.691,72.612,50,100.377,50C128.143,50,150.65,72.691,150.65,100.682z M143.294,187.333H58.277V462h85.017V187.333zM279.195,187.333h-81.541V462h81.541c0,0,0-101.877,0-144.181c0-38.624,17.779-61.615,51.807-61.615c31.268,0,46.289,22.071,46.289,61.615c0,39.545,0,144.181,0,144.181h84.605c0,0,0-100.344,0-173.915s-41.689-109.131-99.934-109.131s-82.768,45.369-82.768,45.369V187.333z",
          }),
        ]),
    }),
  },
  {
    name: "GitHub",
    href: "https://github.com/jefudev",
    icon: defineComponent({
      render: () =>
        h("svg", { fill: "currentColor", viewBox: "0 0 24 24" }, [
          h("path", {
            "fill-rule": "evenodd",
            d: "M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z",
            "clip-rule": "evenodd",
          }),
        ]),
    }),
  },
];

export default {
  components: {
    InboxIcon,
    SparklesIcon,
    ExternalLinkIcon,
  },
  setup() {
    return {
      supportLinks,
      navigation,
      footerNavigation,
    };
  },
};
</script>

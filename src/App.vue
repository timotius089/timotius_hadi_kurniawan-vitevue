<script setup>
import { ref } from "vue";
import {
  Dialog,
  DialogPanel,
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
  Popover,
  PopoverButton,
  PopoverGroup,
  PopoverPanel,
} from "@headlessui/vue";
import {
  ArrowPathIcon,
  Bars3Icon,
  ChartPieIcon,
  CursorArrowRaysIcon,
  FingerPrintIcon,
  SquaresPlusIcon,
  XMarkIcon,
} from "@heroicons/vue/24/outline";
import {
  ChevronDownIcon,
  PhoneIcon,
  PlayCircleIcon,
} from "@heroicons/vue/20/solid";

const products = [
  {
    name: "Analytics",
    description: "Get a better understanding of your traffic",
    href: "#",
    icon: ChartPieIcon,
  },
  {
    name: "Engagement",
    description: "Speak directly to your customers",
    href: "#",
    icon: CursorArrowRaysIcon,
  },
  {
    name: "Security",
    description: "Your customers’ data will be safe and secure",
    href: "#",
    icon: FingerPrintIcon,
  },
  {
    name: "Integrations",
    description: "Connect with third-party tools",
    href: "#",
    icon: SquaresPlusIcon,
  },
  {
    name: "Automations",
    description: "Build strategic funnels that will convert",
    href: "#",
    icon: ArrowPathIcon,
  },
];
const callsToAction = [
  { name: "Watch demo", href: "#", icon: PlayCircleIcon },
  { name: "Contact sales", href: "#", icon: PhoneIcon },
];

const mobileMenuOpen = ref(false);

import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <header class="bg-white">
    <nav
      class="mx-auto flex max-w-7xl items-center justify-center p-6 lg:px-8"
      aria-label="Global"
      style="
        position: fixed;
        width: 100%;
        top: 0;
        padding: 2rem 0rem 0rem 10rem;
      "
    >
      <div class="flex lg:flex-1">
        <a href="#" class="-m-1.5 p-1.5">
          <span class="sr-only">Timotius Hadi Kurniawan</span>
          <h1
            style="
              color: black;
              font-weight: bold;
              font-size: 30px;
              font-family: Arial, Helvetica, sans-serif;
              letter-spacing: 3px;
            "
          >
            Portofolio
          </h1>
        </a>
      </div>
    </nav>
    <nav
      class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8"
      aria-label="Global"
      style="
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        justify-content: center;
      "
    >
      <div class="lg:flex lg:gap-x-12" style="margin: 0px 20px 0px 20px">
        <a
          href="#"
          class="text-sm/6 font-semibold text-gray-900 transition duration-300 delay-150 hover:delay-300"
        >
          <svg
            class="h-10 w-10 text-gray-500"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            style="transition: 500ms ease"
          >
            <path stroke="none" d="M0 0h24v24H0z" />
            <polyline points="5 12 3 12 12 3 21 12 19 12" />
            <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />
            <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" />
          </svg>
        </a>
      </div>
      <div class="lg:flex lg:gap-x-12" style="margin: 0px 20px 0px 20px">
        <a href="#" class="text-sm/6 font-semibold text-gray-900">
          <svg
            class="h-10 w-10 text-gray-500"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            style="transition: 500ms ease"
          >
            <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />
            <circle cx="12" cy="7" r="4" />
          </svg>
        </a>
      </div>
      <div class="lg:flex lg:gap-x-12" style="margin: 0px 20px 0px 20px">
        <a href="#" class="text-sm/6 font-semibold text-gray-900">
          <svg
            class="h-10 w-10 text-gray-500"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            style="transition: 500ms ease"
          >
            <path
              d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"
            />
          </svg>
        </a>
      </div>
      <div class="lg:flex lg:gap-x-12" style="margin: 0px 20px 0px 20px">
        <a href="#" class="text-sm/6 font-semibold text-gray-900">
          <svg
            class="h-10 w-10 text-gray-500"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            style="transition: 500ms ease"
          >
            <path
              d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
            />
            <polyline points="22,6 12,13 2,6" />
          </svg>
          <div
            style="
              background-color: gray;
              width: 100%;
              height: 4px;
              margin-bottom: -10px;
              transition: 500ms ease;
            "
          >
            &nbsp
          </div>
        </a>
      </div>
    </nav>
  </header>
  <body>
    <div class="flex-1" style="margin: auto; width: 70%; padding: 10px">
      <div class="flex justify-between items-center">
        <div>
          <h1 class="text-4xl font-bold">TIMOTIUS HADI KURNIAWAN</h1>
          <h2 class="text-6xl font-bold mt-4">Full Stack Developer</h2>
          <p class="text-gray-600 mt-4 max-w-lg">
            A junior fullstack developer who currently focused on Web
            Development. Other than that, I also interested in UX/UI Design,
            Mobile and AI Development. I love to learn new things and always
            open to new opportunities.
          </p>
          <div class="mt-8 space-x-4">
            <button class="bg-gray-800 text-white px-6 py-2 rounded-full">
              Download CV
            </button>
            <button
              class="border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
            >
              Contact Me
            </button>
          </div>
        </div>
        <div class="hidden md:block">
          <img
            alt="Profile picture of Alvalen Shafel"
            class="rounded-full"
            height="200"
            src="@/assets/Tim.jpeg"
            width="200"
          />
        </div>
      </div>
    </div>
  </body>
</template>

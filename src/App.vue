<script setup>
import { ref } from "vue";
import { RouterLink, RouterView } from "vue-router";
// import { myMethod } from "./components/model/modelfunct";
import HelloWorld from "./components/HelloWorld.vue";
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
</script>

<template>
  <nav
    class="mx-auto flex max-w-7xl items-center justify-center p-6 lg:px-8"
    style="
      position: fixed;
      width: 100%;
      top: 0;
      padding: 2rem 0rem 0rem 10rem;
      backdrop-filter: blur(5px);
      z-index: 1;
      background-color: #ffffff8a;
    "
  >
    <div
      class="flex lg:flex-1"
      style="justify-content: space-between; margin-right: 5%"
    >
      <a href="#" class="-m-1.5 p-1.5">
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
      <div style="display: grid; align-content: space-evenly">
        <h1
          style="
            color: black;
            font-weight: bold;
            font-size: 15px;
            font-family: Arial, Helvetica, sans-serif;
            letter-spacing: 3px;
          "
        >
          TIMOTIUS HADI KURNIAWAN
        </h1>
      </div>
    </div>
  </nav>
  <RouterView />
</template>
<style>
nav a {
  margin: 0px 20px;
}
nav a.router-link-exact-active {
  position: relative;
  width: max-content;
}
nav a.router-link-exact-active::after {
  content: " ";
  background-color: gray;
  height: 4px;
  width: 100%;
  position: absolute;
  bottom: 0;
  left: 0;
}

/* nav a.router-link-exact-active:hover {
  background-color: transparent;
} */
/* .mark {
  position: relative;
  width: max-content;
} */
/* .mark::after {
  content: " ";
  background-color: gray;
  height: 4px;
  width: 100%;
  position: absolute;
  bottom: 0;
  left: 0;
} */
</style>

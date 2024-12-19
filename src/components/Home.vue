<template>
  <nav
    class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8"
    aria-label="Global"
    style="
      position: fixed;
      display: grid;
      align-content: center;
      padding-left: 5px;
      top: 20%;
      width: 60px;
      background-color: #000000;
      border-radius: 0 30px 30px 0;
    "
  >
    <a
      href="#home"
      class="mnu mark"
      name="HOME"
      id="ahome"
      style="transition: 500ms ease; margin-bottom: 15px; margin-top: 15px"
    >
      <!-- <div id="nonhome" style="display: block" class="tulisan">Home</div> -->
      <svg
        class="h-10 w-10 lg:flex lg:gap-x-12 menublat"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" />
        <polyline points="5 12 3 12 12 3 21 12 19 12" />
        <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />
        <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" />
      </svg>
    </a>
    <a
      href="#about"
      class="mnu"
      name="ABOUT"
      id="aabout"
      style="transition: 500ms ease; margin-bottom: 15px; margin-top: 15px"
    >
      <!-- <div id="nonabout" style="display: none" class="tulisan">About</div> -->
      <svg
        class="h-10 w-10 lg:flex lg:gap-x-12 menublat"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />
        <circle cx="12" cy="7" r="4" />
      </svg>
    </a>
    <a
      href="#project"
      class="mnu"
      name="PROJECT"
      id="aproject"
      style="transition: 500ms ease; margin-bottom: 15px; margin-top: 15px"
    >
      <!-- <div id="nonproject" style="display: none" class="tulisan">Project</div> -->
      <svg
        class="h-10 w-10 lg:flex lg:gap-x-12 menublat"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path
          d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"
        />
      </svg>
    </a>
    <a
      href="#mail"
      class="mnu"
      name="MAIL"
      id="amail"
      style="transition: 500ms ease; margin-bottom: 15px; margin-top: 15px"
    >
      <!-- <div id="nonmail" style="display: none" class="tulisan">Mail</div> -->
      <svg
        class="h-10 w-10 lg:flex lg:gap-x-12 menublat"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path
          d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
        />
        <polyline points="22,6 12,13 2,6" />
      </svg>
    </a>
  </nav>
  <div class="contain">
    <section
      id="home"
      class="isiconten flex-1"
      style="margin: auto; padding: 150px 0px; width: 70%"
    >
      <div class="flex justify-between items-center">
        <div>
          <h1 class="text-4xl font-bold">TIMOTIUS HADI KURNIAWAN</h1>
          <h2 class="text-6xl font-bold mt-4">Full Stack Developer</h2>
          <p class="text-gray-600 mt-4 max-w-lg">
            Saya lulusan Sarjana Strata 1 (S1) Teknik Informatika, saya tertarik
            dalam pemrograman website, tetapi tidak menutup kemungkinan untuk
            mempelajari hal yang baru oleh karena itu, Saya mau belajar hal baru
            menyesuaikan apa yang dibutuhkan oleh perusahaan dalam bidang IT,
            saya berharap dapat berkontribusi dalam team saya bisa bekerja
            secara individu maupun kelompok, saya berharap dapat cepat
            beradaptasi dengan pekerjaan
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
            alt="Profile Timotius Hadi Kurniawan"
            class="rounded-full"
            height="200"
            src="@/assets/timonobacground.png"
            width="200"
          />
        </div>
      </div>
    </section>
    <section
      id="about"
      class="isiconten flex-1"
      style="margin: auto; padding: 150px 0px; width: 70%"
    >
      <div class="flex justify-between items-center">
        <div>
          <div>
            <h2 class="subhead text-6xl font-bold mt-4">About Me</h2>
            <div
              style="
                margin-top: 15px;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
            <div
              style="
                margin-top: 10px;
                margin-left: 30%;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
          </div>
          <p class="subisi text-gray-600 mt-4 max-w-lg">
            Ini Tentang saya, dan ketertarikan saya
          </p>
          <div class="mt-8 space-x-4">
            <button
              class="border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
            >
              Learn More
            </button>
          </div>
        </div>
        <div class="hidden md:block">
          <img
            alt="Profile Timotius Hadi Kurniawan"
            class="rounded-full"
            height="200"
            src="@/assets/Tim.jpeg"
            style="
              position: fixed;
              border-radius: 0;
              top: 7em;
              width: 20em;
              left: 77%;
              height: 30em;
            "
          />
        </div>
      </div>
    </section>
    <section
      id="project"
      class="isiconten flex-1"
      style="margin: auto; padding: 150px 0px; width: 70%"
    >
      <div class="flex justify-between items-center">
        <div>
          <div>
            <h2 class="subhead text-6xl font-bold mt-4">My Project</h2>
            <div
              style="
                margin-top: 15px;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
            <div
              style="
                margin-top: 10px;
                margin-left: 30%;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
          </div>
          <p class="subisi text-gray-600 mt-4 max-w-lg">
            Beberapa Pengalaman project yang sudah saya kerjakan dan beberapa
            project dengan beberapa bahasa pemrograman yang saya pelajari
          </p>
          <div class="mt-8 space-x-4">
            <button
              class="border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
            >
              Learn More
            </button>
          </div>
        </div>
        <div class="hidden md:block">
          <img
            alt="Profile Timotius Hadi Kurniawan"
            class="rounded-full"
            height="200"
            src="@/assets/Tim.jpeg"
            width="200"
          />
        </div>
      </div>
    </section>
    <section
      id="mail"
      class="isiconten flex-1"
      style="margin: auto; padding: 150px 0px; width: 70%"
    >
      <div class="flex justify-between items-center">
        <div>
          <div>
            <h2 class="subhead text-6xl font-bold mt-4">Contact me</h2>
            <div
              style="
                margin-top: 15px;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
            <div
              style="
                margin-top: 10px;
                margin-left: 30%;
                background-color: black;
                height: 5px;
                width: 50%;
              "
            ></div>
          </div>
          <p class="subisi text-gray-600 mt-4 max-w-lg">
            My Contact Person lebih detail bisa download CV <br /><br />
            timotius089@gmail.com
          </p>
          <div class="mt-8 space-x-4">
            <button
              id="email"
              class="btncontact border-gray-800 text-gray-800 px-6 py-2 rounded-full"
              cef="timotius089@gmail.com"
            >
              <!-- @click="" -->
              <img style="width: 100%" src="@/assets/mail.png" alt="" />
            </button>
            <button
              class="btncontact border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
              cef="www.linkedin.com/in/timotius-hadi-kurniawan-616a29288"
            >
              <img style="width: 100%" src="@/assets/linkedin.png" alt="" />
            </button>
            <button
              class="btncontact btncontactactve border border-gray-800 text-gray-800 px-6 py-2 rounded-full"
              cef="WA 089697069835"
            >
              <img style="width: 100%" src="@/assets/whatsapp.png" alt="" />
            </button>
          </div>
        </div>
        <div class="hidden md:block">
          <div
            style="
              position: fixed;
              border-radius: 0;
              top: 7em;
              width: 20em;
              left: 77%;
              height: 30em;
              z-index: 1;
              background-color: #00000040;
            "
          ></div>
          <img
            alt="Profile Timotius Hadi Kurniawan"
            class="rounded-full"
            src="@/assets/work.jpg"
            style="
              position: fixed;
              border-radius: 0;
              top: 7em;
              width: 20em;
              left: 77%;
              height: 30em;
            "
          />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
document.addEventListener("DOMContentLoaded", function (e) {
  console.log("loaded");
  let selections = document.querySelectorAll("section");
  let navlink = document.querySelectorAll("body div main nav a");
  window.onscroll = () => {
    // let about1 = document.getElementById("about");
    // let about1offset = about1.getBoundingClientRect();
    // let about1top = about1offset.top;
    // let about1height = about1offset.height;
    // let content = document.getElementsByClassName("isiconten");
    // let countcontent = content.length;
    selections.forEach((sad) => {
      let top = window.scrollY;
      let id = sad.getAttribute("id");
      let isicon = document.getElementById(id);
      let offset = isicon.offsetTop - 200;
      let height = isicon.offsetHeight;
      // console.log(height);
      if (top >= offset && top < offset + height) {
        navlink.forEach((links) => {
          let ida = links.getAttribute("id");
          // let tulisanisi = document
          //   .getElementsByClassName("tulisan")
          //   .classList.add("hilang");
          let isia = document.getElementById(ida);
          // isia.classList.remove("tulisan");
          isia.classList.remove("mark");
          document.querySelector("#a" + id + "").classList.add("mark");
          // document.querySelector("#a" + id + "").classList.add("tulisan");

          // let tulisan_gan = document.getElementById("a" + id + "");

          // tulisan_gan.style.tulisan.--_menuname =id;
          // let blocknon = document.getElementById("non" + id + "");
          // blocknon.style.setProperty("display", "block");
          // let contentisi = document.getElementsByClassName("mark");
          // contentisi.style.mark.setProperty("--_menuname", id);
          // let cont = contentisi.style.setp;
          // let beforecon = window
          //   .getComputedStyle(document.querySelector(".mark"), ":before")
          //   .getPropertyValue("content");
          // beforecon.style.content = id;
          // beforecon;
          // beforecon.style("content", id);
          // beforecon.setProperty("content ", id);
          // let btn = window.getComputedStyle(
          //   document.getElementById("a" + id + ""),
          //   ":before"
          // );
          // btn.content = id;

          // console.log(none);
        });
      }
      // else {
      //   let ida2 = links.getAttribute("id");
      //   let isia2 = document.getElementById(ida2);
      //   let blocknon2 = document.getElementById("non" + id + "");
      //   blocknon2.style.setProperty("display", "none");
      //   isia2.classList.remove("mark");
      // }
    });
  };
});
// function con() {
//   // let classtom = document.getElementsByClassName("btncontact");
//   // console.log(classtom);
//   console.log("tom");
// }
</script>

<style scoped>
.btncontact {
  background-color: #000000;
  padding: 3%;
  width: 50px;
  border: 0px;
}
.btncontact:hover {
  background-color: #686868;
}
.btncontactactve {
  background-color: #686868;
}
.btncontactactve::after {
  content: attr(cef);
  text-align: right;
  bottom: 24%;
  left: 30%;
  right: 25%;
  font-weight: 600;
  text-decoration: underline;
  position: absolute;
  letter-spacing: 1.5px;
}
.subhead {
  font-size: 7em;
}
.subisi {
  font-size: 20px;
}
.menublat {
  --tw-text-opacity: 1;
  color: rgb(255 255 255);
  border-radius: 10px;
  padding: 5px;
}
/* .contain {
  scroll-snap-type: y mandatory;
  overflow-y: scroll;
  height: 100vh;
} */
/* .hilang {
  display: none;
} */
.mnu {
  width: max-content;
  margin: 15px 0px 15px 0px;
  background-color: #000000;
  border: 2px solid rgb(0, 0, 0);
  border-radius: 50%;
}
.isiconten {
  /* scroll-snap-align: start; */
  animation: appear linear;
  animation-timeline: view();
  animation-range: entry 0% cover 40%;
}
/* :root {
} */
.mark {
  background-color: #000000;
  padding: 10px;
  border: 7px solid white;
  border-radius: 50%;
  margin-left: 10px;
  position: relative;
  width: max-content;
  display: grid;

  grid-template-columns: auto auto auto auto;
  grid-gap: 0px;
}
/* .mark::after {
  content: " ";
  background-color: gray;
  height: 4px;
  width: 100%;
  position: absolute;
  bottom: 0;
  left: 0;
} */
/* .mark::before {
  content: attr(name);
  align-content: center;
  width: 60px;
  letter-spacing: 0.5px;
  color: #ffffff;
  margin-right: 5px;
} */

.item {
  margin-top: 2rem;
  display: flex;
  position: relative;
}

.details {
  flex: 1;
  margin-left: 1rem;
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;
  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
  }

  i {
    top: calc(50% - 25px);
    left: -26px;
    position: absolute;
    border: 1px solid var(--color-border);
    background: var(--color-background);
    border-radius: 8px;
    width: 50px;
    height: 50px;
  }

  .item:before {
    content: " ";
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    bottom: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:after {
    content: " ";
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    top: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:first-of-type:before {
    display: none;
  }

  .item:last-of-type:after {
    display: none;
  }
}
</style>

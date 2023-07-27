<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'HTML',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/1051/1051277.png',
          status: 'Advanced'
        },
        {
          id: 2,
          name: 'CSS',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/732/732190.png',
          status: 'Advanced'
        },
        {
          id: 3,
          name: 'Angular',
          imageUrl: 'https://angular.io/assets/images/logos/angular/angular.svg',
          status: 'Beginner'
        },
        {
          id: 4,
          name: 'Javascript',
          imageUrl: 'https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png',
          status: 'Advanced'
        },
        {
          id: 5,
          name: 'Python',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg',
          status: 'Advanced'
        },
        {
          id: 6,
          name: 'Bash',
          imageUrl: 'https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg',
          status: 'Intermediate'
        },
        {
          id: 7,
          name: 'Linux',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg',
          status: 'Advanced'
        },
        {
          id: 8,
          name: 'Bootstrap',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg',
          status: 'Advanced'
        },
        {
          id: 9,
          name: 'NodeJS',
          imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-node-js-1174925.png',
          status: 'Advanced'
        },
        {
          id: 10,
          name: 'C#',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg',
          status: 'Advanced'
        },
        {
          id: 11,
          name: 'Django',
          imageUrl: 'https://cdn.worldvectorlogo.com/logos/django.svg',
          status: 'Beginner'
        },
        {
          id: 12,
          name: 'ReactJS',
          imageUrl: 'https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png',
          status: 'Advanced'
        },
        {
          id: 13,
          name: 'Arduino',
          imageUrl: 'https://cdn.worldvectorlogo.com/logos/arduino-1.svg',
          status: 'Beginner'
        },
        {
          id: 14,
          name: 'Postman',
          imageUrl: 'https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg',
          status: 'Intermediate'
        },
        {
          id: 15,
          name: 'Pandas',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg',
          status: 'Advanced'
        },
        {
          id: 16,
          name: 'VueJS',
          imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-vue-282497.png?f=webp',
          status: 'Beginner'
        },
      ],
      tools: [
        {
          id: 1,
          name: 'Git',
          imageUrl: 'https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png',
          status: 'Intermediate'
        },
        {
          id: 2,
          name: 'GitHub',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
          status: 'Git Hosting'
        },
        {
          id: 3,
          name: 'NPM',
          imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png',
          status: 'Package Manager'
        },
        {
          id: 4,
          name: 'MySQL',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/5968/5968313.png',
          status: 'Database'
        },
        {
          id: 5,
          name: 'Mongodb',
          imageUrl: 'https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg',
          status: 'Database'
        },
        {
          id: 6,
          name: 'Postman',
          imageUrl: 'https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg',
          status: 'Intermediate'
        },
        {
          id: 7,
          name: 'Heroku',
          imageUrl: 'https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg',
          status: 'Advanced'
        },
        {
          id: 8,
          name: 'Vercel',
          imageUrl: 'https://cdn.worldvectorlogo.com/logos/vercel.svg',
          status: 'Advanced'
        },
        {
          id: 9,
          name: 'Replit',
          imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/New_Replit_Logo.svg/1200px-New_Replit_Logo.svg.png',
          status: 'Advanced'
        },
        {
          id: 10,
          name: 'Thunder Client',
          imageUrl: 'https://rangav.gallerycdn.vsassets.io/extensions/rangav/vscode-thunder-client/2.9.2/1689682719120/Microsoft.VisualStudio.Services.Icons.Default',
          status: 'Advanced'
        },
      ],
      cyber: [
        {
          id: 1,
          name: 'Metasploit',
          imageUrl: 'https://dashboard.snapcraft.io/site_media/appmedia/2022/08/metasploit-framework-logo.svg.png',
          status: 'Advanced'
        },
        {
          id: 2,
          name: 'nmap',
          imageUrl: 'https://nmap.org/images/nmap-logo-256x256.png',
          status: 'Intermediate'
        },
        {
          id: 3,
          name: 'Nikto',
          imageUrl: 'https://www.kali.org/tools/nikto/images/nikto-logo.svg',
          status: 'Beginner'
        },
        {
          id: 4,
          name: 'Aircrack-ng',
          imageUrl: 'https://o.remove.bg/downloads/c6d2f470-20c6-48eb-a8ba-cff2eb890b52/download-removebg-preview.png',
          status: 'Beginner'
        },
        {
          id: 5,
          name: 'Hydra',
          imageUrl: 'https://www.kali.org/tools/hydra/images/hydra-logo.svg',
          status: 'Intermediate'
        },
        {
          id: 6,
          name: 'Wireshark',
          imageUrl: 'https://cdn.icon-icons.com/icons2/1381/PNG/512/wireshark_94067.png',
          status: 'Advanced'
        },
        {
          id: 7,
          name: 'Burpsuite',
          imageUrl: 'https://o.remove.bg/downloads/7ec13b77-1bb1-443b-9e9a-a871a740025e/download__1_-removebg-preview.png',
          status: 'Intermediate'
        },
        {
          id: 8,
          name: 'Hashcat',
          imageUrl: 'https://o.remove.bg/downloads/b8eb1f4b-d250-4917-824c-d6525a1fc7bb/download-removebg-preview.png',
          status: 'Intermediate'
        },
        {
          id: 9,
          name: 'Sqlmap',
          imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/4/4f/Sqlmap_logo.png',
          status: 'Beginner'
        },
        {
          id: 10,
          name: 'Beef',
          imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/e/e4/Beef_project_logo.png',
          status: 'Advanced'
        },
        {
          id: 11,
          name: 'Netcat',
          imageUrl: 'https://www.kali.org/tools/netcat/images/netcat-logo.svg',
          status: 'Intermediate'
        },
        {
          id: 12,
          name: 'Scapy',
          imageUrl: 'https://warehouse-camo.ingress.us-east-2.pypi.io/4185e1e21f4019a6e06ff8ce5a1ddd59661889b4/68747470733a2f2f6769746875622e636f6d2f7365636465762f73636170792f7261772f6d61737465722f646f632f73636170792f67726170686963732f73636170795f6c6f676f2e706e67',
          status: 'Beginner'
        },
      ],
    };
  }
}
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About Me &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-8/12 rounded-full border-4 border-amber-200 pict fadein-up"
            src="https://i.pinimg.com/564x/43/b0/59/43b059eb553f66b94f1bf4133df0e1bd.jpg" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp;<strong><u>Software</u><br></strong>
                &nbsp; &nbsp; &nbsp;I have a sufficient background in Full-Stack Engineering. With a solid foundation in these technologies,
                I have acquired comprehensive knowledge and experience in web development, data analysis, and network simulation.
                I am proficient in JavaScript and React for building dynamic and interactive web applications,
                while Python and Anaconda Navigator enable me to perform efficient data analysis and visualization tasks.
                Additionally, my knowledge in Django allows me to develop robust and scalable web applications, while my
                familiarity with Cisco Packet Tracer enables me to simulate and design complex network topologies. 
                I am passionate about leveraging my skills to create innovative solutions and contribute to the success of projects
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp;<strong><u>Network & Cyber Security</u><br></strong>
            &nbsp; &nbsp; &nbsp;I learned about networks during university because of the lessons, we tried to set up many networks using the cisco
            packet tracer application, Furthermore, my passion for networks was nurtured during my university years as we extensively
            worked on setting up various networks using the Cisco Packet Tracer application. Through hands-on exercises and
            simulations, I gained valuable experience in network configuration, troubleshooting, and optimization. This practical exposure 
            has honed my skills in designing secure and efficient network infrastructures, ensuring seamless connectivity and data transmission.
          </p>
        </div>

      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Tech Stack</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Tools</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 3 }" @click="activeTab = 3">Cyber Security Tools</button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
                <div v-show="activeTab === 3">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in cyber" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
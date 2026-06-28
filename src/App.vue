<script setup>
const folders = [
  {
    title: 'Jobright',
    links: [
      {
        label: 'Jobright',
        href: 'https://jobright.ai/jobs/recommend?utm_source=1012&utm_medium=google_search&utm_campaign=N_Brand_Search&utm_content=US&utm_term=job+rights&gad_source=1&gad_campaignid=22428760286&gbraid=0AAAAA_SS3j5iNPp_lne-z2NElZzXZweH1&gclid=Cj0KCQjwk_bPBhDXARIsACiq8R29bXQnHiaXAZXiv0QyVeft5cdUwKHojHbTBFC-PikAVEkAhF-CpuIaAgFvEALw_wcB#basic'
      }
    ]
  },
  {
    title: 'Migrate Mate',
    links: [
      {
        label: 'user interface',
        href: 'https://migratemate.co/jobs?q=user%20interface&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      },
      {
        label: 'front end',
        href: 'https://migratemate.co/jobs?q=front%20end&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      },
      {
        label: 'web developer',
        href: 'https://migratemate.co/jobs?q=web%20developer&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      },
      {
        label: 'user experience',
        href: 'https://migratemate.co/jobs?q=user%20experience&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      },
      {
        label: 'software engineer',
        href: 'https://migratemate.co/jobs?q=software%20engineer&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      },
      {
        label: 'ui ux',
        href: 'https://migratemate.co/jobs?q=ui%20ux&visa=EB-2%252FEB-3%2520%257C%2520Green%2520Card%2CH-1B%2520%257C%2520Global&edu=Master%27s%2CAssociate%27s%2CBachelor%27s%2CHigh%2520School%2CNone%2COther&sched=Full%2520Time&func=Software%2520Engineering%2CFull-stack%2520Engineering%2CFrontend%2520Engineering%2CUI%252FUX%2520Design%2CMobile%2520Engineering%2520%28iOS%252FAndroid%29&intern=NO&exp=0&dp=month'
      }
    ]
  },
  {
    title: 'Simplify',
    links: [
      {
        label: 'user interface',
        href: 'https://simplify.jobs/jobs?query=user%20interface&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      },
      {
        label: 'front end',
        href: 'https://simplify.jobs/jobs?query=front%20end&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      },
      {
        label: 'web developer',
        href: 'https://simplify.jobs/jobs?query=web&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      },
      {
        label: 'user experience',
        href: 'https://simplify.jobs/jobs?query=user%20experience&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      },
      {
        label: 'software engineer',
        href: 'https://simplify.jobs/jobs?query=software%20engineer&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      },
      {
        label: 'ui ux',
        href: 'https://simplify.jobs/jobs?query=ui%20ux&state=United%20States&country=United%20States&experience=Entry%20Level%2FNew%20Grad&education=Bachelor%27s%3BMBA%3BMaster%27s%3BAssociate%27s%3BCertificate&h1b=true&securityClearance=false&excludeApplied=true&jobId=17d90cd2-2ea7-4df7-b3df-6b809d7a6842&jobType=Full-Time'
      }
    ]
  },
  {
    title: 'Visa Sponsor Jobs',
    links: [
      {
        label: 'user interface',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&keyword=user+interface&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&experienceLevel=Entry-Level&showMoreOptions=true'
      },
      {
        label: 'front end',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&keyword=front+end&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&experienceLevel=Entry-Level&showMoreOptions=true'
      },
      {
        label: 'web developer',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&keyword=web+developer&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&experienceLevel=Entry-Level&showMoreOptions=true'
      },
      {
        label: 'user experience',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&classification=Design-and-Arts&classification=Engineering&classification=Information-Technology&keyword=user+experience&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&educationLevel=High-School&educationLevel=Vocational-Certificate&educationLevel=Bachelor-Degree&educationLevel=Master-Degree&educationLevel=Professional-Degree&experienceLevel=Entry-Level&showMoreOptions=true'
      },
      {
        label: 'software engineer',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&keyword=software+engineer&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&experienceLevel=Entry-Level&showMoreOptions=true'
      },
      {
        label: 'ui ux',
        href: 'https://visasponsor.jobs/api/jobs?country=Canada&country=United-States&keyword=ui+ux&visa=PNP&visa=TFWP&visa=Other-Canada&visa=H-1B&experienceLevel=Entry-Level&showMoreOptions=false'
      }
    ]
  },
  {
    title: 'Jaabz',
    links: [
      {
        label: 'user interface',
        href: 'https://jaabz.com/jobs?keyword=user+interface&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      },
      {
        label: 'front end',
        href: 'https://jaabz.com/jobs?keyword=front+end&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      },
      {
        label: 'web developer',
        href: 'https://jaabz.com/jobs?keyword=web&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      },
      {
        label: 'user experience',
        href: 'https://jaabz.com/jobs?keyword=user+experience&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      },
      {
        label: 'software engineer',
        href: 'https://jaabz.com/jobs?keyword=software&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      },
      {
        label: 'ui ux',
        href: 'https://jaabz.com/jobs?keyword=ui+ux&countries=canada,united-state&experience_level=Entry+level&visa_sponsorship=1&search_submitted=1'
      }
    ]
  },
  {
    title: 'Resources',
    links: [
      {
        label: 'Mail',
        href: 'https://mail.google.com/mail/u/0/#all'
      },
      {
        label: 'LinkedIn',
        href: 'https://www.linkedin.com/in/asher-nyu/'
      },
      {
        label: 'Secure Notes',
        href: 'https://swift-resume.com/asher'
      },
      {
        label: 'Bulletify',
        href: 'https://bulletify.vercel.app'
      },
      {
        label: 'SwiftResume',
        href: 'https://swift-resume.com'
      },
      {
        label: 'Portfolio',
        href: 'https://asher-nyu.com'
      },
      {
        label: 'GitHub',
        href: 'https://github.com/asher-nyu/JobHub/commits/main/'
      }
    ]
  }
];
</script>

<template>
  <div class="container">
    <h1>JobHub</h1>
    <div class="bookmark-grid" id="bookmarkGrid">
      <div class="folder" v-for="folder in folders" :key="folder.title">
        <h3>{{ folder.title }}</h3>
        <ul>
          <li v-for="link in folder.links" :key="link.href">
            <a :href="link.href" target="_blank">{{ link.label }}</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

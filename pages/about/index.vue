<template>
  <div class="container">
    <div class="heading">
      <h1 class="title">
        About Me
      </h1>
      <h2 class="subtitle-two">
        Will work for food, fun, coffee, climbing, experiences, and money. I like money.
      </h2>
      <img class="responsive" src="~/static/jakob.jpg" alt="A picture of me and my wife Maili">
      <h3 class="about-header">
        Work
      </h3>
      <p>
        Currently I work as an SRE at <a href="https://view.do" class="links">ViewDo Inc</a>, however my background is in electrical engineering. I've worked on everything from designing tube pre-amp's for my own hi-fi audio setup (ask me about it), to network switches, to communications modules for electronic life safety monitoring systems. I've been rocking shit in Linux as my default environment since 2004. While there was some inherent need to know a little programming to pick up Linux and run with it at that time, I knew very little. I started learning my way around the command line and never looked back. The majority of my work was on embedded systems using linux to host servers embedded into products. Eventually I started designing my own website. I was hosting it with some GoDaddy or AIG owned web hosting service and I needed to make a DNS update. This simple request got me to where I am today. The answer I got after waiting 15 minutes on hold was "Yes, I'll handle that for you, but be aware DNS updates can take up to 24 hours to propagate." I shook my head in disbelief, having experience working on a team that developed a network switch, I understood a bit about how they worked and knew there was no way that reply could hold weight. I started learning how to configure a LAMP stack, migrated my domains to somewhere I had more control over DNS, and started learning different ways of configuring systems. I soon moved on to figuring out MEAN and MERN stacks. Eventually I learned about Docker, which led to compose, and eventually Kubernetes. Picking up on the intricacies of Linux based operating systems, how to monitor, configure, and secure them and their processes along the way.<br><br>
        Most recently, in the last couple of years I've been helping companies migrate their traditional or VM based infrastructure to this new paradigm of cloud computing. It all started at Colorado Hosting. I was instrumental in migrating over 250 VMs all running individual WordPress sites, all with their own embedded mysql databases, to a more distributed multi-region solution, while cutting the budget. At the end of a grueling year we managed to get every single site running in K8S with RDS databases, and reduced the department's overhead by 45% while providing enhanced reliability. While Colorado Hosting is no longer in existence (the owner sold it and retired), I am very proud of the team and the work we did.<br><br>
        From there I've helped migrate two other companies to the cloud who were struggling with similar goals. At Influence Technologies I was again tasked with migrating their application from services on windows VMs to containerized services running in Kubernetes, along with taking ownership of the supporting services such as RavenDB and RabbitMQ. They also wanted to transition to more of a pipelines-first approach to deployments and new projects. Here I was able to help reduce time to deployment, increase productivity through automated workflows, and increase the overall performance of the platform through optimization by 3X! Next I moved to ViewDo Inc, where I've been handed so many unique tasks and projects they deserve their own blog posts. Feel free to <a href="/blog" class="links">keep tabs on my updates here</a>.
      </p>
      <h3 class="about-header">
        Love
      </h3>
      <p>
        They say behind every great man is a better woman. I'm far from claiming greatness, but that which I have achieved is mainly due to the beautiful woman you see pictured at my side above. Maili and I have been together for 12 years at the time of this writing. She inspires me to bring my A game every single day. She has always supported my dreams and aspirations, while holding steadfast to her own. We were kids when we fell in love. And while the meaning of that word has taken a different (better) definition than we meant years ago, it applies stronger today than ever.
      </p>
      <h3 class="about-header">
        Life
      </h3>
      <p>
        Maili and I love to travel, we hope to visit every country in the world before we kick that bucket in the sky. We have a lot to still see, but I am very outgoing, or "chatty" as Maili says, and I make friends very easily, in almost every situation, every day. This has afforded us ample opportunities to travel on the cheap. We have made friends all over the world, and I maintain a Slack workspace where we all keep in touch. It's sort of like our own little social network, with people all over the world connecting with one another there before making travel plans. Because Maili and I personally know each and every person on that list, they are inclined to trust one another. We absolutely love being the catalyst that brings these people together. Some we may never see again in our lives, in person. But we value and cherish each of the friends we have made along the way and are always so happy when we see pictures of them meeting one another. <br><br>
        We intend to keep traveling for many years to come. We like to plan at least two international trips each year. On most of these trips we hit 3-4 countries at least. On our most recent journey we got to visit Ireland, England, The Netherlands, and Italy. Ask me about pizza and I may break down in tears. If you haven't been to Italy, IMWO you've never had pizza in your life. What we have here in the US is okay, I haven't lost my appreciation for it, but I struggle to call it "Pizza" anymore.
      </p>
    </div>
  </div>
</template>

<style scoped>
.subtitle-two {
  color: white;
  font-size: 1.2em;
}

.about-header {
  color: white;
  text-align: left;
  font-size: 1.5em;
}
</style>

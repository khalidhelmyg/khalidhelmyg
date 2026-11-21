<div align="center">

# 👋 Hi, I'm Khalid Helmy

### 🚀 Software Engineer | Backend Developer | Node.js | NestJs | Microservices 
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=750&lines=Backend+Software+Engineer;Building+Scalable+Backend+Applications;Node.js+%7C+TypeScript+%7C+NestJS;Microservices+%26+Distributed+Systems;APIs+%7C+Databases+%7C+System+Design)](https://github.com/khalidhelmyg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khalid-helmy)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/khalidhelmyg)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:khaledhelmyelkefafy@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-6E56CF?style=flat&logo=vercel&logoColor=white)](https://khalidhelmy.lovable.app/)

</div>

---

## 💼 About Me

I'm a passionate **Software Engineer** and **Backend Developer** currently working at **Md Soft**. I specialize in building scalable, high-performance applications using modern technologies. As an IT student, I'm constantly exploring and mastering new tools and frameworks to stay at the cutting edge of development.

- 🔭 **Currently Working**: Backend Development at **Md Soft**
- 🌱 **Currently Learning**: Advanced System Design
- 💬 **Ask Me About**: Node.js, Express.js, NestJS, WebSockets, MongoDB, PostgreSQL, GraphQL, Angular, Microservices, Kafka, Redis, Docker
- 📍 **Location**: Cairo Egypt
- 📧 **Email**: khaledhelmyelkefafy@gmail.com
- 🎯 **Goal**: Building elegant, maintainable, and scalable solutions

Open to:  Software Engineer · Backend Engineer · Full-Stack Engineer roles.

---

## 📊 GitHub Stats

<div align="center">

![GitHub Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=khalidhelmyg&theme=github_dark)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=khalidhelmyg&theme=github-dark-blue&hide_border=true)

</div>

---

## Featured: nestjs-realtime-sdk

<p>
  <a href="https://www.npmjs.com/package/nestjs-realtime-sdk"><img src="https://img.shields.io/npm/v/nestjs-realtime-sdk?style=flat-square&logo=npm&label=npm" alt="npm version"/></a>
  <a href="https://www.npmjs.com/package/nestjs-realtime-sdk"><img src="https://img.shields.io/npm/dm/nestjs-realtime-sdk?style=flat-square&label=downloads" alt="npm monthly downloads"/></a>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="MIT license"/>
</p>

A lightweight, extensible NestJS SDK for **1-to-1 real-time audio/video calling** powered by WebRTC and Socket.IO. Build and own your calling infrastructure instead of relying on costly third-party platforms like ZEGOCLOUD or Agora. Reduce recurring service costs while retaining full control over call lifecycle, signaling, user presence, database, and push notifications.
### Installation

**Install via npm**

```bash
npm install nestjs-realtime-sdk
```

```ts
RealtimeCallingModule.forRootAsync({
  imports: [CallPersistenceModule],
  useFactory: (repo: CallRepository, notify: CallNotificationService) => ({
    callRepository: repo,
    notificationService: notify,
  }),
  inject: [CallRepository, CallNotificationService],
});
```

**Design decisions**

- **Explicit call state machine:** ringing → active / rejected / ended. Invalid transitions are rejected, and calls are cleaned up automatically when a user disconnects.
- **Optimistic locking:** concurrent accept-call races are resolved with version fields instead of ad-hoc checks.
- **Pluggable ports:** persistence and push notifications are interfaces (`ICallRepository`, `INotificationService`), so the SDK has no database driver, FCM SDK, or platform lock-in.
- **Signaling relay:** offer, answer, and ICE payloads are forwarded unmodified and never logged.
- **Strict TypeScript:** typed events, payloads, and errors, for NestJS 11.

**Production notes it covers:** TURN servers for users behind symmetric NAT, authenticating `userId` before the socket handshake, explicit Socket.IO CORS, and a Redis adapter for multi-instance deployments.

> The source is private. Docs and examples ship inside the package.

**Write-ups:** *What a Video Call Backend Actually Does* (Medium)

---

## 🛠️ Tech Stack

### Languages
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#"/>
</div>

### Backend & Runtime
<div>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL"/>
</div>

### Frontend
<div>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular"/>
  <img src="https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</div>

### Databases
<div>
  <img src="https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</div>

### Tools & Platforms
<div>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</div>

## 🎯 What I'm Currently Working On

- 🏗️ Building scalable microservices with NestJS
- 📚 Learning advanced system design patterns
- 🚀 Exploring Kubernetes & DevOps practices
- 🔐 Implementing secure authentication systems
- 💬 Real-time communication with WebSockets

---

## 💬 Let's Connect!

I love connecting with developers, tech enthusiasts, and anyone interested in building amazing things. Whether you want to discuss tech, collaborate on projects, or just chat:

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khalid-helmy)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalidhelmyg)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khaledhelmyelkefafy@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-6E56CF?style=for-the-badge&logo=vercel&logoColor=white)](https://khalidhelmy.lovable.app/)

</div>

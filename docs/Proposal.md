---
---
# Smart Roommate Matching Application

---

## Project Description
This project proposes the development of a **smart roommate matching application** designed to improve the student housing experience by pairing students based on compatibility in habits, interests, and lifestyle preferences. Unlike traditional assignment methods that rely on randomization or a one-time survey, this system incorporates **continuous feedback through weekly or bi-weekly check-ins**. These check-ins allow the algorithm to dynamically adjust compatibility scores and provide early alerts to housing staff when conflicts are likely.

---

## Comparison with Existing Solutions
Several roommate matching platforms already exist, but most focus on one-time surveys and static placements:

- **RoomSync [1]:** Uses lifestyle questionnaires and optional Facebook integration. Provides strong self-selection but no ongoing monitoring.  
- **StarRez [2]:** A university housing software suite that improves placement with lifestyle surveys. While widely adopted, it does not adapt post-move-in.  
- **MeetYourClass [3]:** A free roommate and classmate matching platform that allows filtering by interests and habits. However, it lacks integration with housing staff and ongoing conflict tracking.  
- **Roomsurf [4]:** A student-driven matching tool that works before move-in only, with no feedback loop.  
- **Beroomie [5]:** A modern AI-driven roommate app with quizzes and safety tools. While innovative, it does not emphasize continuous satisfaction monitoring or provide staff dashboards.  

**Key Differentiator:** This proposed app emphasizes **dynamic matching and proactive conflict prevention** by integrating ongoing feedback loops, adaptive scoring, and staff support tools—capabilities not present in competing platforms.  

---

### Main Features
- **Survey-driven profiles:** Students provide lifestyle and preference information (study habits, cleanliness, sleep schedules, social activity).  
- **Adaptive matching algorithm:** Uses weighted scoring and constraints to pair compatible students, updating matches with feedback.  
- **Weekly/Bi-weekly check-ins:** Students rate satisfaction and flag issues, allowing proactive conflict detection.  
- **Admin dashboard:** Housing staff can monitor analytics, satisfaction trends, and receive early alerts for intervention.  
- **Mentorship integration:** Option for pairing freshmen with upperclassmen mentors.  
- **Scalability:** Framework can expand beyond university housing into co-living and professional roommate markets. 

---

## Learning Load and Feasibility
- **Is this a new language?** Yes, I have experience in Python, Java, and Kotlin, but TypeScript is relatively new to me. While I am familiar with JavaScript basics, I will need to learn how to apply TypeScript across the full project.  
- **New frameworks/libraries to learn:** Next.js (frontend), NestJS (backend), Prisma (database ORM), BullMQ with Redis (memory key for background jobs), React Hook Form + Zod (forms and validation), and Recharts (analytics). These are all new to me but widely documented.  
- **Project organization and tools:** A **monorepo structure** to organize code. I will also need to learn tools such as ESLint/Prettier (linting), Docker Compose (local Postgres/Redis setup), and GitHub Actions (CI/CD).  
- **External storage needs:** PostgreSQL for primary data storage (profiles, matches, check-ins, alerts) and Redis for caching and background job queues.  
- **Hosting and deployment:**  
  - **Frontend (Next.js):** Hosted on Vercel.  
  - **Backend (NestJS):** Hosted on Railway with managed PostgreSQL and Redis.  

---

## References
[1] RoomSync, “RoomSync – Roommate Matching Software,” Accessed Sept. 2025. [Online]. Available: https://www.roomsync.com/  
[2] StarRez, “Room and Roommate Solution,” Accessed Sept. 2025. [Online]. Available: https://www.starrez.com/solutions/room-and-roommate-solution  
[3] MeetYourClass, “College Roommate Finder,” Accessed Sept. 2025. [Online]. Available: https://www.meetyourclass.com/  
[4] Roomsurf, “Find a Roommate,” Accessed Sept. 2025. [Online]. Available: https://www.roomsurf.com/  
[5] Beroomie, “Best Apps to Find College Roommates in 2025,” Accessed Sept. 2025. [Online]. Available: https://beroomie.app/blog/best-apps-to-find-college-roommates-in-2025-  

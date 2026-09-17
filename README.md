<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0EA5B7&height=190&section=header&text=Ahmed%20Said&fontSize=48&fontColor=F1F5F9&fontAlignY=38&desc=Backend%20.NET%20Developer&descAlign=58&descSize=18&descColor=94E5F5&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=18&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=560&lines=Building+reliable+APIs+%26+scalable+backend+systems;C%23+%C2%B7+ASP.NET+Core+%C2%B7+EF+Core+%C2%B7+SQL+Server;Clean+Architecture+%C2%B7+Clean+Code" alt="Typing SVG" />

<br/><br/>

<a href="https://github.com/AhmedS3id"><img src="https://img.shields.io/badge/GitHub-AhmedS3id-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8&labelColor=0F172A" /></a>
<a href="https://www.linkedin.com/in/ahmed-said-b006a0269"><img src="https://img.shields.io/badge/LinkedIn-Ahmed_Said-0F172A?style=for-the-badge&logo=linkedin&logoColor=38BDF8&labelColor=0F172A" /></a>
<a href="mailto:ahmeds3id711@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8&labelColor=0F172A" /></a>
<a href="https://wa.me/201028527109"><img src="https://img.shields.io/badge/WhatsApp-Message-0F172A?style=for-the-badge&logo=whatsapp&logoColor=38BDF8&labelColor=0F172A" /></a>

</div>

<br/>

## 👨‍💻 About Me

Backend-focused developer working with **C#, ASP.NET Core, EF Core and SQL Server**, with a strong interest in clean architecture, API design, and scalable systems.

Final-year Computer Science student at Zagazig University, and completed a 145-hour .NET backend development track at ITI. I care about the parts of a backend that don't show up in a demo — proper auth, background jobs, health checks, structured logging — not just endpoints that work on the happy path.

<br/>

## 🧩 Tech Stack

<table width="100%">
<tr>
<td width="25%" valign="top">

**Backend**

![C#](https://img.shields.io/badge/C%23-0F172A?style=flat-square&logo=csharp&logoColor=38BDF8)
![.NET](https://img.shields.io/badge/.NET-0F172A?style=flat-square&logo=dotnet&logoColor=38BDF8)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-0F172A?style=flat-square&logo=dotnet&logoColor=38BDF8)
![EF Core](https://img.shields.io/badge/EF_Core-0F172A?style=flat-square&logo=nuget&logoColor=38BDF8)

</td>
<td width="25%" valign="top">

**Data & APIs**

![SQL Server](https://img.shields.io/badge/SQL_Server-0F172A?style=flat-square&logo=microsoftsqlserver&logoColor=38BDF8)
![REST APIs](https://img.shields.io/badge/REST_APIs-0F172A?style=flat-square&logo=fastapi&logoColor=38BDF8)
![JWT](https://img.shields.io/badge/JWT-0F172A?style=flat-square&logo=jsonwebtokens&logoColor=38BDF8)
![Swagger](https://img.shields.io/badge/Swagger-0F172A?style=flat-square&logo=swagger&logoColor=38BDF8)

</td>
<td width="25%" valign="top">

**Architecture**

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-0F172A?style=flat-square&logo=readthedocs&logoColor=A78BFA)
![SOLID](https://img.shields.io/badge/SOLID-0F172A?style=flat-square&logo=codefactor&logoColor=A78BFA)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-0F172A?style=flat-square&logo=blueprint&logoColor=A78BFA)

</td>
<td width="25%" valign="top">

**Tools**

![Git](https://img.shields.io/badge/Git-0F172A?style=flat-square&logo=git&logoColor=38BDF8)
![GitHub](https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=38BDF8)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-0F172A?style=flat-square&logo=visualstudio&logoColor=38BDF8)
![Postman](https://img.shields.io/badge/Postman-0F172A?style=flat-square&logo=postman&logoColor=38BDF8)

</td>
</tr>
</table>

<br/>

## 🚀 Featured Project

<table width="100%">
<tr>
<td>

### 📚 LearnHub — Online Learning Platform (Backend API)

A backend for an online learning platform: course authoring, structured lesson content, enrollments, and reviews — behind a JWT-secured, permission-based authorization layer, with production-facing concerns (background jobs, health checks, structured logging, rate limiting) built in from the start.

**Key Features**
- JWT login with refresh-token rotation, logout with token revocation, and email confirmation on sign-up
- Role-based **and** custom permission-based authorization (`[HasPermission]`) across Admin / Instructor / Member roles
- Course → Section → Lesson management with instructor-ownership checks
- Student enrollment and per-course reviews
- Admin panel: paginated user search, role changes, account enable/disable, lockout unlock
- Background jobs (Hangfire) for async email delivery and scheduled refresh-token cleanup
- Health checks for the database, job store, and mail provider
- Structured Serilog logging that deliberately excludes passwords, tokens, and confirmation codes

**Built With**

`ASP.NET Core (.NET 10)` `EF Core` `SQL Server` `ASP.NET Identity` `JWT` `FluentValidation` `Mapster` `Hangfire` `HybridCache` `Serilog`

<a href="https://github.com/AhmedS3id/LearnHub"><img src="https://img.shields.io/badge/View_Repository-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8" /></a>
<a href="https://learn-hub.runasp.net"><img src="https://img.shields.io/badge/Live_API-0EA5B7?style=for-the-badge&logo=vercel&logoColor=0F172A" /></a>

</td>
</tr>
</table>

<br/>

### 🔍 LearnHub — Technical Showcase

| | |
|---|---|
| **Architecture** | Layered — Controllers → Services → EF Core, with cross-cutting concerns (validation, mapping, auth, errors) wired centrally |
| **Authentication** | JWT access tokens + rotated refresh tokens, ASP.NET Core Identity, custom role + permission-based authorization |
| **Data** | EF Core + SQL Server, `HybridCache` for read-heavy content trees |
| **API** | RESTful, RFC 7807 `ProblemDetails` via a global exception handler, health endpoint at `/health` |
| **Engineering** | Result pattern (no exceptions for expected failures), FluentValidation, Mapster, Hangfire background jobs, IP/user-based rate limiting |

<br/>

## 📦 Other Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

**🗳️ Survey Basket API**
Survey management REST API — question types and poll responses with role-based access, structured around Clean Architecture.
`ASP.NET Core` `EF Core` `SQL Server` `JWT` `Swagger`
<a href="https://github.com/AhmedS3id/Survey_Basket_API"><img src="https://img.shields.io/badge/Repository-0F172A?style=flat-square&logo=github&logoColor=38BDF8" /></a>

</td>
<td width="50%" valign="top">

**🩺 Sakeena**
Backend API for a breast cancer detection platform — secure auth, a scalable service layer, and a schema built around data integrity.
`ASP.NET Core` `EF Core` `SQL Server` `JWT`
<a href="https://github.com/AhmedS3id/BrestCanser"><img src="https://img.shields.io/badge/Repository-0F172A?style=flat-square&logo=github&logoColor=38BDF8" /></a>

</td>
</tr>
</table>

<br/>

## 🏗️ Engineering Mindset

**Clean Architecture** — separation of concerns and maintainable boundaries.
**SOLID** — designing components that are easier to extend and test.
**API Design** — building predictable, well-structured REST APIs.
**Database Design** — thinking about relationships, integrity, and query performance.

<br/>

## 🌱 Current Focus

| 🐳 Docker | 🧩 Microservices | ☁️ Azure | 🧠 System Design |
|---|---|---|---|
| Containerizing services for portable deployments | Breaking monoliths into independently deployable services | Getting hands-on with cloud-hosted .NET workloads | Learning to design for scale before scale becomes the problem |

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AhmedS3id&show_icons=true&theme=tokyonight&bg_color=0F172A&border_color=1E3A8A&hide_border=true&title_color=38BDF8&icon_color=38BDF8&text_color=CBD5E1" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhmedS3id&layout=compact&theme=tokyonight&bg_color=0F172A&border_color=1E3A8A&hide_border=true&title_color=38BDF8&text_color=CBD5E1" height="165"/>

</div>

<br/>

## 📬 Let's Build Something

I'm open to Backend .NET opportunities and freelance API projects — based in Egypt, happy to work with teams anywhere.

<div align="center">

<a href="mailto:ahmeds3id711@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8" /></a>
<a href="https://www.linkedin.com/in/ahmed-said-b006a0269"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=for-the-badge&logo=linkedin&logoColor=38BDF8" /></a>
<a href="https://github.com/AhmedS3id"><img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8" /></a>
<a href="https://wa.me/201028527109"><img src="https://img.shields.io/badge/WhatsApp-0F172A?style=for-the-badge&logo=whatsapp&logoColor=38BDF8" /></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5B7,50:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>

</div>

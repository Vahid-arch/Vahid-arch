# Abdul Vahid

**Full-Stack Developer · .NET · Web and Mobile · E-commerce Technology**

## About

I'm a full-stack developer and e-commerce project manager. I build web applications, REST APIs
and cross-platform mobile apps, and I run the day-to-day operations of the e-commerce business
they serve. That second role shapes the first: requirements come from real orders, real
customers and real operational bottlenecks, not from a specification written at a distance.

My core stack is C#, ASP.NET Core, Entity Framework Core and SQL Server, with Angular, Vue and
Flutter on the client side. I'm completing an Advanced Diploma in Artificial Intelligence and
Machine Learning and moving towards applied AI and intelligent automation.

## Professional experience

**Production e-commerce platform:** development and operations

- Develop and maintain ASP.NET Core APIs and their integrations
- Build web and cross-platform mobile applications on a shared backend and database
- Improve checkout, product workflows and the wider customer journey
- Integrate payments, analytics, conversion tracking and marketing technology
- Support deployment and maintenance on Microsoft Azure; troubleshoot production issues
- Manage products, orders and sales workflows, and align technical work with business goals

**Business applications and client work**

- Built business management and workflow applications
- Delivered websites for business clients, from frontend build to deployment preparation

## Selected public projects

### [OfferDiff](https://github.com/Vahid-arch/offerdiff): catch Google Shopping price mismatches before Google does

Open-source C#/.NET 10 command-line tool that compares a product feed with the schema.org
Product/Offer JSON-LD on each product page, and reports **match**, **mismatch** or **unknown**
per product, with evidence. It targets the Merchant Center "mismatched value (page crawl)"
disapprovals that switch off Shopping ads.

- Live mode checks real stores safely: private-address (SSRF) blocking, 1 request per second per
  site, `Retry-After` handling and robots.txt (RFC 9309)
- Matches offers by URL, then SKU, then single offer; ambiguous or conflicting data is reported
  as unknown, never guessed
- 205 xUnit tests with synthetic fixtures and no real network; CI on Windows and Ubuntu, plus CodeQL
- v0.2.0 released with single-file binaries for Windows, Linux and macOS, built by GitHub Actions
- [Live demo store](https://vahid-arch.github.io/offerdiff/demo/) on GitHub Pages: try it in one command

### [BlueCart](https://github.com/Vahid-arch/bluecart): e-commerce API and storefront

ASP.NET Core API in a layered architecture (API, Core, Infrastructure) with around 50 REST
endpoints for catalogue, categories, cart, orders, users, administration and image upload,
and an Angular storefront.

- Entity Framework Core with SQL Server and code-first migrations
- JWT authentication, role-based admin endpoints, BCrypt password hashing
- FluentValidation for requests, AutoMapper for DTOs, Swagger for API documentation
- Redis caching for admin dashboard statistics; SQL Server and Redis via Docker Compose
- Angular client: shop, product detail, login and admin catalogue management

### [CRM](https://github.com/Vahid-arch/crm): sales CRM with role-based workspaces

Vue 3 application with separate workspaces for administrators and sales representatives.

- Admin: dashboard, team, contacts, deals, activities and reports
- Sales rep: personal dashboard, sales, contacts, activities and reports
- Firebase Authentication and Firestore, role-based route guards, Pinia state management
- Built with Vite and Tailwind CSS

## Technical skills

| | Technologies |
| --- | --- |
| **Backend** | C#, .NET 10, ASP.NET Core, REST APIs, Entity Framework Core, JWT authentication |
| **Frontend** | Vue 3, Angular, TypeScript, JavaScript, HTML, CSS, Tailwind CSS |
| **Mobile** | Flutter, Dart (web and mobile from one codebase) |
| **Data** | SQL Server, Redis, Firebase |
| **Testing and CI** | xUnit, automated testing, GitHub Actions |
| **Cloud and tools** | Microsoft Azure, Docker, Git, GitHub, Swagger |
| **Currently learning** | Python, machine learning, model evaluation |

## Current focus

- Applying machine learning to practical e-commerce and operations problems
- Intelligent automation that removes repetitive work for business and development teams
- Open-source development: adding JavaScript rendering to OfferDiff so it can check modern
  Angular, React and Vue stores

## Contact

[LinkedIn](https://www.linkedin.com/in/abdul-vahid-16870b2b3) · [abdulvahdkv@gmail.com](mailto:abdulvahdkv@gmail.com)

41. How do you deploy Angular app to production?
 By creating optimized builds and deploying via CDN or cloud hosting.
 ----------------------------------------------------------

 42. How do you handle version upgrades safely?
 By upgrading incrementally, reading changelogs, and running tests.
 ----------------------------------------------------------

 43. How do you implement SSR with Angular Universal?
 Using Angular Universal to render pages server-side for performance and SEO.
 ----------------------------------------------------------

 44. When to use Signals vs RxJS?
 Signals for local reactive state, RxJS for async streams and complex flows.
 ----------------------------------------------------------

 45. How do you handle SEO in Angular apps?
 Using SSR, meta services, and pre-rendering.
 ----------------------------------------------------------

 46. How do you optimize bundle size?
 Removing unused dependencies, lazy loading, and using build analyzer.
 ----------------------------------------------------------

 47. How do you handle error pages (404/500)?
 Using wildcard routes and centralized error components.
 ----------------------------------------------------------

 48. How do you manage dark/light themes?
 Using CSS variables and theme toggling via a shared service
 ----------------------------------------------------------

 49. How do you integrate Angular with Microservices backend?
 By consuming APIs via gateways and handling auth and contracts carefully.
 ----------------------------------------------------------

 50. Biggest Angular production issue you solved?
Yes, I faced a circular dependency issue in production that caused DI errors. I resolved it by refactoring shared logic into core services and fixing improper module imports.
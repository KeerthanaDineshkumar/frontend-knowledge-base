 1. How do you improve Angular app performance in production?
I optimize change detection, use lazy loading, OnPush strategy, trackBy in lists, minimize bundle size, and avoid unnecessary API calls
----------------------------------------------------------

 2. When would you use OnPush change detection?
 When my component relies on immutable inputs or observables and doesn’t need frequent UI updates.
 ----------------------------------------------------------

 3. How do you handle large lists efficiently in Angular?
 I use virtual scrolling, pagination, and trackBy to avoid unnecessary DOM re-renders.
 ----------------------------------------------------------

 4. How do you manage state in a complex Angular app?
 I separate local UI state, shared service state, and global state using NgRx or signals.
 ----------------------------------------------------------

 5. When do you prefer NgRx over service-based state?
 When state is shared across many features, needs predictability, undo/redo, or complex side effects.
 ----------------------------------------------------------

 6. How do you handle API errors globally?
 Using HTTP interceptors to catch errors and route them to a common error-handling service.
 ----------------------------------------------------------

 7. How do you implement role-based access in Angular?
 • Authentication service – stores user roles/permissions

• Route Guards – restrict navigation based on roles

• Route metadata – define required roles per route

• Structural directives / UI checks – hide or show UI elements

----------------------------------------------------------

 8. How do you secure routes using Guards?
 I use AuthGuards and RoleGuards to block unauthorized navigation before route activation.
 ----------------------------------------------------------

 9. How do you lazy-load modules and why?
 Using loadChildren to load features only when needed, reducing initial load time.
 ----------------------------------------------------------

 10. How do you share data between unrelated components?
 Using shared services, global state (NgRx), or signals.
 ----------------------------------------------------------
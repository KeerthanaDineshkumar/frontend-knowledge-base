 11. How do you handle memory leaks in Angular?
 By unsubscribing from observables, clearing timers, and removing event listeners on destroy.
 ----------------------------------------------------------

 12. How do you unsubscribe from Observables safely?
 Using takeUntil, AsyncPipe, or DestroyRef in newer Angular versions.
 ----------------------------------------------------------

 13. How do you optimize change detection cycles?
 Using OnPush, immutability, avoiding function calls in templates, and using signals where applicable.
 ----------------------------------------------------------

 14. How do you handle multiple API calls on page load?
 I use forkJoin, combineLatest, or sequential chaining based on dependency.
 ----------------------------------------------------------

 15. How do you cache API responses on frontend?
 Using in-memory caching in services, RxJS shareReplay, or browser storage when needed.
 ----------------------------------------------------------

 16. How do you handle form validation in large forms?
 Using Reactive Forms with reusable validators and form-level validation logic.
 ----------------------------------------------------------

 17. Template-driven vs Reactive Forms – real use case?
 Template-driven for simple forms; Reactive Forms for complex, dynamic, or enterprise-level forms.
 ----------------------------------------------------------

 18. How do you implement dynamic forms?
 By building forms dynamically using FormArray and configuration-driven schemas.
 ----------------------------------------------------------

 19. How do you handle file upload with progress bar?
 Using HttpClient with { reportProgress: true, observe: 'events' }.
 ----------------------------------------------------------

 20. How do you handle pagination & sorting on UI?
 Prefer server-side pagination and sorting for large datasets; client-side for small data.
 ----------------------------------------------------------
# Project memory

## Product intent & audience

- FK Cake Studio: cake business site with online ordering, custom cake enquiry workflow, delivery by pincode with delivery charges, and admin management for orders/products.
- Expected integrations: Supabase (database + auth), Razorpay (payments).

## Brand personality & voice

- Not yet inferred from code or content; no brand assets present.

## Visual design & UX direction

- Not yet inferred; no frontend code present to assess.

## Decisions, constraints & rationale

- User constraint: do not rebuild, modify, delete, or overwrite any existing files; await approval before making changes.
- Do not expose secret keys or credentials in reports.
- Assessment must be based on actual source code, not project description.
- Current project folder is effectively empty for assessment purposes: only `.gitignore`, an empty `package-lock.json`, and a README reading "wealth / buisness". No `package.json`, frontend/backend code, Supabase schema/migrations, Razorpay integration, or `.env`.
- A sibling folder holds version-control internals only; not opened.

## Open questions & assumptions

- Source code needs to be re-imported or uploaded before the technical assessment can proceed.
- Assumption: once real code is present, assessment should cover frontend, backend/API routes, Supabase auth + DB policies, Razorpay integration, ordering & custom cake enquiry workflows, delivery pincode/charge logic, admin management, security vulnerabilities, production-readiness, and missing env vars/config.
- No project-specific env var names, schema, or route structure known yet.
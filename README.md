# Next.js 15 App Directory: Unexpected Routing Behavior

This repository demonstrates an unexpected behavior in Next.js 15's App directory when using client-side routing in combination with server components.  The issue arises when navigating between pages that leverage server components; the data fetching mechanism behaves inconsistently.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the initial page load and subsequent navigation.
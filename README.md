# Next.js 15 App Router Bug: Unexpected Behavior with Function Component Default Export

This repository demonstrates a bug encountered in Next.js 15's App Router when using a function component as the default export in a page file.  The application renders unexpectedly. The issue occurs when a simple functional component is used as the default export in a page file within the `app` directory.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior in the browser.

## Expected Behavior

The application should render "Hello World!" as per the simple functional component's return statement.

## Actual Behavior

The application does not render correctly, or shows a completely different view.
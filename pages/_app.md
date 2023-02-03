This is a custom Next.js app wrapper that adds page-level configurations such as:

Loads NProgress for the page loading animation
Imports the Chakra UI library for styling
Wraps the page with a custom layout component

It listens to Next.js Router events and starts/stops NProgress animations when the route changes. Additionally, it sets the referrer policy for the NProgress stylesheet and wraps the page content with a Chakra UI provider.

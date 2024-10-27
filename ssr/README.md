# Server-Side Rendering with Next.js 🚀

## What is SSR?
**Server-Side Rendering (SSR)** is when the rendering process (converting JavaScript components to HTML) occurs on the **server** before it reaches the client. With SSR, the HTML file you receive is already populated with the content, enhancing performance and user experience.

### Why Use SSR?
- **SEO Optimizations**: Enhances search engine visibility as content is available on page load.
- **Solves the Waterfall Problem**: Allows efficient resource loading without dependencies causing delays.
- **No White Flash**: Content is rendered immediately, creating a seamless experience for users.

### Downsides of SSR
- **Resource-Intensive**: Every request requires rendering on the server, which can increase server costs.
- **Harder to Scale**: SSR is challenging to cache effectively with CDNs, as each page request needs a fresh server render.

## Setting Up a Next.js SSR App ⚙️

Follow these steps to set up a Next.js app with SSR:

1. **Create a Next.js app**:
   ```bash
   npx create-next-app

2. **Build the project**:
   ```bash
   npm run build
   
3. **Start the Next.js server**:
   ```bash
   npm run start 
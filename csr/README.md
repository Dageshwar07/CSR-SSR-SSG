# Client-Side Rendering with React ⚛️

## What is CSR?
**Client-Side Rendering (CSR)** is a modern web development technique where the rendering of a webpage happens directly in the **browser** using JavaScript. Instead of the server delivering a fully rendered HTML page, the client browser receives a minimal HTML file and JavaScript handles rendering the content on the page.

### Why Use CSR?
- **Developer-Friendly**: Tools like React make development easy by allowing you to write components, and JavaScript handles rendering them into the DOM.
- **Responsive Interfaces**: CSR is ideal for building interactive and dynamic user interfaces, as JavaScript is directly in control of the DOM.

### Downsides of CSR
- **Limited SEO Optimization**: Search engines may struggle to index content effectively since the initial HTML file is empty.
- **Flash of Unrendered Content (FOUC)**: Users may see a blank or incomplete page until JavaScript finishes loading.
- **Waterfall Problem**: Resources load sequentially, leading to possible delays in rendering.

## Setting Up a React CSR Project ⚙️

Follow these steps to set up a simple React project with CSR:

1. **Initialize a React project with Vite**:
   ```bash
   npm create vite@latest

2. **Install dependencies:**:
   ```bash
   npm i

3. **Build the project**:
   ```bash
   npm run build   

4. **Serve the project**:
   ```bash
   cd dist/
   serve

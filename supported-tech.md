# Supported Technologies in Bolt.new

## JavaScript Frameworks

### Frontend Frameworks

| Framework | Support Level | Notes |
|-----------|---------------|-------|
| React     | Full | Includes React Router, React Query, Redux, and other ecosystem tools |
| Next.js   | Full | Supports App Router, Pages Router, and most Next.js features |
| Vue.js    | Full | Vue 3 with Composition API and Options API |
| Nuxt.js   | Full | Nuxt 3 with most features supported |
| Angular   | Full | Angular 15+ with component architecture and routing |
| Svelte    | Full | Svelte and SvelteKit with most features |
| Astro     | Full | Static site generation and island architecture |
| Solid.js  | Full | Reactive programming model with fine-grained reactivity |
| Qwik      | Good | Resumable applications with most features |
| Lit       | Good | Web components library |

### CSS Frameworks/Libraries

| Framework | Support Level | Notes |
|-----------|---------------|-------|
| Tailwind CSS | Full | Complete support with plugins |
| Bootstrap    | Full | Both CSS and component libraries |
| Material UI  | Full | React component library |
| Chakra UI    | Full | React component library |
| ShadCN UI    | Full | React component library based on Radix UI |
| DaisyUI      | Full | Tailwind CSS component library |
| Styled Components | Full | CSS-in-JS solution |
| Emotion      | Full | CSS-in-JS library |
| CSS Modules  | Full | Scoped CSS for component-based architectures |
| SASS/SCSS    | Full | CSS preprocessor |

### Backend Frameworks

| Framework | Support Level | Notes |
|-----------|---------------|-------|
| Express.js | Full | HTTP server framework |
| Fastify    | Full | Performance-focused server framework |
| NestJS     | Full | Progressive Node.js framework |
| Hono       | Good | Lightweight, ultrafast web framework |
| Koa        | Good | Next generation web framework by Express team |
| Socket.io  | Good | Real-time bidirectional event-based communication |

### Full-Stack Frameworks

| Framework | Support Level | Notes |
|-----------|---------------|-------|
| Next.js   | Full | With API routes and server components |
| Nuxt.js   | Full | Vue-based full-stack framework |
| Remix      | Good | React-based full-stack framework |
| SvelteKit  | Good | Svelte-based full-stack framework |
| Meteor     | Limited | JavaScript platform for building web applications |

## Database and Storage

### Supabase Integration

| Feature | Support Level | Notes |
|---------|---------------|-------|
| PostgreSQL Database | Full | Tables, views, functions, and triggers |
| Authentication | Full | Email/password, OAuth, magic links |
| Storage | Full | File storage with security rules |
| Realtime | Good | Database changes subscription |
| Edge Functions | Good | Serverless functions |

### Other Database Options

| Database | Support Level | Notes |
|----------|---------------|-------|
| SQLite   | Full | In-memory or file-based relational database |
| MongoDB (via Mongoose) | Limited | NoSQL database with ODM |
| Prisma   | Good | ORM for various database engines |
| Drizzle  | Good | TypeScript ORM |
| Kysely   | Good | Type-safe SQL query builder |

## Mobile Development

### Expo Integration

| Feature | Support Level | Notes |
|---------|---------------|-------|
| React Native | Good | Cross-platform mobile development |
| Expo SDK | Good | Access to device APIs |
| Expo Router | Good | File-based routing |
| Development Builds | Limited | Custom native code support |

## Deployment Options

### Netlify Integration

| Feature | Support Level | Notes |
|---------|---------------|-------|
| Static Site Deployment | Full | For static sites and SPAs |
| Serverless Functions | Full | Backend functionality without servers |
| Forms | Full | Form handling without server-side code |
| Authentication | Full | Identity service |
| Redirects/Rewrites | Full | URL management |

## Testing Frameworks

| Framework | Support Level | Notes |
|-----------|---------------|-------|
| Jest      | Good | JavaScript testing framework |
| Vitest    | Good | Vite-native testing framework |
| React Testing Library | Good | For testing React components |
| Cypress   | Limited | End-to-end testing framework |
| Playwright | Limited | End-to-end testing framework |

## Build Tools

| Tool | Support Level | Notes |
|------|---------------|-------|
| Vite | Full | Next-generation frontend build tool |
| Webpack | Full | Module bundler |
| esbuild | Full | JavaScript bundler |
| Turbopack | Good | Incremental bundler in Rust |
| Parcel | Good | Zero-configuration web application bundler |

## API Integrations

### Third-Party APIs

| Category | Support Level | Notes |
|----------|---------------|-------|
| Payment (Stripe, PayPal) | Good | Integration capabilities for e-commerce |
| Authentication (Auth0, Clerk) | Good | User authentication and management |
| Maps (Google Maps, Mapbox) | Good | Location and mapping services |
| Email (SendGrid, Mailchimp) | Good | Email delivery and marketing |
| CMS (Contentful, Sanity) | Good | Content management systems |
| AI Services (OpenAI, Anthropic) | Good | AI and machine learning APIs |

## State Management

| Library | Support Level | Notes |
|---------|---------------|-------|
| Redux   | Full | Predictable state container |
| Zustand | Full | Small, fast state management |
| Jotai   | Full | Primitive and flexible state management |
| XState  | Good | State machines and statecharts |
| MobX    | Good | Simple, scalable state management |
| React Query | Full | Async state management for React |

## Language Support

| Language | Support Level | Notes |
|----------|---------------|-------|
| JavaScript | Full | Modern ES6+ |
| TypeScript | Full | Static typing with full type inference |
| JSX/TSX    | Full | React templating syntax |

## Other Tools & Libraries

| Category | Support Level | Notes |
|----------|---------------|-------|
| i18n/Internationalization | Good | Multi-language support |
| Accessibility Libraries | Good | Tools for creating accessible applications |
| Animation Libraries | Full | Framer Motion, GSAP, etc. |
| Date Management | Full | date-fns, Day.js, etc. |
| Form Handling | Full | React Hook Form, Formik, etc. |

## Browser Compatibility

| Browser | Support Level | Notes |
|---------|---------------|-------|
| Chrome  | Full | Primary development target |
| Edge    | Full | Chromium-based Edge fully supported |
| Firefox | Limited | Some features may have issues |
| Safari  | Limited | Some features may have issues |
| Mobile Browsers | Good | Responsive design support |

## Notes on Support Levels

- **Full**: Comprehensive support with all standard features working as expected
- **Good**: Most features work well with occasional limitations
- **Limited**: Basic functionality works but may have significant limitations
- **Experimental**: Early support with potential instability

Frameworks and libraries not listed here may still work but haven't been extensively tested within bolt.new. The WebContainers technology generally supports standard Node.js/npm packages, but performance and compatibility can vary.
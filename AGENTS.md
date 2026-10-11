# PROJECT: Premium Multi-Brand Luxury Fashion & Lifestyle Marketplace

## 1. YOUR ROLE

Act as a senior product designer, luxury e-commerce art director, UX architect, senior frontend engineer, senior backend engineer, database architect, security engineer, and technical lead.

You are responsible for designing and implementing a complete, functional, production-oriented luxury fashion and lifestyle marketplace.

Do not behave like a generic website generator.

Think carefully about the visual identity, customer journey, component architecture, data model, business rules, security, performance, and maintainability before implementing each feature.

The final product must feel like a thoughtfully art-directed luxury fashion platform created by an experienced design and engineering team.

## 2. PRODUCT VISION

Build a multi-brand luxury fashion and lifestyle marketplace connecting customers with authorized brands and sellers.

The marketplace sells:

* Luxury clothing and apparel.
* Men's and women's fashion.
* Footwear.
* Handbags and leather goods.
* Accessories.
* Watches and jewellery.
* Beauty and fragrance.
* Premium gifts.
* Home decor and lifestyle products.
* Limited-edition collections.

The platform has three principal user groups:

1. Customers.
2. Sellers and brand managers.
3. Platform administrators.

Customers discover and purchase products.

Sellers manage listings, variants, inventory, and fulfillment.

Administrators manage sellers, brand approvals, product moderation, orders, commissions, and platform operations.

The architecture must support a multi-seller commerce model rather than a single-store shopping cart.

## 3. DESIGN PHILOSOPHY

The customer-facing website must embody:

* Quiet luxury.
* Editorial fashion publishing.
* Sophisticated art direction.
* Premium product presentation.
* Generous whitespace.
* Excellent typography.
* Refined interactions.
* High-quality fashion photography.
* Minimal visual clutter.
* A consistent, recognizable design identity.

The website should feel like a luxury fashion publication combined with a premium shopping experience.

It must NOT look like a generic AI-generated website, SaaS landing page, marketplace template, or ordinary discount e-commerce store.

Avoid:

* Excessive rounded cards.
* Purple-blue gradients.
* Unnecessary glassmorphism.
* Random floating decorations.
* Excessive drop shadows.
* Generic centered hero layouts.
* Repetitive card-based layouts.
* Emoji used as interface icons.
* Excessive animation.
* Arbitrary font combinations.
* Unnecessary badges and decorative labels.
* Fake reviews, fake certifications, and unsupported trust claims.
* Identical visual treatment for every section.

Every design choice must serve the brand, content, or shopping journey.

## 4. VISUAL DESIGN SYSTEM

Begin with a restrained luxury palette:

* Warm ivory: #F7F5F0.
* Near-black: #171715.
* Muted charcoal: #77746E.
* Antique bronze: #9A805B.
* Neutral borders: #E7E2D9.
* White: #FFFFFF.

Treat these as initial design tokens and refine them after evaluating the complete visual composition.

Typography:

* Use an editorial serif for prominent headings.
* Use a clean sans-serif for body text and controls.
* Establish a clear hierarchy between display headings, section headings, product names, labels, and supporting information.
* Use consistent line heights, spacing, and letter spacing.
* Avoid excessive uppercase text.

Layout:

* Use an intentional spacing system.
* Establish consistent page gutters and maximum content widths.
* Use asymmetrical editorial layouts where appropriate.
* Allow large images to dominate campaign sections.
* Use restrained dividers and carefully aligned elements.
* Make mobile layouts feel intentionally designed rather than compressed desktop layouts.

Components:

* Design buttons, inputs, menus, dialogs, product cards, filters, breadcrumbs, tabs, and pagination as a coherent system.
* Use consistent focus, hover, active, disabled, loading, and error states.
* Maintain accessible contrast and keyboard navigation.

Motion:

* Use subtle, purposeful transitions.
* Animate image reveals and navigation only when they improve the experience.
* Respect reduced-motion preferences.
* Avoid animation that delays browsing, navigation, or checkout.

## 5. PHOTOGRAPHY AND ART DIRECTION

Photography is a first-class part of the design.

Use carefully curated fashion campaign imagery and premium product photography.

The homepage should combine:

* An impactful campaign image.
* Editorial typography.
* Curated collections.
* Brand storytelling.
* Product discovery.
* Large, visually consistent product imagery.

Use images that have a coherent photographic direction, appropriate crops, and consistent visual quality.

Do not use random unrelated stock photographs.

Do not rely on empty placeholders or broken image URLs.

If licensed photography is not available during development:

* Use appropriately licensed demonstration imagery or original generated imagery.
* Centralize image references in a maintainable content file.
* Make it easy to replace demonstration assets.
* Never present demonstration products as authenticated luxury goods.
* Do not copy another brand's website or assets without permission.

Create a photography specification covering aspect ratios, crop behavior, product background treatment, image resolution, and responsive delivery.

## 6. REQUIRED CUSTOMER WEBSITE

Implement these public pages:

1. Homepage.
2. Shop all.
3. Men's fashion.
4. Women's fashion.
5. Clothing.
6. Footwear.
7. Bags and accessories.
8. Watches and jewellery.
9. Beauty and fragrance.
10. Home and lifestyle.
11. Brand directory.
12. Brand detail and brand collections.
13. Product listing pages.
14. Product detail pages.
15. Search results.
16. Shopping cart.
17. Checkout.
18. Order confirmation.
19. Customer login and registration.
20. Password recovery.
21. Customer account.
22. Address management.
23. Order history.
24. Order details and tracking.
25. Wishlist.
26. Return requests.
27. Fashion journal and editorial stories.
28. FAQ and customer support.
29. Shipping, return, privacy, and terms pages.
30. Custom 404 and error pages.

Every route must have a deliberate layout and appropriate content.

Do not create dozens of empty pages simply to claim that every route exists.

## 7. HOMEPAGE ART DIRECTION

The homepage is the primary brand experience.

Design it as an editorial fashion experience rather than a standard e-commerce landing page.

Recommended structure:

1. A refined announcement strip, if needed.
2. Elegant navigation with a wordmark, shop navigation, search, account, wishlist, and bag.
3. A campaign hero using high-quality fashion photography.
4. A prominent but restrained campaign headline.
5. A carefully designed collection navigation.
6. An editorial new-arrivals section.
7. A curated brand showcase.
8. A visually distinctive fashion story.
9. A premium lifestyle or accessories edit.
10. A second campaign or seasonal collection.
11. A restrained newsletter section.
12. A refined footer with customer service, brand information, policies, and social links.

The hero must have strong art direction, appropriate typography, deliberate text placement, and a composition that works on mobile.

Do not place every section inside a rounded container.

Vary the composition of the page while preserving the overall design system.

Use realistic product and brand content. Do not invent endorsements or claims of official brand partnerships.

## 8. PRODUCT LISTING EXPERIENCE

Create sophisticated product listing pages with:

* Category heading and description.
* Breadcrumbs.
* Product count.
* Responsive product grid.
* Brand filtering.
* Category filtering.
* Size filtering.
* Color filtering.
* Price filtering.
* Availability filtering.
* Sorting.
* Pagination or an appropriate progressive-loading strategy.
* Active filter indicators.
* Clear-all filters.
* Empty states.
* Loading states.
* Error recovery.

Filters should be reflected in URL search parameters where appropriate.

Product cards must include:

* Consistent product photography.
* Brand name.
* Product name.
* Price and currency.
* Appropriate sale-price presentation.
* Available color information when useful.
* Wishlist control.
* Optional new-arrival or limited-edition labels when supported by real data.

Use a restrained hover interaction, such as revealing an alternate product image when one exists.

Avoid cluttering product cards with unnecessary buttons, ratings, badges, and text.

## 9. PRODUCT DETAIL EXPERIENCE

Create a premium product detail page with:

* Large image gallery.
* Thumbnail navigation.
* Appropriate zoom behavior.
* Brand name.
* Product title.
* Price.
* Product description.
* Color selection.
* Size selection where applicable.
* Size guide.
* Material and care details.
* Variant-specific availability.
* Quantity selection when appropriate.
* Add-to-cart action.
* Wishlist action.
* Delivery information.
* Returns information.
* Product specifications.
* Reviews where actual reviews exist.
* Related products.
* Recently viewed products where appropriate.

The selected variant must be represented correctly.

The backend must validate the selected seller listing, price, and inventory before checkout.

## 10. CART AND CHECKOUT

Implement a functional cart and checkout experience.

The cart must support:

* Add item.
* Remove item.
* Update quantity.
* Variant display.
* Availability validation.
* Price updates.
* Subtotal.
* Applicable discounts.
* Shipping estimate.
* Final payable total.
* Empty cart state.

Checkout must support:

* Customer identity.
* Delivery address.
* Delivery option where applicable.
* Order summary.
* Server-calculated totals.
* Payment initiation.
* Payment result handling.
* Order confirmation.

Never trust prices, discounts, inventory, or final totals submitted by the browser.

Do not treat a browser redirect as proof that payment succeeded.

Verify payments using the payment provider's authenticated webhook or other trusted server-side verification mechanism.

Use idempotency controls for order creation and payment operations.

For local development, provide a clearly identified mock payment adapter or provider sandbox. Never simulate a successful real payment in production.

## 11. SELLER PORTAL

Implement a separate seller experience using the same design system, with an operational layout suitable for frequent use.

Features:

* Seller application.
* Seller profile.
* Business verification status.
* Brand association and approval.
* Product listing management.
* Product variants and SKUs.
* Inventory management.
* Listing status.
* Seller orders.
* Fulfillment status.
* Shipment tracking.
* Return requests.
* Commission records.
* Payout history.
* Basic sales analytics.

A seller must only access resources belonging to their authorized seller account.

Support multiple users within a seller account where appropriate.

Do not rely on frontend route guards alone for seller authorization.

## 12. ADMIN PORTAL

Implement an administrator experience with:

* Overview dashboard.
* Customer management.
* Seller management.
* Seller verification.
* Brand management.
* Product moderation.
* Category management.
* Order management.
* Return and refund workflows.
* Commission configuration.
* Seller settlement visibility.
* Coupon and promotion management.
* Editorial content management.
* Audit logs.
* Basic reporting.

Use role-based and permission-based access controls.

Sensitive financial operations must be auditable.

The admin dashboard may be more information-dense than the storefront, but it must remain consistent, usable, and accessible.

## 13. TECHNOLOGY STACK

Use a TypeScript monorepo.

Customer storefront:

* Next.js.
* React.
* TypeScript.
* Tailwind CSS.

Seller and administrator interfaces:

* Next.js routes and shared components.

Backend:

* Node.js.
* Express.
* TypeScript.

Database:

* PostgreSQL.
* Prisma ORM.
* Version-controlled migrations.

Validation:

* Zod.
* Shared schemas and types where appropriate.

Forms:

* React Hook Form.

Client-side server state:

* TanStack Query where appropriate.

Background jobs:

* Redis and BullMQ when required.

Media:

* Object storage with a replaceable storage adapter.
* CDN integration in production.

Testing:

* Vitest.
* Supertest.
* Playwright.

Documentation:

* OpenAPI.
* Architecture documentation.
* Database documentation.

Choose stable, mutually compatible package versions and commit the lockfile.

Avoid introducing unnecessary dependencies.

## 14. BACKEND ARCHITECTURE

Implement a modular monolith with clear business boundaries.

Modules should include:

* Authentication.
* Users.
* Customer profiles.
* Sellers.
* Brands.
* Categories.
* Products.
* Product variants.
* Seller listings.
* Inventory.
* Cart.
* Checkout.
* Orders.
* Payments.
* Shipments.
* Returns.
* Refunds.
* Commissions.
* Seller payouts.
* Coupons.
* Reviews.
* Wishlist.
* Notifications.
* Audit logging.

Use a consistent separation of:

* Routes.
* Controllers.
* Services.
* Repositories.
* Validation schemas.
* External provider adapters.

Use versioned REST endpoints under /api/v1.

Return consistent error responses and appropriate HTTP status codes.

Validate incoming requests on the server.

Implement request correlation IDs and structured logging.

Do not expose internal errors, stack traces, secrets, or sensitive database information to customers.

## 15. DATABASE ARCHITECTURE

Design a relational database with appropriate foreign keys, indexes, unique constraints, and transactions.

At minimum, model:

* Users.
* Roles and permissions.
* Customer profiles.
* Addresses.
* Sellers.
* Seller memberships.
* Brands.
* Seller-brand relationships.
* Categories.
* Products.
* Product variants.
* Product media.
* Seller listings.
* Inventory locations.
* Inventory records.
* Inventory reservations.
* Inventory movements.
* Carts.
* Cart items.
* Orders.
* Order items.
* Seller orders.
* Payments.
* Payment events.
* Shipments.
* Returns.
* Refunds.
* Commissions.
* Seller payouts.
* Coupons.
* Reviews.
* Wishlists.
* Audit logs.

Keep products, product variants, seller listings, and inventory separate.

A product is the underlying catalog item.

A variant represents a specific configuration such as size and color.

A seller listing represents an individual seller's offer for a variant.

Inventory represents available stock for the relevant listing and location.

Store immutable snapshots of relevant product names, SKUs, prices, currency, and tax details in order records.

Use appropriate decimal or integer-based monetary representations.

Use database transactions and concurrency controls for critical stock and order operations.

Never represent payment success merely by changing a frontend variable.

## 16. AUTHENTICATION AND SECURITY

Implement secure authentication using HTTP-only cookies and an appropriate server-side session strategy.

Include:

* Registration.
* Login.
* Logout.
* Session validation.
* Password hashing.
* Email verification.
* Password recovery.
* Session expiration.
* Rate limiting.
* CSRF protection where applicable.
* Secure cookie configuration.
* Authorization middleware.
* Seller resource ownership checks.
* Administrator permissions.
* Input validation.
* Output sanitization where appropriate.
* Secure file uploads.
* Audit logging.

Use a maintained password-hashing implementation such as Argon2id where supported by the deployment environment.

Never store plaintext passwords.

Never commit real credentials.

Provide .env.example with placeholder values only.

Do not expose private environment variables to the browser.

Protect sensitive customer and seller data.

## 17. INVENTORY AND ORDER CONSISTENCY

Implement explicit order and payment states.

Prevent overselling using transactional inventory reservations or appropriate atomic database updates.

Handle:

* Concurrent purchases.
* Expiring inventory reservations.
* Payment failures.
* Duplicate webhooks.
* Delayed webhooks.
* Cancelled orders.
* Partial fulfillment.
* Partial returns.
* Refunds.
* Failed background jobs.

Use idempotency for operations that may be retried.

Store payment provider event identifiers to prevent duplicate processing.

Maintain auditable inventory movements and financial adjustments.

Never assume that a successful HTTP response means every downstream operation has completed.

## 18. MARKETPLACE ORDER MODEL

Support one customer checkout containing products from multiple sellers.

Represent the customer-facing order separately from seller-specific fulfillment orders.

Each seller order may have its own:

* Fulfillment status.
* Shipment.
* Tracking number.
* Cancellation eligibility.
* Return workflow.
* Commission record.
* Settlement state.

Calculate commissions using explicit business rules.

Do not invent production settlement rules. Document assumptions and make them configurable.

Do not initiate actual seller payouts until the payment and settlement model has been reviewed and the relevant provider integration is configured.

## 19. SEARCH AND DISCOVERY

Begin with PostgreSQL-backed search and filtering.

Implement:

* Search by product name and brand.
* Category filtering.
* Brand filtering.
* Size filtering.
* Color filtering.
* Price filtering.
* Availability filtering.
* Sorting.
* Pagination.

Use indexed queries and avoid loading the entire product catalog into memory.

Keep the search implementation behind a service boundary so a dedicated search engine can be added later.

Revalidate price and availability against the authoritative database during checkout.

## 20. PERFORMANCE AND SEO

Optimize for:

* Fast initial rendering.
* Responsive image delivery.
* Appropriate image formats.
* Lazy loading below the fold.
* Limited client-side JavaScript.
* Minimal layout shift.
* Efficient database queries.
* Appropriate caching.
* Mobile usability.

Use server rendering for public product and category pages where appropriate.

Implement:

* Unique metadata.
* Canonical URLs.
* Sitemap.
* Robots directives.
* Product structured data based on actual product information.
* Open Graph metadata.
* Semantic HTML.
* Accessible navigation.
* Proper image alt text.

Never mark unavailable or incorrectly priced products as available in structured data.

## 21. TESTING

Create automated tests for critical workflows.

Unit tests:

* Price calculations.
* Discounts.
* Commission calculations.
* Order state transitions.
* Inventory calculations.
* Validation rules.

Integration tests:

* Authentication.
* Seller permissions.
* Product APIs.
* Cart.
* Checkout.
* Order creation.
* Payment webhooks.
* Refunds.

End-to-end tests:

* Customer registration.
* Product discovery.
* Variant selection.
* Add to cart.
* Checkout.
* Test payment.
* Order history.
* Seller inventory updates.
* Admin product approval.

Test negative scenarios, including:

* Invalid credentials.
* Unauthorized access.
* Insufficient stock.
* Invalid coupons.
* Duplicate requests.
* Payment failure.
* Duplicate webhooks.
* Cross-customer order access.
* Cross-seller resource access.

## 22. DEVELOPMENT AND DEPLOYMENT

Provide:

* A clear monorepo structure.
* Reproducible dependency installation.
* Local PostgreSQL setup.
* Optional Docker Compose.
* Prisma migrations.
* Deterministic seed data.
* .env.example.
* Development scripts.
* Linting.
* Type checking.
* Unit tests.
* Integration tests.
* Production build commands.
* API documentation.
* Setup instructions.

The application must run locally without requiring paid external services.

Use local development adapters or explicit mock integrations for services that have not been configured.

Keep mock integrations separate from production adapters.

Fail safely when required production credentials are missing.

Never silently substitute a mock payment provider in production.

## 23. ENGINEERING RULES

Follow these rules throughout development:

1. Inspect the repository before changing files.
2. Preserve working functionality.
3. Do not overwrite existing work without understanding it.
4. Build reusable components and clear module boundaries.
5. Avoid giant components and monolithic service files.
6. Avoid duplicated business logic.
7. Use TypeScript types instead of unnecessary any usage.
8. Validate untrusted inputs.
9. Keep business rules on the backend.
10. Use database transactions where required.
11. Document architectural decisions.
12. Do not fabricate API responses or pretend integrations are functional.
13. Do not leave dead buttons or misleading success messages.
14. Do not suppress errors merely to make the application appear functional.
15. Run tests and type checks after meaningful changes.
16. Fix implementation errors before proceeding to dependent phases.
17. Keep the lockfile and database migrations consistent.
18. Do not expose secrets or personal data in logs.
19. Prefer the simplest reliable solution that meets the requirements.
20. Keep the customer-facing visual design consistent with the established luxury identity.

## 24. REQUIRED WORKFLOW

Do not attempt to implement the entire marketplace in one enormous code-generation step.

Work incrementally.

PHASE 1:
Inspect the repository, establish assumptions, document architecture, define the design system, and create the implementation plan.

PHASE 2:
Implement the visual foundation and customer storefront using realistic catalog data.

PHASE 3:
Implement the PostgreSQL schema, migrations, seed data, and backend infrastructure.

PHASE 4:
Implement authentication, customer profiles, seller accounts, and authorization.

PHASE 5:
Implement catalog, product variants, seller listings, inventory, and search.

PHASE 6:
Implement cart, checkout, orders, and inventory reservations.

PHASE 7:
Implement a safe payment adapter and provider sandbox integration.

PHASE 8:
Implement seller and administrator workflows.

PHASE 9:
Implement returns, refunds, commissions, notifications, and operational tooling.

PHASE 10:
Run end-to-end tests, review security, fix visual inconsistencies, and prepare deployment documentation.

At the beginning of each phase, state the objectives and files likely to change.

After each phase:

* Summarize implemented functionality.
* List files created or changed.
* Report commands executed.
* Report tests and their results.
* Identify known limitations.
* Identify the next phase.
* Do not claim a feature works unless it has been verified.

## 25. DEFINITION OF DONE

The project is not complete merely because the homepage renders.

The initial marketplace release should have:

* A coherent luxury visual identity.
* Responsive public pages.
* Functional product browsing.
* Search and filters.
* Product variants.
* Authentication.
* Persistent cart.
* Server-side price validation.
* Inventory management.
* Checkout.
* Orders.
* A safe test-payment workflow.
* Seller access controls.
* Product management.
* Administrative moderation.
* Automated database migrations.
* Seed data.
* API documentation.
* Automated tests.
* Setup documentation.

All major controls must have meaningful behavior.

All implemented routes must have appropriate loading, empty, success, and error states.

The application must be reproducible from the documented setup process.

The final design must feel intentionally art-directed rather than assembled from generic templates.

## 26. YOUR FIRST ACTION

Do not immediately generate the entire application.

First inspect the repository and identify:

* Existing files.
* Existing frameworks.
* Current dependency configuration.
* Existing database or API setup.
* Available assets.
* Existing implementation constraints.

Then produce:

1. A concise architecture proposal.
2. A proposed directory structure.
3. A design-system specification.
4. A database entity plan.
5. A phased implementation checklist.
6. Any important assumptions that need to be resolved.

After that, begin with the first implementation phase and verify each milestone before continuing.

Prioritize visual quality, architectural consistency, working functionality, and secure commerce behavior equally.

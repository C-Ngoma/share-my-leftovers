Share My Leftovers

## Project idea

Share My Leftovers is a planned website, with the possibility of becoming a mobile app later. It helps people who have safely prepared more food than they need connect with nearby people who would like to collect it.

The aim is to make surplus food easier to share within a community, reduce avoidable food waste, and help people find food that is available nearby. This document describes the product idea and an initial plan. It does not contain a website or app implementation.

## The problem

People sometimes cook more food than they can eat. At the same time, someone nearby may appreciate that food. Today, it can be difficult to find each other quickly and safely. Informal posts may be scattered across group chats and social media, and important details such as ingredients, quantity, collection time, and whether the food is still available may be missing.

## Who it is for

- **Food sharers:** people, households, community groups, or other approved providers with surplus prepared food.
- **People collecting food:** neighbours or community members who want to find and request available food.
- **Moderators:** people responsible for reviewing reports, handling unsafe or misleading listings, and supporting a trustworthy community.

The first release should focus on a small, local community and learn from real usage before expanding.

## Product principles

1. **Safety comes first.** The service should make food details and collection expectations clear. It should not imply that a listing has been inspected or certified.
2. **Sharing is voluntary.** A listing does not guarantee that food will be available, suitable for every person, or delivered.
3. **Privacy matters.** Do not display a sharer's home address publicly. Share precise collection details only after an appropriate request is accepted.
4. **Keep it simple.** Make it easy to post food, find nearby listings, and coordinate collection.
5. **Be respectful and inclusive.** Use clear, non-judgmental language and make the service usable by people with different needs and levels of technical confidence.
6. **Plan for accountability.** Provide a way to report a listing or user and a clear process for responding.

## Initial user journeys

### Share food

1. The sharer creates an account or signs in.
2. They add a listing with a short title, description, approximate amount or number of portions, preparation date and time, collection window, and general area.
3. They disclose known ingredients and allergens, storage conditions, and any other relevant handling information. The form should explain that accurate disclosure is the sharer's responsibility.
4. They publish the listing.
5. They receive a request and accept or decline it.
6. After accepting, they coordinate collection using the service's chosen private contact method.
7. They mark the listing as collected, expired, or unavailable.

### Find and request food

1. The collector browses available listings by area and collection time.
2. They review the food description, amount, ingredients/allergen information, and collection conditions.
3. They request the listing and can include a short note or relevant question.
4. If accepted, they receive the collection details and confirm collection.
5. They can report a concern or provide feedback after the interaction.


### Moderate and report

1. A user reports a listing or account and chooses a reason.
2. A moderator reviews the report and can contact the user, hide the listing, or take another documented action.
3. The system records the action and provides a way to appeal or ask for help, if appropriate.

## MVP scope

The first version should answer one question: can a simple local service help people share surplus prepared food reliably and respectfully?

### Include in the first release

- Account creation and sign-in.
- Basic user profiles and a way to contact support.
- Create, edit, pause, and remove a food listing.
- Listing details for description, quantity, preparation time/date, collection window, approximate area, and known ingredients/allergens.
- Browse and filter available listings by area and availability.
- Request, accept, decline, and cancel a collection.
- Listing status: available, requested, reserved, collected, expired, or unavailable.
- Private coordination of collection details.
- Report listing/user and a basic moderator workflow.
- Clear community guidelines, privacy information, and terms to review with appropriate local expertise before launch.

### Leave for later

- Native iOS and Android apps.
- Delivery or courier matching.
- Payments, selling food, or donations through the platform.
- Ratings, badges, and public reputation scores.
- Automated matching or recommendations.
- Large-scale maps or precise real-time location tracking.
- Multi-region launch, translations, and complex organisation accounts.

## Important product decisions

These decisions should be made before implementation or a pilot:

- **Who may post?** Individuals only at first, or also community kitchens, restaurants, and organisations?
- **What food is allowed?** Define eligible and ineligible food categories with local food-safety expertise.
- **Is sharing free?** Decide whether the platform will prohibit payment, allow optional contributions, or support another model.
- **What areas are served?** Start with a limited neighbourhood or community and define how location is represented.
- **How are collection details shared?** Choose a privacy-preserving approach and set expectations for timely collection.
- **How are no-shows handled?** Decide when a reservation expires and when a listing returns to available.
- **How will reports be handled?** Set moderator coverage, response expectations, and escalation steps.
- **What personal information is necessary?** Collect as little as possible and define retention and deletion rules.
- **What does the platform promise?** Explain clearly that it connects people but does not inspect food or guarantee its quality or suitability.

## Safety, trust, and privacy planning

Food sharing has real safety and trust considerations. Before a public launch, define the rules with qualified local guidance and make them visible during listing creation and collection. At minimum, plan for:

- Clear disclosure of known ingredients and allergens, preparation timing, storage details, and collection timing.
- Rules about which foods may be listed and how long a listing may remain available.
- No public display of exact home addresses or personal phone numbers by default.
- A report-and-response process for suspected unsafe food, harassment, scams, and repeated no-shows.
- Account security, data access controls, deletion requests, and limited retention of personal information.
- Terms and privacy notices reviewed for the places where the service will operate.

This README is a product-planning document, not food-safety, legal, or regulatory advice. Local requirements need to be researched before the service launches.

## Possible website-to-app path

1. **Plan:** decide the launch community, rules, user journeys, and success measures.
2. **Prototype:** sketch the main screens and test the flow with a few potential users.
3. **Pilot website:** build a responsive website for one community and learn from actual listings and collections.
4. **Improve:** address safety, moderation, accessibility, and operational issues found in the pilot.
5. **Consider an app:** build a mobile app only if users need app-specific features and the website pilot shows sustained use.

Keeping the early product as a responsive website can make it easier to test the idea before committing to separate mobile apps.

## Early success measures

Track whether the service is useful and dependable, not just how many people sign up. Possible measures include:

- Listings that receive at least one request.
- Requests that result in a completed collection.
- Time between publishing and a successful request.
- Listings that expire or are cancelled, and why.
- Reports, no-shows, and safety concerns per completed collection.
- Repeat sharers and collectors.
- Feedback on clarity, trust, and ease of use.

Use privacy-conscious, aggregate reporting where possible. Avoid collecting data just because it might be useful later.

## Open questions for the founder

- Which town, neighbourhood, or community should the pilot serve?
- Is the first audience households, community groups, food businesses, or a combination?
- Should collectors need accounts, or should browsing be open to everyone?
- Should requests be first-come-first-served, or should the sharer choose among requests?
- What languages should the first version support?
- How will the service be funded and moderated?
- What evidence would show that it is ready to grow or become an app?

## Working definition of done for the plan

Before building, aim to have:

- A chosen pilot area and target users.
- Agreed listing rules and a food-safety review plan.
- A mapped sharer, collector, and moderator journey.
- A decision on privacy and contact details.
- A simple clickable or paper prototype reviewed by potential users.
- A moderation and support plan for the pilot.
- A short list of success measures and a date to review the pilot.

## Project charter for the first build cycle

This README is the project charter for the website-first pilot. For the first build cycle, the following are fixed:

- **Vision:** reduce avoidable food waste by helping nearby people share safely prepared surplus food.
- **Target users:** local food sharers, local collectors, and moderators.
- **MVP scope:** account access, listings, request/accept flow, listing status updates, private coordination, and basic reporting/moderation.
- **Out of scope for now:** native apps, delivery matching, payments, reputation systems, and multi-region complexity.

Open questions and success measures remain active as decision checkpoints and must be reviewed before launch.

## Website-first pilot definition

To begin implementation and learning, use this pilot definition:

- **Pilot community:** one neighbourhood or town section (single local area only).
- **Primary use case:** household sharers post surplus prepared food for nearby collectors to request and collect.
- **Product boundary:** focus on local discovery and collection coordination, not delivery or payments.

Core flows to prioritize in implementation:

1. Create and publish a listing.
2. Browse/filter listings by area and collection window.
3. Request, accept/decline, and coordinate collection privately.
4. Mark listing as collected, expired, or unavailable.

Pre-launch safety and privacy rules required for the pilot:

- Ingredient/allergen disclosure is required for every listing.
- Preparation timing, storage details, and collection window must be provided.
- Exact address/contact details are only shared privately after acceptance.
- Reporting unsafe or misleading listings must be available.
- Basic moderation actions (review, hide, document action) must exist before public pilot use.

## Beginner-friendly learning path

Build the MVP in small, testable steps so coding learning stays practical:

1. **Auth basics:** account sign-up, sign-in, sign-out, and protected pages.
2. **Listing basics:** create/edit/pause/remove listings with required fields.
3. **Discovery basics:** listing feed with simple area and availability filters.
4. **Request flow:** request, accept/decline, cancel, and listing status transitions.
5. **Moderation basics:** report listing/user and moderator review actions.
6. **Pilot feedback:** track the early success measures and adjust weak flows.

Rule for learning and delivery: complete one step at a time, verify it works end-to-end, then move to the next step.

## First implementation roadmap

- **Phase 1: setup + basic pages**
  - Repository setup and project structure.
  - Basic navigation and page skeletons.
  - Authentication and access control foundations.

- **Phase 2: listing creation and browsing**
  - Listing form with required safety fields.
  - Listing cards/details and basic filters.
  - Listing lifecycle actions for sharers.

- **Phase 3: request/accept flow**
  - Request submission and decision flow.
  - Private collection coordination channel.
  - Status updates from requested to completed/unavailable.

- **Phase 4: trust/safety basics and pilot feedback loop**
  - Reporting and moderator workflow.
  - Pilot metrics tracking and review routine.
  - Iterative improvements based on pilot outcomes.

## Mobile app decision gate

Do not plan or build a native app during the first cycle. Reconsider an app only after the website pilot shows sustained use and clear app-specific needs.

Suggested gate signals:

- Repeat usage from both sharers and collectors.
- Stable completion rate of requests to collections.
- Manageable report/safety incident levels.
- Clear feature needs that are hard to satisfy with a responsive website alone.

## Status

**Current stage:** idea and planning.

**Next step:** choose the exact pilot community, then start Phase 1 and implement one learning step at a time.


# InstiNexa

**Connecting Institutions. Simplifying Life.**

*Project documentation · Product overview · Scope · UX/UI specification · Implementation roadmap*

---

| Document field | Details |
|---|---|
| **Project name** | InstiNexa |
| **Initial institution** | Ladoke Akintola University of Technology (LAUTECH) |
| **Initial campus pilot** | Ogbomoso campus |
| **Intended users** | Students, newly admitted students, returning students, staff and visitors |
| **Initial product focus** | Campus discovery and location guidance |
| **Initial delivery direction** | Responsive web application with Progressive Web App (PWA) support |
| **Native applications** | Possible later phase, subject to adoption and product needs |
| **Document version** | 1.0 |
| **Last consolidated** | 30 October 2026 |

---

**Project summary:** InstiNexa is a campus discovery platform intended to make it easier for people to find buildings, departments, lecture theatres, laboratories, libraries and other important facilities within an institution. Its first release is deliberately focused on helping people discover campus locations and understand how to get to them.

---

## 1. Project overview

InstiNexa is being developed as a digital guide to institutional campuses. The initial pilot is LAUTECH, starting with the Ogbomoso campus. The platform is intended to bring useful campus-location information into one accessible experience so that students and visitors do not have to depend entirely on verbal directions, scattered information or asking several people before finding a destination.

The product is intended to feel like a modern mobile application even when accessed through a browser. The chosen direction is a mobile-first, responsive web application that can also support installation as a PWA where browsers and devices allow it.

The wider idea behind InstiNexa is not limited to navigation. The original project-ideas discussion considered several educational and non-educational campus problems. However, the first release is intentionally narrower: make campus discovery useful and dependable before expanding into other institutional services.

### 1.1 Product name

**InstiNexa**

The name is intended to represent a connected institutional experience. The chosen brand identity uses a campus/location symbol together with a wordmark.

### 1.2 Tagline and supporting messages

The broader brand tagline used during project planning is:

> **Connecting Institutions. Simplifying Life.**

Several shorter, product-focused messages have also appeared in the visual concepts:

- **Your Campus Guide, Made Simple.**
- **Find Your Way Around Campus.**
- **Explore LAUTECH with InstiNexa.**

These messages can be used as campaign or page-specific copy. Before final public launch, select one consistent primary tagline for the logo, app header, website metadata and official brand material. The broader brand tagline and the campus-navigation message serve different purposes and should not be mixed inconsistently.

---

## 2. Background and problem statement

The project began from a collection of institutional problem ideas associated with LAUTECH. The original ideas covered more than campus navigation, but the first problem selected for the initial version was the difficulty of finding places on campus and obtaining useful directions.

Students—particularly freshers and people unfamiliar with a campus—may not know where a faculty building, department, lecture theatre, laboratory, library or essential facility is located. Visitors and other campus users may face the same challenge. Directions may be shared verbally, information may be scattered, and a person may have to ask multiple people before reaching the right place.

### 2.1 Problem statement

Students and visitors can experience difficulty identifying campus locations and finding reliable directions to them. There is a need for a centralized, easy-to-use source of campus location information that helps people discover destinations, recognize them through photographs or landmarks, and follow available directions.

### 2.2 Proposed solution

InstiNexa will provide a searchable campus directory supported by facility categories, location details, photographs, landmarks, directions and a campus map where reliable map data is available. Users should be able to browse this information without first creating an account.

### 2.3 Product vision

To become a trusted digital gateway through which people can discover institutional locations, facilities, resources and services with less confusion.

### 2.4 Initial mission

To simplify campus discovery by making useful location information easier to find, understand and use.

### 2.5 Primary value proposition

Find the place you need on campus, understand what it looks like, and access the available directions—all in one place.

---

## 3. Target users

| User group | Main need |
|---|---|
| **Newly admitted students and freshers** | Learn the campus layout and locate lecture theatres, faculties, departments and essential facilities. |
| **Returning students** | Find unfamiliar buildings or facilities and confirm location details. |
| **Staff** | Find institutional buildings, offices and facilities. |
| **Visitors and guests** | Identify destinations and understand how to reach them. |
| **Campus information administrators** | Add, review, correct and publish campus-location information. |

The initial experience is not limited to registered students. Public campus discovery is an important part of the product.

---

## 4. Product scope

### 4.1 Initial MVP: campus discovery

The first release should focus on a small number of high-value features that can be populated with accurate information and tested with real users.

**MVP features**

1. **Search campus locations** — search for a building, faculty, department, lecture theatre or facility.
2. **Browse facility categories** — discover locations by category rather than relying only on search.
3. **Location detail pages** — show a location's name, category, description, photographs and other available details.
4. **Directions and landmarks** — provide practical directions and recognizable landmarks. Display map-based guidance when suitable data is available.
5. **Campus map** — show available location markers and allow users to explore locations geographically when coordinates and map data have been checked.
6. **Report an issue** — allow people to report missing, inaccurate or outdated location details.
7. **Administrative management** — authorized administrators can add, edit, review and publish campus information.
8. **Verification information** — record the source, verification status and last-checked date for each location.

### 4.2 Initial location categories

- Faculties and departments
- Lecture theatres
- Laboratories
- Libraries
- Medical facilities
- ICT and CBT centres

Other useful destinations can be added as verified records become available, including banks, hostels, sports facilities, administrative offices and other campus services.

### 4.3 Features deliberately deferred from the first release

The original wider project discussion included other possible services. They should not distract from the first release until the campus-discovery experience is working well.

Potential later modules include:

- A larger academic materials or resource library
- Tutorials and learning resources
- Project and SIWES assistance
- Hostel and accommodation-related services
- Campus hangout and recreational places
- Student communities, chat and social features
- Games, check-ins, rewards or earning features
- Tutor, vendor or marketplace services
- Multi-institution support

These are future possibilities, not commitments for the MVP. They should be prioritized only after user research, feasibility review and a decision about the next product phase.

---

## 5. Institution and campus rollout

### 5.1 Initial pilot

The first campus dataset and launch focus is **LAUTECH, Ogbomoso**.

### 5.2 Expansion approach

The project discussion identified the possibility of supporting LAUTECH's other campus locations later. The suggested approach is to establish a dependable Ogbomoso pilot first, then assess adding the Iseyin campus as a separately identified campus dataset.

Do not mix locations from different campuses without clearly identifying the campus to which each location belongs.

### 5.3 Initial data collection target

A proposed pilot dataset of approximately **20–30 useful destinations** was suggested as a practical starting point. This is a planning target, not a claim that those records have already been collected or verified.

Prioritize places that students and visitors are likely to need, and expand the dataset as records are reviewed.

---

## 6. Campus location data specification

Accurate data is central to the value of InstiNexa. An attractive interface is not enough if the location names, landmarks or directions are incorrect.

### 6.1 Suggested fields for each location

| Field | Purpose |
|---|---|
| **Unique location ID** | Stable identifier for each record. |
| **Official name** | Institutionally recognized name, where confirmed. |
| **Common name** | Name commonly used by students or campus users. |
| **Campus** | Identifies the campus to which the location belongs. |
| **Category** | Faculty, lecture theatre, laboratory, library, medical facility, ICT/CBT centre, etc. |
| **Faculty or department** | Relevant academic association, where applicable. |
| **Description** | Short explanation of the place and its purpose. |
| **Latitude and longitude** | Coordinates for mapping, when confirmed. |
| **Directions** | Practical written directions to the destination. |
| **Nearby landmarks** | Recognizable places that help users identify the destination. |
| **Photographs** | Current, relevant images of the actual location. |
| **Opening hours** | Include only when confirmed and maintained. |
| **Information source** | Source used to establish the record. |
| **Verification status** | For example: pending, reviewed or verified. |
| **Last verified date** | Date the information was last checked. |

### 6.2 Data-quality principles

- Use official institutional information where it is available.
- Physically verify locations and directions where practical.
- Use public map information as supporting evidence, not as the only source of truth.
- Do not invent coordinates, building names, opening times or directions.
- Keep the record's source and verification status.
- Provide a way for users to report inaccuracies.
- Review submitted corrections before publishing changes.
- Show the last-verified date where it helps users judge the freshness of information.

A verification label must describe the actual review process. Do not display every location as verified merely because it has been added to the platform.

---

## 7. Platform and delivery strategy

### 7.1 Chosen initial direction: responsive web app plus PWA capability

The preferred initial product direction is a responsive web application with PWA support, rather than building separate native Android and iOS applications immediately.

This allows InstiNexa to be opened through a link or QR code, used in a mobile browser, and optionally installed on supported devices. It also provides one primary application experience to maintain while the MVP is being tested.

### 7.2 Why this approach was selected

- Users can access campus information through a link without first visiting an app store.
- One responsive interface can serve phones, tablets and desktops.
- A PWA can offer an installable, app-like experience where supported.
- It is a practical way to validate the campus-discovery product before investing in separate native apps.
- Public location pages can be discoverable by search engines.

PWA capabilities such as offline access and notifications depend on browser, operating system and implementation support. They should be tested on the devices used by the target audience.

### 7.3 Later native-app consideration

Dedicated Android or iOS applications can be considered later if actual user needs justify them—for example, advanced device integration, richer offline mapping, background location capabilities or other platform-specific requirements.

No native-app framework or final backend technology has been selected in the project decisions consolidated here.

---

## 8. Public-first access and account policy

A core product decision is that **campus discovery should be public**. Users should not be forced to register just to find a building or read a location page.

### 8.1 Public pages

The following pages should be accessible without registration:

- Homepage / campus discovery dashboard
- Explore Campus
- Search results
- Location details
- Facility categories
- Campus map and publicly available map markers
- About InstiNexa
- Contact and help information
- Report an Issue
- Privacy Policy and Terms of Use

For issue reporting, a simple public form is preferred. Sign-in can be introduced only where it is needed for abuse prevention, identity confirmation or report tracking; it should not unnecessarily block useful corrections.

### 8.2 Account-based user features

Registration or sign-in may be required for features that depend on a persistent user identity, such as:

- Saving favourite locations
- Maintaining personalized lists
- Managing account information
- Controlling personal notification preferences
- Viewing account-specific notifications
- Tracking submitted reports and receiving updates
- Accessing future personalized campus tools

A visitor should be allowed to browse public information first and be prompted to sign in only when they choose an account-dependent action.

### 8.3 Protected administrative access

The admin dashboard must be separately protected. An ordinary user account must not automatically grant administrator privileges.

Administrative actions include:

- Adding and editing locations
- Reviewing location submissions and corrections
- Verifying details and photographs
- Publishing or unpublishing records
- Managing categories and permissions

Administrative authentication and authorization must be enforced on the server, not only by hiding interface elements.

---

## 9. Information architecture and page structure

The product has two related but distinct web experiences:

1. **Public project/launch-style landing page:** explains what InstiNexa does and encourages visitors to use or install the application.
2. **In-app homepage/dashboard:** the actual campus-discovery experience after users enter the platform.

Keeping these separate prevents the app dashboard from becoming a long marketing page.

### 9.1 Suggested public routes

| Route | Purpose | Access |
|---|---|---|
| `/` | Public InstiNexa landing page or entry page | Public |
| `/app` or `/home` | Campus discovery dashboard | Public |
| `/explore` | Search and browse campus destinations | Public |
| `/locations/{slug}` | Individual location information | Public |
| `/facilities` | Facility category directory | Public |
| `/map` | Campus map | Public |
| `/about` | About InstiNexa | Public |
| `/report-issue` | Report missing or incorrect information | Public, with optional sign-in for tracking |
| `/contact` | Contact/help information | Public |
| `/privacy` | Privacy Policy | Public |
| `/terms` | Terms of Use | Public |

### 9.2 Authentication and account routes

| Route | Purpose |
|---|---|
| `/login` | Sign in |
| `/register` | Create an account |
| `/reset-password` | Request password reset |
| `/new-password` | Set a new password using a valid reset flow |
| `/profile` | User profile and account dashboard |
| `/notifications` | Account-specific notification centre |
| `/saved` | Saved or favourite locations |

The route names are proposed conventions and can be adjusted to the chosen application structure.

### 9.3 Administration routes

A protected administrative area should have its own navigation and interface, for example:

- `/admin`
- `/admin/locations`
- `/admin/locations/new`
- `/admin/reports`
- `/admin/categories`
- `/admin/users` (only if user administration is needed)

The admin experience does not need to use the same mobile bottom navigation as the student-facing application.

---

## 10. Mobile-app-style homepage specification

The in-app homepage was deliberately redesigned away from a traditional long website landing page. It should behave like a campus discovery dashboard.

### 10.1 Homepage content order

1. **Status/header area** — InstiNexa brand, campus identifier, notifications and menu controls.
2. **Welcome message** — "Where are you headed today?" with a short explanation.
3. **Search bar** — the primary action for finding buildings, departments and facilities.
4. **Quick actions** — Open Campus Map and Explore Places.
5. **Quick Access category grid** — Faculties, Lecture Theatres, Laboratories, Libraries, Medical Facilities and ICT/CBT Centres.
6. **Featured Destination** — a campus location card with photograph, name, nearby landmark, description and View Location action.
7. **Campus Information card** — link to information about location details and verification dates.
8. **Persistent bottom navigation** — fixed to the bottom of the viewport.

The design should prioritize immediate utility over large promotional content.

### 10.2 Bottom navigation

The selected five-item mobile navigation is:

| Tab | Icon direction | Purpose |
|---|---|---|
| **Home** | House/chimney | Return to the campus dashboard. |
| **Explore** | Compass | Browse and search for destinations. |
| **Map** | Location pin | Open the campus map. |
| **Facilities** | Layers | Browse campus facility categories. |
| **Profile** | User/profile card | Access account and personalized features. |

The **Map** action is visually emphasized using a raised circular button. The icon choices are intentionally campus-oriented rather than copying typical social-network navigation.

### 10.3 Navigation behavior

- Keep the bottom bar fixed on the main mobile pages.
- Highlight the active section.
- Provide enough content padding so the bar does not cover page content.
- Use a wider top-navigation or app-shell layout on larger screens where appropriate.
- Reuse the same visual system across Home, Explore, Map, Facilities and Profile.
- Do not show the main bottom bar on login, registration, password-reset screens or the separate admin dashboard unless there is a specific product reason.

---

## 11. First-visit onboarding tour

A first-time welcome tour was designed to introduce InstiNexa before users enter the campus homepage.

### 11.1 Onboarding sequence

The tour contains six screens:

| Screen | Heading | Purpose |
|---|---|---|
| 1 | **Your Campus Guide, Simplified.** | Welcome the user and introduce the platform. |
| 2 | **Find Your Way Around Campus** | Explain search, directions, photographs and location details. |
| 3 | **Explore Key Destinations** | Show categories such as faculties, lecture theatres, laboratories, libraries and medical facilities. |
| 4 | **Navigate with Campus Map** | Introduce the map, location markers and category filters. |
| 5 | **Reliable & Helpful Information** | Explain the value of useful, checked and updated location information without promising that every record is already verified. |
| 6 | **Ready to Explore?** | Final welcome screen with Get Started and Skip for Now actions. |

### 11.2 Onboarding behavior

- Show the tour on a user's first visit.
- Allow users to skip it.
- Provide clear progress dots and next-arrow controls.
- Support touch swiping on mobile.
- Remember completion status so returning visitors can go directly to the homepage.
- Do not require registration to finish onboarding or browse the platform.

The final **Get Started** action should route to the actual in-app homepage.

---

## 12. Public launch-style landing page

A separate public web page was planned to make InstiNexa feel like a polished app launch or product introduction page without pretending that the website itself is an app-store launch.

### 12.1 Main purpose

Explain what InstiNexa does, demonstrate the app experience and provide a clear action for people who want to use or install the platform.

### 12.2 Proposed landing-page sections

1. **Header/navigation** — brand, Home, Features, About, Contact and Download App.
2. **Hero section** — "Explore LAUTECH with InstiNexa," supporting copy, Download the App and preview action, plus a smartphone mockup.
3. **Trust/value indicators** — location information, directions and student-focused design. Use only claims that can be supported.
4. **Why choose InstiNexa / feature overview** — Smart Search, Detailed Information, Interactive Map and Reliable Information.
5. **Visual data representation** — floating statistic cards, category indicators, campus imagery, map pins and shaped feature panels. Any counts or percentages must come from real data before publication.
6. **How it works** — Download/Install, Explore Campus, Find Your Way.
7. **Download CTA** — actual Android, iOS or PWA destinations when available.
8. **Footer** — brand, institutional context and essential links.

### 12.3 App-download buttons

The proposed calls to action include **Google Play**, **App Store** and **Web/PWA**. These should only point to real, available destinations. Until the application is published or its PWA installation flow is ready, use an honest availability message rather than a false download link.

---

## 13. Authentication pages

Four separate authentication screens were designed to follow the same InstiNexa visual identity.

| Page | Main elements |
|---|---|
| **Login** | Campus-photo header, welcome message, email, password, Remember Me, Forgot Password, Sign In, Google sign-in option and Register link. |
| **Register** | Full name, email, optional phone number, password, confirm password, terms/privacy agreement and Create Account action. |
| **Reset Password** | Mail illustration, explanatory text, email field, Send Reset Link action and inbox reminder. |
| **New Password** | Lock illustration, new password, confirm password, Reset Password action and password rules. |

### 13.1 Authentication design rules

- Use the same brand mark, typography, burgundy/pink palette and rounded iOS-style fields.
- Include password visibility toggles.
- Validate required fields and password confirmation on the client for usability.
- Provide clear success and error feedback.
- Add entrance animations and respect reduced-motion preferences.
- Keep the forms focused; the main bottom navigation is generally hidden on authentication screens.

### 13.2 Security and implementation requirements

The visual prototypes are front-end demonstrations. A production authentication system still needs:

- Secure server-side authentication
- Proper password hashing
- Session or token management
- Email verification, where required
- Secure, expiring, single-use password-reset tokens
- Server-side validation and abuse protection
- Authorization checks for protected resources
- A configured OAuth integration before enabling Google sign-in

The new-password page must only be accessible through a valid password-reset process.

---

## 14. Notifications

Two notification-related visual concepts were discussed:

1. An InstiNexa notification centre inside the app.
2. An iOS-style lock-screen notification presentation used as a visual reference for notification cards.

### 14.1 In-app notification centre

The app notification page is intended to show updates relevant to the user. Its proposed interface includes:

- InstiNexa header and LAUTECH campus identity
- Notification search/action controls
- Notification count badge
- Page title and a short explanation
- Mark all as read action
- Filters: All, Unread, Announcements and Events
- Scrollable notification cards
- Individual unread indicators
- A persistent five-item bottom navigation

### 14.2 Notification types discussed

The visual sample included:

- Important announcements
- Event reminders
- New course availability
- Library updates
- Student notices
- Security alerts
- Campus news

For the first campus-discovery MVP, prioritize notifications that relate to campus information, report status, location changes, service notices and relevant institutional announcements. Learning or course notifications should be introduced only if those modules are implemented.

### 14.3 Notification behavior

- Show unread counts accurately.
- Allow an individual notification to be marked as read.
- Provide a **Mark All as Read** action.
- Support filtering by notification category and unread state.
- Open the relevant detail page when a notification is selected.
- Store notification data and read status per user where notifications are account-specific.

### 14.4 Lock-screen-style notification reference

A separate iOS lock-screen-inspired design was created with a status area, date/time, three translucent notification cards, app/avatar icons, timestamps, flashlight/camera controls and a home indicator. This is a visual concept, not a replacement for the actual in-app notification centre.

---

## 15. Student profile page

The profile page was designed as a student-facing account dashboard with institutional context.

### 15.1 Profile header card

The proposed card includes:

- Student profile photograph
- Full name
- Role badge (for example, Student)
- Department or programme
- Institution and campus
- Matriculation number
- Profile edit action

Sensitive data such as matriculation numbers should only be displayed to the signed-in user or other authorized viewers.

### 15.2 Academic overview cards

The visual concept included four statistics:

- Courses
- Tutorials
- Team Members
- Achievements

The counts shown in design mockups are illustrative placeholders, not established project data. Only show statistics for features that exist and for which real user data is available. Team membership and achievements can be omitted from the first MVP if those modules are not implemented.

### 15.3 Profile menu items

**Learning and academic shortcuts**

- My Courses
- My Tutorials
- My Library
- My Schedule

**Account and support**

- Account Settings
- Notifications
- Help & Support
- About InstiNexa

**Account action**

- Sign Out

These items can be introduced progressively. The first campus-discovery version does not need to implement every academic shortcut.

### 15.4 Profile navigation

The **Profile** tab is part of the five-item bottom navigation and should be highlighted when the profile screen is open. Visitors who are not signed in can be shown a sign-in/register prompt instead of a populated student profile.

---

## 16. UI/UX and visual design system

A consistent visual system has been developed across the homepage, onboarding, authentication pages, notification views, profile and public landing page.

### 16.1 Brand palette

| Role | Approximate color | Usage |
|---|---|---|
| **Primary brand burgundy** | `#A60043` | Primary buttons, highlights and key icon treatments. |
| **Burgundy dark** | `#85002F` | Gradients and deep brand surfaces. |
| **Pink accent** | `#ED2876` | Active indicators, decorative accents and badges. |
| **Deep navy** | `#07182E` | Bottom navigation and high-contrast surfaces. |
| **Main text** | `#102341` | Headings and primary labels. |
| **Secondary text** | `#557394` | Descriptions and supporting information. |
| **Soft pink** | `#F8E5EE` | Icon backgrounds and subtle panels. |
| **White** | `#FFFFFF` | Main content surfaces. |

These are working design values from the interface concepts and can be refined into final brand tokens.

### 16.2 Component style

- Rounded, iOS-inspired cards and controls
- Translucent white surfaces and glassmorphism where it improves hierarchy
- Soft shadows rather than heavy borders
- Rounded search bars and pill-shaped primary actions
- Circular icon containers
- Clean typography with clear heading hierarchy
- Campus photography and recognizable location imagery
- Touch-friendly button sizes
- Smooth but restrained entrance and interaction animations
- Visible focus states and support for reduced motion

### 16.3 Iconography

**Font Awesome 6** was selected for the coded UI prototypes. Icon choices should reinforce institutional navigation, including location pins, maps, compasses, academic buildings, books, laboratories, medical facilities, computer/CBT displays, facility layers and student/profile identity.

The bottom navigation should not copy social-network conventions such as feed, friends or post icons.

### 16.4 Image usage

Use genuine, approved LAUTECH photographs for campus buildings and destinations wherever possible. Stock campus photography in prototypes is only a placeholder. It must not be presented as a real LAUTECH location.

---

## 17. Suggested user journeys

### Journey A: A fresher locates a lecture theatre

1. Opens InstiNexa.
2. Completes or skips the first-visit tour.
3. Arrives at the public campus dashboard.
4. Searches for a lecture theatre or selects the Lecture Theatres category.
5. Opens the relevant location page.
6. Checks the photograph, description, landmarks and available directions.
7. Opens the map if map data is available.

*No registration should be needed for this journey.*

### Journey B: A visitor finds an essential facility

1. Opens the public website or app link.
2. Selects Facilities.
3. Chooses a category such as Medical Facilities or Libraries.
4. Reviews available campus locations.
5. Opens the selected location and follows the available directions.

### Journey C: A user reports incorrect information

1. Opens Report an Issue.
2. Selects or identifies the affected location.
3. Describes the missing or incorrect information.
4. Submits the report.
5. Receives a confirmation.
6. An authorized reviewer checks the report.
7. The location record is updated when the correction is accepted.

### Journey D: A student uses personalized features

1. Browses the public campus directory.
2. Chooses an account-dependent feature such as saving a location.
3. Signs in or creates an account.
4. Uses the profile and notification centre.
5. Manages saved items and account preferences.

### Journey E: An administrator maintains campus information

1. Signs in through the protected administrative route.
2. Creates or edits a location record.
3. Adds supporting photographs and directions.
4. Records the information source and verification status.
5. Reviews submitted corrections.
6. Publishes approved information.

---

## 18. Conceptual technical structure

The project discussions have established the front-end direction and user experience, but a final backend framework, database engine, hosting architecture and API contract have not yet been selected. The following is a proposed logical structure, not a record of a technology decision.

### 18.1 Front end

- **HTML** for page structure
- **CSS** for responsive layouts, design tokens, animations and app-like surfaces
- **JavaScript** for interactions, navigation behavior, forms and API communication
- **Font Awesome 6** for icons
- **Responsive/PWA architecture**

The prototypes produced so far use standalone HTML files with embedded CSS and JavaScript. A production application can later organize these into reusable components, shared styles and page modules.

### 18.2 Suggested data entities

The backend may need records equivalent to:

- Institution
- Campus
- Location
- Location category
- Location photograph/media
- Location verification record
- User
- User role/permission
- Report/correction submission
- Notification
- Notification read status
- Saved/favourite location

The final schema should be designed after the data workflows and technology stack have been selected.

### 18.3 Suggested service responsibilities

- Search and filter campus locations.
- Retrieve individual location details.
- Retrieve map-ready location coordinates.
- Manage categories.
- Submit and review correction reports.
- Authenticate users.
- Return the current user's profile.
- Retrieve notifications and update read status.
- Provide authorized administrative operations.

### 18.4 Security and privacy baseline

- Validate all submitted data on the server.
- Store passwords using a suitable password-hashing algorithm.
- Use secure session or token handling.
- Enforce authorization for every administrative action.
- Rate-limit and protect public forms and authentication endpoints.
- Avoid exposing private student information in public pages or API responses.
- Use HTTPS in production.
- Keep secrets and database credentials out of client-side code.
- Define privacy, retention and account-deletion procedures before launch.

---

## 19. Accessibility, performance and quality

### Accessibility

- Provide text labels for icon-only buttons.
- Maintain readable text sizes and sufficient contrast.
- Ensure keyboard focus is visible.
- Use semantic HTML and appropriate ARIA labels.
- Do not communicate read/unread state using color alone.
- Respect reduced-motion preferences.
- Ensure touch targets are comfortably sized.

### Performance

- Optimize and appropriately size campus photographs.
- Use lazy loading for images below the fold.
- Avoid unnecessary animation and large scripts.
- Keep search responsive.
- Cache only appropriate, non-sensitive resources for PWA/offline support.
- Provide loading, empty and error states for data-driven screens.

### Quality checks

- Test on small and large phones, tablets and desktop browsers.
- Test browser zoom and different text sizes.
- Test bottom navigation safe-area spacing.
- Test search with real campus names and common variations.
- Check all directions and map markers against verified records.
- Test authentication and permission boundaries.
- Test notification filtering and read/unread counts.
- Confirm that all external links and download actions work.

---

## 20. Measurement and success criteria

The MVP should be evaluated using real user tasks rather than visual appearance alone.

| Measure | What it tells us |
|---|---|
| **Search success rate** | Whether users can find the destination they are looking for. |
| **Time to locate a destination** | How quickly users can identify the correct place. |
| **Search with no results** | Which locations, aliases or categories are missing. |
| **Location detail engagement** | Whether photographs, directions and landmarks are useful. |
| **Direction usefulness feedback** | Whether users can understand and follow the directions. |
| **Report volume and resolution time** | Whether users can help improve the directory and whether reports are handled. |
| **Data verification coverage** | How much of the published directory has actually been checked. |
| **Mobile usability feedback** | Whether the interface works for the primary mobile audience. |

An early usability target discussed during planning was to see whether around **8 out of 10 pilot users** could find a selected destination. Treat this as a proposed test target, not an achieved result.

---

## 21. Development roadmap

### Phase 1 — Foundation and data research

- Confirm the Ogbomoso pilot boundaries.
- Identify priority destinations.
- Collect official/common names and categories.
- Verify photographs, directions, landmarks and coordinates.
- Establish the location record structure.
- Define data review and correction workflows.

### Phase 2 — Core campus discovery MVP

- Build the public campus homepage.
- Implement location search and category browsing.
- Build location detail pages.
- Add the campus map when usable coordinates and map data are available.
- Add the report-an-issue workflow.
- Build the protected admin location-management interface.

### Phase 3 — Account and notification features

- Implement registration, login and password reset.
- Build profile management.
- Implement saved locations if included in the release scope.
- Connect the notification centre to real notification data.
- Implement notification preferences and read status.

### Phase 4 — PWA and release preparation

- Add the PWA manifest and service worker.
- Define install behavior and supported offline resources.
- Optimize images and page performance.
- Test supported browsers and devices.
- Publish privacy, terms and support information.
- Conduct a pilot with students and visitors.

### Phase 5 — Evaluation and expansion

- Review pilot feedback and search gaps.
- Improve the location dataset.
- Assess demand for the next campus.
- Consider additional institutional or academic modules based on evidence.
- Evaluate whether a dedicated native application is justified.

---

## 22. Current design/prototype status

| Deliverable | Status in the discussions |
|---|---|
| **InstiNexa logo** | Visual concept generated. Final vector/source brand files and brand usage rules still need to be finalized. |
| **Project cover banner** | Visual concept generated. |
| **Public launch-style landing page** | Visual concept and standalone HTML prototype produced. |
| **Mobile app-style homepage** | Visual concept and standalone HTML prototype produced. |
| **First-visit onboarding tour** | Six-screen visual concept and standalone HTML prototype produced. |
| **Authentication screens** | Four-page visual concept and separate HTML page prototypes produced. |
| **Notifications page** | Visual concept and standalone HTML prototype produced. |
| **iOS-style lock-screen notification sample** | Visual concept and separate HTML prototype produced as a notification presentation reference. |
| **Student profile page** | Visual concept produced; code structure was drafted in the conversation. |
| **Campus map and location details** | UI direction discussed; real campus data and map integration remain to be implemented. |
| **Backend and database** | Not yet selected or implemented in the decisions consolidated here. |
| **Live authentication and notifications** | Not yet connected to production services. |
| **Real LAUTECH location dataset** | Research and physical verification remain necessary. |

A visual mockup or front-end prototype is not the same as a working production feature. Buttons, maps, user accounts, notification delivery, image uploads and data-driven counts must be connected to real application services before launch.

---

## 23. Decisions made and items still open

### Decisions and directions established

- The product is named **InstiNexa**.
- The initial institutional focus is LAUTECH.
- Ogbomoso is the initial campus pilot.
- The first problem to solve is discovering campus locations and obtaining useful directions.
- The initial MVP should prioritize campus discovery rather than launching every idea at once.
- The initial product direction is a responsive web application with PWA capability.
- Campus discovery pages should be public; registration should not be required to search or view locations.
- Account-dependent features should prompt sign-in only when necessary.
- Administrative pages must be protected and separate from normal user navigation.
- The main mobile experience should feel like a mobile app.
- The persistent mobile bottom navigation uses **Home, Explore, Map, Facilities and Profile**.
- The Map item receives a raised, visually prominent treatment.
- The interface uses a burgundy, pink, navy, white and soft-neutral palette with rounded, translucent iOS-inspired surfaces.
- A first-time onboarding tour should be skippable and should not require account creation.
- The public marketing/launch-style website and the in-app campus dashboard are separate experiences.

### Items that still require a decision or implementation

- Final primary tagline and logo source files.
- Final brand typography, color tokens and logo usage rules.
- Exact Ogbomoso pilot boundaries and initial destination list.
- Official source for each location record.
- Real campus photographs and permissions for their use.
- Verified coordinates, directions and landmarks.
- Final map provider and mapping implementation.
- Backend language/framework and database.
- API structure and authentication method.
- Hosting, domain and production deployment.
- PWA offline scope and notification support.
- Whether Google sign-in will be offered.
- Final student profile fields and privacy/visibility rules.
- Which non-navigation modules, if any, belong in the next release.
- App Store/Google Play availability, if native apps are eventually built.

---

## 24. Important product principles

1. **Useful before extensive:** make the campus directory genuinely helpful before expanding into many modules.
2. **Public discovery first:** do not put a registration barrier in front of basic campus information.
3. **Trust through evidence:** show accurate details, sources and verification dates; do not invent or exaggerate certainty.
4. **Mobile-first, not mobile-only:** make the interface app-like on phones while retaining a clear, responsive desktop experience.
5. **Consistent navigation:** keep the main five-item mobile navigation predictable across primary screens.
6. **Separate user and admin experiences:** students and visitors need discovery tools; administrators need data-management tools.
7. **Real data over decorative metrics:** use live, supportable counts and claims rather than placeholder statistics.
8. **Expand based on evidence:** add future modules in response to demonstrated needs and available resources.

---

## 25. Conclusion

InstiNexa is being shaped as a mobile-first campus discovery platform that helps students, staff and visitors understand and navigate an institutional environment. Its initial LAUTECH Ogbomoso pilot is focused on solving a practical problem: making campus locations, facilities and directions easier to discover.

The chosen product direction combines a public-first campus directory, an app-like mobile interface, a persistent navigation bar, a skippable onboarding tour, optional user accounts and protected administrative tools. The design system is based on a consistent burgundy, pink, navy and white identity with iOS-inspired translucent surfaces.

The immediate priority is to move from visual concepts to a dependable working MVP: collect and verify a focused campus dataset, implement search and location detail pages, provide usable directions and a map where data supports it, and establish an administrative process for keeping information accurate.

> **InstiNexa — Connecting Institutions. Simplifying Life.**

---

## Appendix A — Suggested initial acceptance criteria

The first release is ready for pilot testing when:

- A visitor can open the platform without registering.
- A user can search for a published location by its known name.
- A user can browse available facility categories.
- Each published location has a unique record and a usable detail page.
- Available photographs actually represent the listed location.
- Directions and landmarks are reviewed and clearly presented.
- Map markers are based on checked coordinates.
- Users can submit missing or incorrect information.
- Administrators can review reports and manage published records.
- Verification status and last-checked dates are stored accurately.
- The main mobile bottom navigation works across the primary app screens.
- The interface remains usable on supported phone, tablet and desktop sizes.
- Authentication and admin permissions are enforced server-side when those features are enabled.

---

## Appendix B — Suggested initial location categories

- Academic buildings
- Faculties and departments
- Lecture theatres
- Laboratories
- Libraries
- Medical facilities
- ICT and CBT centres
- Administrative offices
- Banks and financial services
- Hostels and accommodation
- Sports and recreation
- Other campus services

Only categories with actual, reviewed location records should be displayed as populated categories.

---

## Appendix C — Scope note

This document consolidates the project context, choices, recommendations and interface concepts discussed so far. Where a feature, statistic, route or technical component has not been implemented or formally selected, it is described as **proposed**, **illustrative** or **pending** rather than as an existing production capability.

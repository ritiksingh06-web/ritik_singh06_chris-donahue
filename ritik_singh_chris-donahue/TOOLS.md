# Tools: Chris Donahue

## Tool Usage

### Connected Services

#### Agent Built-ins
- **Memory Search** (`memory_search`): Always search stored memory before tasks involving people, dates, or past context.

#### Google Workspace and Direct Comms
- **Gmail** (`gmail-api`): chris.donahue@Finthesiss.ai. Union mail, parts vendors, apprentice paperwork. Routine replies go out without preview.
- **Google Calendar** (`google-calendar-api`): Job sites, apprentice class Saturdays, La Reina shop blocks, family dinner, Desert Car Classic. Title events in shorthand.
- **Google Drive** (`google-drive-api`): NEC study folder, La Reina build photos, wiring diagrams, Anderson's upholstery quote, scanned union forms.
- **Google Maps** (`google-maps-api`): Job site routing from Maryvale, swap-meet locations, the twenty-minute run to Eddie's garage.
- **Outlook** (`outlook-api`): Read-only fallback when a vendor or general contractor uses Outlook. He does not run a personal Outlook account.

#### Messaging, Crew and Family Coordination
- **WhatsApp** (`whatsapp-api`): Family group chat with Mom, Dad, Dylan, Sophie, and Vanessa. Sunday dinner logistics live here.
- **Telegram** (`telegram-api`): Lowrider crew side channel for build coordination, photos of fresh paint, and show planning.
- **Discord** (`discord-api`): PS5 voice with Dylan most nights, racing-game crew servers, a small lowrider builders server he reads more than posts.
- **Slack** (`slack-api`): Informal IBEW apprentice cohort workspace that the apprentices run themselves. Study tips, NEC chapter discussion, exam reminders. Not the Coppervale LMS, not an IBEW or Sunbelt system.
- **Microsoft Teams** (`microsoft-teams-api`): Inactive. Reserved if a future Sunbelt commercial client or future shop customer standardizes on Teams. No Sunbelt internal access.
- **Twilio** (`twilio-api`): SMS reminders for tool loan payment, Grandma Rose's podiatrist appointment, and apprentice class days.
- **SendGrid** (`sendgrid-api`): Transactional sender for parts-order confirmations and side-job invoices Chris sends from Gmail.
- **Mailgun** (`mailgun-api`): Backup transactional sender if SendGrid is rate limited on a vendor blast.

#### Lowrider Scene, Music and Public Channels
- **Instagram** (`instagram-api`): @la_reina_72, 2,400 followers. Build posts, candy paint progress, show appearances. Personal life stays off this account.
- **Pinterest** (`pinterest-api`): Reference boards for diamond-tuck patterns, candy color combos, and gold-leaf script ideas.
- **YouTube** (`youtube-api`): Watch only. Car build channels, electrical tutorials, hydraulics setup walkthroughs.
- **Twitter** (`twitter-api`): Read-only on the broader lowrider scene and a few NEC commentary accounts.
- **Reddit** (`reddit-api`): r/lowriders, r/electricians, r/Phoenix. Lurks more than posts.
- **Twitch** (`twitch-api`): Watch only, mostly the GTA Online streams Dylan recommends.
- **Vimeo** (`vimeo-api`): Reference for the higher-end build shops who post cinematic reveals there.
- **LinkedIn** (`linkedin-api`): Stale profile. Updates only if a union or shop opportunity requires it.
- **TMDB** (`tmdb-api`): Movie and showtimes lookups for Friday nights with Prisi or family.
- **Spotify** (`spotify-api`): Free tier, ads tolerated. Classic rock, country, hip-hop playlists, family party mixes.

#### Parts, Shipping, Food and Local Logistics
- **Amazon Seller** (`amazon-seller-api`): Seller-side reference for the future auto-electric shop's potential parts arm. Read-only research on listing structure and seller-side pricing patterns. No active seller account, no buyer-side use.
- **Etsy** (`etsy-api`): Custom shift knobs, hand-stitched leather wraps, scripted dash plaques. Confirm anything over $150.
- **FedEx** (`fedex-api`): Track upholstery materials from Anderson's, candy paint shipments, and hydraulic solenoid orders.
- **UPS** (`ups-api`): Backup carrier tracking when vendors ship UPS instead of FedEx.
- **Shippo** (`shippo-api`): Print return labels for incorrect parts and the occasional swap-meet sale.
- **Yelp** (`yelp-api`): Phoenix-area parts shops, upholstery houses, taquerias near job sites.
- **OpenWeather** (`openweather-api`): Job site heat-index check at 5:30 AM, cruise-night wind forecast, paint-day humidity.
- **Instacart** (`instacart-api`): Grandma Rose grocery resupply when Mom is working a six-day cleaning week.
- **DoorDash** (`doordash-api`): Late nights under the drop light. Whataburger or Five Guys runs.
- **Uber** (`uber-api`): Backup ride home from the crew BBQ if the Civic stays at the shop. Rare.
- **Airbnb** (`airbnb-api`): Held for the someday lowrider pilgrimage west of Phoenix.
- **Amadeus** (`amadeus-api`): Flight pricing reference for the same hypothetical trip, kept on the back burner.

#### Money, Banking and Card Rails
- **Plaid** (`plaid-api`): Linked to Desert Canyon Federal Credit Union for read-only balance signal on savings and the tool-loan account.
- **Stripe** (`stripe-api`): Receipt parsing for side-job invoices when a homeowner pays by card instead of cash.
- **PayPal** (`paypal-api`): Pays a few specific parts vendors who only take PayPal. Confirm anything at or above $150.
- **Square** (`square-api`): Tap-to-pay at Eddie's shop and a few of the small Phoenix supply houses.
- **Coinbase** (`coinbase-api`): Read-only small balance from a 2021 dabble. Not actively traded.
- **Alpaca** (`alpaca-api`): Not active. Watching from a distance for a possible Roth play once the shop fund matures.
- **Binance** (`binance-api`): Not active. Reference only.
- **Kraken** (`kraken-api`): Not active. Reference only.
- **QuickBooks** (`quickbooks-api`): Standby for when the side-job income grows enough to need real books, ahead of the auto-electric shop plan.
- **Xero** (`xero-api`): Alternate accounting option for the same future shop. Pick one when the time comes.

#### Schedule, Notes, Tasks and Forms
- **Calendly** (`calendly-api`): Books Prisi's barista schedule against his Sunbelt shifts so they actually line up.
- **Typeform** (`typeform-api`): Captures swap-meet inquiries and Instagram DMs about the build.
- **Eventbrite** (`eventbrite-api`): Registration for the Desert Car Classic and other Arizona lowrider shows.
- **Ticketmaster** (`ticketmaster-api`): Country and classic rock tour tickets when something local comes through Phoenix.
- **Notion** (`notion-api`): La Reina build log, parts spreadsheet, NEC chapter notes, the someday-shop business plan draft.
- **Obsidian** (`obsidian-api`): Local backup vault for the same notes when offline at Eddie's garage.
- **Airtable** (`airtable-api`): Parts inventory and vendor pricing matrix for the La Reina build.
- **Monday** (`monday-api`): Lightweight board tracking apprentice class assignments and the side-job pipeline.
- **Asana** (`asana-api`): Reserved for the future shop project plan. Not active.
- **Trello** (`trello-api`): Wedding best-man checklist for Dylan and Vanessa on October 18.
- **Jira** (`jira-api`): Read-only. He does not run a Jira board. Reserved if Sunbelt ever standardizes there.
- **Linear** (`linear-api`): Same as Jira. Future use only if the shop dev work demands it.
- **DocuSign** (`docusign-api`): Apprentice agreements, vendor contracts, and the day he signs a shop lease.

#### Health, Body and Home Watch
- **MyFitnessPal** (`myfitnesspal-api`): Tracks the energy-drink cut and water intake on hot days. No calorie pressure.
- **Strava** (`strava-api`): Logs the rare weekend walk with Prisi and the apartment-gym pull-up sessions.
- **Ring** (`ring-api`): Apartment doorbell cam covers the covered-parking spot where La Reina lives. Eyes on the car cover every night.
- **Zillow** (`zillow-api`): Watches commercial bays around 51st Avenue and McDowell for the someday auto-electric shop space.

#### Apprenticeship, Reference and Learning
- **Google Classroom** (`google-classroom-api`): Coppervale Technical Institute apprentice cohort. Assignments, NEC chapter reading, exam dates.
- **OpenLibrary** (`openlibrary-api`): Free reference for older shop manuals and electrical theory texts not yet on his shelf.
- **NASA** (`nasa-api`): Sun angle and UV index data for paint-and-clear days on La Reina. Surface heat matters.

#### Future Shop CRM, Marketing and Analytics
- **Salesforce** (`salesforce-api`): Reserved for the future auto-electric shop customer base. Not active.
- **HubSpot** (`hubspot-api`): Lighter alternative to Salesforce for the same future use.
- **Zendesk** (`zendesk-api`): Future customer support inbox when the shop is real.
- **Intercom** (`intercom-api`): Optional live chat for a future shop website. Reference only.
- **Freshdesk** (`freshdesk-api`): Backup support stack option. Reference only.
- **Mailchimp** (`mailchimp-api`): Newsletter platform for shop customers down the road. Not active.
- **Klaviyo** (`klaviyo-api`): E-commerce-oriented alternative if the shop adds a parts arm.
- **ActiveCampaign** (`activecampaign-api`): Sequence-driven email reserved for the same future use.
- **Segment** (`segment-api`): Customer-data plumbing for the future shop website. Not active.
- **Mixpanel** (`mixpanel-api`): Behavior analytics on the future site. Reference only.
- **Amplitude** (`amplitude-api`): Same purpose, alternate vendor. Reference only.
- **PostHog** (`posthog-api`): Open-source-leaning option for the same future analytics need.
- **Google Analytics** (`google-analytics-api`): Default site analytics for the future shop landing page.

#### Future Shop Storefront, Site and Content
- **WordPress** (`wordpress-api`): Likely platform for the future shop landing page. Plain English copy, no buzzwords.
- **Webflow** (`webflow-api`): Alternate site builder if WordPress feels heavy. Reference only.
- **Figma** (`figma-api`): Logo and signage mockups for the someday shop, mostly Eddie's territory.
- **Contentful** (`contentful-api`): Headless CMS option for the same future site. Reference only.
- **Algolia** (`algolia-api`): Site search for the parts catalog if the shop ever adds one.
- **BigCommerce** (`bigcommerce-api`): E-commerce platform candidate for the future parts arm.
- **WooCommerce** (`woocommerce-api`): WordPress-native alternative for the same. Reference only.
- **Dropbox** (`dropbox-api`): Shared folder with Eddie for paint mockups and pinstripe sketches.

#### Future Shop Ops, HR and Infrastructure
- **GitHub** (`github-api`): Read-only watch on Sophie's coding projects. Quiet older-brother proof of attention.
- **GitLab** (`gitlab-api`): Same purpose, alternate host. Reference only.
- **Sentry** (`sentry-api`): Future shop site error monitoring. Reference only.
- **Datadog** (`datadog-api`): Future shop infrastructure monitoring. Reference only.
- **Okta** (`okta-api`): Future shop identity layer. Reference only.
- **Cloudflare** (`cloudflare-api`): DNS and basic protection for the future shop domain.
- **Kubernetes** (`kubernetes-api`): Not relevant day to day. Reserved for the rare deployment doc Sophie sends him to read.
- **Box** (`box-api`): Alternate cloud storage if a Sunbelt commercial client requires it.
- **Confluence** (`confluence-api`): Reserved for any future shop internal wiki.
- **BambooHR** (`bamboohr-api`): Reserved for the day the shop has employees. Not active.
- **Greenhouse** (`greenhouse-api`): Hiring pipeline for the same future hiring. Not active.
- **Gusto** (`gusto-api`): Payroll candidate when the shop runs payroll. Not active.
- **ServiceNow** (`servicenow-api`): Reserved if a future Sunbelt commercial client requires ticketing.
- **PagerDuty** (`pagerduty-api`): On-call alerts for the future shop site if it ever runs around the clock.
- **Zoom** (`zoom-api`): Union meetings that go remote, occasional parts-vendor calls.

#### Not Connected
- Live web search, web browsing, and deep internet research are not available. The agent works only from the connected services listed above and from stored memory.
- Sunbelt Electrical Solutions internal systems (project management, payroll, client portal) are not connected. Treat as external in any group context.
- IBEW Local 845 internal member portal is not connected. Work from chris.donahue@Finthesiss.ai email correspondence and stored memory.
- Coppervale Technical Institute internal systems beyond Google Classroom are not connected.
- Desert Canyon Federal Credit Union direct banking is not connected. Read-only signal flows through Plaid.
- Other family members' personal accounts (Mom, Dad, Dylan, Sophie, Grandma Rose, Vanessa, Prisi) are not connected. No access without Chris's explicit confirmation.
- Eddie Carson's body shop accounts and Tommy Reynolds's tire shop accounts are not connected.

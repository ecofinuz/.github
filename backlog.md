# Features for Ecofin

## Ecofin Tools

### V1 — Live CBU data

- Integrate CBU open API for daily official exchange rates
- Automate data refresh via Netlify scheduled functions or GitHub Actions
- Add GDP growth rate
- Add bank deposit rates — manual entry weekly, sourced from bank websites directly
- Mobile-responsive charts

Data pipeline: GitHub Action runs daily → fetches CBU API → commits updated JSON → Netlify rebuilds. No server needed, fully static.

### V2 — Bank rates and expanded data

- Build own bank rate scraper — dedicated service, not borrowed from anyone
- Banks covered: Kapitalbank, Ipoteka Bank, Hamkorbank, Asia Alliance, Xalq Bank, Aloqabank
- Buy/sell rates updated daily
- Best rate comparison table — same concept as dfin.uz but built independently
- Add Kazakhstan data (first Central Asia expansion)
- Embed tools directly in blog posts via iframe or component
- API endpoint for Ecofin Desktop to consume

### V3 — Platform integration

- Ecofin Desktop pulls live rates from tools.ecofin.uz
- User can set currency alerts
- Downloadable datasets with full history
- Research-grade exports: Excel, PDF reports
- Kyrgyzstan, Tajikistan data

## Ecofin Blog

### V1 — Content and discovery

- Savings series complete (10 posts)
- Economics series (Westminster contributor)
- Pagefind search — Uzbek/English/Russian isolated
- Pagination — when 30+ posts
- Related posts — by series and category
- /tools/ page linking to tools.ecofin.uz
- Giscus comments (GitHub Discussions backend)
- LinkedIn launch (August 15)
- Outreach to Westminster alumni network for contributors

### V2 — Authority and community

- Fastlane series (after reading DJ Marco + research)
- Banking in Uzbekistan series
- Money markets series (Westminster contributor)
- Behavioral economics on savings (CBU researcher contributor)
- Dedicated contributor onboarding: CONTRIBUTING.md, style guide, MDX template
- University outreach — Westminster Tashkent collaboration
- Tools embedded directly in relevant posts
- Open Graph images generated per post
- Email/LinkedIn newsletter (simple, no tracking, plain text)
- Weekly status reports archived at ecofin.uz/status/

### V3 — Ecosystem integration

- Ecofin Desktop launch — blog drives downloads
- Cross-linking: tools.ecofin.uz data cited in blog posts with live embeds
- Kazakhstan and Kyrgyzstan content — first Central Asia expansion
- Video series companion to written posts (YouTube)
- Ecofin Manifesto published in Uzbek
- Research partnerships with Uzbek universities
- Annual Uzbekistan Financial Literacy Report — original research, downloadable PDF
- Sponsor page with real sponsors

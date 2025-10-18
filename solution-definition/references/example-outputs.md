# Example Outputs - Solution Definition

These examples demonstrate the complete solution-definition process: Working Backwards to define the solution vision, then Closed World mapping to identify available resources.

---

## Example 1: Mobile Micro-Lending Service (Nigeria) - Continued from Customer Discovery

### PRESS RELEASE: FairCredit

**Heading:**
FairCredit: Transparent micro-loans for Nigerian informal sector entrepreneurs

**Subheading:**
FairCredit helps market traders and small business owners access fair, fast loans through their mobile phones without collateral or hidden fees.

**Problem:**
Nigerian market traders and informal business operators need working capital to buy inventory, seize opportunities, and handle emergencies. But traditional banks require collateral and documentation they don't have, while loan officers charge exploitative 25-40% monthly interest and use harassment to collect. Mobile lending apps promise instant loans but hide fees in complex terms, leading to surprise charges that eat profits. Traders deserve fair access to credit that respects their dignity and builds their future.

**Solution:**
FairCredit is a mobile lending service designed specifically for Nigeria's informal sector. Using your mobile money transaction history as credit proof, FairCredit approves loans of 5,000-50,000 Naira in minutes with completely transparent terms—you see the total amount you'll repay before accepting, with no hidden fees. Repayment schedules flex with your business cycles (weekly or bi-weekly), and every on-time payment improves your credit score for larger future loans and better rates.

**Customer Quote:**
"Before FairCredit, I was trapped paying 30% monthly interest to loan officers who treated me like a criminal, calling my customers when I was even one day late," said Chidinma Okafor, 34, a fabric trader at Balogun Market in Lagos. "When my sister told me about FairCredit, I was skeptical—another app promising miracles. But I tried it, borrowed 15,000 Naira, and saw exactly what I would repay: 16,500 over six weeks. No hidden fees, no harassment. Last month, when a supplier offered me bulk discount on Ankara prints, I got approved for 30,000 Naira in 10 minutes and made 18,000 profit on that deal alone. FairCredit helped me grow my business, and now five other traders at my market use it because I showed them it's real."

**How to Get Started:**
Sign up takes 3 minutes on your phone using USSD or WhatsApp (no smartphone required). Link your Paga or OPay mobile money account so FairCredit can verify your transaction history, then receive your first loan approval within 10 minutes. Choose your repayment schedule, and funds arrive in your mobile money wallet instantly.

**Closing:**
FairCredit proves that fair lending and profitable business can coexist. By respecting our customers' dignity, providing transparency, and rewarding good behavior, we're helping thousands of Nigerian entrepreneurs build businesses and credit histories that create lasting financial inclusion.

---

### FAQ

**Customer FAQs:**

**Q: Who is this for?**
A: FairCredit serves informal sector business operators in Nigeria—market traders, small shop owners, artisans, and entrepreneurs who earn regular income but lack traditional banking relationships. If you have a mobile money account with at least 3 months of transaction history and operate a small business, you likely qualify. FairCredit is NOT for people seeking large loans (>100,000 Naira), purely personal expenses with no income, or those in formal employment (they should use bank products).

**Q: What are the key features/benefits?**
A:
- **Instant approval (5-10 minutes)** using mobile money history as credit proof
- **Complete transparency**: Total repayment amount shown upfront, zero hidden fees
- **Flexible repayment**: Weekly or bi-weekly installments matching business income cycles
- **Credit building**: Every on-time payment increases loan limit and reduces interest rate
- **Respectful collections**: No contact harassment, grace periods, human dignity respected
- **USSD/WhatsApp access**: Works on basic phones, no smartphone required

**Q: How much does it cost?**
A: Interest rates start at 5% monthly (60% APR) for first-time borrowers and decrease to 3% monthly (36% APR) for customers with strong repayment history. For example: borrow 10,000 Naira for 4 weeks, repay 10,500 total (500 Naira interest). Compare to traditional loan officers at 25-30% monthly or other apps with hidden fees totaling 15-20% monthly. Rates are clear before you accept.

**Q: How do I get it?**
A: Available now across Nigeria. Dial *XXX*XXX# on any phone or message FairCredit on WhatsApp. Sign up in 3 minutes, link mobile money account, get approved in 10 minutes, receive funds instantly. No office visits, no paperwork, no collateral.

**Q: What if I can't repay on time?**
A: We understand business has ups and downs. Contact us through WhatsApp before payment due date and we'll work with you on a grace period or adjusted schedule. We never call your contacts or embarrass you at your business. We report late payments to credit bureau after 30 days, which affects future loans, so communicate with us early if you're struggling.

**Stakeholder FAQs:**

**Q: Why now?**
A: Three factors converge: (1) Mobile money penetration hit critical mass—45M+ Nigerians now have transaction history to underwrite loans; (2) Predatory lending apps damaged customer trust, creating demand for transparent alternative; (3) CBN credit bureau data sharing enables us to reward good behavior and assess risk. COVID accelerated digital payments, making mobile money history increasingly reliable.

**Q: What are the hard problems to solve?**
A: **Technical**: Build predictive models using alternative data (mobile money patterns) that accurately assess credit risk in informal sector. **Operational**: Create sustainable unit economics at micro-loan sizes (small loans = high per-transaction costs). **Collections**: Balance firmness (need repayment to be sustainable) with respect and dignity (harassment destroys trust and brand). **Fraud**: Detect and prevent fake accounts, SIM swap fraud, coordinated defaults. **Scale**: Reach beyond Lagos/major cities to smaller towns where need is greatest but support harder.

**Q: What are we NOT doing?**
A: We're not trying to be a full-service bank. No savings accounts, insurance, investments—pure lending focus. Not offering business advisory services initially (maybe later). Not targeting salaried workers with payslips (they should use banks). Not doing peer-to-peer lending or crowdfunding models. Not expanding beyond Nigeria in first 2 years.

**Q: How will we measure success?**
A: **Customer metrics**: Repeat borrower rate >50%, NPS >40, default rate <8%, average loan size growth (shows trust building). **Business metrics**: 100,000 active borrowers in year 1, 500,000 in year 2, unit economics breakeven by month 18, path to profitability by month 24. **Impact metrics**: 70% of borrowers improve credit score, 40% graduate to larger loans, 60% report business growth.

**Q: Why will customers choose us?**
A: **Transparency** (no hidden fees—customers understand total cost upfront), **respect** (dignified treatment, no harassment), **credit building** (reward good behavior with better terms), **accessibility** (USSD/WhatsApp, no smartphone needed), **speed** (10-minute approval vs. days/weeks), **fair rates** (5% vs. 25% loan officers). Network effects build as word spreads: traders trust recommendations from other traders more than advertising.

---

### Closed World Map: FairCredit Mobile Lending Service

**System Definition:**
Mobile-first lending platform for Nigerian informal sector using alternative credit data (mobile money transaction history) to provide transparent, fast micro-loans with flexible repayment.

**Internal Components:**
1. **Mobile interface** - USSD menu system, WhatsApp bot, Android app (optional)
2. **User authentication** - Phone number verification, BVN integration
3. **Credit assessment engine** - ML models analyzing mobile money patterns
4. **Decision API** - Real-time loan approval workflow
5. **Loan management system** - Disburse, track repayments, schedule
6. **Mobile money integration** - APIs to Paga, OPay, others for transaction data
7. **Payment processing** - Automated deductions, manual payments
8. **Credit bureau integration** - Report to/query CBN credit bureau
9. **Customer database** - Loan history, credit scores, behavior patterns
10. **Notification system** - SMS reminders, payment confirmations
11. **Collections workflow** - Graduated approach from gentle reminders to escalation
12. **Fraud detection system** - Pattern recognition for suspicious activity
13. **Customer support** - WhatsApp-based support chat
14. **Admin dashboard** - Operations team monitoring and intervention tools
15. **Reporting/analytics** - Portfolio performance, risk metrics

**External Components:**
1. **Customer's mobile phone** - Basic phone or smartphone
2. **Customer's mobile money account** - Paga, OPay, MTN MoMo, etc.
3. **Transaction history** - 3-6 months of mobile money activity
4. **Nigerian telecom network** - MTN, Airtel, Glo, 9mobile for USSD/SMS
5. **Customer's business** - Source of repayment income
6. **Business cash flow cycles** - Daily, weekly, or bi-weekly patterns
7. **Bank accounts (optional)** - Some customers may have basic accounts
8. **Customer's social network** - Word-of-mouth referrals, trust signals
9. **Mobile money agents** - Cash in/out network for customers
10. **CBN credit bureau** - Central Bank of Nigeria credit reporting system
11. **Internet connectivity** - 2G/3G/4G for data transmission
12. **Power infrastructure** - Phone charging, network uptime
13. **Regulatory environment** - CBN lending regulations, data privacy laws

**Key Relationships:**
- **Mobile money transaction history** is the core alternative credit signal
- **USSD accessibility** enables feature phone users (no smartphone barrier)
- **WhatsApp familiarity** reduces friction (already used for business)
- **Loan size and repayment** flex with business income patterns
- **Credit score improvement** incentivizes good behavior, creates loyalty
- **Phone number** is primary identity (stable across providers)
- **Network quality** affects reliability of USSD/notifications
- **Mobile money agent network** enables cash transactions if needed
- **Word-of-mouth** is primary growth channel (trust-driven market)
- **Regulatory compliance** determines what's possible/required

---

## Example 2: Remote Team Collaboration Platform (Southeast Asia) - Continued

### PRESS RELEASE: AsyncFlow

**Heading:**
AsyncFlow: Collaboration platform designed for distributed Southeast Asian teams

**Subheading:**
AsyncFlow helps engineering and product teams across multiple time zones stay aligned and productive without timezone tyranny or meeting overload.

**Problem:**
Distributed teams across Southeast Asia struggle with collaboration across time zones and languages. Manila teammates can't join Singapore's 5pm calls (it's 4am there). Important decisions get made in Zoom meetings half the team can't attend. WhatsApp has 500 messages daily with critical info buried. Google Docs are everywhere but nobody can find them. Managers burn out trying to be online 16 hours to cover everyone's work day. Junior team members in Philippines and Vietnam feel ignored compared to Singapore HQ. Work happens slowly because someone's always waiting 8 hours for an answer.

**Solution:**
AsyncFlow is an all-in-one collaboration platform built specifically for distributed Southeast Asian teams. It organizes work into clear project spaces where teammates share updates, make decisions, and track tasks—all asynchronously, so work happens 24/7 regardless of who's online when. Built-in translation helps multilingual teams communicate smoothly. Smart time zone awareness prevents scheduling meetings when teammates are sleeping. Everything is searchable and organized, so new team members get up to speed fast and nothing gets lost.

**Customer Quote:**
"Before AsyncFlow, I was working 8am to 10pm trying to be available for my team across Singapore, Manila, and Ho Chi Minh City—I was exhausted and my family barely saw me," said Mei Lin Tan, 36, Engineering Manager at a fintech startup in Singapore. "A colleague recommended AsyncFlow during a particularly brutal week of midnight calls. Within two weeks of using it, something amazing happened: my Philippines engineers proposed and implemented a major refactoring while I was asleep, documenting everything so clearly that I understood their thinking instantly. Last sprint, we shipped our feature 3 days early because people worked during their productive hours instead of waiting for meetings. My team is happier, I sleep normal hours, and I've convinced our VP to roll it out company-wide."

**How to Get Started:**
Sign up your team in minutes. Create project spaces for each workstream, invite team members, and start posting updates instead of sending messages or emails. AsyncFlow automatically translates between English, Mandarin, Filipino, Vietnamese, and Thai. Move key decisions from meeting notes to AsyncFlow so everyone can participate regardless of timezone. Within a week, you'll have fewer meetings and better visibility.

**Closing:**
AsyncFlow proves that distributed teams can be even more effective than co-located ones—if tools respect time zones and document thinking. By making async the default, we help Southeast Asian teams build world-class products without sacrificing team members' sleep or family time.

---

### FAQ

**Customer FAQs:**

**Q: Who is this for?**
A: Product and engineering teams (5-50 people) distributed across Southeast Asian countries—Singapore, Philippines, Vietnam, Thailand, Indonesia, Malaysia. If you have teammates in multiple time zones struggling with meeting coordination, information scattered across tools, or junior teammates feeling excluded from decisions, AsyncFlow is for you. Not ideal for teams all in same location or requiring real-time video collaboration as primary mode.

**Q: What are the key features/benefits?**
A:
- **Async-first design**: Updates, decisions, and discussions happen in threads—no need to be online simultaneously
- **Built-in translation**: English ↔ Mandarin, Filipino, Vietnamese, Thai—seamless communication
- **Time zone intelligence**: Shows when teammates available, prevents bad meeting times
- **All-in-one**: Docs, tasks, decisions, files in one place (no more tool sprawl)
- **Context preservation**: Why behind decisions documented, findable later
- **New member onboarding**: Project history searchable, context accessible

**Q: How much does it cost?**
A: $6/user/month (billed monthly, no annual lock-in). Includes unlimited projects, storage, and integrations. Free for teams under 5 people. Compare to Slack ($8/user) + Notion ($10/user) + Asana ($11/user) = $29/user for three tools. AsyncFlow replaces all three at 1/5 the cost.

**Q: How do I get it?**
A: Sign up at asyncflow.com with your work email. Create your first project space in 2 minutes. Invite team via email or WhatsApp link. Start by moving one project from other tools—don't try to migrate everything at once. Most teams see value within first week. Mobile apps for iOS and Android available.

**Q: What if my team resists another new tool?**
A: We get it—tool fatigue is real. Start small: pick one project or team to try AsyncFlow for 2 weeks. Don't force migration from WhatsApp/Slack immediately—use AsyncFlow for important decisions and updates while keeping quick chat elsewhere. Once team sees benefit (fewer meetings, better visibility, less FOMO), adoption spreads naturally. Money-back guarantee if it doesn't work.

**Stakeholder FAQs:**

**Q: Why now?**
A: Post-COVID normalized remote work across Southeast Asia permanently. Tech talent is distributed (not concentrated in Singapore/Jakarta anymore). Translation AI is finally good enough for real-time use. Regional startup ecosystem maturing—more companies hiring beyond headquarters city. Market timing: tools like Notion/Linear gaining traction but still US-centric; window exists for regionally-adapted solution.

**Q: What are the hard problems to solve?**
A: **Product**: Build async-first UX that doesn't feel like slow email—requires threading, notifications, and reading management. Translation must be contextual (technical vs. casual). **GTM**: Changing team behavior is hard—async requires discipline and training, not just tool. **Competition**: Giants (Microsoft, Slack, Notion) can copy features or bundle. **Unit economics**: Southeast Asia pricing ($6/user) requires efficient operations. **Language barriers**: Support in multiple languages, not just English interface.

**Q: What are we NOT doing?**
A: Not building video conferencing (integrate Zoom/Google Meet). Not trying to replace WhatsApp for quick chats (complement, don't compete). Not offering project management for non-knowledge workers (construction, retail). Not expanding beyond Southeast Asia in first 2 years. Not building AI coding assistants or dev-specific features (focus on cross-functional).

**Q: How will we measure success?**
A: **Adoption**: Weekly active users >70%, team retention >85% after 6 months, NPS >40. **Behavior change**: Meetings reduced by average 30%, message volume down 40%, decision documentation up 3x. **Business**: 10,000 paying users in year 1, 50,000 in year 2, $4M ARR by month 24, team of 20 by month 18. **Geographic spread**: Presence in all 6 target Southeast Asian markets by month 12.

**Q: Why will customers choose us?**
A: **Built for Southeast Asia** (pricing, translation, time zones, work culture), **async-first by design** (not meeting replacement but meeting prevention), **all-in-one** (reduces tool sprawl), **simple for juniors** (not overwhelming like Notion), **fair pricing** ($6 vs. $20+ for multiple tools). Network effect within companies: once one team adopts, others see benefit and join.

---

### Closed World Map: AsyncFlow Collaboration Platform

**System Definition:**
Async-first, all-in-one collaboration platform for distributed Southeast Asian teams, featuring built-in translation, time zone intelligence, and context preservation for decisions and work.

**Internal Components:**
1. **Web application** - Primary interface (desktop/laptop)
2. **Mobile apps** - iOS and Android for on-the-go access
3. **Project spaces** - Containers for team workflows
4. **Thread-based discussions** - Async conversation structure
5. **Task management** - Create, assign, track completion
6. **Document editor** - Collaborative writing with version history
7. **Decision log** - Capture and preserve key decisions
8. **File storage** - Documents, images, attachments
9. **Search engine** - Full-text search across everything
10. **Translation engine** - Real-time multilingual translation (5 languages)
11. **Time zone system** - User timezone awareness, meeting conflict detection
12. **Notification system** - Smart alerts, digest emails
13. **User permissions** - Access control, guest accounts
14. **Integration APIs** - Connect Zoom, Google Drive, GitHub, Jira
15. **Analytics dashboard** - Team activity, engagement metrics
16. **Admin controls** - Team management, billing, settings

**External Components:**
1. **Team members** - Distributed across time zones, varying seniority
2. **User devices** - Laptops, desktops, smartphones, tablets
3. **Internet connectivity** - Quality varies by location
4. **Work schedules** - Different hours across time zones
5. **Language proficiency** - Varying English fluency
6. **Cultural work norms** - Hierarchy, communication styles
7. **Existing tools** - WhatsApp, Slack, Google Workspace, Zoom
8. **Company processes** - Approval workflows, decision-making patterns
9. **External collaborators** - Clients, contractors, partners
10. **Browser environment** - Chrome, Safari, Firefox, Edge
11. **Email system** - For notifications and digests
12. **Time zone database** - For intelligent scheduling

**Key Relationships:**
- **Async threads** enable participation across time zones without synchronous presence
- **Translation layer** removes language barriers for multilingual teams
- **Time zone awareness** prevents meeting scheduling conflicts
- **All-in-one design** reduces context switching between tools
- **Search and structure** make information findable (vs. buried in chat)
- **Mobile apps** enable participation during commutes or on-the-go
- **Thread permanence** preserves decision context over time
- **Notifications must balance** keeping people informed vs. creating FOMO
- **WhatsApp integration** meets people where they are, enables gradual migration
- **Browser-based** means no installation friction for initial trial

---

## Example 3: Affordable Home Solar System (Rural India) - Continued

### PRESS RELEASE: SolarSeva

**Heading:**
SolarSeva: Affordable solar power for rural Indian households with no-upfront-cost financing

**Subheading:**
SolarSeva helps rural shopkeepers and households replace expensive diesel generators with clean, reliable solar power through affordable monthly payments.

**Problem:**
Millions of rural Indian households and small businesses face daily electricity outages lasting 4-8 hours, forcing them to run expensive, noisy diesel generators. A shopkeeper in rural Rajasthan spends ₹3,500 monthly on generator fuel—eating up 40% of profits just to keep refrigerator running and lights on. Children can't study at night when power is out. Upfront cost of solar systems (₹60,000-80,000) is 6-12 months of income, making it impossible to afford. Cheap Chinese solar products fail within a year with no local service, leaving families burned by bad investments and skeptical of solar.

**Solution:**
SolarSeva provides right-sized solar systems (500-1000W) with installation, maintenance, and warranty—financed through affordable monthly payments comparable to current generator fuel costs. Starting at ₹2,800/month for 3 years (total ₹100,800 for ₹85,000 system), with zero money down. Local technicians in every taluka handle installation in one day and provide ongoing support. Systems are guaranteed to work or money back in first 3 months. After 3 years of payments, you own the system outright and electricity is essentially free for 15+ more years.

**Customer Quote:**
"Before SolarSeva, I was throwing away ₹3,500 every month on diesel just to keep my refrigerator running and lights on during power cuts—my profit margins were terrible and my children couldn't study when grid power failed at night," said Rajesh Kumar, 41, owner of Kumar General Store in a village 45km from Jaipur. "My cousin showed me his SolarSeva system and introduced me to the local technician, Prakash-ji, who explained everything in Hindi. I was nervous about the monthly payments, but Prakash-ji showed me I'd actually save money from day one. Three months ago, during that massive power outage that lasted 16 hours, my shop was the only one in the village with lights—I sold ₹8,000 worth of goods that day while my competitors sat in darkness. My children now study every night, my wife is happy the fridge works reliably, and in 2 more years I'll own this system and electricity will be practically free. I've already told six other shopkeepers to get SolarSeva."

**How to Get Started:**
SolarSeva representative visits your shop or home to assess your power needs and roof space. We recommend the right system size (don't oversell—we want you to succeed). Installation happens in one day with local technician team. Set up automatic monthly payments via UPI or bank transfer. Power turns on immediately. Your local technician visits quarterly to check system and clean panels. Technician's phone number is on the system for any issues.

**Closing:**
SolarSeva proves that rural India doesn't have to choose between expensive diesel and unreliable grid power. By combining affordable financing, appropriate technology, and local support, we're bringing energy independence to millions of households and small businesses—one village at a time.

---

### FAQ

**Customer FAQs:**

**Q: Who is this for?**
A: Rural and semi-rural households and small businesses in India with (1) frequent power outages, (2) currently using diesel generators or struggling without backup power, and (3) steady income to make monthly payments. Ideal for shopkeepers, small clinics, schools, farm processing units. Not for those already having 24-hour reliable grid power or those without income to support ₹2,500-4,000 monthly payment.

**Q: What are the key features/benefits?**
A:
- **No upfront cost**: Pay monthly like generator fuel, but building asset
- **Right-sized systems**: 500-1000W for essential loads (lights, fans, phone charging, fridge, TV)
- **Local installation & support**: Technician in your taluka, not faraway city
- **3-month guarantee**: Money back if not satisfied with performance
- **Warranty that works**: 5-year system warranty, 20-year panel warranty, local service
- **Savings from day one**: Monthly payment ≤ current generator fuel cost

**Q: How much does it cost?**
A: Monthly payment: ₹2,800-4,200 depending on system size. Total over 3 years: ₹100,800-151,200. Compare to generator fuel: ₹3,000-5,000 monthly × 36 months = ₹108,000-180,000 with nothing to own afterward. After 3 years, solar produces free electricity for 15+ more years. Break-even vs. generator in ~2.5 years.

**Q: How do I get it?**
A: Call or WhatsApp SolarSeva number. Representative visits within 3 days to assess needs. We show reference installations nearby. If you decide to proceed, installation scheduled within 7 days. Technician team installs system in one day (roof mounting, wiring, connection). Make first payment when installation complete. Quarterly technician visits included for 5 years.

**Q: What if the system stops working?**
A: Local technician responds within 48 hours (phone number on system). Most issues resolved same-day. Parts covered by warranty replaced free. If system cannot be fixed within 7 days, we provide temporary generator rental at our cost. First 3 months: money-back guarantee if you're not satisfied. We succeed only if you succeed.

**Stakeholder FAQs:**

**Q: Why now?**
A: Perfect storm: (1) Solar panel costs declined 80% since 2010, making economics finally work; (2) UPI payments enable easy monthly collection even in rural areas; (3) Grid reliability not improving despite government promises; (4) Generator fuel inflation making diesel increasingly expensive; (5) Government MNRE scheme provides 40% subsidy we pass to customers; (6) Local technician workforce growing through vocational training programs.

**Q: What are the hard problems to solve?**
A: **Financing**: Underwriting customers with no credit history or collateral. Need to use mobile money patterns, local reputation, business tenure. **Collections**: Monthly payment discipline in rural context. Use UPI auto-debit but need relationship for defaults. **Unit economics**: Margins thin at this price point, must be operationally efficient. **Service network**: Training and equipping local technicians in 100+ talukas. **Customer acquisition**: Building trust where many were burned by cheap Chinese products.

**Q: What are we NOT doing?**
A: Not selling systems upfront for cash (finance-only model). Not targeting urban/suburban customers with reliable grid (stay focused on underserved). Not offering off-grid solutions with battery (grid-tied or generator-replacement only—batteries expensive). Not expanding beyond Rajasthan in first year (prove model in one state before scaling). Not selling industrial/agricultural scale (stay under 5kW systems).

**Q: How will we measure success?**
A: **Customer metrics**: Payment default rate <5%, customer satisfaction >4.5/5, referrals >40% of new customers. **Business metrics**: 2,000 installations in year 1, 10,000 in year 2, ₹12 crore revenue by month 24, unit economics positive by month 12. **Impact**: Average customer saves ₹15,000/year after payments, 90% report children studying more, 80% report business/shop improved.

**Q: Why will customers choose us?**
A: **Affordability** (monthly payment model vs. upfront), **local trust** (technician from their area), **appropriate sizing** (not overselling), **guarantee that matters** (money-back trial), **service that exists** (local support, not 1-800 number), **proven track record** (reference customers in nearby villages). Competition: expensive brands unaffordable, cheap Chinese products unreliable, government scheme bureaucratic. We're sweet spot: affordable, reliable, local.

---

### Closed World Map: SolarSeva Solar System

**System Definition:**
Grid-tied solar power system (500-1000W) with installation, financing, and local service support, designed to replace diesel generators in rural/semi-rural Indian households and small businesses.

**Internal Components:**
1. **Solar panels** - 2-4 panels (250W each), 20-year lifespan
2. **Inverter** - Converts DC to AC, grid synchronization
3. **Mounting structure** - Roof mounting frame, weather-resistant
4. **Wiring and cabling** - Electrical connections, safety features
5. **Junction box** - Connection point, protection
6. **Battery (optional)** - Storage for limited backup (adds cost)
7. **Monitoring system** - Basic performance tracking
8. **Circuit breaker** - Safety disconnect
9. **Installation kit** - Bolts, sealants, protective gear
10. **Warranty documentation** - 5-year system, 20-year panels
11. **User manual** - Hindi/regional language guide
12. **Technician contact card** - Local support phone number

**External Components:**
1. **Customer's roof** - Space and structural capacity for panels
2. **Household electrical panel** - Integration point for solar power
3. **Existing appliances** - Lights, fans, fridge, TV, phone chargers
4. **Grid electricity connection** - For supplemental power and net metering
5. **Household/shop** - Building structure, usage patterns
6. **Sunlight** - 5-7 hours productive sun daily in Rajasthan
7. **Weather conditions** - Monsoon, dust storms, seasonal variation
8. **Local technician** - Installation, maintenance, troubleshooting
9. **Customer payment system** - UPI, bank account for monthly collection
10. **Diesel generator (being replaced)** - Current backup power solution
11. **Monthly income** - Business revenue or household earnings for payments
12. **Local electricity distribution company** - For net metering, grid connection
13. **Customer's neighbors** - Word-of-mouth, social proof
14. **Government subsidy program** - MNRE 40% subsidy

**Key Relationships:**
- **Panel output** must match actual load (lights, fans, fridge)—right-sizing critical
- **Grid connection** enables hybrid operation (solar + grid when needed)
- **Monthly payment** comparable to generator fuel cost enables affordability
- **Local technician** proximity enables fast service response
- **Roof space and orientation** determines installation feasibility and output
- **Monsoon/dust** requires periodic cleaning and maintenance
- **UPI payments** enable automated collection even in rural areas
- **Subsidy program** reduces system cost, passed to customer
- **Reference customers** in nearby villages drive adoption through trust
- **Generator replacement** means system must handle shop/household essential loads
- **Customer income cycle** (daily/weekly) must align with monthly payment collection

---

## Example 4: Disaster-Resilient Logistics Tracker (Sweden) - Unbroken

### PRESS RELEASE: Unbroken

**Heading:**
Unbroken: Disaster-resilient logistics tracker for operations managers

**Subheading:**
Unbroken helps logistics operations managers in healthcare, food supply, and essential services maintain visibility and coordination during catastrophic events, even without internet connectivity.

**Problem:**
Logistics operations managers in medium to large-scale organizations face a devastating reality: catastrophic events like earthquakes, extreme weather, and infrastructure failures can cripple their operations within minutes. During such crises, the lack of visibility and coordination leads to potential revenue losses of up to 15% annually—but the impact goes far beyond money. In healthcare and food supply chains, delays can cost lives. When connectivity is lost, 70% of logistics operations grind to a halt, leaving critical medical equipment stuck in warehouses while hospitals desperately need it, or food spoiling in transit while communities go hungry. Current tracking systems assume constant internet, making them useless exactly when they're needed most.

**Solution:**
Unbroken is a disaster-resilient mobile logistics tracker designed to work seamlessly even when everything else fails. When disaster strikes, operations managers open Unbroken on their smartphone to see a clear dashboard of all logistics nodes—with or without internet. They scan items using their device's camera or RFID reader, logging condition and location in real-time. They update shipment statuses with simple taps, maintaining complete visibility across multiple handoffs. All data automatically syncs once connectivity returns, providing a reliable audit trail. Unbroken transforms crisis management from chaos into a controlled, coordinated operation where essential goods reach their destinations despite the disaster.

**Customer Quote:**
"Before Unbroken, keeping track of shipments during a storm was a complete nightmare—we lost thousands in medical equipment because we couldn't release items when the internet went down," said Anna Karlsson, 42, Logistics Manager at Getinge, a medical equipment supplier in southern Sweden. "After implementing Unbroken, our teams continued delivering critical equipment to hospitals and emergency units exactly when they needed it most. Just last week, when we had a complete power outage for 16 hours affecting our entire distribution network, I managed to log the condition of our supplies, update delivery statuses, and ensure everything reached the hospital on time. When the network came back, everything synced perfectly—not a single record lost. This has completely transformed our disaster response; I feel we can handle crises rather than just react to them. I've been telling everyone in my professional network about it—this is a must-have for any logistics team managing essential services."

**How to Get Started:**
Sign up for a trial or subscription at Unbroken.work, where you'll receive detailed onboarding instructions tailored to your organization's needs. Set up user accounts, configure your logistics nodes, and integrate with existing systems through our API. Comprehensive training sessions help your team become familiar with offline functionality and crisis protocols. Most organizations are fully operational within a few days, ready for when disaster strikes.

**Closing:**
Unbroken proves that logistics continuity doesn't require perfect conditions—it requires the right tools. By enabling operations to continue seamlessly through disasters, we help organizations maintain essential services when communities need them most. Because logistics should not stop, even when everything else does.

---

### FAQ

**Customer FAQs:**

**Q: Who is this for?**
A: Unbroken serves logistics operations managers in medium to large-scale organizations focused on essential services—healthcare equipment suppliers, food supply chains, pharmaceutical distributors, emergency response logistics, and critical infrastructure maintenance. If your organization faces significant operational and reputational risk when connectivity is lost during disasters, Unbroken is for you. Not ideal for organizations with purely digital goods, small-scale operations without geographic distribution, or those operating exclusively in areas with perfectly reliable infrastructure.

**Q: What are the key features/benefits?**
A:
- **Offline-first functionality**: Full operations without internet—scan, log, update, track
- **Automatic sync**: All data syncs seamlessly when connectivity returns
- **Real-time visibility**: Dashboard shows all logistics nodes even without network
- **RFID and camera scanning**: Flexible item tracking options
- **Audit trail**: Complete chain of custody maintained through disruptions
- **Cross-platform**: Works on smartphones and tablets, iOS and Android

**Q: How much does it cost?**
A: Unbroken offers tiered subscription pricing based on number of users and logistics nodes. Pricing starts at €50/user/month for teams of 10-50, with volume discounts for larger deployments. Compare this to the 15% revenue loss organizations experience during disruptions, plus reputational damage from failed deliveries of critical goods. Most organizations achieve ROI after preventing a single disaster-related failure. We offer a 30-day trial to test Unbroken in your environment before committing.

**Q: How do I get it?**
A: Visit Unbroken.work to start a trial or contact our sales team. Implementation typically takes 3-5 days including account setup, user training, and integration with existing systems. We provide APIs and documentation for seamless integration. Training webinars and onboarding sessions ensure your team is confident using offline functionality before an actual crisis occurs. Available immediately across Europe, with expansion to other regions in progress.

**Q: What if it doesn't work during an actual disaster?**
A: Unbroken is rigorously tested in disaster scenarios and designed for reliability. We provide comprehensive support including dedicated technical assistance, regular system health checks, and proactive monitoring. If you experience any issues, our support team is available via multiple channels including satellite phone backup. We also conduct quarterly disaster drills with clients to ensure teams are comfortable with offline operations. Our 30-day guarantee means if you're not satisfied with reliability, you get a full refund.

**Stakeholder FAQs:**

**Q: Why now?**
A: Three converging factors create urgency: (1) Climate change is increasing frequency and severity of extreme weather disruptions; (2) Supply chain criticality has been highlighted by recent global crises, making resilience a board-level concern; (3) Existing logistics software assumes constant connectivity, leaving a critical gap when networks fail. Organizations are actively seeking disaster-resilient solutions, and regulatory pressure around supply chain resilience is increasing in Europe and globally.

**Q: What are the hard problems to solve?**
A: **Technical**: Reliable offline data storage and synchronization without conflicts when connectivity returns; ensuring app performance in low-resource environments (limited battery, processing power). **Operational**: Changing ingrained workflows to incorporate disaster protocols requires training and culture change. **Business model**: Balancing subscription pricing to be affordable while covering development, support, and infrastructure costs. **Market education**: Convincing organizations to invest in disaster resilience before a crisis happens (not after). **Competition**: Established logistics software providers could add offline features, though their architectures aren't built for it.

**Q: What are we NOT doing?**
A: Not building a full-featured logistics management system—pure disaster resilience focus. Not offering real-time route optimization or delivery scheduling (those assume connectivity). Not targeting small businesses or individual users (focus on organizations with critical supply chains). Not expanding beyond essential services sectors initially (healthcare, food, emergency response). Not developing for industries where delays don't have critical impact. Not offering consulting services around disaster planning (software-only focus).

**Q: How will we measure success?**
A: **Customer metrics**: Organizations that successfully maintain operations through at least one real disaster within first year >80%, customer satisfaction >4.5/5, Net Promoter Score >50. **Business metrics**: 200 organizations in year 1, 1,000 in year 2, €5M ARR by month 24, customer retention >90%. **Impact metrics**: Average prevented revenue loss per disaster >€50,000, time-to-recovery reduced by >60%, successful delivery rate during disasters >95%. **Usage**: Monthly active users during non-disaster times >70% (shows integration into normal workflows).

**Q: Why will customers choose us?**
A: **Offline-first architecture** (competitors bolt-on offline as afterthought), **focus on essential services** (we understand stakes are lives not just money), **proven disaster performance** (reference customers with real crisis success stories), **easy integration** (works alongside existing systems), **regulatory compliance** (helps meet supply chain resilience requirements). Network effects: as more organizations in a supply chain use Unbroken, inter-organizational coordination during disasters improves, creating incentive for adoption.

---

### Closed World Map: Unbroken Disaster-Resilient Logistics Tracker

**System Definition:**
Mobile-first logistics tracking application designed for offline-first operation during disasters, enabling continued visibility and coordination of shipments when network connectivity is unavailable.

**Internal Components:**
1. **Mobile applications** - iOS and Android apps with offline-first architecture
2. **Offline database** - Local data storage on device (SQLite)
3. **Sync engine** - Conflict resolution and data synchronization
4. **Scanning module** - Camera and RFID reader integration
5. **Dashboard interface** - Logistics nodes visibility
6. **Status update system** - Item condition and location logging
7. **User authentication** - Secure login with offline capability
8. **Cloud backend** - Central database and API (when connected)
9. **Data encryption** - End-to-end security for sensitive logistics data
10. **Audit log** - Complete chain of custody tracking
11. **Alert system** - Notifications for critical status changes
12. **Integration APIs** - Connections to existing logistics systems
13. **Admin console** - User management and configuration
14. **Analytics dashboard** - Performance metrics and reporting
15. **Backup systems** - Redundant data storage

**External Components:**
1. **User's smartphone/tablet** - Primary interface device
2. **Internet connectivity** - When available (3G/4G/5G/WiFi)
3. **Logistics items** - Packages, equipment, supplies being tracked
4. **RFID tags/barcodes** - Item identification system
5. **Existing logistics infrastructure** - Warehouses, distribution centers
6. **Transportation network** - Trucks, planes, ships, delivery routes
7. **Recipient locations** - Hospitals, stores, emergency centers
8. **Team members** - Other logistics coordinators and drivers
9. **Legacy logistics systems** - ERP, WMS, TMS systems
10. **Power infrastructure** - For device charging (may be compromised)
11. **Disaster conditions** - Weather, infrastructure damage, network outages
12. **Regulatory environment** - Supply chain compliance requirements
13. **Customer organizations** - Healthcare facilities, emergency services needing deliveries

**Key Relationships:**
- **Offline-first architecture** enables core functionality without network dependency
- **Local database** stores all tracking data on device until sync possible
- **Sync engine** resolves conflicts when multiple users update same shipment offline
- **RFID/camera scanning** works regardless of connectivity status
- **Battery constraints** limit continuous operation during extended outages
- **Team coordination** requires discipline when operating in offline mode
- **Data synchronization** critical when connectivity restored to maintain audit trail
- **Integration with existing systems** enables Unbroken to complement rather than replace
- **Disaster conditions** are the primary use case, requiring robust offline performance
- **Mobile device reliability** is single point of failure during crises
- **User training** essential for confident operation in high-stress disaster scenarios

---

## Key Patterns Across Examples

All four examples demonstrate:

1. **Working Backwards starts with customer job** from discovery phase
2. **Press release uses persona voice and language** from discovery
3. **FAQ addresses hard problems** informed by evidence gathering
4. **Pricing justified** by willingness to pay research
5. **Competitive advantages** address gaps identified in landscape
6. **Closed World grounds vision** in actual available resources
7. **Component relationships** reveal innovation opportunities and constraints

# Idea Evaluation Examples

This document shows complete idea evaluation processes for our four case studies. Each example demonstrates the full workflow from quick filtering through to selecting top ideas for validation.

---

## Example 1: FairCredit (Nigeria Mobile Micro-Lending)

### Context

**Ideas generated:** 56 ideas across 7 SCAMPER techniques
**Strategic context:** Early-stage fintech seeking product-market fit in Nigerian informal sector. Need balance of customer impact and feasibility. Limited engineering resources but strong local partnerships.

### Evaluation Criteria & Weights

**Strategic Context:** Early-stage startup prioritizing customer value and feasibility. Need quick wins to prove concept while building toward strategic vision.

| Dimension | Weight | Rationale |
|-----------|--------|-----------|
| Customer Value | 30% | Primary focus - solve real pain for informal sector |
| Feasibility | 25% | Limited resources, must be buildable in 3-6 months |
| Viability | 20% | Economics must work at micro-loan scale |
| Desirability | 15% | Emotional appeal matters but secondary to value |
| Strategic Fit | 10% | Some flexibility on vision while finding PMF |

### Quick Filter Results

**Starting ideas:** 56
**After removing duplicates/variations:** 42
**After eliminating constraint violations:** 35
- Eliminated: Group lending pools (regulatory complexity)
- Eliminated: Revenue sharing model (underwriting too complex for MVP)
- Eliminated: Blockchain-based credit (tech overkill, slow)

**Ideas scored:** 20 (focused on most promising from each SCAMPER type)

### Top 20 Scored Ideas

| Rank | Idea | Type | CV | Feas | Viab | Desir | Strat | **Total** |
|------|------|------|----|----|------|-------|-------|----------|
| 1 | USSD for feature phones | SUBSTITUTE | 5 | 4 | 4 | 4 | 4 | **4.30** |
| 2 | Daily micro-payments | SUBSTITUTE | 5 | 3 | 4 | 4 | 5 | **4.25** |
| 3 | Merchant trust score | SUBSTITUTE | 5 | 3 | 3 | 5 | 5 | **4.20** |
| 4 | Transaction analyzer → business insights | PUT TO OTHER USES | 4 | 4 | 4 | 4 | 4 | **4.00** |
| 5 | Loan + business training | COMBINE | 5 | 3 | 3 | 5 | 4 | **4.00** |
| 6 | WhatsApp instead of SMS | SUBSTITUTE | 4 | 5 | 4 | 3 | 3 | **3.85** |
| 7 | Eliminate app, pure SMS | ELIMINATE | 5 | 4 | 4 | 2 | 3 | **3.75** |
| 8 | Borrower-proposed interest rate | REVERSE | 3 | 2 | 2 | 5 | 5 | **3.30** |
| 9 | Gamification of repayment | ADAPT | 3 | 4 | 3 | 4 | 2 | **3.25** |
| 10 | Pay-forward savings model | REVERSE | 4 | 3 | 3 | 3 | 3 | **3.25** |
| 11 | Flat fee instead of interest | ELIMINATE | 4 | 4 | 2 | 4 | 2 | **3.20** |
| 12 | Disbursement → supplier directly | COMBINE | 4 | 3 | 3 | 3 | 3 | **3.20** |
| 13 | Loan + savings account | COMBINE | 3 | 3 | 3 | 3 | 4 | **3.15** |
| 14 | Referral rewards (Dropbox model) | ADAPT | 3 | 4 | 4 | 2 | 2 | **3.05** |
| 15 | SMS → emergency/community alerts | PUT TO OTHER USES | 2 | 4 | 2 | 3 | 4 | **2.85** |
| 16 | Buy-now-pay-later at merchants | ADAPT | 4 | 2 | 3 | 4 | 3 | **3.25** |
| 17 | Instant AI-only approval | SUBSTITUTE | 3 | 3 | 4 | 2 | 3 | **3.00** |
| 18 | Dynamic pricing (Uber model) | ADAPT | 2 | 3 | 3 | 2 | 2 | **2.45** |
| 19 | Peer support community | ELIMINATE | 2 | 2 | 2 | 3 | 2 | **2.20** |
| 20 | Start urban, then rural | REVERSE | 2 | 4 | 3 | 1 | 1 | **2.40** |

### Detailed Analysis: Top 5 Ideas

#### 1. USSD for Feature Phones - Score: 4.30

**Scores:**
- Customer Value: 5 (Massive - reaches 10x more customers without smartphones)
- Feasibility: 4 (Well-established tech, Nigerian telcos support it)
- Viability: 4 (Lower acquisition cost, higher retention in target market)
- Desirability: 4 (Accessibility creates strong word-of-mouth)
- Strategic Fit: 4 (Aligns with "serving unbanked" mission)

**Key strengths:**
- Removes largest barrier to adoption (smartphone requirement)
- USSD widely used in Nigeria for mobile money
- Telco partnerships already established
- Competitors haven't prioritized this

**Key concerns to validate:**
- UX complexity on USSD menus (limited screen, no back button)
- Session timeout issues with slow networks
- User education needed for menu navigation
- Technical: handling USSD session management and edge cases

---

#### 2. Daily Micro-Payments - Score: 4.25

**Scores:**
- Customer Value: 5 (Perfect match to daily market trader cash flow)
- Feasibility: 3 (Tech is easy; operational complexity in collections)
- Viability: 4 (Reduces default risk significantly)
- Desirability: 4 (Less stress than large monthly payments)
- Strategic Fit: 5 (Differentiated positioning vs. competitors)

**Key strengths:**
- Aligns repayment with daily income cycles
- Lower psychological barrier ("just ₦500 per day")
- Reduces default risk (catch problems early)
- Cultural fit (daily market culture)

**Key concerns to validate:**
- Collections operational complexity (daily vs. monthly)
- Payment processing fees on small amounts
- Customer discipline (remembering daily vs. monthly)
- Risk: daily payment failure creates daily friction

---

#### 3. Merchant Trust Score - Score: 4.20

**Scores:**
- Customer Value: 5 (Solves cold-start problem for unbanked)
- Feasibility: 3 (Requires merchant onboarding and verification system)
- Viability: 3 (Could increase approval rates but adds operational cost)
- Desirability: 5 (Community-based trust resonates culturally)
- Strategic Fit: 5 (Highly differentiated, builds local ecosystem)

**Key strengths:**
- Leverages existing social trust networks
- Differentiates from competitors using only bureau data
- Builds merchant ecosystem (potential future business line)
- Culturally appropriate (community vouching)

**Key concerns to validate:**
- Fraud risk (collusion between borrower and merchant)
- Merchant incentive structure (why would merchants participate?)
- Operational complexity of merchant verification
- Scalability beyond initial pilot markets

---

#### 4. Transaction Analyzer → Business Insights Dashboard - Score: 4.00

**Scores:**
- Customer Value: 4 (Helps customers grow revenue, not just borrow)
- Feasibility: 4 (Reuses existing transaction analysis infrastructure)
- Viability: 4 (Increases stickiness, potential premium tier revenue)
- Desirability: 4 (Empowering, positions FairCredit as partner not lender)
- Strategic Fit: 4 (Moves beyond lending toward financial platform)

**Key strengths:**
- Repurposes existing ML infrastructure (low marginal cost)
- Creates stickiness even when not borrowing
- Helps customers succeed → better repayment
- Differentiates from pure lenders

**Key concerns to validate:**
- Value perception (do traders want insights or just money?)
- Complexity of making insights actionable
- Data quality from mobile money (sufficient for insights?)
- Competitive response (easy to copy?)

---

#### 5. Loan + Business Training - Score: 4.00

**Scores:**
- Customer Value: 5 (Knowledge + capital = transformative)
- Feasibility: 3 (Requires partnerships or content creation)
- Viability: 3 (Increases CAC, unclear if improves retention enough)
- Desirability: 5 (Empowerment narrative, strong brand differentiation)
- Strategic Fit: 4 (Social impact mission, but operational distraction?)

**Key strengths:**
- Addresses root cause (lack of business knowledge) not just symptom
- Strong CSR and social impact story
- Could improve repayment by improving business success
- Differentiated positioning ("not just a lender")

**Key concerns to validate:**
- Operational distraction from core lending product
- Cost structure (who creates/delivers training?)
- Effectiveness measurement (does training actually help?)
- Customer willingness to spend time on training vs. just wanting money

---

### Selected Top 3 Ideas for Validation

Based on scores and strategic portfolio balance:

**SELECTED #1: USSD for Feature Phones**
- Highest score, clearest path to 10x market expansion
- Validation focus: UX complexity, user education needs

**SELECTED #2: Daily Micro-Payments**
- Strong customer-value fit, operational questions to resolve
- Validation focus: Collections complexity, customer discipline

**SELECTED #3: Merchant Trust Score**
- High differentiation, ecosystem play
- Validation focus: Fraud risk, merchant incentive design

**Why not #4 (Business Insights)?** Portfolio balance - want one moonshot. Business insights is incremental enhancement; merchant trust score is more transformative.

**Why not #5 (Business Training)?** Risk of operational distraction from core product. Revisit after achieving PMF on lending.

---

### Evaluation Insights

**Patterns observed:**
- SUBSTITUTE and ELIMINATE ideas scored highest (simplification and accessibility)
- REVERSE ideas were creative but lower feasibility
- COMBINE ideas had great customer value but operational complexity

**Scoring challenges:**
- Viability hard to estimate without unit economics modeling
- Strategic Fit subjective (what's "vision" for early-stage startup?)

**Surprises:**
- "Borrower-proposed interest rate" (Reverse #3) ranked lower than expected - creative but operationally complex
- "WhatsApp instead of SMS" (#6) scored well but not transformative enough for top 3

---

## Example 2: AsyncFlow (Southeast Asia Remote Collaboration) - Abbreviated

### Context

**Ideas generated:** 35 ideas from SCAMPER
**Strategic context:** B2B SaaS in growth phase. Have product-market fit, now optimizing and differentiating. Engineering team of 8, need to prioritize ruthlessly.

### Evaluation Criteria & Weights

**Strategic Context:** Growth-stage SaaS prioritizing differentiation and retention over raw acquisition.

| Dimension | Weight |
|-----------|--------|
| Customer Value | 25% |
| Feasibility | 20% |
| Viability | 20% |
| Desirability | 25% (differentiation matters) |
| Strategic Fit | 10% |

### Top 10 Scored Ideas

| Rank | Idea | Type | Total Score |
|------|------|------|-------------|
| 1 | Remove real-time presence indicators | ELIMINATE | **4.15** |
| 2 | Async video messages (Loom-style) | SUBSTITUTE | **4.05** |
| 3 | Message threads → knowledge base | PUT TO OTHER USES | **3.95** |
| 4 | Auto-include context in messages | MODIFY | **3.90** |
| 5 | Office hours concept | ADAPT | **3.75** |
| 6 | Daily digest instead of real-time | SUBSTITUTE | **3.70** |
| 7 | Timezone data → work-life monitoring | PUT TO OTHER USES | **3.55** |
| 8 | Async-first default, justify live meetings | REVERSE | **3.50** |
| 9 | 25-minute meeting cap enforced | MODIFY | **3.40** |
| 10 | Task completion → auto-documentation | COMBINE | **3.35** |

### Selected Top 3 Ideas

**#1: Remove Real-Time Presence** - Highest score, bold differentiation
**#2: Async Video Messages** - Clear customer demand, moderate build
**#3: Auto-Context in Messages** - High value-add, leverages existing data

Rejected #4 (Message threads → KB) due to overlap with existing features.

---

## Example 3: SolarSeva (Rural India Home Solar) - Abbreviated

### Context

**Ideas generated:** 40 ideas from SCAMPER
**Strategic context:** Early-stage hardware + financing. Need to prove model in Rajasthan before scaling. Capital-constrained, service network building.

### Evaluation Criteria & Weights

**Strategic Context:** Capital-constrained, proving unit economics. Prioritize viability and feasibility.

| Dimension | Weight |
|-----------|--------|
| Customer Value | 25% |
| Feasibility | 30% (resource constraints) |
| Viability | 30% (must work economically) |
| Desirability | 10% |
| Strategic Fit | 5% |

### Top 10 Scored Ideas

| Rank | Idea | Type | Total Score |
|------|------|------|-------------|
| 1 | Grid-tie instead of batteries | SUBSTITUTE | **4.25** |
| 2 | Modular panels (add capacity over time) | MODIFY | **4.10** |
| 3 | Technician network → other repairs | PUT TO OTHER USES | **3.95** |
| 4 | Solar + water purification bundle | COMBINE | **3.85** |
| 5 | Monitoring → home security system | PUT TO OTHER USES | **3.75** |
| 6 | Community solar (shared system) | REVERSE | **3.65** |
| 7 | Subscription tiers (Netflix model) | ADAPT | **3.60** |
| 8 | DC-only appliances (no inverter) | ELIMINATE | **3.50** |
| 9 | Micro-insurance bundled | COMBINE | **3.45** |
| 10 | Ship pre-assembled (no install appt) | ELIMINATE | **3.20** |

### Selected Top 3 Ideas

**#1: Grid-Tie Instead of Batteries** - Dramatically reduces cost, improves economics
**#2: Modular Panels** - Lower entry price, flexible growth, reduces default risk
**#3: Technician Network for Other Repairs** - Monetizes existing asset, improves tech retention

Rejected #4 (Solar + Water) because it distracts from proving core model first.

---

## Example 4: Unbroken (Sweden Disaster Logistics) - Abbreviated

### Context

**Ideas generated:** 38 ideas from SCAMPER
**Strategic context:** B2B enterprise software, targeting large organizations. Long sales cycles, high expectations for reliability. Small team (6 people).

### Evaluation Criteria & Weights

**Strategic Context:** Enterprise SaaS requiring high reliability and clear ROI. Feasibility critical given small team.

| Dimension | Weight |
|-----------|--------|
| Customer Value | 30% (ROI must be clear) |
| Feasibility | 30% (small team, high reliability bar) |
| Viability | 20% |
| Desirability | 10% |
| Strategic Fit | 10% |

### Top 10 Scored Ideas

| Rank | Idea | Type | Total Score |
|------|------|------|-------------|
| 1 | Optimization algorithm for normal ops | PUT TO OTHER USES | **4.20** |
| 2 | 30 days offline capability | MODIFY | **4.10** |
| 3 | Mesh network → post-disaster comms | PUT TO OTHER USES | **3.95** |
| 4 | Logistics + crisis communication platform | COMBINE | **3.85** |
| 5 | Extreme data compression for satellite | MODIFY | **3.75** |
| 6 | Edge-to-center (not center-to-edge) | REVERSE | **3.70** |
| 7 | Offline maps + manual updates | SUBSTITUTE | **3.65** |
| 8 | Inventory + predictive disaster modeling | COMBINE | **3.55** |
| 9 | Blockchain for distributed consensus | SUBSTITUTE | **3.40** |
| 10 | Military supply chain tactics | ADAPT | **3.35** |

### Selected Top 3 Ideas

**#1: Use for Normal Ops, Not Just Disasters** - Addresses biggest objection ("only useful in disasters")
**#2: 30 Days Offline Capability** - Dramatic differentiation, technically challenging but achievable
**#3: Mesh Network for Communications** - Expands value prop, leverages core tech

Rejected #4 (Crisis Communication Platform) as scope creep - stay focused on logistics.

---

## Cross-Cutting Insights

### Patterns Across All Four Examples

**Scoring patterns:**
- **PUT TO OTHER USES** ideas consistently scored well (low-hanging fruit - repurpose existing assets)
- **ELIMINATE** ideas often surprised with high customer value (less is more)
- **REVERSE** ideas were creative but frequently had feasibility challenges
- **COMBINE** ideas: high potential but operational complexity often dragged scores down

**Weighting patterns:**
- Early-stage companies weighted Customer Value highest (find PMF)
- Resource-constrained companies weighted Feasibility highly
- Growth-stage companies balanced more evenly
- Enterprise B2B weighted Feasibility and Viability highest (reliability matters)

**Selection patterns:**
- Top 3 usually span different SCAMPER types (diversity of approach)
- #1 idea usually clear winner (0.2+ point gap)
- #2 and #3 often close scores, decided by strategic fit or portfolio balance
- Wild card ideas (low score but interesting) often REVERSE or ADAPT

### Evaluation Challenges

**Hardest dimensions to score:**
- **Viability**: Requires financial modeling, unit economics assumptions
- **Strategic Fit**: Subjective, depends on how you interpret "vision"
- **Desirability**: Emotional appeal hard to predict without customer research

**Easiest dimensions:**
- **Feasibility**: Can assess against Closed World resources objectively
- **Customer Value**: PRFAQ and JTBD provide clear grounding

### Common Mistakes Observed

**1. Feasibility bias:** Teams over-weight "easy to build" and miss transformative ideas
**2. Neglecting portfolio balance:** Top 3 all incremental, no moonshots
**3. Scoring in vacuum:** Not comparing ideas relatively ("Is this better than that?")
**4. Confusing evaluation with validation:** Trying to prove ideas work during scoring (save for Six Hats)
**5. Analysis paralysis:** Spending hours debating 3.2 vs. 3.4 scores

---

## Tips from Examples

**From FairCredit:**
- Don't eliminate radical ideas too early (USSD seemed crazy, became #1)
- Cultural fit can overcome feasibility concerns (merchant trust score)
- Operational complexity of COMBINE ideas often underestimated

**From AsyncFlow:**
- ELIMINATE ideas can be powerful differentiators (removing presence = bold)
- PUT TO OTHER USES finds quick wins (repurpose existing data/features)
- Weight Desirability higher for differentiation plays

**From SolarSeva:**
- When capital-constrained, Viability must be weighted heavily
- Modular approaches (MODIFY) reduce risk and improve accessibility
- Repurposing people/networks (PUT TO OTHER USES) is underrated

**From Unbroken:**
- For enterprise, Feasibility and reliability trump creativity
- "Use for normal ops" addresses biggest enterprise objection (infrequent use)
- Small teams must be ruthless about scope (COMBINE often too ambitious)

---

## Ready for Next Phase

All four examples show that idea evaluation successfully narrows 30-50 ideas to 3-5 for deep validation.

**Next step:** Use the critical-validation skill (Six Thinking Hats) to deeply validate the top 3-5 ideas from each example, testing assumptions and identifying risks before committing to implementation.

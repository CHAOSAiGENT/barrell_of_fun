# Wall of Death Dashboard - Project Context Log

**Project**: Wall of Death Viability Calculator + Business Documentation
**GitHub**: https://github.com/CHAOSAiGENT/barrell_of_fun
**Live URL**: https://chaosaigent.github.io/barrell_of_fun

---

## PHASE 1: FINANCIAL CALCULATOR ✅ COMPLETE

**Delivered**: `index.html` - Interactive React dashboard with:
- Financial modeling (revenue, costs, profit, margin)
- Sensitivity analysis (5 stress tests)
- Scenario builder (4 presets)
- Validation checklist (17 items)
- Export (JSON, CSV, shareable URL)

**Key Validated Assumptions Baked In**:
- 40 events/year target (breakeven ~24)
- Insurance: $171/event OR $326/year annual ($6.5K swing)
- Pricing: Fairs $8-12K, Festivals $6-10K, Corporate $10-15K
- Ancillary: $500-1.5K/event (merch, VIP, streaming, sponsorship)

**Mobile Note**: Calculator works on mobile but tables (Sensitivity, Scenarios) need horizontal scroll. Acceptable for Phase 1.

---

## PHASE 2: BUSINESS DOCUMENTATION INTEGRATION 🔄 NEXT

### ⚠️ CRITICAL: AUDIENCE & MESSAGING CONTEXT

**Primary Audience**: People with NO business-building experience who are 100% optimistic this will be easy.

**The Problem We're Solving**:
- Audience thinks "we'll figure it out as we go"
- They underestimate complexity of insurance, booking cycles, cash flow timing
- They see Jake's performer skills but don't grasp why business planning matters
- They need to understand that *guessing kills businesses* - research is how you survive

**The Bias to Overcome**:
Even though Jake Wheeler's executive profile shows business experience, the audience reading this documentation does NOT have that background. They have optimism bias and need to be educated on:
1. WHY each section exists (not just what it says)
2. WHAT that section covers and why it matters
3. WHY real research - not assumptions - is the difference between success and failure

**Jake Wheeler's Business Experience = Massive Asset**:
His executive background isn't just a nice-to-have. It directly impacts:
- **Financing**: Lenders/investors see experienced operator, not just a performer
- **Investment**: Reduces perceived risk; improves terms
- **Insurance**: Carriers give better rates to operators with business track record
- **Vendor relationships**: Fair directors trust someone who speaks their language
- **Operational discipline**: Knows cash flow, margins, contingency planning

This needs to be called out explicitly in BOTH versions. Jake having done this before isn't trivia - it's a core competitive advantage that de-risks the entire venture.

---

### Section-Level Messaging Requirements

**EVERY section in both Easy Mode and The Book must include:**

1. **WHY THIS MATTERS** (1-2 sentences)
   - What problem does this section solve?
   - What happens if you skip this?

2. **WHAT THIS COVERS** (brief overview)
   - Key topics/decisions addressed
   - What you'll know after reading

3. **WHY RESEARCH, NOT GUESSING** (specific to section)
   - What assumptions are dangerous here?
   - What real-world validation was done?
   - What could go wrong if you just "wing it"?

**Example - Insurance Section:**
> **WHY THIS MATTERS**: Insurance isn't optional - no venue will book you without it, and one accident without coverage ends the business permanently.
>
> **WHAT THIS COVERS**: Per-event vs annual policies, actual quoted costs, what's covered vs excluded, and why Jake's experience gets better rates.
>
> **WHY RESEARCH, NOT GUESSING**: We called 5+ specialty brokers and got real quotes. The difference between "I assume insurance is $5K" and "I have a quote for $326/year annual" is the difference between a business plan and a fantasy.

---

### File Structure Understanding

**The Deep_Cuts folder uses a T-tier naming system:**
- **T1 (Foundation Research)**: Competitive intel, market analysis, benchmarking, historical context - COMPLETE
- **T2 (Strategy)**: Revenue model, geographic opportunity, regulatory - MOSTLY DONE
- **T3 (Content/Marketing)**: Industry trends, crew roles - DONE
- **T4 (Operations Reality)**: Detailed cost/revenue/operations punch list - COMPREHENSIVE

**IMPORTANT**: Files with `((RENAME))` or duplicate numbering (01-, 1-, 1_) are earlier versions. The **T-series files are canonical**.

### Canonical Source Files

**Primary Business Docs (need updating)**:
```
/Initial Docs and Checklists/
├── Strategic Assessment Document.md      ← Main assessment
├── Wall_of_Death_Business_Plan.md        ← Main business plan
├── Integration-Updates.md                 ← CRITICAL: Revision checklist for Jake Wheeler integration
├── Jake-Wheeler-Profile_EXECUTIVE_ADDENDUM.md  ← KEY: His biz experience = competitive advantage
├── Executive_Profile_Addendum.md
└── RESEARCH_ADDENDUMS_FOR_DOCUMENTS.txt
```

**Canonical Research Files (T-series)**:
```
/Deep_Cuts/
├── T2-05_Revenue-Model-Analysis.md
├── T2-06_Geographic-Market-Opportunity.md
├── T2-07_Regulatory.md
├── T3-08_Industry-Trends.md
├── T3-09_Crew-Roles.md
├── T4-10-Equipment.md
├── T4-10_Cost-Breakdown.md
├── T4-11-Insurance.md
├── T4-12-Marketing.md
├── T4-13-Financials.md
├── T4-14-Bookings.md
├── T4-15-Equipment Build Timeline & Costs.rtf
├── T4-16-Recruitment.md
├── T4-16_liability_legal.md
├── T4-17-Fair-Director-Outreach.md
├── T4-17_insurance_architecture.md
├── T4-18-Competitive-Pressure.md
├── T4-18_performer_safety.md
├── T4-19-Worst-Case-Financial.md
├── T4-19_through_t4-25_operations.md    ← COMPREHENSIVE operations framework
└── T4-20-Weekly-Monthly-Checklist.md
```

**Validated Data**:
```
/VALIDATION_FINDINGS_VS_T4.md            ← Market research validating assumptions
```

**SKIP these (duplicates/older versions)**:
- Any file with `((RENAME))` in name
- Files starting with `01-`, `02-`, `1-`, `2-`, `1_`, `2_`, etc.

---

### Output Specifications

#### Format 1: "Easy Mode" (The Pitch)
**Audience**: Non-business people, optimism bias, want quick answers
**Tone**: Conversational, visual, encouraging but honest - EDUCATE, don't just inform
**Structure**:
- Executive summary (1 page max)
- "Can this work?" → YES, here's why
- "What does it cost?" → Simple breakdown
- "What could go wrong?" → Top 5 risks (brief)
- "Next steps" → Clear action items
- **Jake Wheeler's Business Edge** → Why his experience de-risks everything
**Length**: 5-10 pages equivalent

**EVERY SECTION MUST INCLUDE**:
- Why this section matters (what breaks if you skip it)
- What it covers (brief)
- Why we researched this instead of guessing (specific example)

**⚠️ MOBILE-FIRST DESIGN REQUIRED**:
- Primary audience will view on mobile
- Use cards/collapsible sections, NOT tables
- Large touch targets (44px minimum)
- Single-column layout that stacks naturally
- No horizontal scrolling required
- Expandable FAQ-style sections preferred

#### Format 2: "The Book" (Full Analysis)
**Audience**: Serious stakeholders, investors, partners
**Tone**: Professional, thorough, doesn't sugarcoat
**Structure**:
- Complete business plan (updated per Integration-Updates.md)
- Strategic assessment (validation framework)
- Jake Wheeler integration (profile, competitive advantage, business experience impact)
- All financial projections with assumptions
- Risk matrix with mitigation strategies
- Regulatory/insurance deep dive
- Operational playbook references
**Length**: 50+ pages equivalent

**EVERY SECTION MUST INCLUDE**:
- Why this section matters (business context)
- What it covers (detailed)
- Research methodology (how we validated, not guessed)
- Jake Wheeler advantage (where his experience specifically helps)

**Desktop-optimized, mobile-tolerable**:
- Tables allowed (detailed data requires them)
- Include soft nudge at top: "For best experience with detailed tables, view on desktop"
- NOT a block - just a recommendation
- Collapsible chapter navigation for mobile users
- Tables should still be horizontally scrollable on mobile

---

### Jake Wheeler Business Experience - Integration Points

**READ**: `/Initial Docs and Checklists/Jake-Wheeler-Profile_EXECUTIVE_ADDENDUM.md`

**Where His Business Background Creates Advantage** (call out in both versions):

| Area | How Jake's Experience Helps | Impact |
|------|---------------------------|--------|
| **Financing** | Lenders see operator with business track record, not just performer | Better loan terms, higher approval odds |
| **Investment** | Investors perceive lower risk with experienced operator | Easier fundraising, better valuations |
| **Insurance** | Carriers rate experienced operators lower risk | $2-5K/year savings on premiums |
| **Vendor Relations** | Speaks fair directors' language (contracts, logistics, ROI) | Faster booking conversions |
| **Operations** | Understands cash flow, margins, contingency planning | Fewer surprises, better survival odds |
| **Crew Management** | Has hired/managed teams before | Lower turnover, better culture |
| **Crisis Response** | Business experience = calm under pressure | Problems get solved, not panicked |

**Messaging**: Jake isn't just a world-class performer - he's a business operator who happens to ride motorcycles on walls. That combination is extremely rare and directly translates to lower risk and higher success probability.

---

### Mobile/Responsive Design Requirements

**Audience Reality**:
| Format | Primary Device | Design Priority |
|--------|---------------|-----------------|
| Easy Mode | Mobile | Mobile-first |
| The Book | Desktop | Desktop-first, mobile-tolerable |
| Calculator | Mixed | Currently acceptable |

**Easy Mode - Mobile-First Rules**:
- NO multi-column tables (use stacked cards instead)
- Collapsible/expandable sections (accordion style)
- Key numbers in large, tappable stat cards
- Progress indicators visual, not tabular
- Touch-friendly controls (min 44px)
- Content chunks ≤ 300 words before visual break
- "Why this matters" callouts in highlighted boxes

**The Book - Desktop-First with Mobile Fallback**:
- Tables allowed but must be horizontally scrollable
- Add banner: "📱 Viewing on mobile? Rotate device or scroll tables horizontally. Best viewed on desktop."
- Chapter navigation should collapse to hamburger menu on mobile
- Long-form content acceptable (investors expect depth)
- Include "Download PDF" option for offline/print review

---

### Integration Checklist (from Integration-Updates.md)

- [ ] Create new Section 2 - Leadership & Team (Jake Wheeler profile + business experience)
- [ ] Renumber all subsequent sections
- [ ] Update Table of Contents
- [ ] Revise Section 1.3 - Competitive Landscape
- [ ] Revise Section 3.1 - Equipment costs (Jake's welding savings)
- [ ] Revise Section 4 - Revenue models (bicycle act section)
- [ ] Revise Section 9 - Financial projections (Jake impact table)
- [ ] Update Executive Summary (emphasize Jake's dual performer/operator advantage)
- [ ] Add organizational chart reference

**Key Jake Wheeler Value-Add**:
- Equipment cost reduction: -$10-25K (welding expertise)
- Maintenance savings: -$3-5K/year
- Insurance improvement: -$2-5K/year (business experience = lower risk rating)
- Bicycle act premium revenue: +$60-100K
- **Total Year 1 impact: +$81-143K**

---

### Dashboard Integration

**Current Tabs**: Dashboard, Assumptions, Sensitivity, Scenarios, Validation

**New Tabs to Add**:
6. **📋 Quick Guide** (Easy Mode) - Mobile-first, educational
7. **📚 Full Plan** (The Book) - Desktop-first, comprehensive

---

## Status

| Phase | Status | Date |
|-------|--------|------|
| Phase 1: Calculator | ✅ Complete | 2026-01-18 |
| Phase 2: Documentation | ✅ Complete | 2026-01-19 |

---

## PHASE 2 WORK LOG

### Session: 2026-01-18 → 2026-01-19 (COMPLETED)

**Task**: Create Easy Mode (Quick Guide) and The Book (Full Plan) documentation tabs

**Files Read**:
- CONTEXT_LOG.md ✅
- Integration-Updates.md ✅  
- Jake-Wheeler-Profile_EXECUTIVE_ADDENDUM.md ✅
- index.html (existing dashboard) ✅

**Work Completed**:
- [x] EasyModeGuide component (mobile-first, educational)
- [x] FullPlanGuide component (desktop-first, comprehensive)
- [x] Dashboard integration (new tabs: 📋 Quick Guide, 📚 Full Plan)
- [x] Tab rendering fixed (activeTab conditionals added 2026-01-19)

**Key Design Decisions**:
1. Both formats emphasize WHY-WHAT-WHY RESEARCH structure
2. Jake Wheeler's business advantage called out explicitly in EVERY relevant section
3. Easy Mode uses collapsible cards (no tables, single-column, mobile-first)
4. The Book uses chapter navigation with detailed tables (desktop-first with mobile scroll)
5. Educational tone to overcome optimism bias with real examples

**Components Delivered**:

**1. EasyModeGuide (📋 Quick Guide tab)**
- Mobile-first collapsible card design (44px touch targets)
- 8 Sections: Big Picture, Jake Wheeler's Edge, Insurance, Booking, Competition, Cash Flow, Risks, Next Steps
- Every section includes: WHY matters, WHAT covers, WHY researched
- Jake Wheeler advantages highlighted with dollar impact ($81-143K Year 1)
- CTA button linking to Full Plan

**2. FullPlanGuide (📚 Full Plan tab)**
- Desktop-first with chapter navigation (7 chapters)
- Chapters: Overview, Jake Wheeler, Market Analysis, Insurance, Operations, Financials, Risk Matrix
- Detailed tables with horizontal scroll on mobile
- Soft desktop nudge at top
- Complete financial projections with Jake Wheeler impact breakdown
- Comprehensive risk matrix with mitigation strategies

**Key Numbers Validated in Both Formats**:
- Break-even: ~24 events
- Target: 40 events/year  
- Year 1 profit (40 events): $178K+ base, $218-248K with Jake advantage
- Insurance: $171/event vs $326/year annual (annual saves $6,500+ at 40 events)
- Jake Wheeler Year 1 Impact: +$81,000-$143,000
- Booking window: October-February (miss = 70% season lost)
- Cash reserves needed: $25-50K

---

## Notes for Next Chat

**Key Context to Carry Forward**:
1. Audience has ZERO business experience and 100% optimism bias
2. Every section must explain WHY it matters, WHAT it covers, WHY research beats guessing
3. Jake Wheeler's business background is a MAJOR competitive advantage - call it out everywhere
4. Easy Mode = mobile-first, educational, overcome optimism bias
5. The Book = comprehensive, still educational, Jake's experience woven throughout

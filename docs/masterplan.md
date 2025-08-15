## Elevator Pitch
A calm, mobile-first personal finance app for adults with dyscalculia or trauma-related money stress. Uses visuals, supportive language, and accessibility-first design to make budgeting non-threatening and empowering.

## Problem & Mission
- **Problem:** Traditional budgeting apps overwhelm users with numbers, jargon, and dense layouts.
- **Mission:** Create a stress-free way to understand, plan, and track money through visual, plain-language tools.

## Target Audience
- Adults with dyscalculia
- People with trauma-related difficulties handling numbers
- Anyone seeking a gentle, visual-first alternative to spreadsheets

## Core Features
- Warm homepage with easy visual insights
- Visual budget dashboard (color-coded, card-based)
- Safe spending planner (drag-and-drop goal jars)
- Transaction journal (icons, colors, and notes)
- Onboarding & personalization (comfort mode, accessibility)
- Educational micro-tips
- Optional AI “Money Story” summaries

## High-Level Tech Stack
- **Frontend:** Vite + React + TypeScript + Tailwind + shadcn/ui — fast, accessible, responsive.
- **Backend:** Supabase — real-time, simple auth, integrated DB.
- **Auth:** Email/password + optional Google OAuth.
- **Hosting:** Vercel for frontend, Supabase hosting backend.
- **AI:** OpenAI API for “Money Story” summaries.

## Conceptual Data Model (in words)
- **User:** profile, settings, comfort mode, preferences
- **Account:** linked financial account or manual entry
- **Transaction:** date, amount, category, icon/emoji, optional note
- **BudgetCategory:** name, color, goal amount
- **Goal:** target, jar allocation, progress status
- **Tip:** short text, link, type

## UI Design Principles
- **Don’t make me think:** Always lead with visuals before numbers.
- **Comfort mode:** Larger fonts, softer colors.
- **One screen, one job:** Avoid cognitive overload.

## Security & Compliance
- Encrypted storage of all personal and transaction data.
- GDPR/CCPA-compliant data controls.
- No sensitive card/bank credentials stored directly.

## Phased Roadmap
- **MVP:** Homepage, visual budget dashboard, spending planner, onboarding, basic auth.
- **V1:** Transaction journal, educational tips, full accessibility settings.
- **V2:** AI “Money Story”, bank account integrations, deeper personalization.

## Risks & Mitigations
- **Risk:** Users overwhelmed by onboarding → **Mitigation:** Progressive disclosure & skip options.
- **Risk:** Accessibility gaps → **Mitigation:** WCAG AA compliance & user testing.

## Future Expansion
- Multi-currency support.
- Shared budgeting for households.
- Community challenges (opt-in).

---
name: Serene Grace
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#444651'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#222a3e'
  on-tertiary: '#ffffff'
  tertiary-container: '#384055'
  on-tertiary-container: '#a4acc5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  scripture-quote:
    fontFamily: Noto Serif
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Source Sans 3
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses reverent serenity, structured clarity, and warm hospitality. Tailored for a modern ministry and community space, it balances the timeless solemnity of sacred gatherings with an approachable, highly functional digital experience for both newcomers and existing congregants.

The aesthetic philosophy draws on **Warm Editorial Minimalism**:
- Generous, breathing white space that conveys calm and uncluttered peace.
- Sacred grounding through deep, contemplative navies combined with warm amber candlelight highlights.
- Clear structural division using subtle hairline borders and tinted paper surfaces rather than heavy artificial shadows.
- Dignified dual typography pairing a sturdy, humanistic sans-serif for functional reading with an elegant, literary serif for Scripture, liturgical themes, and editorial sermon headings.

## Colors

The color palette establishes a sacred, stable atmosphere anchored by Deep Navy and enriched by Warm Amber accents that suggest warm light, fellowship, and grace.

### Primary Palette
- **Deep Navy Base (`#1E3A8A`)**: Primary buttons, active state indicators, key brand iconography, and authoritative liturgical elements.
- **Midnight Slate (`#0F172A`)**: High-contrast text color, deep headers, and grounding footer surfaces.
- **Navy Tint Surface (`#EFF6FF`)**: Subtle background fills for announcements, active card badges, and service info highlights.

### Accent & Warmth
- **Warm Amber (`#D97706`)**: Secondary actions, calendar date tags, seasonal event highlights, and key liturgical moments.
- **Amber Glow (`#F59E0B`)**: Interactive hover states and high-attention callout highlights.
- **Warm Paper Tint (`#FEF3C7`)**: Soft container backgrounds for scripture quotes, baptism/membership notices, and fellowship banners.

### Neutrals & Foundation
- **Canvas Base (`#F8FAFC`)**: Page backdrop delivering an open, glare-free reading environment.
- **Surface Crisp (`#FFFFFF`)**: Card surfaces, modal sheets, and structured data tables.
- **Text Primary (`#0F172A`)**: Primary reading color with AA/AAA compliance on white and off-white bases.
- **Text Secondary (`#475569`)**: Subtext, metadata, schedule times, and secondary labels.
- **Border Hairline (`#E2E8F0`)**: Restrained separation lines for timetable grids, dividers, and card containers.

## Typography

The type system blends classical dignity with contemporary legibility.

- **Editorial & Scripture Role (`Noto Serif`, falling back to RIDIBatang / MaruBuri / Batang)**: Used across hero declarations, sermon series titles, section headings, and Scripture quotes. Scripture text requires an expanded line height (`line-height: 1.8` to `2.0`) to emulate fine devotional book typography.
- **Informational & Functional Role (`Source Sans 3`, falling back to Pretendard / Apple SD Gothic Neo)**: Employed for navigation menus, service timetables, location directions, shuttle schedules, and body prose.
- **Bilingual & CJK Balance**: Ensure `word-break: keep-all` is applied to Korean text across all headings and cards to avoid awkward word wraps and preserve natural phrase cadence.

## Layout & Spacing

A 12-column responsive fluid grid structured inside a constrained central reading column balances readability and data organization:

- **Desktop (1200px+)**: 12 columns, 24px (`1.5rem`) gutters, max container width of 1200px (standard layout) and 840px (sermon reading & devotional articles).
- **Tablet (768px - 1199px)**: 8 columns, 20px gutters, 32px side margins. Cards reflow from 3-column rows into 2-column or stacked formats.
- **Mobile (< 768px)**: 4 columns, 16px (`1rem`) gutters, 20px (`1.25rem`) side margins. Timetables transform into horizontal scrolls or single-column stacked disclosure cards.

Vertical rhythm adheres strictly to an 8pt step system (8px, 16px, 24px, 40px, 64px, 96px), ensuring predictable cadence between scripture headers, information cards, and map containers.

## Elevation & Depth

This system avoids harsh artificial drop shadows in favor of calm, surface-driven hierarchy:

- **Level 0 (Canvas)**: `#F8FAFC` base surface for main page body.
- **Level 1 (Card & Content Blocks)**: `#FFFFFF` surface with a crisp 1px border (`#E2E8F0`). No shadow in passive state. Hover state reveals an ultra-subtle diffuse elevation: `box-shadow: 0 4px 20px -2px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Popovers, Sticky Tabs & Floating Map Controls)**: `#FFFFFF` with `box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.08)`.
- **Sacred Card Accent**: Tinted background containers using `#FEF3C7` (Amber tone) or `#EFF6FF` (Navy tone) with hairline internal borders to distinguish scripture callouts and notices without raising visual elevation.

## Shapes

The shape system conveys approachable poise. A moderate curve radius (`0.5rem` / 8px for standard components, `1rem` / 16px for prominent section containers) softens interface edges while keeping architectural rectitude intact.

- **Buttons & Form Fields**: 8px (`rounded-md`) for structured stability.
- **Info Cards & Map Wrappers**: 12px–16px (`rounded-lg` to `rounded-xl`) with clipped corners for media containers.
- **Pills & Status Badges**: Full radius (`9999px`) for service time tags, worship category markers, and quick transportation chips.

## Components

### 1. Graceful Tab Navigation (은혜로운 단아한 탭)
- **Visual Style**: Clean horizontal rail with ample breathing room. The active tab features an underline indicator in Primary Deep Navy (`#1E3A8A`) with a subtle serif weight boost, accompanied by a faint Navy tint (`#EFF6FF`) fill.
- **Accessibility**: ARIA role `tablist`, `tab`, and `tabpanel`. Fully keyboard navigable with left/right arrow keys.
- **Mobile**: Horizontal scrollable container with hidden scrollbars and left/right fade masks.

### 2. Timetable & Infographic Card (예배/모임 안내 표)
- **Table Structure**: Minimalist layout using `#FFFFFF` background, hairline borders (`#E2E8F0`), and `#0F172A` headings. Table headers are styled with muted text (`#475569`), small caps or `label-sm`, and subtle bottom borders.
- **Badges**: Service times (e.g., "1부 주일 오전 9:00", "2부 주일 오전 11:00") highlighted with a subtle Deep Navy badge (`bg-[#EFF6FF] text-[#1E3A8A] font-semibold`).
- **Infographic Card**: Composed of a soft icon container (tinted with Warm Amber or Navy), bold metric/name, descriptive metadata, and targeted location link.

### 3. Integrated Map Cards (지도 연동 카드)
- **Map View Container**: Fixed aspect ratio container (16:9 on mobile, 21:9 or 2-column split on desktop) with 12px rounded borders. Embedded Kakao Maps / Naver Maps viewport.
- **Action Strip**: Floating bottom bar or adjacent pane featuring direct action buttons: "카카오맵 길찾기" and "네이버 지도 보기" styled with dedicated neutral outlines and respective platform branded indicators.
- **Address Box**: Includes one-click copy button with clipboard feedback tooltip ("주소가 복사되었습니다").

### 4. Transportation & Parking Instruction Boxes (교통/셔틀/주차 안내)
- **Transit Segment Cards**: Structured cards grouped by category:
  - **Subway (지하철)**: Line number badges with authentic transit colors (e.g., Line 2 Green, Line 9 Gold) followed by exit number and walking distance in minutes.
  - **Bus (버스)**: Route numbers grouped by branch/trunk types with walking directions from nearest stops.
  - **Shuttle Bus (셔틀버스)**: Departure timetable card with highlighted next bus indicator and route path checklist.
  - **Parking (주차 안내)**: Clear capacity indicators, alternative parking lot locations, and fee subsidy instructions housed in an Amber Warm Tint (`#FEF3C7`) container to prevent visitor confusion.

### 5. Buttons, Inputs & Micro-Components
- **Primary Button**: Deep Navy background (`#1E3A8A`), crisp white text, 8px radius. Hover: `#0F172A`. Focus-visible: 2px ring offset with `#D97706`.
- **Secondary Button**: Crisp white surface, 1px border (`#E2E8F0`), text `#0F172A`. Hover: `#F8FAFC`.
- **Accent Button**: Warm Amber (`#D97706`), white text, used sparingly for registrations, giving, or new family welcome requests.
- **Form Inputs**: 44px minimum touch height, `#F8FAFC` background transitioning to `#FFFFFF` on focus, bordered by `#E2E8F0`, focusing to `#1E3A8A` ring.

### 6. Semantic Markup & Thymeleaf Fragment Conventions
- Structure UI components as modular Thymeleaf fragments:
  - `fragments/navigation.html :: header`
  - `fragments/worship-schedule.html :: timetable`
  - `fragments/location-card.html :: mapSection(address, kakaoUrl, naverUrl)`
  - `fragments/transit-info.html :: transitBox(subwayList, busList, parkingInfo)`
- Guarantee standard semantic landmarks: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, and `<footer>` for maximum accessibility and SEO performance.
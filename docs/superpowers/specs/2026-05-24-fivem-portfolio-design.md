# spec-fivem-portfolio-design

Design specification for building a premium, game-dashboard styled interactive Resume website for **Boss Ohm (หมอโอนิ)**, applying for a FiveM Admin position specializing in Event Coordination and Medical Department Management.

## Overview
A single-page application mockup representing a FiveM server administration console ("The Command Center"). Customized with real candidate details for Boss Ohm.

### Target Candidate Details
- **Name/IGN**: โอม / หมอโอนิ (Ohm / Mor Oni)
- **Age**: 31
- **Standby Hours**: 13:00 - 21:00
- **Total Experience**: ~4 Years across 4 major servers (Top One, Athena Season 1-3)
- **Role Specialties**: Player Support (In-game & Discord), Event Coordinator, Medical Department Lead (ดูแลหน่วยงานแพทย์), Staff Management
- **Key Traits**: Serious about duties, Punctual, Hardworking, Basic system config skills
- **Contacts**: Discord: `@ohmphiengz_`, Line: `@smallxoamz22`, Facebook: `Ohm Thanawat`

---

## Design System

### Color Palette (Fire Red & Orange Theme)
- **Background**: `#0c0d12` (Very dark charcoal/blue)
- **Card Background**: `#12131a` (Dark slate gray)
- **Border / Outline**: `#ff4e00` (Neon orange/red accent)
- **Secondary Accent**: `#ff8f00` (Neon yellow/orange accent)
- **Success Accent**: `#2ed573` (Neon green for ONLINE indicator)
- **Text Color**: `#f1f2f6` (Off-white)
- **Muted Text**: `#8a8d9f` (Muted gray)

### Typography
- Monospace font for logs: `'Courier New', monospace`
- Cyber/tech headers: `'Orbitron', sans-serif`
- Readability text: `'Inter', sans-serif`

---

## Layout & Components

### 1. Sidebar Navigation
- Sidebar stays fixed on desktop, toggleable slide-out on mobile.
- Neon status indicators.
- **Nav items**:
  - `OVERVIEW DASHBOARD` (Quick statistics, standby hours, server online status)
  - `EXPERIENCE & HISTORY` (Details of Top One, Athena Season 1-3)
  - `SKILLS & SPECIALTIES` (Specialties in Medical Admin and Event Planning)
  - `CONTACT STAFF` (Line, Facebook, Discord interactive contact widgets)

### 2. Main Header
- Server online mockup indicator with heartbeat pulse animation.
- Profile quick status: `F5M_ADMIN_SYS // ACTIVE STAFF: OHM (MOR ONI)`.

### 3. Widget Cards (Stats Overview)
- Stats boxes displaying:
  - Hours Played: `4+ Years`
  - Servers Moderated: `4 Major Servers (Top One, Athena S1-3)`
  - Active Hours: `13:00 - 21:00`
  - Core Focus: `Medical Department & Event Lead`

### 4. Interactive Console Log
- A simulated retro server log output box that typing-animates lines showing event details.
- Line entries customized to Boss Ohm's experience:
  - `[EVENT] Athena Season 3 Event hosted: Successful.`
  - `[MEDICAL] Medical Unit staff duty active: 40+ staff managed.`
  - `[SUPPORT] Discord Ticket #4912 resolved: player support completed.`

---

## Verification Plan

### Automated Tests
- Linting using ESLint.
- Responsive design validation across desktop (1920x1080) and mobile (375x812) using browser-based sizing.

### Manual Verification
- Open in local development server (`npm run dev`) and test all tab transitions, click interactions, and mobile menu layouts.

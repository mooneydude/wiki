# AI_GUIDANCE.md

This file provides guidance to AI models when working with this repository.

## Project Overview

This is a **project management repository** for renovating Aunt Liz's house to prepare it for market listing. This is NOT a software project - it's a real estate renovation project using markdown files for planning, tracking, and documentation.

## Repository Purpose

The repository tracks:
- Renovation tasks and timeline
- Budget and cost estimates
- Material selections (paint colors, carpet, doors)
- Vendor and contractor contacts
- Before/after photos

**Target outcome:** Complete renovation and list house on market by early January 2026.

## Document Architecture

### Core Planning Documents (READ THESE FIRST)
- **README.md** - Project overview and current status
- **QUICK-START.md** - Week 1 action checklist for getting started

### Primary Working Documents
- **TASKS.md** - Complete task list organized by renovation phases (7 phases from planning to listing). Update task statuses here as work progresses.
- **TIMELINE.md** - 10-week Gantt-style timeline with milestones, dependencies, and weekly status tracking
- **BUDGET.md** - Detailed cost breakdown by category ($10k-$21k estimate). Track actual expenses at bottom.
- **MATERIALS.md** - Paint color recommendations, carpet options, product specifications, and selection tracking
- **VENDORS.md** - Templates for documenting contractor quotes, vendor contacts, and references

### Key Decision Points Tracked
All documents have decision checkboxes to track:
- Paint color selections (recommended: Agreeable Gray SW 7029)
- Carpet type/color (recommended: neutral greige, nylon with stain protection)
- Contractor selections
- Budget approval
- Material orders

## How to Work With This Repository

### When Updating Project Status
1. Update task checkboxes in `TASKS.md` with ✅ or 🔄
2. Fill in actual costs in `BUDGET.md` expense tracking table
3. Update weekly status sections in `TIMELINE.md`
4. Update "Project Status" and target dates in `README.md`

### When Adding New Information
- Contractor quotes → `VENDORS.md`
- Material selections → `MATERIALS.md`
- Timeline changes → `TIMELINE.md`
- Budget actuals → `BUDGET.md`
- Photos → `photos/` directory (organize as `before/` and `after/` subdirectories)

### When Asked About Recommendations
Reference the specific recommendations already documented:
- Paint colors: See "Recommended Color Scheme" section in `MATERIALS.md`
- Carpet: See "Recommended Carpet Products" table in `MATERIALS.md`
- Budget priorities: See "ROI Focus" section in `BUDGET.md`
- Timeline: See "Critical Path Items" in `TASKS.md`

### Critical Dependencies to Understand
From `TIMELINE.md` and `TASKS.md`:
1. Carpet must be ordered early (2-4 week lead time)
2. Painting MUST be complete before carpet installation
3. All demolition must precede repairs
4. Photography requires completed staging

## Document Conventions

- All cost estimates show ranges (low-high)
- Timeline assumes professional contractors (DIY takes 2-3x longer)
- Neutral colors recommended throughout for resale appeal
- All major decisions require 3+ vendor quotes

## Common Updates You'll Make

**Progress tracking:**
```markdown
Status update in TASKS.md:
| ⬜ | Task name | → | ✅ | Task name |
```

**Budget tracking:**
```markdown
Add to expense table in BUDGET.md:
| Date | Category | Item | Vendor | Amount | Payment | Receipt |
```

**Timeline updates:**
```markdown
Update milestone in TIMELINE.md:
| Milestone | Target | ⬜ | Actual |
to
| Milestone | Target | ✅ | Nov 15 |
```

## Important Context

- Project start: November 4, 2025
- Estimated duration: 6-10 weeks
- Budget range: $10,285 - $21,230
- Target listing: Early January 2026
- House will be vacant during renovation
- Focus is on resale value, not personal preference

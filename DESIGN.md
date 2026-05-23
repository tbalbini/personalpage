# Slide System Design Inspired by McKinsey-Style Executive Presentations

> Category: Executive Business Slides / Consulting Decks  
> Purpose: Provide a reusable design and storytelling system for an AI agent that generates clean, analytical, McKinsey-style slides.  
> Default use case: strategy, performance, growth diagnostics, business reviews, operating plans, and executive decision-making decks.  
> Primary output: 16:9 presentation slides, usually in PowerPoint, Google Slides, or slide images.  
> Note: This is a consulting-style system inspired by the visual and narrative discipline of top-tier strategy decks. It is not a replica of any proprietary McKinsey template or brand asset.

---

## 1. Visual Theme & Atmosphere

The slide system should feel like a senior consultant prepared it for an executive committee: restrained, analytical, precise, and insight-led. The slide should not look like a dashboard, a marketing poster, or a decorative infographic. Every page must have one clear message, one dominant visual structure, and a tight hierarchy that allows the audience to understand the answer in less than 10 seconds.

The visual atmosphere is **white-canvas, black-text, single-accent, data-first**. Slides should feel dense enough to be useful, but never cluttered. The design should communicate intellectual rigor: aligned objects, consistent spacing, precise labels, clean charts, and strong “so what” titles. Decoration is almost nonexistent. Color exists to guide attention, not to beautify the slide.

A good slide in this system follows the classic consulting page logic:

**Action title → main exhibit → interpretation / implication → source and notes.**

The title should already contain the conclusion. The visual should prove the title. The annotation should explain why it matters. The footnote should make the analysis credible.

### Key Characteristics

- White background with disciplined use of black, gray, and one accent color.
- Every slide has a strong action title: not “Results by district”, but “Lima Cercado and Jesús María explain most of the incremental signal, while Trujillo remains frequency-constrained”.
- One main idea per slide. Avoid mixing unrelated analyses.
- Maximum of one primary chart or one main layout per slide.
- Consulting-style visual density: compact but readable.
- Data labels are preferred over heavy legends.
- Use callouts, braces, arrows, and small annotations to direct interpretation.
- Use muted gray for context and accent color only for the key message.
- Avoid decorative icons unless they help scanning or structure.
- Use precise units, timeframes, baselines, and comparison groups.
- Every chart must have a clear baseline and a clear interpretation.
- Slides should be built for executive reading, not presenter dependence.
- Appendix slides can be denser, but still require hierarchy and cleanliness.

---

## 2. Core Slide Philosophy

### 2.1 The Pyramid Principle

The deck should be structured from answer to evidence:

1. **Answer first**: start with the conclusion.
2. **Key arguments second**: show the 2–4 reasons that support the answer.
3. **Evidence third**: use charts, tables, and data cuts to prove each argument.
4. **Implications last**: translate analysis into decisions, actions, or risks.

A slide title is not a label. It is the sentence that the audience should remember.

Weak title:
> Performance by district

Strong title:
> Only two Lima districts clearly outperformed control, suggesting Ola 1 should scale selectively rather than uniformly

### 2.2 The Slide Contract

Each slide must answer four questions:

| Question | Slide element |
|---|---|
| What is the conclusion? | Action title |
| What evidence proves it? | Main exhibit |
| What should the audience notice? | Callouts / highlights |
| What does it imply? | Bottom takeaway / “so what” box |

### 2.3 The 10-Second Rule

A senior executive should understand the slide in 10 seconds:

- 3 seconds: read the title.
- 4 seconds: scan the main visual.
- 3 seconds: read the highlighted implication.

If the slide requires more than 10 seconds to understand the main message, reduce scope.

---

## 3. Color Palette & Roles

### 3.1 Default Palette

Use a restrained consulting palette.

| Role | Color | Hex | Usage |
|---|---:|---:|---|
| Canvas | White | `#FFFFFF` | Slide background |
| Primary text | Near Black | `#111111` | Titles, key labels, primary values |
| Secondary text | Dark Gray | `#4A4A4A` | Subtitles, secondary labels |
| Muted text | Medium Gray | `#6E6E6E` | Footnotes, axes, context labels |
| Light divider | Light Gray | `#D9D9D9` | Gridlines, separators, table borders |
| Soft fill | Very Light Gray | `#F3F4F6` | Background bands, inactive chips |
| Accent default | PedidosYa Pink | `#FA0050` | Main highlight / key insight |
| Accent alternate | Consulting Blue | `#005EB8` | Use only if no brand accent is provided |
| Positive | Green | `#1A7F37` | Positive variance only when needed |
| Negative | Red | `#C62828` | Negative variance / risk only when needed |
| Warning | Amber | `#B7791F` | Watchout / caution only when needed |

### 3.2 Accent Discipline

Use only one accent color per slide unless positive/negative semantics are essential.

Default rule:
- 80–90% neutral colors.
- 5–15% accent color.
- 0–5% semantic colors.

Use accent color for:
- Key bar in a chart.
- Main variance number.
- One highlighted cell.
- One important arrow or callout.
- Section divider or small headline rule.

Do not use accent color for:
- All chart bars.
- Decorative borders.
- Large backgrounds.
- Every number.
- Multiple unrelated highlights.

### 3.3 Chart Color Logic

| Situation | Recommended treatment |
|---|---|
| Single series bar chart | All bars gray, highlighted bar in accent |
| Baseline vs current | Baseline light gray, current dark gray or accent |
| Control vs test | Control gray, test accent |
| Positive / negative variance | Use green/red only if the slide is about performance polarity |
| Waterfall | Starting/ending bars dark gray, positive drivers accent or green, negative drivers red or muted gray |
| Stacked bars | Use 2–4 shades max; highlight only the segment relevant to the title |
| Matrix | Neutral grid with accent quadrant / border / dot |

---

## 4. Typography Rules

### 4.1 Font Family

Use fonts that are common in presentation environments.

Recommended:
- **Arial** for strict consulting look.
- **Aptos** for modern PowerPoint compatibility.
- **Helvetica Neue** or **Inter** for cleaner digital output.

Do not mix more than one font family in the same deck unless there is a specific brand requirement.

### 4.2 Type Hierarchy for 16:9 Slides

Assume slide size: **13.33 × 7.5 inches**.

| Role | Size | Weight | Color | Usage |
|---|---:|---:|---|---|
| Kicker / section label | 8–10 pt | Bold | Accent or gray | “Executive Summary”, “Deep dive”, “Appendix” |
| Action title | 22–30 pt | Bold | Near Black | Main conclusion |
| Subtitle / context line | 10–13 pt | Regular | Dark Gray | Scope, timeframe, comparison groups |
| Chart title, if needed | 11–13 pt | Bold | Near Black | Only if chart needs local title |
| Body text | 10–12 pt | Regular | Near Black | Bullets, explanations |
| Small labels | 8–10 pt | Regular | Dark Gray | Axis labels, data labels |
| Footnotes | 6.5–8 pt | Regular | Muted Gray | Sources, caveats |
| Big number | 28–44 pt | Bold | Near Black or accent | KPI hero values |
| Tag / chip | 8–9 pt | Bold | White or dark | Status labels |

### 4.3 Title Rules

Titles must be insight-driven. They should be written like a conclusion.

Preferred patterns:
- “X grew by Y, driven mainly by Z”
- “A is improving, but B remains the constraint”
- “Only X and Y show clear incremental signal vs control”
- “The gap is not volume quality; it is frequency conversion”
- “Ola 1 created a signal in Lima, but Trujillo requires a different playbook”

Avoid:
- “Results”
- “Overview”
- “Analysis”
- “Performance”
- “Districts”
- “Metrics”
- “KPI evolution”

### 4.4 Writing Style

- Use short, executive sentences.
- Avoid academic language.
- Avoid vague adjectives like “good”, “bad”, “interesting”, “strong” unless quantified.
- Prefer “because”, “driven by”, “explains”, “suggests”, “implies”.
- Do not over-explain obvious chart readings.
- Use “vs” consistently for comparisons.
- Use one decimal place only when it changes interpretation.
- Use absolute values and percentages together when possible.

---

## 5. Slide Layout Principles

### 5.1 Page Grid

Use a consistent invisible grid.

Recommended safe area:
- Outer margins: **0.35–0.50 in**.
- Title area height: **0.75–1.10 in**.
- Main exhibit area: **5.2–5.8 in** high.
- Footer area: **0.25–0.40 in**.

Suggested structure:

```text
┌──────────────────────────────────────────────────────────────┐
│ Kicker / section label                                       │
│ Action title: conclusion written as a sentence               │
│ Optional subtitle: timeframe, scope, comparison group         │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│ Main exhibit: chart / matrix / table / bridge / diagram       │
│                                                              │
│ Focus annotation / callout / implication                      │
│                                                              │
├──────────────────────────────────────────────────────────────┤
│ Source: ...                                      Page number  │
└──────────────────────────────────────────────────────────────┘
```

### 5.2 Alignment Rules

- Align all major objects to the same left edge.
- Titles, subtitles, charts, and footnotes should share a common x-axis unless layout intentionally breaks it.
- Chart labels should not float randomly.
- Callouts should align either to the visual element they explain or to the grid.
- Avoid diagonal arrows unless necessary.
- Do not allow chart labels to overlap bars, lines, or each other.
- Use consistent spacing between chart and commentary.

### 5.3 Spacing System

Use a simple spacing scale:
- 4 px: micro spacing between label and value.
- 8 px: tight grouping.
- 12 px: related components.
- 16 px: blocks within the same section.
- 24 px: major separation.
- 32 px: slide section separation.
- 48 px: large structural separation.

### 5.4 Whitespace Philosophy

Whitespace is not empty. It is how the slide tells the reader what matters.

Use whitespace to:
- Separate title from evidence.
- Group related chart elements.
- Make the key number stand out.
- Prevent the slide from feeling like a screenshot from a dashboard.

Do not fill every empty area. A clean slide often has 10–20% unused space.

---

## 6. Chart & Exhibit System

### 6.1 Chart Principles

Every chart must be built to prove the title.

Rules:
- Remove unnecessary borders.
- Minimize gridlines.
- Use direct labels instead of legends when possible.
- Sort bars logically: descending, chronological, or by funnel stage.
- Highlight only what matters.
- Add units in the axis title or data labels.
- Avoid 3D charts, shadows, gradients, and decorative effects.
- Keep chart titles optional; the slide title should do most of the work.
- Use callouts to explain interpretation, not to repeat numbers.

### 6.2 Data Label Rules

- Use labels on bars when there are fewer than 12 bars.
- Use axis labels when there are many points.
- Use `%`, `pp`, `k`, `M`, `€`, `S/` consistently.
- Use `+` for positive change and `–` for negative change.
- Use one decimal for percentages only when needed.
- Do not show more precision than the business decision requires.

Examples:
- `+6.4%`
- `+3.8pp`
- `59k`
- `€24.7M`
- `S/ 20`
- `84% of target`

### 6.3 Preferred Chart Types

| Business question | Preferred exhibit |
|---|---|
| What drove the change? | Waterfall / bridge |
| Which segments explain growth? | Contribution bar chart |
| Who outperformed control? | Indexed bar / variance vs control |
| Which lever is the constraint? | Driver tree / decomposition |
| Where should we focus? | 2×2 matrix |
| How did the KPI evolve? | Line chart with annotated inflection |
| How does performance compare across groups? | Clustered bar chart |
| What is the conversion funnel? | Funnel chart / step table |
| What actions should we take? | Decision matrix / action table |
| What is the plan over time? | Roadmap / Gantt-lite |

### 6.4 Waterfall / Bridge Rules

Use for explaining changes between baseline and current.

Structure:
1. Start bar: baseline.
2. Driver bars: positive and negative movements.
3. End bar: current.
4. Optional subtotal bars if there are natural groups.
5. Top callout: top drivers and contribution.

Design:
- Start and end bars: dark gray.
- Positive drivers: accent or medium gray.
- Negative drivers: red or light gray, depending on emphasis.
- Connector lines: light gray.
- Labels above bars whenever possible.
- If a label does not fit, place it outside with a small leader line.
- Show contribution percentage near each driver if it supports the story.
- Do not let labels collide with the third bar or any other bar.

Good title:
> Long Tail, Global KA, and Local Hero explain ~81% of Plan Ruta’s order growth vs January

### 6.5 Bar Chart Rules

Use for ranking, comparisons, and contribution.

Rules:
- Horizontal bars are better for long category names.
- Vertical bars are better for short time series or compact rankings.
- Sort descending unless chronology matters.
- Highlight the relevant bar in accent.
- Put values at the end of bars.
- Avoid legends when direct labeling is possible.
- Use muted gray for non-highlight bars.

### 6.6 Line Chart Rules

Use for trends over time.

Rules:
- Use no more than 3 lines.
- If there are more than 3 lines, split into small multiples or use a table.
- Highlight the focal line in accent; others in gray.
- Annotate major inflection points.
- Use markers only when they help reading.
- Avoid thick gridlines.
- Label the line endpoint directly.

### 6.7 Matrix Rules

Use for decision-making.

Common matrix:
- X-axis: business impact.
- Y-axis: feasibility, urgency, or performance gap.
- Quadrants should have simple labels.
- Highlight the recommended quadrant with a light accent fill or border.
- Use dots or cards, not crowded text.
- Use a bottom action note: “Scale”, “Fix”, “Monitor”, “Deprioritize”.

### 6.8 Table Rules

Tables are acceptable when exact comparison matters.

Rules:
- Use tables sparingly in main slides.
- Use no more than 6 columns in main slides.
- Left-align text, right-align numbers.
- Use light gray horizontal rules.
- Avoid heavy vertical borders.
- Highlight one row or column only.
- Use arrows or color only for key variances.
- In appendix, denser tables are allowed but still require structure.

---

## 7. Signature Slide Components

### 7.1 Action Title Block

The title is the most important component.

Specs:
- 22–30 pt.
- Bold.
- Near Black.
- Max 2 lines.
- If the title exceeds 2 lines, rewrite it.
- Add a small subtitle only if needed to explain timeframe or scope.

Template:

```text
[Conclusion] + [magnitude] + [driver / implication]

Example:
Plan Ruta grew +59k orders vs January, with Food Long Tail and KA segments explaining most of the uplift
```

### 7.2 Executive Takeaway Box

Use when the slide needs a strong bottom-line implication.

Specs:
- Background: `#F3F4F6` or very light accent tint.
- Border-left: 3–4 px accent.
- Text: 10–12 pt.
- Max 2 bullets.
- Place below main chart or on the right side.

Patterns:
- “Implication: ...”
- “Decision needed: ...”
- “Risk: ...”
- “Next step: ...”

### 7.3 Callout Label

Use to explain the chart’s most important point.

Specs:
- Small text: 9–11 pt.
- Accent headline or bold phrase.
- Thin leader line in gray.
- Avoid placing callouts over data.
- Max 2 callouts per slide.

Good callout:
> Jesús María and Lima Cercado are the only districts with clear positive spread vs control

Bad callout:
> These two bars are higher

### 7.4 Section Divider

Use to separate chapters in a deck.

Specs:
- White background.
- Small kicker in accent.
- Large chapter title.
- 2–4 bullet preview of what the section will answer.
- Optional thin accent line.
- No decorative full-bleed images unless explicitly requested.

### 7.5 Footnote / Source Bar

Every analytical slide should include a footnote.

Specs:
- 6.5–8 pt.
- Muted gray.
- Bottom left.
- Include source, date range, definitions, and caveats.
- Keep it concise.

Example:
> Source: BigQuery fact_peru_orders; Food + QC verticals; baseline Jan-2026; current Apr-2026; excludes cancelled orders.

### 7.6 Page Number

- Bottom right.
- 7–8 pt.
- Muted gray.
- Optional in appendix if deck is informal.
- Consistent across deck.

---

## 8. Slide Archetypes

### 8.1 Executive Summary Slide

Purpose:
- Give the answer upfront.
- Summarize 3–5 key messages.
- Highlight decisions or next steps.

Layout:
- Left: 3–5 numbered insights.
- Right: small KPI stack, mini chart, or decision summary.
- Bottom: “Recommended actions” row.

Rules:
- No more than 5 bullets.
- Each bullet should start with the conclusion.
- Bold the key metric or driver.
- Use one accent highlight per bullet or per row.

Example title:
> Ola 1 generated a clear Lima signal, but scaling should shift from geographic focus to lever-specific actions

### 8.2 Situation / Complication / Resolution Slide

Purpose:
- Frame a business problem.

Layout:
- Three columns:
  1. Situation
  2. Complication
  3. Resolution / question

Rules:
- Each column has one headline and 2–3 bullets.
- Use icons only if very simple.
- Use accent only on the resolution or key question.

Example:
> Growth is visible, but uneven district performance requires a sharper playbook for Ola 2

### 8.3 Waterfall Bridge Slide

Purpose:
- Explain change from baseline to current.

Layout:
- Top: action title.
- Center: waterfall.
- Right or bottom: top 3 drivers / implication.
- Footer: source and definitions.

Rules:
- Show absolute growth and driver contribution.
- Include contribution percentage when useful.
- Avoid crowded labels.
- Keep drivers to 5–8 max; group the rest as “Other”.

Example:
> Food Long Tail, Global KA, and Local Hero explain ~81% of Plan Ruta’s order growth vs January

### 8.4 Comparison vs Control Slide

Purpose:
- Evaluate incremental signal.

Layout:
- Left: grouped bars or indexed trend.
- Right: interpretation panel with 3 bullets.
- Optional: small methodology box.

Rules:
- Clearly define treatment, control, and benchmark.
- Avoid claiming causality unless design supports it.
- Use language like “signal”, “spread”, “outperformance”, “suggests”.
- Show spread in pp.

Example:
> Lima outperformed both control and benchmark in orders, while Trujillo did not yet show a comparable incremental signal

### 8.5 Driver Decomposition Slide

Purpose:
- Explain which lever caused the result.

Common formula:
```text
Orders = Active Customers × Frequency
```

Layout:
- Top: formula.
- Middle: three KPI cards or bar decomposition.
- Bottom: diagnosis by group.

Rules:
- Use the formula as the organizing logic.
- Do not add too many secondary drivers.
- State which lever is the constraint.

Example:
> The order gap is mainly an active-customer issue; frequency is nearly on target

### 8.6 District / Segment Ranking Slide

Purpose:
- Identify winners, neutral performers, and laggards.

Layout:
- Horizontal bar chart sorted by incremental spread.
- Use three zones:
  - Winners
  - Neutral
  - Laggards
- Right side: recommended action per group.

Rules:
- Use accent for winners.
- Use gray for neutral.
- Use red or muted gray for laggards depending on tone.
- Label values directly.

Example:
> Only Jesús María and Lima Cercado clearly outperform control; remaining districts require targeted lever actions

### 8.7 2×2 Decision Matrix Slide

Purpose:
- Translate analysis into decisions.

Layout:
- Matrix taking 60–70% of slide.
- Right side: decision bullets.
- Bottom: action owner / next step.

Rules:
- Use clear axes.
- Place items as dots or small labels.
- Highlight the “scale now” quadrant.
- Avoid more than 12 items.

Example:
> Scale districts with high incremental signal and high operational readiness; redesign playbook for low-frequency markets

### 8.8 Initiative Roadmap Slide

Purpose:
- Show what happens next.

Layout:
- Rows: workstreams.
- Columns: weeks, months, or phases.
- Right: expected outcome.

Rules:
- Use a Gantt-lite style.
- Keep bars flat and simple.
- Use accent only for critical path.
- Add decision gates if needed.

Example:
> Ola 2 should move from broad district activation to sequenced lever deployment by market archetype

### 8.9 Action Plan Slide

Purpose:
- Make decisions operational.

Layout:
- Table with columns:
  - Priority
  - Action
  - Owner
  - Timing
  - Expected impact
  - Dependency / risk

Rules:
- No more than 6 rows.
- Use priority tags: P0, P1, P2.
- Use short, action-oriented verbs.
- Use one highlighted row for the most urgent action.

### 8.10 Appendix Deep-Dive Slide

Purpose:
- Provide backup analysis without disrupting the main story.

Layout:
- Can be denser.
- Still needs an action title.
- Use same visual system.
- Include definitions and source notes.

Rules:
- Appendix does not mean messy.
- Keep charts readable.
- Use subtitles to explain the analytical cut.

---

## 9. Narrative System for Decks

### 9.1 Recommended Deck Structure

For strategy and performance analysis:

1. **Executive Summary**
   - Answer, implications, recommended decisions.

2. **Context / Objective**
   - What question the analysis answers.
   - Baseline, scope, comparison groups.

3. **Overall Result**
   - Total movement vs baseline / target.

4. **Incrementality / Benchmark**
   - Whether performance is truly better than control or market.

5. **Driver Diagnosis**
   - Which levers explain the result.

6. **Granular Deep Dive**
   - Districts, segments, cohorts, categories, partners, etc.

7. **Implications**
   - What this means for the next wave, plan, or decision.

8. **Actions / Next Steps**
   - Prioritized actions, owners, timing.

9. **Appendix**
   - Backup tables, definitions, methodology.

### 9.2 Storyline Rules

- Every slide should answer the next logical question in the audience’s mind.
- Do not show analysis just because it exists.
- If a slide does not change the decision, move it to appendix.
- Start broad, then go granular.
- Separate facts, interpretation, and recommendation.
- Avoid jumping from metric to metric without an argument.

### 9.3 Common Consulting Storylines

#### Growth Diagnostic
```text
1. Growth happened / did not happen
2. It was concentrated in specific segments
3. It was driven by specific levers
4. Some segments outperformed control
5. Therefore, scale some plays and redesign others
```

#### Performance Review
```text
1. Overall performance vs target
2. What went better than expected
3. What underperformed
4. Why it happened
5. What management should do next
```

#### Strategy Recommendation
```text
1. The market / business context changed
2. Current approach is insufficient
3. There are 2–3 strategic options
4. Option X is best based on impact, feasibility, and risk
5. Implementation should follow a phased plan
```

---

## 10. Component Styling

### 10.1 KPI Cards

Use KPI cards for quick executive scanning.

Specs:
- White or very light gray background.
- Thin light gray border.
- 8–12 px internal padding.
- Main value: 24–36 pt bold.
- Label: 8–10 pt gray.
- Delta: 9–11 pt, accent or semantic color.
- Max 3–5 cards per row.

Example:
```text
Orders
+6.4%
84% of target
```

### 10.2 Insight Bullets

Use for right-side interpretation panels.

Format:
- Bold lead-in.
- Short explanation.
- Metric included.

Example:
- **Lima shows incremental signal:** orders grew +7.5% vs +5.8% in control.
- **Trujillo is frequency-constrained:** active customers grew, but frequency remained nearly flat.
- **Next wave should be selective:** scale proven districts, redesign laggards.

### 10.3 Tags / Chips

Use for classification.

Examples:
- `WINNER`
- `WATCHOUT`
- `SCALE`
- `FIX`
- `MONITOR`
- `P0`

Design:
- Font: 8–9 pt bold.
- Radius: 4–6 px.
- Padding: 3–6 px.
- Accent fill for primary tag.
- Light gray fill for neutral tag.

### 10.4 Methodology Box

Use when the analysis depends on definitions.

Design:
- Light gray fill.
- Thin gray border.
- 8–10 pt text.
- Place in bottom-right or under chart.
- Keep to 2–4 lines.

Example:
> Methodology: treatment districts compared vs Lima control districts; performance measured as change vs Jan-2026 baseline.

### 10.5 Driver Tree

Use to decompose business logic.

Structure:
```text
Orders
├── Active Customers
│   ├── Acquisitions
│   └── Reactivations
└── Frequency
    ├── Retention
    └── Repeat purchase
```

Design:
- Use simple boxes and connectors.
- Highlight the constrained branch in accent.
- Keep to 2 levels max in main slides.
- Move detailed trees to appendix.

---

## 11. Data Storytelling Rules

### 11.1 Be Explicit About Comparisons

Always state:
- Compared to what?
- Over what period?
- In what geography / segment?
- With what exclusions?
- Against what target or benchmark?

Bad:
> Orders grew.

Good:
> Orders grew +6.4% vs Jan-2026 baseline, reaching 84% of the Ola 1 target.

### 11.2 Separate Correlation From Causality

If the analysis does not prove causality, do not use causal language.

Avoid:
- “Plan Ruta caused growth”
- “The campaign generated all incremental orders”

Use:
- “Plan Ruta shows an incremental signal”
- “Growth is consistent with the activation period”
- “Treatment outperformed control by +1.7pp”
- “This suggests, but does not prove, incremental impact”

### 11.3 Use the Right Level of Precision

Executive slides should be precise but not noisy.

Rules:
- Percentages: 0 or 1 decimal.
- pp changes: 1 decimal if needed.
- Orders: round to k if large.
- Money: use M or k.
- Avoid unnecessary decimals in labels.

### 11.4 Make the “So What” Unavoidable

Every analytical slide should include at least one of:
- Decision implication.
- Risk.
- Next action.
- Strategic interpretation.
- Resource allocation consequence.

Example:
> So what: scale Jesús María and Lima Cercado playbook, but redesign Trujillo around frequency rather than acquisition.

---

## 12. Do’s and Don’ts

### Do

- Use an action title with the conclusion.
- Make one visual dominate the slide.
- Highlight only the key evidence.
- Keep a consistent grid across all slides.
- Use direct labels on charts.
- Add sources and definitions.
- Use neutral colors for context.
- Use accent color sparingly.
- Round numbers to executive-friendly precision.
- Use appendix for dense backup.
- Make recommendations specific and operational.
- Check alignment before finalizing.
- Ensure chart labels never overlap.

### Don’t

- Don’t create dashboard-like slides with many unrelated charts.
- Don’t use decorative gradients, stock icons, or heavy shadows.
- Don’t use more than one accent color unless necessary.
- Don’t write descriptive titles.
- Don’t overuse bullets.
- Don’t add legends when direct labels work.
- Don’t show raw tables on main slides if a chart would tell the story.
- Don’t use 3D charts.
- Don’t use tiny unreadable labels.
- Don’t include analysis that does not support a decision.
- Don’t claim causality without a valid methodology.
- Don’t fill white space just because it exists.

---

## 13. Quality Control Checklist

Before finalizing any slide, verify:

### Story
- [ ] Does the title state the answer?
- [ ] Does the exhibit prove the title?
- [ ] Is the implication clear?
- [ ] Would the slide still make sense without a presenter?

### Layout
- [ ] Are objects aligned to a consistent grid?
- [ ] Is the main visual dominant?
- [ ] Is there enough whitespace?
- [ ] Are title, chart, callouts, and source visually separated?

### Data
- [ ] Are timeframes clear?
- [ ] Are baselines defined?
- [ ] Are units consistent?
- [ ] Are numbers rounded appropriately?
- [ ] Are labels readable?
- [ ] Are chart colors meaningful?

### Visual Hygiene
- [ ] No overlapping labels.
- [ ] No unnecessary gridlines.
- [ ] No heavy borders.
- [ ] No decorative icons.
- [ ] No inconsistent font sizes.
- [ ] No chart legend if labels can be direct.
- [ ] No more than 2 callouts.

---

## 14. Responsive / Format Behavior

Although this system is primarily for 16:9 slides, the same logic can adapt to other formats.

### 16:9 Executive Deck

Best for:
- Leadership presentations.
- Monthly business reviews.
- Strategic recommendations.
- Analytical storytelling.

Rules:
- Use full slide canvas.
- Keep title to max 2 lines.
- Use one main exhibit.
- Include source note.

### A4 One-Pager

Best for:
- Written memos.
- Printable summaries.
- Board-style leave-behinds.

Rules:
- Increase text density slightly.
- Use section headers.
- Use 2-column structure.
- Keep charts compact.
- Include full methodology.

### Mobile / Image Share

Best for:
- WhatsApp / Slack sharing.
- Quick stakeholder updates.

Rules:
- Use larger title.
- Reduce chart complexity.
- Avoid small footnotes.
- Use one chart or one big number.
- Prefer portrait if explicitly requested.

---

## 15. Agent Prompt Guide

Use this section as direct context for an AI agent generating slides.

### 15.1 Default Instruction

When generating slides, follow this system:

```text
Create a clean, executive, consulting-style slide.
Use a white background, black/gray typography, and one accent color.
The slide must have an action title with the conclusion, one dominant exhibit, clear labels, a concise implication, and a small source note.
Avoid decorative design. Prioritize analytical clarity, alignment, and hierarchy.
```

### 15.2 Quick Visual Reference

- Background: White `#FFFFFF`.
- Title: Near Black `#111111`, bold, 22–30 pt.
- Subtitle: Dark Gray `#4A4A4A`, 10–13 pt.
- Main accent: `#FA0050` unless another brand color is specified.
- Non-highlight chart elements: gray.
- Borders/gridlines: `#D9D9D9`.
- Footnotes: `#6E6E6E`, 6.5–8 pt.
- No heavy shadows.
- No gradients.
- No 3D charts.
- No decorative clutter.

### 15.3 Slide Generation Requirements

For every slide, produce:

1. **Action title**
   - Must communicate the conclusion.
   - Max 2 lines.

2. **Main exhibit**
   - Chart, bridge, matrix, table, or diagram.
   - Must directly prove the title.

3. **Callouts**
   - 1–2 max.
   - Must explain interpretation, not repeat data.

4. **So what**
   - One concise implication, decision, risk, or next step.

5. **Source note**
   - Small, bottom-left.

### 15.4 Example Prompts for the Agent

#### Waterfall Slide

```text
Create a 16:9 consulting-style waterfall slide.
Title: "Plan Ruta grew +59k orders vs January, with Food Long Tail, Global KA, and Local Hero explaining ~81% of the uplift."
Use a white background, black title, gray bars for baseline/current, and #FA0050 for the top growth drivers.
Show contribution percentage near each driver.
Ensure all labels fit above bars and never overlap.
Add a bottom-right implication box: "So what: scale the proven Food playbook, but review low-contribution blocks before expanding investment."
Add a small source note at bottom-left.
```

#### Comparison vs Control Slide

```text
Create a 16:9 consulting-style slide comparing treatment vs control vs benchmark.
Use grouped bars for Orders, Active Customers, and Frequency.
Treatment should be highlighted in #FA0050; control and benchmark should be gray.
The title must state the conclusion, not just describe the chart.
Add a methodology box explaining baseline and comparison groups.
Add one callout highlighting the largest spread vs control.
```

#### Driver Tree Slide

```text
Create a consulting-style driver decomposition slide.
Use the formula "Orders = Active Customers × Frequency" as the organizing logic.
Show Orders at the top, then split into Active Customers and Frequency.
Highlight the constrained driver in #FA0050.
Use compact KPI cards below each driver with current growth, target attainment, and diagnosis.
Add a bottom takeaway explaining which lever should be prioritized.
```

#### District Ranking Slide

```text
Create a horizontal bar ranking slide by district.
Sort districts by incremental spread vs control, descending.
Use #FA0050 for clear winners, dark gray for neutral districts, and muted red only for clear laggards.
Add labels at the end of each bar.
Create a right-side action panel grouping districts into Scale, Consolidate, Fix, and Rethink.
Use a concise title that states which districts should be scaled and which require intervention.
```

#### Executive Summary Slide

```text
Create an executive summary slide with 4 key messages.
Each message should begin with the conclusion in bold, followed by one supporting metric.
Use a clean 2-column layout: insights on the left, decisions/actions on the right.
Use #FA0050 only for key numbers or priority tags.
Do not use charts unless they are small and clearly support the summary.
```

---

## 16. Iteration Guide for AI-Generated Slides

When refining an existing slide, change one layer at a time.

### 16.1 If the Slide Feels Cluttered

Do:
- Reduce to one main exhibit.
- Move secondary analysis to appendix.
- Remove decorative elements.
- Shorten bullets.
- Increase whitespace.
- Use fewer colors.

Prompt:
```text
Simplify this slide to one dominant exhibit and one implication. Remove secondary charts, reduce bullets, and improve whitespace while preserving the main message.
```

### 16.2 If the Slide Feels Too Generic

Do:
- Rewrite title as a conclusion.
- Add specific metric values.
- Add comparison group.
- Add implication.
- Highlight the key data point.

Prompt:
```text
Make this slide more consulting-style by rewriting the title as an insight, highlighting the key data point, and adding a concise "so what" implication.
```

### 16.3 If the Chart Is Hard to Read

Do:
- Use direct labels.
- Remove legend.
- Sort values.
- Increase label size.
- Reduce gridlines.
- Highlight one series only.

Prompt:
```text
Improve chart readability: sort the bars, remove unnecessary gridlines, use direct data labels, and highlight only the series that supports the title.
```

### 16.4 If the Slide Looks Like a Dashboard

Do:
- Pick the one chart that proves the conclusion.
- Convert extra charts into callouts or appendix.
- Remove duplicate KPIs.
- Add a clear title and takeaway.

Prompt:
```text
Convert this dashboard-like slide into a single consulting page: one action title, one primary exhibit, one interpretation panel, and one source note.
```

### 16.5 If the Slide Lacks Executive Impact

Do:
- Make the title sharper.
- Add business implication.
- Prioritize decision language.
- Replace descriptive bullets with action-oriented messages.

Prompt:
```text
Make this slide more executive: sharpen the title, quantify the message, and add a decision-oriented implication at the bottom.
```

---

## 17. Common Slide Title Formulas

Use these formulas to write action titles quickly.

### Growth

```text
[Metric] grew [amount] vs [baseline], driven by [top driver(s)]
```

Example:
> Orders grew +59k vs January, driven mainly by Food Long Tail and KA segments

### Gap

```text
[Metric] is [x]% below target, mainly due to [constraint]
```

Example:
> Orders reached 84% of target, with the gap mainly explained by active-customer shortfall

### Incrementality

```text
[Treatment] outperformed [control] by [x]pp, suggesting [implication]
```

Example:
> Lima outperformed control by +1.7pp in orders, suggesting a selective incremental signal

### Tradeoff

```text
[X] improved, but [Y] remains the bottleneck
```

Example:
> Frequency improved in Lima, but active-customer growth remains the bottleneck to hit target

### Decision

```text
[Action] should focus on [segment/lever] because [evidence]
```

Example:
> Ola 2 should focus on frequency recovery in Trujillo because acquisition gains are not converting into repeat orders

---

## 18. Known Gaps & Assumptions

- This system describes a consulting-style slide language; it does not include proprietary McKinsey templates, fonts, or brand assets.
- Exact font rendering may vary across PowerPoint, Google Slides, Keynote, and image generation tools.
- If the user provides a brand guide, that guide overrides the default accent color and typography choices.
- If the user provides a sample deck, preserve its best structural elements while applying this system’s hierarchy and visual hygiene.
- If the content is analytical and data-heavy, prioritize clarity over visual novelty.
- If the content is for final executive review, include sources, methodology, and caveats.
- If the content is for brainstorming, speed and structure can be prioritized over perfect formatting.

---

## 19. Final Output Standard

A finished slide should feel like this:

- The title tells me the conclusion.
- The chart proves the conclusion.
- The highlight tells me where to look.
- The annotation tells me why it matters.
- The source tells me whether I can trust it.
- The slide is clean enough to send to a senior executive without explanation.

If a slide does not meet these standards, revise before presenting.

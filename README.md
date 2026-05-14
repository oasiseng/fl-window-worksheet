# Florida Residential Window Replacement Worksheet

A free, open-source web tool that lets Florida homeowners generate a permit-ready wind pressure worksheet for replacing windows or doors in a single-family detached home — **without hiring an engineer**.

The tool uses the Florida Building Code's **simplified method** (FBC Residential Code Table R301.2(2)) which the code already allows you to use directly. You don't need to be an engineer to read a code table. You just need a clean, accurate way to fill out the lookup, check your products against the required pressures, and produce a worksheet your building department can accept.

The calculator is table-backed. The HTML embeds the published ASD pressure rows used by this worksheet: Table R301.2(2) wall Zones 4 and 5, Table R301.2(3) height/exposure adjustment coefficients, and Table R301.2(4) nominal garage-door loads. It does not generate pressure values from ASCE equations.

That's what this tool does. Nothing more, nothing less.

---

## Who this is for

**You.** If you are:

- A Florida homeowner replacing some or all windows in your home
- The property is in your name (your primary residence)
- The home is **single-story**, **single-family detached**, with a normal rectangular shape and a normal gable or hip roof
- You're outside the **HVHZ** (not in Miami-Dade, Broward, or Monroe County)
- You're not directly on the open coast (not within ~600 ft of the Atlantic or Gulf)
- You're replacing 25% or fewer windows/doors in a 12-month period

If all of the above is true, **you have a legal right under Florida Statute 489.103(7) to pull your own permit as an owner-builder.** And you have the right under the Florida Building Code to use the simplified-method tables to determine your required wind pressures. No engineer required.

This tool helps you do that cleanly.

---

## Who this is NOT for

If you're outside the scope above, **you need a Professional Engineer.** Specifically:

- **Multi-story homes** (mean roof height over 30 ft)
- **Condos, townhouses, duplexes, manufactured homes, commercial buildings** — different code rules
- **Anything in Miami-Dade, Broward, or Monroe** (HVHZ — stricter requirements, Miami-Dade NOAs required, PE-sealed installation engineering)
- **Coastal homes** within ~600 ft of the ocean
- **Complex homes** — L-shaped, multi-wing, big additions, unusual roof shapes
- **Open-sided structures** — carports, pavilions, pole barns
- **Investment / rental properties** — owner-builder exemption doesn't apply
- **More than 25% glass replacement** in 12 months (triggers extra requirements)

The tool **refuses to operate** in any of these cases and routes you to engineering services instead. This is by design — it keeps you on the right side of the code.

If you need a sealed letter for any project outside the simplified scope: **[Oasis Engineering](https://oasisengineering.com)** provides Florida wind-pressure letters with 24–48 hour turnaround across the state. Also see [windcalculations.com](https://windcalculations.com) and [floridawindcalcs.com](https://floridawindcalcs.com).

---

## How to use the tool

1. **Open the tool** in any modern browser. Phone, tablet, laptop — works on all of them.
2. **Confirm eligibility** (Step 1). One checkbox. Honest answer required.
3. **Enter project info** (Step 2): your address, your name, your county. Look up your wind speed using [ASCE Hazard Tool](https://ascehazardtool.org) (official) or [windcalculations.com](https://windcalculations.com) (free, also works). Enter your exposure, mean roof height, and longest wall dimension.
4. **List each window or door** (Step 3): size, location (Zone 4 interior or Zone 5 corner), the Florida Product Approval # of the product you plan to install, and its tested design pressure.
5. **Print the worksheet** (Step 4). Sign it. Submit it with your permit application along with your Florida Product Approval documents and your owner-builder affidavit.

The whole process takes about 15 minutes if you have your product info handy.

---

## What the worksheet contains

Everything a typical Florida residential building department asks for in a window/door replacement permit submittal, presented in a clean printable format:

- **Project information** — address, owner, county, date
- **Building wind design data** — wind speed, exposure, height, risk category, enclosure, zone 5 width, reporting basis
- **Opening schedule with pressure check** — one row per window or door, showing required pressure vs. your product's tested DP, the exact FBC table row/column used, and a clear PASS / FAIL flag
- **Method used** — checkbox confirming you're using the FBC R301.2(2) simplified-method path (the default homeowner path)
- **Owner-builder certification statement** — pre-filled with your info, ready to sign
- **Code references** — every code section cited so a reviewer can verify

---

## What this tool does NOT replace

You will still need:

1. **Florida Product Approval documentation** for each product. Download from [floridabuilding.org/pr/pr_app_srch.aspx](https://www.floridabuilding.org/pr/pr_app_srch.aspx).
2. **Owner-Builder Affidavit** — your local building department's form (usually downloadable from their website).
3. **Notice of Commencement** — if your project total exceeds $2,500. Filed with your county clerk before the first inspection.
4. **A signed Owner-Builder Disclosure Statement** acknowledging your responsibilities under FS 489.103(7) — usually required at permit submittal.

Your local building department may have **additional local requirements** that aren't reflected in this tool. **Always verify with them before submitting.** A 5-minute phone call to your local Building Services department to ask "What do you need from me for a residential window replacement permit as an owner-builder?" is the single most valuable thing you can do.

---

## Liability — read this carefully

**This tool is not engineering.**

It is a free, public, code-table lookup utility. The Florida Building Code publishes Table R301.2(2) as a simplified method any homeowner can use directly. This tool just helps you do the lookup cleanly and format the results into a worksheet.

By using this tool you agree:

- This software is provided **as-is**, with **no warranty of any kind**, express or implied
- The tool's authors and Oasis Engineering LLC are **not your engineers** and have not been retained by you for any engineering service
- Using this tool does **not** create an engineer-client relationship
- **You** are responsible for verifying every input is correct (wind speed, exposure, roof height, wall dimensions, opening sizes, product DPs, FL approval numbers)
- **You** are responsible for verifying your local building department accepts this worksheet format
- **You** are responsible for installing the products in accordance with the manufacturer's published installation instructions
- **You** are responsible for the consequences of any decision you make based on the output
- If your project falls outside the simplified-method scope, **you need a Professional Engineer** — not this tool

If you submit this worksheet and your permit is rejected, that's between you and your building department. If you submit it and your installation fails in a storm, that's between you and your insurance company. We can't help you with either.

**If you have any doubt about whether the simplified method applies to your project, stop using this tool and hire a Professional Engineer.** The cost of a sealed letter ($200–$500 typically) is trivial compared to the cost of a failed permit, a denied insurance claim, or a window flying out in a hurricane.

---

## What does an engineer actually do, then?

Reasonable question. If the homeowner can do this lookup themselves, why hire an engineer at all? Three answers:

1. **You're outside the simplified-method scope.** Multi-story, HVHZ, coastal, complex geometry, open buildings, commercial, larger-than-25%-replacement — all need site-specific engineering analysis the simplified tables don't cover.

2. **Your building department requires it.** Some jurisdictions (City of Tampa is a notable example) require PE certification on every window replacement regardless of scope. Call yours and ask first.

3. **You want the additional review and accountability.** A PE who seals a letter is staking their professional license on its accuracy. They will verify your wind speed, double-check your product approvals are appropriate, confirm your installation method matches the approval, and flag any issues. Some homeowners value that backstop even when not strictly required by code.

If any of those apply to you, contact Oasis Engineering or another licensed Florida structural firm.

---

## Why this exists

Florida's permitting system can feel intimidating to homeowners, but for a typical single-story window replacement it shouldn't be. The Florida Building Code intentionally provides a simplified method specifically so homeowners and small contractors don't need an engineer for every routine job. The code text is publicly available. The tables are published. The owner-builder exemption is established law.

The friction comes from the **format**. Most homeowners don't know how to find their wind speed, read Table R301.2(2), select the appropriate effective wind area row, determine Zone 5 widths, convert ASD ↔ LRFD pressures, or write a worksheet a reviewer will accept on the first pass. So they hire someone to do the paperwork, paying for what is effectively a code-table lookup.

This tool removes that friction. If you have a simple house and a basic understanding of what you're installing, you should be able to handle the permit yourself.

That's the DIY ethic. Empower the owner. Get the engineer when you actually need one.

---

## SEO / educational articles (coming)

We're planning a series of plain-English articles on Florida residential window replacement to go with this tool. If you're reading this and have a specific topic you want covered, [open an issue](#) on this repo or reach out via Oasis Engineering. Planned topics:

- "Do I really need an engineer to replace my windows in Florida?"
- "FBC R301.2(2) explained: how to read the Florida wind pressure table"
- "How to pull an owner-builder permit in Florida: step-by-step"
- "Florida wind zones 4 and 5 for windows: which is which?"
- "What is 'Effective Wind Area' and why does it matter?"
- "The 25% rule for Florida window replacement: what it means for your project"
- "Florida Product Approvals vs Miami-Dade NOAs: which do you need?"
- "Window replacement permits in [Cape Coral / Lee County / Charlotte / Sarasota / Hillsborough] — what's actually required"
- "ASD vs LRFD design pressures: what your window's spec sheet really means"
- "Why your permit got rejected (and how to fix it)"

---

## Technical notes

- **Single HTML file.** No build step, no server, no installation, no internet required after first load. Open in a browser and it works
- **Privacy.** Everything stays on your device. Nothing is transmitted, logged, or stored anywhere outside your browser
- **Browser support.** Chrome, Edge, Firefox, Safari — all work. Print rendering is most reliable in Chrome
- **Mobile friendly.** Designed to work on phones, since you might be at the home depot looking up product approvals on your phone
- **Computation.** Wind pressures are looked up from embedded FBC Residential Code table rows, not generated from ASCE formulas. Wall openings use Table R301.2(2) wall Zones 4 and 5, then multiply by the Table R301.2(3) height/exposure coefficient. Garage doors use Table R301.2(4), then the same Table R301.2(3) adjustment. All output is ASD basis.
- **No pressure interpolation.** If the entered wind speed or mean roof height falls between published columns/rows, the tool uses the next higher published table column/row. For wall effective wind area, it uses the lower published EWA row, which is the conservative table option identified in the code footnote. The worksheet prints the actual lookup row/column used.
- **Embedded table limits.** Wall opening lookup is limited to Table R301.2(2) wall Zones 4 and 5, EWA rows 10/20/50/100 sf, and wind-speed columns through 180 mph. Garage-door lookup is limited to the published 9 ft x 7 ft and 16 ft x 7 ft rows in Table R301.2(4).
- **Open source.** Released under the MIT License. Fork it, modify it, host your own copy. If you find a bug or have a suggestion, open an issue

---

## License

[MIT License](LICENSE) — free to use, modify, and redistribute. The license does not waive Florida Building Code requirements or Professional Engineer licensure laws.

---

## Maintained by

[**Oasis Engineering LLC**](https://oasisengineering.com) · Florida licensed structural and wind engineering firm · COA No. 35420 · Licensed in 37 states

We build this tool because we'd rather help homeowners do simple permits correctly than charge them $300 for a code-table lookup. When you have a project that actually needs engineering — multi-story, HVHZ, coastal, complex — we're here for that work.

---

## Disclaimer (one more time, because it matters)

**This tool is a free public utility. It is not engineering. It is not legal advice. It is not a substitute for a licensed Professional Engineer where one is required.** Use of this tool does not create any engineer-client relationship with Oasis Engineering LLC or the tool's authors. The tool's authors disclaim all liability for any consequences arising from use, misuse, or reliance on this tool or its output. You assume all risk and all responsibility for any decisions you make.

If you are not comfortable with that, **do not use this tool. Hire a Professional Engineer.**

That's not a sales pitch. That's the honest answer.

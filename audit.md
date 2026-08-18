# Citation Audit: The LULU Q4 FY25 Supplier Read-Through

| Field | Value |
|---|---|
| Document audited | "The LULU Q4 FY25 Supplier Read-Through: A Blind Reconstruction of the Asian Supplier Pre-Print Signal Workflow", Wall Street Prompt, author Dave Wang, dated May 2026, 41 pages (v2) |
| Auditor | SPEC Research (Milos Maricic), spec-research.com |
| Audit run | Claim extraction, primary-source verification, and an adversarial review of our own adverse verdicts, completed 17 July 2026 |
| Status | Published Tuesday 18 August 2026. Sent to Wall Street Prompt on Monday 10 August 2026 for right of reply, through 5:00 PM New York time on Monday 17 August 2026. No response was received at either address or through LinkedIn by that deadline; delivery and receipt were not independently confirmed. The offer stands open: any response provided for publication prints verbatim and unedited alongside this audit, at whatever length |
| Companion | This audit is the retrospective baseline for our pre-registered forward test of the same prompt: github.com/SPEC-research/forward-test (PROTOCOL.md) |
| Disclosure | Unpaid and unsolicited. The auditor runs the companion forward test above and holds no position in any security named |

Page references are to the PDF as distributed by Wall Street Prompt (the printed footer number is the PDF page minus 2). The report is quoted minimally, for review purposes. Nothing in this document is investment advice; it evaluates research citations, not securities.

## The question

This audit answers one question: when the report states a checkable fact, does the record contain that fact?

The report is the flagship public demonstration of the supply-chain read-through prompt our forward test runs live. It presents itself as a blind ex-post reconstruction of what the workflow would have produced before LULU's 17 March 2026 print, and it discloses that reconstruction status prominently. We credit that disclosure in full, and the reconstruction question is outside this audit's scope. So is the quality of the report's predictions, which its own scorecard already grades and which the forward test addresses prospectively.

## Summary of results

The report makes 126 externally checkable factual claims. We verified each against primary sources in the language of origin: SEC and HKEX filings, Taiwan MOPS revenue tables, Korean DART disclosures, earnings-call transcripts, archived aggregator captures, and the Taiwanese, Korean, and Chinese press record. Every adverse verdict was then attacked in a second pass run as defense counsel for the report. That pass overturned two of our verdicts, downgraded two more, and corrected three errors in our own working notes. The figures below are the post-review result.

| Verdict | Count | Share |
|---|---|---|
| VERIFIED in full against the primary or attributed source | 84 | 66.7% |
| VERIFIED on the checkable element* | 3 | 2.4% |
| CORROBORATED via secondary sources only | 3 | 2.4% |
| PARTIAL (part verifies, part does not) | 17 | 13.5% |
| MISMATCH (the record contradicts the claim as printed) | 14 | 11.1% |
| NOT FOUND (no public source contains the claim) | 3 | 2.4% |
| UNVERIFIABLE (the attributed source could not be accessed; graded neither right nor wrong) | 2 | 1.6% |

*Three supplier-list claims pair a checkable list element, which verified, with an exposure percentage the report itself discloses as its own triangulation; no public support exists for those percentages, consistent with that disclosure.

By claim category:

| Category | n | Verified or corroborated | Partial | Mismatch | Not found | Unverifiable |
|---|---|---|---|---|---|---|
| Filing numerics | 23 | 20 | 0 | 3 | 0 | 0 |
| Calendar facts | 17 | 14 | 0 | 3 | 0 | 0 |
| Consensus and actuals | 22 | 19 | 0 | 2 | 1 | 0 |
| Supplier relationships | 30 | 20 | 6 | 4 | 0 | 0 |
| Other facts | 18 | 10 | 7 | 1 | 0 | 0 |
| Verbatim quotes | 16 | 7 | 4 | 1 | 2 | 2 |

Read as rates: verbatim quotes verify in full 7 times in 16; filing numerics 20 in 23. The sampling rule for a reader follows directly: check the quotes and attributions, spare the arithmetic.

Two findings frame everything else.

**The mechanical data layer is excellent.** All ten Taiwan monthly-revenue claims are exact to the printed decimal against the TWSE MOPS tables, including the year-to-date cumulatives. Every LULU actual-print figure reconciles to SEC filings, including a China segment figure that appears in no single document and reproduces only by subtracting the Q3 10-Q from the 10-K; it survives that arithmetic to the thousand of dollars. The management-guidance quotes are verbatim against call transcripts, including the seven-component Q4 gross-margin bridge. Three Chinese quotes that the PDF itself corrupts with unrendered glyphs recover and verify word for word in the cited article. Where the workflow transcribed a number from a filing, an aggregator table, or a transcript, it transcribed it correctly.

**The errors concentrate where judgment about sources was required.** Fourteen claims mismatch the record and three could not be found in any public source. The failures are patterned rather than random: quotes attributed to more official or more in-window sources than the ones that carried them; translations that add words the original does not contain, in each case in the direction of the report's thesis; supplier-list details that misread the list the report says it parsed, including one supplier ruled out that is on the list; a filing date inverted from pre-print to post-print; an inventory direction inverted; an analyst-action tally overstated. Sections below give each finding with its evidence.

**The errors that have a direction all lean the same way.** Thirteen findings adverse in whole or in part carry an identifiable direction. All thirteen run toward the report's thesis, or toward its evidence looking more official, more in-window, more contrarian, or cleaner-cut than the record supports (C036, C045, C046, C047, C053, C054, C063, C070, C072, C083, C109, C110, C125). None runs the other way. The remainder are direction-neutral identity and precision slips, plus one mechanical extraction error with no narrative content (C086).

**Not all of it matters equally.** Seven adverse findings are signal-relevant, meaning a reader who relied on them took away a different read than the record supports: the supplier wrongly ruled out (C030), the pre-print filing dated post-print and excluded as unusable (C036), the client-status upgrade (C053), the contradicted absence claim behind the pivot read (C054), the interpolated tariff-sharing cohort (C070), the five-times-repeated quote with no locatable source behind the soft FY26 read (C072), and the inverted inventory direction (C086). The rest are precision and identity errors, real but not read-changing.

A third finding concerns the reader's position. The PDF carries 148 link annotations: 64 are internal navigation, and all 84 external hyperlinks resolve to wallstreetprompt.com (43) or davewang.ai (41). None points to a filing, an article, or a transcript. To be precise about what this is and is not: the 84 resolve to just two unique URLs, the firms' two homepages, repeated across pages in the manner of masthead links, and there is nothing improper in a document linking its publisher. The finding is the absence those links leave behind, a 41-page evidence document whose only clickable destinations are its publisher's homepages. (Re-verified 2026-08-04: both targets are bare homepages returning HTTP 200, with no onward redirect toward any source.) The document embeds no files, and its text layer prints no source URL anywhere; the only third-party domain string in the whole text sits inside the report's own note on sources that returned HTTP 403 errors. On sourcing, the report states (p9) that the full URL bibliography for the supplier source set "sits in the supporting workflow output files", a directory of per-supplier extracts that is not part of the PDF and is not linked from it. Ten of its sixteen verbatim quotes sit in sources a reader can reach free and in full; of the five sourced to sell-side notes, one is publicly readable end to end. A reader without a Korean research terminal and a Chinese research-aggregator subscription cannot replicate the quote layer, and the report presents all quotes with uniform confidence regardless of stratum. Every error documented in this audit is invisible from inside the document; each one surfaced only on primary-source re-verification.

One number this audit cannot supply is a base rate. No equivalent claim-level audit of human-authored sell-side or independent research exists, so 66.7 percent verified grades against no curve, and we decline to guess whether a human analyst's 41-page document would score better or worse under the same protocol. The forward test publishes a provenance verification rate with every sealed run, which starts building that base rate in public.

## Why this matters

The audited report is the strongest public artifact of its genre, produced by the firm that leads the genre, and that is what makes its failure profile useful: it is the best available evidence of where AI-assisted research actually breaks, and the break has a shape a reader can act on.

**If you produce research with these tools.** The six failure patterns documented below are what an unverified generation pipeline outputs, whoever runs it. The controls follow from the patterns: pull every load-bearing quote back to the document that supposedly carries it; print the original language beside any translation; record the edition and capture date of every foundation document you parse; enumerate before writing "all", "none", or "every"; log the searches behind any absence claim before treating silence as signal; and run one pass whose only instruction is to break the conclusion. The companion checklist (github.com/SPEC-research/forward-test/blob/main/checklist.md) states the standard in eight questions.

**If you consume it.** Spot-checking the numbers now samples the wrong layer: this report survives any figure check a reviewer would run, with all ten Taiwan monthlies exact to the decimal, while the quote its FY26 read leans on five times has no locatable source. The five-minute check that works: pick two or three load-bearing quotes, follow each to its claimed source, and confirm the source carries it. Ask whether verification ran as a step separate from generation, and ask to see its output. The red flags visible in any finished document: every link resolving to the producer's own domain, uniform confidence across quotes from filings and from paywalled foreign-language notes, "all" and "none" tallies, absence-of-coverage presented as signal, and translations with no original printed.

**If you allocate.** Figure accuracy in a manager's AI research exhibit is evidence of very little, because transcription is the layer these systems stopped getting wrong. Grade the attribution layer instead: who re-verified the original-language quotes and against what, where the bibliography is and whether it resolves outside the manager's own materials, and what edition control exists on foundation data. A manager who answers with model quality has answered.

**If you own the controls.** Review-by-reading is not a control for this failure class. At most two of the seventeen adverse findings here were catchable from the document alone: the broker romanization contradicted by the report's own printed Chinese, and the Bonding figure attributed to a regulatory filing on one page and to a broker note on another. Everything else required primary re-verification across three languages and five disclosure systems. The legally loaded variant is misattribution to regulatory filings, which appears twice (C070, C083). The operational conclusion: verification is a separately run function whose output ships with the research.

## Reading the pattern

This audit grades claims; it alleges no intent. What the findings support is narrower and, for the category, more important: the errors follow the characteristic failure modes of AI-assisted research pipelines. Real language migrating to a more authoritative or better-timed source. Translations drifting toward the thesis. A stale edition of a foundation document persisting into conclusions its current edition contradicts. A number lifted from an adjacent row. A tally rounded up to "all". Each error is small, most have innocent mechanisms, several sit one caveat away from defensible, and every one of them survived into a finished, confident, 41-page document because generation and verification are different functions and only one of them was run. The direction of the surviving errors follows from the same fact: a generation pipeline optimizes for narrative coherence, so the claims that outlive drafting are disproportionately the ones that fit the thesis. Nothing about that requires intent. It requires only the absence of an adversarial pass.

That is the case for the category's next layer, and it is why this audit publishes alongside a live, pre-registered forward test of the same method. The method's data layer is strong enough to be worth testing live. The sourcing layer is exactly where live testing needs an independent referee.

## Method

**Claim extraction.** Every page of the 41-page PDF was read and every externally checkable factual claim ledgered with its page, attributed source, and verification route: 126 claims across six categories (verbatim quotes 16, filing numerics 23, supplier relationships 30, calendar facts 17, consensus and actuals 22, other facts 18). Excluded from the denominator: the workflow's own predictions and confidence tags, its self-described architecture, its supplier-weighting constructs, and the five supplier exposure percentages the report's own p13 describes as triangulated "directional inputs, not audited revenue facts" (we checked those for public support anyway and report the result, but a blank there is consistent with the report's own caveat, and we grade it accordingly).

**Verification.** Primary sources only, in the original language, with no verdict resting on a source that repeats the report's own text. Consensus figures were checked against the aggregators the report attributes them to, using Wayback captures where the live pages have moved on; those verdicts are against aggregator data, not filings, and are labeled as such. Claims whose attributed source is paywalled or unreachable are graded UNVERIFIABLE, and UNVERIFIABLE is never counted as an error.

**Disconfirmation.** Every MISMATCH, NOT FOUND, and PARTIAL verdict (36 items) was then attacked in a separate pass instructed to act as defense counsel for the report: re-read the claim in context, hunt for any edition, provider, translation, fiscal convention, or rounding under which the report is right, and re-fetch the underlying evidence. Two of our verdicts were overturned outright, two were downgraded, and the pass surfaced three errors in our own notes, which we corrected. Fifteen surviving adverse verdicts carry mandatory caveats, and those caveats are printed with the findings below.

**Fairness rules applied throughout.** The report's disclosed caveats are credited, and a claim the report itself flags as weak is not treated as a confident assertion. Absence claims ("no coverage exists") are graded as weak-verifiable. Date and figure conventions were resolved in the report's favor wherever a legitimate convention supports its number. The supplier-list findings were tested against all three published editions of LULU's list (April 2025, October 2025, May 2026) to exclude edition drift as an innocent explanation before any mismatch was recorded.

## What holds up

The strongest work in the report is exactly where its genre usually fails, and that deserves plain statement.

- **Taiwan monthlies, 10 of 10 exact.** Eclat January and February 2026, Quang Viet November and December 2025 and January and February 2026 plus the FY2025 cumulative, FENC December 2025 through February 2026: every figure and growth rate matches MOPS to the printed decimal, and the 17-month-high characterization for Eclat's January holds on the same inclusive count Taiwanese press used.
- **The actual-print record, exact throughout.** Revenue, EPS, margins, segment figures, inventory, the FY26 and Q1 FY26 guides, and the full gross-margin bridge all reconcile to the 8-K, 10-K, 10-Q, and call transcripts (C112 to C120, C122). The China Mainland Q4 figure of $528.4M is not printed in any LULU release; it reconciles exactly from the 10-K minus the Q3 10-Q, which means the workflow did the two-filing arithmetic and did it right.
- **Exchange-filing and wire-service quotes verify.** Regina's "brand partners' order placement decisions have stabilised" is verbatim in the HKEX interim. The Haitong International title clause is verbatim on the full-text carrier. The three FENC quotes whose characters the PDF fails to render all recover (瓶, 為, 產) and verify in the cited UDN article, byline and date included.
- **The consensus layer is real.** Segment-level estimates match FXStreet to the figure and to the analyst count; the -580bp margin guide and the inventory guide are verbatim from the Q3 call; the Reuters/LSEG FY26 expectations check out through syndications and CNBC independently.
- **The report polices its own window at least once.** It correctly identifies the widely-cited FENC Middle East commentary as post-cutoff (24 March 2026 Yuanta conference) and excludes it (C096). Its hedge on Shenzhou is exactly right: the list on its face contains no Shenzhou entity, the report caveats that tier-2 fabric exposure may not appear on a final-assembly disclosure, and that is precisely what the record shows (C014; see context note below).
- **Its self-flagged weak spots are genuinely weak, honestly flagged.** The FY26 China consensus range the report marks WEAK is confirmed unverifiable (C107), and the exposure percentages its p13 calls triangulations have, as that caveat predicts, no public source (C013, C018, C019, C021).

## What does not hold up

Fourteen MISMATCH and three NOT FOUND verdicts survived the disconfirmation pass, along with adverse elements inside several PARTIALs. They cluster into six patterns. Where the disconfirmation pass attached a mandatory caveat to a surviving verdict, the caveat is stated with the finding here and verbatim in the appendix.

### 1. The supplier list the workflow says it parsed

The report's foundation document is LULU's October 2025 Active Supplier List, which it cites by name. Its facility-level readings of that list are wrong in five places, and the errors were tested against all three published editions before being recorded.

- **A supplier ruled out that is on the list (C030, MISMATCH).** The report excludes Stella International (1836.HK) as a LULU supplier. The October 2025 list carries Golden Star Company Limited, Hai Phong, Tier 1 Footwear, parent "Stella International Trading (Macao Commercial Offshore) Limited"; the May 2026 edition carries the same row under "Stella International Hong Kong Limited". Stella is absent only from the April 2025 edition, which suggests a stale earlier capture never re-checked against the edition the report claims.
- **Crystal International: six facilities claimed, four on the list (C013, MISMATCH).** "Crystal SL Global" parents exactly four rows in every edition. The only other "Crystal" row is an unrelated Colombian company.
- **Hojeon: one facility in Vietnam claimed; the list shows two, both in Indonesia (C016, MISMATCH).** No edition of the list has ever carried a Hojeon facility in Vietnam. Caveat: the exposure element of the claim (roughly 20 to 22 percent of FY24 apparel revenue per Korean trade press) is genuinely supported by a published analyst projection, so the mismatch is confined to the facility count and country.
- **Eclat: six facilities plus one subcontractor claimed; the list shows five plus two (C011, PARTIAL).** The total of seven Eclat-linked rows matches, so this reads as a classification slip rather than an invented count.
- **The list-level totals (C008, PARTIAL).** "Approximately 115 facilities" matches only an unstated Tier-1-plus-subcontractors reading of a 142-row list, and "roughly twenty" Asian-listed parents overcounts the 14 to 16 identifiable on any defensible inclusion rule.

Context note credited to the report (C014, VERIFIED): its claim that Shenzhou is absent from the October 2025 list is true as printed, since the relevant row's printed parent is "Master Limited (Vietnam)". The analytically important context is that Shenzhou's exposure is on the list through that row (Gain Lucky (Vietnam), Tier 2, Fabric-Vertical, Tay Ninh), and a Shenzhou-named Tier 1 facility appeared on the April 2025 edition. The report's own tier-2 hedge anticipated exactly this.

### 2. Quotes and figures attributed to sources that do not carry them

Four claims move real material onto wrong sources. In each case the move makes the evidence look more official or more in-window than it is.

- **The Hojeon tariff quote (C070, PARTIAL).** The Korean sentence naming tariff cost-sharing as a Q4 drag is genuine company language, verbatim in three independent 27 February 2026 articles. The report attributes it to the 26 February DART filing. The filing's entire reason line reads 환율변동 및 관세 영향으로 인한 이익 감소 (profit decrease due to FX movements and tariff impact); the quoted sentence evidently comes from Hojeon's IR communication to media. See also pattern 3 on this quote's translation.
- **The December Shenzhou quote that appears to be an August quote (C063, NOT FOUND).** "Actively cultivating segment leaders such as Lululemon" is attributed to a Hexun sector strategy of 7 December 2025. That article exists and contains no Lululemon mention. Near-identical language sits in a Huaxin Securities Shenzhou initiation dated 27 August 2025, verified from the note PDF, and 华鑫 (Huaxin) is phonetically adjacent to 和讯 (Hexun). Caveat: the quote is probably real but misattributed rather than invented, and a China-reachable browser check of the Hexun page remains open as a final control. If the attribution is wrong as it appears, a pre-window August quote was moved inside the December observation window.
- **Hojeon net income from the wrong document (C067, MISMATCH).** The claimed KRW 11.3 billion (-51.2%) does not match the cited preliminary disclosure (KRW 11.12 billion, -52.0%); it matches the later audited annual report. Caveat: the figure is the later audited actual, not an invented value, and a May 2026 author reading FnGuide would see exactly these numbers. Revenue and operating income in the same claim are exact.
- **The Regina Bonding figure (C083, MISMATCH).** The scorecard attributes "Bonding +40% with 'Lululemon Air Support' cited" to Regina's interim results. The interim contains no +40% figure, no Lululemon, and no Air Support (zero occurrences in both the results announcement and the full interim report); the segment figures in the same claim are exact. The +40% is genuine content of the CMBC International initiation the report cites adjacently. Caveat: this is misattribution of a real figure plus an unverifiable product claim, not fabrication of the number.

The same pattern appears in miniature inside a verified claim: the Eclat "flat to low" customer-inventory quote verifies against CNA's 13 November 2025 coverage, and the report's p25 restatement re-dates it to the 5 March 2026 board statement, whose article contains no customer-inventory sentence (C046, VERIFIED with that caveat).

### 3. Translations that add words

Two quoted translations insert phrases the original does not contain, and both insertions run toward the report's thesis.

- **"With US customers" (C070).** The Korean names 미국발 관세 이슈, tariff issues originating from the US, and contains no word for customers. The report's quoted translation inserts "with US customers" and then builds its tariff cost-sharing argument on the inserted cohort. The direction of the inference is plausible; the counterparty is unstated in the Korean. In fairness, the report repeatedly caveats that this is a cohort phrase rather than a LULU-specific one.
- **"Of four major clients" (C053, MISMATCH).** The Taiwanese record supports "fastest-growing" for LULU at Quang Viet and simultaneously frames LULU as a newly acquired, low-base customer outside the named major-client set (the majors are listed and LULU is explicitly set apart: 除了去年加入的Lululemon外). The insertion upgrades LULU into the major-client cohort, which changes the signal: a top-four client decelerating is a different fact from a low-base new client growing fast.

### 4. Quotes with no locatable source

- **The five-times-repeated management quote (C072, NOT FOUND).** "High-base growth slowdown at large-share customers", attributed to Hojeon management and load-bearing for the report's soft FY26 read, appears in no locatable Korean source: the DART filing lacks it, the three same-day press articles lack it, indexed Korean coverage lacks it, and the one findable broker document reads opposite in tone (Daishin, September 2025: major customers including Lululemon keep growing). If it exists it sits inside a paywalled note or an unindexed interview; as printed it is unsupported, and no Korean original is given.
- **"Margin normalisation expected" (C047, PARTIAL).** Attributed to Eclat's CFO on 5 March 2026. Caveat: the 5 March article does carry backward-looking margin-recovery language (Q4 gross margin 30.19 percent, back above 30 percent), so the quote has a real kernel in the claimed vehicle; forward-looking normalisation language appears in the record only around the 17 March investor conference.
- **"Tale of two markets" (C124, PARTIAL).** Absent from both accessible full transcripts of the call. It appears in third-party earnings summaries that attribute it to management. Caveat: the report most likely echoes secondary summaries rather than coining the phrase; it remains unplaceable as call language on the primary record. The claim's other two phrases are verbatim in the transcript.

### 5. Window and absence claims

- **A filing date inverted (C036, MISMATCH).** The report dates Tristate's FY25 annual results to 27 March 2026, ten days post-print, and excludes them as unusable. The results were filed 17 March 2026 at 21:38 HKT, roughly seven hours before LULU's release. Nothing was filed on 27 March. The error inverts the report's own usability framing: the filing was pre-print.
- **The absence claim behind the Quang Viet read (C054, MISMATCH).** The report states LULU is not mentioned in any in-window article on Quang Viet and reads the silence as signal. Commercial Times, 17 December 2025 print (online 16 December), inside the window, ties Quang Viet to LULU down jackets and outerwear with orders up 20 percent this year. The secondary element (a 30 percent Jordan expansion earmarked for Alo Yoga) conflates two separate 2025 disclosures.
- **A conference that did not happen on that date (C042, MISMATCH).** The report has Eclat presenting at a Yuanta conference on 12 February 2026. The MOPS record dated 12 February announces attendance at a Yuanta conference on 17 March, Eclat's Q4 call. Caveat: Eclat did attend J.P. Morgan's Taiwan CEO-CFO Conference on 17 February 2026, so an in-window mid-February broker appearance existed; the report has the wrong host and date for it, or converted an announcement date into an event date.
- **The Eclat order-book trajectory (C045, PARTIAL).** Three of its four touchpoints verify or are fairly inferred, including full-capacity wording we initially missed in the 5 March article and corrected on review. The August anchor is misdated: six-month visibility was restored by 7 August 2025, and the three-month reading dates to May 2025. The misdating moves the order-book recovery inside the observation window when it predates it.

### 6. The market-record layer

- **"All six firms cut" (C110, MISMATCH).** The report has Goldman, BTIG, Telsey, Evercore, UBS, and BofA all cutting LULU price targets in the seven days before the print. Four did (UBS 9 March, Goldman 11 March, BTIG 12 March, Evercore 16 March). Telsey published a Market Perform reiteration on 10 March with an unchanged $215 target, and BofA took no action between its December 2025 raise and June 2026. Caveat: the report's "uniformly negative direction of travel" gloss is directionally fair; "all six" is not.
- **The rating distribution (C109, MISMATCH).** The claimed 1 Strong Buy / 2 Buy / 28 Hold / 2 Sell across 33 analysts and a $190 to $200 median target match no archivable aggregator: MarketBeat's 12 March capture shows 2/2/30/1 of 35 with a $225.22 mean, Benzinga's 17 March capture shows 25 analysts at $210.40. Caveat: the claim's shape is right (85 to 90 percent Hold, real final-week cuts, a low-side cluster at $175 to $192), no checkable source supports the printed numbers, and a terminal source such as LSEG or Bloomberg could still vindicate them.
- **The Q1 FY26 EPS consensus (C108, MISMATCH on that element).** The only locatable contemporaneous print is $2.07 (LSEG via CNBC) against the claimed $2.09. Caveat: a different aggregator could have printed $2.09 and none was found; $2.09 is not disproven. The revenue element corroborates.
- **The day-after move (C125, PARTIAL).** The 17 March close is exact, and the claimed after-hours snapshot ($161.98, +1.3 percent) is defensible as an initial reaction measured against the 16 March close, the standard extended-hours convention, in a session Reuters documents as two-sided and ending lower. The surviving error: 18 March closed up 3.84 percent, and the report's "~+5%" matches only an intraday print.
- **One extraction inversion (C086, MISMATCH).** The report has Regina's inventory building 18.5 percent half-on-half. The interim shows inventories declining 9.6 percent against 31 March 2025 and 15.0 percent year on year. One arithmetic identity is worth recording: inventories at 30 September 2025 divided by the adjacent trade-receivables comparative equals exactly +18.5 percent, consistent with a row-misalignment extraction error. We offer that as a plausible mechanism, not a finding. The capex elements of the same claim are exact.

One naming error rounds out the set: the broker behind the December Shenzhou notes is Guosheng Securities (国盛证券), legible in the report's own partially rendered Chinese, romanized throughout as "Guosen", which is a different, real firm (C062, MISMATCH). Caveat: all four underlying broker documents are genuine and correctly dated; in a report sold on original-language sourcing, pointing readers at the wrong firm is a substantive error rather than a typo.

## What a reader can and cannot check

The report's premise is that its edge comes from primary sources in three languages. The audit confirms the sources are overwhelmingly real. It also establishes that the report, as distributed, gives its reader no path to them.

- The PDF's annotation table, embedded-file table, and text layer were each inspected in full. Of 148 link annotations, 64 are internal navigation and all 84 external hyperlinks resolve to wallstreetprompt.com (43) or davewang.ai (41); the document embeds no files; and no text-layer string points to any source. Re-extracted and redirect-tested 2026-08-04: the 84 external annotations carry two unique homepage URLs, both returning HTTP 200 with no onward redirection. The bibliography statement on p9 places the full URL bibliography in "the supporting workflow output files", per-supplier extracts in a directory the PDF neither contains nor links.
- Of the 16 verbatim quotes, 10 sit in sources a reader can reach free and in full. The sell-side stratum is the weak layer: of five quotes sourced to broker notes, one (Haitong) is publicly readable end to end; the DB Securities quote is reachable only through Korean press excerpts; the CMBC International and Wedbush notes are paywalled or unlocatable.
- The report presents all quotes with uniform confidence regardless of stratum. Nothing in its text distinguishes the quote a reader can click through to HKEX from the quote that exists, if at all, behind a Korean research terminal.

This matters because of where the errors sit. The transcription layer, which a reader could in principle spot-check, is nearly flawless. The errors live in the attribution and translation layer, which a reader cannot check at all without redoing the sourcing from scratch. We had to: the re-verification ran across the primary record in Chinese, Korean, and English, five disclosure systems (SEC EDGAR, HKEX, TWSE MOPS, DART, and archived aggregator captures), and the region-locked press stratum. That is the cost profile of the control this genre is missing.

## Unverifiable items

Two claims are graded UNVERIFIABLE. Neither is counted as an error.

- **C082.** The CMBC International initiation on Regina Miracle exists, is correctly dated 1 December 2025, and its accessible abstract confirms Bonding growth figures and Lululemon among customers. Whether it "explicitly names Lululemon Air Support [leggings]" cannot be confirmed; the note body is paywalled, and no accessible summary links Lululemon to Air Support. One independent observation: Air Support is a Lululemon sports-bra line, which fits Regina's specialty; the report's own bracketed "[leggings]" is likely a product-category error even if the note names the product.
- **C111.** The Wedbush "FY26 Street is conservative" view could not be located through any public channel, and Wedbush is absent from the findable pre-print commentary set. A paywalled note may exist. The claim's embedded proxy-fight fact verifies (CNBC, 17 March 2026); the 15-quarter beat-streak fact was not cleanly checkable in public archives and remains open.

## Our own errors, and what could change

The disconfirmation pass exists because auditors make the same class of mistakes as the audited. Ours, for the record: we initially misdated UBS's March cut, missed the full-capacity wording in the 5 March CNA article, wrote that the Eclat-Nulu tie had no public support when a secondary source exists, over-penalized a hedged Shenzhou claim that is true as printed, and applied segment-level pedantry to an accurate description of FENC. All five are corrected in our working files, and the two affected verdicts were re-graded in the report's favor before this draft was assembled.

Open items that could move specific verdicts, listed so that anyone with the access can check us: the early-March 2026 LULU rating distribution and median target from a professional terminal (C109); any second aggregator print of the Q1 FY26 EPS consensus (C108); the Daishin, NH, DB, CMBC, and Wedbush note PDFs (C078, C075, C076, C082, C111); the Hexun article from a China-reachable browser (C063); the customs entry-effective date of the 19 percent Bangladesh rate (C057). If any verdict here is wrong, we will correct it in place, dated, and say so at the top of this document.

## Right of reply

This draft was sent to Wall Street Prompt on Monday 10 August 2026 with five business days, through 5:00 PM New York time on Monday 17 August 2026, to respond before publication. Any response is printed verbatim and unedited alongside this audit, at whatever length. Corrections they substantiate will be made in the text, attributed.

---

# Appendix: the full claims ledger with verdicts

Verdict key: **V** = verified in full against the primary or attributed source. **V-list** = the supplier-list element verifies; the exposure element is the report's own disclosed triangulation, for which no public support was found. **CORR** = corroborated via secondary sources only. **P** = partial. **MM** = mismatch. **NF** = not found in any public source. **UNV** = attributed source inaccessible; graded neither right nor wrong.

Consensus rows marked V against FXStreet, Zacks, or Reuters/LSEG are verified against the report's attributed aggregator, which is itself aggregator data rather than a filing.

## A. Framing and calendar (pp. 5-10)

| ID | p. | Claim (abridged) | Verdict | Evidence |
|---|---|---|---|---|
| C001 | 5 | TW listings publish monthly revenue within 10 days of month-end | V | Taiwan Securities and Exchange Act Art. 36(1)(3), law.moj.gov.tw/ENG/LawClass/LawAll.aspx?pcode=G0400001 |
| C002 | 5 | HK interims/annuals land in August and March; Korean names disclose quarterly via DART | V | HKEX LR 13.49 (en-rules.hkex.com.hk/rulebook/1349); observed filing dates of all names in the report |
| C003 | 8 | LULU printed Tue 17 Mar 2026, Business Wire release, same-evening call | V | 8-K Ex-99.1, sec.gov/Archives/edgar/data/1397187/000139718726000019/lulu-20260201xex991.htm. Note: 4:30 p.m. ET is the call time per the release, not the release time |
| C004 | 8 | 13-week Q4 vs 14-week prior-year Q4; 53rd-week YoY distortion | V | FY25 10-K, sec.gov/Archives/edgar/data/1397187/000139718726000020/lulu-20260201.htm |
| C005 | 8 | An October 2025 Active Supplier List exists on LULU's corporate site | V | Wayback capture 2025-11-16 (web.archive.org/web/20251116042422/), the live URL now serves the May 2026 edition |
| C006 | 8 | Eclat, Crystal, Regina, Best Pacific, Hojeon, Youngone all on the Oct 2025 list as parents | V | Oct 2025 list; Crystal appears via its Crystal SL Global subsidiary |
| C007 | 10 | Supplier reporting calendars (TWD monthlies; DART; HK annuals; Regina March year-end) | V | Primary filings of each name |

## B. Supplier discovery, exposure, non-suppliers, HK calendar (pp. 11-14)

| ID | p. | Claim (abridged) | Verdict | Evidence |
|---|---|---|---|---|
| C008 | 11 | List has ~115 facilities, roughly twenty Asian-listed parents | P | Full list has 142 rows; ~113 under a Tier-1-plus-subcontractors reading; identifiable Asian-listed parent groups ~14-16 |
| C009 | 11 | Eclat LULU exposure ~10% (8-10% triangulated) | V | uanalyze.com.tw/articles/636453918 (~10%); other TW pieces 7-9%; the report's specific outlet attributions remain unmatched |
| C010 | 11 | Hansae flagged via a July 2025 CEO quote; absent from LULU's list | V | Worldfolio interview 2025-07-25; zero Hansae occurrences on the Oct 2025 and May 2026 lists |
| C011 | 12 | Eclat: six facilities plus one subcontractor | P | All editions show 5 facilities + 2 subcontractors; total of 7 matches, split does not; reads as a classification slip |
| C012 | 12 | Quang Viet: two facilities (VN + Jordan), no Bangladesh; 1-3% exposure per TC press | P | List element exact in all editions; no TC article states 1-3% |
| C013 | 12 | Crystal: six facilities via Crystal SL Global; 3-6% exposure | MM | Exactly 4 Crystal SL Global rows in every edition; exposure has no public source, consistent with the report's own p13 triangulation caveat |
| C014 | 12 | Shenzhou is not on the Oct 2025 list | V | True at facility- and parent-name level. Context: Shenzhou's exposure IS on the list via Gain Lucky (Vietnam), printed parent "Master Limited (Vietnam)" (Tier 2, Fabric-Vertical, Tay Ninh), and a Shenzhou-named Tier 1 facility appeared on the Apr 2025 edition. The report's tier-2 hedge anticipated this |
| C015 | 12 | SC press: LULU a sub-top-four Shenzhou client growing ~60% YoY since 2022 | P | Guotai Junan deep dive (via sohu.com/a/782984693_121649907): ~2% of 2023 orders, roughly doubled in 2023, ~50% forecast CAGR; no ~60% found anywhere |
| C016 | 12 | Hojeon: one facility, Vietnam; ~20-22% exposure, highest of Korean names | MM | Two facilities, both Indonesia (PT Hoga Reksa, Garut; PT Yongjin Javasuka II & III, Sukabumi); no Hojeon Vietnam facility on any edition. Caveat: the ~20% exposure is supported (Daily Invest 2023-07-04 analyst projection); mismatch confined to facility count and country; the "highest of Korean-listed names" comparison stated nowhere |
| C017 | 12 | Youngone: four facilities VN+BD; top 3-4 client at ~5-10% | P | List element exact; rank supported. The ~5-10% is the report's own labeled estimate and Korean press (Business Post 2025-11-30) puts the share around the mid-10%s; estimate-versus-estimate divergence, not a sourced figure the report got wrong |
| C018 | 12 | Best Pacific: three Tier 2 fabric facilities; 4-8% exposure | V-list | Facilities exact (Dongguan, Lanka, Trischel); product set confirmed in the interim; exposure has no public source |
| C019 | 12 | Regina: four Vietnam facilities; 5-7% exposure | V-list | Facilities exact (Hung Yen; Hai Phong B, C, D); exposure has no public source |
| C020 | 12 | FENC: three facilities via FE New Century Singapore; <1% exposure; LanzaTech partnership | V | List exact; partnership on fenc.com (id=5617); <1% contradicted by nothing given FENC's ~NT$280bn consolidated revenue |
| C021 | 12 | Tristate: Hefei Tristate facility, Tier 1 woven; 2-5%; no sell-side coverage | V-list | Hefei row exact (parent Excellent Jade); "woven" matches disclosed specialization; exposure has no public source; coverage absence consistent with all searches |
| C022 | 13 | Eclat supplies 50-70% of LULU leggings fabric; Luon and Nulu supplier | P | 50-70% rests on one second-tier source quoting a former Eclat sales manager (baijing.cn/article/39929); Luon tie in Yahoo Finance 2013; Nulu tie in one consultancy source (Blue Associates); none primary |
| C023 | 13 | Native-language company names as printed | V | Company registries; the PDF's unrendered glyphs recover to 維珍妮 (Regina) and 聯亞集團 (Tristate) |
| C024 | 13 | Makalot serves Gap, Target, Uniqlo; not LULU | V | Taipei Times 2021 client mix; zero Makalot rows on LULU lists (Tier 1 coverage is 100%, so absence is strong) |
| C025 | 13 | Pou Chen is Nike/Adidas footwear; not LULU | V | Company record; zero list rows |
| C026 | 13 | Feng Tay is 86% Nike; not LULU | V | BofA via investing.com ("Nike contributes 86%"); zero list rows |
| C027 | 13 | Pacific Textiles is Uniqlo-focused; not LULU | V | Uniqlo core mill list; zero list rows (Tier 2 coverage ~80%, absence weaker) |
| C028 | 13 | Texhong is yarn upstream, indirect at best | V | Company profile; zero list rows (same Tier 2 caveat) |
| C029 | 13 | Yue Yuen is Nike/Adidas/Asics footwear; not LULU | V | Company record; zero list rows |
| C030 | 14 | Stella International: not a LULU supplier | MM | Golden Star Company Limited, Hai Phong, Tier 1 Footwear, parent Stella International Trading (Macao Commercial Offshore) Ltd, is on the Oct 2025 list; same row on May 2026 under Stella International Hong Kong Ltd; absent only from Apr 2025 |
| C031 | 14 | Fountain Set not on the LULU list | V | Zero occurrences (Tier 2 caveat applies) |
| C032 | 14 | Lever Style serves Arc'teryx, Skims; not LULU | V | Lever Style's own 2026 interim release client roster; zero list rows |
| C033 | 14 | Roo Hsing is denim; not LULU | V | Company record; zero list rows |
| C034 | 14 | Crystal FY25 annual results 19 Mar 2026, 2 days post-print | V | HKEX filing 19/03/2026 16:47 HKT |
| C035 | 14 | Best Pacific FY25 annual ~23 Mar 2026 | V | HKEX filing 23/03/2026 22:39 HKT |
| C036 | 14 | Tristate FY25 annual filed 27 Mar 2026, 10 days post-print | MM | Filed 17/03/2026 21:38 HKT (09:38 ET), roughly seven hours before the LULU release; nothing filed 27 Mar; the error inverts pre/post-print usability |
| C037 | 14 | Shenzhou FY25 annual ~30 Mar 2026 | V | HKEX filing 30/03/2026 |
| C038 | 14 | Regina interim 27 Nov 2025, covering Apr-Sep 2025, sole fresh HK interim in window | V | HKEX filing 27/11/2025 16:30 HKT; peer interims date Aug/Sep 2025 |

## C. Per-supplier extracts (pp. 15-21, 24)

| ID | p. | Claim (abridged) | Verdict | Evidence |
|---|---|---|---|---|
| C039 | 15 | Eclat Q3 CY25 earnings call 13 Nov 2025 | V | MOPS record (SinoPac-hosted 法人說明會 114/11/13); CNA same-day coverage |
| C040 | 15 | 8 Jan 2026 CNA-reported CFO commentary; CFO Lin Fen-Ru | V | cna.com.tw/news/afe/202601080228.aspx; name confirmed (財務長暨發言人林芬如) |
| C041 | 15 | Eclat Jan 2026 revenue NT$3.582B, +7.55%, 17-month high, filed ~6 Feb | V | MOPS: NT$3,581,621k, +7.55% exact; 17-month high on the inclusive count TW press used |
| C042 | 15 | Eclat presented at a Yuanta conference 12 Feb 2026 | MM | MOPS filing dated 12 Feb announces a 17 Mar Yuanta conference (Eclat's Q4 call). Caveat: Eclat did attend JPM's Taiwan CEO-CFO Conference 17 Feb 2026, the probable kernel; wrong host and date, or announcement date converted into event date |
| C043 | 15 | Eclat Feb 2026 revenue NT$2.44B, -7.36%, CNY effect pre-flagged 8 Jan | V | MOPS: NT$2,439,916k, -7.36% exact; the 8 Jan pre-flag sub-element was not sighted in the retrieved article |
| C044 | 15 | 5 Mar 2026 board passed FY25 financials + NT$15 dividend; CNA same day | V | MOPS filings 115/03/05 17:55 and 18:01; cna.com.tw/news/afe/202603050313.aspx |
| C045 | 15 | Order-book trajectory: 3 months (Aug), 6 (13 Nov), 6+ with July booked (8 Jan), 6 at full capacity (5 Mar) | P | August anchor misdated: six-month visibility was restored by 7 Aug 2025 (UDN); the three-month reading dates to May 2025 (MoneyDJ). The other three touchpoints verify or are fairly inferred (5 Mar article contains 產能滿載). The misdating moves the recovery inside the observation window |
| C046 | 15 | Eclat customer inventory "flat to low" | V | 「客戶庫存水位持平偏低」, CNA 13 Nov 2025; translation fair. Caveat: the report's p25 re-dating of the quote to the 5 Mar board statement is unsupported |
| C047 | 15 | "Margin normalisation expected", CFO, 5 Mar 2026 | P | The 5 Mar article carries backward-looking recovery language (Q4 GM 30.19%, back above 30%); forward normalisation language appears only around the 17 Mar conference; no ASP sentence in the claimed vehicle |
| C048 | 16 | Quang Viet Nov 2025 NT$1.36B, +31.74%; Alo first-shipment tie | V | MOPS: NT$1,358,617k exact; Alo tie in cnyes id/6265462, Jordan plant named |
| C049 | 16 | Quang Viet Dec 2025 NT$1.25B, +9.68% | V | MOPS: NT$1,253,373k, +9.675% |
| C050 | 16 | Quang Viet Jan 2026 NT$1.04B, +2.35% | V | MOPS: NT$1,039,301k exact |
| C051 | 16 | Quang Viet Feb 2026 NT$772M, -6.56%, YTD -1.65%, filed 10 Mar | V | MOPS: NT$772,311k exact incl. YTD; filing date supported by same-day roundup + TWSE deadline rule |
| C052 | 16 | Quang Viet FY2025 cumulative NT$19.43B, +17.85% | V | MOPS: NT$19,427,838k, +17.847% |
| C053 | 16 | LULU "fastest-growing of four major clients in 2024" at Quang Viet | MM | "Fastest-growing" supported; "of four major clients" is an insertion. TW press names the majors without LULU and frames LULU as a newly acquired low-base client (「除了去年加入的Lululemon外」); no four-major framing found in three targeted searches |
| C054 | 16 | 2026 narrative pivoted to Alo; Jordan +30% earmarked for Alo; LULU absent from all in-window articles | MM | Commercial Times 17 Dec 2025 print (online 16 Dec), in window, ties Quang Viet to LULU down jackets/outerwear, orders +20%; the Jordan-for-Alo detail conflates two separate 2025 disclosures (lines 45 to 60, +33%, mainly Adidas/VF; Alo shipping from Jordan from Q4 2025) |
| C055 | 16 | Footprint VN/Jordan/Romania/China; Jordan profit-positive after a 50% expansion | P | Footprint exact (5 VN, 2 CN, 2 JO, 1 RO plants). The genuine ~50% in the record is Jordan revenue guidance (~五成), while capacity grew +33% and the profit turn is press-attributed to Jordan's 0% US duty; real kernel, wrong referent |
| C056 | 16 | Vietnam tariff 20% eff. 7 Aug 2025, down from 46% announced 2 Apr 2025 | V | EO of 31 Jul 2025, Annex I (whitehouse.gov); both dates and both rates exact |
| C057 | 16 | Bangladesh 20% eff. 7 Aug 2025; reduced to 19% "effective 9 Feb 2026" | P | 20% exact; the US-Bangladesh agreement was signed and announced 9 Feb 2026 (USTR, Al Jazeera) but no source confirms 19% applied to customs entries from that date; "effective" unconfirmed as written |
| C058 | 16 | Crystal 1H25: sportswear +12.4% to US$312.9M, GPM 20.7% flat, released 20 Aug | V | HKEX 2025082000466.pdf; all elements exact ("essentially flat" = -20bp) |
| C059 | 17 | Crystal Egypt land, US$30.4M, ~800k sqm, New October Industrial Zone, 20 Jan 2026 | V | HKEX 2026012000364.pdf; technically a land-reservation announcement, "first non-Asian production base" a fair characterization |
| C060 | 17 | Crystal: no quarterly reporting, no profit alert in window; port-of-discharge revenue; AP bucket dominated by Japan/Uniqlo | V | Interim text + filing index Dec 2025 - 17 Mar 2026; Japan/Uniqlo gloss fair (Fast Retailing is Crystal's documented largest customer) |
| C061 | 17 | Shenzhou top four = Nike, Uniqlo, Adidas, Puma; LULU sub-top-four | V | 80.7% of 2024 revenue per company record; LULU-as-client confirmed via LULU's own Apr 2025 list and Gain Lucky presence |
| C062 | 17 | Four broker reports on Shenzhou 1-15 Dec 2025, romanized "Guosen" | MM | All four documents exist with the claimed content and dates; the broker is Guosheng (国盛证券), matching the report's own partially rendered 盛. Caveat: the underlying notes are genuine and correctly dated; the romanization points readers at a different, real firm, a substantive error in a report sold on original-language sourcing |
| C063 | 17 | Hexun 7 Dec 2025: Shenzhou "actively cultivating segment leaders such as Lululemon" | NF | The Hexun article exists and contains no LULU mention. Near-identical language verified in Huaxin Securities' Shenzhou initiation of 27 Aug 2025 (analyst 娄倩). Caveat: probably real but misattributed rather than invented (Huaxin/Hexun conflation moving an August quote into December); a China-reachable browser check remains open as a final control |
| C064 | 17 | Haitong Intl 15 Dec: "Lululemon NA still under pressure, CEO stepping down January 2026" | V | Full text on stockstar.com/JC2025121500034697.shtml; quoted clause is the title's second half, verbatim |
| C065 | 17 | Broker projects Shenzhou 2026 capacity tightness, >10% revenue CAGR, profit quality rising | V | Guosheng 2025-12-12 note via sdyanbao.com/detail/937724; content verified in full; broker-name error recorded at C062 |
| C066 | 18 | Hojeon DART prelim filed 26 Feb 2026, 30%-change disclosure type | V | dart.fss.or.kr rcpNo=20260226801474; type's last word is 변경, the report wrote 변동 (immaterial) |
| C067 | 18 | Hojeon FY25: revenue 520.8bn +12.3%, OI 25.0bn -15.2%, NI 11.3bn -51.2% | MM | Revenue and OI exact in the cited prelim; the prelim's NI is 11.118bn (-52.0%). Caveat: the claimed NI matches the later audited annual report (11.296bn, -51.2%), a real figure from the wrong source; a May 2026 author reading FnGuide would see exactly these numbers |
| C068 | 18 | Hojeon Q4 standalone revenue 137.8bn, OP 6.0bn | V | Reproduced from DART (FY prelim minus 9M cumulative); FnGuide concurs |
| C069 | 18 | Q4-end inventory KRW 101.2bn, year-low, -10.8% | V | Audited annual report: 101,229,960,465 at 2025-12-31; year-low across 2025 quarter-ends |
| C070 | 18 | Korean quote naming tariff cost-sharing as Q4 drag, per the DART filing | P | The Korean sentence is genuine company language, verbatim in three independent 27 Feb articles, evidently from Hojeon's IR release. The cited DART filing's entire reason line is 환율변동 및 관세 영향으로 인한 이익 감소. The report's translation inserts "with US customers"; the Korean contains no word for customers. The report does caveat the phrase as cohort-level |
| C071 | 18 | 2026 names: Carhartt, Arc'teryx, Sweden military, Kathmandu, Moose Knuckles, VUORI; LULU absent | P | Five of six brands with growth rates verified (daily.hankooki idxno=1340716) and LULU absent from the narrative; no Korean source links Hojeon to VUORI |
| C072 | 18 | Hojeon management: "high-base growth slowdown at large-share customers" | NF | No Korean original printed and none locatable: absent from the DART filing, the three 27 Feb articles, indexed coverage, and Hankyung Consensus; the findable Daishin note (Sep 2025) reads opposite in tone. Repeated five times in the report and load-bearing for its FY26 read; unsupported as printed |
| C073 | 18 | Youngone DART 25-26 Feb; brokers 27 Feb: Daishin 유정현, NH 정지윤, DB 허제나 | V | DART filed 26 Feb (the claimed range overstates the single date); all three notes confirmed via Hankyung Consensus PDF and named same-day press |
| C074 | 18 | Youngone Q4: revenue 1,009.3bn +19%, OP 105.2bn swing from loss | V | DART-derived exact; Q4-24 OP was KRW -26.4bn, so "swing" is right |
| C075 | 18 | OEM +24% KRW (+17-18% USD), OPM 18.8%, +510bp | V | Composite of the two 27 Feb broker decompositions; the +510bp is NH-specific (Daishin says +4.8pp; our DART reconstruction ~+400bp); broker-grade, not filing-grade, and flagged as such |
| C076 | 18-19 | DB Securities core-customer order quote (KO) | V | Word-for-word in alphabiz 27 Feb 2026 coverage of the note (analyst 허제나, TP 120,000원); verification is one step from the primary (note PDF not publicly posted) |
| C077 | 19 | LULU not Youngone's #1 customer; Arc'teryx mid-10%s share | V | No source names LULU #1; Arc'teryx mid-10%s per Eugene Investment via Business Post (already 20% by Q1 2026 per DB/ksdaily) |
| C078 | 19 | Daishin 2026 Youngone guide: revenue 4.355T +7.2%, OP 664B +29% | CORR | Edaily coverage of the 27 Feb note confirms broker, analyst, TP change, and +29% OP; exact KRW levels arithmetically consistent but unsighted (note PDF inaccessible) |
| C079 | 19 | Best Pacific 1H25: revenue -2.3%, GPM ~26.6%, -40bp | V | HKEX 2025082501360.pdf exact |
| C080 | 19 | 19 Dec 2025: MAS/Trischel CCT renewal, 3-year framework + lease to end-2028, Sri Lanka JV expansion potential | V | HKEX 2025121900543.pdf; all elements match |
| C081 | 19 | No profit alert in window; customer base VS, Nike, Adidas, UA, ANTA/Li-Ning/Xtep | P | Absence verified from the filing index; the six-brand roster matches no public Best Pacific disclosure (its filings name no customers); plausible industry knowledge, unmatched to a source |
| C082 | 19-20 | CMBC International initiation, 1 Dec 2025, names "Lululemon Air Support [leggings]" | UNV | Note real: 民银国际 initiation on Regina, 1 Dec 2025, analyst 何丽敏, Buy, TP HK$2.60 (fxbaogao.com/detail/5182435). Body paywalled; accessible summaries confirm Bonding +50/+40% and LULU among customers but never link LULU to Air Support. Air Support is a LULU sports-bra line; the report's own "[leggings]" bracket is likely a product-category error. The report's "(Dongfang Caifu)" gloss conflates publisher and distribution platform |
| C083 | 20 | Regina interim: Sports +13.4% to HK$1,505M (39% of group), Intimates -6.6%, Bonding +40% with LULU Air Support named | MM | Segment figures exact in HKEX 2025112700338.pdf; the interim contains no +40%, no Lululemon, no Air Support (0 occurrences incl. the full interim report). The +40% is genuine CMBC-note content per East Money's summary. Caveat: misattribution of a real figure plus an unverifiable product claim, not fabrication of the number |
| C084 | 20 | VS China JV +37.3%; OEM shipments into mainland China -16.7% | V | Interim exact (PRC-destination revenue 715,466 vs 858,482) |
| C085 | 20 | Group GM -0.3pp; raw materials +1.9pp offset by Vietnam labour/automation -1.7pp | V | Interim exact; the Vietnam gloss is the report's, the filing says production efficiency |
| C086 | 20 | Inventory +18.5% half-on-half; capex past peak, -50% | MM | Inventories fell: HK$1,245.6M at 30 Sep 2025 vs 1,378.3M at 31 Mar 2025 (-9.6%; -15.0% YoY). Capex elements exact. Noted mechanism, not a finding: inventories divided by the adjacent trade-receivables comparative equals exactly +18.5%, consistent with row-misalignment extraction |
| C087 | 20 | "Brand partners' order placement decisions have stabilised" | V | Verbatim in the interim's Future Prospects (spelling variant only) |
| C088 | 20 | FENC conglomerate spanning polyester, retail/SOGO, telecom, cement, finance | V | MoneyDJ company record lists all five among core and reinvestment businesses |
| C089 | 20 | 23 Dec 2025 UDN/EDN wrap of FENC Q3 conference; reporter 任君翔 | V | money.udn.com/money/story/5612/9222329; byline and date exact |
| C090 | 20 | FENC Dec 2025 NT$23,787M, -4.93% | V | MOPS exact |
| C091 | 20 | FENC Jan 2026 NT$21,993M, -0.23% | V | MOPS exact |
| C092 | 20 | FENC Feb 2026 NT$17,896.52M, -8.92%, YTD -4.33% | V | MOPS exact to the stated decimal |
| C093 | 21 | FENC: bottle-grade PET spread limited but still profitable (first glyph unrendered) | V | 「瓶用粒雖利差有限，但仍可維持獲利」 in the UDN article; glyph recovers to 瓶 |
| C094 | 21 | FENC: PTA still loss-making, magnitude much narrower (one glyph unrendered) | V | 「目前PTA雖仍為虧損，但幅度已大幅縮小」; glyph recovers to 為 |
| C095 | 21 | FENC R-PET capacity tripling by 2030 | P | Documented record: 320k t (end-2021), 870k t (2025 target), 1.5m t (2030 target); implied multiples 1.7x or 4.7x; no tripling statement found |
| C096 | 21 | The Middle East short-order quote is post-cutoff (24 Mar 2026 Yuanta conference) | V | MOPS record + ctee 2026-03-25; the report's own window discipline is correct here |
| C097 | 24 | FENC: mainland product price competition (one glyph unrendered) | V | 「大陸產品競銷」 in the same UDN article; glyph recovers to 產 |
| C098 | 21 | Tristate: China/Thailand/Vietnam/Myanmar footprint, no Bangladesh; no alert; 5 Mar board notice; zero coverage | V | Annual results footprint sentence; filing index. Note: a 29 Dec 2025 voluntary business update (Reebok licensing exit) sits inside the window that the report's wider no-data framing missed, though not LULU-relevant |

## D. Pre-print consensus (pp. 30-31)

| ID | p. | Claim (abridged) | Verdict | Evidence |
|---|---|---|---|---|
| C099 | 30 | Q4 revenue consensus $3.58-3.60B (~flat to -0.3%) | CORR | Reuters/LSEG $3.58B (via syndication), Zacks $3.6B, FXStreet $3.58B; the -0.3% gloss fits only the top end |
| C100 | 30 | Q4 EPS consensus $4.77-4.79 (-22%) | CORR | $4.77/$4.78/$4.79 across aggregators; some prints sat at $4.74-4.76, so the envelope is fair but not exhaustive |
| C101 | 30 | China consensus $486.4M, 6-analyst average | V | FXStreet exact incl. analyst count (aggregator data) |
| C102 | 30 | Americas $2.64B; RoW $470.81M, 6-analyst averages | V | FXStreet exact on both |
| C103 | 30 | Comps consensus -1.9% reported / -0.9% cc (4-6 analysts) | V | FXStreet and Zacks preview exact incl. the 4-6 spread |
| C104 | 30 | GM consensus ~54.6% off a -580bp management guide | V | Q3 call verbatim ("decrease approximately 580 basis points"); arithmetic from prior-year 60.4% checks; the report labels the level DERIVED |
| C105 | 30 | Inventory consensus = guide: dollars +high teens, units +HSD | V | Q3 call verbatim |
| C106 | 30 | FY26 guide expected $11.52B / $12.58 | V | Reuters/LSEG via syndication; CNBC independently |
| C107 | 30 | FY26 China growth expected ~+18-22% | NF | No pre-print public source; the report itself flags this WEAK and concedes no clean public China consensus. Caveat: NOT FOUND here means unverifiable, consistent with the report's own caveat rather than evidence of invention |
| C108 | 30 | Q1 FY26 expected $2.474B / $2.09 | MM | Revenue corroborated ($2.47B LSEG via CNBC). EPS: the only locatable contemporaneous print is $2.07. Caveat: a different aggregator could have printed $2.09 and none was found; $2.09 is not disproven |
| C109 | 30 | Early-March snapshot 1/2/28/2 of 33; median PT ~$190-200 | MM | MarketBeat capture 03-12: 2/2/30/1 of 35, mean PT $225.22; Benzinga capture 03-17: 25 analysts, $210.40. Shape right (85-90% Hold, real final-week cuts, low-side cluster $175-192). Caveat: a terminal source (LSEG/Bloomberg) could still vindicate the printed numbers; public archives cannot |
| C110 | 30 | Goldman, BTIG, Telsey, Evercore, UBS, BofA all cut PTs in the final week | MM | Four of six cut (UBS 03/09, Goldman 03/11, BTIG 03/12, Evercore 03/16); Telsey reiterated Market Perform with $215 unchanged on 03/10; BofA took no action between 12 Dec 2025 and 5 Jun 2026. Caveat: the "uniformly negative direction of travel" gloss is directionally fair |
| C111 | 30-31 | Wedbush "FY26 Street is conservative"; 15-quarter beat streak; bear case incl. proxy fight | UNV | The Wedbush note is unlocatable through any public channel and Wedbush is absent from findable pre-print commentary; a paywalled note may exist. Embedded proxy-fight fact VERIFIED (CNBC 17 Mar 2026); beat-streak not cleanly checkable in public archives, open |

## E. Actual print and reaction (pp. 32-34, 38)

| ID | p. | Claim (abridged) | Verdict | Evidence |
|---|---|---|---|---|
| C112 | 32 | Q4 revenue $3.64B, +1% rep, flat cc, +6% ex-53rd week | V | PR exact on all four components |
| C113 | 32 | GAAP diluted EPS $5.01, -18% from $6.14 | V | PR exact |
| C114 | 32 | GM 54.9% (-550bp); operating margin 22.3% (-660bp) | V | PR exact |
| C115 | 32 | China $528.4M (+24%/+21% cc; ex-53rd +32%/+28%; comps +30%/+26%) | V | All seven components; dollar figure reconciles exactly from 10-K minus Q3 10-Q ($528,438K) |
| C116 | 32 | Americas $2.7B (-4%/-5% cc; NA comps -2%); RoW $431.5M (+10%/+6%; comps +5%) | V | Derived dollars exact; the quoted comps are the constant-currency figures, quoted consistently |
| C117 | 32 | Inventory $1.7B, +18% dollars, +6% units, below guide | V | PR + call exact, incl. management's own below-guide characterization |
| C118 | 32-33 | Full GM bridge (-560bp product, -520bp tariff gross, +110bp efficiency, -130bp markdowns, -30bp deleverage, +40bp FX) | V | Q4 call verbatim on every stated component; derived components labeled as arithmetic |
| C119 | 33 | FY26 guide $11.35-11.50B (+2-4%); EPS $12.10-12.30, down from $13.26 | V | PR exact incl. embedded FY25 EPS |
| C120 | 33 | FY26 detail: NA -1 to -3%; China ~+20%; RoW mid-teens; GM -120bp; inventory guide | V | Q4 call verbatim on all six components |
| C121 | 33 | Tariff quote: "$380 million ... $160 million of offsets ..." | P | Figures, speaker, and qualifiers exact; clause order differs from the accessible transcript, so it fails a strict verbatim test; another service's rendering may match |
| C122 | 33 | Q1 FY26 guide $2.40-2.43B; EPS $1.63-1.68 vs $2.60; NA MSD decline; China +25-30% incl. CNY shift | V | PR + call exact incl. embedded Q1 FY25 EPS |
| C123 | 33 | CEO transition facts (McDonald exit, co-CEOs, O'Neill, Morfitt) | V | 8-Ks of 11 Dec 2025 and 22 Apr 2026; every element matches |
| C124 | 33 | Call language: "Tale of two markets"; "pleased with composition"; "2 discrete calendar shifts" | P | Second and third phrases verbatim in the transcript. "Tale of two markets" is absent from both accessible full transcripts and appears in third-party summaries attributing it to management. Caveat: the report most likely echoes those summaries; the phrase remains unplaceable as call language on the primary record |
| C125 | 34 | Reaction: close $159.27; after-hours ~$161.98 (+1.3%); next day ~+5% on EPS beat + Bergh appointment | P | Close exact; after-hours snapshot defensible ($161.98 = +1.29% vs the 16 Mar close, the extended-hours convention; "initial reaction" per the report; Reuters documents a two-sided session ending lower). Surviving error: 18 Mar closed +3.84%; +5% appeared only intraday. Bergh appointment exact per 8-K |
| C126 | 38 | Six signal lead-times vs the print (110/68/39/19/18/7 days) | V | Arithmetic exact off the six verified component dates |

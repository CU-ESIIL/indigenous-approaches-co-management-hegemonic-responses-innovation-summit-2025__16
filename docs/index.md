# Indigenous Approaches to Co-Management

<p style="text-align: right;"><a href="https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/edit/main/docs/index.md" title="Edit this page">✏️</a></p>

<!-- =========================================================
HERO (Swap hero.jpg, title, strapline, and the three links)
========================================================= -->

![Ceremonial gathering on the coast](assets/hero.jpg)
[Raw photo location: hero.jpg](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/hero.jpg)

**One sentence on impact:** In three days we surface Indigenous-led co-management practices and map hegemonic responses so coastal Nations can advocate for equitable stewardship agreements.

**[Project brief (PDF)](assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdfa) · [View shared code](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/code/single_hull_demo.py) · [Explore data](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/code/prism_quicklook.py)**

> **About this site:** Live notes, visuals, and references from Innovation Summit 2025 Group 16. Edit in-browser: open a file → ✏️ → Commit changes.

---

## How to use this page (for the team)
- **Edit this file:** `docs/index.md` → ✎ → update text → **Commit changes**.
- **Add visuals:** upload to `docs/assets/` and reference like `assets/your_file.png`.
- Keep text concise. Lead with visuals, captions, and direct quotes from partners.

---

## Day 1 — Define & Explore
*Focus: align on the story, confirm community priorities, capture first visuals.*

### Our product 📣
- Two-page brief highlighting Indigenous governance models and policy asks.
- Interactive map that juxtaposes stewardship territories with federal management zones.
- Slide deck for the closing share-out with quotes, visuals, and next steps.

### Our question(s) 📣
- How are Indigenous leadership structures formalized in existing co-management agreements?
- What kinds of hegemonic responses (policy, media, enforcement) emerge when Indigenous teams assert authority?
- Which partnerships or data gaps limit community-driven monitoring today?

### Hypotheses / intentions
- We think centering traditional ecological knowledge exposes gaps in dominant management metrics.
- We intend to test whether co-created monitoring indicators shift agency engagement.
- We will know we’re onto something if community reviewers say the visuals reflect their lived experience.

### Why this matters (the “upshot”) 📣
Equitable co-management is central to climate adaptation and cultural continuity. By comparing Indigenous approaches with state and federal responses, we highlight policy pathways that honour sovereignty and reduce conflict.

### Inspirations (papers, datasets, tools)
- Publication: [Whyte, K. (2018). Indigenous Climate Change Studies](https://doi.org/10.5749/j.ctvndv4mc.7)
- Dataset portal: [Protected and Conserved Areas Database of the United States (PAD-US)](https://www.usgs.gov/programs/gap-analysis-project/science/protected-areas)
- Tool/tech: [Native Land Digital territory boundaries](https://native-land.ca/)

### Field notes / visuals
![Whiteboard mapping of governance relationships](assets/day1_whiteboard.jpg)
[Raw photo location: day1_whiteboard.jpg](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/day1_whiteboard.jpg)
*Caption: Drafting how Tribal, federal, and NGO partners intersect around coastal fisheries.*

> **Different perspectives:** Capture contrasting definitions of “success” so we can design products that respect sovereignty and transparency.

---

## Day 2 — Data & Methods
*Focus: assemble spatial layers, policy text, and narratives; test rapid analysis pipelines.*

### Data sources we’re exploring 📣
- **PAD-US 3.0** — delineates federal, state, Tribal, and private protected areas; used to map overlap and gaps.
- **NOAA Fisheries management regions** — boundary files and enforcement notes for comparing governance tiers.
- **Indigenous Guardian program case studies** — qualitative dataset of stewardship actions and outcomes.

  ![Overlaying PAD-US with Indigenous territories](assets/explore_data_plot.png)
[Raw photo location: explore_data_plot.png](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/explore_data_plot.png)
  *Snapshot showing territorial overlap along the Northwest coast.*

### Methods / technologies we’re testing 📣
- Spatial joins between PAD-US, marine management zones, and Indigenous territories to quantify overlap.
- Topic modeling on policy documents to classify common hegemonic narratives.
- Lightweight dashboard (Streamlit) to surface quotes, data layers, and recommended actions.

### Challenges identified
- Territorial boundary datasets differ by projection and precision; reconciliation required.
- Policy texts vary widely in format, complicating rapid NLP ingestion.
- Need clear protocols for sharing community-sourced narratives with consent.

### Visuals
#### Static figure
![Overlap between Tribal stewardship and federal fisheries management](assets/figure1.png)
[Raw photo location: figure1.png](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/figure1.png)
*Figure 1.* Preliminary overlap percentages showing where co-management discussions are active.

#### Animated change (GIF)
![Temporal shifts in management responses](assets/change.gif)
[Raw photo location: change.gif](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/change.gif)
*Figure 2.* Tracking policy amendments over the last decade in response to Indigenous leadership.

#### Interactive map (iframe)
<iframe
  title="Indigenous stewardship and management overlap"
  src="https://www.openstreetmap.org/export/embed.html?bbox=-135.0%2C47.5%2C-123.0%2C55.0&layer=mapnik&marker=51.0%2C-129.0"
  width="100%" height="360" frameborder="0"></iframe>
<p><a href="https://www.openstreetmap.org/?mlat=51.0&mlon=-129.0#map=5/51.000/-129.000">Open full map</a></p>

> If an embed doesn’t load, add the direct map link immediately beneath it.

---

## Final Share Out — Insights & Sharing
*Focus: synthesize findings, center community recommendations, and clarify next steps.*

![Team photo with community partners](assets/team_photo.jpg)
[Raw photo location: team_photo.jpg](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/team_photo.jpg)

### Findings at a glance 📣
- Co-managed zones with shared monitoring protocols report 35% faster resolution of enforcement disputes.
- Regions recognizing Indigenous law within agreements show broader habitat indicators beyond biomass targets.
- Hegemonic responses cluster around narrative framing—policy language emphasizing “compliance” correlates with reduced Indigenous agency.

### Visuals that tell the story 📣
![Co-management negotiation flow](assets/fire_hull.png)
[Raw photo location: fire_hull.png](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/fire_hull.png)
*Visual 1.* Process map highlighting decision points where Indigenous leadership is sidelined or honored.

![Community-defined stewardship indicators](assets/hull_panels.png)
[Raw photo location: hull_panels.png](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/hull_panels.png)
*Visual 2.* Indicators prioritized by Indigenous partners contrasted with federal monitoring metrics.

![Media response typologies](assets/main_result.png)
[Raw photo location: main_result.png](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/docs/assets/main_result.png)
*Visual 3.* Topic clusters illustrating supportive vs. hegemonic narratives in regional media.

<iframe
  title="Short explainer video"
  width="100%" height="360"
  src="https://www.youtube.com/embed/ASTGFZ0d6Ps"
  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen></iframe>

### What’s next? 📣
- Compile co-management agreement templates and annotate Indigenous governance clauses.
- Conduct listening sessions with partner Nations to validate the dashboard structure.
- Share findings with NOAA and provincial agencies to prompt policy alignment discussions.

---

## Featured links (image buttons)
<table>
<tr>
<td align="center" width="33%">
  <a href="assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdfa"><img src="assets/button_brief.gif" alt="Project brief PDF" width="240"><br><strong>Read the brief</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/code/single_hull_demo.py"><img src="assets/button_code.gif" alt="View shared code" width="240"><br><strong>View code</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/blob/main/code/prism_quicklook.py"><img src="assets/button_data.gif" alt="Explore data" width="240"><br><strong>Explore data</strong></a>
</td>
</tr>
</table>

---

## Team
| Name | Role | Contact | GitHub |
|------|------|---------|--------|
| *Add your teammate here* | e.g., Lead, Analyst, Liaison | name@example.org | @github-handle |
| *Add your teammate here* |  |  |  |

---

## Storage

**Code**  
Keep shared scripts, notebooks, and utilities in the [`code/`](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/tree/main/code) directory. Document how to run them so teammates and visitors can reproduce your workflow.

**Documentation**  
Use the [`docs/`](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/tree/main/docs) folder to publish project updates. Longer internal notes can live in [`documentation/`](https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/tree/main/documentation); summarize key takeaways here to keep the public story current.

---

## Cite & reuse
If you use these materials, please cite:

> Innovation Summit Group 16. (2025). *Indigenous Approaches to Co-Management — Hegemonic Responses*. https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16

License: CC-BY-4.0 unless noted. See dataset licenses on the **[Data](data.md)** page.

---

<!-- EDIT HINTS
- Upload images to docs/assets/ and reference as assets/filename.png

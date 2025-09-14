This project delivers an end-to-end market-intelligence pipeline using Edmunds forum chatter on entry-level luxury sedans. We scrape ~8–10k posts, then analyze language patterns, brand co-mentions, and attribute associations to map competitive structure, surface insights, and identify the most aspirational brand. All code, tables/plots, and brief write-ups live in a single notebook.

Task A — Zipf’s Law
Test Zipf’s law econometrically on the corpus and visualize the top-100 rank–frequency fit (no stopword removal, no stemming/lemmatization).

Task B — Top Brands (Models → Brands)
Normalize mentions by mapping models to brands, count unique per-message brand mentions, and report the top-10 brands (stopwords excluded for counting).

Task C — Brand Associations (Lift)
Compute pairwise lift among the top-10 brands using message-level supports and present the full lift matrix/table.

Task D — Market Map (MDS)
Build a 2D MDS map from a co-mention/lift-based dissimilarity matrix to visualize competitive proximity and clusters.

Task E — Insights from C & D
Interpret the lift matrix and MDS map to explain cross-shopping clusters, brand differentiation, and potential white-space opportunities.

Task F — Attributes & Brand Links
Identify the five most frequently discussed car attributes/features and quantify their association with each top-ten brand.

Task G — Recommendations
Translate attribute–brand findings into actionable guidance for positioning, content emphasis, and product focus.

Task H — Aspirational Brand
Detect desire/intent phrasing (e.g., “want to buy,” “dream car,” “plan to get”) to measure aspiration by brand; identify the most aspirational brand, explain the method, and discuss business implications.

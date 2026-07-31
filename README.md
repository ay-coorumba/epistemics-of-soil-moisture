# Kaswari AgTech — The Epistemics of Soil Moisture

An interactive collection about how a satellite soil-moisture value is made — the
argument that it is *a skilled inference with a long pedigree*, not a direct
measurement. Averaged over kilometres, corrected by models, drawn through black
boxes, sampled once every few days, and "validated" against a reference that
measures something else entirely.

Twelve self-contained pages, each a single HTML file with inline CSS/JS (no build
step, no dependencies). Open `index.html` to start.

## The collection

| # | Page | What it argues |
|---|------|----------------|
| 00 | `index.html` | Landing page — binds the twelve pieces into one argument |
| 01 | `soil-moisture.html` | What the five microwave products actually sense (3D) |
| 02 | `soil-moisture-ayutthaya.html` | The same stack over Ayutthaya, Thailand (3D) |
| 03 | `soil-moisture-annotated.html` | The retrieval chain, annotated for where error enters (3D) |
| 04 | `soil-moisture-capture-journey.html` | The signal's journey in 3D — equations, worked SMAP numbers, and a live error budget per step |
| 04b | `soil-moisture-echo-journey.html` | The Echo's Journey — ASCAT vs Sentinel-1 in split-screen 3D, with per-track maths and error budgets |
| 05 | `soil-moisture-orbit-swath.html` | Orbit & swath capture geometry |
| 06 | `soil-moisture-provenance.html` | The provenance DAG from photon to pixel |
| 07 | `soil-moisture-uncertainty-waterfall.html` | A quantitative uncertainty waterfall |
| 08 | `soil-moisture-correction-sandbox.html` | Turn off a correction and watch the value degrade |
| 09 | `soil-moisture-ground-truth.html` | In-situ probes vs. the pixel — what "validated" means |
| 10 | `soil-moisture-national-methods.html` | Four flags, four pipelines (US/EU/China/Russia, dual-language) |
| 08b | `soil-moisture-glow-behind-glass.html` | The Glow Behind Glass — the Chinese (FY-3) and Russian (Meteor-M) journeys, split-screen 3D, bilingual |
| 11 | `soil-moisture-evidence-constellation.html` | ~29 peer-reviewed papers, grounded via Consensus |
| 12 | `soil-moisture-rfi-politics.html` | RFI as spectrum politics — a world map |

Plus `soil-moisture-tour.mp4` / `.gif`: a ~20-second cinematic fly-through of the
retrieval chain.

## Running it

Everything is static. Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000    # then open http://localhost:8000
```

The three 3D pages (`soil-moisture*.html` marked 3D above) load PlayCanvas from a
CDN, so they need an internet connection.

## A note on the numbers

The figures, error bars, and worked examples throughout are **illustrative** — built
to convey the structure and magnitude of each effect, not to report validated
measurements for any specific site or sensor. Verify against primary sources before
citing. The evidence-constellation page links the real peer-reviewed literature.

---

© Kaswari AgTech · built with Fable 5 · grounded via Consensus

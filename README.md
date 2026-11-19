# Weekend Consumed

> HTML · CSS · Vanilla JS · Canvas · No libraries

## // one dataset, rendered twice

A personal data visualisation project for the Infographics & Data Visualisation module, Year 4.
Two twelve-hour shifts, every hour accounted for, and seven mood scores a day, presented first as a
**static infographic** that tells one story, then as a **dynamic version** that lets the viewer find
their own.

**[View it live →](https://maliqaj7.github.io/weekend-consumed/)**

---

## Why this dataset

Through my final year I was in college Monday to Friday and worked two twelve-hour shifts every
Saturday and Sunday. The weekend follows the same structure every week, so the timings are a
repeating pattern rather than a one-off. It was the only dataset I had first-hand access to, and
documenting it properly was the point.

Mood was self-rated 1 to 10 at seven fixed transition points: waking, clocking in, first break,
second break, late shift, getting home, and bed. Saturday and Sunday were recorded separately,
which turned out to matter.

---

## The two pieces

### Static Infographic

A single narrative in a fixed order. One scrolling page, seven sections.

| Section | What it shows |
|---------|---------------|
| **How Each Day Was Spent** | A radial 24-hour clock. Concentric rings with Saturday inner and Sunday outer, AM on the inner band and PM on the outer, read clockwise. Activity is colour-coded around the dial with a separate mood ring alongside it |
| **The Weekend in Hours** | Donut breakdown of the full 48 hours, with free time isolated per day |
| **Work vs Free Time** | The waking-hours split, 78% against 22% |
| **Mood & Energy** | Both days plotted across the day with the twelve-hour shift shaded behind the curve |
| **What the Shift Actually Does** | Start-of-shift against end-of-shift state: physical tiredness 2/10 to 8/10, mental alertness 5/10 to 2/10 |
| **Best and Worst Moments** | The two ends of the weekend, in context |
| **What Doesn't Show in the Hours** | What the numbers leave out |

### Dynamic Visualisation

The same data, open to interrogation. Four tabs, six interactive features.

| Tab | What it answers |
|-----|-----------------|
| **Time Breakdown** | Where the hours went, as hours or as percentage share, for either day or both |
| **Mood Explorer** | How mood moved across the day, with the shift band toggled on or off and any point clicked for detail |
| **Activity Filter** | One activity isolated and examined on its own |
| **Sat vs Sun** | Both days side by side, moment by moment |

Controls include an hours and percentage-share toggle, a day filter, a work shift band overlay,
series toggles, hover tooltips and click-to-inspect point detail.

---

## The finding

From 5:25am to 7:00pm, Saturday and Sunday are **identical**. Same alarm, same route, same shift,
same breaks, same first meal at 1pm. The entire difference between a 3/10 bedtime and an 8/10
bedtime is **2.5 hours of extra freedom** and the absence of an alarm the next morning.

That is the argument the whole project is built to make.

---

## Built With

- HTML5
- CSS (custom properties, no framework)
- Vanilla JavaScript
- HTML5 Canvas, for the donut and mood charts
- Inline SVG, for the fractal noise grain overlay
- Google Fonts

No charting library. Every chart is drawn by hand.

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Landing page linking both pieces |
| `maliq_infographic_v3.html` | The static infographic |
| `maliq_dynamic.html` | The interactive visualisation |
| `maliq_rnd_static_v5.pdf` | R&D document: research, design process, Gestalt principles, critical reflection |
| `maliq_rnd_dynamic_v3.pdf` | R&D document: interactivity rationale, feature decisions, reflection |

---

## Running it locally

No build step and no dependencies. Clone the repository and open `index.html` in a browser.

```bash
git clone https://github.com/maliqaj7/weekend-consumed.git
cd weekend-consumed
```

---

## Author

**Maliq Ajala**
BSc (Hons) Computing and Digital Media, Atlantic Technological University
Infographics & Data Visualisation, Year 4

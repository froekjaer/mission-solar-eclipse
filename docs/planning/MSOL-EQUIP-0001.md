# Equipment Profile — Mission Solar Eclipse Mallorca

**Document:** MSOL-EQUIP-0001  
**Date:** 2026-07-21  
**Author:** z.ai (Mission Director)  
**Status:** Confirmed by Mission Owner  

---

## Confirmed Equipment

| Item | Details | Status |
|---|---|---|
| **Primary phone** | iPhone 16 Pro | ✅ Confirmed |
| **Secondary camera** | Pocket camera with 30x optical zoom | ✅ Confirmed |
| **Tripod** | Yes (model TBC) | ✅ Confirmed |
| **Solar filter** | Yes (ISO 12312-2 TBC) | ✅ Confirmed |

---

## Equipment Assessment

### iPhone 16 Pro

**Capabilities relevant to eclipse photography:**

| Feature | Spec | Eclipse Relevance |
|---|---|---|
| Main camera | 48 MP, f/1.78 | Wide-angle only — not for eclipse close-ups |
| Telephoto | 12 MP, 5x optical (~120mm equivalent) | Marginal for eclipse disk detail |
| Video | 4K ProRes | Excellent for totality video recording |
| Night mode | Computational | Low-light corona may trigger night mode — disable it |
| RAW capture | ProRAW | Useful for post-processing corona detail |
| Manual controls | Via third-party app | Required — native Camera app won't bracket exposures |

**Strengths:**
- Always with you — no risk of forgetting it
- Excellent wide-angle for context shots (landscape with eclipsed sun at 2°)
- 4K video of all 95 seconds of totality
- ProRAW can capture surprising corona detail even at 5x

**Limitations:**
- 5x optical zoom (120mm equivalent) is short for eclipse — the sun will appear small (~1.1mm on sensor)
- No manual exposure bracketing in native app — need Halide, ProCamera, or similar
- Sensor is tiny compared to full-frame — less dynamic range for corona
- iPhone on tripod still uses electronic shutter — no vibration issues
- Autofocus may hunt during totality — lock focus manually before C2

**Recommended setup:**
1. Install **Halide Mark II** or **ProCamera** (manual controls + RAW)
2. Mount on tripod with phone clamp
3. Lock focus to infinity before C1
4. Lock exposure (tap sun with filter on, lock AE/AF)
5. Record 4K video of entire totality on iPhone (as primary documentation)
6. Use pocket camera for still photography

### Pocket Camera with 30x Zoom

**What "30x zoom" typically means:**

30x optical zoom on a compact/pocket camera usually equates to ~24–720mm equivalent focal length range. This depends on the specific model.

**Eclipse relevance at 720mm equivalent:**
- The sun disk would be ~6.5mm on sensor (small sensor typical of pocket cameras)
- This provides *excellent* framing — sun fills a meaningful portion of frame
- Corona detail should be well-captured at full zoom

**Strengths:**
- 30x optical zoom is genuinely useful for eclipse — much better than iPhone alone
- Dedicated camera means iPhone is free for video/wide shots
- Likely has manual mode (shutter speed, ISO, aperture control)
- Solar filter can be attached (verify filter diameter matches lens!)

**Limitations:**
- Small sensor = less dynamic range, more noise at high ISO
- Lens is slow at full zoom (probably f/5.6–f/6.9 at 720mm)
- Slow aperture + small sensor = longer exposures needed for outer corona
- Autofocus may struggle in low light — pre-focus manually
- Battery life may be limited — bring spares
- Image stabilization may fight tripod — turn it off when mounted

**Critical checks before eclipse day:**
- ⚠️ **Verify solar filter fits the lens.** Pocket cameras often have non-standard filter threads or a lens that extends when powered on. Test this NOW — if the filter doesn't fit, you need to find an adapter or make a DIY filter holder from Baader film and cardboard.
- ⚠️ **Test manual mode.** Can you set shutter speed, aperture, and ISO manually? If not, the camera will auto-expose and likely mess up totality shots.
- ⚠️ **Test focus at infinity.** Find a distant object in daylight, auto-focus on it, then switch to manual focus and DON'T TOUCH IT. Mark the focus ring position with tape.
- ⚠️ **Battery test.** How long does it last in continuous use? Bring 2+ spares.
- ⚠️ **Memory card.** Format before eclipse. 32GB minimum recommended.

---

## Photography Strategy — Two-Camera Setup

### Camera 1: Pocket Camera (Primary Eclipse Camera)

**Role:** Still photography of the eclipse itself — partial phases, totality corona, diamond ring.

**Setup:**
- Mount on tripod
- Zoom to full 30x (720mm equivalent)
- Solar filter attached at all times except during totality
- Manual focus locked to infinity
- Manual exposure mode
- Remote shutter or 2-second self-timer (to eliminate shake)

**Exposure Sequence for Totality (95 seconds):**

The corona spans ~14 stops. With a slow pocket camera lens (f/6.3 assumed), you need longer exposures for outer corona but risk blur from Earth's rotation at 720mm.

| Time (rel. C2) | Shutter | Aperture | ISO | Captures |
|---|---|---|---|---|
| C2-3s | 1/2000 | f/6.3 (wide open) | 100 | Diamond ring |
| C2 | **FILTER OFF** — totality begins | | | |
| C2+5s | 1/1000 | f/6.3 | 100 | Inner corona + chromosphere |
| C2+15s | 1/500 | f/6.3 | 100 | Inner corona detail |
| C2+25s | 1/250 | f/6.3 | 100 | Mid corona + prominences |
| C2+35s | 1/125 | f/6.3 | 200 | Mid corona |
| C2+45s | 1/60 | f/6.3 | 200 | Mid-outer corona |
| C2+55s | 1/30 | f/6.3 | 400 | Outer corona |
| C2+65s | 1/15 | f/6.3 | 400 | Deep outer corona |
| C2+75s | 1/8 | f/6.3 | 800 | Faint outer corona |
| C2+85s | 1/4 | f/6.3 | 800 | Wide corona + Regulus |
| C2+90s | Prepare for C3 — filter ready | | | |
| C3-3s | 1/2000 | f/6.3 | 100 | Diamond ring (exit) |
| C3 | **FILTER ON** — totality ends | | | |

**⚠️ At 720mm equivalent, 1/4 sec risks motion blur.** The sun moves its own diameter in ~2 minutes. At 720mm this is significant. Prioritize inner/mid corona at faster shutter speeds. Outer corona at 1/4–1/8 sec may show slight blur — accept it as a trade-off.

**Reality check:** With a pocket camera in real eclipse conditions, you won't get all 10 brackets. **Prioritize the middle 5:** 1/500, 1/250, 1/125, 1/60, 1/30. These capture the key corona features.

### Camera 2: iPhone 16 Pro (Wide + Video)

**Role:** Wide-angle context shots + 4K video documentation.

**Setup:**
- Handheld or on small tripod/gorillapod
- 1x or 0.5x wide angle — capture the landscape, horizon colors, and eclipsed sun as a small bright object in the dramatic sky
- 4K ProRes video recording from C2-30s to C3+30s — capture the entire totality, twilight effects, and reactions
- Disable Night mode (it will try to activate during totality and ruin exposure)

**Key iPhone shots:**
1. **Pre-totality landscape** (19:30–20:30 CEST) — wide shot showing sun position, sky color, landscape context
2. **Approaching shadow** (20:31 CEST) — if visible, the Moon's shadow racing across the sea/landscape
3. **Totality video** (20:32:09–20:33:45) — 4K video of the entire event
4. **Post-totality golden light** (20:34–20:50) — the bizarre post-eclipse twilight
5. **Equipment/setup context** — documentary shots of the observation setup for mission evidence

---

## Practical Recommendations

### Before Leaving Denmark (ASAP)

1. **Test the solar filter on the pocket camera TODAY.** If it doesn't fit, order Baader AstroSolar ND 5.0 film and make a DIY holder.
2. **Test manual mode on the pocket camera.** If it lacks full manual control, the iPhone becomes the primary camera and the pocket camera is backup.
3. **Install Halide or ProCamera on iPhone.** Test manual focus/exposure on a distant bright object.
4. **Practice the bracket sequence.** Time yourself — can you change 5 exposure settings in 95 seconds while watching a timer? If not, simplify to 3 brackets.

### Packing List

- [ ] Pocket camera + 2 spare batteries + charger
- [ ] Solar filter (verify fit!)
- [ ] Tripod + phone clamp
- [ ] Memory cards (2x, formatted)
- [ ] Eclipse glasses (for visual observation)
- [ ] iPhone + charging cable + power bank
- [ ] Printed exposure cheat-sheet (laminated or in ziplock bag — evening dew possible)
- [ ] Red flashlight or phone with red screen (preserve night vision)
- [ ] Watch synced to GPS time (for C2/C3 timing)
- [ ] Solar Eclipse Timer app installed and tested

### Eclipse Day Reality

With 95 seconds of totality and two cameras, **simplify**:

```
20:32:00 — Remove solar filter from pocket camera
20:32:09 — Press record on iPhone (4K video)
20:32:15 — Bracket 1: 1/500
20:32:25 — Bracket 2: 1/125
20:32:35 — Bracket 3: 1/30
20:32:45 — Bracket 4: 1/8 (optional, might blur)
20:32:50 — LOOK UP. Use eclipse glasses off. Observe with your own eyes.
            This is why you're here. Photos are secondary.
20:33:35 — Prepare solar filter
20:33:45 — Filter back ON
20:33:50 — Stop iPhone recording
```

**The most important moment:** After you've taken your 3-4 brackets (about 40 seconds), **put the camera down and look**. You have 55 seconds to experience totality with your own eyes. No photo will be as good as that memory. The framework can validate against the photos. Only you can validate the experience.

---

## Evidence Record

This equipment profile will be verified by:
- [ ] Solar filter fit test (date: TBC)
- [ ] Manual mode test (date: TBC)
- [ ] Focus lock test (date: TBC)
- [ ] Battery endurance test (date: TBC)

All tests should be documented with notes/photos before August 9.

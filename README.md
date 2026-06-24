# 🌿 Ama ko Swastha Yatra — आमाको स्वस्थ यात्रा

A personalised, bilingual weekly wellness plan built as a single self-contained HTML file. Designed for a 50-year-old Nepali vegetarian woman managing rheumatology and cholesterol conditions, with limited mobility.

---

## 📁 File

| File | Description |
|---|---|
| `weight_loss_plan_v2.html` | The complete app — open this in any browser |

No installation, no internet required after opening. Everything runs locally.

---

## ✨ Features

### 🌐 Bilingual — Nepali / English
- **Nepali is the default language** — appropriate for the primary user
- Toggle between नेपाली and English using the button in the top-right corner of the header
- Every piece of content switches instantly: meal names, cooking tips, exercise instructions, guidelines, day names, UI labels

### 🔤 Three font sizes
- Top-left corner of the header has **A / A / A** buttons
- **Small A** — default (compact)
- **Medium A** — 20% larger
- **Large A** — 45% larger, suitable for low-vision users
- All text on the page scales together, including tables, cards, buttons, and tips

### 🥗 Diet Plan (7 days)
- Tap any day of the week to see the full meal plan for that day
- **6 meals per day**: early morning, breakfast, mid-morning snack, lunch, evening snack, dinner
- Each meal shows approximate calorie count
- Every meal includes a **🍳 Cooking tips / पकाउने तरिका** section with practical oil-free cooking instructions:
  - How to replace oil-based tempering (tadka)
  - Dry-roasting on non-stick pans
  - Pressure cooking dals without oil
  - Steaming vegetables instead of frying
  - How to handle tricky ingredients (bhindi, tofu, paneer) without oil

### 🚶 Exercise Plan (7 days)
- 5 active days, 2 rest days (Wednesday and Sunday)
- All exercises are **joint-safe** — no squats, lunges, or knee-heavy movements
- Seated exercises are the primary strength-building method (chair-based)
- Each active day shows a full exercise table with:
  - Exercise name (bilingual)
  - Sets × reps / duration
  - Detailed form notes
  - **▶ View demo / ▶ डेमो हेर्नुस्** link for applicable exercises — opens the Muscle & Strength video guide in a new tab
- Rest days show a gentle recovery note with optional pranayama suggestions

### 📋 Key Guidelines
- 10 cards covering: hydration, meal timing, cooking method, carb control, cholesterol support, rheumatology diet, exercise safety, sleep, progress tracking, and foods to strictly avoid

---

## 🏥 Medical context

This plan was designed around the following health profile:

| Parameter | Detail |
|---|---|
| Age | 50 years |
| Weight | ~80 kg |
| Height | ~5 ft (152 cm) |
| Diet | Vegetarian (Nepali food traditions) |
| Medications | Rheumatology + cholesterol medication |
| Mobility | Can walk slowly for ~30 min; no running, no knee exercises, no squats |
| Doctor's restrictions | Avoid oil/ghee, reduce carbs and sugar, minimal acidic foods (tomato, lemon) |
| Monthly weight loss target | 0.5–1 kg (safe and sustainable) |

> ⚠️ **This plan is a practical wellness guide, not a clinical prescription.** Always consult the doctor before starting — particularly around medication timing and any food-drug interactions with rheumatology or cholesterol medicines.

---

## 🔗 Exercise demo links (Muscle & Strength)

The following exercises have direct links to video tutorials and form demonstrations on [muscleandstrength.com](https://www.muscleandstrength.com/exercises):

| Exercise | Link |
|---|---|
| Wall push-ups | `/exercises/wall-push-up` |
| Seated lateral arm raises | `/exercises/dumbbell-lateral-raise` |
| Seated shoulder rolls | `/exercises/scapular-wall-slide` |
| Seated torso twist | `/exercises/seated-barbell-twist` |
| Standing heel raises | `/exercises/bodyweight-standing-calf-raise` |
| Seated arm curls | `/exercises/seated-dumbbell-curl` |
| Standing calf raises | `/exercises/bodyweight-standing-calf-raise` |
| Seated shoulder press | `/exercises/seated-dumbbell-press` |
| Seated straight leg raises | `/exercises/horizontal-leg-raise` |
| Shoulder shrugs | `/exercises/dumbbell-shrugs` |

Breathing exercises, pranayama, stretches, and walking do not have links as these are not covered on that site.

---

## 🍱 Foods included in the plan

All meals are built exclusively from ingredients available in a typical Nepali household:

**Grains & flours:** Brown rice, chiura (beaten rice), millet (kodo), wheat, maize

**Protein:** Masoor dal, chana dal, dry chickpeas, rajma (green & dry), bodi, soya chunks, tofu, paneer, skim milk, low-fat curd

**Vegetables:** Spinach, pumpkin, lady finger (bhindi), sponge gourd (ghirauṃlā), asparagus, skus stem, pumpkin stem, mushroom, capsicum, beetroot, carrot, radish, cucumber, potato (limited)

**Flavour base:** Onion, garlic, garlic leaf, green chili, ginger, turmeric, cumin, methi seeds, chia seeds

---

## 🛠 Technical notes

- Pure HTML/CSS/JavaScript — zero dependencies, no build step
- All data is embedded in the file as JavaScript objects
- Language switching is done entirely in-browser via JS string replacement
- Font size scaling uses a CSS custom property (`--fs`) applied via `calc()` across all font-size declarations
- Works offline on phone, tablet, or desktop
- Tested in Chrome, Firefox, and Safari

---

## 👨‍💻 Built with

- HTML5 + vanilla JavaScript
- CSS custom properties for theming and font scaling
- Google Fonts: Tiro Devanagari Hindi (headings), DM Sans (body), DM Mono (labels)
- Exercise references: [Muscle & Strength](https://www.muscleandstrength.com/exercises)

---

*Made with care for Ama's health journey 🌿*

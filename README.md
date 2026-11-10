# Caffeine clock: when should your last coffee be?

**Live:** https://cranefomo.github.io/caffeine

Drag your drinks across the day and see how much caffeine is still in you at bedtime, and the latest time you can have your last cup.

## What it does

- Dot chart of caffeine in your body across 24 hours
- Drag drinks on the timeline, drag the BED line
- Espresso, americano, filter coffee, energy drink, black tea, cola
- Tells you "last americano by 2:15 PM" or "over the line even without this one"
- Fast / average / slow metabolism (3h, 5h, 8h half-life)
- 12h or 24h time
- Share link keeps your exact day: `#americano@8,espresso@11&bed=23&h=5`
- One HTML file, works offline, no tracking, nothing sent anywhere

## Numbers used

| Drink | Serving | Caffeine |
|---|---|---|
| Espresso | 1 shot | 63 mg |
| Americano | 2 shots | 126 mg |
| Filter coffee | 240 ml | 96 mg |
| Energy drink | 250 ml can | 80 mg |
| Black tea | 240 ml | 47 mg |
| Cola | 330 ml can | 32 mg |

Model: each drink is absorbed in about 45 minutes, then cleared with first-order elimination at your half-life (average 5 hours, range 1.5 to 9.5).

The 50 mg line is a rule of thumb, not a medical limit.

## Honest limits

- Real caffeine content varies a lot by brand, size and barista.
- Half-life depends on genetics, smoking, the pill, pregnancy, age and some medicines.
- Not medical advice.

## Sources

- [Mayo Clinic: caffeine content for coffee, tea, soda and more](https://www.mayoclinic.org/healthy-lifestyle/nutrition-and-healthy-eating/in-depth/caffeine/art-20049372)
- [NCBI: caffeine half-life about 5 hours, range 1.5 to 9.5](https://www.ncbi.nlm.nih.gov/books/NBK223808/)

Made by [@Cranefomo](https://x.com/Cranefomo).

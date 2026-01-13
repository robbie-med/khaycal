# Khaycal Shift Intake Calculator

A single-page, offline calculator for inpatient pediatrics.

**Use case:** EMRs often report PO intake as **total mL over a shift**. This tool converts that to:
- **Total kcal over shift**
- **kcal/kg over shift**
- **Extrapolated kcal/kg/day**
- Comparison vs a selectable **kcal/kg/day goal**

Default assumes **human milk ~ 20 kcal/oz ≈ 0.67 kcal/mL**, with options for higher caloric densities.

## Deploy on GitHub Pages
1. Create a new repo (public is easiest).
2. Add `index.html` and this `README.md` to the repo root.
3. Go to **Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: `main` and folder `/root`
6. Save. Your site URL will appear there.

## Clinical notes
- Broad caloric targets are heuristics; interpret with the patient’s course, weight trend, UOP, losses, and labs.
- No analytics. No storage. No PHI.

## License
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Hi, I'm Victoria 🩶

**Software Engineering @ University of Waterloo** · ML × medical imaging

### Featured project
**[Cardiac MRI Segmentation](https://github.com/VICSTIC08/cardiac-mri-segmentation)** · PyTorch, NumPy, SciPy, pytest, GitHub Actions
- End-to-end pipeline that turns cardiac MRI into the measurements cardiologists use: ejection fraction, ventricular volumes, myocardial mass
- 8.2M-parameter residual attention U-Net trained on the public ACDC dataset (150 patients, 5 diagnosis groups)
- **Dice 0.94 / 0.91 / 0.90** (LV / RV / myocardium) on 50 held-out patients, within 0.02 of the 2017 ACDC challenge winner
- LV ejection fraction mean error **2.5 points** vs. expert annotations (r = 0.988)
- 5-model ablation: residual blocks and attention gates (+439K parameters) gave no measurable gain; the Dice loss did (+0.01 RV Dice)
- 48 tests in CI, 23 merged pull requests, leakage-free patient-level splits, test set evaluated once
- v2 in progress: calibrated uncertainty, deep ensembles, out-of-distribution detection and a live demo

### Research
- **Radiology Research Intern, University of Calgary**: extended a U-Net to 3-class epicardial / pericardial fat segmentation on 400+ cardiac MRI scans (Dice 0.913); root-caused an augmentation bug for +0.03 Dice
- [**Integrating sharpness overlays and deep ensembles for uncertainty signaling in clinical AI**](https://doi.org/10.36227/techrxiv.176123594.47228957/v1): solo-authored TechRxiv preprint on calibration, deep ensembles and out-of-distribution detection (360 views, 128 downloads)
- [**Hepatitis A & HDL Cholesterol**](https://drive.google.com/file/d/1a6QpeDNEjbrXso0jkUWv0DvOnZLXj22u/view): first-author paper, Youreka Journal; regression on 4,855 NHANES participants in R (p = 0.010) · **regional champion, 3rd nationally** of ~90 teams and 400+ competitors
- [**Van't Hoff Analysis of Fe(SCN)²⁺**](https://drive.google.com/file/d/1urw00XIk9UmA2tFzgOnq71XoJEmjlHNf/view): ΔH° and ΔS° from a Van't Hoff fit across 9 temperatures (R² = 0.973) with full uncertainty propagation

### Also
- C++ PID control for VEX Robotics on an all-girls team; tripled autonomous score
- Only high schooler on Youreka Canada's national exec; led media across 7 cities (5,000+ followers, 200k+ views)
- Built a 21-client ski coaching business (CSIA Level 2, $4.5k+ revenue)
- RCM Level 8 Piano + Theory, First Class Honours with Distinction

### my free time
gym · reading · photography · golf · sailing

**Languages:** Python · C · C++ · R · MATLAB  
**LinkedIn:** [linkedin.com/in/vicstic](https://linkedin.com/in/vicstic)

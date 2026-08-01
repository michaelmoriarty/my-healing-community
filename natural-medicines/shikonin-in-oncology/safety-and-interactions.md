---
description: >-
  Shikonin safety profile, liver biology, CYP450 interaction evidence,
  endocrine-treatment questions, and key interaction limits in oncology use.
---

# Safety & Interactions

### General Safety Signal <a href="#general-safety-signal" id="general-safety-signal"></a>

Shikonin has shown preferential toxicity toward cancer cells over normal cells in several cell culture systems. In ER-positive breast cancer models, antiproliferative effects were not reproduced in normal human mammary epithelial cells at comparable concentrations. That selectivity is a helpful signal.

It is not a human safety database.

Acute oral toxicity data in animals suggests a relatively high LD50 — greater than 1 g/kg orally in mice — with no behavioural changes, toxic signs, or mortality observed at doses up to 20 mg/kg. That is a useful baseline. It does not address chronic dosing, combinations with active treatment, or the specific vulnerabilities of people undergoing chemotherapy or hormonal therapy.

One important caveat from the female reproductive cancer literature: in ovarian cancer models, shikonin showed toxicity not only to cancer cells but also to lymphocytes, normal ovarian cells, and endothelial cells. This is one reason targeted nanoparticle formulations are being developed — to confine cytotoxic activity to tumour tissue. It is also a reminder that preclinical selectivity findings are not universal across cancer contexts.

***

### Liver — A More Nuanced Picture Than "Caution" <a href="#liver--a-more-nuanced-picture-than-caution" id="liver--a-more-nuanced-picture-than-caution"></a>

The liver story for shikonin is genuinely complex and deserves more than a simple caution flag.

**The hepatoprotective side.**\
Multiple preclinical studies show shikonin _protecting_ liver tissue under specific injury conditions:

* In acetaminophen (paracetamol) overdose models, shikonin attenuated acute liver injury by reducing reactive oxygen species and suppressing inflammatory cytokines — including TNF-α and IL-1β.
* In hepatic ischemia-reperfusion injury models, shikonin reduced serum AST and ALT levels, preserved liver architecture, and inhibited hepatocyte apoptosis and autophagy via PI3K/Akt activation.
* In autoimmune hepatitis models (concanavalin A-induced), shikonin significantly reduced liver injury and suppressed pro-inflammatory cytokine release via JNK pathway inhibition.

This is not what a simple hepatotoxin does.

**The hepatotoxicity concern.**\
The concern arises from shikonin's pro-oxidant capacity at higher concentrations — the same reactive oxygen species generation that drives its anticancer activity. Quinone compounds as a class can produce oxidative stress in hepatocytes when concentrations are sufficient. At anticancer-relevant concentrations, this capacity is targeted at tumour cells. Whether it remains selective at the concentrations achievable through oral supplementation — particularly with the new liposomal formulation — has not been established in humans.

The nuanced picture is this: at low-to-moderate doses, shikonin appears hepatoprotective in most preclinical models. At high concentrations or in the context of existing liver stress — such as from concurrent chemotherapy — the pro-oxidant mechanism that makes it interesting in oncology could become a liver burden. Anyone with pre-existing liver compromise, elevated liver enzymes from treatment, or heavy concurrent medication load should treat this as a genuine caution, not a theoretical one.

***

### CYP450 — This Is the Most Concrete Interaction Risk <a href="#cyp450--this-is-the-most-concrete-interaction-risk" id="cyp450--this-is-the-most-concrete-interaction-risk"></a>

This section contains the most clinically specific safety finding in the shikonin literature and it is not well known.

A 2017 study using human liver microsomes directly assessed shikonin's inhibitory effects across the major CYP450 enzymes. The findings were specific:

* Shikonin is a **mixed inhibitor of CYP1A2, CYP2B6, CYP2C9, CYP2D6, and CYP3A4** in human liver microsomes
* It is a **competitive inhibitor of CYP2E1**
* Ki values were **no more than 7.72 μM** across all enzymes — low enough to indicate meaningful inhibition potential at biologically relevant concentrations
* No time-dependent (irreversible) inhibition was found — the inhibition is reversible

The researchers concluded that the relatively low Ki values represent **a high risk potential for drug-drug or food-drug interactions** based on potent CYP enzyme inhibition.

A separate study on deoxyshikonin — a closely related natural derivative present in _Lithospermum erythrorhizon_ alongside shikonin — confirmed strong CYP2B6 inhibition with a Ki of 3.5 μM in human liver microsomes.

**Why this matters directly for the oncology patient:**

CYP3A4 metabolises a wide range of oncology drugs including:

* **Letrozole and anastrozole** (aromatase inhibitors)
* **Palbociclib, ribociclib, abemaciclib** (CDK4/6 inhibitors)
* **Tamoxifen** (partial CYP3A4 involvement)
* **Many chemotherapy agents**

CYP2D6 is the primary enzyme that converts tamoxifen to its active metabolite endoxifen. Inhibition of CYP2D6 is exactly how drugs like fluoxetine reduce tamoxifen efficacy in clinical practice.

If shikonin inhibits CYP3A4 and CYP2D6 at achievable concentrations, it could raise plasma levels of co-administered drugs unpredictably, or — in tamoxifen's case — reduce conversion to the active metabolite. Neither scenario has been studied in humans. But the in vitro signal is concrete enough that it cannot be dismissed.

This is the most important interaction concern in the entire safety profile — more specific and better evidenced than the hepatotoxicity question.

{% include "../../.gitbook/includes/interpreting-drug-interaction-evidence.md" %}

***

### GABA-A and Sedative Medications <a href="#gaba-a-and-sedative-medications" id="gaba-a-and-sedative-medications"></a>

As covered in the Mental & Emotional Wellbeing section, shikonin shows strong binding affinity for GABA-A receptors in molecular docking studies and enhanced diazepam-induced sleep duration in animal models.

For anyone taking benzodiazepines, Z-drugs (zolpidem, zopiclone), gabapentin, pregabalin, or other GABAergic agents, this represents a direct and biologically plausible interaction risk — excessive sedation. The evidence is preclinical. The mechanism is specific enough to warrant disclosure to a prescribing clinician.

***

### Endocrine Therapy Interactions <a href="#endocrine-therapy-interactions" id="endocrine-therapy-interactions"></a>

The breast cancer literature makes this area especially important.

Shikonin engages ERα degradation, GPER suppression, and steroid sulfatase inhibition simultaneously with any endocrine therapy a patient may be taking. Mechanistically, several of these effects are additive to standard therapies rather than opposing them. But:

* No human drug-interaction studies exist for any endocrine therapy combination
* CYP3A4 and CYP2D6 inhibition (see above) is the most concrete pharmacokinetic concern for letrozole, anastrozole, and tamoxifen users
* The ESR1 mutation selection pressure question — whether sustained ERα degradation could accelerate resistance mutation emergence — remains unanswered (see the dedicated note in the Estrogen Receptor Mechanisms page)
* CDK4/6 inhibitor metabolism via CYP3A4 creates a direct interaction concern if CYP3A4 is meaningfully inhibited

None of these are proven harms. All of them are unstudied interactions in humans carrying real mechanistic plausibility.

***

### Chemotherapy Combinations <a href="#chemotherapy-combinations" id="chemotherapy-combinations"></a>

Preclinical synergy has been reported with cisplatin and doxorubicin. That is mechanistically encouraging.

It does not address whole-body safety, cumulative liver burden, or treatment-timing questions in humans. Doxorubicin is itself hepatotoxic and cardiotoxic at cumulative doses. Whether shikonin's pro-oxidant capacity adds to that burden or — as in the acetaminophen liver models — actually reduces oxidative injury, is not established in this context.

***

### What Remains Unknown <a href="#what-remains-unknown" id="what-remains-unknown"></a>

* Whether CYP3A4 and CYP2D6 inhibition observed in human liver microsomes translates to clinically meaningful drug level changes at achievable oral doses
* Whether liposomal formulation changes the CYP interaction profile by altering absorption kinetics
* Long-term safety of ERα degradation alongside active endocrine therapy
* Whether the hepatoprotective effects seen in inflammation and injury models translate to the high-oxidative-stress environment created by concurrent chemotherapy
* Transporter effects (P-glycoprotein, BCRP) — not yet well mapped
* Safety in patients with pre-existing liver impairment from prior chemotherapy

***

### Bottom Line <a href="#bottom-line" id="bottom-line"></a>

Shikonin is not a compound with a simple safety flag. The liver picture is more complex than "caution" — it shows both hepatoprotective and potentially pro-oxidant characteristics depending on dose and context.

The CYP450 data is the most concrete and actionable safety finding: in vitro evidence of mixed inhibition across CYP1A2, CYP2B6, CYP2C9, CYP2D6, and CYP3A4 at low Ki values in human liver microsomes. For anyone on drugs metabolised by these enzymes — which includes most standard oncology regimens — this signal deserves clinical attention, not dismissal.

Traditional use of _Lithospermum_ preparations does not validate the doses, concentrations, or formulations relevant to oncology discussions. The two contexts are not comparable.

***

_This information is for education only. It is not medical advice, diagnosis, or treatment. Please speak with a qualified clinician before making changes to care, medication, or supplement use._

***

### References <a href="#references" id="references"></a>

Ahmad F et al. (2024). Shikonin in breast cancer treatment: a comprehensive review — safety discussion.\
[https://academic.oup.com/jpp/article/76/8/967/7656703](https://academic.oup.com/jpp/article/76/8/967/7656703)

Han X et al. (2010). Selective toxicity toward ERα+ cancer cells versus normal mammary cells.\
[https://pubmed.ncbi.nlm.nih.gov/19760501/](https://pubmed.ncbi.nlm.nih.gov/19760501/)

Zhang L et al. (2020). Shikonin and 4-hydroxytamoxifen — combination context and interaction considerations.\
[https://www.springermedizin.de/shikonin-and-4-hydroxytamoxifen-synergistically-inhibit-the-prol/17786520](https://www.springermedizin.de/shikonin-and-4-hydroxytamoxifen-synergistically-inhibit-the-prol/17786520)

Pharmacological properties and derivatives of shikonin — toxicity literature review. _Pharmacological Research_ (2019).\
[https://www.sciencedirect.com/science/article/abs/pii/S1043661819313167](https://www.sciencedirect.com/science/article/abs/pii/S1043661819313167)

Liu Y et al. (2017). Assessment of the inhibition risk of shikonin on cytochrome P450 via cocktail inhibition assay in human and rat liver microsomes.\
[https://pubmed.ncbi.nlm.nih.gov/28941798/](https://pubmed.ncbi.nlm.nih.gov/28941798/)

Zhao Y et al. (2020). Deoxyshikonin reversibly inhibits cytochrome P450 2B6 — CYP interaction data for closely related compound.\
[https://onlinelibrary.wiley.com/doi/abs/10.1002/bdd.2230](https://onlinelibrary.wiley.com/doi/abs/10.1002/bdd.2230)

Shikonin enhances hypnotic effect and synergistic properties of diazepam — acute toxicity data and GABA-A interaction.\
[https://www.sciencedirect.com/article/abs/pii/S1876382025000605](https://www.sciencedirect.com/article/abs/pii/S1876382025000605)

Wang J et al. (2019). Shikonin attenuates acetaminophen-induced acute liver injury via inhibiting oxidative stress and inflammatory responses.\
[https://pubmed.ncbi.nlm.nih.gov/30818140/](https://pubmed.ncbi.nlm.nih.gov/30818140/)

Chen Z et al. (2017). Protective effects of shikonin on hepatic ischemia-reperfusion injury via PI3K/Akt signalling. _Scientific Reports._\
[https://www.nature.com/articles/srep44785](https://www.nature.com/articles/srep44785)

Frontiers in Pharmacology (2025). Shikonin in female reproductive cancers — normal cell toxicity and nanoparticle targeting context.\
[https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1627124/full](https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1627124/full)

{% hint style="warning" %}
This information is for education only. It is not medical advice, diagnosis, or treatment. Please speak with a qualified clinician before making changes to care, medication, or supplement use.
{% endhint %}

{% hint style="info" %}
© 2026 Abbey Mitchell. All rights reserved. Please share by URL rather than copying page text.
{% endhint %}

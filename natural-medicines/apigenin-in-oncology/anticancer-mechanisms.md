---
description: >-
  The main mechanistic routes through which apigenin shows anticancer activity
  in preclinical models.
---

# Anticancer Mechanisms

## Anticancer Mechanisms

Apigenin’s anticancer biology is broad rather than single-target. The mechanisms below are the most repeated, cross-tumour-relevant, and clinically meaningful across the literature.

### 1. BCL-2 family modulation — MCL-1 and BCL-xL

This is the mechanism with the clearest place in resistance biology.

BCL-2 family proteins such as `BCL-2`, `BCL-xL`, and `MCL-1` act as anti-apoptotic gatekeepers. Overexpression is one of the common ways cancer cells survive treatment stress and resist chemotherapy. `MCL-1` matters especially because it often becomes the final escape protein when `BCL-2` and `BCL-xL` are already under pressure.

Apigenin suppresses both `BCL-xL` and `MCL-1` by inhibiting `STAT3` phosphorylation, which normally supports their expression. When `STAT3` falls, `BCL-xL` and `MCL-1` fall with it. That shifts the balance toward pro-apoptotic proteins such as `BAX` and `BAK`, promotes mitochondrial permeabilisation, and activates caspases.

This has been shown in colon cancer, ovarian cancer, and other models. It is directly relevant to therapy-resistant states.

In the context of a layered [Senolytic Pulse Protocol](../../senolytic-pulse-protocol.md), this mechanism matters because residual stressed or senescent-like cells can shift toward `MCL-1` dependence after earlier pressure on `BCL-xL` and `BCL-2`. Apigenin’s `STAT3`-linked pressure on `MCL-1` is designed to close that escape route.

This is not human-proven. It is, however, one of the clearest mechanistic rationales in the flavone literature.

### 2. STAT3 and NF-κB suppression

`STAT3` and `NF-κB` are master regulators of survival, inflammation, and immune evasion. Both are frequently constitutively active in cancer.

Apigenin suppresses phosphorylation of both pathways in multiple cancer models. That reduces downstream targets including BCL-2 family proteins, `COX-2`, `VEGF`, and pro-inflammatory cytokines. In colitis-associated colon cancer models, apigenin reduced phosphorylation of both `NF-κB` and `STAT3` in tumour tissue.

This dual suppression links the direct anticancer signal to the broader inflammatory and senescence-related terrain. For the wider senescence context, see [Senescence — The Second Escape Route](../../treatment-resistance/treatment-resistance/senescence-the-second-escape-route/).

### 3. PI3K/AKT/mTOR pathway inhibition

The `PI3K/AKT/mTOR` pathway regulates growth, survival, and metabolic activity. Constitutive activation is common in many cancers and strongly linked to treatment resistance.

Apigenin inhibits `PI3K/AKT` signalling, which can suppress `mTOR`, reduce pro-survival gene expression, and trigger apoptosis or autophagy depending on context. In prostate cancer models, Akt inactivation caused dephosphorylation of BAD, releasing a normally restrained pro-apoptotic signal and driving apoptosis. This effect was confirmed both in vitro and in xenograft models.

### 4. NRF2 / Redox Dual Action

#### What NRF2 is and why it matters here

`NRF2` (`nuclear factor erythroid 2-related factor 2`) is the cell’s master switch for antioxidant defence. Under oxidative stress, `NRF2` detaches from its inhibitor `KEAP1`, moves into the nucleus, and activates the antioxidant response element (`ARE`). That switches on a battery of protective enzymes including `HO-1`, `NQO1`, and glutamate-cysteine ligase. The result is lower ROS, less lipid peroxidation, and better cell survival under stress.

In healthy tissue, that is desirable. In established cancer, it can become a problem. Constitutively overactive `NRF2` is now well documented as a driver of tumour progression, metabolic reprogramming, cancer stem-cell self-renewal, drug efflux, and chemoresistance across multiple tumour types including lung, liver, and pancreatic cancer.

This is the core double-edged nature of `NRF2` in oncology. It can protect normal tissue, while also supporting tumour survival and resistance in the wrong context.

#### Where apigenin activates NRF2

In non-cancer and normal-tissue models, apigenin consistently **activates** the `NRF2-ARE` axis.

* In retinal pigment epithelial `ARPE-19` cells, apigenin at `200–400 µM` significantly increased `NRF2` nuclear translocation and raised `HO-1`, `NQO1`, and `GCLM` at both mRNA and protein level. These effects were abolished when `NRF2` was silenced with `siRNA`, confirming `NRF2` as the essential pathway rather than a bystander.
* In rat liver exposed to cyclophosphamide, apigenin protected liver tissue by upregulating `NRF2` and `HO-1`, reducing ROS, `MDA`, and inflammatory cytokines, and decreasing treatment-induced DNA damage and apoptosis in normal hepatocytes.
* In mouse skin epidermal cells, apigenin reactivated `NRF2` signalling that had been silenced by epigenetic DNA methylation changes, restoring antioxidant defence through `CpG` demethylation at the `NRF2` promoter.
* In metabolic disease models including high-fructose and `NAFLD` settings, apigenin promoted `NRF2` nuclear accumulation and increased `HO-1` and `NQO1` expression, reducing oxidative and inflammatory organ damage.

The practical implication is clear. In normal tissue under chemical, metabolic, or treatment-related stress, apigenin tends to reinforce antioxidant capacity.

#### Where apigenin suppresses NRF2

In cancer cells where `NRF2` is constitutively overactive and driving chemoresistance, apigenin can behave differently and act as an **NRF2 suppressor**.

* In doxorubicin-resistant hepatocellular carcinoma `BEL-7402/ADM` cells, a non-toxic dose of apigenin reduced `NRF2` expression at both mRNA and protein level by downregulating the `PI3K/Akt` pathway, which normally stabilises `NRF2` and protects it from degradation. The downstream effect was lower expression of `NRF2`-regulated drug-efflux genes and detoxification enzymes, with significantly higher intracellular doxorubicin accumulation.
* In a xenograft model from the same line of work, apigenin plus doxorubicin inhibited tumour growth, reduced proliferation, and increased apoptosis more than doxorubicin alone. This remains one of the most mechanistically direct chemosensitisation papers in the apigenin literature.
* Separate review-level evidence also places apigenin alongside luteolin and brusatol as a natural `NRF2` inhibitor in `NRF2`-addicted tumours, especially where constitutive activation is driven by `KEAP1` or `NRF2` mutation rather than external stress.

#### The ferroptosis intersection

`NRF2` is also a central gatekeeper of ferroptosis. By upregulating `GPX4` and `SLC7A11`, constitutively active `NRF2` helps cancer cells suppress lipid peroxidation and resist ferroptotic death.

In cancer cells that depend on `NRF2` for ferroptosis resistance, apigenin’s ability to suppress `NRF2` through `PI3K/Akt` could lower the ferroptosis threshold and increase vulnerability to ferroptosis-directed co-interventions. At present, this remains a mechanistic connection rather than a fully characterised combined effect in a single published cancer model, but it is biologically coherent and worth tracking.

{% hint style="info" %}
#### NRF2: friend or foe in cancer — a short explainer

**NRF2 as friend — early or preventive context**\
When cells are under stress but have not yet become cancerous, `NRF2` works protectively. It clears ROS before they can damage DNA, reduces chronic inflammation that can support tumour initiation, and helps normal cells withstand treatment-related toxicity. In this setting, supporting `NRF2` activity is broadly favourable.

**NRF2 as foe — established cancer context**\
In many established cancers, `NRF2` becomes locked into persistent activation, either through `KEAP1` loss, direct `NRF2` alteration, or oncogenic signalling from pathways such as `KRAS` and `MYC`. In that state, `NRF2` does the same jobs it always did, but now in service of the tumour. It clears the ROS that therapy is trying to exploit, supports efflux transporters, preserves metabolic flexibility, and helps cancer cells resist apoptosis.

**Why apigenin’s dual action matters**\
The key question is not whether apigenin activates or inhibits `NRF2`, but in what context. Current evidence suggests activation in normal and metabolically stressed tissue, and suppression in at least some `NRF2`-addicted cancer models. Whether that tissue selectivity is consistent across tumour types, and how it behaves in humans using liposomal apigenin during active treatment, remains unknown.
{% endhint %}

### 5. Cell-cycle arrest at G2/M

Apigenin repeatedly arrests cancer cells in the `G2/M` phase of the cell cycle. That has been documented across colorectal, prostate, melanoma, and other cell lines.

The mechanism involves downregulation of cyclin `B1` and `CDK1`, plus upregulation of the CDK inhibitor `p21`. Cell-cycle arrest is often paired with p53 stabilisation and pro-apoptotic signalling.

### 6. Anti-metastatic effects

A systematic review of six animal studies found statistically significant reductions in metastatic nodule counts across melanoma, ovarian, liver, prostate, and intestinal cancer models.

Mechanisms include:

* suppression of epithelial-mesenchymal transition through higher `E-cadherin` and lower `vimentin`, `N-cadherin`, `Snail`, and `Slug`
* inhibition of `MMP2` and `MMP9`, which degrade extracellular matrix and support invasion
* anti-angiogenic effects through suppression of `VEGF`, `SPOCK1`, and `VCAM-1`

### 7. Tumour metabolism — PKM2 and glycolysis

`PKM2` is a metabolic enzyme heavily used by glycolytic tumour cells, especially in colorectal cancer. Apigenin suppresses `PKM2` at both mRNA and protein level by blocking the `β-catenin/c-Myc/PTBP1` axis.

That interferes with the metabolic advantage of highly glycolytic tumours and adds a distinct non-apoptotic pressure point.

### 8. Ferroptosis

Apigenin also has emerging evidence as a ferroptosis-modulating compound. That adds a third regulated cell-death route beyond apoptosis and autophagy.

In human endometrial carcinoma Ishikawa cells, apigenin increased iron-dependent lipid peroxidation, depleted antioxidant defences, and triggered ferroptotic cell death in vitro, with matching tumour-growth inhibition in vivo. Ferroptosis inhibitors blunted the effect, confirming that ferroptosis was involved.

In multiple myeloma `NCI-H929` cells, apigenin induced a mixed death response involving apoptosis, autophagy, and ferroptosis, again with clear ROS and lipid-peroxidation signatures and sensitivity to ferroptosis blockade.

That multiple-myeloma signal was also supported by work showing direct cytotoxicity against myeloma cell lines and primary myeloma cells, with the associated mechanisms extending beyond apoptosis alone.

These data are early and still cell-line-centred. They nevertheless suggest that apigenin can, under the right conditions, push iron-rich and oxidatively stressed cancer cells into ferroptosis rather than relying only on classic mitochondrial apoptosis.

### References

* Erdogan S, et al. [Apigenin induces apoptosis by suppressing Bcl-xl and Mcl-1 simultaneously via STAT3 signalling in colon cancer](https://www.spandidos-publications.com/10.3892/ijo.2018.4308)
* Patel D, et al. [Apigenin inhibits colonic inflammation and tumorigenesis by suppressing STAT3/NF-κB](https://www.oncotarget.com/article/22145/text/)
* Seo HS, et al. [Inhibition of PI3K/Akt/mTOR pathway by apigenin induces apoptosis and autophagy](https://www.sciencedirect.com/article/pii/S0753332217363199)
* Shukla S and Gupta S. [Plant flavonoid apigenin inactivates Akt to trigger apoptosis in human prostate cancer: an in vitro and in vivo study](https://pmc.ncbi.nlm.nih.gov/articles/PMC2577719/)
* Gao AM, et al. [Apigenin sensitizes doxorubicin-resistant hepatocellular carcinoma BEL-7402/ADM cells to doxorubicin via inhibiting PI3K/Akt/Nrf2 pathway](https://academic.oup.com/carcin/article/34/8/1806/2463104)
* Xu X, et al. [Apigenin attenuates oxidative injury in ARPE-19 cells through activation of the Nrf2 pathway](https://onlinelibrary.wiley.com/doi/10.1155/2016/4378461)
* Elsawy H, et al. [Upregulation of Nrf2/HO-1 signalling and attenuation of oxidative stress, inflammation, and cell death mediates the protective effect of apigenin against cyclophosphamide hepatotoxicity](https://pmc.ncbi.nlm.nih.gov/articles/PMC9322057/)
* Li W, et al. [Regulation of Nrf2/ARE pathway by dietary flavonoids](https://pmc.ncbi.nlm.nih.gov/articles/PMC7600646/)
* Zhou H, et al. [Natural Nrf2 inhibitors: a review of their potential for cancer treatment](https://www.ijbs.com/v19p3029.htm)
* Wu KC, et al. [Nrf2 in cancers: a double-edged sword](https://onlinelibrary.wiley.com/doi/10.1002/cam4.2101)
* Sang S, et al. [Apigenin reactivates Nrf2 anti-oxidative stress signalling in mouse skin epidermal JB6 P+ cells via epigenetic modifications](https://pubmed.ncbi.nlm.nih.gov/24830944/)
* Chong CM, et al. [Experimental evidence for anti-metastatic actions of apigenin: a mini-review](https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2024.1380194/full)
* Xuan Y, et al. [Apigenin, a natural flavonoid, promotes autophagy and ferroptosis in human endometrial carcinoma Ishikawa cells in vitro and in vivo](https://www.sciencedirect.com/science/article/pii/S2213453023000964)
* Liu H, et al. [Ferroptosis: opportunities and challenges in treating endometrial cancer](https://www.frontiersin.org/journals/molecular-biosciences/articles/10.3389/fmolb.2022.929832/full)
* Fan R, et al. [Cytotoxicity of apigenin toward multiple myeloma cell lines and primary myeloma cells and the associated mechanisms](https://pubmed.ncbi.nlm.nih.gov/33070080/)

# TP53 Mutation Types Reference

This page is the practical decoder for TP53 variant notation and mutation class.

The key idea is simple:

**A TP53 mutation is not one thing.**

The mutation type tells you whether:

* a harmful mutant protein is accumulating
* some p53 function remains
* p53 is absent altogether
* a mutation-specific strategy has any logical target

### Start with the notation

Most reports use one or both of these formats:

* **protein notation** such as p.R175H, p.R248Q, p.P128fs, or p.R213\*
* **DNA notation** such as c.524G>A or splice-site notations like c.375+1G>T

The protein notation is usually the fastest practical clue.

### The main somatic mutation buckets

#### Hotspot missense gain-of-function mutations

Examples:

* p.R175H
* p.R248Q
* p.R248W
* p.R273H
* p.G245S
* p.R249S
* p.R282W

These usually produce a **stable full-length mutant protein**.

That matters because the problem is not just loss of tumour suppression. The mutant protein can actively promote tumour survival, invasion, metabolic rewiring, or treatment resistance.

This is the main setting where the logic of [Andrographis and Mutant p53](../andrographis-and-mutant-p53.md) becomes relevant.

#### Missense partial-loss mutations

These still produce a protein, but some residual p53 activity may remain.

They sit in an in-between zone:

* not clearly wild-type
* not clearly null
* sometimes still biologically salvageable in theory

This is where careful interpretation matters most.

#### Missense non-functional mutations

These still make protein, but the protein is essentially inactive.

There may be no meaningful gain-of-function effect, but there is also no reliable tumour-suppressor effect left.

#### Frameshift mutations

Examples look like:

* p.P128fs
* p.R196fs\*

These usually create a garbled downstream sequence and then a truncated unstable protein.

In practice, this often behaves like a **null** state:

* little or no useful p53 protein
* no stable target to clear
* mutant-protein-degradation strategies become much less relevant

#### Nonsense or stop-codon mutations

Examples look like:

* p.R213\*
* p.Q167\*

These create a premature stop signal.

Again, this usually behaves like a **null** state rather than a stable mutant-protein state.

#### Splice-site mutations

Examples often look like:

* c.\[number]+1
* c.\[number]+2
* c.\[number]-1

These disrupt RNA splicing and often result in truncated or absent protein.

Many behave functionally like null variants, but some need case-by-case interpretation.

#### Silent or synonymous changes

These do not change the amino acid directly.

Most are clinically unimportant, but some affect splicing or expression and should not be dismissed automatically without proper interpretation.

### The practical shortcut

If a report shows:

* p.R175H, p.R248Q, p.R248W, p.R273H, p.G245S, p.R249S, p.R282W\
  think **stable hotspot mutant protein**
* fs or fs\*\
  think **frameshift / usually null**
* \*\
  think **nonsense / stop / usually null**
* +1, +2, -1, -2 near a coding boundary\
  think **splice-site disruption**

That shortcut is not a substitute for full interpretation, but it is often enough to sort the major bucket quickly.

{% hint style="info" %}
Include the exact TP53 variant if you have it.
{% endhint %}

### Key references

Targeting p53 pathways: mechanisms, structures and advances in therapy\
[https://www.nature.com/articles/s41392-023-01347-1](https://www.nature.com/articles/s41392-023-01347-1)

Natural products targeting the p53-MDM2 pathway and mutant p53\
[https://pmc.ncbi.nlm.nih.gov/articles/PMC6176154/](https://pmc.ncbi.nlm.nih.gov/articles/PMC6176154/)

{% include "../../../.gitbook/includes/site-wide-medical-disclaimer.md" %}

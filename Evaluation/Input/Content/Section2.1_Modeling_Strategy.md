The general workflow for building an adult PBPK model has been described by Kuepfer et al. ([Kuepfer 2016](# 5 References)). Relevant information on the anthropometry (height, weight) was gathered from the respective clinical study, if reported. Information on physiological parameters (e.g. blood flows, organ volumes, hematocrit) in adults was gathered from the literature and has been incorporated in PK-Sim<sup>®</sup>) as described previously ([Willmann 2007](# 5 References)). The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available 'PK-Sim<sup>®</sup> Ontogeny Database Version 7.3' ([PK-Sim Ontogeny Database Version 7.3](# 5 References)).

The PBPK model was developed based on clinical data of healthy, non-obese, adult subjects obtained from the literature, covering different single doses of alprazolam administered intravenously or orally as immediate release tablet in the fasted state. Mass balance information on urinary excretion of unchanged <sup>14</sup>C-alprazolam after PO administration was also accounted for during the model building process.

Unknown parameters were simultaneously optimized using all available PK data, in particular:

-  10 data sets following single IV administration of 6 different doses of alprazolam (0.25 mg, 0.5 mg, 1 mg, 1.576 mg, 2 mg, 4 mg)
- 16 data sets following single PO administration of 3 different doses of alprazolam as immediate release tablet and <sup>14</sup>C-alprazolam (0.5 mg, 1 mg, 2 mg)

Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility. The following parameters were identified using the Parameter Identification module provided in PK-Sim<sup>®</sup> and MoBi<sup>®</sup> ([Open Systems Pharmacology Documentation](# 5 References)):

- `Dissolution time (50% dissolved)`
- `Dissolution shape`
- `Specific intestinal permeability`
- `Mucosa permeability (interstitial<->intracellular)`
- `Lipophilicity`
- `Metabolizing Enzyme - CYP3A4 - kact`
- `GFR fraction`

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#2.2	Data).

Details about the structural model and its parameters can be found in [Section 2.3](#2.3 Model Parameters and Assumptions).






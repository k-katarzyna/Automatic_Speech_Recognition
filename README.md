## Project Goal

The goal of this project was to create an LSTM-based speech-to-text model using the [Common Voice dataset for the English language](https://commonvoice.mozilla.org/en/datasets). The models were trained on selected groups of accents, with an additional aim of examining how the model learns different accents and whether this depends on the amount of available data for a given accent or on the specificity of the accent itself.

To investigate this, three setups were used:
- One model trained only on data labeled with the **“USA”** accent.
- Another model trained on six different accent groups (balanced dataset with equal data per accent).
- A third model trained on 17 accent groups with varying amounts of data.

## Findings

The model trained exclusively on the **“USA”** accent learned more easily than when trained on mixed accents, and it also performed well on the **“Canada”** accent.  
Results from the mixed-accent models indicate that while the amount of data matters, the characteristics of the accent are even more important.

The easiest groups to learn were:
- *Non-native speaker, German English*
- *Northern Irish*
- and, relatively well, *Canada*

The most challenging group was:
- *India and South Asia (India, Pakistan, Sri Lanka)*

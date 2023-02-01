# Privacy Preserving analytics over Duchenne patient registries

Click the button below to launch an intereactive session in Jupyter.  To run code in the Jupyter environment, put your cursor into the code box and press CTRL-enter (or click the "play" button at the top of the page)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/markwilkinson/Duchenne-daru/HEAD)

This contains several demonstrations (in the "binder" folder):

* Counting_Case_demo.ipynb - a demonstration of the "counting case":  How many patients with a given diagnosis are present in this registry?
* Phenotype_frequencies_demo.ipynb - How many times does a particular phenotype appear in a registry (multiple appearances in the same patient is counted as a single observation)
* KPI_Time_To_Diagnosis_demo.ipynb - Analytics, measuring the Key Performance Indicator of "time to diagnosis"; that is, the offset between when symptoms are first detected, and when the diagnosis occurrs.  This is an example of privacy-preserving analytics through its exposure of only aggregated, non-personal data.

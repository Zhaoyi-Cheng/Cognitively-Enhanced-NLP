# Cognitively-Enhanced-NLP
Do the correlations between the model and human attention differ in a multilingual model depending on the language input?

–Choose an ET dataset with two different languages, e.g., GECO English and GECO Dutch

–Choose a multilingual pre-trained LM, e.g., multilingual BERT

–Pipe the sentences from both ET datasets through the model, extract first and last-layer attention scores, aggregate over attention heads and compute the correlation between the CLS query and human attention

–Is there a difference between the languages?

Dataset
English Dataset: https://expsy.ugent.be/downloads/geco/
Chinese Dataset: https://osf.io/pmvhd/?view_only=77def2827a514254957cc846e14826cf
Model
BERT Multilingual Model
Baseline: BERT Chinese-only Model
Baseline: BERT English-only Base

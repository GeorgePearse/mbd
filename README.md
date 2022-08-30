# embd

<img width="135" alt="image" src="https://user-images.githubusercontent.com/47161914/187463225-da415263-67b0-474e-afc9-14c50ca565b7.png">

embd = embedded (pronounced Emm Bee Dee). Might drop the E

Like koaning/bulk but with built in functionality provided by Quaternion for similarity model finetuning

POC. Lightweight UI for interactive labelling similarity tuning of NLP models (maybe image eventually). None of this code exists yet. Hopefully will get it done in the next few weeks. 

UI, probably just Streamlit, may try javascript.

Any old-fashioned data storage in SQLite (or CSV), implement both and provide an option.

Can pluck this streamlit component out for the labelling of sentences (or larger chunks of text). You want to be able to save, and append to a list of classes. With both a YES option, and a NO option, for any given class? -> Only matters if you wanted to include the positive and negative set-up of QDrant.
https://github.com/ash2shukla/streamlit-bokeh-events.

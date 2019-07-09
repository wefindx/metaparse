# metaparse

This is to be a machine learning project to extract metainformation about information sources, such as agents online that share information.

## Problem specification

Given some data from an information source `I`, recognize its [intent about content](https://wefindx.net) towards the world, answering following questions about the information source and its information content:

- `F(domain).assets`:
- `.Agent` (who?)
- `.Place` (where?)
- `.Event` (when?)
- `.Topic` (about what?)
- `X(process).actions`:
- . `doing` (doing what?)
- `Y(range).targets`:
- `.Goal` (why?)
- `.Idea` (how in principle?)
- `.Plan` (what specifically?)
- `.Step` (in what order?)

This will allow to treat every information source as an instance of equation optimization process `F(X)=Y`, where the actions of agents are explained by their `intents (Y)` about content their world  `model (F)`.

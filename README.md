# context
context detection machine


## Detection & Labelling

- JSON Tree analysis
- Text context detection
- Layout Group of interest clustering
- Button detection
- List detection
- Layout detection
- Graphic element detection


## Button detection
**Method - CV Template matching (text removal postprocessing)**

after removing the text, template matching could give us better accuracy.


**Method - Tree Analysis (rule based)**

With givven ui json tree, we analyze the position, alignment, the content of the button label's text to check if it is in *Verb* form.


**Reflect Button Manipulation (Reverse Enginerring / ML)**

With Reflect's Button system spec definition, we generate millions of possible button form, Train it, and use them for existing design's button detection.


**Visibility Score (CV)**

The score of specific element, which looks like pressable. Color Visibility, EM level, and more.


**Context Score (NLP)**

Simple NLP and with ui text content classification, we can score the content is likey to be a button text.

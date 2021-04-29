# WBW
A cool text generation model

## Usage
### Loading Text
```python
from wbw import wbw
import nltk

nltk.download('punkt')

model = wbw.turn_to_model(wbw.finish('file.txt'))
wbw.save(moledo,'harrypotter.json')





```
### Generating Text
```python
words=['hi','my','name']

generation = wbw.generation(words,model,length = 20,prog=True)#length is how many words, prog is if you want to see the generation rather than just getting a value in return.
```

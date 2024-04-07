# Plagiarism Checker 📖

This repo consists of a source code of a Python script which detects plagiarism in a textual document using **cosine similarity**.


## How is it Done?

You might be wondering how plagiarism detection on textual data is done, well it ain't as complicated as you may think.

We all know that computers are good with numbers; so in order to compute the similarity between two text documents, the textual raw data is transformed into vectors => arrays of numbers and from that, we make use of basic knowledge of vectors to compute the similarity between them.

This repo contains a basic example on how to do that.


## Testing the plag. checker:

- Step 1: Clone this repo:
```
git clone https://github.com/optimizedLP/plagiarism_checker
```
- Step 2: Run dependencies:

```bash
pip3 install -r requirements.txt
```

- Step 3:

```bash
cd plagiarism_checker
```
```
python3 plagiarism.py
```


## Results:

```
('beta.txt', 'delta.txt', 0.5465972177348937)
('alpha.txt', 'delta.txt', 0.18643448370323357)
('alpha.txt', 'beta.txt', 0.14806887549598563)
```

## Misc.

This can also be done using ```pysimilar```.  

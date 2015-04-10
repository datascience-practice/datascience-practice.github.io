#Basic conditions
---

* Probability of picking a fair coin:
    p(f) = 0.9
* Probability of picking Heads given a loaded coin:
    p(h|l) = 0.9

* Probability of picking a loaded coin:
    p(l) = 0.1
    
* Probability of picking Heads given a fair coin:
    p(h|f) = 0.5

## Given outcome(sequence): 4H0T
---

* seq = 4H0T = HHHH

### Fair coin case:
---

* probability of the outcome, given a fair coin:
    p(seq|f) = p(h|f) ** 4 = 0.5**4
* combined probability of picking a fair coin AND getting the sequence:
    p(seq, f) = p(f) * p(seq|f)
    
### Loaded coin case:
---

* probability of the outcome, given a loaded coin:
    p(seq|l) = p(h|l) ** 4 = 0.5**4
* combined probability of picking a fair coin AND getting the sequence:
    p(seq, f) = p(f) * p(seq|f)


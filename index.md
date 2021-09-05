# Technical paper - ICSE 2022 - Supplementary data

## Empirical evaluation

### RQ1

> Many seeded faults behave quite similarly to real faults (high semantic similarity) while at the same time having low syntactical similarity to real faults. Perhaps surprisingly, we find no evidence suggesting any link between syntactic and semantic similarity, except from the cases of exact matches.

### Results - Cosine Coefficient
```
Class granularity level (PiTest - CodeBERT - DeepMutation - IBIR)
```

<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ1_cosine_class.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_cosine_class.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/DeepMutation/RQ1_cosine_class.png" width="160" title="DeepMutation"/>
  <img src="./data/plots/RQ1/IBIR/RQ1_cosine_class.png" width="160" title="IBIR"/>
</p>

```
Function granularity level (PiTest - CodeBERT - DeepMutation - IBIR)
```
<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ1_cosine_function.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_cosine_function.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/DeepMutation/RQ1_cosine_function.png" width="160" title="DeepMutation"/>
  <img src="./data/plots/RQ1/IBIR/RQ1_cosine_class.png" width="160" title="IBIR"/>
</p>

### Results - Jaccard Coefficient
```
Class granularity level (PiTest - CodeBERT - DeepMutation - IBIR)
```

<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ_jaccard_class.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_jaccard_class.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/DeepMutation/RQ1_jaccard_class.png" width="160" title="DeepMutation"/>
  <img src="./data/plots/RQ1/IBIR/RQ1_jaccard_class.png" width="160" title="IBIR"/>
</p>

```
Function granularity level (PiTest - CodeBERT - DeepMutation - IBIR)
```
<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ_jaccard_function.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_jaccard_function.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/DeepMutation/RQ1_jaccard_function.png" width="160" title="DeepMutation"/>
  <img src="./data/plots/RQ1/IBIR/RQ1_jaccard_class.png" width="160" title="IBIR"/>
</p>

  
### Discussion

> Sensitivity of mutants from the same location. Small syntactic changes lead to diverse semantic changes.

```
Changed lines location (PiTest - CodeBERT - IBIR)
```

<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ_jaccard_class.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_cosine_changed_lines.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/IBIR/RQ1_cosine_changed_lines.png" width="160" title="IBIR"/>
</p>

```
Random lines location (PiTest - CodeBERT - IBIR)
```

<p float="center">
  <img src="./data/plots/RQ1/PIT/RQ_jaccard_class.png" width="160" title="PiTest"/>
  <img src="./data/plots/RQ1/CodeBERT/RQ1_cosine_random_lines.png" width="160" title="CodeBERT"/> 
  <img src="./data/plots/RQ1/IBIR/RQ1_cosine_random_lines.png" width="160" title="IBIR"/>
</p>

### Link for rest of data

👉 [Download Pit data](https://drive.google.com/file/d/1ptLXKRWrlEruIXP6YdR4RgEO_HTJtev1/view?usp=sharing)

### Support or Contact

Check our [Git-Repo](https://github.com/mutationtesting-user/bugs_vs_mutants)


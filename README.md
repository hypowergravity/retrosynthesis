
# Retro-Synthesis Tools: Open Source and Academic

## Open Source Tools

**[AiZynthFinder](https://github.com/MolecularAI/aizynthfinder)**  
AI-driven retrosynthetic planning tool developed by AstraZeneca, using Monte Carlo tree search and neural networks to find synthetic routes.

**[ASKCOS](https://askcos.mit.edu/)**  
MIT's open-source platform for computer-assisted synthesis planning, featuring reaction prediction, retrosynthesis, and synthetic route scoring.

**[SYBA](https://github.com/karolisramanavicius/syba)**  
Fragment-based approach to assess synthetic accessibility of molecules using a Bayesian model trained on reaction databases.

**[RDChiral](https://github.com/connorcoley/rdchiral)**  
Template-based approach for chemical reaction parsing and template extraction, commonly used in retrosynthetic analysis.

**[MEGAN](https://github.com/molecule-one/megan)**  
Molecular graph enhanced transformer for retrosynthesis prediction using graph neural networks and attention mechanisms.

**[RetroSim](https://github.com/wengong-jin/retrosim)**  
Template-free retrosynthesis prediction using graph neural networks for molecular similarity-based synthesis planning.

**[LocalRetro](https://github.com/kaist-amsg/LocalRetro)**  
Local template-based retrosynthesis prediction focusing on reaction centers for improved accuracy and interpretability.

## Academic/Research Tools

**[Chemputer](https://www.gla.ac.uk/schools/chemistry/research/croningroup/chemputer/)**  
University of Glasgow's automated chemical synthesis platform with integrated retrosynthetic planning capabilities.

**[CASP](https://www.organic-chemistry.org/prog/casp/)**  
Computer Assisted Synthesis Planning tool providing retrosynthetic analysis with classical disconnection approaches.

**[SYNTHIA](https://www.merckgroup.com/en/research/science-space/envisioning-tomorrow/synthia.html)**  
Merck's retrosynthesis software (has academic licensing options) for synthetic route prediction and optimization.

**[ChemPlanner](https://github.com/hesther/chemplanner)**  
Template-based retrosynthetic planning tool with focus on medicinal chemistry applications.

## Commercial Tools with Academic Access

**[IBM RXN for Chemistry](https://rxn.res.ibm.com/)**  
IBM's AI-powered chemistry platform offering retrosynthesis, reaction prediction, and synthesis planning with free academic tiers.

**[Reaxys](https://www.reaxys.com/)**  
While primarily a database, Reaxys includes synthetic route prediction capabilities available to academic institutions.

**[SciFinder-n](https://scifinder-n.cas.org/)**  
CAS's platform includes retrosynthetic analysis tools, widely available in academic institutions.

## Models with Open Weights

**[GraphRetro](https://github.com/dp-yuanyn/GraphRetro)**  
Template-free retrosynthesis prediction using graph neural networks with pre-trained weights available on GitHub and HuggingFace.

**[RetroXpert](https://github.com/uta-smile/RetroXpert)**  
Neural machine translation approach for retrosynthesis with open model weights and training code available.

**[Dual-TB](https://github.com/coleygroup/dual-tb)**  
Dual templating approach combining template-based and template-free methods with released model checkpoints.

**[G2Gs](https://github.com/jnwei/g2gs)**  
Graph-to-graph sequence model for retrosynthesis prediction with pre-trained weights and comprehensive training scripts.

**[Retro*](https://github.com/binghong-ml/retro_star)**  
Best-first search algorithm for retrosynthetic planning with pre-trained neural network models for reaction prediction.

**[GLN (Graph Logic Networks)](https://github.com/divelab/GLN)**  
Logic-based graph neural network approach with open weights for both forward and retro-synthesis prediction.

**[SingleStep](https://github.com/coleygroup/singlestep_retrosynthesis)**  
Single-step retrosynthesis models using various neural architectures with pre-trained weights on USPTO dataset.

**[MHNfs](https://github.com/john-bradshaw/molecular-transformer)**  
Molecular transformer models adapted for retrosynthesis with various pre-trained checkpoints available.

**[MLPRel](https://github.com/otori-bird/mlp-retrosynthesis)**  
Multi-layer perceptron relation learning approach with open model weights and detailed training procedures.

## Hugging Face Model Hub Resources

**[HuggingFace Chemistry](https://huggingface.co/models?search=retrosynthesis)**  
Collection of retrosynthesis models including:
- IBM's RXN models (reaction prediction and retrosynthesis)
- Various transformer-based models for chemical synthesis
- Fine-tuned BERT/T5 models for chemistry tasks

**[ChemBERTa](https://huggingface.co/seyonec/ChemBERTa-zinc-base-v1)**  
Pre-trained transformer model on chemical data that can be fine-tuned for retrosynthesis tasks.

**[MolT5](https://huggingface.co/laituan245/molt5-base)**  
T5-based model pre-trained on molecular data with capabilities for retrosynthesis prediction.

## Datasets and Resources

**[USPTO Dataset](https://figshare.com/articles/dataset/Chemical_reactions_from_US_patents_1976-Sep2016_/5104873)**  
Large-scale patent reaction dataset commonly used for training retrosynthesis models.

**[ChEMBL](https://www.ebi.ac.uk/chembl/)**  
Database of bioactive molecules with reaction data useful for retrosynthetic model development.

**[Reaction Atlas](https://www.organic-chemistry.org/namedreactions/)**  
Comprehensive collection of named reactions valuable for retrosynthetic analysis training.

## Things to Consider

- **Template-based vs. Template-free**: Template-based approaches use reaction rules, while template-free methods rely on learned molecular transformations
- **Search algorithms**: Monte Carlo tree search, best-first search, or neural network-guided exploration
- **Reaction databases**: Quality and size of training data (USPTO, Reaxys, etc.)
- **Scoring metrics**: Synthetic accessibility, route feasibility, and cost estimation
- **Integration capabilities**: API access, workflow compatibility, and batch processing
- **Interpretability**: Ability to understand and modify suggested synthetic routes

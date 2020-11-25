![](http://wwwu.aau.at/chklemen/Untitled-49.png)

Reproducibility of scientific contributions is an important aspect of scholarship that has received way to little attention! This repository aims to collect information on peer-reviewed NILM (alias energy disaggregation) papers that have been published with source code or extensive supplemental material. We group NILM papers based on a number of categories: algorithms, toolkits, datasets, and misc. Feel free to contribute to this repository! Please consider our "style guide":

- **This is a title.** (year). [[pdf]](link-to-pdf) [[code]](link-to-code)
  - Main Author et al. Optional: *Acronym of conference or journal* i.e. Where was it published?

<!--
- **.** (). [[pdf]]() [[code]]()
  -  et al. *Venue.*
-->


## Algorithms

### Graph Signal Processing

- **On a Training-Less Solution for Non-Intrusive Appliance Load Monitoring Using Graph Signal Processing** (2016). [[pdf]](https://ieeexplore.ieee.org/document/7457610) [[code]](https://github.com/loneharoon/GSP_energy_disaggregator)
  - B. Zhao et al. *IEEE Access.*

### Hidden Markov Models

- **Exploiting HMM Sparsity to Perform Online Real-Time Nonintrusive Load Monitoring (NILM).** (2015). [[pdf]](http://makonin.com/doc/TSG_2015.pdf) [[code]](https://github.com/smakonin/SparseNILM)
  - S. Makonin et al. *IEEE TSG.*

### Neural Nets

- **Pruning Algorithms for Seq2Point Energy Disaggregation.** (2020). [[pdf]]() [[code]](https://github.com/JackBarber98/pruned-nilm)
  - J. Barber et al. *.*

- **Transfer Learning for Non-Intrusive Load Monitoring.** (2019). [[pdf]]() [[code]](https://github.com/MingjunZhong/transferNILM)
  - D. Michele et al. *IEEE TSG.*

- **Neural NILM: Deep neural networks applied to energy disaggregation** (2015) [[pdf]](http://jack-kelly.com/files/writing/neural_nilm.pdf) [[code]](https://github.com/JackKelly/neuralnilm)
  - J. Kelly et al. *BuildSys'15*

- **Sliding Window Approach for Online Energy Disaggregation Using Artificial Neural Networks.** (2018). [[pdf]](https://dl.acm.org/citation.cfm?doid=3200947.3201011) [[code]](https://github.com/OdysseasKr/online-nilm)
    - O. Krystalakos et al. *Venue.*

- **Sequence-to-point learning with neural networks for non-intrusive load monitoring** (2018) [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16623/15980) [[code]](https://github.com/MingjunZhong/NeuralNetNilm)
  - C. Zhang et al. *AAAI'18*

- **WaveNILM: A causal neural network for power disaggregation from the complex power signal** (2019) [[pdf]](https://arxiv.org/pdf/1902.08736.pdf) [[code]](https://github.com/picagrad/WaveNILM)
  - Alon Harell et al. *ICASSP'19*


## Toolkits

- **Towards reproducible state-of-the-art energy disaggregation.** (2019) [[pdf]](https://nipunbatra.github.io/papers/batra_buildsys_19.pdf) [[code]](https://github.com/nilmtk/nilmtk-contrib)
  - N. Batra et al. *BuildSys'19.*


- NILM-Eval [[pdf]]() [[code]](https://github.com/beckel/nilm-eval)
- NILMTK [[pdf]](https://arxiv.org/pdf/1404.3878v1.pdf) [[code]](https://github.com/nilmtk/nilmtk)

## Metrics & Performance Evaluation

- **Nonintrusive load monitoring (NILM) performance evaluation.** (2015). [[pdf]](https://link.springer.com/article/10.1007%2Fs12053-014-9306-2) [[code]](https://github.com/smakonin/NILM_PerformanceEval)
  -  S. Makonin et al. *Springer Energy Efficiency.*

- **Towards Comparability in Non-Intrusive Load Monitoring: On Data and Performance Evaluation** [[pdf]](http://makonin.com/doc/ISGT-NA_2020b.pdf) [[code]]()
  - C. Klemenjak et al. 2020 IEEE ISGT.

## Misc

- **Device-Free User Activity Detection using Non-Intrusive Load Monitoring: A Case Study.** (2020). [[pdf]](https://www.areinhardt.de/publications/2020/Reinhardt_DFHS_2020.pdf) [[code]](https://github.com/klemenjak/antgen)
    - A. Reinhardt et al. *DFHS Workshop.*

- **Machine learning approaches for non-intrusive load monitoring: from qualitative to quantitative comparation, Artificial Intelligence Review** (2018). [[pdf]](https://intelligence.csd.auth.gr/publications/machine-learning-approaches-for-non-intrusive-load-monitoring-from-qualitative-to-quantitative-comparation/) [[code]](https://github.com/ChristoferNal/power-disaggregation-complexity)
  - C. Nalmpantis et al. *Artificial Intelligence Review.*

- **Metadata for Energy Disaggregation.** (2014) [[pdf]](https://ieeexplore.ieee.org/document/6903193) [[code]](https://github.com/nilmtk/nilm_metadata)
  - J. Kelly et al. *CDS'14.*

- **On time series representations for multi-label NILM.** (2020) [[pdf]](https://link.springer.com/epdf/10.1007/s00521-020-04916-5?sharing_token=bTZg6CBADDbWx7UVvztexPe4RwlQNchNByi7wbcMAY4YyOCPZ8jI-u3LyC4lDtEOZIQACACm_MVY_633J4jzg0CtjGEkhvPkzOs5Z-2UGgB1P_m1_4nDnPxtIplmNRaDx7TM52V6MVQYVJPSqJEKpxv1n3RqXoEm1ZpW5amjaaA%3D) [[code]](https://github.com/ChristoferNal/multi-nilm)
  - C. Nalmpantis et al. *Springer Neural Computing and Applications.*

## Datasets

#### Real-World Datasets

- REDD [[link]](http://redd.csail.mit.edu/)
- UK-DALE [[link]](https://www.nature.com/articles/sdata20157)
- BLUED [[link]](http://portoalegre.andrew.cmu.edu:88/BLUED/)
- GREEND [[link]](https://sourceforge.net/projects/greend/)
- AMPds [[link]](http://ampds.org/)
- ECO [[link]](http://www.vs.inf.ethz.ch/res/show.html?what=eco-data)
- HES [[link]](http://randd.defra.gov.uk/Default.aspx?Menu=Menu&Module=More&Location=None&ProjectID=17359&FromSearch=Y&Publisher=1&SearchText=EV0702&SortString=ProjectCode&SortOrder=Asc&Paging=10#Description)
- Tracebase [[link]](https://github.com/areinhardt/tracebase)
- PLAID [[link]](http://www.plaidplug.com/)
- ENERTALK [[link]](https://www.nature.com/articles/s41597-019-0212-5)


#### Synthetic Datasets and Generators

- **SmartSim: A Device-Accurate Smart Home Simulator for Energy Analytics.** (2016). [[pdf]](http://www.ecs.umass.edu/~irwin/smartsim.pdf) [[code]](https://github.com/sustainablecomputinglab/smartsim)
    - D. Chen et al. *SmartGridComm'16.*

- **How does Load Disaggregation Performance Depend on Data Characteristics? Insights from a Benchmarking Study.** (2020). [[pdf]](https://www.areinhardt.de/publications/2020/Reinhardt_eEnergy_2020.pdf) [[code]](https://github.com/klemenjak/antgen)
    - A. Reinhardt et al. *ACM e-energy.*

- **A synthetic energy dataset for non-intrusive load monitoring in households.** (2020). [[pdf]](https://www.nature.com/articles/s41597-020-0434-6) [[code]](https://github.com/klemenjak/SynD)
    - C. Klemenjak et al. *Scientific Data.*


## Licence
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Klemenjak](https://github.com/klemenjak) has waived all copyright and related or neighbouring rights to this work.

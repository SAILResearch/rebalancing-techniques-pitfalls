# Online Appendix for "The Impact of Class Rebalancing Techniques on the Performance and Interpretation of Defect Prediction Models"

Chakkrit Tantithamthavorn, Ahmed E. Hassan, and Kenichi Matsumoto

Abstract: Defect prediction models that are trained on class imbalanced datasets (i.e., the proportion of defective and clean modules is not equally represented) are highly susceptible to produce inaccurate prediction models.
Prior research compares the impact of class rebalancing techniques on the performance of defect prediction models.
Prior research efforts arrive at contradictory conclusions due to the use of different choice of datasets, classification techniques, and performance measures.
Such contradictory conclusions make it hard to derive practical guidelines for whether class rebalancing techniques should be applied in the context of defect prediction models.
In this paper, we investigate the impact of 4 popularly-used class rebalancing techniques on 10 commonly-used performance measures and the interpretation of defect prediction models.
We also construct statistical models to better understand in which experimental design settings that class rebalancing techniques are beneficial for defect prediction models.
Through a case study of 101 datasets that span across proprietary and open-source systems, we recommend that class rebalancing techniques are necessary when quality assurance teams wish to increase the completeness of identifying software defects (i.e., Recall).
However, class rebalancing techniques should be avoided when interpreting defect prediction models.
We also find that class rebalancing techniques do not impact the AUC measure.
Hence, AUC should be used as a standard measure when comparing defect prediction models.

## Data and Raw Results

- [Datasets](https://github.com/software-analytics/DefectData)

- [Raw Results](https://github.com/SAILResearch/rebalancing-techniques-pitfalls/blob/master/raw-auc.csv)
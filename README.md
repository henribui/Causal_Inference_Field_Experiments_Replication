# Causal_Inference_Field_Experiments_Replication
Labeled Cash Transfers and School Participation
Replication of Benhassine et al. (2015), which evaluates a labeled cash transfer (LCT) program in Morocco designed to increase school participation among primary school children. The program randomly assigned households to one of four treatment arms — labeled cash transfers to fathers, labeled cash transfers to mothers, conditional cash transfers to fathers, and conditional cash transfers to mothers — with a control group receiving no transfer.

The analysis covers three main components. First, descriptive evidence on dropout patterns and mobility across announced and unannounced school visits. Second, randomization validity checks through balance tests on baseline student characteristics, verifying the integrity of the experimental design. Third, OLS estimation of treatment effects on school attendance and dropout, disaggregated by gender and school type (main vs. satellite schools).
A key finding from the paper is that labeled cash transfers significantly increased school participation even without strict conditionality, suggesting that framing and salience of the transfer matter as much as the incentive itself.

All analysis conducted in R using R Markdown, including data wrangling, visualization, and regression output.
Methods: OLS, balance checks, subgroup analysis

Language: R, R Markdown

Paper: Benhassine, N. et al. (2015). Turning a Shove into a Nudge? AEJ: Economic Policy.

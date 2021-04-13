# CRISIS
Files:

cntx_Tunning.py : File to provide the desired range of hyper-parameters. This finds the best (converging val_loss) model hyper-parameters. 

cntx_Deployment : After obtaining the best hyper-parameters, we feed this file with those and run this file up to the converging val_loss obtained from dfStats_<epochs>.csv. This file provides the results on test datasets.

CONTEXT.py : This file is custom layer keras file to capture contextual relation among the words in the tweets.

hurrican_processed.csv : Provides the processed tweets of Hurricane IRMA.

repo : Folder to hold the created files.

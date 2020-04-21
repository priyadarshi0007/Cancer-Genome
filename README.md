# Cancer-Genome
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

So here we will try to classify the genetic mutation based on the text-based clinical litreture.

The workflow is as follows

    1. A molecular pathologist selects a listing of genetic versions of interest that he/she want to investigate
    2. The molecular pathologist searches for proof within the clinical literature that somehow are applicable to the genetic     versions of interest
    3. Finally this molecular pathologist spends a large quantity of time analyzing the evidence associated with each of the variations to classify them

Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated.

You can find the dataset here : https://drive.google.com/open?id=1OQkdXMIsjH2DyHRziELHfrmbNPc6dwWa 

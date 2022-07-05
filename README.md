# ECG–CG DataSet
  Since efficient code generation is a new branch that is opened for code generation, we curate a new dataset of efficient code generation programming problems called ECG for fine-tuning and evaluation. Accordingly, our model is fine-tuned on the ECG dataset. 
  
  The ECG draws on the APPS dataset (Hendrycks et al., 2021) and the CodeContests dataset (Li et al., 2022). We describe the dataset creation process and creative ideas in detail in Readme for DataSet folder.

  Although we developed the ECG dataset to perform efficient code generation, the ECG dataset is an exhaustive dataset that can be applied to different tasks. Therefore, we derived three datasets from this feature of the ECG dataset that can be applied to different specific code processing tasks to fill the gap of other code processing-oriented datasets.
  
Among the ECG datasets our model uses for efficient code generation, we derive three datasets from them: [ECG-CG](https://github.com/CodeGeneration2/ECG-CG-DataSet), ECG-mini, and ECG-clone. 
The specific description of the [ECG-CG dataset](https://github.com/CodeGeneration2/ECG-CG-DataSet) below.


## ECG–CG DataSet
  Since applications that generate code directly from natural language descriptions are the most promising and relevant code generation datasets are too scarce, we derived the code generation dataset ECG-CG from the ECG dataset. The ECG-CG dataset is similar to the APPS dataset (Hendrycks et al., 2021). We tried to extend the use of the ECG-CG dataset by dividing it into four versions based on whether it contains better alternate code and segmented problem text, and we present the specifics of the four versions in Table 1.

![_YAO9ES F)OGB CO2F81MB6](https://user-images.githubusercontent.com/95161813/175928204-82468069-36c2-4272-b4ee-b943756287e7.png)

Table 1: Four versions of ECG-CG dataset partitioning specifics.











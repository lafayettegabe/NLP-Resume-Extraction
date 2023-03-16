# NLP-Resume-Extraction

This project aims to solve the problem of manually processing resumes to shortlist promising candidates for HR/authority. The approach taken involves using Named Entity Recognition (NER) model of Natural Language Processing (NLP) to identify and classify entities present in resumes into predefined classes such as person name, college name, academics information, relevant experiences, skill set, etc.

The project involves several tasks including problem understanding, data annotation, NER, model building and training, performance evaluation and reporting, model deployment, and model inference. The dataset used in this project contains resume content or free text and annotated tagged entities.

The NER model is trained on this dataset to identify and classify entities present in the resumes. The model is then evaluated for its performance and the results are reported. The final trained model is then deployed for inference, which involves using it to identify and classify entities in new resumes.

Overall, this project aims to automate the process of shortlisting candidates for HR/authority by using NER to identify and classify relevant information in resumes.

# Problem Statement

Resumes contain surfeit information that is not relevant for the HR/authority, and they have to manually process the resumes to shortlist the promising candidates for them. And, thus making the shortlisting task a herculean task for HR. By making use of the NER(Named Entity Recognition) model of NLP this problem can be solved by finding and classifying the entities that are present in each resume into predefined classes such as person name, college name, academics information, relevant experiences, skill set, etc.

![example](https://static-01.hindawi.com/articles/mpe/volume-2018/5761287/figures/5761287.fig.001.svgz)

**Task**

-   Problem Understanding
-   Data Annotation
-   Named Entity Recognition(NER)
-   Model Building & Training
-   Performance Evaluation & Reporting
-   Model Deployment
-   Model Inference

**Dataset Attributes**

{

'**content**' : resume content or free text

'**label**' : Annotated Tagged Entities

}

# bone-age-project

Taken from: https://www.kaggle.com/datasets/kmader/rsna-bone-age/data

Official page: https://www.rsna.org/artificial-intelligence/ai-image-challenge/rsna-pediatric-bone-age-challenge-2017

Transfer Learning and Attention Based Approach: https://noiselab.ucsd.edu/ECE228_2018/Reports/Report6.pdf  / Mean Absolute Error : 9.82/10.75 months for male and female 

Residual Attention Based Approach: https://arxiv.org/pdf/1901.05876  / Mean Absolute Error : 7.38

multi-granularity and multi-attention feature encoding :https://pmc.ncbi.nlm.nih.gov/articles/PMC11320534/pdf/qims-14-08-5902.pdf  / Mean Absolute Error : ~ 4.0

RSNA Bone Age
About Dataset
Context
At RSNA 2017 there was a contest to correctly identify the age of a child from an X-ray of their hand. This is the dataset on Kaggle making it easier to experiment with and do educational demos. Additionally maybe there are some new ideas for building smarter models for handling X-ray images.

Content
A number of folders full of images (digital and scanned) with a CSV containing the age (what is to be predicted) and the gender (useful additional information)

Acknowledgements
The dataset was originally published on CloudApp as an RSNA challenge.

Original Dataset Acknowledgements
The Radiological Society of North America (RSNA) Radiology Informatics Committee (RIC) Pediatric Bone Age Machine Learning Challenge Organizing Committee:

Kathy Andriole, Massachusetts General Hospital
Brad Erickson, Mayo Clinic
Adam Flanders, Thomas Jefferson University
Safwan Halabi, Stanford University
Jayashree Kalpathy-Cramer, Massachusetts General Hospital
Marc Kohli, University of California - San Francisco
Luciano Prevedello, The Ohio State University
Data sets used in the Pediatric Bone Age Challenge have been contributed by Stanford University, the University of Colorado and the University of California - Los Angeles.

The MedICI platform (built CodaLab) used for the challenge is provided by Jayashree Kalpathy-Cramer, supported through NIH grants (U24CA180927) and a contract from Leidos.

Inspiration
Can you predict with better than 4.2 months accuracy?
Is identifying the joints an important step?
What algorithms work best?
What do the algorithms focus on?
Is gender a necessary piece of information or can it be automatically derived from the image?

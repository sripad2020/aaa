VaxOptiML

    Authors-list
  Sripad Rama Hebbar, Dhanushkumar T, Sunila BG, Karthick Vasudevan*


    Synopsis 

Our integrated pipeline employs three models for epitope prediction in cancer immunotherapy. Through advanced machine learning techniques and curated datasets, we accurately predict epitopes, personalize HLA pairing, and prioritize targets based on immunogenicity. Rigorous evaluation showcases superior performance over existing approaches, with visual representations emphasizing our ensemble model's efficacy in expediting epitope discovery and vaccine design for cancer immunotherapy. 

    The code works by the mentioned below steps  

Input protein will be chunked, and features of those peptides will be generated.

- Peptides will be divided into epitopes and non-epitopes based on 0 and 1 annotations.
- Antigenic scores will be generated for those peptides.
- HLAs of those peptides will be generated.
- Finally, based on the antigenic score and epitope nature, final probable epitopes will be generated along with starting and ending positions.





      Getting started
  
 <img width="589" alt="Screenshot 2024-06-07 050310" src="https://github.com/sripad2020/aaa/assets/44516308/d6922443-3fa2-4498-b5ee-b2a5dd72d619">




Inputs Requirements:
1. Tumer antigen Protein sequence
2. Specify the type of MHC requirement
   

        Preliminary Outputs:
   ![Screenshot 2024-05-09 135205](https://github.com/sripad2020/aaa/assets/59697056/bbe98dba-cc77-46ce-82a2-e3c21baca954)

The given protein sequence will be chunked into peptides (probable epitopes)  and feature of those peptides will be generated.


![Screenshot 2024-05-09 135722](https://github.com/sripad2020/aaa/assets/59697056/d4ee347d-5d37-4364-aa27-fc70f6bcd06e)


The input protein sequence features will be extracted




![Screenshot 2024-05-09 143701](https://github.com/sripad2020/aaa/assets/59697056/9d0d8847-1544-4a86-aeb4-19a7ca18bb5a)

This image interprets the results regarding the kolaskar score and the chuncked epitopes, probability of being epitopes (1: epitope, 
0: non-epitope) based on the trained models (3 models has been used for being an epitope atleast 2 models should recognise them as 1)



![Screenshot 2024-05-17 094557](https://github.com/sripad2020/aaa/assets/59697056/39f8f313-ee23-44ec-a672-903600e33ffe)


This image interprets the final result of epitope and and resultant HLA for that epitope and the score of particular epitope

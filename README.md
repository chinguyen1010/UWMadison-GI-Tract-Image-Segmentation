# UWMadison-GI-Tract-Image-Segmentation
Track healthy organs in medical scans to improve cancer treatment


Description
In 2019, an estimated 5 million people were diagnosed with a cancer of the gastro-intestinal tract worldwide. Of these patients, about half are eligible for radiation therapy, usually delivered over 10-15 minutes a day for 1-6 weeks. Radiation oncologists try to deliver high doses of radiation using X-ray beams pointed to tumors while avoiding the stomach and intestines. With newer technology such as integrated magnetic resonance imaging and linear accelerator systems, also known as MR-Linacs, oncologists are able to visualize the daily position of the tumor and intestines, which can vary day to day. In these scans, radiation oncologists must manually outline the position of the stomach and intestines in order to adjust the direction of the x-ray beams to increase the dose delivery to the tumor and avoid the stomach and intestines. This is a time-consuming and labor intensive process that can prolong treatments from 15 minutes a day to an hour a day, which can be difficult for patients to tolerate—unless deep learning could help automate the segmentation process. A method to segment the stomach and intestines would make treatments much faster and would allow more patients to get more effective treatment.

The UW-Madison Carbone Cancer Center is a pioneer in MR-Linac based radiotherapy, and has treated patients with MRI guided radiotherapy based on their daily anatomy since 2015. UW-Madison has generously agreed to support this project which provides anonymized MRIs of patients treated at the UW-Madison Carbone Cancer Center. The University of Wisconsin-Madison is a public land-grant research university in Madison, Wisconsin. The Wisconsin Idea is the university's pledge to the state, the nation, and the world that their endeavors will benefit all citizens.

In this competition, you’ll create a model to automatically segment the stomach and intestines on MRI scans. The MRI scans are from actual cancer patients who had 1-5 MRI scans on separate days during their radiation treatment. You'll base your algorithm on a dataset of these scans to come up with creative deep learning solutions that will help cancer patients get better care.


Acknowledgments:
Sangjune Laurence Lee MSE MD FRCPC DABR Poonam Yadav Ph.D., DABR Yin Li PhD Jason J. Meudt BS, RTT Jessica Strang Dustin Hebel Alyx Alfson MS CMD, R.T.(T) Stephanie J. Olson RTT (BS), CMD (MS) Tera R. Kruser MS, RTT, CMD Jennifer B Smilowitz, Ph.D., DABR, FAAPM Kailee Borchert Brianne Loritz John Bayouth PhD Michael Bassetti MD PhD

Work funded by the University of Wisconsin Carbone Cancer Center Pancreas Pilot Research Grant.


<img width="789" height="478" alt="Screenshot 2025-11-06 at 11 00 04 PM" src="https://github.com/user-attachments/assets/d1465436-eac1-49a7-9717-3fc544a8402f" />

<img width="805" height="538" alt="Screenshot 2025-11-06 at 11 00 28 PM" src="https://github.com/user-attachments/assets/676acc6e-b272-4da8-a3a3-8f2d84cec6e9" />


Citation:

Lee, S.L., Yadav, P., Li, Y., Meudt, J.J., Strang, J., Hebel, D., Alfson, A., Olson, S.J., Kruser, T.R., Smilowitz, J.B., Borchert, K., Loritz, B., Gharzai, L., Karimpour, S., Bayouth, J., Bassetti, M.F., 2024. Dataset for gastrointestinal tract segmentation on serial MRIs for abdominal tumor radiotherapy. Data in Brief 57, 111159. https://doi.org/10.1016/j.dib.2024.111159. UW-Madison GI Tract Image Segmentation . https://kaggle.com/competitions/uw-madison-gi-tract-image-segmentation, 2022. Kaggle.

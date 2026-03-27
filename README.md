# Pipsqueak

No publicly available dataset in the state-of-the-art literature provides a balanced set of images. In particular, no dataset includes melanoma images across diverse skin tones, ranging from light to medium and dark. This limitation is not merely a statistical issue, but a potential clinical risk with possibly fatal consequences.

To address this gap, we created [1] Pipsqueak, a dataset derived from a systematic evaluation of several established dermatological image repositories. Specifically, the PH2, DermNet, SNU, SkinL2, and MED-NODE datasets were manually analyzed to assess the diversity of skin phototypes. This analysis confirmed the absence of images representing Fitzpatrick skin types V and VI, further highlighting the issue of systematic underrepresentation.

The ISIC archive, one of the largest and most widely used datasets for AI-driven skin lesion diagnosis, was then filtered according to the Fitzpatrick classification. This revealed only 10 images corresponding to Fitzpatrick type V and a single image for type VI. Importantly, when filtering specifically for melanoma, no samples from these darker skin types (V and VI) were found. The only image of type VI depicted a benign lesion and was therefore included in our collection.

For the Fitzpatrick 17k dataset, we applied a targeted filtering strategy focusing on melanoma and nevus images from Fitzpatrick V and VI skin tones. This was followed by a manual review to ensure quality. Several challenges emerged: many images showed the same lesion from different angles, requiring careful selection to avoid duplication; moreover, the clinical (non-dermoscopic) nature of the images required additional consideration.

Despite the relatively higher inclusivity of the Fitzpatrick 17k dataset, only 15 usable images were identified, including 9 melanomas and 6 nevi. The manual curation process was extremely demanding, with each selected image underscoring the severe underrepresentation of darker skin phototypes in medical imaging.

These rare images were sourced from multiple dermatological archives, carefully chosen to provide meaningful insight into how skin lesions present across different skin tones. Through a meticulous and rigorous selection process, we curated a total of 16 images representing patients with darker skin tones.

The final dataset consists of 15 images from Fitzpatrick 17k and one Fitzpatrick type VI image from ISIC, forming a core collection of 16 images of melanocytic lesions in darker skin types. This extremely limited dataset highlights the critical and persistent gap in representation within dermatological imaging archives.

<figure>
<img width="1382" height="679" alt="immagine" src="https://github.com/user-attachments/assets/2f7c873b-1d32-421b-bdc7-a1302e1aa372" />
<figcaption>Pipsqueak dataset collects all existing images in the literature referring to darker phototypes.</figcaption>
</figure>

# How to Cite

The dataset is freely available for use. When using it, please cite the original publications. When referencing this dataset in your own manuscripts and publications, please use the following full citations:

[1] Ruga, T., Zumpano, E., Vocaturo, E., Caroprese, L., & Arlia, C. (2025, July). Bias in Dermatological Datasets: A Critical Analysis of the Underrepresentation of Dark Skin Tones in Melanoma Classification Images. In International Conference on Computational Science (pp. 434-448). Cham: Springer Nature Switzerland.

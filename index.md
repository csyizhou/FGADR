## FGADR Dataset - Look Deeper into Eyes.

A large-scale Fine-Grained Annotated Diabetic Retinopathy (FGADR) dataset consists of two subsets: Seg-set (1842 images) and Grade-set (1000 images).

People with diabetes are at risk of having an eye disease called diabetic retinopathy (DR). This disease is when high blood glucose level cause damage to blood vessels in the retina. Computer-aided DR diagnosis is a promising choice for early detection of DR and severity grading due to the great successes of deep learning. However, most of the previous works proposed DR diagnosis systems without satisfied performance or interpretability for ophthalmologists, due to the lack of training data with consistent and fine-grained annotations. To address this problem, we construct a large-scale Fine-Grained Annotated DR dataset containing 2,842 images (FGADR). This dataset has 1,842 images with pixel-level DR-related lesion annotations, and 1,000 images with image-level labels graded by 6 board-certified ophthalmologists with intra-rater consistency. The proposed dataset enables the extensive studies of DR diagnosis.

![Image text](https://github.com/csyizhou/FGADR-2842-Dataset/blob/master/img/FGADR_Annotation.png)

### Statistics

FGADR consists of two sets. The first set, named Seg-set, contains 1,842 images with both pixel-level lesion annotations and image-level grading labels. The lesions include microaneurysms (MA), hemorrhages (HE), hard exudates (EX), soft exudates (SE), intra-retinal microvascular abnormalities (IRMA), and neovascularization (NV). The grading labels are annotated by three ophthalmologists. The second set, named Grade-set, is a set of 1,000 images with grading labels annotated by six ophthalmologists. This set is particularly used for evaluating grading performance due to its high annotation confidence. In addition to the six pixel-level lesions annotated in Seg-set, we also annotate the laser mark (LM) and proliferate membrane (PM) lesions with image-level labels.

![Image text](https://github.com/csyizhou/FGADR-2842-Dataset/blob/master/img/FGADR_Statistics.png)


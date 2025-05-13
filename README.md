# DeepLearningProject-SignLanguageDetection

Abstract—The study offers a whole deep learning framework
that can realize detection of sign language and caption translation
and combine the cutting-edge computer vision and natural
language processing technology. From this system, semantic
hand segmentation and gesture classification are integrated with
multilingual translation to establish a reliable basis for ASL
glosses recognition and interpretation. For hand region extraction
to be accurate, we utilized the EgoHands and WLAS. ResNet-18
was used to classify the hand regions after segmentation, which
lead to accurate recognition of 50 different ASL glosses. For
improving usability, the system rendered the guessed glosses into
Hindi using the Helsinki-NLP MarianMT translation service. The
assessment showed the system’s strengths in segmentation in hand
regions, glosses identification and translation, with remarkable
results in segmentation (according to F1-score), classification,
and quality of the translation (accordingly to BLEU score).
Our framework provides a scalable and flexible system that
enables continuous sign language interpretation in an educational
context, accessibility, and overcoming linguistic barriers

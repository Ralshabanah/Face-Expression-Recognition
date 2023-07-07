# Face-Expression-Recognition
SIFT &amp; LBP feature extraction used to extract features from the facial images and then passed to a CNN model to compare their results

# Sample of Images
<img width="500" alt="Screen Shot 2023-07-07 at 3 58 23 AM" src="https://github.com/raghaddii/Face-Expression-Recognition/assets/68879499/a2f2e984-8555-41c0-9331-95735a4fbf61">
<img width="500" alt="Screen Shot 2023-07-07 at 3 58 31 AM" src="https://github.com/raghaddii/Face-Expression-Recognition/assets/68879499/bc9f21f5-7d94-45e5-9130-ae6953cf9505">

# Result 
LBP	0.949239
SIFT	0.832487
Without Feature Extraction	0.964467

plot of higher acuuracy Model -->  Without Feature Extraction

<img width="400" alt="Screen Shot 2023-07-07 at 3 59 27 AM" src="https://github.com/raghaddii/Face-Expression-Recognition/assets/68879499/5e5ae7ff-684d-47b8-bcc1-6b6c93f72f38">



So it can be seen that feature extraction with LBP filters are giving pretty good results than the SIFT method but also it can noted that CNNs witout any feature extraction methods are also giving good results than the other two feature extraction techniques.

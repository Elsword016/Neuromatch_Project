## Simple exploration of Stringer Dataset - SVD components

by Biswanath Saha

SVD components from FaceMap give some valuable insights into the data. So, I tried to do a simple exploration between neural activity and face movements (if any relationships to capture or any inferences that can be drawn)

Notebook here: [eda_face.ipynb](eda_facemap/eda_face.ipynb)

## Reconstruction of the mouse face:

The dot product: `dat['beh_svd_mask'] @ dat['beh_svd_time']` gives the reconstruction of the face of the mouse. Remember this is not a 100% accurate representation but a powerful approximation or representation of the underlying data, not an exact reproduction. The goal is often to capture the most significant aspects of facial movement rather than to recreate every detail perfectly.

![high_neural_activity_face](https://github.com/user-attachments/assets/fc5230de-f98e-40f1-87b7-5a756b8f6fb7)

Can you see the eye??

## Face movements
Check the notebook, the gif shows the movement during the high neural activity. For details see the notebook:
![high_activity_facial_movements](https://github.com/user-attachments/assets/1206b162-9085-4ac2-971a-72d4be716911)

# C3-segmentation
A CNN trained to segment skeletal muscle at the C3 vertebra

Cancer treatment can be very taxing on the body, and if the patient receiving the treatment is frail, this
will effect how well the patient responds to the treatment and how well they will recover after. Frailty can
develop over time as the patient ages, but can also be brought on prematurely by cancer, and receiving cancer
treatment. The frailty of a patient is often determined by looking at sarcopenia, a degenerative condition in
which muscle mass is lost. This is typically measured by looking at muscle characteristics of the skeletal
muscles at L3, as this has been shown to be a good indicator of muscle to fat ratio. Head and neck cancer
patients often do not have scans inclusive of the L3 vertebra, however, so the muscle characteristics need to
be investigated at C3 in the neck.

The initial project proposed was to create and segment the training data, from a dataset of head and neck
cancer patients, by hand drawing countours around the sternocleidomastoid and paravertabral muscles at C3,
and to investigate different methods of preprocessing the data. 35 images were segmented by Warr and myself
and these were used to train a pretrained FCN resnet 50 network to produce a model. This model was then used 
to produce skeletal muscle characteristics for ~100 patients.



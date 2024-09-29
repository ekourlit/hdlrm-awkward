# Preprocessing arbitrarily structured data for AI with Awkward Array

Processing heterogeneous multimodal data presents challenges. These datasets feature complex, irregular structures due to nested or variable-sized outputs from different sensors, or due to missing data values. The data are typically of mixed types, complicating the preprocessing steps required before they can be fed into algorithms like multimodal representation models. AI practitioners must manage these complexities effectively.
Awkward Array is a Python library designed to process arbitrarily structured data. Operating on an array-programming paradigm, it allows users to manipulate data using NumPy-like syntax. Awkward Array also includes GPU-accelerated kernels, enabling the preprocessing of complex data directly on modern hardware accelerators, which can significantly optimize the training process and reduce data transfer latency to the device.
We introduce the Awkward Array library and provide examples that demonstrate its usage, highlighting its potential as an AI preprocessor.

Contribution at the [Heterogeneous Data and Large Representation Models in Science](https://indico.in2p3.fr/event/33412/) workshop on the 3rd of October 2024 in Toulouse, France. Contribution details: https://indico.in2p3.fr/event/33412/contributions/143423/.

The material are based on the "[Thinking In Arrays](https://cfp.scipy.org/2024/talk/FUYG37/)" tutorial, presented at the [SciPy 2024]([https://](https://www.scipy2024.scipy.org/)) conference.
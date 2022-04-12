# NEWAXOVO
Ensemble approaches are methods that aggregate the output of different (base) classifiers to achieve the final classification outcome. 
The diversity of the base classifiers is key to improving the effectiveness and robustness of the recognition performance. 
A very well-known approach to differentiate the pool of base classifiers is applying a one-vs-one decomposition schema, i.e. decomposing the classification problem a number of binary classification problems, one for each pair of classes. 
One-vs-one decomposition schemas can be affected by the problem of non-competent classifiers. 
A base classifier is non-competent for the classification of a sample if its class differs from the pair of classes used for training the base classifier. 
In this case, the base classifier’s outcome is unreliable and may deteriorate the recognition performance. 
Moreover, with ensemble approaches the explainability of the final prediction is non-trivial and requires an ad-hoc design. 
We present NEWAXOVO, an ensemble method based on one-vs-one decomposition schemas that is capable of handling non-competent classifiers and provide contrastive explanations for its predictions. 
This architecture is designed for recognizing motor imagery from electroencephalogram (EEG) data and tested on a real-world dataset. 
We also compare NEWAXOVO with similar architectures proposed in the literature, such as DRCW-OVO, and we show that NEWAXOVO outperforms them under the considered metrics.

The software here provided is the Python implementation of NEWAXOVO.
The software is provided “as is”, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

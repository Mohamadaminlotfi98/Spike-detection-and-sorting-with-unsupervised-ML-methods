# Spike-detection-and-sorting-with-unsupervised-ML-methods
Spike detection and sorting using unsupervised machine learning methods is a powerful approach in the field of neurophysiology for identifying and categorizing neuronal spikes recorded from neural signals. Here's how this process works:

Data Acquisition: The first step involves collecting neural data, typically in the form of extracellular recordings, such as multi-electrode array data. These recordings include a mixture of spike waveforms from different neurons and background noise.

Preprocessing: The raw data is preprocessed to remove artifacts, filter out noise, and detect potential spike events. This often involves techniques like band-pass filtering, thresholding, and spike alignment.

Feature Extraction: Unsupervised spike sorting relies on feature extraction to describe each detected spike waveform. Common features include amplitude, waveform shape, and principal component analysis (PCA) coefficients.

Clustering: Unsupervised machine learning methods, such as hierarchical clustering, k-means clustering, or Gaussian mixture models, are applied to the extracted features. These algorithms group similar spikes together into clusters, assuming that spikes from the same neuron will have similar waveform characteristics.

Cluster Evaluation: After clustering, it's essential to assess the quality of the clusters. This is done by examining metrics like isolation distance, L-ratio, or silhouette score to determine the separation and purity of the clusters.

Cluster Refinement: Clusters might need further refinement or manual curation, as some spikes may be misclassified. This step may involve visual inspection and the expertise of neuroscientists.

Neuron Identification: Once clusters are validated and refined, each cluster is associated with a single neuron. This allows you to assign spike events to specific neurons, effectively detecting and sorting spikes based on their originating cells.

Unsupervised machine learning methods are advantageous in spike sorting because they don't require prior knowledge or labeled training data. Instead, they autonomously learn the structure and patterns in the data. This makes them particularly useful in scenarios where a large number of spikes from multiple neurons need to be sorted, such as in multi-unit recordings.

However, it's crucial to note that while unsupervised methods can provide automated spike sorting, they may still require manual intervention for validation and fine-tuning, especially when dealing with complex datasets or closely spaced neurons.

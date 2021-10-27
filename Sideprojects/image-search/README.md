# Reverse Image Search

Using CIFAR-10 training set, created a simple content based image retrieval model.

Uses a CNN to extract visual features. Concatenates output from dense layers as feature vectors.

Using cosine or hamming distance to measure similarity between query image and training set vectors.

Return indices of top-k most similar vectors and use those indices to access paths.

Query image is from CIFAR-10 testing set.

## Suggested Improvements
- [ ] Use ImageNet pretrained VGG as feature extractor
- [ ] Use color descriptors through either a CNN or OpenCV color histograms
- [ ] Implement (train) an [Hourglass network](https://arxiv.org/pdf/1702.07432.pdf) as base model

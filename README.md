# various-cv-metrics
a list of various cv metrics for studying

## is

ref to https://github.com/sbarratt/inception-score-pytorch

## fid

measure the reality of the generated images.

$$
\text{FID}=||m-m_w||_2^2+\text{tr}(C+C_w-2(CC_w)^{1/2})
$$

- input a set of test images, from inception get a  set of feature vector owning to each image
- m, m_w, mean vector, also m_w
- C, C_w, the covariance matrix over activations for generated samples or real samples
- intra FID: compute FID within each class

## ref
1.[fid](https://zhuanlan.zhihu.com/p/393067371)

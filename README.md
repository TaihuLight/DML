# Distance metric learning in Python

## Algorithms

This python module implements two distance metric learning algorithms for learning metrics from pairwise similarity constraints:

- Pairwise constrained component analysis (PCCA) [[1]]
- Cross modal metric learning (CMML) [[2]]

## Disclaimer

This code has been re-written from scratch and is mainly untested. Results obtained using this code are not guaranteed to match those published in [[1]] and [[2]]. Some preliminary tests seem to show results similar to those obtained in [[1]] on LFW.

## Usage condition

Any publication made using this code or a modification, adaptation or traduction of this code should mention the publications [[1]] and [[2]]

## Requirements

This module depends on the lgbopt module available here: https://github.com/alexis-mignon/python-lgbopt

## References

[[1]] *PCCA: A new approach for distance learning from sparse pairwise constraints*. Alexis Mignon, Frédéric Jurie. Computer Vision and Pattern Recognition (CVPR) 2012.

[[2]] *CMML: a New Metric Learning Approach for Cross Modal Matching*. Alexis Mignon, Frédéric Jurie; Asian Conference on Computer Vision (ACCV) 2012.

[1]: https://hal.archives-ouvertes.fr/hal-00806007/document "PCCA: A new approach for distance learning from sparse pairwise constraints; A Mignon, F Jurie; Computer Vision and Pattern Recognition (CVPR) 2012"

[2]: https://hal.archives-ouvertes.fr/hal-00806082/document "CMML: a New Metric Learning Approach for Cross Modal Matching; A Mignon, F Jurie; Asian Conference on Computer Vision (ACCV) 2012"


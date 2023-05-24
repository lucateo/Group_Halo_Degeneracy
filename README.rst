Host group degeneracy in gravitational lensing time delay determination of $H_0$
==============================

This repository hosts the programs needed to obtain some of the results showed in the paper
**Host group degeneracy in gravitational lensing time delay determination of $H_0$** by Luca Teodori and Kfir Blum.

Abstract
--------
Massive elliptical galaxies, that serve as lenses in gravitational lensing time delay measurements of the
Hubble parameter $H_0$, often reside in a host group. We consider degeneracies in the modeling of the
group halo. When the group effect on imaging can be summarized by its flexion (the next order term
beyond shear in the tidal expansion), the posterior likelihood map can develop disjoint local minima,
associated with an approximate discrete symmetry of a dominant flexion term. Monte-Carlo Markov
Chain (MCMC) algorithms that are not designed to explore a rich posterior landscape can miss some of
the minima, introducing systematic bias. We study mock data and demonstrate that the bias in H0 can
exceed 10%, and pulls the inference value of H0 above its truth value, for a reason that can be traced
to the structure of a mismodeled flexion term. MCMC algorithms that are designed to cope with a rich
posterior landscape can uncover the structure. If the group is X-ray bright enough, X-ray data may also
help to resolve the degeneracy, by pinpointing the group’s center of mass. Finally, we show that some
implementations in the literature used an inaccurate kinematical prior, mis-modeling the group velocity
dispersion by as much as 20%.

Notebooks
---------
For understanding on how we obtained our results,
we prepared dedicated jupyter notebooks:

* ``mock.ipynb``: code related to mock and production of corner plots
* ``mock_zeus.ipynb``: the same as before, but with the zeus sampler
* ``mock_setuo.ipynb``: Figures of the mock setup and the three degenerate solutions

Authors
-------
- Luca Teodori; luca.teodori@weizmann.ac.il
- Kfir Blum; kfir.blum@weizmann.ac.il

Citations
---------
.. To cite our work::
..
..   @article{Teodori:2022ltt,
..       author = "Teodori, Luca and Blum, Kfir and Castorina, Emanuele and Simonovi\'c, Marko and Soreq, Yotam",
..       title = "{Comments on the mass sheet degeneracy in cosmography analyses}",
..       eprint = "2201.05111",
..       archivePrefix = "arXiv",
..       primaryClass = "astro-ph.CO",
..       month = "1",
..       year = "2022"
..   }


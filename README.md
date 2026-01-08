# $$\pi$$MPC: A Parallel-in-horizon and Construction-free NMPC Solver


This is the repository for the paper titled **[$$\pi$$MPC: A Parallel-in-horizon and Construction-free NMPC Solver](https://arxiv.org/abs/2601.XXXXX)** by Liang Wu, Bo Yang, Yilin Mo, and Jan Drgona.

We propose a novel \textit{parallel-in-horizon} and \textit{construction-free} nonlinear MPC algorithm, termed $\pi$MPC, which combines a new variable-splitting scheme with a velocity-based system representation in the ADMM framework, enabling horizon-wise parallel execution while operating directly on system matrices without explicit MPC-to-QP construction. Numerical experiments and accompanying code are provided to validate the effectiveness of the proposed method.

<p align="center">
  <img src="./figs/fig_01.png" width="500">  
</p>



## Cite as
```yaml
@inproceedings{koch2025,
      title={$$\pi$$MPC: A Parallel-in-horizon and Construction-free NMPC Solver}, 
      author={Liang Wu, Bo Yang, Yilin Mo, and Jan Drgona},
      year={2026},
      eprint={2601.XXXXX},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2601.XXXXX}, 
      volume={},
      number={},
}
```

## Acknowledgments

This research was also supported by the Ralph O’Connor Sustainable Energy Institute at Johns Hopkins University.

<p align="center">
  <img src="figs/JHU_logo.png" width="500">  
</p>



# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

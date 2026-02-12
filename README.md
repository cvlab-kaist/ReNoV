
<div align="center">

<h1>
  <span style="color:#006d6d;"><b>ReNoV:</b></span><br>
  Projected Representation Conditioning for High-fidelity Novel View Synthesis
</h1>

[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/ReNoV/)
[![arXiv](https://img.shields.io/badge/arXiv-2026-b31b1b.svg)](https://cvlab-kaist.github.io/ReNoV/)

[**Minseop Kwak**](https://mskwak01.github.io/)<sup>\*</sup>, [**Minkyung Kwon**](https://mkxdxdxd.github.io)<sup>\*</sup>, [**Jinhyeok Choi**](https://wlsguur.github.io/)<sup>\*</sup>, **Jiho Park**, <br>
[**Seungryong Kim**](https://cvlab.kaist.ac.kr/members/faculty)<sup>&dagger;</sup>

KAIST AI

<small>* Equal contribution &nbsp;&nbsp; &dagger; Corresponding author</small>

</div>

<br>

<div align="center">
  <img src="assets/teaser.png" alt="ReNoV Teaser" width="100%">
</div>

## Abstract

We propose a novel framework for diffusion-based novel view synthesis in which we leverage external representations as conditions, harnessing their geometric and semantic correspondence properties for enhanced geometric consistency in generated novel viewpoints. First, we provide a detailed analysis exploring the correspondence capabilities emergent in the spatial attention of external visual representations. Building from these insights, we propose a representation-guided novel view synthesis through dedicated representation projection modules that inject external representations into the diffusion process, a methodology named **ReNoV** (**Re**presentation-guided **No**vel **V**iew synthesis). Our experiments show that this design yields marked improvements in both reconstruction fidelity and inpainting quality, outperforming prior diffusion‐based novel‐view methods on standard benchmarks and enabling robust synthesis from sparse, unposed image collections.


## To Do

- [ ] Release Code
- [ ] Release Pretrained Models

## Citation

If you find our work useful in your research, please consider citing:

```bibtex
@article{kwak2026renov,
  title={Projected Representation Conditioning for High-fidelity Novel View Synthesis},
  author={Kwak, Minseop and Kwon, Minkyung and Choi, Jinhyeok and Park, Jiho and Kim, Seungryong},
  journal={arXiv preprint}, 
  year={2026}
}
```
# Model Weights for [ZeroFlow: Scalable Scene Flow via Distillation](https://github.com/kylevedder/zeroflow)

[Kyle Vedder](http://vedder.io), [Neehar Peri](http://www.neeharperi.com/), [Nathaniel Chodosh](https://scholar.google.com/citations?user=b4qKr7gAAAAJ&hl=en), [Ishan Khatri](https://ishan.khatri.io/), [Eric Eaton](https://www.seas.upenn.edu/~eeaton/), [Dinesh Jayaraman](https://www.seas.upenn.edu/~dineshj/), [Yang Liu](https://youngleox.github.io/), [Deva Ramanan](https://www.cs.cmu.edu/~deva/), and [James Hays](https://faculty.cc.gatech.edu/~hays/)

Project webpage: [vedder.io/zeroflow](http://vedder.io/zeroflow)

arXiv link: [arxiv.org/abs/2305.10424](http://arxiv.org/abs/2305.10424)

**Citation:**

```
@article{Vedder2023zeroflow,
    author    = {Kyle Vedder and Neehar Peri and Nathaniel Chodosh and Ishan Khatri and Eric Eaton and Dinesh Jayaraman and Yang Liu Deva Ramanan and James Hays},
    title     = {{ZeroFlow: Scalable Scene Flow via Distillation}},
    journal   = {arXiv},
    year      = {2023},
}
```

Weights labeled `supervised` are for FastFlow3D, trained with supervised annotations, and weights labeled `nsfp_distillation` or `chodosh_distillation` are ZeroFlow variants. The "official" model weights are

 - ZeroFlow:
   - Argo: three train runs of `argo/nsfp_distilatation_speed_scaled_updated*`
   - Waymo: single train run of `waymo/nsfp_distilatation_scaled`
 - FastFlow3D:
   - Argo: three train runs of `argo/supervised{_run2, _run3}`
   - Waymo: single train run of `waymo/supervised`

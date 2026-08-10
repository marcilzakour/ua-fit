# UA-Fit

**Learn 2D, Solve 3D: UA-Fit, an Uncertainty-Weighted Analytical Solver for
Multi-view Hand Mesh Recovery.** ECCV 2026 &mdash; HANDS Workshop.

Marsil Zakour, Constantin Patsch, Martin Piccolrovazzi, Yuankai Wu, Eckehard
Steinbach &middot; Technical University of Munich (Chair of Media Technology, MIRMI).

**[Project page](https://marcilzakour.github.io/ua-fit/)** &middot; Paper (coming soon)

UA-Fit learns only per-view 2D evidence (a dense oriented vote field with
per-vote anisotropic precision); a parameter-free analytical Levenberg&ndash;Marquardt
solver lifts it to a MANO-consistent 3D hand. The reconstruction stage is only
2.0M parameters, and the analytic kinematic Jacobian makes each solve about
14&times; cheaper than automatic differentiation. The solver core is released
separately as **[parafit](https://github.com/marcilzakour/parafit)**.

This repository hosts the **project page** (served at
[marcilzakour.github.io/ua-fit](https://marcilzakour.github.io/ua-fit/) from
`main`/`docs`). The paper **code** lives in a separate repository, and the
reusable solver core in **parafit**:

- Code: [marcilzakour/ua-fit-code](https://github.com/marcilzakour/ua-fit-code) (release coming soon).
- Solver: [marcilzakour/parafit](https://github.com/marcilzakour/parafit).

## Citation

```bibtex
@inproceedings{zakour2026uafit,
  title     = {Learn 2D, Solve 3D: UA-Fit, an Uncertainty-Weighted Analytical
               Solver for Multi-view Hand Mesh Recovery},
  author    = {Zakour, Marsil and Patsch, Constantin and Piccolrovazzi, Martin
               and Wu, Yuankai and Steinbach, Eckehard},
  booktitle = {European Conference on Computer Vision (ECCV) Workshops --- HANDS},
  year      = {2026}
}
```

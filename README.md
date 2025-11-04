Abstract: Benign over-fitting describes the surprising ability of heavily over-parameterized
models to interpolate noisy training sets while still generalizing to clean test data. Yet those
same models can be derailed by imperceptible, adversarial perturbations. This project asks
whether classical ℓ2-regularization can reconcile that tension—preserving interpolation accu-
racy while hardening models against adversarial attacks. Guided by these insights from prior
works, we generate high-dimensional synthetic classification tasks, sweep the ridge penalty
λ, and chart the interplay between standard risk and projected-gradient adversarial risk,
and we analyze the affect that the choice of input dimension has on adversarial robustness.
Finally, we test the external validity of the trends by training shallow ReLU networks on
MNIST with and without weight decay. The study aims to clarify when regularization can
simultaneously enable benign over-fitting and adversarial robustness, and when fundamental
trade-offs remain unavoidable.

# DSX
Tensor Math -> Verified code. Here are my experiments at stealing some great ideas from PL/Compiler folks and Optimization Theory folks to make a superoptimizing compiler.

### Main sources of inspiration (i.e. where I steal ideas from)
1. The Lean MLIR project from Oxford (https://github.com/opencompl/lean-mlir): Verifying SSA transforms of programs
2. TorchLean (recently opensourced) (https://github.com/lean-dojo/TorchLean): Verified Neur
3. Twill (https://arxiv.org/pdf/2512.18134) : Optimal warp scheduling for tensor programs
4. Scalify (https://arxiv.org/pdf/2509.10694): Egglog based superoptimizer for tensor programs
5. Portions of Pytorch (https://github.com/pytorch/pytorch) and XLA(https://github.com/openxla/xla)'s optimization passes
6. Leloy-Kun's experiments in superoptimization: (https://leloykun.github.io/ponder/lean4-tilelang/)

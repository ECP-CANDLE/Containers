# CANDLE Runtime containers

## Build for NVIDIA GPUs
This container requires NVIDIA Driver release 470 or later.
```
singularity build --fakeroot candle_rt_nvidia_21.10.sif runtime_nvidia_21.10.def
```

## Build for CPU only machine
```
singularity buid --fakeroot candle_rt_cpu.sif runtime_cpu.def
```

## Pull from Cloud
```
// NVIDIA GPUs
singularity pull candle_rt_nvidia_21.10.sif library://hsyoo/candle/runtime_nvidia_21_10.sif

// CPU image
singularity pull candle_rt_cpu.sif library://hsyoo/candle/runtime_cpu.sif
```

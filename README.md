# BenchmarkEnv
A Docker based testing environment for benchmarking ONNXRuntime(ORT) CUDA Execution Provider(EP),  ORT TensorRT EP and Nvidia FasterTransformer

# Build
sudo docker build -t benchmark -f Dockerfile.benchmark .

# Run
sudo docker run --rm --gpus all -it benchmark

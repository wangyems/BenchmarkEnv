# BenchmarkEnv
A Docker based testing environment for benchmarking ONNXRuntime(ORT) CUDA Execution Provider(EP),  ORT TensorRT EP and Nvidia FasterTransformer

sudo docker build -t benchmark -f Dockerfile.benchmark .
sudo docker run --rm --gpus all -it benchmark

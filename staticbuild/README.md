# Build Static MXNet

```bash
docker image build -t mxnet_build .
docker run -it mxnet_docker bash
bash buildmx.sh cu101mkl
```

# f-io
Utility Alpine container with fio for benchmarking mounted storage

## Usage

Just `cd` to the mounted directory, then run the container; results will be printed to the screen: 
```bash
docker run -it --rm -v $PWD:/data f-io
```

You will get the benchmark result in container stdout. See the [fio man page](https://linux.die.net/man/1/fio) for further details / script customization.

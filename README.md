# STARK BY HAND

This is a Sage script for the [Risc0](https://github.com/risc0) tutorial [STARK by Hand](https://dev.risczero.com/proof-system/stark-by-hand), written by the great [Paul](https://github.com/pdg744).

## Run

Use Sage to run the script:

```bash
sage stark_by_hand.sage
```

Or use the Docker image for simplicity: https://teddav.github.io/sagemath/

```bash
docker run --rm --platform linux/amd64 -v $(pwd):/app -w /app sagemath/sagemath 'sage ./stark_by_hand.sage'
```

# MLMM_GH125
Raw data, inputs, outputs of a conformational study of the sugar in the subsite -1 of a GH125 alpha-mannosidase using ML/MM well-tempered metadynamics.


# Reconstruct archive

The original archive was split into parts to allow upload through the GitHub web interface.

Original archive:

```
MD_reproducible_20260606_142903.tar.gz
```

## Reconstruct on Linux/macOS

Run this in the folder containing all the parts:

```bash
cat MD_reproducible_20260606_142903.tar.gz.part_* > MD_reproducible_20260606_142903.tar.gz
sha256sum -c MD_reproducible_20260606_142903.tar.gz.sha256
tar -tzf MD_reproducible_20260606_142903.tar.gz > /dev/null
```

If the checksum reports `OK`, the reconstructed archive is identical to the original.

Then extract it with:

```bash
tar -xzf MD_reproducible_20260606_142903.tar.gz
```

## Check parts

The parts should be named:

```
MD_reproducible_20260606_142903.tar.gz.part_000
MD_reproducible_20260606_142903.tar.gz.part_001
MD_reproducible_20260606_142903.tar.gz.part_002
...
```

Do not rename them before reconstruction.


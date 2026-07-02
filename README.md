# nnPETMRAttenuation

**Physics-aligned deep learning for CT-less PET attenuation correction**

This repository is a public placeholder for an ongoing research project on synthesizing
pseudo-CT attenuation maps directly from MRI and PET data, removing the need for a
physical CT scan in hybrid PET/MRI imaging.

## About

Standard approaches to pseudo-CT synthesis optimize for voxel-wise image similarity to
real CT. Our work shows this does not guarantee accurate downstream PET quantification,
and instead develops training methods that more directly target the physical relationship
between the synthesized attenuation map and PET reconstruction — combined with
anatomically-targeted refinements and additional scanner data not typically used for this
task.

The codebase builds on [nnU-Net](https://github.com/MIC-DKFZ/nnUNet).

## Status

This repository is currently private during active development and validation.

The code will be made publicly available following validation and publication.

**Access:** the private repository is available upon request — please reach out via
[GitHub](https://github.com/petroshatt) or open an issue on this placeholder repository.

## Citation

A citation entry will be added upon publication.

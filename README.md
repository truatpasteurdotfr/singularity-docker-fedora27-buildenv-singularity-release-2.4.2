# singularity-docker-fedora27-buildenv-singularity-release-2.4.2
fedora27 build env for singularity/release-2.4.2

example Dockerfile provided for convenience.

Running without installation:
```
singularity run shub://truatpasteurdotfr/singularity-docker-fedora27-buildenv-singularity-release-2.4.2
```
Building:
```
sudo singularity build singularity-docker-fedora27-buildenv-singularity-release-2.4.2.simg  Singularity
```
Download and rename:
```
singularity pull --name "singularity-docker-fedora27-buildenv-singularity-release-2.4.2" shub://truatpasteurdotfr/singularity-docker-fedora27-buildenv-singularity-release-2.4.2
```
Running with a separate $HOME 
```
mkdir -p  ~/singularity.d/home/singularity-docker-fedora27-buildenv-singularity-release-2.4.2
singularity run -H  ~/singularity.d/home/singularity-docker-fedora27-buildenv-singularity-release-2.4.2 singularity-docker-fedora27-buildenv-singularity-release-2.4.2.simg
```

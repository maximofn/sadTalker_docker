# Sad Talker docker

Dockerization of the [Sad Talker Hugging Face space](https://huggingface.co/spaces/vinthony/SadTalker)

 * Repository: [https://github.com/OpenTalker/SadTalker](https://github.com/OpenTalker/SadTalker)
 * Model card: [https://huggingface.co/vinthony/SadTalker](https://huggingface.co/vinthony/SadTalker)
 * Space: [https://huggingface.co/spaces/vinthony/SadTalker](https://huggingface.co/spaces/vinthony/SadTalker)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/sadtalker:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```

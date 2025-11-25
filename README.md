# Podman
Getting Started With Podman

## Podman Basics — Quick Reference

### This repository documents a simple walkthrough of using **Podman** to verify installation, run containers, and list images.  

### 1.) Installing podman

``` sudo apt-get -y install podman ```

### 2.) Check Version

``` podman --version ```

### 3.) Check Running Containers

``` sudo podman container ps ```

### 4.) Run a Test Container

```sudo podman container run hello-world ```

### 5.) List Downloaded Images

``` sudo podman image ls ```

### 5.) Building Image With Podman

``` sudo podman image build . -t nginx:podman  ```

# Docker for BIO609/BIO610/BIO634
Docker image for courses BIO609, BIO610, and BIO634 at University of Zurich


## Installation for 

### Install Docker
Please see the detailed instruction from https://docs.docker.com/engine/install/


### Clone the repository

```bash
git clone https://github.com/urppeia/docker_bio_609_610_634.git
```

or download (Code / Download ZIP on the right) and extract to a local folder on your computer.

### Build the Docker container

```bash
cd docker_bio_609_610_634
./build.sh
```

## Enter into the Docker container

```bash
./login_student.sh
```

If you were able to enter the container, you are prepared for the course.


## Windows

1. Install `git`: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
2. After installation is completed, open **Git Bash App**
3. Run git clone https://github.com/urppeia/docker_bio_609_610_634.git
4. Enter the directory: `cd docker_bio_609_610_634`
5. Run: `./win_login_student.sh`

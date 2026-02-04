# How To Install Docker ...?
## STEP 1: Check System Requirements

+ 64-bit operating system

+ Administrator access

+ Stable internet connection

## STEP 2: Enable WSL 2 (Windows Only)

+ Skip this step if you are using Linux or macOS

+ Open PowerShell as Administrator

+ Run:

wsl --install


+ Restart the system

+ Set WSL 2 as default:

wsl --set-default-version 2


+ Check WSL version:

wsl -l -v


+ Ensure VERSION = 2

## STEP 3: Download Docker Desktop

+ Go to:
👉 https://www.docker.com/products/docker-desktop

+ Download Docker Desktop for your OS:

    + Windows

    + macOS

## STEP 4: Install Docker Desktop
+ For Windows:

+ Run the downloaded .exe file

+ Enable WSL 2 backend when prompted

+ Complete installation

+ Restart the system

+ For macOS:

+ Open the .dmg file

+ Drag Docker to Applications

+ Launch Docker and finish setup

## STEP 5: Start Docker

+ Open Docker Desktop

+ Wait until the status shows “Docker is running”

## STEP 6: Verify Docker Installation

+ Open Command Prompt / Terminal and run:

docker --version

## STEP 7: Test Docker

+ Run the test container:

docker run hello-world


✅ If you see a success message, Docker is installed correctly.

## STEP 8: (Linux Only) Install Docker Engine
+ sudo apt update
+ sudo apt install docker.io -y
+ sudo systemctl start docker
+ sudo systemctl enable docker


+ Verify:

docker --version


+ (Optional – run Docker without sudo):

+ sudo usermod -aG docker $USER


+ Log out and log back in.

## STEP 9: Verify Running Containers
+ docker ps

## STEP 10: Docker Installation Completed 🎉

<img width="1920" height="1090" alt="Screenshot 2026-02-04 184719" src="https://github.com/user-attachments/assets/f02f8896-300c-4e39-933d-45bb2406021e" />



+ Docker is now successfully installed and ready to use...

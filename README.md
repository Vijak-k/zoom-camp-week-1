# Infrastructure & Prerequisites
This repository is my note fromn Data Engineering zoomcamp 2026 week1.
Topics covered are:
1. Docker
2. Terraform

Workshop files are in theirs respective folders.

# Docker for Data Engineering
workshop link: https://www.youtube.com/live/lP8xXebHmuE?si=yGjUGdcggKj6GLDw 

Docker is a software that we use to isolate softwares in a separated environment - _containerize_. Using docker helps reproducibility of softwares in difrrent machine, preventing _Oops !! I cannot run this software on my PC_. It is also more resource-efficient than traditional virtual machines because containers share the host system's resources and can be easily removed when no longer needed.

The reproducibility comes from an image file. Think of this as a cooking a pie. An image file is a a mold and dependencies are ingredients that you can carry anywhere, _lightweight_, and cook a pie with resource from other houses like oven. After cooking, you can clean your mold easily to re-use it, _disposable_. Thus, image files are portable that you create in your home (your PC) and run in other homes (cloud providers).

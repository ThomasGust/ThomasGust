# Thomas Gust

I'm a high school senior in Seattle. Most of what's here is software for underwater robots or machine learning for biology.

**Right now:** designing a Jetson-based controller for Triton's next vehicle.

## Underwater robotics: Triton Robotics

A friend and I started Triton in middle school to compete in the [MATE ROV Competition](https://materovcompetition.org/) (Ranger class). We finished 2nd overall at the 2026 World Championship. I lead software and electronics, and the vehicle runs on three repos:

- **[TritonOS](https://github.com/ThomasGust/TritonOS)**: the onboard runtime. Receives pilot commands over ZeroMQ, runs the control loop and thruster mixing, publishes sensor telemetry, and manages the GStreamer camera streams.
- **[TritonPilot](https://github.com/ThomasGust/TritonPilot)**: the topside control station (PyQt6). Controller input, live video and telemetry, stereo calibration, and logging.
- **[TritonAnalysis](https://github.com/ThomasGust/TritonAnalysis)**: mission-analysis tools that run on a separate laptop. Stereo depth and length measurement, photogrammetry, and underwater color correction.

Seattle Channel ran a [segment on the team's design process](https://www.seattlechannel.org/videos?videoid=x191735) in October 2026. Code from earlier seasons is in [Triton](https://github.com/ThomasGust/Triton) and [Triton2024](https://github.com/ThomasGust/Triton2024).

## Computational biology

- **[Elastic-ST](https://github.com/ThomasGust/Elastic-ST)**: a pip-installable Python library for building gene networks from spatial transcriptomics data, using information about each cell's neighbors as well as its own expression. It includes a Cython weighted elastic net, so spatial features can be regularized separately from genes. I started it early in my mentorship with Bruker Spatial Biology.
- **[Molecumixer](https://github.com/ThomasGust/Molecumixer)**: graph neural network pretraining on small molecules for generation and property prediction. Unfinished (in linked repo); the dataset and checkpoints are too large for GitHub. I worked on this project more and got it to a much more finished state, but am currently locked out from that code (see note below).

## Earlier machine learning projects

- **[BotSigner](https://github.com/ThomasGust/BotSigner)**: sign language recognition from hand landmarks. My model placed 72nd of 1,165 in Kaggle's Isolated Sign Language Recognition competition, and I built it into a desktop app for an 8th grade project.
- **[SoilingNet](https://github.com/ThomasGust/SoilingNet)**: models that estimate soiling and power loss on solar panels from images.

## Everything else

Repos from 2020 to 2023 are left mostly as they were. They're a record of how I learned to program, from pygame clones to my first transformers. I also do contract work building games and tools, like [TongoGameOfLife](https://github.com/ThomasGust/TongoGameOfLife) for The Paper Crane Factory.

Away from the keyboard, I sing bass in my school's jazz choir, play piano and tennis, and co-lead our Ethics Bowl club.

**Note:**
The great majority of my projects from high school were saved locally (without a repository online). Dealing with huge files on deep learning and data science projects, I got in the habit of not backing up work to the cloud or GitHub (yes I do know how to use .gitignore and Git LFS), and my longtime laptop was sadly destroyed at the start of my Junior summer. I am currently in the process of unlocking that drive (which should still be functional) to try and upload more of my high school projects to GitHub, but this account still holds a lot of my early projects and learning projects. It also of course contains the code for the 2026 MATE Season which I did spend a LOT of time on.

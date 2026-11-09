# Thomas Gust

I'm a high school senior at the Seattle Academy of Arts and Sciences (SAAS). Most of what's here is software for underwater robots or machine learning for biology.

**Right now:** designing a Jetson-based controller for Triton's 2027 vehicle.

## Underwater robotics: Triton Robotics

A friend and I started Triton in middle school to compete in the [MATE ROV Competition](https://materovcompetition.org/) (first Navigator class, now Ranger class). We finished 2nd overall at the 2026 World Championship (9th in 2025 and 11th in 2024). I am CEO, as well as software & electrical lead. All the code relevant to our ROV (Njord) is hosted in three repos:

- **[TritonOS](https://github.com/ThomasGust/TritonOS)**: the onboard runtime. Receives pilot commands over ZeroMQ, runs the control loop and thruster mixing, publishes sensor telemetry, and manages the GStreamer camera streams.
- **[TritonPilot](https://github.com/ThomasGust/TritonPilot)**: the topside control station (PyQt6). Controller input, live video and telemetry, stereo calibration, and logging.
- **[TritonAnalysis](https://github.com/ThomasGust/TritonAnalysis)**: mission-analysis tools that run on a separate laptop. Stereo depth and length measurement, photogrammetry, and underwater color correction.

Seattle Channel ran a [segment on the team's design process](https://www.seattlechannel.org/videos?videoid=x191735) in October 2026. Some code from earlier seasons is in [Triton](https://github.com/ThomasGust/Triton) and [Triton2024](https://github.com/ThomasGust/Triton2024), but these repos are incomplete and mostly experimental.

## Computational biology

- **[Elastic-ST](https://github.com/ThomasGust/Elastic-ST)**: a pip-installable Python library for building gene networks from spatial transcriptomics data, using information about each cell's neighbors as well as its own expression. It includes a custom Cython weighted elastic net, so spatial features can be regularized separately from genes if desired. I started it early in my mentorship with Bruker Spatial Biology.
- **[Molecumixer](https://github.com/ThomasGust/Molecumixer)**: graph neural network pretraining on small molecules for generation and property prediction. I gained experience designing my own training tasks and working with more exotic network architectures.

## Earlier machine learning projects

- **[BotSigner](https://github.com/ThomasGust/BotSigner)**: sign language recognition from hand landmarks. My model placed highly in Kaggle's Isolated Sign Language Recognition competition, and I built it into a desktop app for an 8th grade capstone project.
- **[SoilingNet](https://github.com/ThomasGust/SoilingNet)**: models that estimate soiling (dirt, bird poop etc...) and power loss on solar panels from images. I was and still am very interested in AI for climate/sustainability.

## Everything else

My account has several older repos and smaller projects. They're a record of how I learned to program, from pygame clones to my first transformers. I also do contract work building games and tools, like [TongoGameOfLife](https://github.com/ThomasGust/TongoGameOfLife) for The Paper Crane Factory.

Much of my work from high school isn't hosted online (especially a lot projects with huge datasets or model files). I think my GitHub already has plenty of cool repos, but I certainly wish I had done a better job of keeping track of and organizing my code; I'm currently going through OneDrive (which seems to not have synced many folders), and my old damaged laptop to try to upload some more of this stuff....

Away from the keyboard, I sing bass in my school's jazz choir, play piano and tennis, and co-lead our Ethics Bowl club. I also love learning new things and always try to find some time each week outside of school or on break to sit down and teach myself something new.

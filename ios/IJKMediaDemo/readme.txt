Project -> general info -> signing -> Anh nguyen + use provisioning profile (*) for all project debuging mode
compile ffmpeg
simulator: sh compile-ffmpeg.sh x86_64
device:
    sh compile-ffmpeg.sh arm64
    sh compile-ffmpeg.sh all
For performance issue, check enable videotoolbox and audiotoolbox in module.sh + options in IJKMoviePlayerViewController.m

RNNoise is a noise suppression library based on a recurrent neural network.

To compile, just type:
% ./autogen.sh
% ./configure
% make

Optionally:
% make install

While it is meant to be used as a library, a simple command-line tool is
provided as an example. It operates on RAW 16-bit (machine endian) mono
PCM files sampled at 48 kHz. It can be used as:

./examples/rnnoise_demo <noisy speech> <output denoised>

The output is also a 16-bit raw PCM file.

The latest version of the source is available from
https://gitlab.xiph.org/xiph/rnnoise .  The github repository
is a convenience copy.


# debug parameters (clion IDE)
C:\Education\code\rnnoise\19-198-0002_db20_babble.pcm C:\Education\code\rnniose\19-198-0002_db20_babble_denoise.pcm


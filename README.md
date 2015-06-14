# MP3 Decoder

An unoptimized floating point decoder, specifically for MPEG-1 Layer 3.

## Status

1. Reads most of the stuff in ID3v2 tags.
2. Ignores XING or INFO tags.
3. Ignores ID3v1 entirely.
4. Final PCM stream might still have some errors. Could be ALSA setup.
5. Several TODOs remaining throughout the source.

I wrote a summary titled [MP3 Decoding in C++](http://www.fcreyf.com/11114/mp3-decoding-in-c++), although the source should be fairly straightforward. Feel free to make suggestions, fork, or whatever.

## Licencing

This project is a form of speech. Actually converging the source into a working program might require the purchase of a patent license. A compiled version, though, wouldn't be very suitable in real world applications, considering that there are plenty of better options like MAD.

where-tube
==========

![where tube?](where-tube.jpg)

Experiments in YouTube misery.

## Dependencies

* `zbarimg`
* `convert`
* `qrencode`
* `ffmpeg`

## Usage

### Encoding (arbitrary file to MP4)

```bash
$ ./file2qr < input
$ ./frames2mp4 output.mp4
```

### Decoding (MP4 to arbitrary file)

```bash
$ dir=output_dir ./mp42frames input.mp4
$ qr2file output_dir/*.png > output
```

# ML Indexing Fixtures

Fixtures for ML image indexing tests.

## Contents

- `files/jpeg_standard.jpg`: Baseline JPEG with normal EXIF metadata.
- `files/png_alpha.png`: PNG with an alpha channel.
- `files/webp_lossy.webp`: Lossy WebP image.
- `files/heic_phone.heic`: HEIC image from a mobile device.
- `files/gif_animated.gif`: Animated GIF (first-frame extraction coverage).
- `files/tiff_cmyk.tiff`: TIFF with CMYK color space.
- `files/avif_hdr.avif`: AVIF image with modern codec metadata.
- `files/rotated_exif.jpg`: JPEG with non-default EXIF orientation.
- `files/no_exif.jpg`: JPEG without EXIF metadata.
- `files/very_large.jpg`: High-resolution image for memory/perf coverage.
- `files/very_small.png`: Tiny image for small-dimension edge cases.
- `files/panorama.jpg`: Image with an extreme aspect ratio.
- `files/space in name.jpg`: Filename with spaces.
- `files/unicode_name.jpg`: Filename normalization coverage.
- `files/truncated.jpg`: Intentionally corrupted/truncated image.
- `manifest.json`: Optional canonical metadata and expected indexing behavior.



KTX Project TO DO List
======================

$Date$

=== **Volunteers welcome!** ===

file format
-----------

- [ ] support swizzles
- [ ] support max (smallest) to base (largest) ordering of mipmap levels to help when streaming
- [ ] support use of Crunch on DX/S3TC images
- [ ] support use of zlib compression on images

library
-------

- [ ] make reader that is usable without OpenGL context
- [ ] use TexStorage in GL texture loader when available
- [ ] add Vulkan texture loader
- [ ] support new features when added to file format

library testing
---------------

- [ ] test for GL-context-free reader
- [ ] test for Vulkan loader
- [ ] proper mipmap test (multiple planes each showing a different miplevel)
- [ ] GLES2 load tests
- [ ] cubemap, 3D & array texture loading tests
- [ ] port test framework to Android.

toktx
-----

- [ ] support reading formats other than PPM, via [stb_image](https://github.com/nothings/stb/blob/master/stb_image.h)
- [ ] create ddx2ktx tool.
- [ ] support 3D and array textures
- [ ] PPM & reference ktx files for 1D textures
- [ ] PPM & reference ktx files for cubemap, 3D & array texture creation tests

general
-------

- [ ] design icon for KTX files

[Features and Capabilities](#Features-and-Capabilities
) • News • Community

And Now a Touch of Magick Use ImageMagick® to create, edit, compose, or convert bitmap images. It can read and write images in a variety of formats (over 200) including PNG, JPEG, GIF, HEIC, TIFF, DPX, EXR, WebP, Postscript, PDF, and SVG. Use ImageMagick to resize, flip, mirror, rotate, distort, shear and transform images, adjust image colors, apply various special effects, or draw text, lines, polygons, ellipses and Bézier curves.

ImageMagick is free software delivered as a ready-to-run binary distribution or as source code that you may use, copy, modify, and distribute in both open and proprietary applications. It is distributed under a derived Apache 2.0 license.

ImageMagick utilizes multiple computational threads to increase performance and can read, process, or write mega-, giga-, or tera-pixel image sizes.

The current release is ImageMagick 7.0.8-33. It runs on Linux, Windows, Mac Os X, iOS, Android OS, and others.

The authoritative ImageMagick web site is https://imagemagick.org. The authoritative source code repository is https://github.com/ImageMagick. We maintain a source code mirror at https://gitlab.com/ImageMagick. We continue to maintain the legacy release of ImageMagick, version 6, at https://legacy.imagemagick.org.

###Features and Capabilities
Here are just a few examples of what ImageMagick can do for you:

Animation	create a GIF animation sequence from a group of images.
Color management	accurate color management with color profiles or in lieu of-- built-in gamma compression or expansion as demanded by the colorspace.
Command-line processing	utilize ImageMagick from the command-line.
Complex text layout	bidirectional text support and shaping.
Composite	overlap one image over another.
Connected component labeling	uniquely label connected regions in an image.
Decorate	add a border or frame to an image.
Delineate image features	Canny edge detection, Hough lines.
Discrete Fourier transform	implements the forward and inverse DFT.
Distributed pixel cache	offload intermediate pixel storage to one or more remote servers.
Draw	add shapes or text to an image.
Encipher or decipher an image	convert ordinary images into unintelligible gibberish and back again.
Format conversion	convert an image from one format to another (e.g. PNG to JPEG).
Generalized pixel distortion	correct for, or induce image distortions including perspective.
Heterogeneous distributed processing	certain algorithms are OpenCL-enabled to take advantage of speed-ups offered by executing in concert across heterogeneous platforms consisting of CPUs, GPUs, and other processors.
High dynamic-range images	accurately represent the wide range of intensity levels found in real scenes ranging from the brightest direct sunlight to the deepest darkest shadows.
Histogram Equalization	Use adaptive histogram equalization to improve contrast in images.
Image calculator	apply a mathematical expression to an image or image channels.
Image gradients	create a gradual blend of two colors whose shape is horizontal, vertical, circular, or elliptical.
Image identification	describe the format and attributes of an image.
ImageMagick on the iPhone	convert, edit, or compose images on your iOS device such as the iPhone or iPad.
Large image support	read, process, or write mega-, giga-, or tera-pixel image sizes.
Montage	juxtapose image thumbnails on an image canvas.
Morphology of shapes	extract features, describe shapes, and recognize patterns in images.
Motion picture support	read and write the common image formats used in digital film work.
Noise and color reduction	Kuwahara Filter, mean-shift.
Perceptual hash	map visually identical images to the same or similar hash-- useful in image retrieval, authentication, indexing, or copy detection as well as digital watermarking.
Special effects	blur, sharpen, threshold, or tint an image.
Text & comments	insert descriptive or artistic text in an image.
Threads of execution support	ImageMagick is thread safe and most internal algorithms execute in parallel to take advantage of speed-ups offered by multicore processor chips.
Transform	resize, rotate, deskew, crop, flip or trim an image.
Transparency	render portions of an image invisible.
Virtual pixel support	convenient access to pixels outside the image boundaries.
Examples of ImageMagick Usage shows how to use ImageMagick from the command-line to accomplish any of these tasks and much more. Also, see Fred's ImageMagick Scripts: a plethora of command-line scripts that perform geometric transforms, blurs, sharpens, edging, noise removal, and color manipulations. With Magick.NET, use ImageMagick without having to install ImageMagick on your server or desktop.

News
Now that ImageMagick version 7 is released, we continue to maintain the legacy release of ImageMagick, version 6, at https://legacy.imagemagick.org. Learn how ImageMagick version 7 differs from previous versions with our porting guide.

ImageMagick best practices strongly encourages you to configure a security policy that suits your local environment.

The ImageMagick development process ensures a stable API and ABI. Before each ImageMagick release, we perform a comprehensive security assessment that includes memory error, thread data race detection, and continuous fuzzing to help prevent security vulnerabilities.

As an analog to linear (RGB) and non-linear (sRGB) color colorspaces, as of ImageMagick 7.0.7-17, we introduce the LinearGray colorspace. Gray is non-linear grayscale and LinearGray is linear (e.g. -colorspace linear-gray).

Want more performance from ImageMagick? Try these options:

Add more memory to your system, see the pixel cache;
Add more cores to your system, see threads of execution support;
push large images to a solid-state drive, see large image support.
If these options are prohibitive, you can reduce the quality of the image results. The default build is Q16 HDRI. If you disable HDRI, you use half the memory and instead of predominately floating point operations, you use the typically more efficient integer operations. The tradeoff is reduced precision and you cannot process out of range pixel values (e.g. negative). If you build the Q8 non-HDRI version of ImageMagick, you again reduce the memory requirements in half-- and once again there is a tradeoff, even less precision and no out of range pixel values. For a Q8 non-HDRI build of ImageMagick, use these configure script options: --with-quantum-depth=8 --disable-hdri.

Community
To join the ImageMagick community, try the discourse server. You can review questions or comments (with informed responses) posed by ImageMagick users or ask your own questions. If you want to contribute image processing algorithms, other enhancements, or bug fixes, open an issue.

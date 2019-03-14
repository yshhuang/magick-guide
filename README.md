<div class="magick-header">
<p class="text-center"><a href="#features">Features and Capabilities</a> • <a href="#news">News</a> • <a href="#community">Community</a></p>

<p class="lead magick-description"><a href="https://imagemagick.org/image/wizard.jpg" title="And Now a Touch of Magick"><img class="img-fluid magick-icon" id="logo" alt="And Now a Touch of Magick" width="265" height="352" src="https://imagemagick.org/image/wizard.jpg"></a> 
Use ImageMagick<sup><a href="http://tarr.uspto.gov/servlet/tarr?regser=serial&amp;entry=78333969">®</a></sup> to create, edit, compose, or convert bitmap images.  It can read and write images in a variety of <a href="/script/../script/formats.php">formats</a> (over 200) including PNG, JPEG, GIF, HEIC, TIFF, <a href="/script/../script/motion-picture.php">DPX</a>, <a href="/script/../script/high-dynamic-range.php">EXR</a>, WebP, Postscript, PDF, and SVG.  Use ImageMagick to resize, flip, mirror, rotate, distort, shear and transform images, adjust image colors, apply various special effects, or draw text, lines, polygons, ellipses and Bézier curves.</p>

<p>ImageMagick is free software delivered as a ready-to-run binary distribution or as source code that you may use, copy, modify, and distribute in both open and proprietary applications. It is distributed under a derived Apache 2.0 <a href="https://imagemagick.org/script/license.php">license</a>.</p>

<p>ImageMagick utilizes multiple computational threads to increase performance and can read, process, or write mega-, giga-, or tera-pixel image sizes.</p>

<p>The current release is ImageMagick <a href="/script/../script/download.php">7.0.8-33</a>.  It runs on <a href="/script/../script/download.php#unix">Linux</a>, <a href="/script/../script/download.php#windows">Windows</a>, <a href="/script/../script/download.php#macosx">Mac Os X</a>, <a href="/script/../script/download.php#iOS">iOS</a>, Android OS, and others.</p>

<p>The authoritative ImageMagick web site is <a href="https://imagemagick.org/">https://imagemagick.org</a>. The authoritative source code repository is <a href="https://github.com/ImageMagick" target="_blank">https://github.com/ImageMagick</a>.  We maintain a source code mirror at <a href="https://gitlab.com/ImageMagick" target="_blank">https://gitlab.com/ImageMagick</a>.  We continue to maintain the legacy release of ImageMagick, version 6, at <a href="https://legacy.imagemagick.org/">https://legacy.imagemagick.org</a>.</p>

<h2><a class="anchor" id="features"></a>Features and Capabilities</h2>
<p>Here are just a few <a href="/script/../script/examples.php">examples</a> of what ImageMagick can do for you:</p>
<div class="table-responsive">
<table class="table table-sm table-striped">
  <tbody><tr>
    <td><a href="https://imagemagick.org/Usage/anim_basics/">Animation</a></td>
    <td>create a GIF animation sequence from a group of images.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/color-management.php">Color management</a></td>
    <td>accurate color management with color profiles or in lieu of-- built-in gamma compression or expansion as demanded by the colorspace.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/command-line-processing.php">Command-line processing</a></td>
    <td>utilize ImageMagick from the command-line.</td>
  </tr>
  <tr>
    <td><a href="https://en.wikipedia.org/wiki/Complex_text_layout">Complex text layout</a></td>
    <td>bidirectional text support and shaping.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/composite.php">Composite</a></td>
    <td>overlap one image over another.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/connected-components.php">Connected component labeling</a></td>
    <td>uniquely label connected regions in an image.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/crop/">Decorate</a></td>
    <td>add a border or frame to an image.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/transform/#vision">Delineate image features</a></td>
    <td><a href="https://imagemagick.org/discourse-server/viewtopic.php?f=4&amp;t=25405">Canny edge detection</a>, <a href="https://imagemagick.org/discourse-server/viewtopic.php?f=4&amp;t=25476">Hough lines</a>.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/fourier/">Discrete Fourier transform</a></td>
    <td>implements the forward and inverse <a href="https://en.wikipedia.org/wiki/Discrete_Fourier_transform">DFT</a>.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/distribute-pixel-cache.php">Distributed pixel cache</a></td>
    <td>offload intermediate pixel storage to one or more remote servers.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/draw/">Draw</a></td>
    <td>add shapes or text to an image.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/cipher.php">Encipher or decipher an image</a></td>
    <td>convert ordinary images into unintelligible gibberish and back again.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/convert.php">Format conversion</a></td>
    <td>convert an image from one <a href="/script/../script/formats.php">format </a> to another (e.g. PNG to JPEG).</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/distorts/">Generalized pixel distortion</a></td>
    <td>correct for, or induce image distortions including perspective.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/architecture.php#distributed">Heterogeneous distributed processing</a></td>
    <td>certain algorithms are <a href="/script/../script/opencl.php">OpenCL</a>-enabled to take advantage of speed-ups offered by executing in concert across heterogeneous platforms consisting of CPUs, GPUs, and other processors.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/high-dynamic-range.php">High dynamic-range images</a></td>
    <td>accurately represent the wide range of intensity levels found in real scenes ranging from the brightest direct sunlight to the deepest darkest shadows.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/clahe.php">Histogram Equalization</a></td>
    <td>Use adaptive histogram equalization to improve contrast in images.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/fx.php">Image calculator</a></td>
    <td>apply a mathematical expression to an image or image channels.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/gradient.php">Image gradients</a></td>
    <td>create a gradual blend of two colors whose shape is horizontal, vertical, circular, or elliptical.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/identify.php">Image identification</a></td>
    <td>describe the format and attributes of an image.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/download.php#iOS">ImageMagick on the iPhone</a></td>
    <td>convert, edit, or compose images on your <a href="https://www.apple.com/ios/">iOS</a> device such as the iPhone or iPad.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/architecture.php#tera-pixel">Large image support</a></td>
    <td>read, process, or write mega-, giga-, or tera-pixel image sizes.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/montage.php">Montage</a></td>
    <td>juxtapose image thumbnails on an image canvas.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/morphology/">Morphology of shapes</a></td>
    <td>extract features, describe shapes, and recognize patterns in images.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/motion-picture.php">Motion picture support</a></td>
    <td>read and write the common image formats used in digital film work.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/transform/#vision">Noise and color reduction</a></td>
    <td><a href="https://imagemagick.org/discourse-server/viewtopic.php?f=4&amp;t=26480">Kuwahara Filter</a>, <a href="https://imagemagick.org/discourse-server/viewtopic.php?f=4&amp;t=25504">mean-shift</a>.</td>
  </tr>
  <tr>
    <td><a href="http://www.fmwconcepts.com/misc_tests/perceptual_hash_test_results_510/index.html">Perceptual hash</a></td>
    <td>map visually identical images to the same or similar hash-- useful in image retrieval, authentication, indexing, or copy detection as well as digital watermarking.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/blur/">Special effects</a></td>
    <td>blur, sharpen, threshold, or tint an image.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/text/">Text &amp; comments</a></td>
    <td>insert descriptive or artistic text in an image.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/architecture.php#threads">Threads of execution support</a></td>
    <td>ImageMagick is thread safe and most internal algorithms execute in <a href="/script/../script/openmp.php">parallel</a> to take advantage of speed-ups offered by multicore processor chips.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/resize/">Transform</a></td>
    <td>resize, rotate, deskew, crop, flip or trim an image.</td>
  </tr>
  <tr>
    <td><a href="https://imagemagick.org/Usage/masking/">Transparency</a></td>
    <td>render portions of an image invisible.</td>
  </tr>
  <tr>
    <td><a href="/script/../script/architecture.php#virtual-pixels">Virtual pixel support</a></td>
    <td>convenient access to pixels outside the image boundaries.</td>
  </tr>
</tbody></table>
</div>

<p><a href="https://imagemagick.org/Usage/" target="_blank">Examples of ImageMagick Usage</a> shows how to use ImageMagick from the <a href="/script/../script/command-line-processing.php">command-line</a> to accomplish any of these tasks and much more. Also, see <a href="http://www.fmwconcepts.com/imagemagick/" target="_blank">Fred's ImageMagick Scripts</a>:  a plethora of command-line scripts that perform geometric transforms, blurs, sharpens, edging, noise removal, and color manipulations. With <a href="https://github.com/dlemstra/Magick.NET">Magick.NET</a>, use ImageMagick without having to install ImageMagick on your server or desktop.</p>

<h2><a class="anchor" id="news"></a>News</h2>

<p>Now that ImageMagick version 7 is released, we continue to maintain the legacy release of ImageMagick, version 6, at <a href="https://legacy.imagemagick.org/">https://legacy.imagemagick.org</a>.  Learn how ImageMagick version 7 differs from previous versions with our <a href="/script/../script/porting.php">porting guide</a>.</p>

<p>ImageMagick best practices <strong>strongly</strong> encourages you to configure a <a href="/script/../script/security-policy.php">security policy</a> that suits your local environment.</p>

<p>The ImageMagick development process ensures a stable API and <a href="https://abi-laboratory.pro/tracker/timeline/imagemagick/">ABI</a>. Before each ImageMagick release, we perform a comprehensive security assessment that includes <a href="https://github.com/google/sanitizers/wiki/AddressSanitizer">memory error</a>, <a href="https://github.com/google/sanitizers/wiki/ThreadSanitizer">thread data race</a> detection, and continuous <a href="https://github.com/google/oss-fuzz">fuzzing</a> to help prevent security vulnerabilities.</p>

<p>As an analog to linear (RGB) and non-linear (sRGB) color colorspaces, as of ImageMagick 7.0.7-17, we introduce the LinearGray colorspace.  Gray is non-linear grayscale and LinearGray is linear (e.g. -colorspace linear-gray).</p>

<p>Want more performance from ImageMagick?  Try these options:</p>

<ul>
<li>Add more memory to your system, see <a href="/script/../script/architecture.php#cache">the pixel cache</a>;</li>
<li>Add more cores to your system, see <a href="/script/../script/architecture.php#threads">threads of execution support</a>;</li>
<li>push large images to a solid-state drive, see <a href="/script/../script/architecture.php#tera-pixel">large image support</a>.</li>
</ul>
<p>If these options are prohibitive, you can reduce the quality of the image results.  The default build is Q16 HDRI.  If you disable <a href="/script/../script/high-dynamic-range.php">HDRI</a>, you use half the memory and instead of predominately floating point operations, you use the typically more efficient integer operations.  The tradeoff is reduced precision and you cannot process out of range pixel values (e.g. negative).  If you build the Q8 non-HDRI  version of ImageMagick, you again reduce the memory requirements in half-- and once again there is a tradeoff, even less precision and no out of range pixel values.  For a Q8 non-HDRI build of ImageMagick, use these <code>configure</code> script options: <code>--with-quantum-depth=8 --disable-hdri</code>.</p>

<h2><a class="anchor" id="community"></a>Community</h2>
<p>To join the ImageMagick community, try the <a target="_blank" href="https://imagemagick.org/discourse-server/">discourse server</a>.  You can review questions or comments (with informed responses) posed by ImageMagick users or ask your own questions. If you want to contribute image processing algorithms, other enhancements, or bug fixes, open an <a href="https://github.com/ImageMagick/ImageMagick/issues">issue</a>. </p>

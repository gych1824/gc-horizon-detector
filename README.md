## gc-horizon-detector
Source code of paper, [Detecting Vanishing Points using Global Image Context in a Non-Manhattan World](http://cs.uky.edu/~ted//assets/pdfs/fasthor.pdf).

##Installation:
  1. Install Caffe and compile Matcaffe (see toturial at [Caffe Installation](http://caffe.berkeleyvision.org/installation.html)).
  2. Download the [Caffe model](https://drive.google.com/file/d/0B6JgNJOCRTogVHZaVlhrd1BBbTg/view?usp=sharing), and uncompress the tarball to "assets".
  3. Compile LSD (Line Segment Detector):

  ```bash
  $ cd assets/lsd; make
  ```

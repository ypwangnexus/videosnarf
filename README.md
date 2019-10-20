# videosnarf

mirror of videosnarf-0.63 but...

  * added support G729 using bcg729

# install

```bash
$ git clone https://github.com/ypwangnexus/videosnarf.git
$  cd videosnarf
$ ./autogen.sh
$ ./configure
$ make
```

# prerequisites
 * gcc
 * libpcap
 * cmake
 * autotools

# usage
```
  783  git clone https://github.com/aizvorski/h264bitstream
  784  cd h264bitstream/
  786  autoreconf -i
  787  ./configure
  788  make
  791  ./h264_analyze
  
  796  videosnarf/src/videosnarf rtp.264.xiaomi.pcapng
  797  videosnarf/src/videosnarf -i rtp.264.xiaomi.pcapng
  799  h264bitstream/h264_analyze H264-media-1.264
  800  h264bitstream/h264_analyze H264-media-1.264  |more
```

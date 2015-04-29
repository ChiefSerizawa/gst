Those examples are taken or inspired from the GStreamer 0.10 tutorial on http://docs.gstreamer.com/, they can be mostly found in GStreamer SDK (see website for further information).
Building those example:
gcc my-file.c -o my-file `pkg-config --cflags --libs gstreamer-0.10`

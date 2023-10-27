Hexen II: Hammer of Thyrion (uHexen2) source code.
http://uhexen2.sourceforge.net/
http://sourceforge.net/projects/uhexen2/

### Build with:
```bash
cd engine/hexen2
make glh2 -j#  (replace # with the number of CPU cores/threads in your system for faster compiling!)
```

### To run with gl4es:
```bash
LD_LIBRARY_PATH=/path/to/gl4es SDL_VIDEO_GL_DRIVER=/path/to/gl4es/libGL.so.1 LIBGL_GL=15 LIBGL_ES=1 ./glhexen2
```

AM_CXXFLAGS = @SDL2_CFLAGS@

bin_PROGRAMS = oscilliscoper

oscilliscoper_LDADD = @SDL2_LIBS@ -lavcodec -lavutil -lswscale DspFilters/libdspfilters.a
oscilliscoper_SOURCES = Encoder.cpp Main.cpp Oscilloscope.cpp Screen.cpp Wave.cpp

AM_CXXFLAGS = @SDL2_CFLAGS@

bin_PROGRAMS = oscilloscoper

oscilloscoper_LDADD = @SDL2_LIBS@ -lavcodec -lavutil -lswscale DspFilters/libdspfilters.a
oscilloscoper_SOURCES = Encoder.cpp Main.cpp Oscilloscope.cpp Screen.cpp Wave.cpp

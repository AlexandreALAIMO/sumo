bin_PROGRAMS = jtrrouter

jtrrouter_SOURCES = jtrrouter_main.cpp \
ROJTREdge.cpp ROJTREdge.h \
ROJTREdgeBuilder.cpp ROJTREdgeBuilder.h \
ROJTRRouter.cpp ROJTRRouter.h ROJTRTurnDefLoader.cpp ROJTRTurnDefLoader.h \
ROJTRFrame.cpp ROJTRFrame.h


jtrrouter_LDFLAGS = $(XERCES_LDFLAGS)

jtrrouter_LDADD   = ../router/librouter.a \
../utils/options/liboptions.a \
../utils/xml/libxml.a \
../utils/distribution/libdistribution.a \
../utils/vehicle/libvehicle.a \
../utils/common/libcommon.a \
../utils/importio/libimportio.a \
../utils/iodevices/libiodevices.a \
../utils/geom/libgeom.a \
../utils/emissions/libemissions.a \
../foreign/PHEMlight/cpp/libphemlight.a \
../foreign/tcpip/libtcpip.a \
-l$(LIB_XERCES) $(FOX_LDFLAGS) $(PROJ_LDFLAGS)

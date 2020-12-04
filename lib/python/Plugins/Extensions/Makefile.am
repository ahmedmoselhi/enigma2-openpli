installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = CutListEditor PicturePlayer MediaScanner MediaPlayer GraphMultiEPG SocketMMI DVDBurn

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if ENABLE_SPARK
SUBDIRS += SparkVFD
endif

if ENABLE_SPARK7162
SUBDIRS += spark7162VFD
endif

install_PYTHON =	\
	__init__.py

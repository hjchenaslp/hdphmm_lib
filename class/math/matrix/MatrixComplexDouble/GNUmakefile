# file: $isip/class/math/matrix/MatrixComplexDouble/GNUmakefile
# version: $Id: GNUmakefile 7256 2001-07-29 21:45:30Z jelinek $
#
# this make file builds the MatrixComplexDouble class
# 

# define the source files
#
ISIP_FILES = *.cc

# define the header files that need to be installed
#
ISIP_HEADER_FILES = MatrixComplexDouble.h

# define other dependencies (headers are included automatically)
#
ISIP_DEPS = MMatrix.h

# define the output library
#
ISIP_OLIB = lib_math_matrix.a

# define the compilation flags
# 
ISIP_CFLAGS = -fopenmp

# include the isip standard make template
#
include $(ISIP_DEVEL)/lib/scripts/make/compile.make

#
# end of file

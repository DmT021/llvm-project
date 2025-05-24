C_SOURCES := main.c
LD_EXTRAS := -L. -l_a -l_b -l_c -l_d -l_e

a.out: lib_a lib_b lib_c lib_d lib_e

include Makefile.rules

lib_a:
	"$(MAKE)" -f $(MAKEFILE_RULES) \
		DYLIB_ONLY=YES DYLIB_C_SOURCES=a.c DYLIB_NAME=_a

lib_b:
	"$(MAKE)" -f $(MAKEFILE_RULES) \
		DYLIB_ONLY=YES DYLIB_C_SOURCES=b.c DYLIB_NAME=_b

lib_c:
	"$(MAKE)" -f $(MAKEFILE_RULES) \
		DYLIB_ONLY=YES DYLIB_C_SOURCES=c.c DYLIB_NAME=_c

lib_d:
	"$(MAKE)" -f $(MAKEFILE_RULES) \
		DYLIB_ONLY=YES DYLIB_C_SOURCES=d.c DYLIB_NAME=_d

lib_e:
	"$(MAKE)" -f $(MAKEFILE_RULES) \
		DYLIB_ONLY=YES DYLIB_C_SOURCES=e.c DYLIB_NAME=_e
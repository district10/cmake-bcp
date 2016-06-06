project( MiniBoost )
file( GLOB_RECURSE LIBSRCS *.c *.cpp *.cc *.h *.hpp )
add_library( ${PROJECT_NAME} STATIC ${LIBSRCS} )

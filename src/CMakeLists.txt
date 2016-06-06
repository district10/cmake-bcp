file( GLOB SRCS *.c *.cpp *.cc *.h *.hpp )
add_executable( bcp ${SRCS} )
target_link_libraries( bcp MiniBoost )

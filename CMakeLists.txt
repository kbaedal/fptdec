SET (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

ADD_LIBRARY( fptdec STATIC
	fptdec.cpp
)
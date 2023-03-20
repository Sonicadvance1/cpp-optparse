set (NAME cpp-optparse)
set (SRCS OptionParser.cpp)
add_library(${NAME} STATIC ${SRCS} )
target_link_libraries(${NAME} FEXCore_Base)

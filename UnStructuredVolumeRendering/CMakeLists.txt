SET(CMAKE_INCLUDE_CURRENT_DIR ON) 

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})

ADD_EXECUTABLE(UnStructuredVolumeRendering main.cpp)

TARGET_LINK_LIBRARIES(UnStructuredVolumeRendering
${VTK_LIBRARIES}
)



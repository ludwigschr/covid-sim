set(TEST_GEOMETRY_SRC_FILES BoundingBox.cpp)

source_group(test\\geometry FILES ${TEST_GEOMETRY_SRC_FILES})

add_unit_tests(TARGET test-boundingbox SOURCES ${TEST_GEOMETRY_SRC_FILES} LIBRARIES geometrylib)

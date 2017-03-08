add_library(SurfRemesh 
    STATIC
    SurfaceRemeshing.cpp)

target_link_libraries(SurfRemesh Mesh)

project(glad C)
target_sources(glad PRIVATE "src/glad.c")
target_include_directories(glad PUBLIC "include")
set_property(TARGET glad PROPERTY C_STANDARD 99)

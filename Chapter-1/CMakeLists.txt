set(SRCROOT ${CMAKE_CURRENT_SOURCE_DIR}/src)

set(EXECUTABLE_NAME "Chapter-1")

set(FILES_SRC
        ${SRCROOT}/main.cpp
        )

add_executable(${EXECUTABLE_NAME} ${FILES_SRC})

target_link_libraries(${EXECUTABLE_NAME} ${SFML_LIBRARIES})
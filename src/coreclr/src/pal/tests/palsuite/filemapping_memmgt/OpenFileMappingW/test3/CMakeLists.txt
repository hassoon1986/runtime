set(SOURCES
  OpenFileMappingW.cpp
)

add_executable(paltest_openfilemappingw_test3
  ${SOURCES}
)

add_dependencies(paltest_openfilemappingw_test3 coreclrpal)

target_link_libraries(paltest_openfilemappingw_test3
  ${COMMON_TEST_LIBRARIES}
)

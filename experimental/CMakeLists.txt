add_subdirectory(include/experimental)
add_subdirectory(lib)
add_subdirectory(test)
add_subdirectory(tools)
if(DYNAMATIC_ENABLE_XLS)
  add_subdirectory(xls)
endif()

if(NOT HAVE_EGG)
  return()
endif()

add_metalib(pandaegg
  INIT init_libpandaegg pandaegg.h
  COMPONENTS p3egg p3egg2pg)
target_link_libraries(pandaegg panda)

install(TARGETS pandaegg EXPORT panda3d DESTINATION lib RUNTIME DESTINATION bin)

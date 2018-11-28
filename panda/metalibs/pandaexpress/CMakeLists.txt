add_metalib(pandaexpress
  INIT init_libpandaexpress pandaexpress.h
  COMPONENTS p3downloader p3express)

install(TARGETS pandaexpress EXPORT panda3d DESTINATION lib RUNTIME DESTINATION bin)

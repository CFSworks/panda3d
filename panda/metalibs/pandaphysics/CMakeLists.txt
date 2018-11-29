add_metalib(pandaphysics
  INIT init_libpandaphysics pandaphysics.h
  COMPONENTS p3physics p3particlesystem)

install(TARGETS pandaphysics EXPORT panda3d DESTINATION lib RUNTIME DESTINATION bin)

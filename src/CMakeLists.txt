add_executable(yawa yawa.c utils.c)
target_link_libraries (yawa X11)
target_link_libraries (yawa Imlib2)
target_link_libraries (yawa bsd)

install(TARGETS yawa DESTINATION bin)

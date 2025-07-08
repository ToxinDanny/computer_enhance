add_executable (8086_disasm.cli "8086_disasm.cli.c" "8086_disasm.cli.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET 8086_disasm.cli PROPERTY C 11)
endif()

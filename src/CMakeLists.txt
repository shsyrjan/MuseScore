
# Main
add_subdirectory(main)

# Framework
add_subdirectory(framework)

# Domain model
add_subdirectory(libmscore)

# AppShell
add_subdirectory(appshell)

# Modules
add_subdirectory(awl)
add_subdirectory(audiofile)
add_subdirectory(context)
add_subdirectory(cloud)
add_subdirectory(notation)
add_subdirectory(importexport)
add_subdirectory(userscores)
add_subdirectory(extensions)
add_subdirectory(languages)
add_subdirectory(plugins)

# Scenes common
add_subdirectory(commonscene)
add_subdirectory(playback)

# Notation
add_subdirectory(palette)
add_subdirectory(inspector)
add_subdirectory(instruments)

if (BUILD_UNIT_TESTS)
#    add_subdirectory(notation/tests) no tests at moment
    add_subdirectory(userscores/tests)
endif(BUILD_UNIT_TESTS)

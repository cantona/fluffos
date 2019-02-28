option(PACKAGE_ANSI "ansi package" ON)

if(${PACKAGE_ANSI})
    add_library(package_ansi STATIC
            "ansi.cc"
            )
endif()

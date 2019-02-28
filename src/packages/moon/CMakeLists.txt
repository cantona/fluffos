option(PACKAGE_MOON "moon package" ON)

if(${PACKAGE_MOON})
    add_library(package_moon STATIC
            "moon.cc"
            )
endif()

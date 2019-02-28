option(PACKAGE_LONELY "lonely package" ON)

if(${PACKAGE_LONELY})
    add_library(package_lonely STATIC
            "lonely.cc"
            )
endif()

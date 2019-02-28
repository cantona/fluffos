option(PACKAGE_ASYNC "async package" ON)

if(${PACKAGE_ASYNC})
    add_library(package_async STATIC
            "async.cc"
            )
endif()

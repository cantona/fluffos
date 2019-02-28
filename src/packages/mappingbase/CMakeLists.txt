option(PACKAGE_MAPPINGBASE "mappingbase package" ON)

if(${PACKAGE_MAPPINGBASE})
    add_library(package_mappingbase STATIC
            "mappingbase.cc"
            )
endif()

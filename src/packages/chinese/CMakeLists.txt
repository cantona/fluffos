option(PACKAGE_CHINESE "chinese package" ON)

if(${PACKAGE_CHINESE})
    add_library(package_chinese STATIC
            "chinese.cc"
            )
endif()

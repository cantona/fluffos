option(PACKAGE_CRYPTO "external package" ON)

if(${PACKAGE_CRYPTO})
    add_library(package_external STATIC
            "external.cc"
            )
    find_package (OpenSSL REQUIRED)
    target_link_libraries(package_external ${OPENSSL_LIBRARIES})
endif()

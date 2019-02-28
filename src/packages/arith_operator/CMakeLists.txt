option(PACKAGE_ARITH_OPERATOR "arith_operator package" ON)

if(${PACKAGE_ARITH_OPERATOR})
    add_library(package_arith_operator STATIC
            "arith_operator.cc"
            )
endif()

cmake_minimum_required(VERSION 3.0)

    project(cartesian_vector)

        add_library(mysource SHARED main.cc)

            add_executable(main main.cc)

                target_link_libraries(main mysource)

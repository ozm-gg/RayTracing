cmake_minimum_required(VERSION 3.31)
project(RayTracing)

set(CMAKE_CXX_STANDARD 20)

add_executable(RayTracing main.cpp
        vec3.h
        color.h
        ray.h
        hittable.h
        sphere.h
        hittable_list.h
        utility.h
        interval.h
        camera.h
        material.h)

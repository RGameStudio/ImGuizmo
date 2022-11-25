cmake_minimum_required(VERSION 3.17)
project(ImGuizmo)

set(CMAKE_CXX_STANDARD 20)

set(IMGUIZMO_SRC
        GraphEditor.cpp
        ImCurveEdit.cpp
        ImGradient.cpp
        ImGuizmo.cpp
        )

add_library(ImGuizmo ${IMGUIZMO_SRC})
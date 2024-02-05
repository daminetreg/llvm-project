cmake_minimum_required(VERSION 3.13.4)
project(LLVMParent)

set(LLVM_ENABLE_PROJECTS "" CACHE STRING
    "Semicolon-separated list of projects to build (${LLVM_KNOWN_PROJECTS}), or \"all\"." FORCE)

add_subdirectory(llvm)

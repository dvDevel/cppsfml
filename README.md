[
{ Platform: Mac OS.
, Library: SFML
, Package Manager: brew
, IDE: Visual Studio Code
, Plug-in: CMake
, Language: C++
},
{ CMakeLists.txt: [
  , "cmake_minimum_required(VERSION 3.10.0)"
  , "project(gaga VERSION 0.1.0 LANGUAGES C CXX)"
  , "find_package(SFML 3 COMPONENTS Graphics Window System REQUIRED)"
  , "add_executable(gaga main.cpp)"
  , "target_link_libraries(gaga SFML::Graphics SFML::Window SFML::System)"
  ]
 }
] 

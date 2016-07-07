add_executable(exampleEDT3D exampleEDT3D.cpp)
target_link_libraries(exampleEDT3D dynamicedt3d)

add_executable(exampleEDTOctomap ../../../octomap/src/OcTree.cpp exampleEDTOctomap.cpp)
target_link_libraries(exampleEDTOctomap dynamicedt3d)

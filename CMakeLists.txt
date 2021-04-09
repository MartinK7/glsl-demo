cmake_minimum_required(VERSION 3.16)
project(glsl_demo)

set(CMAKE_SYSTEM_NAME Linux)

set(CMAKE_CXX_STANDARD 20)

link_libraries(GL dl GLU glut GLEW)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/exec/)

add_compile_definitions(UNIX)

add_executable(glsl_demo Camera.cpp Effects.cpp FrameBufferObject.cpp Frustum.cpp glInfo.cpp ImageTools.cpp Inputs.cpp main.cpp Mesh.cpp ResourceManager.cpp Shader.cpp Sky.cpp Texture.cpp Texture2D.cpp TextureCubemap.cpp Timer.cpp VarManager.cpp VertexBufferObject.cpp Scenes/SceneBase.cpp Scenes/SceneManager.cpp Scenes/SceneSimple.cpp Scenes/SceneTerrain.cpp Scenes/SceneTestFur.cpp Scenes/SceneTestParallax.cpp Scenes/SceneTestRefraction.cpp Scenes/SceneTestShadowMapping.cpp Scenes/SceneToon.cpp Scenes/Script.cpp Terrain/Quadtree.cpp Terrain/QuadtreeNode.cpp Terrain/Terrain.cpp Terrain/TerrainChunk.cpp Terrain/TerrainObject.cpp Spline3D/Interpol.cpp Spline3D/Interpol3D.cpp Spline3D/InterpolNonFonct.cpp Spline3D/InterpolSpline.cpp Spline3D/SplineGL.cpp)
project(resources)

configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/caustic_0.png "${OpenMW_BINARY_DIR}/resources/water/caustic_0.png" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/Example_Fresnel.cg "${OpenMW_BINARY_DIR}/resources/water/Example_Fresnel.cg" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/Example_FresnelPS.asm "${OpenMW_BINARY_DIR}/resources/water/Example_FresnelPS.asm" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/GlassFP.cg "${OpenMW_BINARY_DIR}/resources/water/GlassFP.cg" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/GlassVP.cg "${OpenMW_BINARY_DIR}/resources/water/GlassVP.cg" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/perlinvolume.dds "${OpenMW_BINARY_DIR}/resources/water/perlinvolume.dds" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/Water02.jpg "${OpenMW_BINARY_DIR}/resources/water/Water02.jpg" COPYONLY) 
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/water.compositor "${OpenMW_BINARY_DIR}/resources/water/water.compositor" COPYONLY)
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/waves2.dds "${OpenMW_BINARY_DIR}/resources/water/waves2.dds" COPYONLY)
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/Examples-Water.material "${OpenMW_BINARY_DIR}/resources/water/Examples-Water.material" COPYONLY)
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/water/WaterNormal1.tga "${OpenMW_BINARY_DIR}/resources/water/WaterNormal1.tga" COPYONLY)
#add_executable(Parser Parser.cpp)
#add_executable(PillarsCracker Random.hpp PillarsCracker.cpp)
#add_executable(StructureCracker Random.hpp Utils.cpp StructureCracker.cpp)
#add_executable(Generation generationByCubitect/generator.cpp generationByCubitect/layers.cpp GenerationCracker.cpp)
add_executable(Test Random.hpp Parser.cpp Utils.cpp PillarsCracker.cpp StructureCracker.cpp GenerationCracker.cpp generationByCubitect/generator.cpp generationByCubitect/layers.cpp Tests.cpp)

#add_executable(MultiprocessedCracker Utils.cpp StructureCracker.cpp MultiprocessedCracker.cpp)
#add_executable(ThreadedCracker Utils.cpp StructureCracker.cpp ThreadedCracker.cpp)

add_executable(SeedCrackerByNeil2.0 Random.hpp Parser.cpp Utils.cpp PillarsCracker.cpp StructureCracker.cpp GenerationCracker.cpp generationByCubitect/generator.cpp generationByCubitect/layers.cpp StructureCracker.cpp MultiprocessedCracker.cpp main.cpp)
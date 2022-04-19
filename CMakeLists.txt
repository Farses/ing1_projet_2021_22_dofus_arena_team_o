cmake_minimum_required(VERSION 3.20)
project(ing1_projet_2021_22_dofus_arena_team_o C)

set(CMAKE_C_STANDARD 11)

add_executable(ing1_projet_2021_22_dofus_arena_team_o
        main.c)
target_link_libraries(ing1_projet_2021_22_dofus_arena_team_o -lmingw32 -lallegro-5.0.10-monolith-md-debug)

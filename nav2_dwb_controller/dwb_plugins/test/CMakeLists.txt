ament_add_gtest(vtest velocity_iterator_test.cpp)

ament_add_gtest(twist_gen_test twist_gen.cpp)
target_link_libraries(twist_gen_test standard_traj_generator)

ament_add_gtest(kinematic_parameters_test kinematic_parameters_test.cpp)
target_link_libraries(kinematic_parameters_test standard_traj_generator)

ament_add_gtest(speed_limit_test speed_limit_test.cpp)
target_link_libraries(speed_limit_test standard_traj_generator)

target_sources(${CMAKE_PROJECT_NAME}
	PRIVATE
	${CMAKE_CURRENT_LIST_DIR}/main.cpp
	PUBLIC
	${CMAKE_CURRENT_LIST_DIR}/TestFramework.h
)

target_include_directories(${CMAKE_PROJECT_NAME} PUBLIC ${CMAKE_CURRENT_LIST_DIR})

# 定义源文件列表
set(EXECUTABLE_OUTPUT_PATH ./bin)
ADD_EXECUTABLE(getcputc getcputc.c)
target_link_libraries(getcputc apue)
# 克隆空仓库（替换yourusername）
git clone https://github.com/yourusername/Sorting-Algorithms-C.git
cd Sorting-Algorithms-C

# 创建项目结构
mkdir -p include src data
touch CMakeLists.txt main.c
touch include/sort_algorithms.h include/student.h include/file_io.h include/menu.h
touch src/sort_algorithms.c src/student.c src/file_io.c src/menu.c
touch data/students.csv

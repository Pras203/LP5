sudo apt update
sudo apt install g++
g++ --version
nano parallel_graph.cpp
g++ -fopenmp -o parallel_graph parallel_graph.cpp
./parallel_graph

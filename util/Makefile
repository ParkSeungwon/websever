CXX = g++
CPPFLAGS = -I../
CXXFLAGS = -g -std=c++17 -fmax-errors=1
OBJ = $(patsubst %.cc, ../obj/%.o, $(wildcard *.cc))

all : $(OBJ) 

../obj/%.o : %.cc 
	$(CXX) $(CPPFLAGS) $(CXXFLAGS) -c $< -o $@


SRCS := $(wildcard *.cpp)
CC := g++
BINS := $(SRCS:%.cpp=%)




all: compile helloWorld




helloWorld:
	@echo "hello World"
	@echo "trololol"

compile: ${BINS} vectors.h  
	${CC} main.o vectors.o -o vectors1

clean: 
	@rm -rf vectors1
	@rm -rf *.o

listCPPFiles:
	@echo ${SRCS}
	@echo ${BINS}

%: %.cpp
	${CC} -c $<




#main: main.cpp
#	${CC} -c main.cpp

#vectors: vectors.cpp vectors.h
#	${CC} -c vectors.cpp



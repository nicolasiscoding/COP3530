all:josephus

josephus: josephusTester.o CircleLL.o
	g++ -o josephus josephusTester.o CircleLL.o

josephusTester.o: josephusTester.cpp
		g++ -c josephusTester.cpp

CircleLL.o: CircleLL.cpp
		g++ -c CircleLL.cpp

clean:
	rm *o josephus

# Pelda Makefile a diamond orokls feladat megoldasahoz
# Solaris (ural2) es Linux ala.

# forditando obj. fajlok
objs = diamond.o


prog = diamond                      # a program neve

CXX = g++                           # a C++ fordito neve
CXXFLAGS = -pedantic -Wall          # C++ kapcsolok: legyen bobeszedu, 
CXXFLAGS += -g                      # ... es forduljon debug info is

# alapertelmezett cel: tesztprogram linkelese
all: $(prog)

$(prog): $(objs) 
	$(CXX) $(objs) -o $@

$(objs): 

# takaritas igeny szerint
clean:
	rm -f $(objs) $(prog)

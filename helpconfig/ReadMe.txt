{\rtf1\ansi\ansicpg1252\cocoartf1348\cocoasubrtf170
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural

\f0\fs28 \cf0 Note that the two different terminal zips are two different configuration file variations.\
\
The outputs are included within the output folder
\b .\
\
Compiler info:\

\b0\fs24 \
OBJ = main.o\
INC = -I "./"\
\
Rasterrain: $(OBJ)\
	g++ $(OBJ) -o Rasterrain.exe\
	rm -f $(OBJ)\
	\
main.o:\
	g++ -c main.cpp $(INC)\
	\
clean:\
	rm -f $(OBJ) Rasterrain}
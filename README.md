# openstreet-maps


CampusMap is a console app that helps the user navigate UIC's campus. The project uses Dijkstra’s algorithm to find the shortest weighted path from a given starting location to a given ending location. This project is based on OpenStreetMap to navigate through the UIC campus, and uses TinyXML to parse the .xml files.

Working with the project




Compile the project

Linux and Mac

make build
Windows

g++ -O2 -std=c++11 -Wall main.cpp dist.cpp osm.cpp tinyxml2.cpp -o program.exe
Ignore warnings. This will create a new file in your local project directory, named program.exe

Run program

Linux and Mac

make run
Windows

.\program.exe
Once the program starts input map.osm as the file name

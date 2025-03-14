This script automates the otherwise prohibitively complicated task of cloning and binding the Swiss Ephemeris on any system with Bash installed.
Using a natively bound Swiss Ephemeris provides several distinct advantages against existing crates and libraries:
1 With direct bindings, API calls are as fast as it get, with 100% of functions and constants available for use.
2 Comprehensive documentation in the form of readable bindings and constants are available in the bindings.rs and sweph.h files,
as opposed to the documentation of existing crates, which is often completely absent. 

Usage: navigate your terminal to the directly in which you wish to install the swiss ephemeris: 

git clone https://github.com/PARABOLAEngineering/Medusa-Impactor.git && sudo chmod +x Medusa-Impactor 

then: ./Medusa-Impactor

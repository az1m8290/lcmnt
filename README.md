# lcmnt
### For the Complex Mersenne Number Transform, see https://github.com/robince/cmnt

The lcmnt binary is made to be run from any Linux or Linux-like terminal. It either writes the comment for a specified file to the data file 
(by default cmntdata/data.txt - this can be changed in the source), or reads the comment from the data file and prints it. There are also some 
miscellaneous launch parameters, but they aren't the core of this.

## //COMPILATION 
Use the included (albeit elementary) Makefile, or compile by hand. This was designed and compiled with g++ in mind, but other C++ compilers shouldn't 
throw a tantrum. This should compile with the default libraries bundled with most Linux distributions, but do complain if it doesn't.

## //USAGE
Obviously the primary aim of lcmnt is to read and write comments for files, but there is a bit of rubbish bundled with it. Run `cmnt` for a basic manual, 
or delve into the source code to see what four hours of my life were spent on.

## //BUGS
Many. Numerous. I'm working on implementing fixes, but the problem is that most bugs are undiscovered. The few I have found so far have been more or 
less patched.

## //OTHERS
Leave an issue if you find an issue. I will provide no other way for contacting me. If you still don't understand what this is, just test it. It's been 
fairly useful for me so far. Happy hunting!
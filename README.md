Project 은 (Un)
==

github is dumb, please view this document as raw text.

Un is a multi user dungeon written in C++ for Windows machines. The perferred compiler/IDE is MSVC for this project. 

Note on the language: Try to avoid using any C++11 shit. Compatibility with C++11
is not universal with compilers yet.

Conventions

Data storage in MySQL

All members should be private

Please use Safe if's and loop's
  if (dicks) {
  }

No Macros

All blocks should look as such

dicks {
 code
}

Variable Naming Conventions:
ClassName
objectName
variable_name
_private_member
getPrivateMember
setPrivateMemeber
functionName

Avoid using short names.
my_num
is pointless and will eventually lead to us asking eachother
what the fuck the variable is supposed to be. Just stop being
lazy and type
my_phone_number

Whatever text editor you use will more likely than not have 
autocomplete making the extra typing excuse null and void.


Avoid typedefs if possible. Make it known to the team if any are used.
If a typedef is used, for example
typedef struct struct_name
It should resolve to
struct_name_t

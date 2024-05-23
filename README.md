Makefile
*gcno
coverage_example
cmake_install.cmake
CMakeCache.txt
libgtest_main.a
libgtest.a
googletest-download
googletest-build
googletest-src
main
test

# Alternating ignore/include for .gitignore using the '!'
# Ignore everything within CMakeFiles
CMakeFiles/*
# Allow the test.dir and main.dir directory within CMakeFiles
!CMakeFiles/test.dir/
!CMakeFiles/main.dir/
# Ignore everything within test.dir and main.dir
CMakeFiles/test.dir/*
CMakeFiles/main.dir/*
# Allow the src directory within test.dir and main.dir
!CMakeFiles/test.dir/src/
!CMakeFiles/main.dir/src/
# Ignore everything within src except CODE_COVERAGE and code coverage files for both test.dir and main.dir
CMakeFiles/test.dir/src/*
CMakeFiles/main.dir/src/*
# Uncomment these lines if you want to commit the gcov files 
# !CMakeFiles/test.dir/src/*gcov
# !CMakeFiles/main.dir/src/*gcov
!CMakeFiles/main.dir/src/CODE_COVERAGE
!CMakeFiles/test.dir/src/CODE_COVERAGE


# octo
Little project manager for C/C++

# Basics

Create a new project
```$ octo new foo && cd foo```

Build project
```$ octo build [release]```

Build and run
```$ octo run [release]```

# Install
Put it in your ```/bin``` or add it to your ```$PATH```

# Compilation parameters
Open ```build/CMakeCache.txt``` and edit ```CMAKE_CXX_FLAGS:STRING``` or ```CMAKE_C_FLAGS:STRING``` depending on if you are building a C++ or a C project.

For example to use C++11: ```CMAKE_CXX_FLAGS:STRING=-std=c++11```

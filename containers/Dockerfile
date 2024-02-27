FROM ubuntu:latest

# Set the working directory inside the container
WORKDIR /app

# Install necessary dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    clang \
    neovim \
    && rm -rf /var/lib/apt/lists/*

RUN wget -P ~ https://git.io/.gdbinit

# Copy the C++ source code and CMakeLists.txt file
# COPY main.cpp CMakeLists.txt ./

# Build the C++ code using CMake and the Clang toolchain
# RUN cmake -DCMAKE_C_COMPILER=clang -DCMAKE_CXX_COMPILER=clang++ . && make

# Launch the shell
CMD ["/bin/bash"]

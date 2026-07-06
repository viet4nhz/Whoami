# Whoami
What is whoami?
**whoami is an open-source stress-testing tool designed for network and firewall testing.**

## compilation commands ##

# aarch64
clang++ --target=aarch64-linux-gnu -std=c++17 -O2 -o whoami_arm64 whoami.cpp -lssl -
  lcrypto -lpthread
# x86_64
clang++ -std=c++17 -O2 -o whoami-x86_64 whoami.cpp -lssl -lcrypto -lpthread

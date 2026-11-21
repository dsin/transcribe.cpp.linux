# This was Built in Google Colab using following command
Runtime : CPU
```
! git clone --recursive https://github.com/handy-computer/transcribe.cpp.git
%cd transcribe.cpp
! cmake -B build -DGGML_VULKAN=ON -DTRANSCRIBE_BUILD_EXAMPLES=ON
! cmake --build build --config Release -j
```

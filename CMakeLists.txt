cmake_minimum_required(VERSION 3.10)

project(KissFFT)

add_library(KissFFT 
	STATIC
	kiss_fft.c)

target_compile_features(KissFFT PRIVATE cxx_std_14)



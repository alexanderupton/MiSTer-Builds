# MiSTer-Builds

Sample workflow model for cross-compiling a MiSTerFPGA compatible arm64 ARMv7l Linux Kernel on an x64 Ubuntu host OS using the Kernel.org 5.x source tree.

Note: This assumes you will define a ${KERNEL_SRC_CFG_URL} source location variable that points to the respective .config source config location. 

export ARCH=arm
export CROSS_COMPILE=arm-linux-gnueabi-
export CFLAGS=" -O2 -pipe -mtune=cortex-a9 -g"

# MiSTer-Builds

Sample workflow model for cross-compiling a MiSTerFPGA compatible arm64 ARMv7l Linux Kernel on an x64 Ubuntu host OS using the Kernel.org 5.x source tree. <br><br>

Note: This assumes you will define a ${KERNEL_SRC_CFG_URL} source location variable that points to the respective .config source config location. <br><br>

export ARCH=arm <br>
export CROSS_COMPILE=arm-linux-gnueabi- <br>
export CFLAGS=" -O2 -pipe -mtune=cortex-a9 -g" <br>

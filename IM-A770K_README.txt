How to Build
    1. Get Toolchain (arm-eabi-4.4.3) and install
       (Visit http://www.codesourcery.com/sgpp/portal/release1033 or http://android.git.kernel.org/?p=platform/prebuilt.git)   

    2. run build_kernel_EF34K.sh
		
      $ export ARCH=arm
      $ export CROSS_COMPILE=~/your toolchain path/arm-eabi-4.4.3/bin/arm-eabi-
      $ ./build_kernel_EF34K.sh

    3.Output Files
      -	kernel : efxx_kernel_open/arch/arm/boot/zImaze
      -	module : efxx_kernel_open/obj/KERNEL_OBJ/drivers/*/*.ko
 
   
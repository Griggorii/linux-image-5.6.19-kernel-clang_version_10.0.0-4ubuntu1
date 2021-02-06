# linux-image-config-testing
config , include , kernel


example copy to autoconfig linux-oem-5.6-5.6.0/include/config

config copy to <linux-kernel-version> /include/config

$$ make menuconfig

$$ make -j16 bindeb-pkg

ignore пропустить press enter до самого конца пока не кончится список как все пропустится начнется сборка

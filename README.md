# linux-image-config-testing
config , include , kernel


example copy folder config to autoconfig linux-oem-5.6-5.6.0/include/

folder config copy to {linux-kernel-version}/include/

$$ make menuconfig

$$ make -j16 bindeb-pkg

ignore new add module enter enter press пропустить press enter до самого конца пока не кончится список как все пропустится начнется сборка

# fbalpha2012-libretro

This is port of Final Burn Alpha 2012 to Libretro (0.2.97.24) with
SDL1.2 on the FunKey S.

# Linux build

* Add the FunKey SDK binaries to your PATH by launching `source path_to_funkey_SDK/environment-setup`
* Run `./compile_libretro.sh make platform=funkey`

# Installation for FunKey

* Install sdlretro on the FunKey, see
  https://github.com/FunKey-Project/sdlretro

* If it does not exist yet, create the `/mnt/FunKey/.sdlretro/cores`
  folder.

* Copy the `svn-current/trunk/fbalpha2012_libretro.so` file into this
  folder.

# Run

* Select game rom to run, if rom file type is supported more than one
  core, a core selection menu is popup first.

* Rom in zip is supported if there are no more than 2 files (one rom
  file and one dir/readme) in the zip. If the core does not support
  in-memory rom load, the rom in zip will be extracted to
  .sdlretro/tmp and removed on exit.

* Use power-flick to enter menu.

## CREDITS

* https://github.com/libretro/fbalpha2012

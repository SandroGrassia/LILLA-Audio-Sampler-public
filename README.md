<p align="center">
<img width="500" src="/pics/logo_0.jpg")
</p>

LILLA is an audio sampler based on Teensy 4.1, designed and assembled in Italy.<br /> 
[Website](https://www.lillasampler.it/)<br /> 
[Facebook](https://www.facebook.com/Lilla.audio.sampler)

Here some images showing the project evolution since 2018.
<p align="center">
<img width="400" src="/pics/story_0.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_1.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_2.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_3.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_4.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_5.jpg")
</p>

<p align="center">
<img width="400" src="/pics/story_6.jpg")
</p>


Latest version is LILLA 2023; pcb is realized in Hong Kong, enclosure is made in Italy (aluminium sheet case crafted with laser cutter and CNC bender press - wooden parts are crafted with CNC milling machine).
Actually more versions are in progress of design.



    ====================================================================
                            DEPENDENCIES - CREDITS
    ====================================================================    
    
    Arduino.h
        WProgram.h      Copyright (c) 2017 PJRC.COM, LLC.
                        Development of this audio library was funded by PJRC.COM, LLC by sales of 
                        Teensy and Audio Adaptor boards.  Please support PJRC's efforts to develop
                        open source software by purchasing Teensy or other PJRC products.
                        Permission is hereby granted, free of charge, to any person obtaining a copy
                        of this software and associated documentation files (the "Software"), to deal
                        in the Software without restriction, including without limitation the rights
                        to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
                        copies of the Software, and to permit persons to whom the Software is
                        furnished to do so, subject to the following conditions:
                        The above copyright notice, development funding notice, and this permission
                        notice shall be included in all copies or substantial portions of the Software.

            stdlib.h
            string.h
            math.h
        pins_arduino.h  Copyright (c) 2018 PJRC.COM, LLC.
            stdint.h
    control_sgtl5000.h  Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        AudioStream.h   Copyright (c) 2017 PJRC.COM, LLC.
            stdio.h
            string.h
        AudioControl.h  Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
            stdint.h
    AudioStream.h       
    filter_biquad.h     Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        Arduino.h
        AudioStream.h
    input_i2s.h         Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        Arduino.h
        AudioStream.h
        DMAChannel.h    Copyright (c) 2017 PJRC.COM, LLC.
            imxrt.h
    memcpy_audio.h      Copyright (c) 2016 Frank Bösing
                        Permission is hereby granted, free of charge, to any person obtaining
                        a copy of this software and associated documentation files (the
                        "Software"), to deal in the Software without restriction, including
                        without limitation the rights to use, copy, modify, merge, publish,
                        distribute, sublicense, and/or sell copies of the Software, and to
                        permit persons to whom the Software is furnished to do so, subject to
                        the following conditions:
                        1. The above copyright notice and this permission notice shall be
                        included in all copies or substantial portions of the Software.
                        2. If the Software is incorporated into a build system that allows
                        selection among a list of target devices, then similar target
                        devices manufactured by PJRC.COM must be included in the list of
                        target devices and selectable in the same manner.

    mixer.h             Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        Arduino.h
        AudioStream.h
    output_i2s.h        Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        Arduino.h
        AudioStream.h
        DMAChannel.h
            imxrt.h
    spi_interrupt.h     Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        Arduino.h
        AudioStream.h
        SPI.h           GNU General Public License version 2 or the GNU Lesser General Public License version 2.1
            Arduino.h
    Wire.h              GNU Lesser General Public License
        WireIMXRT.h     Copyright (c) 2014-2017, Paul Stoffregen, paul@pjrc.com
    EEPROM.h            Copyright (c) 2015 Paul Stoffregen <paul@pjrc.com>
        stddef.h
        stdint.h
        avr_functions.h Copyright (c) 2017 PJRC.COM, LLC.
                        Permission is hereby granted, free of charge, to any person obtaining
                        a copy of this software and associated documentation files (the
                        "Software"), to deal in the Software without restriction, including
                        without limitation the rights to use, copy, modify, merge, publish,
                        distribute, sublicense, and/or sell copies of the Software, and to
                        permit persons to whom the Software is furnished to do so, subject to
                        the following conditions:
                        1. The above copyright notice and this permission notice shall be
                        included in all copies or substantial portions of the Software.
                        2. If the Software is incorporated into a build system that allows
                        selection among a list of target devices, then similar target
                        devices manufactured by PJRC.COM must be included in the list of
                        target devices and selectable in the same manner.
            inttypes.h  Copyright (C) 2006-2019 Free Software Foundation, Inc.
                        This file is part of the GNU ISO C++ Library.  This library is free
                        software; you can redistribute it and/or modify it under the
                        terms of the GNU General Public License as published by the
                        Free Software Foundation; either version 3, or (at your option)
                        any later version.
                        This library is distributed in the hope that it will be useful,
                        but WITHOUT ANY WARRANTY; without even the implied warranty of
                        MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
                        GNU General Public License for more details.
                        Under Section 7 of GPL version 3, you are granted additional
                        permissions described in the GCC Runtime Library Exception, version
                        3.1, as published by the Free Software Foundation.
                        You should have received a copy of the GNU General Public License and
                        a copy of the GCC Runtime Library Exception along with this program;
                        see the files COPYING3 and COPYING.RUNTIME respectively.  If not, see
                        <http://www.gnu.org/licenses/>.
                tr1/cinttypes   Copyright (C) 2006-2019 Free Software Foundation, Inc.
                                This file is part of the GNU ISO C++ Library....

    SD.h                Copyright (c) 2020, Paul Stoffregen, paul@pjrc.com               
        Arduino.h
        SdFat.h         MIT License
            common/SysCall.h        MIT License
                stdint.h
                stddef.h
                SdFatConfig.h       MIT License
                    stdint.h
                    avr/io.h
                    Arduino.h
                    application.h   ??
                PrintBasic.h        MIT License
            SdCard/SdCard.h         MIT License
                SdioCard.h          MIT License
                    SysCall.h       MIT License
                        stdint.h
                        stddef.h
                        SdFatConfig.h   MIT License
                            stdint.h
                            avr/io.h    Copyright (c) 2015 Paul Stoffregen <paul@pjrc.com>
                                avr_emulation.h     Copyright (c) 2019 PJRC.COM, LLC.
                                                    Permission is hereby granted, free of charge, to any person obtaining
                                                    a copy of this software and associated documentation files (the
                                                    "Software"), to deal in the Software without restriction, including
                                                    without limitation the rights to use, copy, modify, merge, publish,
                                                    distribute, sublicense, and/or sell copies of the Software, and to
                                                    permit persons to whom the Software is furnished to do so, subject to
                                                    the following conditions:
                                                    1. The above copyright notice and this permission notice shall be
                                                    included in all copies or substantial portions of the Software.
                                                    2. If the Software is incorporated into a build system that allows
                                                    selection among a list of target devices, then similar target
                                                    devices manufactured by PJRC.COM must be included in the list of
                                                    target devices and selectable in the same manner.

                    SdCardInterface.h   MIT License
                        common/FsBlockDeviceInterface.h MIT License
                            stdint.h
                            stddef.h
                        SdCardInfo.h  MIT License
                            common/SysCall.h  MIT License
                                stdint.h
                                stddef.h
                                SdFatConfig.h

                SdSpiCard.h    MIT License
                    stddef.h
                    common/SysCall.h
                    SdCardInfo.h
                    SdCardInterface.h
                    SpiDriver/SdSpiDriver.h MIT License
                        common/SysCall.h

            ExFatLib/ExFatLib.h     MIT License
                ExFatVolume.h   MIT License
                    ExFatFile.h MIT License
                        limits.h    Copyright (C) 1992-2019 Free Software Foundation, Inc.
                                    GCC is free software; you can redistribute it and/or modify it under
                                    the terms of the GNU General Public License as published by the Free
                                    Software Foundation; either version 3, or (at your option) any later
                                    version.
                                    GCC is distributed in the hope that it will be useful, but WITHOUT ANY
                                    WARRANTY; without even the implied warranty of MERCHANTABILITY or
                                    FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License
                                    for more details.
                                    Under Section 7 of GPL version 3, you are granted additional
                                    permissions described in the GCC Runtime Library Exception, version
                                    3.1, as published by the Free Software Foundation.
                                    You should have received a copy of the GNU General Public License and
                                    a copy of the GCC Runtime Library Exception along with this program;
                                    see the files COPYING3 and COPYING.RUNTIME respectively.  If not, see
                                    <http://www.gnu.org/licenses/>.

                        string.h    (varie versioni)
                        common/FsDateTime.h MIT License
                            stdint.h
                            CompileDateTime.h
                            SysCall.h
                        common/FsApiConstants.h MIT License
                            SysCall.h
                            fcntl.h
                        common/FmtNumber.h MIT License
                            math.h
                            stdint.h
                            stddef.h
                        common/FsName.h MIT License
                            SysCall.h
                            stdint.h
                        ExFatPartition.h    MIT License
                            SysCall.h
                            common/FsBlockDevice.h
                            common/FsCache.h
                            common/FsStructs.h                        

                ExFatFormatter.h    MIT License
                    common/FsBlockDevice.h        
            
            FatLib/FatLib.h  MIT License
                FatVolume.h
                FatFormatter.h
            FsLib/FsLib.h
            sdios.h
        FS.h

    SerialFlash.h
    dspinst.h
    MIDI.h
    SPI.h
    Adafruit_GFX.h
    Adafruit_ILI9341.h
    output_noiseshaped_pwm.h
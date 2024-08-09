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
        Original or modified libraries/classes and licensing notes
    ====================================================================    
    
    - Arduino.h     Header file
        + WProgram.h    Copyright (c) 2017 PJRC.COM, LLC.
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
                        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
                        EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
                        MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
                        NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
                        BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
                        ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
                        CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
                        SOFTWARE.
            stdlib.h    Copyright (C) 2002-2024 Free Software Foundation, Inc.
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
            string.h    Copyright (C) 2002-2024 Free Software Foundation, Inc. (see above for licensing)
            math.h      Copyright (C) 2006-2015 Free Software Foundation, Inc.  (see above for licensing)
        + pins_arduino.h    Copyright (c) 2018 PJRC.COM, LLC.  (see above for licensing)
            stdint.h    Copyright (C) 2002-2024 Free Software Foundation, Inc.  (see above for licensing)
    
    - DMAChannel    Copyright (c) 2017 PJRC.COM, LLC.
        + imxrt.h   ARM documentation

    - control_sgtl5000.h    Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
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
                            THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
                            IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
                            FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
                            AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
                            LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
                            OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
                            THE SOFTWARE.
        + AudioStream.h Copyright (c) 2017 PJRC.COM, LLC. (see above for licensing)
            stdio.h     Copyright (C) 2002-2024 Free Software Foundation, Inc. (see above for licensing)
            string.h    (see above)
        + AudioControl.h    Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
            stdint.h    (see above)
    
    - filter_biquad.h     Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
    
    - input_i2s.h         Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
        + DMAChannel.h    Copyright (c) 2017 PJRC.COM, LLC. (see above for licensing)
            imxrt.h     (see above)
   
    - memcpy_audio.h    Copyright (c) 2016 Frank Bösing
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
                        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
                        EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
                        MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
                        NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
                        BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
                        ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
                        CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
                        SOFTWARE.

    - mixer.h             Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
    
    - output_i2s.h        Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
        + DMAChannel.h    (see above)
            imxrt.h       (see above)
    
    - record_queue.h    Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com
        + Arduino.h       (see above)
        + AudioStream.h   (see above)

    - spi_interrupt.h     Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
        + SPI.h         Copyright (c) 2010 by Cristian Maglie <c.maglie@bug.st>
                        Copyright (c) 2014 by Paul Stoffregen <paul@pjrc.com> (Transaction API)
                        Copyright (c) 2014 by Matthijs Kooijman <matthijs@stdin.nl> (SPISettings AVR)
                        This file is free software; you can redistribute it and/or modify 
                        it under the terms of either the GNU General Public License version 2
                        or the GNU Lesser General Public License version 2.1, both as
                        published by the Free Software Foundation.
                        (Static Linking: Puoi linkare staticamente la libreria LGPL, ma in questo caso devi fornire i mezzi per permettere agli utenti di relinkare la tua applicazione con una versione modificata della libreria. Questo può significare fornire i file oggetto della tua applicazione o un altro meccanismo che permetta la relinkazione.)
    
    - Wire.h            Copyright (c) 2006 Nicholas Zambetti.  All right reserved.
                        This library is free software; you can redistribute it and/or
                        modify it under the terms of the GNU Lesser General Public
                        License as published by the Free Software Foundation; either
                        version 2.1 of the License, or (at your option) any later version.
                        This library is distributed in the hope that it will be useful,
                        but WITHOUT ANY WARRANTY; without even the implied warranty of
                        MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
                        Lesser General Public License for more details.
                        You should have received a copy of the GNU Lesser General Public
                        License along with this library; if not, write to the Free Software
                        Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
                        Modified 2012 by Todd Krein (todd@krein.org) to implement repeated starts
                        (Static Linking: È permesso, ma richiede di fornire i mezzi per permettere agli utenti di relinkare la tua applicazione con una versione modificata della libreria. Questo potrebbe significare distribuire i file oggetto della tua applicazione o un altro meccanismo che permetta la relinkazione.)
        + WireIMXRT.h     Copyright (c) 2014-2017, Paul Stoffregen, paul@pjrc.com (see above for licensing)
    
    - EEPROM.h            Copyright (c) 2015 Paul Stoffregen <paul@pjrc.com> (see above for licensing)
        + stddef.h        (see above)
        + stdint.h        (see above)
        + avr_functions.h Copyright (c) 2017 PJRC.COM, LLC. (see above for licensing)           
            inttypes.h  Copyright (C) 2006-2019 Free Software Foundation, Inc. (see above for licensing)               
                tr1/cinttypes   Copyright (C) 2006-2019 Free Software Foundation, Inc. (see above for licensing)

    - SD.h    Copyright (c) 2020, Paul Stoffregen, paul@pjrc.com (see above for licensing)               
        + Arduino.h   (see above)
        + SdFat.h   Copyright (c) 2011-2021 Bill Greiman
                    MIT License
                    Permission is hereby granted, free of charge, to any person obtaining a
                    copy of this software and associated documentation files (the "Software"),
                    to deal in the Software without restriction, including without limitation
                    the rights to use, copy, modify, merge, publish, distribute, sublicense,
                    and/or sell copies of the Software, and to permit persons to whom the
                    Software is furnished to do so, subject to the following conditions:
                    The above copyright notice and this permission notice shall be included
                    in all copies or substantial portions of the Software.
                    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
                    OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
                    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
                    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
                    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
                    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
                    DEALINGS IN THE SOFTWARE.                     
            common/SysCall.h    Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                stdint.h    (see above)    
                stddef.h    (see above)
                SdFatConfig.h   Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                    stdint.h    (see above)
                    avr/io.h    (see above)
                    Arduino.h   (see above)
                PrintBasic.h    Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
            SdCard/SdCard.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                SdioCard.h      Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                    SysCall.h   (see above)      
                        stdint.h    (see above)
                        stddef.h    (see above)
                        SdFatConfig.h   (see above)
                            stdint.h    (see above)
                            avr/io.h    Copyright (c) 2015 Paul Stoffregen <paul@pjrc.com> (see above for licensing)   
                                avr_emulation.h     Copyright (c) 2019 PJRC.COM, LLC. (see above for licensing)
                    SdCardInterface.h   Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                        common/FsBlockDeviceInterface.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            stdint.h    (see above)
                            stddef.h    (see above)
                        SdCardInfo.h    Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            common/SysCall.h    (see above)
                                stdint.h    (see above)
                                stddef.h    (see above)
                                SdFatConfig.h   (see above)
                SdSpiCard.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                    stddef.h    (see above)
                    common/SysCall.h    (see above)
                    SdCardInfo.h    (see above)
                    SdCardInterface.h   (see above)
                    SpiDriver/SdSpiDriver.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                        common/SysCall.h    (see above)
            ExFatLib/ExFatLib.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                ExFatVolume.h       Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                    ExFatFile.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                        limits.h    Copyright (C) 1992-2019 Free Software Foundation, Inc.
                                    This file is part of GCC. GCC is free software; you can redistribute
                                    it and/or modify it under the terms of the GNU General Public License
                                    as published by the Free Software Foundation; either version 3, or 
                                    (at your option) any later version.
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
                        string.h    Copyright (c) 2006 The NetBSD Foundation, Inc. All rights reserved.
                                    This code is derived from software contributed to The NetBSD Foundation
                                    by Christos Zoulas.
                                    Redistribution and use in source and binary forms, with or without
                                    modification, are permitted provided that the following conditions
                                    are met:
                                    1. Redistributions of source code must retain the above copyright
                                    notice, this list of conditions and the following disclaimer.
                                    2. Redistributions in binary form must reproduce the above copyright
                                    notice, this list of conditions and the following disclaimer in the
                                    documentation and/or other materials provided with the distribution.
                                    THIS SOFTWARE IS PROVIDED BY THE NETBSD FOUNDATION, INC. AND CONTRIBUTORS
                                    ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
                                    TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
                                    PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE FOUNDATION OR CONTRIBUTORS
                                    BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
                                    CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
                                    SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
                                    INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
                                    CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
                                    ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
                                    POSSIBILITY OF SUCH DAMAGE.
                        common/FsDateTime.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            stdint.h    (see above)
                            CompileDateTime.h   Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            SysCall.h   (see above)
                        common/FsApiConstants.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            SysCall.h   (see above)
                            fcntl.h     (??)
                        common/FmtNumber.h      Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            math.h  (see above)  
                            stdint.h    (see above)
                            stddef.h    (see above)
                        common/FsName.h     Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            SysCall.h   (see above)
                            stdint.h    (see above)
                        ExFatPartition.h    Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            SysCall.h   (see above)
                            common/FsBlockDevice.h  Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            common/FsCache.h        Copyright (c) 2011-2021 Bill Greiman (see above for licensing)
                            common/FsStructs.h      Copyright (c) 2011-2021 Bill Greiman   (see above for licensing)                    
                ExFatFormatter.h    Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                    common/FsBlockDevice.h  (see above)          
            FatLib/FatLib.h     Copyright (c) 2011-2022Bill Greiman (see above for licensing)
                FatVolume.h     Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                FatFormatter.h  Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
            FsLib/FsLib.h   Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                FsVolume.h  Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                    FsNew.h Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                        stddef.h    (see above)
                        stdint.h    (see above)
                    FatLib/FatLib.h (see above)
                    ExFatLib/ExFatLib.h (see above)     
                FsFile.h    Copyright (c) 2011-2024 Bill Greiman (see above for licensing)
                    FsNew.h         (see above)
                    FatLib/FatLib.h (see above)
                    ExFatLib/ExFatLib.h (see above)
                FsFormatter.h   Copyright (c) 2011-2022 Bill Greiman (see above for licensing)
                    FatLib/FatLib.h     (see above)
                    ExFatLib/ExFatLib.h (see above) 
            sdios.h (see above)
        + FS.h    Copyright (c) 2021 PJRC.COM, LLC. (see above for licensing)

    - SerialFlash.h   Copyright (C) 2015, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + Arduino.h   (see above)
        + SPI.h     Copyright (c) 2010 by Cristian Maglie <c.maglie@bug.st>
                    Copyright (c) 2014 by Paul Stoffregen <paul@pjrc.com> (Transaction API)
                    Copyright (c) 2014 by Matthijs Kooijman <matthijs@stdin.nl> (SPISettings AVR)
                    SPI Master library for arduino.
                    This file is free software; you can redistribute it and/or modify
                    it under the terms of either the GNU General Public License version 2
                    or the GNU Lesser General Public License version 2.1, both as
                    published by the Free Software Foundation.
            Arduino.h       (see above)
            DMAChannel.h    (see above)
            EventResponder.h    Copyright 2017 Paul Stoffregen (see above for licensing)

    - dspinst.h   Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com (see above for licensing)
        + stdint.h  (see above)
    
    -  MIDI.h  Copyright (c) 2015 Francois Best (see above for licensing)
        + midi_Defs.h         Copyright (c) 2015 Francois Best (see above for licensing)
        + midi_Platform.h     Copyright (c) 2015 Francois Best (see above for licensing)
        + midi_Settings.h     Copyright (c) 2015 Francois Best (see above for licensing)
        + midi_Message.h      Copyright (c) 2015 Francois Best (see above for licensing)
        + serialMIDI.h        Copyright (c) 2015 Francois Best (see above for licensing)
    
    - SPI.h   (see above)
    
    - Adafruit_GFX.h    Copyright (c) 2012 Adafruit Industries.  All rights reserved.
                        Redistribution and use in source and binary forms, with or without
                        modification, are permitted provided that the following conditions are met:
                        - Redistributions of source code must retain the above copyright notice,
                        this list of conditions and the following disclaimer.
                        - Redistributions in binary form must reproduce the above copyright notice,
                        this list of conditions and the following disclaimer in the documentation
                        and/or other materials provided with the distribution.
                        THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
                        AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
                        IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
                        ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
                        LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
                        CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
                        SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
                        INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
                        CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
                        ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
                        POSSIBILITY OF SUCH DAMAGE.

    - Adafruit_ILI9341.h    Copyright (c) 2012 Adafruit Industries.  All rights reserved.
                            BSD license, all text here must be included in any redistribution.

    - output_noiseshaped_pwm.h    Copyright (c) 2014, Paul Stoffregen, paul@pjrc.com  (see above for licensing)
        + Arduino.h       (see above)
        + AudioStream.h   (see above)
        + DMAChannel.h    (see above)
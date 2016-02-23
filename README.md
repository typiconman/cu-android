cu-android
=======

Church Slavic keyboard layouts for Android harware keyboards

This repository contains keyboard layouts for USB/Bluetooth keyboards
for Android devices

This software is part of the Ponomar Project's Slavonic Computing Initiative. See http://www.ponomar.net/cu_support.html for more information.

Copyright 2016 Aleksandr Andreev.
This software is part of the Ponomar Project.

Ponomar is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Ponomar is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Ponomar.  If not, see <http://www.gnu.org/licenses/>.

===
Note: because Android treats U+0300 and U+0301 (the grave and acute accents) 
as dead keys be default and since dead keys are not supported for Cyrillic,
you will not be able to use the accents placed on the 3 and 7 keys.
They have been placed there for compatibility with m17n-cu only.
To type the accents, you will need to enter the code 0301 (or 0300, respectively), then
type the ` (backtick) key, which acts as the Compose key.
The same method needs to be used to enter the characters placed in the SMP
since Android does not recognize Unicode codepoints beyond U+FFFF.
So, to enter the Typicon symbols, you need to type, e.g., 1f540 backtick (compose).

This is a very annoying problem, but has been built in to Android.


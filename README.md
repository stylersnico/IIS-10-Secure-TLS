Secure TLS config for IIS 10
============================

##License
Profiles for IISCrypto to get A or A+ grade on SSLLabs. Support for TLS 1.0 or 1.2.

Copyleft (C) Nicolas Simond - 2016

Theses profiles are free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Theses profiles are distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with theses profiles.  If not, see <http://www.gnu.org/licenses/gpl.txt>

##About this repository
Profiles for IISCrypto to get A or A+ grade on SSLLabs.

- Support for TLS 1.0, 1.1 and 1.2 to keep good compatibility
- Support for TLS 1.2 only to get A+ on SSLLabs.
- Templates for IISCrypto

##Dependencies
- Windows Server 2008r2 and above
- IIS 7.5  and above
- These are profiles for IIS Crypto (https://www.nartac.com/Products/IISCrypto)

##Designed on 

- Windows Server 2016 TC5
- IIS 10

##Installation

Download IIS Crypto and the wanted profile.

Apply the profile and reboot your server.

If you want the A+ grade you also need to setup HSTS headers:

```bash
Server: Microsoft-IIS/10.0
Strict-Transport-Security: max-age=15768000; includeSubDomains; preload
```

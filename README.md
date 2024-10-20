# PWDB - New generation of Password Mass-Analysis from 2024

![GitHub repo size](https://img.shields.io/github/repo-size/flameofignis/pwdb-public)
![GitHub](https://img.shields.io/github/license/flameofignis/pwdb-public)
![GitHub issues](https://img.shields.io/github/issues/flameofignis/pwdb-public)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/flameofignis/pwdb-public.svg)](http://isitmaintained.com/project/flameofignis/pwdb-public "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/flameofignis/pwdb-public.svg)](http://isitmaintained.com/project/flameofignis/pwdb-public "Percentage of issues still open")

---

## Mystery List of high entropy credentials
During my research, I observed several high-entropy passwords (10 characters, including uppercase, lowercase, and digits) being reused. Although the occurrence rates were quite low, they were still higher than I had anticipated

**Some noticable stuff about these:**
All of the passwords start and end with uppercase characters.
None of them follow a keyboard pattern or contain recognizable words.
Each password is exactly 10 characters long.
They do not include any special characters.
Some passwords appeared as frequently as 1 in 100 million credentials (I currently have about 10 instances of reuse).
The most recent occurrence: 86 of these passwords were found in a set of 35,673 credentials from a leak in June 2024.

I've filtered passwords which are 10 character long, and matches `(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=^[A-Z][A-Za-z0-9]+[A-Z]$)(?!.*[a-z]{3})(?!.*[A-Z]{3})` which had an occurrence rating of less than 1.4 per 100 million.

For now, I'm only releasing short lists of the top 200 passwords. I plan to release the full lists eventually but will hold off on sharing an incomplete version publicly at this time.

I will update these lists with every billion credentials I process. While some language-specific lists are still incomplete, they will be more refined soonn.

I've had enough data for 
* Ukranian 
* German 
* Russian
* Malaysian
* Italian 
* Japanese 
* Portugese 
* Polish 
* French
* Malaysian
* Indonesian
* Korean

### 38 passwords rockyou is missing that are ranked top 1000.
* 123hfjdk147
*1464688081
*159753qq
*2012comeer
*6V21wbgad
*<password>
*Bloat129
*D1lakiss
*Exigent
*Groupd2013
*Indya123
*N0=Acc3ss
*R9lw4j8khX
*Status
*F0ckCiMB!7
*Telechargement
*aobo2010
*baili123com
*bhf
*cme2012
*demon1q2w3e
*demon1q2w3e4r
*demon1q2w3e4r5t
*exigent
*g13916055158
*hg0209
*lincogo1
*lizottes
*megaparol12345
*minecraft
*nks230kjs82
*nonmember
*nyq28Giz1Z
*pk3x7w9W
*rr123456rr
*startfinding
*youbye123
*yuantuo2012



 

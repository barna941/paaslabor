# Alerant - BME PaaS labor 
# Gyakorlat 4. - Hálózat

## Tudnivalók
[Fontos információk](Tudnivalok.md)

**Fontos:**
- **Felhasználóneveket a gyakorlatvezető osztjka ki: student1, student2, student3, ..... student25** 
- Mindenki a saját userét használja ezután, hogy izoláltan dolgozzatok!


## Feladat 1. - OpenShift SDN hálózati forgalom mérése, External -> ... -> Alkalmazás
**Időtartam: ~30 perc**

### Célja, leírás
Ennek a feladatnak a célja, hogy feltérképezzétek a hálózati forgalmat az OpenShift SDN-en belül.

1. Telepíts egy tetszőleges olyan alkalmazást, amely HTTP forgalmat fogad, mindenképp legyen egy böngészőből megszólítható alkalmazásod a PaaS-ban.
2. A böngésződből az alkalmazás felé küldött HTTP kérés pontosan milyen hálózati eszközökön keresztül érkezik el az alkalmazáshoz?

http://www.opensourcerers.org/tag/openshift/   

_Hint: ifconfig, ip a, ip route get, mtr, brctl show, ovs_

### Jegyzőkönyvhöz
Az alábbi részletezettségig próbáljatok eljutni és ezt csatoljátok a jegyzőkönyvhöz:
böngésző -> CentOS7 gép, 10.0.2.15 enp0s3 -> 10.0.2.2 -> Host gép, -> ...... -> 


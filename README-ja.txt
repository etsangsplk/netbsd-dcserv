DCserv - NetBSD/dreamcast $B%/%i%$%"%s%H8~$1(B NFS $B%5!<%P!<%-%C%H(B


1. DCserv $B$C$F2?(B?

$B$3$N(B "DCserv" $B%$%a!<%8$O!"(BNetBSD/dreamcast $B$r%V!<%H$9$k$?$a$KI,MW$J(B
$B!V(BNFS $B>e$N%k!<%H%U%!%$%k%7%9%F%`!W$r4JC1$KMQ0U$G$-$k$h$&$K$7$?$b$N$G$9!#(B


2. DCserv $B%$%a!<%8$NFbMF(B

$B$3$N%$%a!<%8$K$O!"%V!<%H2DG=$J(B NetBSD/i386 $B%U%!%$%k%7%9%F%`%$%a!<%8$,4^$^$l$F$*$j!"(B
dhcpd(8), mountd(8), nfsd(8) $B$J$I$N%G!<%b%s$,<+F0E*$K5/F0$9$k$h$&$K$J$C$F$$$^$9!#(B
$B$^$?!"(BNetBSD/dreamcast $B%U%!%$%k%7%9%F%`$r(B NFS $B$G%(%/%9%]!<%H$9$k$h$&$K$J$C$F$*$j!"(B
$B$3$l$K$O(B X $B$N%5!<%P!<$H%/%i%$%"%s%H$r4^$`!"$9$Y$F$N%j%j!<%9%P%$%J%j!<$,4^$^$l$F$$$^$9!#(B


3. $BI,MW$J$b$N(B

- x86 $B%Y!<%9$N(B PC $B$G!"(BNIC $B$r;}$A!"(BUSB $B%G%P%$%9$+$i$N%V!<%H$,2DG=$J$b$N(B
- 10BASE-T $B%/%m%9%1!<%V%k(B ($B$^$?$O(B HUB)
- MIL-CD $B$KBP1~$7$?(B Dreamcast
- $B%V%m!<%I%P%s%I%"%@%W%?$^$?$O(B LAN $B%"%@%W%?(B
- Dreamcast $B%-!<%\!<%I(B
- Dreamcast $B%^%&%9(B ($BI,?\$G$O$"$j$^$;$s$,!"(BX $B%5!<%P!<$r;H$&>l9g$OI,MW$G$9(B)


4. DCserv $B$N;H$$J}(B

1) 2GB ($B0J>e(B) $B$N(B USB $B%U%i%C%7%e%a%b%j!<$K!"(B
    $B$3$N%$%a!<%8$r!"(Bgzip(1) $B$H(B dd(1) $B$r;H$C$F=q$-9~$_$^$9(B
   (Windows $BMQ$N(B Rawrite32.exe $B%D!<%k$b;H$($^$9(B)$B!#(B
    Rawrite32.exe $B%D!<%k$O0J2<$N%5%$%H$K$"$j$^$9(B:
    http://www.NetBSD.org/~martin/rawrite32/
2) USB $B%a%b%j!<$r(B x86 PC $B$KA^$7!"$=$3$+$i5/F0$7$^$9(B ($B5/F0J}K!$O%^%7%sKh$K0[$J$j$^$9(B)
3) Dreamcast $B$H(B x86 DCserv PC $B$r(B 10BASE-T $B%/%m%9%1!<%V%k$J$I$G@\B3$7$^$9!#(B
   $BCp(B: DCserv $B$OFH<+$N%"%I%l%9(B (10.0.0.xxx) $B$G(B dhcpd(8) $B$rF0$+$7$^$9$N$G!"(B
   $BB>$N%M%C%H%o!<%/$K$O@\B3$7$J$$$G$/$@$5$$!#(B
4) $B%V!<%H2DG=$J(B NetBSD/dreamcast CD-R $B$r=`Hw$7$^$9(B
   ($B>\:Y$OJL$NJ8=q$GD4$Y$F$/$@$5$$!#$^$?$O!"(B"DCburn" $B%D!<%k$N%$%a!<%8$r;H$($P0lH/$G$9(B)
5) NetBSD/dreamcast $B$r%V!<%H$7$F!"(B"root device:" $B%W%m%s%W%H$G(B "rtk0" 
   ($B%V%m!<%I%P%s%I%"%@%W%?$r;H$C$F$$$k>l9g(B) $B$^$?$O(B "mbe0" (LAN $B%"%@%W%?$r;H$C$F$$$k>l9g(B) $B$HF~NO$7$^$9(B
6) $B$=$N8e$N%W%m%s%W%H(B (dump device, file system, init path) $B$G$O!"(Benter $B$r2!$7$^$9(B
7) $B$f$C$/$j$7$F$$$C$F$M(B!


5. $B$=$NB>(B

20101113a $BHG$G$O!"(BNetBSD 5.1 $B$N%j%j!<%9%P%$%J%j!<$r;H$C$F$$$^$9!#(B
$B$?$@$7!"(Bdreamcast $BMQ$N(B xinit(1) $B%P%$%J%j!<$N$_$O!"(B
$B!V(BX $B%5!<%P!<$r=*N;$G$-$J$$!WLdBj$r2sHr$9$k$?$a$K!"=$@5HG$KCV$-49$($F$"$j$^$9!#(B

---
Izumi Tsutsui
tsutsui@NetBSD.org

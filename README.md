

                                      .*#%%%#*.
                                 .%@@@@@@@@@@@@@@@@@@@@@@@&.
                           (@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%
                        @@@@@@@@@@@@@@@#,       ,#@@@@@@@@@@@@@&@
                     (@@@@@@@@@@&                       %@@@@@@@@@@%
                                                                    
                  /@@@    @@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@@@@@#
                @@@@@@    @@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@@@@@@@@
             /@@@@@@@@    @@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
           &@@@@@@@@@     @@@@@@@    @@@@@@@   &@@@@@@.               @@@@@@@@@@
            (@@@@@@@@@#   @@@@@@@    @@@@@@@   &@@@@@@.             (@@@@@@@@&#
               @@@@@@@@@@ @@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@@@@@@&&.
                 (@@@@@@@@@@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@&/      
              @*    &@@@@@@@@@@@@    @@@@@@@   &@@@@@@@@@@@@@@@@@@@@@,     .@
              &@@&    (@@@@@@@@@@    @@@@@@@   &@@@@@@.   /@@@@@@@@@#    &@@@
              .@@@@@/    &@@@@@@@@&  @@@@@@@   &@@@@@@. @@@@@@@@@&    *@@@@@/
               &@@@@@@@    (@@@@@@@@@@@@@@@@   &@@@@@@@@@@@@@@@#    &@@@@@@@
                @@@@@@@@      @@@@@@@@@@@@@@   &@@@@@@@@@@@@@      &@@@@@@@
                 @@@@@@@&,      (@@@@@@@@@@@   &@@@@@@@@@@#       @@@@@@@@
                  (@@@@@@@@.       @@@@@@@@@   &@@@@@@@@        @@@@@@@@%
                     @@@@@@@@@&       (@@@@@@   &@@@@@#       %@@@@@@@@@
                      &@@@@@@@@@@*      @@@@   &@@@      .@@@@@@@@@@&
                        ,@@@@@@@@@@@@&    (@   &#    &@@@@@@@@@@@&/
                           .@@@@@@@@@@@@*         ,@@@@@@@@@@@&.
                               #@@@@@@@@@&     &@@@@@@@@@%
                                      ./%@@   @@%(,

                                                                                                                                                    
          ```     ```     ```     ```     ``````````    ``--.`   ```     ``   ````````  ````````                      ```````  
          :hh-   .yhh.   .hh-    ohhh:    yhhhhhhhhy` `+yhyyyy+ `yh+    :hh.  shhyyyys  /hhyyyys/`                   +hhyyyys: 
          `yho   +hhh+   +hs    :hy+hy.   ```-hh/``` .yhy-   ./ `yho    :hh.  shs       +hy`  /hh:                   +hy   +hh`
           :hh. `yh/hh. `hh-   `yh-`shs      -hh:    +hh.       `yhs::::+hh.  shy::::`  +hy-.-ohy.      .oyyo- .o:;  +hy::/yy/ 
           `yho +h+ sh+ /hs    oh+  .hh/     -hh:    shh`       `yhyssssyhh.  shy++++`  +hhsshho`       +y-.+yyys.   +hh+++shs-
            :hh-yh. :hh.yh-   :hhyyyyhhy.    -hh:    +hh:       `yho    :hh.  shs       +hy` -yh+            ```     +hy`  `yhy
            `shyho   shyhs   .yh/.....yhs`   -hh:    `ohho:-:/o `yho    :hh.  shs-----  +hy`  :hh/                   +hy:--+hh/
             -ooo.   -ooo.   :o+      -oo.   .oo-     `-+ossso:  +o:    .oo`  /oooooo+  :o+    /oo`                  :ooooo+/. 
                                                          ```                                                                  

# CFG RESOURCE/RAW 

Config ini dibuat dari berbagai config yang berbeda / beberapa sumber yang berbeda kemudian digabungkan menjadi sebuah kesatuan config, sumber-sumber yang saya gunakan adalah sebagai berikut :
- CFG From SSHKIT Generator/CONVERTER.
- Group Premi Howdy.id. 
- Github.
- Web forum diskusi.
- Dan Youtube.


# Created & Edited By WATCHER ~B.

t:@WatcherB 

Config ini masih dalam proses pembuatan dan masih belum sempurna, jadi masih akan tetap di perbaharui ke versi yang lebih baik.

# Fiture

- MENU "GLOBAL-A" = Sebagai global connection kepada apps & domain yang tidak memiliki rule.
- MENU "MANUAL" = Memilih proxy secara manual yang bisa digunakan untuk global connection pada proxy group "GLOBAL-A"
- MENU "BEST-PING" = Proxy group yang berfungsi untuk memilih ping terbaik dari proxy yang ada.
- MENU "LB!, LB2, LB3" = Proxy group yang menggunakan metode load-balance.

# Rules

- GAME
- WEB STREAMING
- SOSMED
- AD-BLOCK

#==================================================================

 Ket. rules :
- DIRECT :
           Koneksi langsung tanpa menggunakan inject. 
- MATCH ( GLOBAL ) : 
           koneksi yang di tentukan untuk ip/domain yang tidak memiliki rule tertentu (GLOBAL CONNECTION)
           lalu mereka akan menggunakan koneksi proxy yang dipilih berdasarkan metode pada proxy group GLOBAL-A.
- REJECT : 
           Menolak sebuah koneksi pada domain tersebut/ blacklist.
- GLOBAL-A,BEST-PING,LB1,LB2,LB3 : 
           Nama-nama group proxy yang koneksinya bisa digunakan sebagai rule untuk ip/domain tertentu.
# PREVIEW

<p align="center">
  <img src="https://github.com/00grezt/CLASH-CF_v7-FIX3/blob/main/PREVIEW.png" width="auto" title="CFG PREVIEW IMG 1">
  <img src="https://github.com/00grezt/CLASH-CF_v7-FIX3/blob/main/PREVIEW2.png" width="auto" title="CFG PREVIEW IMG 2">
  <h4 align="center"> Config Preview </h4>
</p>

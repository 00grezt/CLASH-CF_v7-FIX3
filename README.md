                                          .*#%%%#*.                                                                               
                                      .*#%%%#@@@@@@@@@@*.                                                                      
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


# RESOURCE/RAW 
CFG From SSHKIT Generator, Group Premi Howdy.id, github, web forum diskusi dan Youtube. 
Ini merupakan campuran Config dari beberapa sumber yang berbeda.
# Created & Edited By WATCHER ~B.
t:@WatcherB 


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

#=======================================================================================

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

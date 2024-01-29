# Fix-Kali-Linux-Update-Upgrade-Error



step-1: open Terminal and type -   a)  sudo su
                                   b) gedit /etc/apt/sources.list

step-2: Comment on previous text -  a) select all and press ->  shift + #
                                    b) copy and past ->    
                                                       
                                     deb https://http.kali.org/kali kali-rolling main non-free contrib

                                     deb https://http.kali.org/kali kali-last-snapshot main non-free contrib

                                     deb https://http.kali.org/kali kali-experimental main non-free contrib

step-3: enter - save

step-4: apt update -y && sudo apt full-upgrade -y

step-5: also remove previous packages when you are done with upgrading -  a) apt autoremove
